# JavaScript #

***¿Qué es?***

Es un lenguaje de programación **interpretado**. Se define como orientado a objetos, su principal uso es del lado del cliente (client-side) implementando del lado del navegador permite dar una mejoras en el interfaz del usuario , aunque también tiene demasiados uso del lado del servidor.

***¿Por qué JavaScript?***

Es el *lenguaje de la web*, la mayoría de los sitios web modernos utilizan JavaScript. Es versátil al poderse usar en el Frontend, Backend, Internet of Things, VR, Machine learning, etc. Los estándares de JavaScript (ECMA) van incorporando nuevas y mejores maneras de programar.

***¿Como conectar tu archivo de JavaScript con tu HTML?***

Para conectar JavaScript con HTML usamos la etiqueta `script`:
La etiqueta **script** nos da la propiedad **src=""**, en esta propiedad pondremos la ubicación del archivo, en este caso lo nombramos *script.js*.
```html
<script src="script.js"></script>
```

### Variables ###

¿Qué son las variables?

Las variables están formadas por un espacio en memoria y un nombre que está asociado a ese espacio. Las variables se definen con la palabra reservada `var`.

Para declarar una variable es poner la palabra `var`, seguido de el signo `=`, seguido del valor que deseas agregar.

```javascript
var edad = 18;
```

Las variables pueden contener valores `string`, `number`, `boolean`, `array`, `objects`, `function`, entre otros.(https://developer.mozilla.org/es/docs/Web/JavaScript/Data_structures)

Las variables de tipo `string` contienen texto, estas son declaradas de la siguiente manera:

El texto que deseas guardar en la variable va entre comillas dobles o comillas simples ( " ", '' )

```javascript
var saludo = "Hola :)";

```
### Inputs y Outputs ###

***¿Qué son?***

También conocido como I/O, es la comunicación entre un sistema que procesa información, como una computadora, y el mundo exterior, posiblemente un humano u otro sistema de procesamiento de información. Las entradas (inputs) es la data que recibe el sistema y las salidas (outputs) es la data que sale del contenido.

`alert()` es un ejemplo de **input**. Cuando se ejecuta muestra un pequeño modal con el contenido que nosotros pongamos dentro de los paréntesis.

`prompt()` es un ejemplo de **input**. Cuando se ejecuta se muestra un cuadro de diálogo donde el usuario puede escribir una línea de texto.

`console.log()` es un ejemplo de **output**. Imprime lo que se le pase entre paréntesis en algún dispositivo de salida de texto. En los navegadores la salida queda en la consola de JavaScript.

La consola no solamente muestra variables, también podemos hacer operaciones:

`console.log(5+5)`

***La consola***

Como desarrolladores una de las herramientas más importantes es la consola, esta herramienta, nos permite ver qué es lo que esta pasó en nuestro código de JavaScript.


### Operadores Aritméticos ###

Los operadores Aritméticos toman valores numéricos (ya sean literales o variables) como sus operandos y retornan un valor numérico único. Los operadores aritméticos estándar son adición o suma `( + )`, sustracción o resta `( - )`, multiplicación `( * )` , y división `( / )`.
Para comparar dos elementos se utilizan tres iguales `(===)`

***Suma***

La operación suma se lleva acabo mediante la suma de elementos pueden ser variables, números o texto(en el caso de sumar texto se le conoce como concatenar)

Ejemplo:

```javascript
2 + 2 =

var num1 = 10
var num2 = 20

num1 + num2

var saludo = "Hola!!"

var nombre = "Fulanito"

console.log(num1 + num2)
console.log(saludo + nombre)



```
***Quiero saber más...***

http://hectorip.github.io/Eloquent-JavaScript-ES-online/
https://javascript.info/types
https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Operadores/Aritm%C3%A9ticos
https://www.w3schools.com/js/js_type_conversion.asp