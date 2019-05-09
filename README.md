SICP - Estrutura e Interpretação de Programas de Computador
====

<img src="https://sicpebook.files.wordpress.com/2013/09/smile0.png"
 alt="Par smiling" align="right" />
 
Esta é uma nova versão HTML5 e EPUB3 de "Estrutura e Interpretação de Programas de Computador" `_Structure and Interpretation of Computer Programs_` por Abelson, Sussman e Sussman. Inicialmente construido com [Unofficial Texinfo Format](http://www.neilvandyke.org/sicp-texi) que foi convertido do original [versão HTML](https://mitpress.mit.edu/sicp) em _The MIT Press_.

<b>No formato EPUB3: [sicp.epub](https://github.com/ensine-se-ciencia-da-computacao/sicp-portugues/blob/master/sicp.epub?raw=true)</b>

<b>Para uma leitura online: [Livro em HTML](https://ensine-se-ciencia-da-computacao.github.io/sicp-portugues)</b>

Soluções modernas, como gráficos vetoriais escaláveis, marcação matemática com MathML e MathJax, fontes da Web incorporadas e realce de sintaxe são usados. Scaffold rudimentares para design responsivo estão em vigor, o que adapta a página para visualização em dispositivos de bolso e tablets. Mais testes em telas pequenas são necessários para ajustar o tamanho e a formatação da fonte, por isso incentivo o feedback dos proprietários de smartphones e tablets.


Source
------
O diretório raiz contém o conteudo em Texinfo no `sicp-pocket.texi`. Para recriar os arquivos HTML e compilar o EPUB, digite:

```bash
$ make
```

Todos os arquivos no diretório `html`, mas não em subdiretórios, serão sobrescritos, então o lugar preferido para fazer alterações sempre será `sicp-pocket.texi`. O arquivo EPUB será criado no diretório pai, fora da árvore do projeto.

Você precisará do [Texinfo 5.1](https://ftp.gnu.org/gnu/texinfo), Perl 5.12 ou posterior, Ruby 1.9.3 ou mais recente, [Nokogiri](http://nokogiri.org) gem, [PhantomJS](http://phantomjs.org) e conexão com a Internet para compilar o livro.

Agradecimentos
----------------

* Lytha Ayth
* Neil Van Dyke
* Gavrie Philipson
* Li Xuanji
* J. E. Johnson
* Matt Iversen
* Eugene Sharygin

Licença
-------

O arquivo fonte `sicp-pocket.texi,` conteúdo HTML do livro e diagramas no diretório `html/fig` são licenciados sob a licença Creative Commons Atribuição-CompartilhaIgual 4.0 Internacional ([cc by-sa](https://creativecommons.org/licenses/by-sa/4.0)).
          
A maioria dos scripts está licenciada sob a versão 3 da GNU General Public License (para detalhes, veja LICENSE.src).

As fontes estão em SIL Open Font License versão 1.1. Outros arquivos, como bibliotecas Javascript, possuem suas próprias licenças.

Projeto Relacionado
--------------

Uma [versão em PDF](https://github.com/sarabander/sicp-pdf) construída a partir do fonte LaTeX acompanha esta versão em HTML.

Atualmente sem previsão para tradução dessa versão em PDF, portanto, o projeto está lincado no repositorio do [@sarabander](https://github.com/sarabander/sicp-pdf)
