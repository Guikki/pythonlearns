> Olá! Que bom te ver aqui de novo! Caramba, 11 aulas hein? Hoje, vamos aprender como gerar números aleatórios.

Nosso número secreto hoje está estático. Então, para mudarmos isso, vamos usar um dos melhores amigos de qualquer programador: o google!

Uma rápida pesquisa em "python random" e já apareceu pra mim esse link aqui:
https://docs.python.org/3/library/random.html

É muito importante sabermos que as bibliotecas da linguagem de programação estão disponíveis em vários textos pela web. Isso inclui o Python.

Fora isso, existem também explicações das "bibliotecas" que já são integradas dentro do Python. Vamos dar uma olhada nisso:

     FUNÇÕES BUILT IN
Funções _Built in_ são funções já imbutidas dentro do Python. Estas funções existem desde o momento da instalação do programa, então, você não precisa se preocupar em instalar.

É o caso das funções **print** e **int**, que já vêem integradas ao programa.

![image](https://user-images.githubusercontent.com/86801366/222531560-34505f08-1f2f-4ed0-8382-adf5010a3f43.png)

Aqui temos uma lista das funções Built in:

https://docs.python.org/3/library/functions.html

      FUNÇÕES IMPORTÁVEIS
Porém, existem funções que vêem em módulo separado. Elas não são instaladas junto com a própria linguagem de programação, elas requerem que o programador realize uma **_IMPORTAÇÃO DA BIBLIOTECA/IMPORTAÇÃO DA FUNÇÃO_**

Assim, pode ser usada normalmente, mas depende da conveniência do programador, que precisa instalar antes do uso para ter o comando reconhecido. É o caso da **função Random**, que se vocÊ não importar, aparece assim:

![image](https://user-images.githubusercontent.com/86801366/222531676-9d5bf885-b348-4760-ac26-ef121aebfd35.png)

Pra isso, precisamos usar o comando _**Import random**_, e aí sim poderemos utilizar a função tranquilamente.

![image](https://user-images.githubusercontent.com/86801366/222532181-e6a65ba8-0c2a-440f-aa1c-d1191644daab.png)

Porém, na importação da função Random, chegam números quebrados, entre 0 e 1, e com muitas casas decimais... assim:

![image](https://user-images.githubusercontent.com/86801366/222537620-852aa81e-91bf-4c17-8935-5a553f978ee8.png)

Como fazer então para melhorar isso? 

Primeiro, nosso jogo pede números entre 1 e 100; então, uma solução já é multiplicar esses números quebrados que chegam pela função random, por 100.

Assim, já temos uma pequena melhora nos resultados, ficando:

![image](https://user-images.githubusercontent.com/86801366/222537827-6289f8e9-6daf-4003-8f32-3cfb3f8e9d84.png)

Só que ainda temos muitas casas decimais aqui. Então, como proceder?

Uma primeira solução é transformar a função random em uma variável. E depois, usar a **função INT** para transformar essa variável em número inteiro.

A Função int apenas corta os números decimais; tudo após o ponto.

Assim, teremos que:

![image](https://user-images.githubusercontent.com/86801366/222538403-0747d9d5-fa5e-4184-b71e-bc701ac035cf.png)

Além disso, nós também podemos arredondar o número. Para isso, temos uma função que é **_built in_**, chamada **round**

Assim, temos um exemplo, usando as duas formas:

![image](https://user-images.githubusercontent.com/86801366/222538764-3d8a4795-44d6-4d70-9c1c-8505246666b2.png)

>Note que a função INT faz o número random ser **38**; e a função ROUND faz o número random ser **39**!


