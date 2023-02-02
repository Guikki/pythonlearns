Olá! Como é bom te ver aqui de novo! Chegamos a nona aula, ainda falando sobre loop

Como vimos na aula 8, um dos caminhos é usarmos o **_while_** para criar o loop (aquele ciclo de repetição do código).

Pois agora vamos aprender um novo laço iterário, o **_for_**.

> For

Para o **_For_**, a ideia é que você defina com qual valor começar, e até qual valor você quer ir. Por isso, é muito comum que o **_for_** acompanhe a função **_range_**

Então, se eu quero tentar, por exemplo, de 1 a 10, eu chamo o **_for_** e a função **_range_**. Como exemplo, faça um teste simples: Digite

![image](https://user-images.githubusercontent.com/86801366/216461685-2acb9ae5-84f2-4422-bd1a-73a621b59f40.png)

e veja se sua impressão também não sai assim:

![image](https://user-images.githubusercontent.com/86801366/216461747-accab8bd-59c4-487c-b6b8-6ad505edce6c.png)

_note que o 10 não tá incluso na sequência; mas o 1 está_

Essa função **_range_** também permite pular elementos em sequência. Aí é só adicionar um novo número no parêntese da função, com vírgula, ficando assim:

![image](https://user-images.githubusercontent.com/86801366/216462354-77bed0c6-64a0-45a9-acb1-7d22d5de7228.png)

E a sequência fica assim:

![image](https://user-images.githubusercontent.com/86801366/216462435-e62642a0-d47a-4222-a170-aab8a0f39e07.png)

_Porque pulou de 2 em 2 (já que 2 é o último elemento), e seguiu o mesmo alcance da sequência anterior_

Também vale você colocar o **_for_** sem o **_range_**. Mas aí, você tem que colocar cada elemento, ficando assim:

![image](https://user-images.githubusercontent.com/86801366/216462923-4750ecdb-69bd-484f-86fc-0dc845e5be22.png)

![image](https://user-images.githubusercontent.com/86801366/216462974-644d1a39-0f13-4ce2-9bc4-9e49fbd3bae2.png)

> Voltando ao jogo:

Podemos usar o **_for_** pra substituir o **_while_**. O **_for_** não precisa de parêntese, mas pode usar se quiser.

Para isso, vamos mudar um pouco, começando o laço no 1 e indo até o total de tentaivas.

A vantagem do **_for_** é incrementar a variável sozinho; assim, podemos apagar o **_rodada = rodada + 1_** ao final do código. Fica assim:

![image](https://user-images.githubusercontent.com/86801366/216463827-68fa483e-6227-41f5-86f8-2c123ef32458.png)

_Mas você lembra que o for exclui o último elemento?_

Mantendo o código assim, estamos dando ao usuário apenas 2 tentativas, e não 3. Pra isso, uma das soluções é adicionar +1 na variável dentro do _**range**_. Ficando assim:

![image](https://user-images.githubusercontent.com/86801366/216464159-8e7a3feb-2f25-4b9d-aeed-ba6f49872bc7.png)

Pois bem! Aprendemos um pouco do **_for_** aqui. Te vejo na próxima aula!
