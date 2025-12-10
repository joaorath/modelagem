# modelagem
Projeto do segundo semestre de modelagem feito pelo João Vitor Rath. O projeto tende a analisar os dados de um banco do kaggle, contendo dados de jogadores da NBA desde 1950. 

fonte: https://www.kaggle.com/datasets/drgilermo/nba-players-stats?resource=download
Kaggle - drgilermo/nba-players-stats

DOWNLOAD: 
ir no link do kaggle ou pesquisar NBA Players stats since 1950 dentro do site e fazer o download 

Licença: Unknown
Projeto de Machine Learning – Predição de Indicadores NBA

Este projeto faz parte da avaliação da disciplina de Inteligência Artificial / Aprendizado de Máquina e tem como objetivo aplicar todo o ciclo de desenvolvimento de modelos de regressão e classificação usando Python e ferramentas modernas de análise de dados.

Análise Exploratória de Dados (EDA)

Limpeza e tratamento de ausências

Detecção de outliers

Visualizações (histogramas, boxplots, pairplots, heatmap de correlação)

Testes estatísticos (correlação, ANOVA, qui-quadrado)

Modelagem (IA)

Regressão Linear Simples

Regressão Linear Múltipla

Regressão Polinomial

Naive Bayes

Regressão Logística

Interpretação com statsmodels e pipelines com sklearn / pycaret

Avaliação dos Modelos

Regressão: MAE, RMSE, R²

Classificação: Accuracy, Precision, Recall, F1, AUC-ROC, Matriz de Confusão

Diagnóstico de resíduos, multicolinearidade (VIF), homocedasticidade

Otimização dos Modelos

Validação cruzada

Tuning com PyCaret (tune_model, compare_models)

GridSearchCV / RandomizedSearchCV

Comparações antes e depois do tuning

Relatório Final

Realizado dentro do Jupyter Notebook

Explicações em Markdown

Gráficos, tabelas, interpretações e conclusões

    Estrutura do Repositório
|-- data/
|   ├── Players.csv
|   ├── player_data.csv
|   └── Seasons_Stats.csv
|
|-- notebook/
|   └── main.ipynb
|
|-- requirements.txt
|-- README.md  ← (este arquivo)
|-- LICENSE

    Descrição do Dataset

O dataset utilizado contém informações de jogadores da NBA ao longo da história, incluindo estatísticas individuais por temporada, dados demográficos e atributos avançados.

Variável-alvo (regressão):

MVP_score (criada como proxy de performance do jogador)

Variável-alvo (classificação):

Classificação binária definida com base em critérios estatísticos (ex.: acima/abaixo da média da liga)

Fonte dos dados:

<ins>Substitua aqui pelo link oficial do dataset escolhido</ins>
Exemplos: Kaggle, Basketball Reference (via scraping/compilação), repositórios públicos etc.

Licença do dataset:

<ins>Inserir licença do dataset aqui (CC BY, GPL, domínio público, etc.)</ins>

    Tecnologias Utilizadas
Linguagem

Python 3.x

Bibliotecas obrigatórias utilizadas

pandas

numpy

seaborn

matplotlib

statsmodels

sklearn

pycaret

Outras ferramentas úteis

unidecode

jupyter

    Metodologia
1. EDA e Preparação dos Dados

Limpeza e padronização de nomes com Unidecode

Tratamento de NaN

Detecção e análise de outliers

Visualizações exploratórias

Criação do MVP_score, variáveis derivadas e normalizações

2. Modelagem

Regressão Linear Simples (statsmodels)

Regressão Linear Múltipla (statsmodels + sklearn)

Regressão Polinomial

Naive Bayes (GaussianNB)

Regressão Logística

Divisão Train/Validation/Test

3. Avaliação

Métricas quantitativas

Análise dos resíduos

VIF para multicolinearidade

Matriz de confusão e ROC

4. Otimização

Cross-Validation (sklearn & pycaret)

GridSearchCV

RandomizedSearchCV

PyCaret (compare_models, tune_model)

    Como Executar o Projeto
1. Clone o repositório
git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
cd SEU_REPOSITORIO

2. Instale as dependências
pip install -r requirements.txt

3. Execute o Jupyter Notebook
jupyter notebook

4. Abra o arquivo
/notebook/main.ipynb

 Resultados Esperados

Comparação quantitativa entre diferentes algoritmos

Interpretação estatística dos modelos

Demonstração de melhoria via tuning

Gráficos de apoio e diagnóstico

Discussão sobre limitações e possíveis vieses

 Próximos Passos

Implementar modelos adicionais (Random Forest, XGBoost)

Normalização/Padronização mais avançada

Experimentar feature engineering mais elaborado

Refinar métricas personalizadas para avaliação de performance
