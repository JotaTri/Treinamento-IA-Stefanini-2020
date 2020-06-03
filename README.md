Este repositório contém os *notebooks* criados para a execução das tarefas do **Treinamento de Inteligência Artificial** da **Stefanini**. A seguir, é apresentado um resumo sobre o que cada *notebook* deste respositório contém. Para acessar seu conteúdo, é possível visualizá-los pelo próprio **GitHub**, clicando no arquivo de interesse.

## 01 - Aprendizado Supervisionado e Nao Supervisionado
Atividade referente a introdução sobre os tipos de aprendizados de máquina **Supervisionados** e **Não Supervisionados**. Esse *Notebook* representa uma atividade em que se desejava escolher dois *datasets* sendo que um é um bom candidato para o tipo de aprendizado **Supervisionado** e outro para o tipo **Não Supervisionado** com uma exploração dos próprios *datasets* para justificar a escolha.

## 02 - Aula DataScience
Atividade com objetivo de apresentação de dados a partir de um dataset. Para ela, foi realizado uma análise temporal de velocidade e direção de ventos em uma região, com um gráfico que possui um slider que permite a visualização pontual de de um vetor de velocidade apontando para a direção correta do vento nesse momento.

## 03 - Regressão Logística
Atividade com objetivo de construir um modelo de **Regressão Logística** a partir de um dataset e com a construção de um **perceptron**, treinando seus parâmetros a partir da retro-alimentação sequencial do gradiente de **erro** e de **viés** calculados em cada interação.

## 04 - Machine Learning
Atividade com objetivo de construção e comparação de vários **modelos** de **Aprendizado de Máquina** para classificação de Fake News. Nele, foram comparados os modelos Random Forest, K Means, Naive Bayes, Decision Tree e Regressão Logística.

## 05 - Long Short-term Memory com TensorFlow
Atividade em que se utilizou do **TensorFlow** para construção de uma **Rede Neural** com **LSTM** em um dataset que contém dados metereológicos e o ano em que as medidas foram extraídas. O modelo proposto teve como objetivo determinar o ano da medida a partir das métricas com o **Long Short-term Memory** **RNN**.

## 06 - Atividade Data Science
Atividade que teve como objetivo principal a análise prévia de um dataset com erros para a construção de um modelo de forma automática. O dataset contem fotos e deveria ser construído um classificador **gatos - não gatos**. O dataset inicial estava separado em dois conjuntos com propriedades diferentes e fotos editadas, e memes. Identificou-se os **outliers** de forma automática a partir da análise do **Zscore**, extraiu-se informações sobre as imagens e aplicou-se em um **Random Forest Classifier**.

## 07 - Atividade de NLP
Atividade de **Processamento de Linguagem Natural** para **análise de sentimento** para um dataset de reviews de filmes. Extraiu-se informações a partir da análise dos tipos de palavras utilizadas, sua semântica, peso de expressões, oderm/posicionamento e tamanho médio de palavras para aplicação em três modelos: Random Forest Classifier, Regressão Logística e a criação de uma Rede Neural Profunda.

## 08 - Atividade de Reinforcement Learning
Atividade de **Aprendizado por Reforço** em que se construiu um modelo com **Q-Table** e construiu-se todo o **ambiente** para o problema proposto. O problema é composto por um rato que deve passar por um 'mapa' de 6 espaços pegando a maior quantidade de queijos sem passar por nenhuma casa com veneno.

## 09 - Atividade CNN - Deep Learning
Atividade de **Rede Neural Convolucional** para classificação de um dataset de fotos do **CIFAR-10**, que contém 10 classes. O objetivo dessa atividade foi utilizar as camadas mais rasas de uma Rede Neural **já treinada**, utilizando-se, portanto, de **Transfer Learning**. A Rede Neural utilizada foi a **VGG16**