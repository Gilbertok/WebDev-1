# Semanticas HTML
o **Google** se baseia em semânticas para poder realizar suas buscas dentro das paginas de sites, ele se baseia em várias tags diferentes, como title, description etc.

### header
E utilizado para representar o cabeçalho de um documento ou seção declarado no HTML.

### h1 a h6
As são usadas para representar informaçoes da pagina e também para diferenciar o tamanho das palavras.

### section
O elemento representa uma seção dentro de um documento e geralmente contém um título, o qual é definido por meio de um dos elementos h1 a h6 . Podemos utilizar o **section**, por exemplo, para descrever as seções/tópicos de um documento.

### main
O elemento **main** especifica o conteúdo principal e, consequentemente, de maior relevância dentro da página. Para ser considerada bem construída, uma página deve apresentar apenas um conteúdo principal.

### figure

O elemento **figure** é uma marcação de uso específico para a inserção de uma figura. Para incluir a descrição dessa figura, podemos utilizar o elemento **figcaption**.

### footer
O elemento **footer** representa um rodapé de um documento, como a área presente no final de uma página web. Normalmente é utilizado para descrever informações de autoria, como nome e contato do autor, e data de criação do conteúdo.
----
## Semântica no nível do texto
Além da semântica estrutural, o HTML nos permite descrever o significado de um conteúdo em nível de texto utilizando um conjunto de elementos semânticos. Assim, é possível, por exemplo, destacar os trechos de texto que devem receber algum tipo de destaque.

### a
A principal função do elemento é descrever um link, conectando os diversos documentos de um site e permitindo a navegação por esse conteúdo. Normalmente esses documentos estão relacionados por compartilharem um assunto em comum.

<a href=”http://www.google.com.br” alt=”Google”>Google</a>

### em
É utilizado quando desejamos enfatizar um trecho ou palavra no texto, indicando que ela contribui de forma mais relevante para o sentido/compreensão do conteúdo.

<p>Você <em>tem certeza</em> que essa definição está correta?</p>

### strong
O elemento também é utilizado para destacar uma parte do texto. Sua principal diferença em relação ao elemento <em> é que <em> pode alterar o propósito de uma frase, como vimos anteriormente.

### cite e q
O elemento <cite> é utilizado para declarar que naquele trecho há uma citação, isto é, um trecho de texto que não foi escrito pelo autor do conteúdo. Normalmente utiliza-se o <cite> em conjunto com o elemento <q>, responsável por apresentar o conteúdo retirado de outra fonte.

<p>
<q>Lorem ipsum dolor sit amet, consectetur </q> - <cite>http://br.lipsum.com/</cite>.
</p>

### time
O elemento <time> é utilizado para representar datas. Assim, caso seja necessário informar a data em que um conteúdo foi escrito, podemos declarar a tag <time> e acrescentar a ela o atributo datetime para escrever a data de forma padronizada.

<time datetime=”2017-04-07”>4/7</time>

