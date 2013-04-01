# Translation of the Ruby on Rails Tutorial, 2nd Edition

Esto repositorio contiene el codigo funte  HTML por [Ruby on Rails Tutorial, 2nd edition](http://railstutorial.org/), con el proposito de permitir la traduccion de esto tutorial en otro idioma aparte la [*lingua franca*](http://en.wikipedia.org/wiki/Lingua_franca). 

## Para Empiezar

Por traducir el Tutorial de Ruby On Rails, simplemente 'fork' esto repositorio, clonalo en tu maquina local, y empieza a traducir en el tuyo idioma. Si tu quiere trabajar con otro traductores (que sin duda es algo que yo fomentaria), agregalo como colaboradores al repositorio donde estas trabajando. En cualquier momento tu eres libre de poner el resultado en una URL de tu elegion. Una vez que está arriba y listo para el consumo público, enviar URI a `admin@railstutorial.org` y yo voy a enviar el link a eso desde el principal sitio de 'Rails Tutorial'.

Puesto que a menudo hacen correcciones pequeñas al libro, yo recomiendo el 'merging' (agregar los cambios) en el 'master branch' (el ramo principal del repositorio) de vez en cuando. Si te das cuentas que el 'merging' la fusión provoca demasiados conflictos, tu puede omitir este paso optionale.

## Codigo Fuente

El repositorio contiene codigo fuente HTML por cada capítulo de 'Ruby on Rails Tutorial', así como dos CSS archivos por le estilo y el directorio de las imágenes donde estan todos las imágenes del libro. Tenga en cuenta que la imagen de los URI en los archivos HTML son *relativo*, exemplo, aparecen como

    images/figures/foo.png

sin diagonal inicial. Eso porque cuando tu ves los archivos HTML localmente todas las imágenes cargano correctamente. 

Para obtener una versión completamente desplegado del libro, tu puede cambiar la ruta de las imágenes desde relativo a absoluto, tal como

    /images/figures/foo.png

If this ends up being the case, I recommend writing a script to build the production output. You may find the Ruby line

```ruby
text.gsub!('"images/', '"/images/')
```

to be useful in this context.

## License

*Ruby on Rails Tutorial, 2nd Edition*. Copyright &copy; 2012 by Michael Hartl.

The HTML source of the Ruby on Rails Tutorial book is available under the [Creative Commons Attribution-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0/), which allows translation of the book as long as you give attribution to the original author ([Michael Hartl](http://michaelhartl.com/)) and distribute the translation under the same license.
