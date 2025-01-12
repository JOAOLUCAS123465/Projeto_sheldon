Jogo Pedra, Papel, Tesoura, Lagarto e Spock

Este repositório contém uma implementação do jogo Pedra, Papel, Tesoura, Lagarto e Spock, uma versão ampliada do tradicional jogo Pedra, Papel e Tesoura. O jogo pode ser jogado entre dois jogadores ou contra a máquina. Além disso, o tempo para jogar cada turno pode ser ajustado.

Regras do Jogo
O jogo segue as regras clássicas de Pedra, Papel e Tesoura, mas com a adição de dois novos elementos: Lagarto e Spock. Aqui estão as regras detalhadas:

Tesoura corta Papel
Papel cobre Pedra
Pedra esmaga Lagarto
Lagarto envenena Spock
Spock esmaga Tesoura
Tesoura decapita Lagarto
Lagarto come Papel
Papel refuta Spock
Spock vaporiza Pedra
Pedra quebra Tesoura


Como Jogar
Opções de Jogo
O jogo oferece duas opções para o jogador escolher:

Player 1 x Player 2 - Dois jogadores competem entre si.
Player 1 x Máquina - Um jogador compete contra a máquina.


Tempo do Turno
O tempo de cada turno pode ser definido como 30, 45 ou 60 segundos.

Escolha de Jogadas
Durante o jogo, os jogadores devem escolher entre os seguintes itens:
1 - Pedra
2 - Papel
3 - Tesoura
4 - Lagarto
5 - Spock

Vencedor
O vencedor de cada rodada é determinado de acordo com as regras mencionadas acima. Caso ambos escolham a mesma opção, a rodada termina em empate.

Como Rodar o Jogo
Para rodar o jogo, siga os seguintes passos:

Pré-requisitos
Certifique-se de ter um compilador C, como o gcc (GNU Compiler Collection), instalado em seu sistema.

Compilando o Código
Clone este repositório ou baixe o arquivo main.c.

Abra o terminal e navegue até a pasta onde o arquivo main.c está localizado.

Compile o código com o seguinte comando:

css
Copiar código
gcc -o pedra_papel_tesoura main.c
Execute o programa:

bash
Copiar código
./pedra_papel_tesoura
Jogo Interativo
O jogo solicitará que você escolha entre Player 1 x Player 2 ou Player 1 x Máquina, e em seguida, escolherá o tempo do turno e as opções de jogada.

Após o jogo terminar, o placar será exibido, e você poderá optar por jogar novamente.

Funções do Código
mostrar_opcoes()
Exibe as opções de escolha para o jogador (Pedra, Papel, Tesoura, Lagarto, Spock).

determinar_vencedor()
Determina o vencedor entre os jogadores com base nas regras do jogo.

mostrar_regras()
Exibe as regras detalhadas do jogo.

fazer_jogada()
Lida com a entrada dos jogadores, verifica a validade das escolhas e atualiza o placar.

jogar_turno()
Controla a duração de um turno e chama a função fazer_jogada() repetidamente até que o tempo termine.

Contribuindo
Se você gostaria de melhorar ou adicionar novas funcionalidades ao jogo, fique à vontade para fazer um fork deste repositório e enviar um pull request com suas melhorias.
