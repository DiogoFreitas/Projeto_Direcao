# Projeto_Direcao
Projeto de jogo. O jogador precisa selecionar personagens e acertar a que direção se encontram, o primeiro em relação ao segundo selecionado.

/*
Objetivo do jogo:
 O jogador precisa acertar a que direção (pontos cardeais) se encontram, o primeiro em relação ao segundo selecionado.
 
Caso de uso 1: Iniciar
 Jogador abre a tela, no início aparecem muitos personagens na tela e um placar com 3 pontos.
   Pré-requisitos:
   Jogador precisa começar com os três pontos. 

Caso de uso 2: lance da partida
 2.1: Jogador seleciona o primeiro personagem, personagem 1 muda de cor. 
 2.2: Jogador seleciona segundo jogador. Entre eles aparece uma aresta direcionada, segundo personagem também muda de cor.
 2.3: Jogador seleciona a direção. Se acertar, marca um ponto; se errar, perde um ponto. Partida termina se alcançar 12 acertos,    ou se zerar os pontos que possui.
     Pré-requisitos: Aparece uma lista em um quadro ao lado com as opções que o jogador pode escolher. 

 
 
 
 */
 
 /* Ideia para tirar a posição fixa do objeto no centro da matriz Tabuleiro:
 implementar a matriz 5x5 como uma "máscara", para constatar as distâncias dos objetos ao redor; */
