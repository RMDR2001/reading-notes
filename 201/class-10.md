# Read 10

## ¿Qué ha salido mal? Corrigiendo JavaScript

1. Menciona algunas diferencias clave entre un **Syntax Error** y un **Logic Error**

    - **Syntax error** o como su traducción al español **error de sintaxis** son los errores más fáciles de corregirlos ya que nos mandan mensajes de error que tendremos que leerlos y descubrir el error, que son ocacionados comunmente por errores de ortografía y algo que provoca que el código deje de funciar a mitad y no complete todo el algortimo.

    - **Logic Error**, al español: **error lógico**, a diferencia de los de sintaxis, son más difícles de corregir, ya que no hay mensaje de errores, estos errores se dan cuando no hay errores sintácticos, por ende, el programa no da el resultado que buscamos.

1. Enumera algunos tipos de errores que has encontrado en las tareas de laboratorio anteriores y explica cómo fuiste capaz de corregirlos

    - La mayoría de errores que encontré fueron de sintaxis, ya que me en la consola me mandaba la alerta, que la función getElementById(); no encontraba el id que le enviaba, y tras muchos intentos, buscando y leyendo las líneas de código donde me mandaba la alerta de error, resulta que me falta colocar una función del DOM para poder vincular ambos archivos y se pudo corregir.

    - Otro error que me frecuentaba y no me daba mensaje de error era en el proyecto about-me, en la parte de las respuestas, ya que sintácticamente estaba correcto, pero no me daba la respuesta que quería, no me comparaba correctamente las respuestas del usuario, tuve que leer el código línea por línea en la función que había detectado dónde podría estar el error, y di que había un problema en las comparaciones, debió ser una comparación estricta y convertir las respuestas con la función Lower Case.

1. ¿Cómo este tema influye en tus metas a largo plazo?

    Pues, al ser dev, es prácticamente imposible que un proyecto salga bien a la primera, y no que no tenga ningún error, pues somos humanos, y el facto humano siempre está dentro de los proyectos, por ende hay un porcentaje de que exista algún error durante el desarrollo del proyecto, es importante saber como interpretar alertas de errores sintácticos, y aprender a detectar errores lógicos y como solucionarlos. Y todo esto se aprende con la experiencia.

## El depurador de JavaScript

1. ¿Cómo le describirías la herramienta de depuración de JavaScript y su función a una persona que recién comienza en el desarrollo de software?

    La mejor manera de explicarlo es citando a [El depurador de JavaScript](https://developer.mozilla.org/es/docs/Learn/Common_questions/Tools_and_setup/What_are_browser_developer_tools#el_depurador_de_javascript):

    > El depurador de JavaScript te permite observar el valor de las variables y establecer puntos de interrupción, lugares en tu código en los que deseas pausar la ejecución e identificar los problemas que impiden que tu código se ejecute correctamente.

1. Define que es un breakpoint

    Según la respuesta dada por ChatGPT:
    > Un breakpoint, en el contexto de la programación y especialmente en el desarrollo de software, es un punto predefinido en el código donde la ejecución del programa se detiene temporalmente con el fin de permitir a los desarrolladores examinar el estado del programa en ese punto y depurar posibles errores. Los breakpoints son herramientas fundamentales en los entornos de desarrollo integrados (IDE) y se utilizan comúnmente para inspeccionar variables, seguir la ejecución del programa línea por línea y entender el flujo de control del código durante el proceso de desarrollo y depuración.

1. ¿Qué es el call stack?

    En pocas palabras, una sección encargada de mostrar todo el código que se ha ejecutado para llegar a la actual línea.

## Cosas de las que quiero saber más

    Me gustaría saber más sobre los errores y la manera de interpretar **correctamente** las alertas de errores, ya que muchas veces se me ha complicado la lectura de estos y los reportes que dan, ya que indican la línea de código donde se encuentra el error, pero muchas veces es una línea arriba, o una abajo... No entiendo muy bien.
