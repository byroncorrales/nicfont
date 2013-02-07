#Nicfont


Nicfont es un proyecto que aprovecha las virtudes de font-face y CSS3 para optimizar la forma de mostrar un mapa departamental de Nicaragua. Nicfont es una tipografía en donde cada letra representa el area vectorial de un departamento, de esta forma el area del mapa puede ser escalada a cualquier tamaño sin perder la calidad del gráfico.

Encuentra el demo en [Nicfont](http://byroncorrales.github.com/nicfont/) 


¿Cómo Funciona?
Se ha creado una tipografia nicfont-webfont.ttf en donde se asigno a cada letra de la "a" a la "q" con un departamento del Nicaragua. Cada área de departamento esta ubicada de forma relativa con respecto a las otros depatamentos, de tal forma que al crear una secuencia de letras los departamentos se dibujan de forma solapada en una misma área.

¿Cómo usarla?
Basicamente se debe importar el archivo de estilo nicfont.css y usar la siguiente estructura HTML:

    <!-- Incluir dentro de la tag <head> -->
    <link rel="stylesheet" href="css/nicfont.css">
     
    <!-- Dentro del <body> -->
    <ul class="nicfont"> 
      <li id="raan"></li>
      <li id="raas"></li>	
      <li id="rio-san-juan"></li>
      <li id="chontales"></li>
      <li id="boaco"></li>
      <li id="matagalpa"></li>
      <li id="jinotega"></li>
      <li id="esteli"></li>
      <li id="madriz"></li>
      <li id="nueva-segovia"></li>
      <li id="chinandega"></li>
      <li id="leon"></li>
      <li id="managua"></li>
      <li id="masaya"></li>
      <li id="carazo"></li>
      <li id="granada"></li>
      <li id="rivas"></li>
    </ul>
    
##Demo

 [http://byroncorrales.github.com/nicfont/](http://byroncorrales.github.com/nicfont/) 

##Recursos

[Free Online Font Converter](http://www.freefontconverter.com) - Convertir SVG to TTF  

[Font Squirrel](http://www.fontsquirrel.com/fontface/generator) - Convertir TTF a web fonts

[Intridea Blog: How to Make Your Own Symbol Font](http://www.intridea.com/blog/2012/4/24/symbol-font) - Buen lugar para iniciar.

##Créditos

Creado por Byron Corrales basado en [Stately](http://intridea.github.com/stately/)

Byron Corrales[twitter](http://www.twitter.com/byroncor) [website](http://byroncorrales.blogspot.com/)  

 
##Licencia

MIT License. See LICENSE for details.

##Copyright

Copyright (c) 2013 Byron Corrales.

