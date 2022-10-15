# Python Pandas: tratando e analisando dados
Repositório destinado ao curso de Python Pandas da Plataforma Allura.

### 01 - Conhecendo o Júpiter
    Essa aula ensinou a instalar o Anaconda e a utilizar o Júpiter Lab.
### 02 - Importando dados
    Importar a biblioteca - import pandas as pd
    Realizar a leitura de fontes de dados:
    CSV (pd.read_csv(...))
    JSON (pd.read_json(...))
    TXT (pd.read_table(...))
    EXCEL (pd.read_excel(...))
    HTML (pd.read_html(...))
    Conhecer métodos e atributos úteis de dataframes, como:
    info() - retirar informações do arquivo
    head() - mostrar só o topo da tabela
    dtypes - mostra o tipo de cada variável no arquivo lido
    columns - aferição de determinada informação das variáveis
    shape - retorna valor com número de linhas e o número de variáveis
### 03 - Series e index
    Selecionar uma variável do dataframe;
    Eliminar duplicatas (pelo método drop_duplicates())
    Redefinir o index de um dataframe e series
    Concatenar dataframes (lembrando do axis)
    Criar novos dataframes baseados em estruturas de dados Python (lista, dicionários ou tuples)
### 04 - Filtrando dados
    Series booleana usando o método isin(..)
    Filtrar os dados de um dataframe
    Exportar e gravar os dados do dataframe (to_csv())
    Ordenar os dados de um dataframe (sort_values() e sort_index())
### 05 - Frequências de imóveis
    Seleção com a condição OR (|)
    Seleção com a condição AND (&)
    Como criar um Index com split()
    Seleção por linha e coluna em um dataframe:
    Seleção por índices numéricos e os rótulos das linhas
### 06 - Tratamento de dados faltantes
    Identificar valores nulos (missing values)
    Mtodo isnull() indica se os valores são nulos
    Método notnull() retorna o contrário do método isnull()
    Método info() também é uma forma de se verificar a presença de valores faltantes
    Método dropna()
    Inversão de valores booleanos com ~
    Método fillna()
    Métodos de interpolação: ffill, bfill e mean()
### 07 - Novas variáveis
    Criar variáveis
    Excluir variáveis utilizando del, pop() e drop()
    Contadores, através do value_counts()
### 08 - Estatísticas descritivas
    Criar agrupamentos com o groupby()
    Estatísticas descritivas com o describe() e o aggregate()
    Renomear as colunas com o rename()
    Gráficos com o pacote Matplotlib
    Criar faixas de valor com o cut()
### 09 - Removendo Outliers
    Identificar e remover outliers com o box plot
    Fazer um gráfico de pizza com a aplicação do método pie(), da biblioteca matplotlib