# Projeto de Classificação de filmes do IMDB

## Visão Geral do Projeto

Este projeto tem como objetivo classificar filmes a partir do banco de dados do IMDB com base em critérios definidos pelo usuário, tais como ano de lançamento, nota, custo de produção e duração. O código é escrito em Python e faz uso das seguintes bibliotecas:

## Importação de Dependências
- `pandas`: Usado para manipulação e análise de dados.
- `numpy`: Usado para operações numéricas.

## Leitura do Conjunto de Dados
O conjunto de dados é lido a partir do arquivo 'imdb-score.csv' usando a biblioteca Pandas.

## Pré-processamento dos Dados
Os dados do conjunto de dados são tratados da seguinte forma:
- Limpeza e padronização dos nomes das colunas.
- Conversão de valores de colunas relevantes em formatos adequados, como inteiros, flutuantes e datas.
- Conversão do custo de produção para um formato numérico.

## Definição da Importância de Cada Variável em Porcentagem
O usuário pode definir a importância de cada variável na classificação final. As importâncias são expressas em porcentagem.

## Variáveis Escolhidas Pelo Usuário
O usuário pode definir valores para as variáveis que serão usadas como critérios de classificação, como ano de lançamento, nota, custo e duração.

## Variável que Armazenará os Resultados
Uma estrutura de dados é criada para armazenar os resultados da classificação dos filmes.

## Verificação da Igualdade do Ano de Lançamento
O código verifica se o ano de lançamento de cada filme é igual ao valor definido pelo usuário e, se for, atribui a importância correspondente.

## Verificação se a Nota é Maior ou Igual
O código verifica se a nota de cada filme é maior ou igual à nota definida pelo usuário e, se for, atribui a importância correspondente.

## Verificação se o Custo é Maior ou Igual
O código verifica se o custo de produção de cada filme é maior ou igual ao valor definido pelo usuário e, se for, atribui a importância correspondente.

## Verificação se o Tempo do Filme é Maior ou Igual
O código verifica se a duração de cada filme é menor ou igual ao valor definido pelo usuário e, se for, atribui a importância correspondente.

## Ordena os Filmes e Apresenta os 5 Melhores Classificados
Os filmes são classificados com base nas importâncias atribuídas e os 5 melhores classificados são apresentados com seus respectivos percentuais de classificação.

Este projeto permite ao usuário personalizar a classificação de filmes de acordo com seus critérios e prioridades específicas.
