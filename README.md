# Analise_dados_cubos_engie

## Curso Análise de Dados Python, Sql e Power By

### Introdução ao Python

#### Variáveis, tipos primitivos, manipulação de Strings, operadores aritméticos, operadores lógicos, condições,

#### laços de repetições,For e While e Listas.

### Bibiliotecas, Funções

### Dataframes :

Criar dataframe, acessar dados .

#### 

import pandas as pd

print('DataFrame apartir de um dicionário')

dict={

    'idade':[36,35],

    'genero':['f','m'],

    'peso':[63,68],

    'altura':[1.67,1.69]

}

data = pd.DataFrame(dict)

print(data)
