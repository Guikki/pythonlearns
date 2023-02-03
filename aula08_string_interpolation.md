Olá! É bom te ver aqui de novo!

Dessa vez, vamos continuar diretão da aula 7. 

Há uma forma mais interessante de imprimir as variáveis que colocamos. É pra isso que servem as **_formatações de strings_**

Podemos colocar, ao invés da declaração de cada variável, um símbolo de chaves {}. Lembrando que _String_ é o tipo de variável que é inserida por palavras. Lembra da aulinha de tipos de variáveis? (booleana, inteira etc?)

Enfim. Podemos inicialmente colocar o símbolo de chaves para demonstrar que as strings entrarão ali, naqueles espaços.

depois disso, a gente usa a função **_.format()_** e declarar as variáveis na ordem das chaves. Assim, nosso exemplo fica:

![image](https://user-images.githubusercontent.com/86801366/216492900-231980f9-c0f5-498c-87eb-9f79adb2edf9.png)


O nome disso é **_INTERPOLAÇÃO DE STRING_** (String Interpolation); um recurso para as substituições.

> **Conteudo complementar - lições extras**

Mas o **_.format_** não para por aqui não.

Caso você queira inverter o parâmetro, é possível de fazer também nessa função. Basta você colocar os números da posição do parâmetro.

Num exemplo onde queremos preencher o **_.format_** com os números 3, e 10, podemos fazer assim:

![image](https://user-images.githubusercontent.com/86801366/216493360-a55a5822-1bd0-47a2-8997-007040890117.png)

E com a alteração de parâmetro, é só **preencher as chaves com o número do parâmetro desejado**

![image](https://user-images.githubusercontent.com/86801366/216493394-51cdca2f-1b23-4ae5-ba6b-340eb6b4edb1.png)

_lembre que em programação, é bem comum o primeiro parâmetro ser o parâmetro nº 0, e não o número 1._

Caso você queira uma formatação diferente, mais padrozinada, isso também é possível com a função **_.format_**. Pense que você está responsável por escrever um código relacionado aos preços dos produtos de uma loja, como exemplo.

Aí você precisa organizar a tabela de preços, e quando escreve seu código, ele imprime assim:

![image](https://user-images.githubusercontent.com/86801366/216494167-3dbc5995-3666-4154-b33e-31cbcfdefec7.png)

_percebeu como os números estão desalinhados?_

Para alinhar, não é tãããão complicado assim.

Primeiro, a gente precisa mostrar pra função que está recebendo um número em tipagem **float**. Pra isso, escrevemos o comando:

![image](https://user-images.githubusercontent.com/86801366/216494557-1e946688-13aa-4529-85f3-43fa42c68d8f.png)

Perceba que a formatação já mudou aqui. E nós ainda podemos alterar mais

Podemos definir as regras aqui, dizendo quantos números vêm antes e quantos números vêm depois do ponto (que separa o real dos centavos). Para isso, usamos um ponto após os dois pontos; e um número após esse ponto, pra definir quantas casas dos centavos nós teremos:

![image](https://user-images.githubusercontent.com/86801366/216495034-8c5e0301-a5e3-4947-88c9-3075ca3baf43.png)


A ideia aqui é que a impressão dos preços fique alinhada por este ponto de separação, assim:

![image](https://user-images.githubusercontent.com/86801366/216494852-d1d6febb-774a-4d87-99cd-47a7244abcbc.png)

Só que pra chegar nisso de uma maneira prática, precisamos também alinhar quantos caracteres virão antes do ponto. Já sabemos que um número após o ponto isolado ali dentro da função, indica quantas casas decimais teremos (ou quantos centavos teremos na nossa tabela); então é só colocar à esquerda do ponto isolado { [entre os dois pontos (:) e o ponto (.)] } a quantidade de números não decimais, correspondentes aos reais, correto?

Errado!

Nesta posição, colocaremos **_a quantidade total de caracteres_**. Então, se eu quero uma tabela onde hajam 4 pontos pra serem o real; o quinto caractere seja o ponto que separa o real dos centavos; e os dois últimos caracteres sejam os centavos... eu escrevo assim:

Perceba: 7 caracteres no total; 2 caracteres destes serão após o ponto decimal. 

Pareceu até difícil, mas agora faz sentido, não é?

Então, de 7 números no total, sabemos que os dois últimos serão correspondentes aos nossos centavos. Antes dos centavos, sempre temos o ponto decimal; e tudo que vem antes disso é correspondente ao real. Aí fica assim

![image](https://user-images.githubusercontent.com/86801366/216495915-0f1ecf87-3924-4481-9fda-ec956f309445.png)

Ficou legal, mas ainda pode melhorar mais. Colocando zeros (0) à esquerda dos números correspondentes aos reais, teremos uma impressão mais visível das casas a serem preenchidas pelo programa.

pra isso, basta usar o 0 antes do indicativo de caracteres; à direita dos dois pontos. Ficando assim.

![image](https://user-images.githubusercontent.com/86801366/216496291-02225045-38d5-4492-a9a1-26be51aa240c.png)

_Um exemplo com 7 caracteres, dois deles pra centavos; e um exemplo com 8 caracteres, três deles pra centavos_

Esse comando serve não apenas para variáveis do tipo **float**; também serve para números inteiros.

Por alguma razão, os criadores do Python convencionaram o comando pra números inteiros um **d**, de dígito, como representativo (e não um **i**, de inteiro, que seria mais intuitivo. Vai entender...)

![image](https://user-images.githubusercontent.com/86801366/216496812-fa1d1bc9-0bb8-47b6-b568-12c64b5deb75.png)

_nos dois casos, há 7 dígitos_

Também é bom lembrar que, se seu número já preencher a quantidade de casas, não haverá auto preenchimento com 0. Veja nesse exemplo, com datas.

![image](https://user-images.githubusercontent.com/86801366/216497079-54f298fa-f9eb-4769-ae61-a5e6eaa63f9e.png)

_Só tem 0 preenchendo quando a data é um número único; quando já tem 2 números na data, a condição é satisfeita, não há preenchimento com 0_

Eu reconheço que há muita informação aqui. Então, é importante lembrar que o mais valioso é você **saber da existência disso**. Há uma vasta gama de materiais pela internet que informam como usar cada instrução aqui (incluindo este que você tá lendo agora). 

Quando a dúvida bater, não se preocupe: Pesquisar pela internet pra dar uma lembrada é sempre útil!


