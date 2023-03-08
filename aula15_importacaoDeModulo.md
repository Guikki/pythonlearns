>Como é bom te ver aqui novamente! Nessa aula, veremos o início de como adicionar uma nova opção de jogo ao nosso programa!

Como já acompanhamos até o momento, nosso jogo de advinhação de número está bem desenvolvido (inclusive, já dá pra você jogar e eu achei bem divertido tentar advinhar o número randômico que o jogo escolhe!)

Porém, aqui, vamos começar a aprender como podemos desenvolver um programa com 2 jogos: Um jogo sendo o da forca, e o outro, esse de advinhar o número.

Pra isso, precisamos fazer 2 arquivos: Um com o jogo de advinhação, e outro com o jogo de forca. Um bom começo é colocar o nome dos arquivos de forma bem intuitiva, como "advinhacao.py" e "forca.py"

além disso, precisaremos de uma aplicação que irá importar esses módulos, a depender da escolha do usuário. Este, eu vou criar e dar o nome de "jogos.py".

Então, temos 3 arquivos: "advinhacao.py", "forca.py" e "jogos.py"

Após isso, pode usar o cabeçalho com 3 funções print que usamos no jogo inicial nos outros 2 arquivos, ficando algo assim:

![image](https://user-images.githubusercontent.com/86801366/223597215-5eda3406-31c8-44ee-9a3c-f12204b685c9.png)

_esse é nosso forca.py_

![image](https://user-images.githubusercontent.com/86801366/223597275-4ea3c495-5521-4304-977a-e7b6a032b8f9.png)

_Aqui é nosso jogos.py_

Após esse procedimento, iremos explicar ao usuário as entradas, e colocaremos que se o input for igual a 1, o jogo será o da forca; mas se o input for igual a 2, o jogo será o da advinhação.

Em uma nova etapa, iremos usar o que aprendemos sobre **if/elif/else** pra fazer um menu bem rústico sobre a orientação aos jogos. É uma boa hora pra exercitar o que já aprendemos!

![image](https://user-images.githubusercontent.com/86801366/223597722-7b61d544-593b-4aef-9187-75ee42b48af0.png)

_certo. ok. Mas e como iremos colocar os jogos que construímos dentro dessa aplicação?_

Pra isso, usaremos o import lá em cima, e colocaremos **o nome dos arquivos .py que construímos!** Vai ficar assim:

![image](https://user-images.githubusercontent.com/86801366/223597772-b1fe3673-76b9-456e-b5c7-06e27b652cbe.png)

Mas, do jeito que tá aqui, teremos um problema: **As duas aplicações serão executadas**, independente do que o usuário escolha.

E nós não queremos isso. O que queremos, é que ao usuário escolher o jogo desejado, **ele seja direcionado apenas a este jogo!** Mas isso é material pra próxima aula, até lá!
