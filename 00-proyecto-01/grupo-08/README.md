# grupo-01

## integrantes

- nombres apellidos github
- nombres apellidos github
- nombres apellidos github

## descripción del sintetizador realizado

3 párrafos explicando el proyecto

imagen del sintetizador en su contexto

audio o video del sintetizador en acción

## proceso y resultados del reloj y secuenciador

con chips 555 y 4017

incluir texto e imágenes sobre cableado, pruebas, resultados obtenidos.

## proceso y resultados de osciladores y amplificador

Con la base del circuito ya funcionando (clock y secuenciador) avanzamos hacia la etapa del sintetizador y salida, al finalizar el armado, no obtuvimos la señal del parlante y para encontrar el problema, realizamos una revisión por etapas. En primer lugar, confirmamos que tanto el clock (555) y el secuenciador (4017) funcionaban correctamente. Luego, revisamos las conexiones generales del circuito, incluyendo la tierra común y las posibles fallas en componentes específicos. 

Con la recomendación de Misa, empezamos a probar el circuito del sintetizador de manera aislada en otra protoboard. Probamos el funcionamiento del 4093 utilizando un solo potenciómetro, y también verificamos el amplificador 386 por separado, conectándolo directamente a la salida de audio. Este proceso permitió detectar algunos errores, identificamos que los condensadores en el circuito del 386 estaban mal conectados, también consideramos la recomendación de Misa de desconectar un LED porque interfiere en el funcionamiento.  

Finalmente decidimos rehacer la etapa del sintetizador desde cero, además, se incorporó un condensador de 100uF en la etapa del 386, lo que ayudó a estabilizar la señal. Tras estos ajustes y una reorganización general del circuito, finalmente logramos obtener sonido en el parlante.

![foto1](./imagenes/foto1.jpg/) 

## modificaciones realizadas a los circuitos originales

incluir texto, imágenes sobre modificaciones realizadas a los circuitos originales, incluyendo el proceso de diseño, pruebas y resultados obtenidos.

incluir modificaciones en posición, chips, parámetros, valores, etc.

## carcasas de cartón

textos, imágenes

incluir origen de materiales, decisiones de posiciones de los componentes, decisiones estéticas, pruebas, resultados obtenidos.

## interconexión entre módulos

Usamos dos protoboards de 830 puntos para realizar el circuito del clock, el secuenciador y el sintetizador. Primero nos enfocamos en hacer la extensión de los positivos y negativos con cables, para asegurar una alimentación común y ordenada en todo el circuito. En una protoboard de 400 puntos realizamos el circuito de salida de audio. Esta protoboard se conectó a las anteriores compartiendo los mismos positivos y negativos, permitiendo así que todas las etapas del circuito quedarán interconectadas y funcionando en conjunto.

![foto2](./imagenes/foto2.jpg/)

Las conexiones en la protoboard se realizaron principalmente con cables dupont macho-macho. En el caso de los potenciómetros del 555 y del 386, estos se extendieron mediante cables macho-hembra para facilitar su manipulación. Finalmente, el parlante se conectó utilizando caimanes con conectores macho.

![foto3](./imagenes/foto3.jpg/)

![foto4](./imagenes/foto4.jpg/)

![foto5](./imagenes/foto5.jpg/)

Utilizamos un criterio de color para organizar las conexiones y facilitar la lectura del circuito. Los colores como rojo y naranjo, se utilizaron para las conexiones de positivo, mientras que los colores como azul, café y verde se destinaron a negativos. Para las uniones entre potenciómetros y módulos usamos colores más neutros como morado y blanco, lo que ayudó a diferenciar este tipo de conexiones del resto.

Además, intentamos mantener un orden secuencial en el uso de los colores, de manera que si una conexión comenzaba con un color específico, se continuaba con ese mismo criterio a lo largo del recorrido.

![foto6](./imagenes/foto6.jpg/)


## resultados finales

texto

imagen

video / audio

## aprendizajes y errores

Uno de nuestros principales aprendizajes fue la importancia de trabajar de forma organizada en la protoboard. Mantuvimos siempre orden en el cableado, usando cables cortos para conexiones cercanas y respetando colores para diferenciar cada tipo de conexión (por ejemplo, alimentación, tierra y señal). 

Esto nos ayudó a evitar cruces innecesarios y a que el circuito no se viera saturado de cables. Se nos hizo mucho más fácil tanto el armado como la lectura del circuito. Podíamos seguir visualmente las conexiones sin confundirnos, lo que fue necesario al momento de revisar errores o hacer cambios.  

El trabajo en equipo fue un aspecto muy positivo para nosotras. Avanzamos de manera más rápida y nos apoyamos mutuamente en la resolución de los problemas. El hecho de que empezáramos haciendo cada parte por separado fue un gran error, porque dificulta la integración final del circuito y generó confusiones en las conexiones. 

Los errores más comunes en relación al armado fueron principalmente el uso de chips malos, como el 555, que nos impidió el encendido correcto de los LED. Otro error común fue que no nos fijamos que una resistencia de 220 se había soltado en la parte del secuenciador, lo que hacía fallar el funcionamiento del circuito.

La conexión incorrecta de componentes en el chip 386, específicamente los condensadores, fue un error importante porque impedía la salida de audio. Al corregir estas conexiones e incorporar el condensador de 100uF, se logró estabilizar la señal.

A pesar de las dificultades técnicas logramos completar el circuito y obtener el sonido, lo que fue un avance importante para el grupo. El tener errores nos permitió comprender de mejor manera la relación entre las distintas etapas del sistema, clock, secuenciador, sintetizador y salida y evidenció la importancia de un montaje ordenado y colaborativo. 


## conclusiones

sobre modularidad, materialidad, trabajo en equipo, trabajo electrónico, trabajo maquinal.
