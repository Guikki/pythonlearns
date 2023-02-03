Olá! Que bom te ver aqui de novo!

Dando sequência nas anotações, agora vamos falar sobre o laço _while_

> **_lAÇO WHILE_**

Incrementando nosso jogo, seria mais divertido termos uma quantidade de tentativas para repetir, usando as respostas anteriores para nos guiar, não acha?

Mas como fazer isso em nosso código? É nesses momentos que uma das saídas é o _laço while_

O _while_ serve para o código ser reproduzido sucessivamente, dentro de uma condição. Então, _enquanto_ aquilo estiver ocorrendo, vamos repetir o código (ou parte dele).

Entendeu? Ainda não? Vamos de exemplo, que fica mais fácil!

Primeiro, vamos colocar uma nova variável, pra simbolizar o **número de tentativas** que nosso jogador/usuário poderá ter.

Vou chamar de _**numero_de_tentativas**_ (criativo, não?); e vou colocar aqui um total de três, ficando:

![image](https://user-images.githubusercontent.com/86801366/215885000-2bc7175d-e68f-4c30-b98b-2871c022764f.png)

aí, após isso, vamos escrever o **_laço while_**. Ele age como uma função, então, não esqueça o parênteses e os dois pontos depois, ok? 

Dentro do _while_, vamos colocar nossa variável nova, e escrever que a condição é essa variável ser **maior que zero**. Vamos com calma, que lá na frente tudo fará sentido.

Assim, a condição fica:

![image](https://user-images.githubusercontent.com/86801366/215885332-3ec2d166-0445-4ddb-b747-5e3997953868.png)

Percebeu, né? **Todo o código foi colocado dentro do _WHILE_** (e observe bem que há uma identação importantíssima aí. É só selecionar todo o código abaixo do _while_ e apertar tab).

Porém, da forma como tá escrito até agora, a condição **sempre será satisfeita**, afinal a nossa variável _numero_de_tentativas_ não está mudando em nada.

Por isso, no final, nós iremos mudar isso. Lembra que eu falei que ia fazer sentido? Poooois é! 

Agora, após o **_Elif_**, a gente pode colocar uma nova declaração que muda o número de tentativas. Para isso, vamos declarar que a variável _numero_de_tentativas_ vai ganhar um novo valor.

E que valor seria esse? Será o valor da variável _numero_de_tentativas_ -1.

Assim, a variável **_numero_de_tentativas_** vai chegar ao final do **_while_**; vamos subtrair 1 dela, e ela sobe pra o começo do **_while_** com um novo valor! Deu pra entender, né? Olha só!

![image](https://user-images.githubusercontent.com/86801366/215886689-fd16b6d4-253f-49f6-8ecd-380b70259c3d.png)

Para a gente dar uma conferida, vamos usar a **_função print_** falada nas aulas passadas, e colocar pra sabermos quantas tentativas temos. É só colocar isso aqui:

![image](https://user-images.githubusercontent.com/86801366/215896957-5d8cb0c0-1936-4b0e-930e-195c1f9435de.png)

Existem outras formas de você fazer essa saída. Vamos a elas?

Uma alternativa é você falar o número da tentativa, e em seguida a variável. Para isso, podemos criar uma variável para as rodadas.

Só que aí, se você fizer só isso, o programa vai manter a variável **_rodadas_** intacta; e a variável **_numero_de_tentativas_** vai continuar mudando.

logo, precisaremos mudar isso lá embaixo, colocando a incrementação do _while_ na variável **_rodadas_**; não mais em **_numero_de_tentativas_**, ficando assim:

![image](https://user-images.githubusercontent.com/86801366/215923269-ec108131-f283-4944-9e48-dc5249db7790.png)

Perceba que o **_print_** também mudou sua expressão; e rodadas agora é algo printado. Além disso, a variável **rodadas** deve ser **menor ou igual** ao número de tentativas, correto?

Então... em Python, o símbolo de "menor ou igual" é **_<=_**
