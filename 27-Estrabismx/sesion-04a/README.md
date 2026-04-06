# sesion-04a #

## Apuntes ##

La clase inicio con un pequeño resumen / repaso sobre algunos términos y conceptos, donde lo que más destaco es la tabla con las potencias de 10 (la cual tengo en mi bitacora física pero no tan bonita como acá) 

|                           | Potencia de 10  | prefijo | abreviatura |
| ------------------------- | --------------- | ------- | ----------- |
| 1 000 000 000 000 000 000 | $10^{18}$       | Exa     | E           |
| 1 000 000 000 000 000     | $10^{15}$       | Peta    | P           |
| 1 000 000 000 000         | $10^{12}$       | Tera    | T           |
| 1 000 000 000             | $10^{9}$        | Giga    | G           |
| 1 000 000                 | $10^{6}$        | Mega    | M           |
| 1 000                     | $10^{3}$        | Kilo    | k           |
| 100                       | $10^{2}$        | Hecta   | h           |
| 10                        | $10^{1}$        | Deca    | da          |
| 1                         | $10^{0}$        |         |             |
| 0.1                       | $10^{-1}$       | deci    | d           |
| 0.01                      | $10^{-2}$       | centi   | c           |
| 0.001                     | $10^{-3}$       | mili    | m           |
| 0.000 001                 | $10^{-6}$       | micro   | µ           |
| 0.000 000 001             | $10^{-9}$       | nano    | n           |
| 0.000 000 000 001         | $10^{-12}$      | pico    | p           |
| 0.000 000 000 000 001     | $10^{-15}$      | femto   | f           |
| 0.00 000 000 000 000 001  | $10^{-18}$      | atto    | a           |

<br>

Lo siguiente que revisamos fue una variación del circuito anterior (Un Astable que se conectaba a un Monostable), donde se inicia con un Monostable que llega a un Astable.

![Esquematico](./imagenes/esquematico.jpg)

![Protoboard](./imagenes/proto1.jpg)

![Protoboard](./imagenes/proto2.jpg)

![Protoboard](./imagenes/proto3.jpg)


1. Lo primero que debemos entender para llevar a cabo este circuito, es que hace cada uno
  
  a)  El Astable : En el output recibimos una corriente que alterna entre _on_ y _off_
 
  b)  El Monostable: Al presionar el interruptor la energía sigue circulando un tiempo desde que se suelta el switch.

2. Entonces para conectar el circuito _B_ al _A_ vamos a tomar el pin 3 del Monostable y conectarlo al pin _Reset_, es decir al n°4

3. Ahora cada vez que pulsemos el switch, la energía circula por un tiempo determinado donde el Astable, para luego emitir la corriente en ondas cuadradas hasta el parlante

> Una pequeña acotación es la particularidad del sonido, muy similar a como suena una ambulancia

<br>

### Falstad ###

Se nos enseño la web <https://www.falstad.com/circuit/>. Utilizada para visualizar de mejor manera que TinkerCad, ya que podemos ver como circula la energía en estas carreteras llamadas cables.

![Captura de pantalla](./imagenes/captura-de-pantalla04.png)

> Acá podemos ver como es la interfaz del sitio.
>
>> Abajo se pueden ver graficamente las ondas, en Inductores, condensadores, etc..
>>
>> Al lado se puede manipular aspectos de representación
>>
>> Arriba se observa todas las opciones disponibles

<br>

![Captura de pantalla](./imagenes/captura-de-pantalla03.png)

> En este apartado tenemos ejemplos de circuitos, opción bastante útil para aprender

<br>

![Captura de pantalla](./imagenes/captura-de-pantalla02.png)

> Este circuito es un ejemplo de un circuito _Oscilador con bajo ciclo activo_
>
> También se aprecia al mismisimo 555, pero con una _skin_ diferente (en la sesión anterior pudimos aprender esto)

<br>

![Captura de pantalla](./imagenes/captura-de-pantalla01.png)

> Ahora podemos apreciar las opciones para _Archivos_, donde destacan:
>
>> Exportar / Importar como formato de texto: Esto significa que mediante un mensaje podemos compartir diversos circuitos, sin necesidad de descargar un archivo
>>
>> Exportar como enlace: Formato más popular para compartir algo, pero el más volátil en mi opinión (esperemos que no desaparezca el servidor donde está el blog que tengo guardado hace 12 años xd)
>>
>> Exportar como SVG: Me parece fenomenal que exista esta opción, en cualquier momento estampo mi polera con el circuito _Atari Punk Console_
>>
>>> (Scalable Vector Graphics) es un formato de imagen vectorial basado en XML que permite escalar gráficos sin perder calidad ni pixelarse al ampliarlos.

<br>

![Captura de pantalla](./imagenes/captura-de-pantalla00.png)

> Ejemplo de como se ve el formato de texto

<br>

### Elementos a Investigar ###

Como es costumbre, dentro del bombardeo de preguntas que me surgen en clase hubo elementos que considero importantes rescatar:

1. Vimos los elementos internos del 555 y entendiendo que todo lo que hay dentro existe como componente _normal_ (como los que tenemos para usar en una protoboard), significa que se puede recrear desde 0. Además de poder hacerlo en Minecraft

> Un referente que se nos enseñó fue Evil Mad Scientist (el nombre me recorde al grupo criminal de cientificos MAD, de One Piece), quienes vendian un kit donde se recreaba un chip 555 de manera _artesanal_ o de mayor escala que el que tenemos, que cae en un dedo

2. Otro punto importante fue la unidad de medida _henrio_ (de Henry Joseph Henry), utilizada para medir la capacidad de un componente (como una bobina) para almacenar energía en un campo magnético. Un henrio se define como la inductancia de un circuito que produce una FEM (fuerza electromotriz) de 1 voltio cuando la corriente varía a 1 amperio por segundo.

> En palabras menos GPT, el henrio (H) se usa para medir la inducción 

3. Finalmente está el libro que traía la Emi, el cual le tome una fotografía para revisarlo de manera completamente legal y para nada en formato .pdf

![Libro](./imagenes/libro-emi.jpg)

 <br>

<br>

 ## Encargo ##

 Se nos solicito realizar una carnicería electrónica, la idea es desarmar un equipo electrónico y observar, analizar y cuestionarnos el como podría funcionar

 1. El kit utilizado para la operación de nuestro paciente

![Herramientas](./imagenes/desarme07.jpg)

<br>

 2. Nuestro paciente, un Pioneer Cassette Deck Model CT-1040W. Este equipo fue desechado a la basura un dia antes que se nos encargara esta tarea (la suerte me sonrie), por lo que se encontraba bien sucio la verdad

> La primera imagen corresponde a una fotografía de internet, puesto que no le tome fotos antes de iniciar
 
![Pioneer Cassette Deck Model CT-1040W](./imagenes/pioneer.jpg)

<br>

3. Iniciamos con la operación, dejando al paciente con su cerebro expuesto

![Desarme](./imagenes/desarme02.jpg)

![Desarme](./imagenes/desarme00.jpg)

![Desarme](./imagenes/desarme03.jpg)

> Podre utilizar esta imagen de excusa cuando digan que mi circuito no está ordenado (?)

<br>

![Desarme](./imagenes/desarme04.jpg)

Acá observamos los primeros elementos o como se compone, observando de momento 2 placas PCB

<br>

4. Empezamos a ver componentes algo llamativos

![Desarme](./imagenes/desarme05.jpg)

![Desarme](./imagenes/desarme06.jpg)

> Realmente lo más _fome_ conectores _dupont_ y un transformador de voltaje

<br>

![Desarme](./imagenes/desarme08.jpg)

![Desarme](./imagenes/desarme09.jpg)

![Desarme](./imagenes/desarme10.jpg)

![Desarme](./imagenes/desarme11.jpg)

<br>

![Desarme](./imagenes/desarme12.jpg)

> Apreciación de como no todo es perfecto, ni debe estarlo

<br>

![Desarme](./imagenes/desarme13.jpg)

![Desarme](./imagenes/desarme14.jpg)

![Desarme](./imagenes/desarme16.jpg)

![Desarme](./imagenes/desarme19.jpg)

![Desarme](./imagenes/desarme20.jpg)

> Una resistencia de 100 000 000 $\Omega$ 😲

<br> 

![Desarme](./imagenes/desarme21.jpg)

>En efecto, no se medir resistencias en multímetros

<br>

![Desarme](./imagenes/desarme23.jpg)

<br>

6. Recien terminada la primera placa, la cual fue un mundo de posibilidades y cosas nuevas. Iniciamos la etapa 2

![Desarme](./imagenes/desarme23.jpg)

![Desarme](./imagenes/desarme24.jpg)

![Desarme](./imagenes/desarme27.jpg)

>La buena confiable amarra plástica

<br>

![Desarme](./imagenes/desarme29.jpg)

![Desarme](./imagenes/desarme30.jpg)

![Desarme](./imagenes/desarme31.jpg)

> Capacitores XL
>
>> No me atreví a sacarlo ni nada, igualmente considerar que el equipo llevaba más de 10 años guardando polvo. Por lo que espero estuviera descargado

<br>

![Desarme](./imagenes/desarme32.jpg)

![Desarme](./imagenes/desarme33.jpg)

> Curioso, un chip con el simbolo Dolby, posibilidad que funcione para el audio 99%

7. 



