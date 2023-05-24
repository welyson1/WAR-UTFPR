# WAR UTFPR

O jogo analógico baseado em WAR para ensino de Metrica e Estimativas de software

# O jogo
O jogo tem como objetivo testas enquanto aborda conteúdo sobre Estimativas e métricas de software, para tal foi utilizado o jogo analógico WAR como base para desenvolver o WAR UTFPR.

# Regras
#### Iniciando o jogo
O jogo pode ser jogado por 2 ou 4 jogadores;
Cada jogador escolhe uma cor de soldado que representa um curso;

Cada jogador pega uma quantidade igual de cartas de território (5 ou 10 cartas para cada), todos podem ver essas cartas;

Cada jogador recebe uma tropa por carta de território e deve  colocar uma em cada território;
Cada jogador pega uma carta de objetivo, essa carta é secreta;

Todos os jogadores rolam os dados e o jogador com maior soma começa o jogo.

No início de cada rodada, o jogador recebe a mesma quantidade de novas tropas que sua quantidade atual de territórios;

Para ser considerado como conquistado, um território obrigatoriamente deve ter pelo menos uma tropa.

#### Combate
No seu turno, o jogador pode atacar um território inimigo imediatamente ao seu lado, ou ligado por uma linha pontilhada;

Se decidir atacar um território inimigo
O jogador atacante deve escolher com quantas tropas deseja atacar;

O jogador que esta sendo atacado pega a quantidade de perguntas iguais a quantidade de tropas que o jogador atacante escolheu;

Se o atacado errar a pergunta, ele perde uma tropa, se acertar, o atacante perde uma tropa.

#### Turnos
A cada turno os jogadores recebem X tropas para alocar em seus territórios.

#### Vitória
Ganha o jogador que cumprir a carta de objetivo.

# Construção
#### Mapa
O software abaixo divide o PDF do mapa em em quantas folhas e formatos você preferir(Para esse projeto usamos 4 folhas no formato A4).

https://gitlab.mister-muffin.de/josch/plakativ
![Fazer Login](https://raw.githubusercontent.com/welyson1/organon/main/docsTest/Classes%20automatizadas/Login.png)

#### Cartas
O modelo das cartas foram feitas no app DRAW.IO e exportadas em XML.
![Fazer Login](https://raw.githubusercontent.com/welyson1/organon/main/docsTest/Classes%20automatizadas/Login.png)

Para automatizar a geração das cartas foi utilizado um prompt no chatGPT 4.0 para substituir os textos do arquivo XML.
![Fazer Login](https://raw.githubusercontent.com/welyson1/organon/main/docsTest/Classes%20automatizadas/Login.png)

#### Soldados
Para os soldados foi utilizado lantejogas coloridas para representar cada curso
![Fazer Login](https://raw.githubusercontent.com/welyson1/organon/main/docsTest/Classes%20automatizadas/Login.png)

# Downloads

# Teste