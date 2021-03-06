Projeto 2 - Ciência dos Dados - INSPER
Grupo: Antônio Amaral Egydio Martins e Arthur Martins de Souza Barreto

História Hipotética:
No final do ano de 2012 a grande rede de supermercados Walmart entrou em contato com a empresa Antônio e Arthur consultorias afins de fazer predições das vendas semanais que a rede teria no futuro, e gostaria que o projeto desenvolvido obtivesse três diferentes modelos matemáticos para poder comparar taxas de erro, variações e constância de cada um.

A base de dados usada no trabalho pode ser encontrada no link a baixo:
https://www.kaggle.com/rutuspatel/walmart-dataset-retail

A partir disso com o uso das bibliotecas:

- os
- pandas
- numpy
- matplotlib.pyplot
- sklearn
- scipy

a empresa de consultoria início um projeto que têm como objetivo principal predizer - com o uso de regressão linear, DecisionTreeRegressor e RandomForestRegressor - como o comportamento de variaveis secundarias, Features - Temperatura, Preço Combustivo, Inflação e Taxa de desemprego - podem influenciar diretamente no crescimento/decrescimento de uma variável principal target, Vendas Semanais.

Separação de trabalho:
O trabalho foi, em grande parte, feito de forma conjunta com ambos os membros presentes na facção de gráficos, análises e modelos. Dentre as partes feitas em colaboração estão:

- Análise Exploratória - Construção de gráficos, formas de visualização e análises.
- Construção da Base de Dados - limpeza de variáveis que não foram utilizadas, separação da base de dados por semanas - que detém todas as lojas - correlação de termos.
- Apresentação, explicação e aprofundamento da biblioteca Scikit-Learn
- Explicação textual de Decision Tree Regressor (Modelo 2)
- Explicação textual de Random Forest Regressor (Modelo 3)
- Construção do Modelo, incluindo, Dados de treinamento e teste, Regressão Linear, Decision Tree Regressor, Random Forest Regressor, explicação textual de r², rms e Explained Variance Score.
- Conclusão e Referências

- Arthur Barreto: Explicação textual de Machine Learning, explicação textual de Validação cruzada, explicação textual de Explained variance score, Gráficos de Validação cruzada.

- Antônio Martins: Funções: lista_datas, correlacao, dados_grafico_holiday_flag_data, dados_grafico_hf, variavel_baixa, explicação textual de Data Mining, gráficos de projeção 3D, gráficos de sobreposição, gráficos de importância relativa.

Referências:

https://scikit-learn.org/stable/modules/linear_model.html

https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html

https://medium.com/pursuitnotes/decision-tree-regression-in-6-steps-with-python-1a1c5aa2ee16

https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html

https://ensinandomaquinasblog.wordpress.com/2017/12/15/modelos-preditivos-de-notas-de-redacao-do-enem-2015/

https://scikit-learn.org/stable/modules/tree.html

https://scikit-learn.org/stable/auto_examples/tree/plot_tree_regression.html

https://pt.wikipedia.org/wiki/Walmart

https://www.geeksforgeeks.org/ml-linear-regression/

https://www.mathworks.com/discovery/machine-learning.html

https://pt.wikipedia.org/wiki/Aprendizado_de_máquina

https://didatica.tech/a-biblioteca-scikit-learn-pyhton-para-machine-learning/

https://www.ibm.com/br-pt/analytics/machine-learning

https://scikit-learn.org/stable/modules/cross_validation.html

https://levelup.gitconnected.com/random-forest-regression-209c0f354c84

https://scikit-learn.org/stable/modules/model_evaluation.html

https://pt.wikipedia.org/wiki/Erro_quadrático_médio

https://en.wikipedia.org/wiki/Explained_variation
