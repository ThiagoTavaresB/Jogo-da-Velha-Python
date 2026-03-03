# Projeto em Python – Computação

Projeto acadêmico desenvolvido para a disciplina de Programação.

## Objetivo
Realizar um jogo simples em python.

## Tecnologias
- Python

## Como executar
python main.py

## Códigos explicados

● desenhar_tabuleiro(): Responsável por exibir o estado atual do tabuleiro na
tela, utilizando caracteres para representar as posições e peças.
● verificar_vitoria(): Verifica se um determinado jogador ('X' ou 'O') conseguiu
completar uma linha, coluna ou diagonal, indicando uma vitória.
● verificar_empate(): Verifica se todas as posições do tabuleiro estão ocupadas,
indicando um empate.
● jogada_jogador(): Permite que o jogador humano insira as coordenadas da
sua jogada, validando a entrada para garantir que seja uma posição válida e
livre no tabuleiro.
● jogada_computador(): Chama as funções específicas para cada nível de
dificuldade, delegando a decisão da jogada do computador.
● jogada_computador_facil(): Implementa uma estratégia aleatória para a
jogada do computador, escolhendo uma posição vazia de forma aleatória.
● jogada_computador_medio(): Implementa uma estratégia mais elaborada,
priorizando o centro do tabuleiro e os cantos, em seguida, escolhendo uma
posição aleatória.
● main(): É a função principal do programa, responsável por controlar o fluxo do jogo,
inicializar o tabuleiro, solicitar a escolha do modo de jogo, alternar entre as jogadas
dos jogadores e verificar as condições de vitória e empate.
