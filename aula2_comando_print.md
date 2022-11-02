  **Olá! Que bom te ver aqui de volta!**

> Agora, iremos tratar Sobre o comando **print**

Este é o comando que você utiliza pra fazer o programa imprimir algo. Como ele é uma **função**, já sabe que o comando vem com parênteses após, lembra?

- E você sabia que há um comando de ajuda na função print?

Para isso, basta digitar a função **help()** que você verá um menu sobre isso. 

![image](https://user-images.githubusercontent.com/86801366/199402734-50865aa6-adaf-4ce2-822d-02a62a133078.png)

Após abrir o **help()**, você notará que aparecerá uma caixa de código chamada **help>** para você digitar.

Quando você digita **print** ali, vai conseguir abrir uma série de instruções de ajuda sobre o comando de impressão. 

-- Então, o sistema Python irá te mostrar que ele consegue imprimir **value**, e após isso reticências mostrarão que vários valores podem ser impressos;

-- Mostrar o **sep=' '**, que se você quiser separar valores, basta abrir um espaço; 

-- Mostrará também o **end= '\n'**, pra dizer que se você quiser finalizar, digite **\n** (\n significa uma nova linha).

Também diz onde o print deve imprimir (o padrão é definir as impressões no console).

O comando **q** já é o suficiente para você sair da caixa de ajuda, e voltar ao interpretador de python

Brincando um pouco com os comandos que vimos, temos:
![image](https://user-images.githubusercontent.com/86801366/146873756-1d3f4c55-95cf-4805-b49b-ab7c3718571c.png)

Note aqui que: 

-- Na primeira linha, temos a impressão comum, que vimos com o "Olá mundo!"

-- Na segunda linha de código, temos um comando novo, o **sep=" "**. Mas ele não alterou nada! A razão disso, é que escrevemos "Brasil ganhou 5 títulos mundiais" como uma coisa só, não existindo então nenhum elemento a ser separado de outro. Entendeu? Para todos os efeitos, temos um único elemento, e por isso, não há separação.

-- Já na terceira linha, temos 5 valores: o valor "Brasil", um outro "ganhou", outro "5", outro "títulos" e, por fim, "mundiais" é um novo valor. 

Com esses 5 vales, temos 4 espaços de separação. Assim, como estabelecemos que o separador **sep="-"** será igual ao hífen, temos os 5 valores separados por hífen! Legal, né?

Se você quiser dar uma incrementada, coloca um **end=""** e note que não haverá outra linha; seu código terminará aí, ficando assim:
![image](https://user-images.githubusercontent.com/86801366/199403971-64c85027-2944-4a11-9721-8fad7952fd50.png)


E se eu quiser mudar o país e os títulos? Existe uma opção que permite uma flexibilidade maior na frase impressa. Vamos ver isso?

Primeiro, é necessário inserir variável. Vamos iniciar inserindo na variável **pais** e em seguida, vamos guardar nela a string **Itália**. para isso, precisamos escrever pais = "Italia"

Pra confirmar, vale digitar **type(pais)**, e você deve ter de retorno **class 'str'**, que sinaliza que você inseriu na variável uma string, ou seja, um conjunto de letras; uma palavra.

![image](https://user-images.githubusercontent.com/86801366/199404367-32ead300-c053-4040-98e0-aff734a4c3c9.png)


depois, vamos inserir a variável **quantidade**, o valor **4** (NOTE QUE ESTÁ SEM ASPAS), e determinar que **quantidade = 4**. Dando o comando **type(quantidade)**, você verá que dessa vez, o tipo da variável é inteira, ou seja, um número inteiro, não flutuante (sem casas decimais).

![image](https://user-images.githubusercontent.com/86801366/199404627-80cc49f0-8b49-4ece-91a3-e605d68d3ce4.png)

Após isso, você pode escrever o comando da função print com as variáveis declaradas, que ficará:

print (pais, "ganhou", quantidade, "títulos mundiais"), e ver que a impressão sairá correta. Percebeu também que as variáveis declaradas **NÃO POSSUEM ASPAS**? Esta é a razão: Em Python, quando você digita algo na **função print** com aspas, o seu computador irá entender que você está querendo imprimir exatamente aquilo que está entre as aspas; quando você não coloca as aspas, o seu computador lerá que você deseja **imprimir as variáveis**, e você precisará ter declarado alguma variável pra o programa ser executado corretamente.

![image](https://user-images.githubusercontent.com/86801366/199405078-0d2dac03-4c29-4446-af75-055f07dd1001.png)


> Observação!
É bom lembrar que o Python coloca 4 espaçamentos abaixo, quando você insere uma tabulação. É uma forma de ficar organizado, e é padrão do próprio Python.
Para conferir, é só digitar type(variável). Nos exemplos, type(pais) ou type(quantidade)
