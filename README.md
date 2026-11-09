import pandas as pd

# Carregar o arquivo CSV
df = pd.read_csv("/content/nome_do_arquivo.csv")

# Exibir as primeiras 5 linhas
print(df.head())

# Exibir informações gerais do DataFrame
print(df.info())

# Exibir o número de linhas e colunas
print("Dimensões do arquivo:", df.shape)

# Verificar valores ausentes
print(df.isnull().sum())

# Exibir estatísticas descritivas
print(df.describe())

# Exibir os nomes das colunas
print(df.columns)