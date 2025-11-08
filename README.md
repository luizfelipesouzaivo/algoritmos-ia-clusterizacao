# Algoritmos de IA para Clusterização – Projeto INFNET

Este projeto foi desenvolvido como entrega final da disciplina “Algoritmos de Inteligência Artificial para Clusterização” no Instituto INFNET, com o objetivo de aplicar técnicas de aprendizado não supervisionado para agrupar países segundo indicadores socioeconômicos e de saúde.

# Objetivo do Projeto

O trabalho consiste em aplicar algoritmos de clusterização (K-Means e Clusterização Hierárquica) para identificar grupos de países com características semelhantes, utilizando a base de dados do Kaggle:

https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data

# Ambiente e Infraestrutura

O projeto foi desenvolvido em:

* Python: 3.12.12
* Ambiente virtual: Anaconda
* IDE: Jupyter Notebook (rodando localmente)
 
Bibliotecas principais:
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

# Etapas do Projeto
Parte 1 – Infraestrutura
* Configuração do ambiente virtual (Anaconda)
* Geração do arquivo requirements.txt
* Execução do notebook em ambiente local
* Prova do ambiente funcionando (print incluído no relatório)

Parte 2 – Base de Dados e Análise Exploratória
* Dataset com 167 países
* Análise de variáveis: mortalidade infantil, exportações, saúde, importações, renda, inflação, expectativa de vida, fertilidade e PIB per capita
* Visualizações: histogramas, boxplots e scatterplots
* Identificação de outliers e decisão por padronização dos dados com StandardScaler

Parte 3 – Clusterização

🔹 K-Means
Definição de 3 clusters
Interpretação dos grupos:
Cluster 0 – Intermediário: países com indicadores médios
Cluster 1 – Desenvolvido: alta renda, baixa mortalidade infantil e alta expectativa de vida
Cluster 2 – Subdesenvolvido: baixa renda, alta mortalidade infantil e baixa expectativa de vida

🔹 Clusterização Hierárquica
Método: Ward linkage
Visualização via dendrograma
Resultados comparados com o K-Means, apresentando padrões semelhantes de agrupamento

Parte 4 – Teoria e Comparações
* Etapas do algoritmo K-Means detalhadas
* Versão adaptada para uso de medóides (representando o ponto real mais próximo do centróide)

Discussão teórica:
* Sensibilidade do K-Means a outliers
* Robustez do DBScan a ruídos e valores extremos

# Autor
Luiz Felipe Souza Ivo - Instituto INFNET
