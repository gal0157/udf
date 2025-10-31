# Projeto Temático de Halloween - Técnicas de Desenvolvimento de Algoritmo

[cite_start]Este repositório contém os projetos desenvolvidos para a disciplina de Técnicas de Desenvolvimento de Algoritmo[cite: 1]. [cite_start]O objetivo é explorar conceitos fundamentais de programação, como estruturas de controle, manipulação de strings, listas e o uso de módulos [cite: 1][cite_start], através de dois jogos com a temática de Halloween[cite: 7].

## 🎃 Jogos Incluídos

### 1. Adivinhe o Segredo da Bruxa (adivinhacao_bruxa.py)

[cite_start]Um jogo de adivinhação onde o jogador deve descobrir um número secreto guardado pela bruxa[cite: 3, 5, 6].

* [cite_start]**Foco:** Loops (`while`) [cite: 3][cite_start], condicionais (`if/elif/else`) [cite: 3][cite_start], e o uso da biblioteca `random`[cite: 3].
* [cite_start]**Conceitos:** Geração de números aleatórios (`random.randint`) [cite: 34, 119][cite_start], tratamento de exceções (`try...except ValueError`) [cite: 125][cite_start], e variáveis de controle (flags)[cite: 121, 122].

### 2. Forca Assustadora (forca_assustadora.py)

[cite_start]Uma implementação do clássico Jogo da Forca, utilizando um banco de palavras secreto relacionado ao Halloween[cite: 4, 131].

* [cite_start]**Foco:** Manipulação de strings [cite: 4][cite_start], uso de listas (para a palavra secreta e estados da forca) [cite: 4, 371, 372][cite_start], loops e lógica de arrays[cite: 4].
* [cite_start]**Conceitos:** Seleção aleatória de itens de uma lista (`random.choice`) [cite: 252][cite_start], manipulação de listas (`append`, `join`) [cite: 301, 354, 356][cite_start], e iteração sobre strings para construção da exibição[cite: 283, 382].

## 🛠️ Conceitos Aplicados

Este projeto demonstra a aplicação prática dos seguintes conceitos de algoritmos:

* [cite_start]**Estruturas de Controle:** Uso de loops `while` para controlar o fluxo principal dos jogos [cite: 52, 123, 272, 374] [cite_start]e condicionais `if/elif/else` para a tomada de decisão[cite: 96, 127, 333].
* [cite_start]**Manipulação de Listas e Strings:** Utilização de listas para armazenar o banco de palavras [cite: 254][cite_start], as letras (certas e erradas) [cite: 373][cite_start], e os estágios da forca[cite: 142, 371]. [cite_start]A iteração e concatenação de strings são usadas para exibir o status do jogo[cite: 283, 384].
* [cite_start]**Módulos:** Importação e uso da biblioteca `random` para selecionar números e palavras secretas [cite: 118, 369] [cite_start]e do módulo `os` para limpar a tela do console[cite: 133, 370].
* [cite_start]**Tratamento de Exceções:** Implementação de `try...except ValueError` no jogo de adivinhação para garantir que o programa não falhe se o usuário digitar uma entrada não numérica[cite: 61, 66, 125].

## 🚀 Como Executar

Você precisará ter o Python instalado em sua máquina.

1.  Clone este repositório:
    ```bash
    git clone <URL-DO-SEU-REPOSITORIO>
    ```
2.  Navegue até o diretório do projeto:
    ```bash
    cd <NOME-DO-DIRETORIO>
    ```
3.  Execute um dos jogos diretamente pelo terminal:

    **Para o Jogo de Adivinhação:**
    ```bash
    python adivinhacao_bruxa.py
    ```
    [cite_start][cite: 390]

    **Para o Jogo da Forca:**
    ```bash
    python forca_assustadora.py
    ```
    [cite_start][cite: 392]

## 🧪 Testes Sugeridos

[cite_start]Para garantir que os algoritmos funcionam como esperado, execute os seguintes cenários de teste[cite: 393]:

* [cite_start]**Caminho Feliz (Vitória):** Tente acertar o número ou a palavra corretamente antes que as tentativas se esgotem[cite: 394].
* [cite_start]**Caminho Triste (Derrota):** Esgote deliberadamente as tentativas (7 no Jogo 1, 6 no Jogo 2) sem acertar[cite: 395].
* **Entrada Inválida:**
    * [cite_start]No Jogo 1: Digite um texto (ex: "abc") em vez de um número[cite: 396].
    * [cite_start]No Jogo 1: Digite um palpite fora do intervalo (ex: 0 ou 51)[cite: 396].
    * [cite_start]No Jogo 2: Tente chutar mais de uma letra (ex: "AB")[cite: 396].
* [cite_start]**Tentativa Repetida:** No Jogo 2, tente chutar uma letra (certa ou errada) que já foi jogada[cite: 398].
