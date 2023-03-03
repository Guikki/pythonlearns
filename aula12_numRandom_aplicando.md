> Aqui é uma continuação da aula 11, onde iremos aplicar a função random em nosso jogo.

     MAS ONDE IREMOS COLOCAR A FUNÇÃO RANDOM?

Como queremos que o número seja aleatório, e temos uma variável pra o número, o ideal é armazenamos nesta variável o nosso número aleatório. 

O primeiro passo, é **importar a função random**, ficando:

![image](https://user-images.githubusercontent.com/86801366/222607870-14dff057-2b86-4d65-af41-e2a2b6f70511.png)

Então, queremos que a variável **numero_secreto** seja randômica; logo, ela será igual a função random. Assim, teremos:

![image](https://user-images.githubusercontent.com/86801366/222607418-ae5e0e6b-c1b3-46d4-a77b-af38a4c390ac.png)

Só que precisamos de um número entre 1 e 100; e essa função só nos dá números entre 0 e 1. Assim, precisamos multiplica-la por 100! Dessa forma:

![image](https://user-images.githubusercontent.com/86801366/222607545-4551df7a-5b8a-4dcc-8545-6167fa310ed6.png)

Mas ainda temos um problema: As casas decimais! Na aula passada, vimos que podemos resolve usando a **função int** ou a **função round**; eu vou usar a **round** aqui. E assim, ficou:

![image](https://user-images.githubusercontent.com/86801366/222607643-c5df7e7a-556b-46ae-a129-7c9256395097.png)

e no final, teremos um "cabeçalho" de código assim:

![image](https://user-images.githubusercontent.com/86801366/222607941-30239115-af8f-4be5-bf14-a549742d4cf3.png)

Parece funcionar. Testa aí e me diz como ficou! 

Uma dica: Apenas para TESTAR, use uma função print com a variável no número secreto, abaixo de onde vocÊ declara o número de tentativas; e veja se o código tá funcionando direitinho (ou tente advinhar com 3 tentativas! hahahahaha!)

> Beleza! O código bruto desse problema tá pronto! Só que, parafraseando o jogador Richarlison, "I speak python, my friend!"

O python tem uma função que nos dá exatamente o que precisamos. Está no link das bibliotecas que vimos na aula passada; é a função **randrange()**

Essa função nos dá números inteiros dentro do intervalo que definirmos dentro do parênteses dela. Então, podemos substituir todo o "**round(random.random()) * 100**" por um "random.randrange(1,101)".

![image](https://user-images.githubusercontent.com/86801366/222608940-6b812f18-fa92-4ad5-8ccb-75409757faad.png)

lembrando que o último termo é excluído da função; se você colocar randrange(1,100), ele vai usar os números de 1 a 99. Essa solução daqui também elimina a rara ocasião de termos um número igual a 0 na variável **numero_secreto**
