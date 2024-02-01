# Data Money

## A empresa Data Money

A empresa Data Money fornece serviços de consultoria de Análise e Ciência de Dados para grandes
empresas no Brasil e no exterior.

O seu principal diferencial de mercado em relação aos concorrentes é o alto retorno financeiro para as
empresas clientes, graças a performance de seus algoritmos de Machine Learning.

A Data Money acredita que a expertise no treinamento e ajuste fino dos algoritmos, feito pelos Cientistas de Dados da empresa, é a principal motivo dos ótimos resultados que as consultorias vem entregando aos seus clientes.

Para continuar crescendo a expertise do time, os Cientistas de Dados acreditam que é extremamente
importante realizar ensaios nos algoritmos de Machine Learning para adquirir uma experiência cada vez
maior sobre o seu funcionamento e em quais cenários as performances são máximas e mínimas, para que a
escolha do algoritmo para cada situação seja a mais correta possível.

Como Cientista de Dados recém contratado pela empresa, a sua principal tarefa será realizar 3 ensaios comalgoritmos de Classificação, Regressão e Clusterização, a fim de extrair aprendizados sobre o seu
funcionamento em determinados cenário e conseguir transmitir esse conhecimento para o restante do time.

## O Ensaio de Machine Learning

O ensaio de Machine Learning ajuda os Cientistas de Dados a ganhar mais experiência na aplicação dos
algoritmos. Nesse ensaio, em específico, cada algoritmo será treinado com os dados de treinamento e
sua performance será medida usando 3 conjuntos de dados:

1. Os próprios dados de treinamento
2. Os dados de validação
3. Os dados de teste.

A performance de cada algoritmo será medida, utilizando diferentes métricas de performance.

## Os algoritmos e métricas do ensaio

### Classificação
- Algoritmos: K-Nearest Neighbors, Decision Tree, Logistic Regression e Random Forest;
- Métricas de Performance: Accuracy, Precision, Recall, F1 Score.

### Regressão
- Algoritmos: Decision Tree Regressor, Random Forest Regressor, Linear Regression, Linear Regression Lasso, Linear Regression Ridge, Linear Regression Elastic Net, Polynomial Regression, Polynomial - Regression Lasso, Polynomial Regression Ridge e Polynomial Regression Elastic Net;
Métricas de Performance: R-Quadrado, MSE, RMSE, MAE, MAPE.

### Clusterização
- Algoritmos: K-Means, Affinity Propagation;
- Métricas de Performance: Silhouette Score.

## Resultados Obtidos

### Classificação

- Treino

| **Model**               | **Accuracy** | **Precision** | **Recall** | **F1 Score** |
|-------------------------|:------------:|:-------------:|:----------:|:------------:|
| **KNN**                 | 0.782        | 0.756         | 0.733      | 0.744        |
| **Decision Tree**       | 1.0          | 1.0           | 1.0        | 1.0          |
| **Random Forest**       | 1.0          | 1.0           | 1.0        | 1.0          |
| **Logistic Regression** | 0.567        | 0.0           | 0.0        | 0.0          |

- Validação

| **Model**               | **Accuracy** | **Precision** | **Recall** | **F1 Score** |
|-------------------------|:------------:|:-------------:|:----------:|:------------:|
| **KNN**                 | 0.676        | 0.632         | 0.603      | 0.617        |
| **Decision Tree**       | 0.945        | 0.935         | 0.938      | 0.936        |
| **Random Forest**       | 0.965        | 0.974         | 0.944      | 0.959        |
| **Logistic Regression** | 0.567        | 0.0           | 0.0        | 0.0          |

- Teste

| **Model**               | **Accuracy** | **Precision** | **Recall** | **F1 Score** |
|-------------------------|:------------:|:-------------:|:----------:|:------------:|
| **KNN**                 | 0.681        | 0.675         | 0.525      | 0.591        |
| **Decision Tree**       | 0.955        | 0.954         | 0.944      | 0.949        |
| **Random Forest**       | 0.965        | 0.974         | 0.946      | 0.960        |
| **Logistic Regression** | 0.872        | 0.868         | 0.835      | 0.851        |


### Regressão

- Treino

| **Model**                              | **R-Squared** | **MSE** | **RMSE** | **MAE** | **MAPE** |
|----------------------------------------|:-------------:|:-------:|:--------:|:-------:|:--------:|
| **Linear Regression**                  | 0.046         | 455.996 | 21.354   | 16.998  | 8.653    |
| **Decision Tree - Regressor**          | 0.992         | 3.940   | 1.985    | 0.214   | 0.083    |
| **Random Forest Regressor**            | 0.903         | 46.332  | 6.807    | 4.862   | 2.602    |
| **Polynomial Regression**              | 0.094         | 432.986 | 20.808   | 16.458  | 8.351    |
| **Linear Regression - Lasso**          | 0.007         | 474.475 | 21.782   | 17.305  | 8.737    |
| **Linear Regression - Ridge**          | 0.046         | 455.996 | 21.354   | 16.998  | 8.653    |
| **Linear Regression - ElasticNet**     | 0.008         | 474.269 | 21.778   | 17.300  | 8.732    |
| **Polynomial Regression - Lasso**      | 0.009         | 473.639 | 21.763   | 17.285  | 8.700    |
| **Polynomial Regression - Ridge**      | 0.093         | 433.475 | 20.820   | 16.472  | 8.373    |
| **Polynomial Regression - ElasticNet** | 0.013         | 471.878 | 21.723   | 17.244  | 8.679    |

- Validação

| **Model**                              | **R-Squared** | **MSE** | **RMSE** | **MAE** | **MAPE** |
|----------------------------------------|:-------------:|:-------:|:--------:|:-------:|:--------:|
| **Linear Regression**                  | 0.040         | 458.447 | 21.411   | 17.040  | 8.683    |
| **Decision Tree - Regressor**          | -0.293        | 617.528 | 24.850   | 17.141  | 6.880    |
| **Random Forest Regressor**            | 0.332         | 318.793 | 17.855   | 13.017  | 7.046    |
| **Polynomial Regression**              | 0.066         | 445.768 | 21.113   | 16.750  | 8.548    |
| **Linear Regression - Lasso**          | 0.008         | 473.747 | 21.766   | 17.265  | 8.696    |
| **Linear Regression - Ridge**          | 0.040         | 458.445 | 21.411   | 17.039  | 8.682    |
| **Linear Regression - ElasticNet**     | 0.008         | 473.636 | 21.763   | 17.263  | 8.694    |
| **Polynomial Regression - Lasso**      | 0.010         | 472.913 | 21.747   | 17.238  | 8.682    |
| **Polynomial Regression - Ridge**      | 0.068         | 445.184 | 21.099   | 16.739  | 8.569    |
| **Polynomial Regression - ElasticNet** | 0.013         | 471.408 | 21.712   | 17.200  | 8.675    |

- Teste

| **Model**                              | **R-Squared** | **MSE** | **RMSE** | **MAE** | **MAPE** |
|----------------------------------------|:-------------:|:-------:|:--------:|:-------:|:--------:|
| **Linear Regression**                  | 0.051         | 461.988 | 21.494   | 17.144  | 8.531    |
| **Decision Tree - Regressor**          | -0.15         | 560.107 | 23.667   | 15.695  | 6.091    |
| **Random Forest Regressor**            | 0.342         | 320.237 | 17.895   | 13.178  | 6.533    |
| **Polynomial Regression**              | 0.091         | 442.641 | 21.039   | 16.736  | 8.277    |
| **Linear Regression - Lasso**          | 0.051         | 461.988 | 21.494   | 17.144  | 8.531    |
| **Linear Regression - Ridge**          | 0.051         | 462.243 | 21.500   | 17.142  | 8.553    |
| **Linear Regression - ElasticNet**     | 0.051         | 461.988 | 21.494   | 17.144  | 8.531    |
| **Polynomial Regression - Lasso**      | 0.091         | 442.674 | 21.400   | 16.734  | 8.288    |
| **Polynomial Regression - Ridge**      | 0.090         | 442.967 | 21.047   | 16.742  | 8.309    |
| **Polynomial Regression - ElasticNet** | 0.091         | 442.674 | 21.400   | 16.734  | 8.288    |


### Clusterização

| **Model**                | **N Clusters** | **Average Silhouette Score** |
|--------------------------|:--------------:|:----------------------------:|
| **K-Means**              | 3              | 0.233                        |
| **Affinity Propagation** | 3              | 0.215                        |