# Clase 08: Lectura

## Learn CSS - Flexbox

1. **Flexbox está diseñado para contenido unidensional. Explica lo que significa esto.**

    En pocas palabras, está diseñado para arreglar elementos en una dirección, ya sea horizontalmente o verticalmente, pero no ambas al mismo tiempo.

2. **Explica la diferencia entre main axis y cross axis**

    - **Main Axis**: Dependendiendo de cómo se configure el *Flexbox* puede ser el eje principal de manera horizontal o vertical

    - **Cros Axis**: Por ende, este eje será perpendicular al Main Axis.

3. **¿Cómo es que utilizar ciertas propiedades de flexbox impacta negativamente en la accesibilidad?**
    Según ChatGPT:

    - **Orden Visual**: Flexbox permite cambiar el orden visual de los elementos sin cambiar su orden en el HTML (DOM). Esto puede confundir a los usuarios que depende de loctores de pantalla, ya que el orden de lectura puede no coincidir con el orden visual.

    - **Alineación Compleja**: Usar propiedades como justify-content y align-items para cambiar la posición de los elementos puede hacer que la navegación por teclado sea difícil. Los usuarios que navegan usando el teclado pueden no esperar la disposición no estándar de los elementos.

    - **Flexibilidad en el Tamaño**: Los elementos que crecen y se encogen (usando flex-grow y flex-shrink) pueden resultar en cambios inesperados en el tamaño y la posición de los elementos, lo cual puede ser confuso para los usuarios con discapacidades visuales o cognitivas.

    - **Focus y Orden de Tabulación**: Cambiar la disposición de los elementos puede afectar el orden de tabulación (la secuencia en la que se navega a través de los elementos con la tecla Tab). Esto puede desorientar a los usuarios que navegan con el teclado.

    - **Contenido Oculto**: A veces, se utiliza Flexbox para ocultar contenido fuera de la vista (por ejemplo, usando display: none o visibility: hidden). Los lectores de pantalla pueden ignorar este contenido, lo cual puede ser problemático si el contenido oculto es importante.

## CSS Layout - Flexbox

1. **¿Cuáles son algunas de las ventajas de utilizar flexbox sobre float?**

    - Alineación:

        - Flexbox: Centra y alinea elementos fácilmente.
        - Float: Es difícil de alinear correctamente.

    - Orden:

        - Flexbox: Cambia el orden de los elementos sin cambiar el HTML.
        - Float: No puedes cambiar el orden sin modificar el HTML.

    - Espacio:

        - Flexbox: Ajusta automáticamente el espacio entre elementos.
        - Float: Necesita ajustes manuales para distribuir el espacio.

    - Responsivo:

        - Flexbox: Funciona mejor en pantallas de diferentes tamaños.
        - Float: Requiere más trabajo para ser responsivo.

    - Centrado:

        - Flexbox: Centra elementos fácilmente.
        - Float: Centrar elementos es complicado.

2. **¿Cómo es que este tema se conecta con tus metas a largo plazo?**

    Como developer debo buscar un balance entre hacer productos en tiempos cómodos para el cliente y que tengan un buen resultado, y flexbox al tener varias ventajas me ayudaría a tener mejores resultados.

## Cosas de las que quiero saber más

Quiero saber más sobre flexbox, cuando es recomendable utilizarlo y aprender de eso con casos prácticos
