# SnakeGame_Python
O jogo da cobrinha, como ficou popularmente conhecido, é um jogo extremamente viciante e simples. Nesse projeto, optei por recriar o jogo da cobrinha utilizando a linguagem Python.

Além da linguagem Python, utilizei uma biblioteca chamada "turtle" para criação dos objetos e do jogador. Essa biblioteca é muito útil para criação de jogos, principalmente aqueles com mecânicas simples.

Para criação do jogo primeiro devemos ter alguns passos em mente.

1: O jogador deve poder mudar a direção da cobra, sempre utilizando a cabeça como referência para mudar sua direção.

2: Devemos ter um placar para contabilizar os pontos, além da maior pontuação realizada na máquina.

3: Precisamos gerar a "comida" em pontos aleatórios do mapa.

4: Ao colidir com a comida, a cobra deve ficar maior e a comida deve desaparecer e reaparecer em um lugar aleatório da tela.

5: Ao colidir com alguma parede ou com o próprio corpo, o jogador perde e o jogo é reiniciado.

Tendo esses passos em mente, podemos dividir o jogo entre jogador, comida e placar.
