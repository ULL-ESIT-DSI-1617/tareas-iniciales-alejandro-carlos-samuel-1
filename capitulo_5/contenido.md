# Markdown & GitBook

## Markdown

`Markdown` es un lenguaje de marcado ligero creado por John Gruber que trata de conseguir la máxima legibilidad y facilidad de publicación tanto en su forma de entrada como de salida, inspirándose en muchas convenciones existentes para marcar mensajes de correo electrónico usando texto plano.

Para conocer este lenguaje, se ha seguido este [tutorial](https://guides.github.com/features/mastering-markdown).

## GitBook

[GitBook](https://gitbook.com) fue creado a mediados de 2014 con la visión de crear una solución moderna y simple para la documentación, la escritura digital y la publicación.

`Gitbook` es una manera fácil de crear, publicar y hostear libros. Es la solución más fácil de publicar tu contenido y colaborar en él.

Para realizar la instalación mediante npm:

`$ sudo npm install gitbook-cli -g`

Para inicializar la estructura del libro generando automáticamente el SUMMARY.md y README.md (introducción al libro):

`$ gitbook init`

Para obtener una vista previa del libro de manera local, utilizamos `$ gitbook serve`.

Para generar la página web sobre el libro: `$ gitbook build`.

![gitbook](/img/gitbook.png)

## gh-pages

Se trata de la rama del repositorio donde se publicará la documentación de `gitbook`.

## Pandoc

[Pandoc](http://www.pandoc.org) es un conversor de documentos libre y de código abierto, mayormente usado como una herramienta de escritura (especialmente por académicos), y es una base para la publicación de flujos de trabajo. Fue creado originalmente por John MacFarlane, un profesor de Filosofía en la Universidad de California, Berkeley.

Existen diferentes maneras de [instalar Pandoc](http://pandoc.org/installing.html) dependiendo del sistema operativo que se utilice. En el caso de Mac OS se debe ejecutar `brew install pandoc`.

Para transformar un fichero en formato `MarkDown` a un fichero `html` ejecutamos el siguiente comando:

`pandoc file1.md -f markdown -t html -s -o file2.html`
