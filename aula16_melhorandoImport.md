>Bom demais te ver aqui de novo! Vamos direto pra aula? Esta aqui é continuação direta da aula 15

Vimos na aula anterior que a função import tem um papel imenso, mas estamos executando os 2 jogos ao mesmo tempo. Como melhorar isso?

Pra isso, precisamos executar uma função que chame o jogo na hora desejada (algo parecido com o que fazemos constantemente com a função print: A gente só pede pra imprimir no momento desejado.

Aí, podemos fazer algo assim:

![image](https://user-images.githubusercontent.com/86801366/223599602-02b4c134-36ab-4c5b-85d4-48e49876f78b.png)

Só que note: Não temos uma função definida ainda, temos apenas o nome.

Precisamos então transformar o jogo em uma função (ou colocar o jogo dentro de uma função). Pra isso, iremos **definir uma função** para colocar o conteúdo do jogo dentro dela.

Pra isso, em Python, existe o comando **def**. Iremos então usar o def pra definir uma função (com o nome anterior: "jogar_forca"/"jogar_advinhacao"), e colocar todo o conteúdo dos jogos em seu respectivo def.

Começando pela forca, ficaremos assim:

![image](https://user-images.githubusercontent.com/86801366/223600637-5913e2e5-10b6-41c8-a594-96fae8d4c784.png)

_notou a identação que o def exige? Tudo dentro da identação será chamado na função._

O mesmo serve pra advinhação, ficando:

![image](https://user-images.githubusercontent.com/86801366/223600575-e3dd07d7-7e0a-4c74-b7ea-00dec4676b24.png)

_O nome da função def está apenas como jogar, você vai entender já já o porquê_

E agora, é só colocar isso na função. Vimos anteriormente onde colocaremos a função de jogar forca, e a função de jogar advinhação, correto?

Só que, pra usar o **import**, precisamos chamar o módulo e o nome da função. Por isso, podemos usar apenas o módulo pra orientar qual jogo será executado; isso remove a necessidade de repetir dentro da função qual jogo será executado.

Não entendeu não? Então vamos por partes:

1 - o comando **import** lá em cima chama um módulo: **import advinhcacao** chama o módulo **advinhacao**, e **import forca** chama o módulo **forca**
2- Usamos no módulo o mesmo nome do jogo pra facilitar a organização e intuitividade de nosso código.
3 - Assim, como o módulo tem o nome do jogo, podemos usar apenas o módulo pra nos orientar de qual função está sendo chamada.
4 - Como dentro do jogo **forca.py** temos a função **def jogar()**; e dentro do jogo **advinhacao.py** temos a função **def jogar()**, iremos usar estas funções no nosso arquivo **jogos.py**
5 - Dessa forma, ficará assim o uso dos módulos do import:

![image](https://user-images.githubusercontent.com/86801366/223601538-4eaacb2d-783d-4b65-aa40-72564a832c2f.png)

_Agora ficou mais claro?_

Só que isso gera um probleminha também: Só posso acessar os jogos **advinhacao.py** e **forca.py** por dentro do **jogos.py**

Como resolver isso? Ahhh! Material pra próxima aula!
