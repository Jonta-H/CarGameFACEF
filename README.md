<h1 align="center">SpaceShooter Game 🚀</h1>
<p align="center">Jogo: https://jontah.itch.io/spaceshooter </p>

<h2 align="center">Como jogar 🚀</h2>

<p align="center">Movimente e atire com sua nave. Seja ágil! Não permita que as naves inimigas cheguem até você. Destrua-as.</p>
<p align="center">Mova-se através das setas direcionais e utilize o mouse para atirar e ativar seu escudo.</p>

<h2 align="center">Sobre o jogo 🚀</h2>

<p align="center">Este jogo foi desenvolvido como parte de um projeto acadêmico para o 1º semestre do curso de Sistemas de Informação do Uni-FACEF. Utilizou-se a versão gratuita do Construct 3, uma plataforma online voltada ao desenvolvimento, programação e publicação de jogos 2D. 
<p align="center">O objetivo do jogo é simples: sobreviver o maior tempo possível sem permitir que os inimigos alcancem você.</p>
<p align="center">A proposta era criar uma experiência sem um final definido, que fosse desafiadora e colocasse à prova as habilidades do jogador, incentivando-o a alcançar pontuações cada vez mais altas. Para isso, foi implementado um sistema de pontuação com integração ao banco de dados do Firebase, responsável por armazenar os dados dos jogadores.</p>
<p align="center">O jogo está publicado na plataforma Itch.io e pode ser acessado <a href="https://jontah.itch.io/spaceshooter">clicando aqui</a>.</p>

<h2 align="center">Efeitos e funções</h2>

<p align="center">A fim de tornar a gameplay mais dinâmica e divertida, foram adicionadas ao jogo algumas funcionalidades e efeitos como:</p>
<p align="center">
  <ul>
    <li>Spawn aleatório de inimigos</li>
    <li>Naves destruídas explodem gerando partículas e causando um tremor na tela</li>
    <li>Surgimento ocasional de orbes que, quando atingidos, causam um flash e destroem todos os inimigos</li>
    <li>Naves inimigas possuem características distintas, desde a movimentação até a resistência</li>
    <li>Escudo de proteção que se recarrega durante o jogo</li>
    <li>Aumento progressivo na velocidade dos inimigos</li>
    <li>Placar que exibe a pontuação e o nível atual do jogador</li>
    <li>Um ranking de melhores pontuações</li>
  </ul>
</p>

<h2 align="center">Firebase 🚀</h2>

<p align="center">Integrado ao Firebase, o jogo utiliza dos recursos de armazenamento e sincronização de dados em tempo real para coletar a pontuação do jogador, possibilitando o registro com seu nome no Ranking de pontuações. O envio e recebimento é feito através da função AJAX disponível no Construct, que permite ao jogo solicitar e enviar informações para outras páginas da web.</p>



<h2 align="center">Assets/Sprites 🚀</h2>

<p align="center">Durante o desenvolvimento do projeto, foram utilizados diversos modelos para representação de naves, efeitos, partículas, cenário e HUD, todos eles feitos à mão.
<p align="center">Alguns deles:</p>
</p>
<table>
  <tr>
    <td><img src="Assets/player.png" width="300"></td>
    <td><img src="Assets/enemy2.png" width="300"></td>
    <td><img src="Assets/player_shield.png" width="300"></td>
  </tr>
  <tr align="center">
    <td>Nave do Jogador</td>
    <td>Nave Inimiga</td>
    <td>Escudo</td>
  </tr>
</table>


<h2 align="center">Prints 🚀</h2>

<p align="center">Abaixo estão algumas imagens que mostram um pouco do desenvolvimento e funcionamento do jogo, além também do Banco de dados e sua configuração.</p>

<h3 align="center">Jogo</h3>
  <div align="center">
   <Table>
      <tr>
        <td><img src="Prints/mainLayout.png" width="900"></td>
        <td><img src="Prints/mainLayout_config.png" width="300">
      </tr>
      <tr align="center">
        <td>Layout Principal</td>
        <td>Propriedades</td>
      </tr>
  </Table>
  <Table>
      <tr>
        <td><img src="Prints/objectsLayout.png" width="900"></td>
        <td><img src="Prints/objectsLayout_config.png" width="300">
      </tr>
      <tr align="center">
        <td>Layout Secundário</td>
        <td>Propriedades</td>
      </tr>
  </Table>
  <Table>
    <tr>
      <td><img src="Prints/start_screen.png" width="500"></td>
      <td><img src="Prints/gameOver_screen.png" width="500"></td>
    </tr>
    <tr align="center">
      <td>Tela de Início</td>
      <td>Tela de GameOver</td>
    </tr>
  </Table>
  <Table>
    <tr>
      <td><img src="Prints/inGame.png" width="400"></td>
      <td><img src="Prints/inGame_flashOn.png" width="400"></td>
      <td><img src="Prints/inGame_shieldOn.png" width="400"></td>
    </tr>
    <tr align="center">
      <td>inGame</td>
      <td>Flash Ativado</td>
      <td>Escudo Ativado</td>
    </tr>
  </Table>
  <table>
    <tr><td><img src="Prints/shield_bar.gif" width="400"></td></tr>
    <tr align="center"><td>Barra do escudo</td></tr>
  </table>
  <Table>
    <tr><th colspan="2">Folha de Eventos</th></tr>
    <tr>
      <td><img src="Prints/eventSheet_1.png" width="500"></td>
      <td><img src="Prints/eventSheet_2.png" width="500"></td>
    </tr>
    <tr>
      <td><img src="Prints/eventSheet_3.png" width="500"></td>
      <td><img src="Prints/eventSheet_4.png" width="500"></td>
    </tr>
    <tr>
      <td><img src="Prints/eventSheet_5.png" width="500"></td>
      <td><img src="Prints/eventSheet_6.png" width="500"></td>
    </tr>
    <tr>
      <td><img src="Prints/eventSheet_7.png" width="500"></td>
      <td><img src="Prints/eventSheet_8.png" width="500"></td>
    </tr>
    <tr align="center"><td colspan="2"><img src="Prints/variables.png" width="700"></td></tr>
    <tr align="center"><td colspan="2">Variáveis</td></tr>
  </Table>
</div>
<h3 align="center">Banco de dados</h3>
<div align="center">
  <table>
    <tr><td><img src="Prints/Firebase.png" width="900"></td></tr>
    <tr align="center"><td>BD Firebase</td></tr>
  </table>
  <table>
    <tr><td><img src="Prints/Database_rules.png" width="900"></td></tr>
    <tr align="center"><td>Regras</td></tr>
  </table>
</div>
