# Lista de Exercícios - Inteligência Artificial (PCS3438)

Este repositório contém os códigos criados para resolver as questões 1 a 4 da lista de exercícios.

Os códigos foram feitos em Python 3 através do Jupyter Notebook com o auxílio de módulos adicionais, como sklearn, pandas e numpy.

## Minhas respostas para as questões

### 1) Naive Bayes
**Holdout**
- Acurácia para a base de treino: 70,00%
- Acurácia para a base de teste: 68,61%

**Leave-One-Out**
- Acurácia média para a base de treino: 68,2000% +/- 0,0029%  (média +/- desv. pad. da média)
- Acurácia média para a base de teste: 64,2% +/- 1,5% (idem)

### 2) kNN (k = 10 neighbors)
**K-Fold (k = 10 folders)**
- Acurácia média para a base de teste: 83,40% +/- 0,88%

### 3) LASSO
**Leave-One-Out**
- RMSE médio para a base de treino: 19,22026 +/- 0,00047
- RMSE médio para a base de teste: 15,47 +/- 0,37

### 4) Decision Tree
**K-Fold (k = 10)**
- MAE médio para a base de treino: 0 +/- 0
- MAE médio para a base de teste: 43,057 +/- 0,083

### 5) Verdadeiro ou Falso
- (**V**) Quando ajustamos um modelo linear, geralmente supomos que os erros tem distribuição normal e
são independentes e identicamente distribuídos (i.i.d.).
- (**V**) Quando ajustamos um modelo de regressão, podemos utilizar os valores preditos e os resíduos do
modelo para avaliar se o modelo se adequa bem aos dados.
- (**V**) O coeficiente de determinação (r²) indica, em termos percentuais, quanto da variabilidade da
variável resposta é explicada pelas covariáveis do modelo.
- (**F**) Os modelos de regressão não são afetados por observações atípicas (outliers) e valores faltantes.
- (**V**) Considerando um modelo de regressão simples, temos que o coeficiente associado à covariável
representa o grau de inclinação da reta.
- (**V**) Para efetuar regressão com o algoritmo KNN, pode-se fazer uma votação simples dos valores dos 𝑘
vizinhos encontrados.
- (**V**) Para melhor desempenho da árvore de regressão, pode-se utilizar regressões lineares em suas folhas
para previsão do valor final.
- (**V**) No algoritmo Random Forest para regressão, o valor predito é obtido pela média dos valores
encontrados em cada árvore. 
