# Arquitetura CSS - Alura

Curso de Arquitetura CSS da Alura, onde é ensinado boas práticas para nomeação de classes, estruturação das pastas de estilo e organização do código CSS utilizando o conceito de Atomic Design e BEM(Block Element Modifier)

### Atomic Design

Metodologia para criar sistemas de design em unidades/componentes menores, chamados de Átomos.

* **Átomo** -> Uma tag/elemento HTML

* **Molécula** -> Conjunto de tags/elementos HTML
    Ex: Uma logo com um menu de navegação

* **Organismos** -> Junção de várias moléculas

* **Templates** -> Junção de vários organismos, geralmente não possui dados reais, apenas representações geométricas

* **Páginas** -> Junção de vários organismos, porém com dados reais


Referência - [Atomic Design](https://bradfrost.com/blog/post/atomic-web-design/)

### BEM (Block Element Modifier)

Metodologia para padronizar o nome das classes CSS, separando-as em: 
* **Bloco** - Um bloco ou componente maior.
    Ex: Um cabeçalho, uma sidebar, etc.
* **Elemento** - Elementos filhos de um bloco, representado com **__**
    Ex: Lista de botões de uma sidebar, logo de uma header
* **Modificador** - Classes que realizam determinadas modificações nos elementos, representado por **--**
    Ex: Uma classe size-big, shadow-yes, col-wide, etc. Que incrementa/modifica determinado elemento

Referência - [BEM](http://getbem.com/naming/)
