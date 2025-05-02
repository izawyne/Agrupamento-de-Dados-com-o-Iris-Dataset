# Agrupamento-de-Dados-com-o-Iris-Dataset
Este projeto tem como objetivo aplicar técnicas de aprendizado não supervisionado, utilizando o algoritmo KMeans++, para realizar a clusterização das amostras de flores do conjunto de dados Iris.

Embora o Iris Flower Dataset seja amplamente utilizado em problemas de classificação supervisionada, no qual contém rótulos de espécie para cada amostra, neste projeto ele será explorado de uma forma diferente: como um problema de aprendizado não supervisionado.

# Objetivo
O objetivo deste projeto é utilizar o algoritmo KMeans++ para identificar padrões e segmentar as flores Iris em clusters distintos, sem a necessidade de rótulos pré-definidos. O modelo será avaliado comparando os agrupamentos obtidos com os rótulos reais, para verificar a eficácia da clusterização.

# Descrição do Conjunto de Dados
* O Iris Flower Dataset contém informações sobre três espécies de flores (Setosa, Versicolor e Virginica), com os seguintes atributos:

* Sepal Length (Comprimento da Sépala)

* Sepal Width (Largura da Sépala)

* Petal Length (Comprimento da Pétala)

* Petal Width (Largura da Pétala)

* Species (Espécie da flor)

# Bibliotecas Utilizadas
* Pandas: Manipulação de dados.

* NumPy: Cálculos numéricos.

* Matplotlib: Visualização de dados.

* Seaborn: Visualizações estatísticas.

* Scikit-learn: Implementação do algoritmo KMeans++ e métricas de avaliação.

# Resultados
Após a execução, o modelo gera uma visualização gráfica dos clusters formados, com as flores agrupadas conforme as características morfológicas. A precisão da segmentação foi de 88%, indicando uma boa correspondência entre os clusters e as espécies reais.

# Conclusão
O modelo de KMeans obteve um desempenho satisfatório, agrupando as flores de forma coerente com as espécies reais. Embora a acurácia não tenha sido perfeita, o resultado indica que o algoritmo conseguiu identificar padrões naturais nas amostras de flores.
