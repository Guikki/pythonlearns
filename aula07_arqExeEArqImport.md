>Olá! Estamos na reta final dessa parte inicial dos aprendizados em Python! Aqui, vamos resolver o problema do arquivo executado e importado!

Vimos que só tínhamos acesso ao **advinhacao.py** e o arquivo **forca.py** dentro do **jogos.py**; não sendo possível mais executar a advinhação e a forca de forma independente.

Pra isso, podemos começar colocando a **função jogar()** embaixo do código. Assim, fica:

![image](https://user-images.githubusercontent.com/86801366/223602791-61b03909-f8c8-4080-a48a-906b18c8ba26.png)

_note que ficou fora da identação da função def, ok?_

Só que temos um novo problema ao fazer isso: Agora, usando o **jogos.py** pra acessar o jogo de advinhação, ele já o executa sem o usuário pedir!

Precisamos dosar isso; chamar o jogo da advinhação de forma direta quando a gente quiser, e permitir que o **jogos.py** não te force a jogar advinhação.

Pra isso, quando você roda o arquivo diretamente, o python seta uma variável (ele cria uma variável e a preenche). Assim, podemos perguntar a essa variável se ela está preenchida.

Essa variável se chama **main**, mas a escrita dela é diferente, e ela depende de outra variável para o objetivo que queremos: a variável **name**

Essas variáveis, _ _name_ _ (dois underlines em cada lado, mas são colados). e _ _main_ _ (também com dois underlines, e também colados), é que determinam se o arquivo está sendo executado diretamente, ou inderetamente.

Se __name__ tiver o mesmo valor que __main__, isso mostra que o jogo tá sendo executado diretamente. Neste caso, precisamos usar a função jogar no final do jogo, para ser executado corretamente.

caso a variável _ _name_ _ tenha valor diferente, aí sabemos que precisamos evitar a execução da função **jogar()** ao final do código. 

Logo, **se name for igual a main, usaremos a função jogar**

Fica assim então:

![image](https://user-images.githubusercontent.com/86801366/223603812-e75a8895-15d1-4620-921a-1e4de9674155.png)

_note esse **if** fora da identação da função **def**; e também a função **jogar()** identada, dentro do **if**_

Agora sim, temos nosso jogo funcionando como queremos! Podemos usar a mesma coisa com o jogo da forca, então, pratica aí!

E aqui, nos despedimos dos assunotos iniciais de Python. Este é o fim das minhas anotações sobre o curso básico de python da Alura, pessoal! 

Obrigado por chegar até aqui, e nos vemos nos próximos módulos!
