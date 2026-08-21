  # Gerador de Histograma em Python

## Descrição

Este projeto foi desenvolvido como atividade acadêmica para a disciplina de Introdução à Computação do curso de **Matemática Aplicada e Computacional da Universidade de São Paulo (USP)**.

O programa gera uma amostra aleatória de números reais dentro de um intervalo definido pelo usuário, calcula a frequência dos valores em classes pré-determinadas e exibe um histograma textual diretamente no terminal.

Além da construção do histograma, o projeto contempla validações de entrada, tratamento de erros e organização dos dados em intervalos estatísticos.

---

## Funcionalidades

- Geração de amostras aleatórias utilizando semente fixa.
- Definição personalizada dos limites do intervalo `[a, b)`.
- Escolha do tamanho da amostra.
- Definição do número de intervalos (classes).
- Cálculo automático das frequências.
- Exibição da tabela de frequências.
- Construção de histograma textual.
- Validação de entradas inválidas.
- Possibilidade de gerar múltiplos histogramas durante a execução.

---

## Tecnologias Utilizadas

- Python 3
- Biblioteca `random`

---

## Conceitos Aplicados

- Geração de números pseudoaleatórios
- Estruturas de repetição
- Estruturas condicionais
- Tratamento de exceções
- Estatística descritiva
- Distribuição de frequências
- Histogramas
- Manipulação de listas e dicionários

---

## Exemplo de Saída

```text
INTERVALO                  FREQUÊNCIA
0.00 a 2.00               004
2.00 a 4.00               007
4.00 a 6.00               006
6.00 a 8.00               002
8.00 a 10.00              001

HISTOGRAMA

      ■
      ■
■     ■     ■
■     ■     ■
■     ■     ■
■     ■     ■     ■
■     ■     ■     ■     ■

0.00  2.00  4.00  6.00  8.00
2.00  4.00  6.00  8.00 10.00

004   007   006   002   001
