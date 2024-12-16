# 📓 Algumas Funções Python que Você Deve Saber na Ponta da Língua

Este repositório apresenta exemplos práticos de algumas funções essenciais do Python que todo desenvolvedor deve conhecer. Estas funções são amplamente utilizadas por programadores para simplificar tarefas e tornar o código mais eficiente e legível.

## 🚀 Funções Abordadas

### 👉 **`sorted()`**  
Ordena dados de forma simples—em ordem crescente ou decrescente! Ideal para organizar arrays ou encontrar medianas.  
#### Exemplo:  
```python
numeros = [5, 2, 9, 1, 5, 6]
ordenados = sorted(numeros)
print(ordenados)  # Saída: [1, 2, 5, 5, 6, 9]
```

### 👉 **`zip()`**  
Agrupa dados como um verdadeiro profissional. Combine listas, tuplas ou iteráveis com facilidade.  
#### Exemplo:  
```python
nomes = ['Ana', 'João', 'Carlos']
idades = [25, 30, 22]
combinado = list(zip(nomes, idades))
print(combinado)
# Saída: [('Ana', 25), ('João', 30), ('Carlos', 22)]
```

### 👉 **`max()` / `min()`**  
Encontre rapidamente o maior ou menor elemento. Perfeito para problemas de otimização e manipulação de arrays.  
#### Exemplo:  
```python
valores = [10, 15, 7, 40, 28]
print(max(valores))  # Saída: 40
print(min(valores))  # Saída: 7
```

### 👉 **`enumerate()`**  
Percorra listas de forma inteligente! Acompanhe os índices sem precisar criar contadores manuais.  
#### Exemplo:  
```python
lista = ['a', 'b', 'c']
for indice, valor in enumerate(lista):
    print(f"Índice {indice}: Valor {valor}")
# Saída:
# Índice 0: Valor a
# Índice 1: Valor b
# Índice 2: Valor c
```

### 👉 **`map()`**  
Transforme coleções com elegância. Aplique funções a iteráveis em apenas uma linha de código.  
#### Exemplo:  
```python
numeros = [1, 2, 3, 4]
quadrados = list(map(lambda x: x**2, numeros))
print(quadrados)  # Saída: [1, 4, 9, 16]
```

### 👉 **`itertools.combinations()`**  
Gere todos os subconjuntos ou combinações possíveis. Essencial para resolver problemas de combinações ou subconjuntos.  
#### Exemplo:  
```python
from itertools import combinations
dados = [1, 2, 3]
combinacoes = list(combinations(dados, 2))
print(combinacoes)  # Saída: [(1, 2), (1, 3), (2, 3)]
```

### 👉 **`collections.Counter()`**  
Conte frequências em questão de segundos. Ideal para histogramas ou rastrear ocorrências em dados.  
#### Exemplo:  
```python
from collections import Counter
frutas = ['maçã', 'banana', 'maçã', 'laranja', 'banana', 'maçã']
contagem = Counter(frutas)
print(contagem)
# Saída: Counter({'maçã': 3, 'banana': 2, 'laranja': 1})
