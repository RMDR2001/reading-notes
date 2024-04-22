# Clase 05: Lectura

## Lecturas: Imágenes, Color, Texto

### Medios en HTML

1. ¿Cuál es un caso práctica del atributo `alt` en una página web?

    El atributo `alt` permite dar una "texto alternativo", donde se indica una descripción textual de, por ejemplo, una imagen:

    `<img src="ejemplo.jpg" alt="Descripción de la imagen">` (Ejemplo dado por Chat.OpenAI)

2. ¿Cómo puedes mejorar la accesibilidad de las imágenes en un documetno HTML?

    - Colocando todas las imágenes en una sola carpeta para que sea fácil ubicarla.
    - Las imágenes deben tener un nombre claro.
    - En el texto a leer en la actividad recomienda que se le coloque un título a la imágen.

3. Da un ejemplo en el que el elemento `figure` sería útil en un documento HTML.

    \<<Ejemplo dado por: ["IMAGENES EN HTML"](https://developer.mozilla.org/es/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML#comentar_im%C3%A1genes_con_figure_y_figcaption)>>:

    ```
    <figure>
        <img
            src="images/dinosaur.jpg"
            alt="La cabeza y el torso de un esqueleto de dinosaurio; tiene una cabeza grande con dientes largos y afilados"
            width="400"
            height="341" />

        <figcaption>
            Exposición de un T-Rex en el museo de la Universidad de Manchester.
        </figcaption>
    </figure>
    ```

4. Describe la diferencia entre una imagen `gif` y una imagen `svg`, imagina que se lo estás explicando a una persona mayor de tu comunidad.

    SVG es un formato de imagen vectorial, quiere decir que utiliza vectores matemáticos para la calidad de imagen, por ende, son escalables y la calidad no perdería, en cambio en los gif, se define los colores por pixeles.

5. ¿Qué tipo de imagen usuarias para mostrar una captura de pantalla en tu página web y por qué?

    Según el texto: \<<[Imagen file type and format guide](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types)>>, podemos deducir que la mejor manera sería png, ya que es una de los más populares, más usados y más compatibles y distintos navegadores web.

### Aprende CSS

1. Describe la diferencia entre un color de primer plano y un color de fondo de un elemento HTML, imagina que estás hablando con una persona sin conocimientos técnicos.

    El color de primer plano es un color principal, predominante, que se puede ver sin ninguna dificultad, y un color de fondo, como su nombre lo dice, debe ser un color más claro y que no provoque dificultad para leer el texto o sature la vista del usuario.

2. Tu amigo te pide que le des un retoque a este blog sin colores ¿Cómo usarías el color para darle un poco de personalidad a este blog?

    Primero preguntaría que color le gustaría tener su blog, de acuerdo a eso, podría usar una herramiento para ver paletas de colores, para ver colores compatibles y demás.

    De acuerdo a eso se define colores principales, secundarios, colores de primer plano, etc.

3. ¿Qué debes tener en cuenta al escoger tipos de letra para un documento HTML?

    - Que haya compatibilidad en la mayoría de navegadores.
    - Que cumpla con las espectativas de historias de usuario.
    - Que sea legible.

4. ¿Cuál es la relación entre `font-size`, `font-weight`, y `font-style` con los elementos de textos en HTML?

    - **font-size:** Ayuda a modificar el tamaño del texto
    - **font-weight:** Ayuda a modificar el ancho (grosor) del texto
    - **font-style:** Ayuda a modificar el estilo del texto (negrita, cursiva)

5. Describe dos formas de añadir espaciado alrededor de los caracteres mostrados en un elemento `h1`

    1. Utilizando y modificando el margin
    2. Utilizando y modificando el padding

## Cosas de las que quiero saber más

    Me gustaría saber como estructurar un archivo css, cuales son las buenas praxis para modificar en un archivo css