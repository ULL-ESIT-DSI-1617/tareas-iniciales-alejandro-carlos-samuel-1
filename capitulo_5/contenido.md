# Markdown & GitBook

## Markdown

`Markdown` es un lenguaje de marcado ligero creado por John Gruber que trata de conseguir la máxima legibilidad y facilidad de publicación tanto en su forma de entrada como de salida, inspirándose en muchas convenciones existentes para marcar mensajes de correo electrónico usando texto plano.

Para conocer este lenguaje, se ha seguido este [tutorial](https://guides.github.com/features/mastering-markdown).

## GitBook

## Pandoc

[Pandoc](http://pandoc.org) es un conversor de documentos libre y de código abierto, mayormente usado como una herramienta de escritura (especialmente por académicos), y es una base para la publicación de flujos de trabajo. Fue creado originalmente por John MacFarlane, un profesor de Filosofía en la Universidad de California, Berkeley.

Existen diferentes maneras de [instalar Pandoc](http://http://pandoc.org/installing.html) dependiendo del sistema operativo que se utilice. En el caso de Mac OS se debe ejecutar `brew install pandoc`.

Para transformar un fichero en formato `MarkDown` a un fichero `html` ejecutamos el siguiente comando:

`pandoc file1.md -f markdown -t html -s -o file2.html`
