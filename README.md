# Desafio Batalha Naval (Solução em C)

> Status: Concluído 🚀

Este repositório contém a minha solução para o desafio "Batalha Naval", um projeto acadêmico focado na manipulação de **matrizes (arrays bidimensionais)** na linguagem C.

## 🎯 Nível Realizado

Este código implementa a solução completa para o **Nível Mestre** do desafio.

O programa cria e exibe um tabuleiro 10x10 e, em seguida, utiliza lógica de matrizes para:
1.  "Desenhar" três padrões de habilidades especiais (Cone, Cruz e Octaedro).
2.  Posicionar essas habilidades em locais específicos do tabuleiro.
3.  Adicionar quatro navios (vertical, horizontal e dois diagonais) no tabuleiro final.

## 🛠️ Conceitos Aplicados

* **Linguagem C**
* **Funções:** O código foi organizado em funções (ex: `inicializarTabuleiro`, `exibirTabuleiro`) para evitar repetição.
* **Matrizes (Arrays 2D):** Usadas para representar o tabuleiro principal e os padrões de habilidades.
* **Constantes (`#define`):** Para definir tamanhos fixos (linhas e colunas), facilitando a manutenção.
* **Loops Aninhados (`for`):** Essenciais para percorrer e preencher as matrizes.
* **Lógica Condicional (`if`, `||`, `&&`):** Usada para criar os "desenhos" das habilidades (ex: `if(i == 1 || j == 2)`).
* **Função `printf`:** Para exibir o tabuleiro formatado no console.

## ⚙️ Como Executar

Se você quiser testar o projeto:

1.  Clone este repositório:
    ```bash
    git clone https://github.com/camilesoria/batalhaNaval.git
    ```
2.  Navegue até a pasta do projeto e compile o arquivo `.c`:
    ```bash
    gcc batalhaNaval.c -o batalha_naval
    ```
3.  Execute o programa:
    ```bash
    ./batalha_naval
    ```

---

## 📜 Descrição Original do Desafio (Fornecida pela Faculdade)

Bem-vindo ao desafio "Batalha Naval"! Este projeto desafiará suas habilidades de programação utilizando vetores e matrizes para simular um jogo de Batalha Naval, dividido em três níveis: Novato, Aventureiro e Mestre. Em cada nível, novas funcionalidades serão adicionadas, tornando o desafio progressivamente mais complexo.
