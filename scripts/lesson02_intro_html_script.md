# Lección 2: Estructura HTML básica 
 
---
 
## Introducción y "en manzanas"
 
¿Qué tal a todos? Bienvenidos a esta segunda lección. Hoy vamos a aprender sobre la estructura básica de etiquetas HTML.
 
Para que lo entiendan fácil: imaginen que construir una página web es como hacer una construcción en Minecraft. El HTML son los bloques base. Sin esos bloques, no tienes dónde construir. Es como intentar construir una casa en Minecraft, sin que haya ningún piso para poner los primeros bloques. Cada etiqueta en HTML es como una caja. Tienes cajas grandes que guardan cajas más pequeñas adentro.
 
Por definición técnica: HTML significa HyperText Markup Language, o Lenguaje de Marcado de Hipertexto. No es un lenguaje de programación, sino un lenguaje de marcado. Usamos etiquetas para decirle al navegador web qué es un título, qué es un párrafo, qué es una imagen y demás elementos.
 
---
 
## Anatomía de un documento HTML
 
Antes de ensuciarnos las manos con el código, veamos la anatomía rápida de un documento.
 
Todo archivo arranca avisándole al navegador las reglas del juego. Para eso, en la primera línea escribimos la declaración `<!DOCTYPE html>`.
 
Luego, abrimos la caja madre: la etiqueta `<html>`. Esta envuelve absolutamente todo el proyecto. Y adentro de ella, siempre van a convivir dos bloques principales: el `<head>` y el `<body>`.
 
**El `<head>`** es el cerebro de la página. Aquí van las configuraciones en segundo plano que el usuario no ve. Por ejemplo, la metadata. Solemos poner una etiqueta `<meta charset="UTF-8">` que solo sirve para que tu página soporte tildes y eñes sin que el texto lance símbolos raros. También ponemos el `<title>`, que es simplemente el nombre que aparece en la pestaña de tu navegador. Configuras este bloque y te olvidas.
 
**El `<body>`** es tu zona de juego. Todo, absolutamente todo lo que metas dentro del `<body>` es lo que va a existir visualmente en la pantalla.
 
---
 
## ¿Qué es una etiqueta HTML?
 
En términos simples, es un sistema de empaquetado. Por definición, es un elemento de marcado que le dice al navegador dónde empieza, cómo se comporta y dónde termina un bloque de contenido.
 
Para que lo entiendan perfecto, imagínenlo en cuatro pasos:
 
**Paso 1 — La caja abierta.** Tienes una caja abierta en el suelo. Esta representa tu etiqueta de apertura. Para este ejemplo, digamos que la caja tiene escrito el nombre `div`.
 
**Paso 2 — Los atributos.** A esta caja vacía le vamos a pegar dos stickers por fuera. Un sticker dice `class` y el otro dice `id`. En programación, a estos stickers los llamamos atributos. Sirven para darle una identidad única a la caja y poder darle estilos más adelante.
 
**Paso 3 — El contenido.** A nuestra caja abierta con stickers le metemos cosas adentro. Puede ser texto, una imagen, o incluso otras cajas más pequeñas.
 
**Paso 4 — La tapa.** Le ponemos la tapa a la caja para cerrarla. Esta es la etiqueta de cierre, que se escribe con una barra diagonal antes del nombre: `</div>`. La regla inquebrantable: **caja que abres, caja que tapas.**
 
---
 
## Ejemplo práctico en CodePen
 
Para ello utilizaremos el editor online [codepen.io](https://codepen.io). Como bien explicamos, todo el contenido de tu página va dentro de la etiqueta `<body>`. En este editor en línea, el `<body>` está representado por el cuadro de HTML.
 
Digamos que queremos un título grande. Para eso usamos la etiqueta `<h1>`, que viene de *Heading 1*:
 
```html
<h1>Mi Primera Página Web</h1>
```
 
¿Y si queremos texto normal? Usamos la etiqueta `<p>`, que significa párrafo:
 
```html
<p>Hola, estoy aprendiendo a hacer páginas web</p>
```
 
Ahora repliquemos la caja genérica paso a paso:
 
```html
<div class="mi-clase" id="mi-id">
  <h2>Sección Agrupada</h2>
  <p>Este Texto Vive Dentro de una Caja más Grande</p>
</div>
```
 
Noten cómo está ordenado el código. Las cajas que están dentro de otras tienen un pequeño espacio a la izquierda. Esto se llama **indentar**, y es vital para no perdernos.
 
---
 
## Cierre
 
Hoy aprendimos que una página es solo un sistema de cajas dentro de cajas. La declaración `DOCTYPE`, el `<html>`, luego `<head>` y `<body>`, y adentro los títulos y párrafos. Jueguen con esto y nos vemos en la próxima lección.
