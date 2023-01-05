# Jogo da Forca - Hangman 
O jogo da forca é um jogo em que o jogador tem que acertar qual é a palavra proposta, tendo como dica o número de letras e o tema ligado à palavra. A cada letra errada, é desenhado uma parte do corpo do enforcado. O jogo termina ou com o acerto da palavra ou com o término do preenchimento das partes corpóreas do enforcado.

---

O desenvolvimento do projeto foi realizado com as melhores práticas de programação tentando evidenciar as técnicas de programação orientada a objeto. O projeto consiste em, 

## Classe -> Hangman()
Na classe temos 6 métodos, 

* #### --init--: Método Construtor.
* #### gues(): Método para adivinhar a letra.
* #### hangman_over(): Método para verificar se o jogo terminou.
* #### hangman_won(): Método para verificar se o jogador venceu.
* #### hide_word(): Método para não mostrar a letra no board.
* #### print_game_status(): Método para checar o status do game e imprimir o board na tela.

---

## Function -> rand_word()
Função para ler uma palavra de forma aleatória do banco (.txt) de palavras

---

## Function -> main()
Execução do Programa, enquanto o jogo não tiver terminado, print do status, solicita uma letra e faz a leitura do caracter
