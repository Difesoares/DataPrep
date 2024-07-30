# DataPrep

# Preparação dos Dados - Projeto relacionado a base de Churn utilizada no repositório de feature engineering

Neste notebook a ideia é apresentar o processo de preparação dos dados ( DataPrep ) para algorítmos de Machine Learning. Os dados foram separados entre treino e teste, mas apenas foi utilizado o conjuto de treino.

A preparação consiste em : 

1 - Análise de Metadados:
Com o metadados conseguimos ver o tipo de cada variável, a quantidade e a percentagem de nulos e a cardinalidade.

2 - Tratamento de nulos: 
As variáveis que apresentam mais de 70% de nulos foram excluidas. Para as variáveis com menos de 70% de nulos preenchi com a média dos valores existentes. 

3 - Normalização / Padronização:
Utilizei a padronização, pois é uma técnica que favorece quando uma distribuição for normal. E também não prejudica o algoritmo quando não for uma distribuição normal.

4 - OneHot / Label Encoding:
São técnicas de transformação usada para converter variáveis categoricas em um formato que pode ser fornecido aos algoritmos de aprendizado de máquina. 




