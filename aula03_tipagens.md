> O QUE SÃO TIPAGENS?

Como vimos na aula anterior, a variável "pais" estava com a typagem em **string**.

Note aqui que **não houve necessidade em momento algum de declararmos que a variável "pais" era do tipo string**.

E essa é uma das grandes vantagens do Python: Fazer parte das **LINGUAGENS DINÂMICAS**, que guardam automaticamente o tipo da variável, sem precisar de várias declarações anteriores.
Isso tem um lado positivo muito bom, mas também há lado negativo.

Por exemplo: vamos voltar à variável "pais".

Você fez o teste anterior e viu que, quando declarou que "pais = Brasil" e usou a função **type()**, a classe que a variável tinha era "String", representada pelo "str".

Agora, experimente colocar "pais = 644", e depois volte a usar a função **type(pais)**, e você verá que a classificação mudou pra 'int', sendo um número inteiro. Percebeu?

![image](https://user-images.githubusercontent.com/86801366/199606550-67a8d6d0-e3a1-4dec-bd2e-ede4b4225e47.png)


Novamente, declare que "pais = 7.9", e use a mesma função **type(pais)**. Apareceu aí "class 'float'"? 

![image](https://user-images.githubusercontent.com/86801366/199606583-7f311f36-b1d5-4fe4-8d20-1d758320705f.png)


Isso é a tipagem dinâmica: A própria linguagem reconhece a variável, sem você precisar declarar qual o tipo. A vantagem é evitar que você tenha a preocupação de declarar tipo por tipo de variável;

a desvantagem, por sua vez, é que se você precisar declarar uma variável com formato atípico (como uma string que tenha um formato numérico, por exemplo), deverá lembrar que o python vai converter pra "int" ou "float", e você terá que fazer o trabalho de declaração.

É bom lembrar que o Python coloca 4 espaçamentos abaixo, quando você insere uma tabulação. É uma forma de ficar organizado, e é padrão do próprio Python.
Para conferir, é só digitar type(variável). Nos exemplos, type(pais) ou type(quantidade)
