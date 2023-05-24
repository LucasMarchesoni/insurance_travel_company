# insurance_travel_company

A análise foi realizada utilizando duas bases de uma empresa de viagens que está tentando saber quais clientes estão mais propícios a comprar o seguro de vida durante a viagem e as bases foram retiradas do www.kaggle.com.

A motivação da análise é entender quais fatores podem influenciar a aquisição do seguro de vida (nossa variável target). Sabendo isso, a empresa pode direcionar ações para as pessoas que não tem a tendência a adquirir para poder convencer elas a comprar esse seguro e aumentar o lucro da empresa.

Algumas perguntas que tentaremos responder:
* Quais as idades mais predominantes?
* Quais os setores que possuem mais (menos) clientes empregados?
* A quantidade de clientes que sofrem de algum tipo de doença de maior gravidade?
* A quantidade de viajantes frequentes?
* A quantidade de viajantes para fora do país?
* Quantos membros da familia cada cliente possui? Isso impacta na renda do cliente?
* Existe relação entre a escolaridade e a renda do cliente?
* Existe relação entre viajar para fora do país e renda do cliente? E com relação a escolaridade?
* Relações das variáveis com a variável target?

# Conclusão
O melhor modelo que conseguimos utilizar foi o KNN com um precision de 83%, escolhi utilizar essa métrica porque precisamos identificar qual clientes estariam verdadeiramente interessados em adquirir o seguro para poder direcionar ações efetivas para aumentar a chance deles comprarem. O modelo poderia atingir uma melhor acurácia possivelmente usando algum escalonador.
