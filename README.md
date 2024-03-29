# Portfolio

<p align="center">
  <img src="capa_port.png" >
</p>

## Índice

- [Projetos](https://github.com/gabrielrflopes/Data-Science-Portfolio/tree/main#projetos)
- [Projetos de Estudos IBM](https://github.com/gabrielrflopes/Data-Science-Portfolio/tree/main#projetos-de-estudos-ibm)
- [Certificados](https://github.com/gabrielrflopes/Data-Science-Portfolio/tree/main#certificados)
- [Artigos](https://github.com/gabrielrflopes/Data-Science-Portfolio/tree/main#artigos-sobre-os-projetos)
- [Quem Sou Eu](https://github.com/gabrielrflopes/Data-Science-Portfolio/tree/main#gabriel-r-f-lopes)
- [Links Importantes](https://github.com/gabrielrflopes/Data-Science-Portfolio/tree/main#links-importantes)

## Projetos

### Análise Exploratória e Tratamento dos Dados

1. [**Analisando os Dados do AirBnb na Cidade de Roma**](https://github.com/gabrielrflopes/Rome_Airbnb_Data_Analysis): Neste projeto, utilizei os dados disponíveis no Inside AirBnb para fazer uma análise exploratória completa dos dados, identificando média de preços, tipos de imóveis mais comuns, média de noites, médias de preços por bairros e a distribuição geográfica de imóveis classificados por preço.
2. [**Panorama do COVID-19 no Brasil e no Mundo**](https://github.com/gabrielrflopes/covid_project): Nesse projeto, utilizei os dados fornecidos pelo *Our World in Data* para analisar o panorama do COVID no Brasil e no mundo. O foco foi em avaliar a evolução da pandemia, os países mais afetados e o efeito da vacinação sobre casos e mortes.

### Aprendizado Supervisionado e Otimização de Modelos

3. [**Detecção de Fraudes em Cartões de Crédito**](https://github.com/gabrielrflopes/credit_card_fraud_detection): Desenvolvi modelos supervisionados de Machine Learning que classificam transações fraudulentas e legítimas. Comparei os modelos de regressão logística e de árvore de decisão, visando soluções para problemas de negócios reais que empresas de cartões de crédito podem passar.
4. [**Machine Learning Aplicado à Previsão de Rotatividade**](https://github.com/gabrielrflopes/Churn_Prediction): Desenvolvi modelos de classificação para **previsão de Churn** de clientes  de uma empresa de telecomunicações a partir de dados históricos. Foram utilizadas técnicas de pré-processamento para codificação das variáveis categóricas, como LabelEncoder para variáveis binárias. Os treinamentos dos modelos foram feitos utilizando técnicas de **validação cruzada e GridSearchCV**, permitindo otimização de hiperparâmetros visando maximizar a métrica de recall, que se refere à previsão de Churn. Três modelos foram criados com diferentes graus de previsão, podendo se adequar às circunstâncias das empresas segundo as particularidades do problema de negócios em questão.

### Auto Machine Learning

5. [**AutoML aplicado à previsão de custos de seguros de saúde**](https://github.com/gabrielrflopes/Health_Insurance_Prediction): Modelos de regressão foram testados para a previsão de custos de seguros de saúde, baseados em atributos demográficos e relacionados a hábitos de vida dos clientes. Os modelos foram construídos e otimizados através de um pipeline de _Machine Learning_ integrado no PyCaret. Os modelos resultantes obtiveram ótimas métricas de generalização para novos exemplos, sendo o Bayesian Ridge o melhor dentre os testados, com R2 de 0,878 e RMSE de 4159.
6. [**Classificação de saúde fetal**](https://github.com/gabrielrflopes/Fetal_Health_Classification): Este projeto visou explorar dados do exame de CTG para análise de saúde fetal. A partir de pipelines de pré-processamento e ajuste de modelos, foram construídos classificadores para identificar casos graves a partir dos atributos do exame, visando maximizar a métrica *recall*. Numa primeira abordagem, foram construídos 5 modelos e, nos dados de teste, o que melhor performou foi o *Extra Trees* com *recall* de 97%. Na abordagem com **AutoML**, construiu-se um modelo de análise de discriminannte linear com *recall* de 94%.

### Séries Temporais

7. [**Previsão de Demanda de Vendas utilizando Séries Temporais**](https://github.com/gabrielrflopes/Wine_Demand_Prediction): Este projeto analisou os dados de 219 vinhos distintos e seus respectivos dados de venda ao longo de 3 anos. Com um conjunto de dados de mais de 700 mil entradas, construiu-se uma análise exploratória completa dos produtos, investigando quais possuem maior fluxo de vendas e quais convertem em maior receita. Assim, foi possível vislumbrar uma estratégia logística para o negócio. Da parte da previsão de demanda, utilizou-se o Prophet sobre dados históricos de vendas, construíndo um modelo de série temporal estacionária que obteve um erro absoluto médio (**MAE**) baixíssimo, de 0,74, e um **MAPE** abaixo de 10%. Foi possível prever, com um nível aceitável de incerteza, até um ano de vendas futuras.

## Projetos de Estudos IBM

### Regressão Línear e Regressão Múltipla

1. [**Previsão de Emissão de CO2 para Novos Carros Fabricados**](https://colab.research.google.com/drive/1YdhkPmyvPqyp-h94axbzrI5u8l7BmHTW?usp=sharing): Estudo de um conjunto de dados históricos sobre carros fabricados de diversas marcas, visando criar modelos de regressão linear, linear múltipla e polinomial para prever a emissão de CO2 de um novo carro.

### Classificação e Clustering

2. [**Previsão de Medicamentos com Classificação por Árvore de Decisão**](https://colab.research.google.com/drive/1Rp57ufNyUBFN1U95HVRlT-ektVqDpprk?usp=sharing): Estudo de dados sobre caractéristicas de pacientes, como colesterol e pressão arterial, visando criar um modelo de classificação de árvore de decisão que possa classificar corretamente qual o medicamento a ser prescrito.
3. [**Serviços de Telecomunicações com K-Nearest Neighbours**](https://colab.research.google.com/drive/1ezAn6Ikifn5Chg8ebb1XMEq1lPk3a4ie?usp=sharing): Estudo com dados históricos de uma empresa de telecomunicações visando criar um classificador baseado no algoritmo de KNN. O objetivo é direcionar grupos de clientes a serviços e estratégias de marketing adequados a cada perfil.
4. [**Previsão de Rotatividade com Regressão Logística**](https://colab.research.google.com/drive/1Hs75Uay1Jzn778zhcZQ6RW8IkV632nnG?usp=sharing): Estudo de previsão de rotatividade, criando um modelo de regressão logística para estimar os padrões envolvidos em clientes que rotacionam ou não.
5. [**Detecção de Tumores com SVM**](https://colab.research.google.com/drive/1GYX2X6bJC3Hfe4vuENFbED0sb43CPwC9?usp=sharing): Estudo com dados de centenas de células humanas, com o objetivo de criar um modelo baseado em máquinas de vetores de suporte capaz de classificar tumores benignos e malignos. Foi explorado as correlações das variáveis, e a construção do modelo passou por um processo de otimização via Grid Search.
6. [**Segmentação de Clientes com K-Means Clustering**](https://colab.research.google.com/drive/1CgVloU9GYzuOhJGPg2fsoQze41EVqwHR?usp=sharing): Estudo com dados históricos de clientes, baseando-se em atributos como educação, renda e dívidas, por exemplo. O objetivo consistiu de criar grupos de clientes com padrões de compras parecidos, através do algorítmo de clusterização K-Means. Com isto, é possível direcionar estratégias de marketing mais efetivas para cada grupo, economizando recursos para a empresa.

### Análise Exploratória
  
7. [**Análise dos Lançamentos do Foguete Falcon 9 da SpaceX**](https://colab.research.google.com/drive/1wBaDuSR0EfCIneDtiqLOgbKD6T-BJyAn?usp=sharing): Estudo que consiste da análise exploratória e visualização de dados, utilizando Matplotlib e Seaborn, dos lançamentos do foguete Falcon 9 da SpaceX.

#### Habilidades 

- Programação: **Python, SQL**
- Habilidades Técnicas: **Matemática Avançada, Probabilidade e Estatística, Física, Time Series, Metodologia Científica**
- Ferramentas: **Numpy, Pandas, Matplotlib, Seaborn, Scikit-learn, PyCaret, TensorFlow, Keras, LaTeX, DataBricks, AWS, Power BI**

#### Soft Skills 

- Pensamento Analítico; Escrita Científica; Oratória; Comunicação interpessoal; Organização.

#### Idiomas

- Inglês avançado (B2 - Excelente conversação, escrita e leitura)
- Espanhol básico (Entende bem, Lê bem)

## Certificados

- [IBM Machine Learning With Python](https://www.credly.com/badges/486f31f9-bf09-4757-b283-ca6468ef7f85/public_url)
- [IBM Data Analysis With Python](https://www.credly.com/badges/4ff462e1-6834-4a6b-856e-03e7b0047c7d/linked_in_profile)
- [IBM SQL and Relational Databases](https://courses.cognitiveclass.ai/certificates/dd8369f75490408db92608d9f2476678)
   
## Artigos Sobre os Projetos

* [Analisando os dados do AirBnb na cidade de Roma](https://grflopes.medium.com/analisando-os-dados-do-airbnb-na-cidade-de-roma-4ee6af13bbdc) 
* [Panorama do COVID-19 no Brasil e no mundo](https://medium.com/@grflopes/panorama-do-covid-19-no-brasil-e-no-mundo-a67cfb94af5f)
* [Aprendizado supervisionado aplicado à detecção de fraudes em cartões de crédito](https://grflopes.medium.com/aprendizado-supervisionado-aplicado-%C3%A0-detec%C3%A7%C3%A3o-de-fraudes-em-cart%C3%B5es-de-cr%C3%A9dito-d74501220ec2)
* [Machine Learning Aplicado à Previsão de Rotatividade](https://medium.com/@grflopes/machine-learning-aplicado-à-previsão-de-rotatividade-de-clientes-1d29c491ed3a)
* [Classificação de saúde fetal](https://grflopes.medium.com/machine-learning-aplicado-ao-diagnóstico-de-saúde-fetal-d470b4e321c1)
* [Previsão de demanda com séries temporais](https://medium.com/@grflopes/uma-maneira-de-prever-demanda-de-vendas-com-séries-temporais-970ad550b8e9)

## Artigos Sobre Data Science

* [Personal Branding](https://www.linkedin.com/pulse/urg%25C3%25AAncia-de-causar-uma-boa-impress%25C3%25A3o-gabriel-ribeiro-ferreira-lopes/?trackingId=EjBT1icNTLeqkPLBvieGOQ%3D%3D)
* [Decisões orientadas por dados](https://www.linkedin.com/pulse/alguns-fatos-incontest%C3%A1veis-sobre-decis%C3%A3o-orientada-gabriel/)
* [Como usar cada tipo de gráfico no contexto certo usando o Matplotlib](https://grflopes.medium.com/como-usar-cada-tipo-de-gr%C3%A1fico-no-contexto-certo-usando-o-matplotlib-c640bbcdfe79)
* [Criando interações com gráficos usando o iPyWidgets](https://medium.com/@grflopes/criando-intera%C3%A7%C3%B5es-com-gr%C3%A1ficos-usando-o-ipywidgets-49a83dad43ec)
* [O dicionário de conceitos fundamentais em Data Science](https://grflopes.medium.com/o-dicionário-de-conceitos-fundamentais-em-data-science-c818b04e3a2b)
* [Por que a otimização é importante no Machine Learning?](https://medium.com/@grflopes/por-que-a-otimiza%C3%A7%C3%A3o-%C3%A9-importante-no-machine-learning-53cd4ace03f)
* [Conceitos de Deep Learning para novos curiosos](https://medium.com/@grflopes/definições-de-deep-learning-para-novos-curiosos-0067a74e2cbf)

## Artigos Acadêmicos

**Área: Física da Matéria Condensada**

* [Photoconductivity effect in SnTe quantum well (Applied Physics Letters)](https://pubs.aip.org/aip/apl/article/119/3/032104/41763/Photoconductivity-effect-in-SnTe-quantum-well)
* [Weak antilocalization effect and multi-channel transport in SnTe quantum well (Applied Physics Letters)](https://pubs.aip.org/aip/apl/article/120/20/203102/2833593/Weak-antilocalization-effect-and-multi-channel)

## Gabriel R. F. Lopes

Bacharel e Mestre em Física pela Universidade Federal de Itajubá, referência mundial na área de exatas e engenharia. Possuo 6 anos de experiência com projetos de análise de dados, desde a condução de experimentos, coleta de dados, até o tratamento e visualização desses dados para apresentação. Trabalhei para transformar informação em conhecimento através da interpretação de variáveis e conceitos de física e matemática avançadas utilizando dados.

Na minha experiência acadêmica durante o Mestrado, coordenei e supervisionei experimentos, realizei a análise dos dados, construí modelos preditivos e testei hipóteses sobre o comportamento de semicondutores para aplicações em dispositivos eletrônicos. Da pesquisa, resultaram dois artigos publicadods na *Applied Physics Letters* com estudos inéditos.

Como cientista de dados, construo modelos preditivos baseados em aprendizado de máquina, utilizando das técnicas mais difundidas. Com amplo conhecimento das ferramentas do Python e suas bibliotecas essenciais, além da experiência com SQL, bancos de dados relacionais, Big Data e Cloud, sou  capaz de criar soluções visando soluções para problemas de negócios em diversos nichos.

Tenho experiência com modelos de aprendizado supervisionado e não-supervisionado, como regressão (linear, polinomial, bayesiana, lasso), classificação (regressão logística, decision trees, random forest, kNN, SVM), clustering (K-Means, DBSCAN), além de técnicas de Boosting de Gradiente, como XGBoost e LightGBM.

Busco apresentar meus códigos sempre de maneira organiza e bem documentada, seguindo os princípios do _data storytelling_ para melhorar o entendimento e hierarquização das informações. Nas minhas análises, busco seguir uma metodologia científica para tirar conclusões precisas e não-intuitivas.

## Links importantes:

* [LinkedIn](https://www.linkedin.com/in/gabrielrflopes/)
* [Medium](https://medium.com/@grflopes)
* [Instagram](https://www.instagram.com/gabrielr.lopes/)
