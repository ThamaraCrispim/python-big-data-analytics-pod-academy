# Aula 3 – Python (Hands-on) 🐍💻

Aula prática com foco em funções, estruturação de código e manipulação inicial de dados em Python.

## Exemplos Trabalhados

### Funções
    def soma(a, b):
        return a + b

    def media(valores):
        return sum(valores) / len(valores)

### Parâmetros e Escopo
    x = 10

    def teste():
        x = 5
        return x

### Estruturas de Repetição
    for i in range(5):
        print(i)

    contador = 3
    while contador > 0:
        contador -= 1

### List Comprehension
    pares = [n for n in range(10) if n % 2 == 0]

### Importação de Bibliotecas
    import pandas as pd
    import math

### Pandas – DataFrame
    df = pd.DataFrame({
        "nome": ["Ana", "João", "Maria"],
        "idade": [23, 30, 27]
    })

### Operações com Dados
    df.head()
    df.describe()

    df[df["idade"] > 25]

    df["idade_dobrada"] = df["idade"].apply(lambda x: x * 2)

> Aula desenvolvida em notebook (.ipynb), com abordagem totalmente prática (hands-on).


