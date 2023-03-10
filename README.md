# Reggae Maze
**Número da Lista**: 34<br>
**Conteúdo da Disciplina**: Trabalho Final<br>
**Algoritmos Utilizados**: DFS com Backtracking (Grafos) + Knapsack adaptada (Programação Dinâmica)

# Alunos
|Matrícula | Aluno |
| -- | -- |
| 180144979  |  Caetano Santos Lucio |
| 200019228  |  Gustavo Martins Ribeiro |

# Sobre o Jogo
Quando criança, Jorginho era um ET muito serelepinho que adorava brincar de esconde esconde com seus amiguinhos. Contudo, o tempo passa e um dia a criança cresce, trazendo consigo grandes responsabilidades. É nesse contexto que o jorginho agora é o Jorge, um homem formado defensor de Selkers diante das constantes caçadas comerciais humanas. (Selkers são cachorros extra terrestres cuja carne vale muito nos mercados humanos)

Diante do exposto, a sua missão consiste em auxiliar o Jorge nessa empreitada, levando em consideração diversos utensílios que você encontrará espalhados pelo mapa.
Boa sorte nessa empreitada!

# Objetivo
O seu objetivo consiste em ajudar o Jorge a salvar o máximo de Selkers possível. Cuidado com as armadilhas, pois elas atrapalharão sua missão. Faça uso consciente dos itens, pois quando usados da maneira correta, podem ser grandes aliados nessa aventura!

# Personagens
Os personagens do jogo baseiam-se no Jorginho, Selkers e Black Selkers.


![1](https://user-images.githubusercontent.com/72039007/216835973-ab57775c-678d-4ec4-8208-06fc9671e36c.png)
### *Imagem 1* - Jorginho, o ET vida loka defensor de Selkers

![2](https://user-images.githubusercontent.com/72039007/216835976-95e0f742-f901-4162-82c2-785a21abe933.png)
### *Imagem 2* - Selkers: animalzinhos indefesos (são como os cachorros para os ETs)

![selkerNegro](https://user-images.githubusercontent.com/72039007/216835984-9552455e-b74d-48d0-85bb-976acd0df345.png)
### *Imagem 3* - Black Selkers: armadilhas, baseadas nos Selkers, criadas pelos humanos para caçar ETs

# Menu de opções
O menu de opções é composto, basicamente, por duas telas: o menu inicial e o menu de musicas, o qual pode ser acessado ao clicar em "Start" no menu inicial.

![image](https://user-images.githubusercontent.com/72039007/216840391-1c11689a-fa08-4019-8427-13d46505079a.png)
### *Imagem 4* - Menu Inicial

![image](https://user-images.githubusercontent.com/72039007/217028252-2c3b3e97-08d7-4a7b-b9d6-3c04b470c036.png)
### *Imagem 5* - Menu de Músicas

# Itens

![baseadao](https://user-images.githubusercontent.com/72039007/216836913-881363a6-f232-4e82-85d9-b9870bd7f7ba.png)
### *Imagem 6* - Baseadonys: o baseadones ajuda e atrapalha, use-o com moderação (fornece perda de velocidade, mas ganha um pouco de tempo)

![gasolina](https://user-images.githubusercontent.com/72039007/216836965-037309a8-ae77-41af-8705-a1fa751f124f.png)
### *Imagem 7* - Gasolina Fast Furious: fornece um grande aumento de velocidade para o Jorginho

![watch](https://user-images.githubusercontent.com/72039007/216836923-1d6b7565-953a-4615-ad00-70a31b3c9a32.png)
### *Imagem 8* - Relógio Mary Jane: hoje é seu dia de sorte! O Relógio Mary Jane fornece um grande aumento de tempo.

# Tela de derrota

![image](https://user-images.githubusercontent.com/72039007/216836703-723ed2d5-eb41-436d-adab-79224595ef02.png)
### *Imagem 9* - Tela de derrota: uma mensagem motivacional do grandioso Nelson Mandela para acalmar os ânimos. - "No pain, no gain brah !"
<br>

# Informações do Software

**Linguagem**: Python<br>
**Bibliotecas**: PyGame<br>

<br>

>A resolução padrão configurada para este projeto é de 900x600 para melhor visualização do labirinto. Caso a resolução do seu sistema seja menor ou deseja testar outras resoluções, sinta-se livre para mudar o parâmetro ```RES``` presente nas primeiras linhas do arquivo ```./maze_generator.py```.

<br>

- ### Windows
Baixe o pacote Python3 do [site official](https://www.python.org/downloads/), e no momento da instalação, marque a opção "Add Python to PATH" para no próximo passo instalar as dependências via terminal e rodar o nosso jogo.

- ### Linux
Execute no terminal do Linux a atualização dos pacotes e instalação do python3

```bash
sudo apt update
sudo apt install python3
sudo apt install python3-pip
```
- ### Ambos os sistemas
Execute no terminal:

```bash
pip install pygame
```
# Execução
Abra um terminal na pasta raiz onde foram salvos os arquivos do projeto e execute o comando:
```
python3 ./main.py
```
ou 
```
python ./main.py
```

>No Windows, dependendo de como seu sistema está configurado, a execução também pode ser feita abrindo o arquivo ```main.py```.

# Jogabilidade
O jorginho pode ser movimentando usando as teclas W(cima), A(esquerda), S(embaixo) e D(direita) e as teclado direcionais do teclado. O botão ESC retorna para o menu principal e sai do jogo quando já se está no menu principal. 
<br>Cuidado com as paredes!
<br>Divirta-se!

## Sobre o autor
Olá, eu sou o Gustavo Martins Ribeiro, um jovem amante da cultura Reggae com raízes na cultura afro brasileira. Diante disso, é importante ressaltar que a temática escolhida para esse projeto não se refere à apologia às drogas, e sim da apresentação de um jogo com uma temática da cultura Reggae, a qual vem sendo oprimida gradualmente na sociedade atual. Desejo tudo de bom na vida de vocês e um ótimo descanso. Abraço!

![euReggae](https://user-images.githubusercontent.com/72039007/216838141-90b315c3-fcdb-4cb4-ad01-cd24cf96f393.jpg)

## Sobre o coautor

Caetano Santos Lucio.
<br>
[github.com/caeslucio](github.com/caeslucio)
>Se você tem falta de motivação para fazer algo, pode ser que grande parte do impedimento seja medo de não conseguir, medo de investir tempo e esforço em algo que você acredita que não dará certo. Mas olhe esse medo e perceba que você pode ultrapassá-lo e passar a confiar cada vez mais em si. Comece e se permita.
