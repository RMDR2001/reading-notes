# Clase 09: Lectura

## Formularios en HTML

1. **¿Por qué los formularios son tan importantes en el desarrollo web?**

    Su importancia se debe a que es "uno de los principales puntos de interacción entre un usuario y un sitio web o aplicación"

2. **Al diseñar un formulario, ¿cuáles son algunas de las cosas más importantes a tener en cuenta sobre la experiencia de usuario?**

    - Según el texto [Diseñar tu formulario](https://developer.mozilla.org/es/docs/Learn/Forms/Your_first_form#dise%C3%B1ar_tu_formulario) es importante tomarnos el tiempo necesario para **pensar en tu formulario**.

    - Mientras más grande sea el formulario, la probabilidad de frustrar y perder al usuario es mayor.

3. **Enumera 5 elementos de los formularios y explica su importancia**

    - \<form>: Es el principal, ya que con este elemento se indica que se hará un formulario.

    - \<label>: Permite definir de manera "formal una etiqueta para un control de un formulario HTML", es considerado imporante ya que apoya a que nuestro formulario sea más accesible.

    - \<input>: Es un espacio donde el usuario podrá ingresar la información solicitada, obviamente su importancia se debe a que los formularios están hechos para recopilar información, y la manera de hacer es con un input.

    -\<button>: Los botones son otros elementos que se deben consideran importantes en un formulario, es especial uno que va al final de este, que se le denomina Submit, ya que con ese se podrá enviar la información al dueño de la página web y reciba la información otorgada por el usuario.

    - \<select>: Es un elemento que nos sirve para que el usuario pueda seleccionar una opción, nos sirve en caso necesitamos que el usuario mande sí o sí un dato que necesitamos estrictamente, para evitar que el usuario escriba mal las cosas u otro error humano, entonces a veces es mejor dar una lista con ciertas opciones de respuestas esperadas.

## Aprende JS

1. **¿Cómo describías los event a un amigo sin conocimiento técnico?**

    El evento podríamos definirlo como una **acción específica** que ocurre en la interfaz del usuario en una página web. Estas acciones nos aydaría a interactuar con el usuario y que el programador lo use para que se realice alguna cosa en la página web.

2. **Al utilizar el método `addEventListener()`, ¿cuáles son los 2 arguments que debes proporcionar?**

    Con ayuda de [devdocs.io](https://devdocs.io/dom/eventtarget/addeventlistener) podemos definir los dos argumentos:

    1. type: "Una cadena sensible a mayúsculas y minúsculas que representa el tipo de evento al que escuchar"

    1. listener: "El objeto que recibe una notificación (un objeto que implementa la interfaz de Evento) cuando ocurre un evento del tipo especificado. Esto debe ser null, un objeto con un método handleEvent(), o una función de JavaScript. Consulta El callback del escuchador de eventos para obtener detalles sobre el propio callback"

3. **Describe el objeto event. ¿Por qué el target dentro del objeto event es útil?**

    Luego de haber leído la descripción en la pregunta 1 y tener conocimiento de los argumentos de la pregunta 2, es necesario indicar el tipo del evento a escuchar, ya que con eso sabemos como es la interacción del usuario para con la página web, por eso es que se considera útil.

4. **¿Cuál es la diferencia entre event bubbling y event capturing?**

    Gracias a la respuesta brindada por el modelo de inteligencia artificial de OpenAI tenemos, sabemos que:

    - Ambos son dos fases diferentes en el proceso de propagación de eventros en el DOM

    - Event Capturing:

        - "El evento se captura en la parte superior del árbol DOM y se propaga hacia abajo hasta llegar al objetivo del evento"

        - "Los eventos se manejan primero en el elemento raíz del árbol DOM y luego se propagan hacia abajo hasta llegar al elemento objetivo"

        - "Es decir, el evento se detecta desde el nodo exterior hacia el nodo interior del árbol DOM"

    - Event Bubbling:

        - ''Después de que el evento alcanza su objetivo y se maneja, comienza la fase de "bubbling"''

        - "Durante esta fase, el evento se propaga desde el objetivo hacia arriba a través de los ancestros en el árbol DOM"

        - "Es decir, el evento se propaga desde el nodo objetivo hacia el nodo exterior del árbol DOM"

## Cosas de las que quiero saber más

    Tengo interés con respecto a Event Capturing y Event Bubbling, ya que tenemos el conocimiento teórico, pero no tengo clara la idea de como se aplica en la práctica.
