Aulas de Python - **Alura**
anotações sobre as aulas de Python do curso . Disponível em: https://cursos.alura.com.br/course/python-introducao-a-linguagem/task/22687

Realizei o download da versão **3.10.7** em https://www.python.org/downloads/

Como eu estou aprendendo isso aqui no windows, as instruções aqui são pra esse sistema operacional, ok?

O primeiro passo é instalar o Python no site mostrado aí acima.

Depois, vale checar se o python foi corretamente instalado

Pra isso, comece abrindo o prompt de comando (atalho: tecla windows + R).

para executar, o comando já é escrever **python** aí no terminal mesmo.

Para saber a versão do Python que você está executando, escreva no prompt de comando **python -v** (mas vale lembrar que a própria execução no passo anterior informa a versão, entre outras coisas)

O sinal que você fez certo é aparecer o símbolo **>>>** já em outra linha. Isso significa que o Python já está rodando em seu computador.

O mais legal aqui é que você pode escrever diretamente no Prompt de comando, no VSC (ou outro IDE que você prefira), e também executando o IDLE que é instalado junto com o próprio Python.

>> mas Gui, e se eu não quiser nem instalar nada... dá pra escrever código em Python?

E a resposta é: **SIM**

Existem programas como o **Repl.it** (disponível em: https://replit.com/ clicka em "start coding" e faz do seu jeitinho) que permitem você escrever o código sem instalar nada. 

A experiência não se compara a de você ter um programa local rodando Python, e aplicações mais sofisticadas exigirão o Python instalado em sua máquina; mas dá sim pra escrever códigos por ele!


Então, escolha a forma de sua preferência, e vamos nessa!

Para abrir o menu de ajuda, use o comando **help()**

Aqui, vai abrir uma caixa de dicas para que você entenda um pouco mais sobre o Python.

> Sobre o comando print

Após abrir o **help()**, você notará que aparecerá uma caixa de código chamada **help>** para você digitar.
Quando você digita **print** ali, vai conseguir abrir uma série de instruções de ajuda sobre o comando de impressão. 

Então, o sistema Python irá te mostrar que ele consegue imprimir **value**, e após isso reticências mostrarão que vários valores podem ser impressos; Mostrar o **sep=' '**, que se você quiser separar valores, basta abrir um espaço; mostrará também o **end= '\n'**, pra dizer que se você quiser finalizar, digite **\n** (\n significa uma nova linha).

Também diz onde o print deve imprimir (o padrão é definir as impressões no console.

O comando **q** já é o suficiente para você sair da caixa de ajuda, e voltar ao interpretador de python

Brincando um pouco com os comandos que vimos, temos:
![image](https://user-images.githubusercontent.com/86801366/146873756-1d3f4c55-95cf-4805-b49b-ab7c3718571c.png)

E se eu quiser mudar o país e os títulos?
primeiro, é necessário inserir variável. Vamos iniciar inserindo na variável **pais** a string **Itália**. para isso, precisamos escrever pais = "Italia"

depois, vamos inserir a variável **quantidade**, o valor **4** (NOTE QUE ESTÁ SEM ASPAS).


> Observação!

É bom lembrar que o Python coloca 4 espaçamentos abaixo, quando você insere uma tabulação. É uma forma de ficar organizado, e é padrão do próprio Python.
Para conferir, é só digitar type(variável). Nos exemplos, type(pais) ou type(quantidade)
