# Clase 03: Lectura

    La estructura de los archivos HTML son muy importantes, por ello se debe definir hasta los tipos de listas (ordenadas y no ordenadas).

    Además conoceremos sobre los Arrays y la poderosa herramienta que esta puede sere, sobre todo en el momento de almacenar datos.

## Aprende HTML

1. ¿Cuándo se puede utilizar un `lista no ordenada` en tu documento HTML?

    Como dice su propio nombre: "lista **no ordenada** es para crear listas en donde el orden de los elementos de estas no debe ser prioritaria, por lo tanto, en vez de tener números, llevará viñetas.

2. ¿Cómo cambiar el `estilo bullet` de la lista de elementos no ordenados?

    Para modificar cualquier estilo se deberá manejar en el archivo CSS, para este caso sería:

    ```
    ul {
        list-style-type: ___;
    }
    ```

    En la parte en blanco puede ir:

    - square
    - circle
    - disc
    - none

3. ¿Cuándo debes usar una `lista ordenada`o `lista no ordenada`en tu documento HTML?

    Como mencioné en la primera pregunta, varía depende del criterio del programador, si desea crear una lista donde se dará prioridad el orden de esta lista para enumerarlo.

4. Describe dos formas en las que puedes cambiar lo números en los `elementos de la lista` proporcionados por una `lista ordenada`

    Para ambas formas utilizaremos el atributo *"type"*, y las dos formas sería:

    + InLine:

        ```
        <ol type="A">
            <li>Elemento Ordenado 1</li>
            <li>Elemento Ordenado 2</li>
            <li>Elemento Ordenado 3</li>
        </ol>
        ```
    
    + Modificación en Style (Ya sea en un \<style> o en un archivo externo CSS):

        ```
        <style>
            ul {
                type: "A";
            }
        </style>
        ```

## Aprende CSS

1. Describe las propiedades de `margin` y `padding` en CSS como si fueran los personajes de una historia. ¿Cuál es el rol en lahistoria: "El Box Model"?

    

2. Enumera y describe las **cuatro** partes ded un box del elementos HTML según el `box model`



## Aprende JS

1. ¿Qué `tipos de daots`puedes almacenar en un `Array`?



2. ¿El array `people` es un de JavaScript válido? De ser así, ¿cómo puedo acceder a los valores almacenados? Y si no, ¿por qué?

    ```
    ¿const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
    ```



3. Enumera **cinco** operadores abreviados de asignación en javascript y describe lo que hacen.



4. Lee el código a continuación, evalúa la último `expresión` y explica cuál sería el resultado y por qué

    ```
    let a = 10;
    let b = 'dog';
    let c = false;

    // evalúa esto
    (a + c) + b;
    ```

5. Describe un ejemplo cotidiano de por qué una declaración condicional se debería usar en un programa en JavaScript

6. Da un ejemplo de por qué un `Bucle`es útil en JavaScript

## Cosas de las que quiero saber más

    Quiero saber más sobre todo lo que conlleva a los Arrays, qué métodos tiene para realizar búsquedas, añadir nuevos elementos, eliminar de acuerdo a la posición, etc.
