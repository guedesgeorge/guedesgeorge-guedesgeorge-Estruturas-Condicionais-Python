# Estruturas Condicionais em Python 🐍

Este repositório contém exercícios e exemplos práticos sobre lógica de programação utilizando Python, focando em estruturas de decisão e operadores lógicos.

## 📝 Conteúdo Estudado

### 1. Estruturas de Decisão (`if`, `else`, `elif`)
Aprendi como o programa toma decisões baseadas em condições verdadeiras ou falsas.
- **IF:** Executa um bloco de código se a condição for verdadeira.
- **ELSE:** Define o que acontece quando a condição inicial é falsa.
- **ELIF:** Permite testar múltiplas condições em sequência.

### 2. Operadores de Comparação
Utilizados para avaliar relações entre valores:
* `==` (Igual a)
* `!=` (Diferente de)
* `>` e `<` (Maior e Menor que)
* `>=` e `<=` (Maior ou igual / Menor ou igual)

### 3. Expressões Lógicas e Tabela Verdade
Uso de operadores para combinar condições:
* **AND:** Retorna verdadeiro apenas se **todas** as condições forem verdadeiras.
* **OR:** Retorna verdadeiro se **pelo menos uma** condição for verdadeira.
* **NOT:** Inverte o valor lógico (o que é falso vira verdadeiro).
* **IN:** Verifica se um elemento está contido em uma sequência (lista ou string).

## 🚀 Exemplos Práticos

### Sistema de Notas
Um algoritmo que avalia a média de um estudante:
- Média >= 6.0: **Aprovado**
- Média entre 4.0 e 5.9: **Recuperação**
- Média < 4.0: **Reprovado**

```python
media = float(input("Digite a média: "))

if media >= 6.0:
    print("Aprovado")
elif 4.0 <= media < 6.0:
    print("Recuperação")
else:
    print("Reprovado")
