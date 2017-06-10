# BoulderDash_Multiplayer
Jogo Boulder Dash em multijogador || Boulder Dash game in multiplayer |


Cada jogador possui o seu personagem Rockford que pode garimpar pelas cavernas e pelo meios das rochas existentes, na pesquisa das gemas de diamante;
-----------------
Todos os outros jogadores devem ver-se mutuamente bem como as cavernas, as rochas existentes e as gemas que vão sendo apanhadas;
-----------------
Cada jogador deve ter um interface que lhe permita visualizar os outros jogadores, as cavernas, os caminhos que vão sendo escavados e as gemas que podem ser apanhadas;
-----------------
Um servidor deve suportar vários jogos de cada vez; cada jogo exige a presença de 2 jogadores (clientes) e limita o máximo a 4; cada jogador só pode jogar um jogo de cada vez;
-----------------
Para acederem ao serviço os jogadores devem registar-se com um username e password;
-----------------
Os jogadores efectuam a autenticação e acedem ao hall de entrada; nesta área poderão visualizar os jogos existentes, juntar-se a um jogo ou criar um novo jogo e esperar por adversários para começar o jogo;
-----------------
Depois de se juntar a um jogo, cada jogador deverá sincronizar as suas acções (e.g., posição/movimentação, estado das cavernas, rochas, gemas, pontuação, etc.) com o servidor e este com os restantes jogadores;
-----------------
O sistema deverá gerir automaticamente a persistência dos seus jogos através de uma base de dados ou ficheiros;
-----------------
O estado dos diferentes jogos deve ser distribuído/replicado para outros servidores, para garantir tolerância a falhas;
-----------------
Se um servidor falhar então os clientes poderão/deverão contactar o coordenador que os encaminhará para um novo servidor que possua uma réplica actualizada do jogo;
-----------------
Se o coordenador falhar então deve proceder-se à eleição de outro coordenador para restabelecer as condições de suporte aos jogos;
