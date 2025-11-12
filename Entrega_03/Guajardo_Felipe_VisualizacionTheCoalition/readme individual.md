# Explicación construcción de la visualización 

Antes de comenzar con la base de datos en Google Colab, consideré las correcciones de la entrega número 2; por ende, convertí toda la columna del tamaño de los videojuegos, donde algunos estaban en MB, otros en GB y uno en KB, por ende, transformé todos a MB. Así también, eliminé todos los caracteres especiales como las "ñ", letras con tílde y de otro tipo para evitar errores a la hora de que se procesen los datos. El otro cambio que realicé fue respecto a las plataformas de los videojuegos para evitar demasiada información acumulada en las celdas, por lo que cree tres columnas para identificar si esos videojuegos estaban disponibles en tal plataforma, donde la información responde a "Si" o "No" (Si/No esta disponible).

Una vez hecho eso, analicé la base de datos para poder identificar qué es lo que realmente quería visualizar, ya que es imposible visualizar todo y que a la vez sea coherente. Decidi trabajar específicamente con los juegos de la compañia The Coalition, porque sus trabajos han sido mucho más continuos y no son tantos títulos asi como tampoco pocos, por lo que creo que es más preciso. Así tambien, la escogi porque en cierto grado representa una correlación directa en cuanto el numero de trabajadores y el peso del videojuego, es decir, en la medida que los videojuegos son más pesados, hay menos desarrolladores (esto no es algo lineal o perfecto, pero se puede observar esa tendencia).

## Proceso de programación

En primer lugar, importé a la plataforma la base de datos a Google Colab con altair. Luego seguí los mismos pasos que hemos realizado en clases que es que "corra" la base, que se pueda leer copiando la ruta del documento.

Luego, como no quiero usar todos los datos de la BD, repeti lo de importar en altair; repeti las mismas lineas inciales, pero en lugar de copiar la ruta de acceso (porque eso ya esta hecho), filtré la base de datos (que es *source*). Entonces creé nuevos valores que es el source_filtrado, donde inicialmente puse la compañia con la que quiero trabajar (The Coalition), pero eso no es suficiente, porque si lo dejaba solo con eso, se iban a imprimir columnas que no vienen al caso, por ende, agregué otro filtro que es el del videojuego, el tamaño y el numero de trabajadores (esos son los que me importan para trabajar en esta ocasión). Luego de eso, puse print para asegurarme de que todo estuviera bien.

En cuanto a la forma de graficar, aqui fue mucho más dificil porque como queria mostrar la relación entre el tamaño del juego y la cantidad de trabajadores, sentia que era más apropiado usar este grafico: 

![alt text](<Captura de Pantalla 2025-10-16 a la(s) 17.07.58.png>)

En lugar de cuatro gráficos serían dos, por mis variables (tamaño y trabajadores), pero no logre que aparecieran los titulos de los juegos, solo se completaba un grafico y era una especie de pila, un bloque de color, por ende, no graficaba de buena forma.

Viendo otros ejemplos, decidí trabajar con algo sencillo que es el resultado de mi trabajo de visualización; el resultado es este gráfico de dispersión, donde fue reemplazando los valores:

![alt text](visualization-1.png)

Trate de hacer modificaciones para que los valores numericos estuvieran en las lineas de manera creciente, de menor a mayor, y a pesar de buscar en internet, no lo logré. Pero eso no quita el funcionamiento del grafico, asi como la información en las viñetas.

## Preguntas posibles que se pueden responder:
¿Cuántos trabajadores contribuyeron al juegos de mayor tamaño de The Coalition?

¿Hay alguna tendencia en cuanto al aumento del tamaño del juego con la cantidad de trabajadores?

Si no es así, ¿que juegos demuestran lo contrario?

Si es así, ¿qué juegos demuestran aquello?

A simple vista, ¿A qué se debe la dispersión del gráfico?

