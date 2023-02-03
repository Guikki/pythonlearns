Olá! Maravilha te ver por aqui!

a aula de hoje é uma continuação da aula passada. Então, se você ainda não conferiu, é bom ver a aula 09 antes de continuar, ok?

> Break

Como você deve ter notado, fizemos na aula passada o _loop_ do nosso joguinho com o comando **_for_**, juntamente com a função **_range_**

Porém, se você testar o Código, vai ver que mesmo acertando, **o jogo continua** até a última tentativa.

Como é que você acerta o número e ele pede um próximo número? Não faz sentido.

Então, a gente pode voltar ao código, e pedir pra que ele pare e saia do laço quando o usuário acertar. Como temos um trecho do código que é escrito justamente para quando o usuário acerta, já temos aqui uma pista de **onde** colocar o comando de saída do laço, não é verdade?

Pois bem.

Existe um comando chamado **_break_**, que é utilizado quando você deseja parar a condição do código; sair do laço iterativo, seja ele o **_while_** ou o **_for_**

Como a gente só quer que o código pare quando **o usuário acerta**, usamos o **_break_** após o print do acerto, **com a mesma identação dele**, ficando assim:

![image](https://user-images.githubusercontent.com/86801366/216490925-9121b643-9ea6-4e75-bf4e-f7a3293613c7.png)

ou assim:

![image](https://user-images.githubusercontent.com/86801366/216490970-fe377cd2-3529-465c-bcef-c03f9e18afe2.png)

_Tudo depende de você estar usando **for** ou **while**_

Há um outro recurso limitador que também é importante.

Se você testar seu jogo, vai notar que podemos usar números negativos, ou números exorbitantes de tão altos, e o jogo aceitará as entradas mesmo assim.

Seria mais legal se a gente pudesse impedir isso, colocando um limite de chute entre 1 e 100, por exemplo... e nós podemos! (yes, we can!)

Pra isso, devemos fazer **_um novo if_** para cada condição de chute do usuário. Você pode usar a **_função if_** duas vezes (uma para números menores que 1, e outra para números maiores que 100); ou **juntar tudo numa única _função if_**, que precisa de um conectivo: o **_or_**.

a segunda opção é o que eu vou fazer, e por aqui ficou assim:

![image](https://user-images.githubusercontent.com/86801366/216491996-77ff0f86-8206-4808-8408-3f31b1909334.png)

_Eu vou seguir com o código do **for**, mas também serve se você estiver usando o **while**_

Note que há um comando após a **_função if_**, que tem a mesma identação do **_print_**; é o comando **_continue_**, que permite o usuário **continuar no jogo, mesmo inserindo um número fora do solicitado**

Então, nosso querido player que arriscar um número muito baixo ou muito alto, receberá um lindo aviso de número incorreto e perderá uma tentativa.
