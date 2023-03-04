>Olá! Chegamos a mais um capítulo desse conteúdo! Já percebeu o quanto foi aprendido até aqui? Hoje, veremos uma forma de fazer uma pontuação pra quem tá jogando.

O primeiro passo é definir uma pontuação inicial. Vamos começar colocando 1000 pontos, lá em cima, ficando:

Após isso, vamos definir um sistema de pontos. A linha de raciocínio de proximidade do chute parece interessante em uma primeira vista, então, vou usar essa.

Quem chutar mais perto, perde menos pontos de quem chutar mais distante. Então, precisaremos de uma variável nova pra calcular esses pontos

Vou chamar essa variável de **pontos_perdidos**, e defini-la como sendo **numero_secreto - chute**, ficando:

![image](https://user-images.githubusercontent.com/86801366/222869718-18b823a5-0ba1-419d-b610-10275c71e9e3.png)

Perceba que no final, a gente coloca um novo valor na variável **pontos**, definindo-a como sendo **pontos - pontos_perdidos**.

Entendendo variáveis como espaços de armazenamento de valor, fica fácil entender por que estamos repetindo; estamos colocando um novo valor no espaço que antes já tinha o valor.

Dessa forma, o espaço anterior que preenchia a variável **pontos**, e era igual ao número 1000, será repreenchido por um novo valor; e este novo valor será os 1000 anteriores, subtraído do total que estiver acumulado na variável **pontos_perdidos**. Agora ficou mais tranquilo entender?

Só que temos um problema aqui: E se o chute for maior que o número? Um **numero_secreto = 60**, e um **chute = 80**, fará um valor de **numero_secreto - chute = 60 - 80 = -20**.

E não dá pra termos um número negativo aqui; precisamos do **NÚMERO ABSOLUTO**, ou seja, o módulo, a distância entre o chute e o número secreto; o número bruto, sem sinal.

E mais uma vez, voltamos a parafrasear Richarlisson: _We speak python, my friend!_

Em python, existe uma função chamada **abs**, e iremos utiliza-la pra chegar nesse resultado, colocando nossa subtração dentro dela. Assim, teremos:

![image](https://user-images.githubusercontent.com/86801366/222869996-18d85263-8de7-41ae-a9e5-528117de97d5.png)

_Olha a função built in aí de novo_

Finalizando essa aula, temos que mostrar pro usuário a pontuação dele, né? E como fazer isso? Simples! Voltamos à Interpolação de strings!

Aí, fazendo aqui, ficou assim:

![image](https://user-images.githubusercontent.com/86801366/222870351-5f3074d6-4383-4d19-98b6-59bf7bb4055e.png)

Dá uma conferida, que o joguinho tá ficando bem legal! Até a próxima anotação! 
