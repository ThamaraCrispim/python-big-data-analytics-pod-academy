# Aula 2 – Python para Big Data & Analytics 🐍📊

Nesta aula foram abordados os principais fundamentos da linguagem Python, com foco em lógica de programação e manipulação de dados, essenciais para aplicações em Big Data e Analytics.

---

## 📌 Conteúdos Abordados

### 🔹 Indentação
- Python utiliza indentação para definir blocos de código.
- Essencial para estruturas como `if`, `for`, `while` e funções.

---

### 🔹 Operadores
- **Atribuição**: `=`, `+=`, `-=`, `*=`, `/=`
- **Comparação**: `==`, `!=`, `>`, `<`, `>=`, `<=`
- Diferença entre:
  - `==` → compara valores
  - `is` → compara identidade (mesmo objeto na memória)

---

### 🔹 Estruturas Condicionais
- `if`, `elif`, `else`
- Controle do fluxo do programa baseado em condições lógicas.

---

### 🔹 Estruturas de Repetição
- **for**
- **while**
- Funções auxiliares:
  - `range()`
  - `enumerate()`

---

### 🔹 Coleções em Python

#### 📋 Listas
- Criação e manipulação de listas
- Operações:
  - Tamanho (`len`)
  - Ordenação
  - Divisão (slicing)
  - Remoção de elementos (`remove`, `pop`, `del`)
  - Limpeza da lista

#### 📦 Dicionários (dict)
- Estrutura chave–valor
- Operações:
  - Inserção, remoção e limpeza
  - `keys()`, `values()`, `items()`
  - Junção de dicionários
  - Métricas: `min`, `max`
  - Identificação da chave associada ao maior valor
- Observação: não permite chaves duplicadas

---

### 🔹 List Comprehension
- Forma concisa de criar listas
- Sintaxe:
  ```python
  [expressao for item in sequencia if condicao]
