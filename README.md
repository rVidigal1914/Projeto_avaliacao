# Projeto_avaliacao

LINK PARA ACESSO À RESOLUÇÃO DO EXERCÍCIO:

https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4142108789700180/2913106976143531/5988171451136863/latest.html

PASSO A PASSO:

1. A criação das tabelas ATENDIMENTOS e PRODUTOS foram realizadas através do PYTHON, utilizando a biblioteca SPARKSESSION e as respectivas estruturas necessárias ( tipos ) para nosso contexto
2. A alimentação dessas tabelas foi realizada através da biblioteca FAKER, que gerou os dados das duas tabelas supramencionadas, utilizando-se da criação de Dataframes, remoção da tabela ( caso ela já existisse), salvamento da respectiva tabela e lançamento de exceção caso ocorra algum erro.
3. Com as 2 tabelas criadas e alimentadas, elaboramos scripts de SELECT para trazer as informações solicitadas em cada passo do exercício.
4. Considerando as tabelas geradas pelo FAKER, chegamos às seguintes informações para tomada de decisão:
       a) O produto "CULTURE" deve ser priorizado em campanhas de marketing porque gerou o maior faturamento ( 5968644.93 ).
       b) A filial "WEST DAVID" deve receber mais investimentos porque teve o maior número de atendimentos ( 5.652 ).
       c) O estoque pode ser otimizado reduzindo o estoque do produto "SON", que tem o maior valor alocado (3419639.57).
5. Para a geração do gráfico, demonstrando as top 5 filiais, trabalhamos com as bibliotecas SPARKSESSION , PANDAS & MATPLOTLIB
       - A biblioteca SPARKSESSION auxiliou na execução da consulta SQL que obteve as top 5 filiais
       - A biblioteca PANDAS foi necessária para trabalharmos com o DATAFRAME resultante da consulta SQL executada pelo SPARK
       - Enquanto a biblioteca MATPLOTLIB foi a responsável por plotar e gerar o gráfico exibido no bloco 29
6. A resolução do exercício ocorre a partir do bloco 28. Os blocos anteriores foram utilizados para testes e criação, alimentação das tabelas, conforme mencionado nos parágrafos anteriores.


