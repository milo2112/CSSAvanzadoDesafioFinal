# CSSAvanzadoDesafioFinal
Desafio final módulo CSS avanzado - modificando componente card de bootstrap 

NOTA: Existe un error en la generación del enlace a github pages, pero no logro identificar por qué

Al parecer son problemas en los archivos descargados de bootstrap donde yo no hice intervenciones 
(carpetas distintas a las scss donde yo intervine), aunque no descarto que mis modificaciones sean la causa.

ACTUALIZACION: agregué liquid raw tags en: {% raw %} {{- $match := findRE ":root {([^}]*)}" $css 1 -}} {% endraw %} del archivo css-variables.md y logré corregir el error, pero al ejecutar el enlace github pages, no muestra los cambios que realicé y que aparecen en los commits. :'(


![image](https://user-images.githubusercontent.com/31677756/170917457-b25a95c7-d1d2-44b4-9b4e-30b3b4474047.png)

