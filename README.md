# Projetos - RBAC
### Neste repositorio temos todos os principais projetos que realizei ao longo do meu curso de Data Science na EBAC
### Aqui poderemos encontrar projetos mais simples desde estatistica basica ate de modelo avancados
***
## Modulo 13 - Estatistica

#### Sobre o projeto

Aqui aplicamos fundamentos de estatisticas e tiraremos nossos insights através deles. Usaremos metricas como media, mediana, moda e desvio padrao para idenficar outliers e analisar se existe alguma tendência. Tambem e claro plotaremos alguns graficos para nos auxiliar, visualizar e tambem treinar plotagem dos graficos. Nesse projeto trabalharemos com a base de dados de produtos de um supermercado do Chile.

#### Ferramentas

Usamos as bibliotecas 
Pandas : para manipulacao de dado
Numpy : para calculos matematicos e estatisticos
Matplotlib e Seaborn : Para plotagem dos graficos

*** 
# Modulo 17 - Pre-Modelagem

#### Sobre o projeto

O processamento de dados e uma das etapas mais importantes pois ela precede o modelo de machine learning podendo prejudicar ou melhorar diretamente o modelo. Aqui usaremos tecnicas como identificacao de valore unicos, nulos e duplicados e consequentemente identificando qual melhor operacao para o tratamento deles, alem disso faremos o balanceamento de dados e no final separaremos entre a base de treino e teste. Usaremos aqui uma base de score de credito.

#### Ferramentas

Usamos as bibliotecas :
Pandas : para manipulacao de dado
Matplotlib e Seaborn : Para plotagem dos graficos
LabelEncoder : Tratamento de dados categoricos
train_test_split : Separarar dados de treino e teste
SMOTE : Balanceamento de dados

*** 
# Modulo 21 - Primeiros modelos

#### Sobre o projeto

No módulo 17, realizamos a primeira etapa do projeto de crédito. Então fizemos o tratamento dos dados, balanceamento das classes, transformacao das variáveis categóricas e separacao base de treino e teste. Posteriormente em outro modulo fizmos uma atividade para, aplicar a base já tratada o algoritmo de Naive Bayes, onde avaliaram os resultados das previsões. Nesse módulo aplicaremos a nossa base o algoritmo da árvore de decisão.

#### Ferramentas

Usamos as bibliotecas :
Pandas : para manipulacao de dado
Matplotlib : Para plotagem dos graficos
LabelEncoder : Tratamento de dados categoricos
SMOTE : Balanceamento de dados
Sklearn.metrics : Para metricas de avaliacao
Sklearn.tree : Para o duelo dos modelos de arvore de decisao

*** 
# Modulo 26 - Operacoes com SQL

#### Sobre o Projeto

Dessa vez utilizamos python para executar SQL dentro do jupiter nootebook e tambem fizems um deashboard interatvo, aqui fizeremos algumas etapas. Tratamento de Dados: Realizar a junção (JOIN) de duas tabelas utilizando SQL para consolidar as informações. Análise de Dados: Exportar os dados resultantes para um arquivo CSV. Visualização de Dados: Desenvolver um dashboard interativo e informativo para visualização das principais métricas e insights do e-commerce.


#### Ferramentas
Usamos as bibliotecas :
Pandas : para exportar o dataset
sqlite3 : para executar SQL e manipular o dataframe

Usamos o software :
PowerBI : Para fazer o dashboard

***
# Modulo 33 - Modelos Avancados

#### Sobre o Projeto
Nesta tarefa, exploraramos o algoritmo de clustering K-means aplicado a um contexto diferente do usual. Em vez de segmentar perfis de viajantes ou clientes de e-commerce, vamos usar dados biológicos para segmentar diferentes espécies de pinguins com base em características físicas. Esta abordagem destaca a versatilidade do K-means para diversas áreas além de vendas e marketing. A base de dados utilizada é a penguins do pacote seaborn, que contém informações sobre três espécies de pinguins: Adelie, Chinstrap e Gentoo. As variáveis disponíveis incluem medições físicas dos pinguins coletadas na Antártica.

#### Ferramentas 
Usamos as bibliotecas :
Pandas : para manipulacao de dado
Ploty.express e seaborn : Para plotagem dos graficos
sklearn.preprocessing : Para padronizacao dos dados
Sklearn.cluster : Para implementacao do modelo

****
# Projeto final do curso

#### Sobre o projeto

Aqui pude escolher entre 3 data sets para aplicar todo meu conhecimento adquirido durante minha longa jornada. Por ja ter familiaridade, escolhi o data set do jogo League Of legends no qual tinha o principal objetivo entender quais sao as principais causas de vitoria e prever a probabilidade de ganhar de um time com base nelas.

#### Ferramentas
Usamos as bibliotecas :
Pandas : para manipulacao de dado
Matplotlib e seaborn : Para plotagem dos graficos
sklearn.model_selection : separacao de treino e teste
sklearn.ensemble : importar a arvore de decisao
Sklearn.metrics : Para avaliacao de metricas
Xgboost : Melhoramento do modelo
sklearn.model_selection : Para o pos modelo
