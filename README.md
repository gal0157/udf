# Projeto da Disciplina: Técnicas de Desenvolvimento de Algoritmo

Este repositório armazena os projetos práticos desenvolvidos para a disciplina de Técnicas de Desenvolvimento de Algoritmo. O objetivo é aplicar conceitos fundamentais de programação, como estruturas de controle, manipulação de dados (strings e listas) e o uso de módulos.

## 💻 Projetos Implementados

### 1. Jogo de Adivinhação de Número (jogo_adivinhacao.py)

Um jogo onde o usuário deve adivinhar um número secreto gerado aleatoriamente dentro de um intervalo definido.

* **Foco:** Loops (`while`), estruturas condicionais (`if/elif/else`), e o uso da biblioteca `random`.
* **Conceitos:** Geração de números pseudo-aleatórios (`random.randint`), tratamento de exceções (`try...except ValueError`), e uso de variáveis de controle (flags).

### 2. Jogo da Forca (jogo_forca.py)

Uma implementação do clássico Jogo da Forca, onde o usuário tenta adivinhar uma palavra secreta com um número limitado de erros.

* **Foco:** Manipulação de strings, uso de listas (para o banco de palavras e o estado do jogo), loops e lógica de arrays.
* **Conceitos:** Seleção aleatória de itens de uma lista (`random.choice`), manipulação de listas (`append`), e iteração sobre strings para construção da exibição da palavra.

## 🛠️ Conceitos Técnicos Aplicados

Este projeto demonstra a aplicação prática dos seguintes conceitos de algoritmos:

* **Estruturas de Controle:** Uso de loops `while` para gerenciar o estado principal dos jogos (enquanto houver tentativas ou a palavra não for descoberta).
* **Tomada de Decisão:** Utilização de `if/elif/else` para comparar a entrada do usuário com o valor secreto e fornecer feedback.
* **Estruturas de Dados:** Uso de listas para armazenar o banco de palavras, as letras (corretas e incorretas), e os estágios visuais do jogo (desenho da forca).
* **Módulos e Bibliotecas:** Importação e uso da biblioteca `random` (para `randint` e `choice`)
