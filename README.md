# *SESSION Y COOKIES*


## Objetivo
En esta práctica veremos cómo podemos utilizar Express Validator y además
seguiremos aprendiendo sobre cookies y Session, súper necesarias para nuestras
aplicaciones.
¡Buena suerte!😎👍✨

## Micro desafío - Paso 1:
Crear un pequeño proyecto de Express, implementar una vista que le muestre al
visitante un sencillo formulario que contenga:
- Un label que diga: “Ingrese su nombre”, con un input para recibir dicho valor
(requerido).
- Un listado de opciones desplegable, que deberá tener varias opciones con
nombres de colores de los cuales el visitante elegirá uno de ellos (requerido).
- Un label que diga: “Ingrese su email”, con un input para recibir dicho valor
(requerido).
- Un label que diga: “Ingrese su edad”, con un input para recibir dicho valor (no
requerido).
- Un botón de enviar.

Tras ingresar los datos y al dar clic en el botón de enviar debemos redireccionar al
usuario a la misma página y que se muestre un texto que diga:

- Hola nombreUsuario, elegiste el color: colorSelecionado, tu email es:
emailUsuario y tu edad es: edadUsuario

Con Express Validator, debemos validar:
- Los campos que son requeridos y, en caso de que no se ingresen, debemos
mostrar un mensaje de error indicando que deben completarse.
- En caso de que se ingrese la edad, debemos validar que sea un número, en caso
contrario, mostrar el error.

## Micro desafío - Paso 2:
Cuando se haga submit del formulario, debemos cambiar en el body el color del
background-color al que el usuario seleccionó en el formulario y, además, debemos crear
otra vista que también aplique el cambio del background-color en el body según se
seleccionó y que se visualice el mensaje:
- nombreUsuario, gracias por visitarnos.

## Micro desafío - Paso 3:
Modificar el formulario para que:
- Tenga un checkbox que diga "Recordar color". Y que si el visitante de la
aplicación tilda este checkbox, el color elegido se persista cuando se cierre y se
vuelva a abrir el navegador.
- Tenga un botón que implemente la funcionalidad de "Olvidar el color" la cual
deberá volver todo a su estado inicial.

## Conclusión
Usando tanto cookies y Session en nuestras aplicaciones podemos ofrecerle al usuario
una mejor experiencia y también, si implementamos Express Validator, podemos validar
los datos ingresados antes de procesarlos y así evitarnos grandes dolores de cabeza si no
lo hacemos.
¡Hasta la próxima!

