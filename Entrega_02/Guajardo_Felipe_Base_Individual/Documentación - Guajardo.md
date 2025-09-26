# Documentación 

Como nuestro objetivo es trabajar y analizar juegos de categoría Triple A, nos interesan las principales plataformas en el mercado, dejando así juegos de tipo indie. Para comenzar hemos decidido trabajar con las plataformas y juegos de Sony (Play Station) y Xbox (Microsoft/Xbox Games Studio), pero solo los juegos desarrollados por esas compañías ya que de lo contrario sería demasiada información y datos, datos que incluso no van al caso.

En mi caso, que trabaje con los títulos desarrollados por Xbox Game Studios, la principal fuente de datos de esos títulos es Wikipedia, por ende, esa fue la limpieza de datos, el filtro de selección de juegos solo desarrollados por el estudio de Xbox. Incluso, inicialmente trate de recopilar todos los títulos para la primera Xbox, y eran muchos títulos, y por eso se hace esa distinción, ya que además nuestro objeto son los juegos Triple A.

La siguiente imagen es una captura de una parte de la base de datos (en PDF, porque borré el documento original) en la que estaba trabajando sobre juegos solo de la primera Xbox, pero al ser tantos datos se tomó la decisión de solo trabajar con Xbox Games Studio.

![alt text](<Captura de Pantalla 2025-09-26 a la(s) 20.07.19.png>) 

Volviendo al tema de fuentes de datos y decisiones, se trabajó principalmente con Wikipedia porque en cada página se puede encontrar una tabla ya elaborada, mientras que en otras plataformas como MobyGames (que se usó como fuente secundaria) también tenía esa información, pero no sintetizada en una tabla, sino que había una página por cada título, por ende, Wikipedia lo hacía más rápido, sobre todo por la metodología que se mencionó anteriormente en la ficha técnica. 

De igual modo, las tablas de Wikipedia entregaban información que no es relevante en el proyecto como por ejemplo los publicadores de los títulos, notas y referencias. Esa información se removió a la hora de construir la base de datos por lo que igual se considera parte del proceso de selección y limpieza. Para limpiar esos datos extras, como el CSV ya está tabulado, se seleccionaron las columnas que tenían esa información y se eliminaron. 

La pagina principal de Wikipedia que tiene los estudios de Xbox Games Studio es:
https://en.m.wikipedia.org/wiki/Xbox_Game_Studios
Pero también se utilizo la plataforma de MobyGames (https://www.mobygames.com), Steam, App Store, y foros de videojuegos que tienen información sobre el tamaño de los juegos (en caso de que no estuvieran ni en Steam o la App Store).

Posteriormente también se decidió incluir la categoría de puntaje medio de los juegos, es decir, cuál es la valoración de estos en una escala del 1 al 100 y la fuente de esa información es la página web Metacritic, que sería el equivalente a GameRankings que ya no existe. 

Preguntas que se pueden responder con la base de datos son:
¿Qué estudio es el que desarrolló más juegos?
¿Qué estudio es el que utilizó más trabajadores para desarrollar juegos? (así como también menos)
¿Hay alguna frecuencia de desarrollo en cuanto al tiempo?
¿Hay alguna evolución en cuanto al peso de los juegos desarrollados?
¿Hay alguna tendencia en cuanto al formato de juegos? ¿se están desarrollando más juegos originales o remasterizados?
¿Qué compañía trabaja más en juegos de saga?
¿Las valoraciones de los videojuegos ha mejorado, empeorado o se ha mantenido con el pasar del tiempo? (o incluso que compañía tiene una mejor valoración).

