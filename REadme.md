# **Mi Primera página web**
~~~ 
En este taller conocerás el funcionamiento de una página web y aprenderás a crear una página web desde cero con la estructura HTML y agregar estilos con CSS, además se utilizará Bootstrap para facilitar la creación.
~~~

##  **Competencias Generales**
### - Crear páginas web desde cero.
### - Integrar Bootstrap al proyecto.


![miprimerapagina](assets/img/DesMoments.jpg)


## **Introducción a páginas web**
## **¿Qué es una página web?**

~~~

Si buscamos en google, posiblemente encontremos desde respuestas muy complejas a que la respuesta esta en nuestro corazón, así que definiremos de forma muy simple algunos términos.

WebPage (página web): Es un documento que puede ser visto en la pantalla a través de un navegador como Firefox, Google Chrome, Internet Explorer. sólo es un documento.

Website (sitio Web): Es una colección de páginas(documentos), agrupadas y conectadas, generalmente de un mismo tema o tópico.

Web Server (servidor Web): Es un computador que guarda los archivos de los sitios web.

CSS(Cascading Stylesheets): Significa hojas de estilo en cascada y es un lenguaje para definir estilos a las etiquetas HTML. CSS también puede definir como los elementos pueden ser mostrados.

JS (JavaScript): Es un lenguaje de programación que permite modificar dinámicamente elementos de HTML y CSS y de esta forma agregar componentes y comportamientos nuevos a la página web así como agregar diversos tipos de animaciones e interactuar con información de otros sitios web.
~~~

## **¿Qué es la Estructura HTML?**
~~~
Un archivo HTML para poder ser interpretado correctamente deber tener una estructura. Esta estructura básica consiste en una cabeza (head) y un cuerpo (body), la cabeza contiene toda la información que es para el navegador, el cuerpo de la página contiene toda la información que es para el usuario. Dentro de las etiquetas HTML se encuentra todo el contenido de la página, y dentro de ellas están los dos bloques previamente mencionados. La estructura de una página en HTML es la siguiente:
~~~


    <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Document</title>
        </head>
        <body>        
        </body>
    </html>




~~~
El doctype (o tipo de documento) es la primera etiqueta que leeremos y le indica al navegador como debe interpretar el resto del documento. En el ejemplo veremos que el doctype especificado es de HTML5, el cuál es el estándar de actual.

La etiqueta <html> especifica que desde ese punto en adelante todo lo que venga deberá ser interpretado como HTML.

En HTML la etiqueta <head> Contendrá información variada, desde dónde encontrar las hojas de estilo o los iconos, hasta cuál es el título del sitio o sencillamente cómo debe manejar la página en el caso de que tenga que adaptarse a distintos tamaños de pantalla.
~~~

## **¿Qué es CSS?**
~~~
CSS es acrónimo de Cascading Style Sheet, o sea hojas de estilo que se pueden incorporar dentro de HTML para darle forma y color a nuestra voluntad.

Hay tres formas de incorporar CSS dentro de una página web.

La primera es con un conjunto de atributos y valores dentro de la etiqueta del mismo HTML.
La segunda consiste en agregar el CSS dentro del head del mismo documento HTML.
La tercera forma consiste en utilizar un archivo externo.
La forma recomendada de trabajar es la 3º, pero para explicar como funciona CSS ejemplificaremos sobre la primera y se dará una breve explicación de la segunda.

Sintaxis y primera forma
Todas las instrucciones en CSS se escriben en pares propiedad: valor, para agregar CSS sobre una etiqueta HTML (Primera forma) debes agregar a la etiqueta style="propiedad: valor"
Un ejemplo: color para un párrafo
~~~

    <p style="color: red"> </p>


## ** ¿Qué es Bootstrap? **

~~~
Bootstrap es el framework más popular para el desarrollo de sitios responsive en la web, su código es compatible con SaSS y LESS por lo que podemos trabajar en nuestro preprocesador favorito sin problemas, además existen cientos de herramientas y plantillas que podemos integrar directamente con Bootstrap.

Framework: Es un entorno o marco de desarrollo que estandariza herramientas para resolver problemas de índole similar.

Responsive: Se refiere a la facultad de que tu página se vea bien en cualquier dispositivo ( escritorio, tablets, teléfono).

Sass: Syntactically Awesome Style Sheets, Facilita diversos aspectos de la creación de CSS al añadir mejoras de pre-procesamiento.

Less Leaner Style Sheets, Cumple la misma función que SaSS son herramientas que compiten entre ellas y sus funciones son muy similares pero la sintaxis cambia.
~~~


