# README - A Nota Esquecida

## Descrição do Problema

João, um estudante de Geografia, precisa descobrir a nota da segunda prova que ele fez. Ele se lembra de uma das notas e da média das duas provas, mas não consegue recordar a outra nota. Sua tarefa é calcular qual é essa nota.

## Fórmula

A média \( M \) de duas notas \( A \) e \( B \) é dada pela fórmula:

\[ M = \frac{A + B}{2} \]

Para encontrar a nota \( B \), podemos rearranjar a fórmula:

\[ B = 2M - A \]

## Entrada

A entrada consiste em duas linhas:
1. Um número inteiro \( A \) que representa a nota de uma das provas. 
   - **Condições**: \( 0 \leq A \leq 100 \)
2. Um número inteiro \( M \) que representa a média das duas notas.
   - **Condições**: \( 0 \leq M \leq 100 \)

## Saída

A saída deve ser um número inteiro, que representa a nota da segunda prova \( B \).

## Exemplo de Entrada e Saída

### Exemplo 1
**Entrada**
```
100
70
```
**Saída**
```
40
```

### Exemplo 2
**Entrada**
```
80
75
```
**Saída**
```
70
```

### Exemplo 3
**Entrada**
```
1
50
```
**Saída**
```
99
```

## Restrições

- As notas devem ser números inteiros entre 0 e 100.
- A média \( M \) também deve ser um número inteiro entre 0 e 100.

## Considerações

- O problema envolve o cálculo simples de uma média e a reordenação da fórmula para encontrar a nota que João não se lembra.
- O programa deve garantir que o valor calculado para \( B \) esteja dentro do intervalo permitido.
- A complexidade do algoritmo é O(1), já que apenas envolve operações aritméticas básicas.

## Implementação

Aqui está um exemplo de como você pode implementar a solução em Python:

```python
# Leitura das entradas
A = int(input())
M = int(input())

# Cálculo da segunda nota
B = 2 * M - A

# Saída da nota da outra prova
print(B)
```

## Autores

- Este problema foi apresentado na Olimpíada Brasileira de Informática – OBI 2019, na fase estadual, nível 1.
