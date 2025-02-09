---------------------Match The Tiles- Sliding Game-----------------------

Na nossa versão do jogo 'Match The Tiles- Sliding Game', existem quatro movimentos de peças possíveis (up, down, left, right). Todas as peças coloridas devem deslizar no tabuleiro e corresponder com peças da respetiva cor.
Aém disso,estes movimentos sincronizados das peças, devem contornar os obstáculos existentes para a respetiva resolução do puzzle.


----Funcionalidades----
- interface gráfica simples;
- Possibilidade de escolher diferentes tabuleiros com níveis de dificuldade diferentes;
- Oportunidade de executar 'restart' aos moves do jogo no respetivo nível e de terminal o jogo('quit')
- #Opção de escolher o search algorithm desejado#
- #Função de dica ('hint'), que varia de acordo com o search algorithm usado, mostrando a próxima jogada possível#

----Algoritmos de busca utilizados no trabalho----

- Breadht-First Search(BFS)- utiliza uma fila para explorar estados e encontrar a solução.
 A função retorna o caminho para a solução ou None se não houver solução dentro da profundidade máxima definida.

- A* Algorithm (A Star) - Utiliza uma fila de prioridade, um conjunto de estados visitados, um caminho e uma contagem de profundidade para explorar estados e encontrar a solução.
   O algoritmo usa a distância de Manhattan como heurística e a soma da distância heurística e do custo do caminho percorrido como custo total. 
   A função retorna o caminho para a solução ou None se não houver solução dentro da profundidade máxima definida.


----Requisitos----
- Python; bibliotecas Pygame, Sys, Copy.

----Método de utilização----
- Instalar a biblioteca Pygame, caso não esteja previamente instalada;
- Aceda ao terminal e verifique que se encontra no diretório 'jogo' para ter acesso ao mesmo;
- Execute o comando python3 e escolha se deseja jogar o jogo em Pygame ou no terminal;
- Selecione a dificuldade (fácil, médio ou difícil) e o respetivo nível que deseja jogar (nível 1,2 ou 3);
- Use as teclas w(up),s(down),a(left) e d(right) para movimentar as peças no tabuleiro, tanto em Pygame como no input pedido no terminal ;
- Os espaços vazios, ou seja, locais para onde se podem movimentar as peças, estão representados por espaços em branco em Pygame e por zeros no terminal. Além disso, os obstáculos (espaços pretos em Pygame) e as paredes/limites do tabuleiro estão representados por '*' no terminal, enquanto que as peças a movimentar estão representadas por 1,2,(...) e as respetivas correspondências por -1,-2(...);
- #Se precisar de ajuda, clique no botão 'Hint' para ver a próxima jogada possível#;
- Tente mover a(s) peça(s) distinta(s) até estas encontrarem a sua correspondência. No caso do Pygame, a(s) peça(s) de distinta(s) cor(es) devem dar 'match' com as respetivas peças e no terminal as peças que são representadas por 1,2, (...) devem, através dos movimentos corretos, dar o respetivo 'match' com -1.-2,(...);
-#Explore as outras possibilidades do 'Menu', em Pygame, tal como a seleção do search algorithm que deseja e da profundidade a que o algoritmo tem acesso, ou então no terminal quando seleciona a 'hint'#
 
 
Trabalho desenvolvido para a cadeira de Elementos de Inteligência Artificial e Ciência de Dados, realizado por:
- Cristiana Silva, up202305464
- Filipa Marinha, up202304935
- Filipa Ferreira, up202305895

  Esperemos que gostem!
  
