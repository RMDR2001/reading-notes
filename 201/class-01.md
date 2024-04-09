# Clase 01: Lectura

## Primeros Pasos

1. **Crea un poema corto describiendo cómo HTTP envía datos entre computadoras**

    Todo lo que busca el cliente,
    lo tiene un servidor existente,
    y el navegador de manera muy insistente,
    va pidiendo mediante peticiones http,
    una copia para que pueda verlo nuestro cliente.

2. **Describe como los archivos HTML, CSS y JS son "analizados" en el navegador**

    Primero analiza e interpreta el archivo HTML para saber todo el contenido que este tiene, para luego revisarlo y estructurarlo de acuerdo al orden que está.
    Luego gracias a los archivos CSS determina la estética de cada uno de los elementos y las modificaciones que ha tenido para poder detallarlos en el monitor deel usuario, para luego revisar el JS y termina todo el análisis.

    ¡Y todo eso en cuestión de segundos!

3. **¿Cómo puedes encontrar imágenes para agregar a una página web?**

    Simple! Solo tienes que hacer clic derecho en la imagen que desees agregar (previamente buscada en tu navegador), se le da a guardar imangen y la guardas en la carpeta de tu proyecto.
    
    Otra manera, ha repitiendo los pasos pero en vez de dar a guardar imágene, se copia la dirección web de la imágen y se invoca con una url en nuestro html.

4. **¿Cómo creas una `String` en comparación con un `Number`en Javascript?**

    Usando un comparador simple: `==` ya que va a ver el valor de ambos y no si es un String o un Number, OJO! Si usas un comprador estricto: `===` indicará un error porque son tipos de variables distintas.

5. **¿Qué es una `Variable` y por qué son importantes en JavaScript?**

    Una variable es un espacio de memoria destinada a guardar información, son importantes porque como mencioné antes, permite almacenar información que debe ser útil para el desempeño del programa.

## Introducción a HTML

1. **¿Qué es un atributo en HTML?**

    Se le puede considerar como una **caracterísitca adicional** a un elemento para modificarlo.

2. **Describe la anatomía de un elemento en HTML**

    Como vimos en las clases Code 102, cuenta de 3 partes, un "Opening tag", un "Closing tag" y un "Content" (Como muestra la imágen del texto "Primeros pasos con HTML"), la etiqueta de apertura, como dice el nombre abre la etiqueta, ahí dentro podemos añadir atributos; luego en el contenido, como se deduce va el contenido del elemento y por último en la etiqeuta de cierra permite cerrar el elemento.

3. **¿Cuál es la diferencia entre las etiquetas `<article>`y `<section>`**

    Según una comparacióne extraída con ayuda de el Modelo IA de OpenAI, `<article>`es utilizado para un "contenido autónomo y autocontenido", mientras que `<section>` se utiliza para "agrupar contenido relacionado".

4. **¿Qué elementos se incluyen en una página web "típica"?**

    Debería contender:

    - \<head>
    - \<body>
        - \<header>
        - \<main>
        - \<footer>

5. **¿Cómo influyen los metadatos en el Posicionamiento en buscadores (SEO)?**

    Los metadatos vana proporcionar información importante sobre el contenido de nuestra página web ayudando a su visibilidad.

6. **¿Cómo se utiliza la etiqueta `<meta>` en HTML cuando se quiere especificar metadatos?**

    Meta se puede utilizar para:

    - Especificación de la codificación del documento

        `<meta charset="UTF-8">`

    - Especificar la descripción de páginas web

        `<meta name="description" content="Descripción del contenido de la página web">`

    - Especificar palabras claves

        `<meta meta="keywords" content="palabra clave1, palabra clave2">`

    - Indicar el autor del documento

        `<meta name="author" content="Nombre del autor">`

    - Especificar el viewport para un diseño adaptable

        `<meta name="viewport" content="width=device-with, initial-scale=1.0">`

    - Especificación de la vista previa de la pa´gina en redes sociales (Este es aportado por ChatGPT! Que desconocía que podía hacerse esto!)

        `<meta property="og:title" content="Título de la página">`

        `<meta property="og:description" content="Descripción de la página">`

        `<meta property="og:image" content="URL de la imagen">`

        `<meta property="og:url" content="URL de la página">`

## Miscelánea

### ¿Cómo empiezo a diseñar mi sitio web?

1. **¿Cuál es el primer paso para diseñar una página web?**

    El primer paso es **"DEFINIR LO QUE SE QUIERE LOGRAR CON ÉL"**

2. **¿Cuál es la pregunta más importante que se debe responder al diseñar una página web?**

    - ¿Qué es exactamente lo que quiero lograr?

    - ¿Cómo un sitio web me ayudará a alcanzar mis metas?

    - ¿Qué es necesario hacer, y en qué orden, para alcanzar mis metas?

### Semántica

1. **¿Por qué se debe utilizar un elemento `<h1>`en vez de un `<span>` para mostrar un título de primer nivel?**

    `<h1>` está hecho para que se le de la función de encabeza de nivel superior, en cambio `<span>`"puede hacer que cualquier elemento *parezca* un títutlo de nivel superior"

2. **¿Cuáles son los beneficios de utilizar etiquetas semánticas en nuestro HTML?**
    Favorece en la legibilidad y accesibilidad en el código.

### ¿Qué JavaScript?

1. **Describe 2 cosas que *requieran* de JavaScript en el navegador.**

    (Estracto de respuesta otorgado por Open AI, porque no entiendo bien la pregunta)

    - Interactividad del usuario:

        La interactividad del usuario es una parte esencial de muchas aplicaciones web modernas. JavaScript permite crear elementos interactivos como botones, formularios, menús desplegables, ventanas emergentes, carruseles de imágenes, entre otros.
        Las acciones del usuario, como hacer clic en un botón, enviar un formulario, arrastrar y soltar elementos, cambiar el tamaño de una ventana, etc., pueden desencadenar eventos JavaScript que realizan acciones específicas en respuesta.
        Por ejemplo, al hacer clic en un botón de "Me gusta" en una publicación de redes sociales, se puede utilizar JavaScript para enviar una solicitud al servidor y actualizar la interfaz de usuario para mostrar el nuevo recuento de "Me gusta" sin necesidad de recargar la página.
    
    - Manipulación del DOM (Document Object Model):

        El DOM es una representación del documento HTML de una página web que el navegador crea y con el que trabaja el JavaScript.
        JavaScript se utiliza para manipular el DOM dinámicamente, permitiendo agregar, eliminar o modificar elementos HTML y sus atributos en respuesta a eventos del usuario o a cambios en los datos.
        Por ejemplo, JavaScript se puede utilizar para crear una lista de tareas pendientes que se actualiza dinámicamente cuando el usuario agrega o elimina elementos de la lista. Esto se logra manipulando el DOM para agregar o eliminar elementos de la lista según las acciones del usuario.

2. **¿Cómo se puede añadir JavaScript a un documento en HTML?**

|   Usando la etiqueta `<script>`