Olá! que bom te ver de volta! Vamos falar aqui sobre as condicionais, as famosas "if" e "else" no Python

> Como a gente coloca as condicionais em python?

Notou que **SE** a condição for verdadeira (ou seja, **SE** _numero_secreto_ for igual a _chute_), é que teremos o print " **Você acertou!** "?
(uma obsevação: É muito comum programadores falarem da função como se fosse substantivo ou verbo, ok? "Faz um print", "printa isso", "já deu um print?" é muito comum, e será usado aqui de agora em diante)

Pois é. A condição **SE** é traduzida pra língua mãe da programação (o inglês) como **IF**. Por isso, temos uma função com esse nome: **função if**.

E quando você entende isso, é muito simples escrever no código. O meu ficou assim:

![image](https://user-images.githubusercontent.com/86801366/202100433-52bfca86-2d34-4e74-a6b9-67483103f621.png)


Notou que tem dois pontos após o código? Isso implica em dizer que **CASO A CONDIÇÃO SEJA VERDADEIRA**, tudo aquilo abaixo dos dois pontos será executado.

Outra coisa interessante: percebeu a distância da **função print**, abaixo da **função if**? A maioria dos IDEs* modernos já aplicam esse distanciamento, chamado de _identação_. 
É equivalente ao recuo de parágrafo que você precisou fazer no seu TCC em Direito, para estar adequado às normas da ABNT.

Em nosso caso, a linguagem python precisa da identação para entender aonde está cada função. Assim, a **função print** que vamos colocar **embaixo da função if** irá imprimir aquilo **apenas se a condição for satisfeita**
Caso não seja, ela vai pular para o próximo estágio/ próxima função do código.

Após o **if**, precisamos colocar 4 espaços (ou um tab) para realizar a identação correta. Não se perca nisso!

> E o "Se não"?

Para nosso código, nos casos em que a pessoa erre o número, a condição acima não será satisfeita. Dessa forma, o "se não" é usado pela **função else**

**Se** a pessoa acerta; vai imprimir "parabéns! Você acertou!"
**Se não** acerta, vai imprimir "que pena, você errou!".

Então, você escreve o código desse jeito assim:

![image](https://user-images.githubusercontent.com/86801366/202103879-206ed71c-8758-44f9-81e1-37fd3c137b72.png)

Pois agora, vamos verificar rapidinho como tá o Código. Teste seu programa aí no computador e insira o 42 como resposta certa do usuário.
Quando você for realizar os testes, você vai ver que... DEU ERRADO! Exatamente!

_ué? mas como assim "deu errado"?

Deu errado porque, por ser entrada do usuário, nosso querido python recebe como padrão uma variável tipo **string**, ou seja, é uma variável do tipo de letras e palavras.

Mas, você viu nas aulas passadas que, no momento em que colocamos **numero_secreto = 42**, o Python faz a tipagem automática para uma variável do tipo **inteiro**.

Dessa forma, nosso programa até o momento tá comparando "stg = int". Por isso que tá dando errado!

E como você deve imaginar, há uma forma de consertarmos isso... há até mais!

Uma delas é você **declarar uma segunda variável**, e dizer que ela é aquilo que o usuário inseriu, 
mas do tipo inteiro (ou, como programadores falam, "é um input int/ é um int input"), ficando assim:

![image](https://user-images.githubusercontent.com/86801366/202104740-80bf399b-5d98-47b4-959d-87d8f99e3a07.png)

Uma outra forma é você juntar os dois, fazendo com que a **input** já chegue como **int**. Assim, fica dessa forma:

![image](https://user-images.githubusercontent.com/86801366/202105451-0f6cd615-1ee1-47d0-965b-50667b07315f.png)

perceba como aqui, é como se **dentro da função int, eu colocasse a função input**. Assim, dali em diante, já chega considerando que a input será um número inteiro

No final, na mesma linha vertical do else, crie uma função print pra encerrar o jogo. Combinado? 

![image](https://user-images.githubusercontent.com/86801366/202106485-f5225136-7993-4d96-9353-c9eb5ee246af.png)

E só de lembrete, vou te avisar aqui: Também existe uma forma de você unir **if** e **else** num comando só.

_Pareceu confuso? Vamos explicar devagar então._

**AS VEZES** você pode precisar usar uma condição dentro da condição. E é nessas horas que existe o **elif**, que nada prática, nada mais é do que um **if** dentro de um **else**.

Vamos voltar ao nosso exemplo: Você tem o número secreto, e o chute. Caso o chute seja igual ao número secreto, temos o uso do **if** já colocado aí em cima;

Quando a condição não é satisfeita (ou seja, quando o número secreto é diferente do chute), temos o **else** ali pra isso.

Mas note que **dentro do ELSE, podemos colocar uma outra condição**. Assim, seria uma forma de você não identar novamente o if dentro de um novo else; pra isso serve o **ELIF**.

![image](https://user-images.githubusercontent.com/86801366/210686598-da8aed10-e501-4564-8477-93cf91951b71.png)


_Cara, fala sério! Um else ali e já tava resolvido!_

Sim, **NESTE CASO**, de fato. Mas pense pelo lado positivo: Você acaba de aprender um recurso novo, que pode ser útil em seu futuro! =]

Nos vemos no próximo material!

* *IDE = Integrated Development Environment, ou ambiente de desenvolvimento integrado. São programas que você usa para escrever seu código. Mais detalhes, pode acessar esse link aqui: https://www.alura.com.br/artigos/o-que-e-uma-ide
