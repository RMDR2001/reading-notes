# Lecturas: Conceptos básicos de HTML, CSS y JS

    HTML es estructura de una página, CSS es el diseño y JavaScript es el dinamismo de la misma.

## Sigue Leyendo Introducción a HTML

1. **¿Por qué es importante utilizar elementos semánticos en nuestro HTML?**

    Por la accesibilidad, ya que ayuda a que la estructura va a ser clara, siendo fácil la comprensión y navegación.

2. **¿Cuántos niveles de encabezado existen en HTML?**

    Existen 6 encabezados que comienzan del h1 al h6.

3. **¿Cuáles son algunos de los usos para los elementos `<sup>`y `<sub>`?**

    `<sup>`: Es un **sup**eríndice

    `<sub>`: Corresponde a un **sub**índice

4. **Al utilizar `<abbr>`, ¿qué atributo se debe añadir para proporcionar una ampliación del término?**

    Se debe debe añadir el atributo `'title=""'`

## Aprende CSS

1. **¿De qué formas podemos añadir CSS a nuestro HTML?**

    Podemos utilizarlo en `<head>` utilizando dentro `<style>` y dentro del documento HTML podemos escribir en formato CSS.

    Otra forma es inline, dentro de los atributos de un elemento HTML podemos modificarlo: `"style= ""`

    De otra manera es importar un archivo CSS externo a nuestro documento HTML dentro del head: `<link rel="stylesheet" href="styles.css>`

2. **¿Por qué deberíamos evitar utilizar estilos inline?**

    Por una buena praxis, es bueno utilizar solo HTML para la estructura de la página web, porque si utilizaramos estilos inline se vería desordenado y difícil de identificar elementos en documentos HTML.

3. **Revisa el código a continuación y responde a las siguientes preguntas:**

    1. **¿Que representa el selector?**

        Todos los elementos `<h2>` que se encuentren en el documento CSS

    2. **¿Qué componentes son declaraciones CSS?**

        Las declaraciones son cada línea dentro de las llaves:

        - color: black;

        - padding: 5px;

    3. **¿Qué componentes se consideran propiedades?**

        Podemos ver dos componentes cosiderados:

        - color

        - padding

    ```
    h2 {
        color: black;
        padding: 5px;
    }
    ```

## Aprende JS

### Fundamentos de Java Script

1. **¿Qué tipo de dato es una secuencia de texto entre comillas simples?**

    Se utiliza las comillas simples para los tipos de dato *String*

2. **Enumera 4 tipos de operadores en JavaScript**

    I. Aritméticos, como la suma, resta, multiplicación, división y módulo.

    II. De asignación, que se utiliza el signo igual (=)

    III. De Comparación, en donde hay igual a (==), igualdad estricta (===) y variaciones como mayor igual, menor igual, diferente a, etc.

    IV. Lógicos, que son el Y (&&), O (||) y NO (!)

3. **Describe un problema práctica que puedes resolver con una función**

    Como vimos en el Code 102, un problema práctica y común es el crear un validador en donde se repita hasta que el usuario ingrese un dato válido.

### Tomando decisiones en tu código - condicionales

1. **Si una declaración if comprueba un __ y si resulta ___, entonces el código se ejecutará**

    Todo if si la condicional está bien declarada el código se ejecutará, dando por resultado TRUE o FALSE

2. **¿Cuál es el uso del `else if`?**

    Permite ingresar otra comparación en caso la primera proposición sea falso, por ejemplo

    ```
    if (a == b) {            <-- Primera comparación (Que en este caso es falsa)
        return true
    } else if (a =! b){      <-- Segunda comparación (else if) porque el primer if es falso
        return true
    }
    ```

3. **Enumera 3 tipos de operadores de comparación**

    - Mayor que: `>`

    - Menor que: `<`

    - Igual que: `==`

4. **¿Cuál es la diferencia entre los operadores lógicos `&&`y `||`?**

    El operador lógico `&&` es conocido como `AND`, el cual hace que el comparador `if` retorne *TRUE* siempre y cuando ambas proposiciones a comprar sean verdad, en cambio con `OR`, o como en la pregunta indica: `||`, retorna *TRUE* siempre y cuando haya al menos una proposición verdadera.

## Cosas de las que quiero saber más

    Quiero saber si hay alguna "norma no escrita" que recomiendo cuantos IF podemos anidar como programadores, o siempre es bueno usar "switch" si se necesita más de 2 comparaciones.
