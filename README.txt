IA DE XADREZ FEITA EM PYTHON PARA O CHESS CHALLENGE ICEV 2023
----------------------------------------
Jogo básico de xadrez com interface gráfica utilizando pygame;
O jogo permite que uma IA controle um dos lados, utilizando o algoritmo de busca Negamax com Poda alpha-beta.

O código utiliza dicionários para atribuir pontuações a diferentes peças do xadrez.
Matrizes são usadas para atribuir pontuações específicas a posições do tabuleiro para diferentes peças, levando em consideração estratégias como a preferência por certas casas para cavalos, bispos, etc.


A função findMoveNegaMaxAlphaBeta implementa o algoritmo negamax com poda alfa-beta. Ele realiza uma busca recursiva no espaço de estados do jogo para encontrar a melhor jogada possível.
A função recebe o estado atual do jogo (gs), a lista de movimentos válidos, a profundidade da busca (depth), e os valores de alfa e beta para poda.
A variável turnMultiplier é usada para alternar entre os turnos dos jogadores durante a busca.
----------------------------------------
NECESSÁRIO PARA JOGAR:
pygame
----------------------------------------
GRUPO: OS ENXADRISTAS

INTEGRANTES: 
- Wickham Carneiro Pereira
- Heitor Macedo Monteiro de Araújo
- Antônio Neves Aguiar Neto