# Clase 06: Lectura

## Lecturas: Descripción del problema, Objetos y el DOM

1. **¿Cómo le describirías un objeto a un amigo sin conocimiento técnico con el que creciste?**

    Un objeto podría definirse como un **molde**, con el cual podemos crear varias copias que tengas sus caracterísiticas particulares, a parte de las que tiene definido ese molde.

2. **¿Cuáles son algunas de las ventajas de crear objetos literales?**

    Son mucho más fáciles de entender y declarar, por ende, varias veces se usan en lugar de las clases.

3. **¿En qué se diferencian los objetos de los arrays?**

    Según la respuesta dada por ChatGPT:

    - **Objetos**: Son colecciones de pares clave-valor donde las clasves son strings que identifican los valores asociados. Se accede a los valores por nombre.
    - **Arrays**: Son colecciones ordenadas de elementos accesibles por índices numérico. Los elementos se almacenan en un orden específico, empezando desde el ínidice 0.

4. **Da un ejemplo acerca de los momentos en los que necesitarías utilizar bracket notation para acceder a la propiedad de un objeto en vez de dot notation.**

    Utilizaré y mostraré el ejemplo que nos brinda el texto [Notación de Punto](https://developer.mozilla.org/es/docs/Learn/JavaScript/Objects/Basics#notaci%C3%B3n_de_punto):

    **Notación de Punto**
    ```
    persona.edad;
    persona.intereses[1];
    ```

    **Bracket Notation**
    ```
    persona["edad"];
    persona["nombre"]["pila"];
    ```

5. **Evalúa el siguiente código ¿A qué se refiere el término `this` y cuál es la ventaja de utilizarlo?**

    ```
    const dog={
        name: 'Sport',
        age: 2,
        color: 'white with black spots',
        humanAge: function(){
            console.log(`${this.name} is ${this.age*7} in human years`);
        }
    }
    ```

    Es un puntero, encargado de indicar que se utilizará el dato de la variable que se encuentre y/o objetenga en ese objeto ya definido.

## Introducción a DOM

1. **¿Qué es el DOM?**

    De sus siglas al español Modelos de Objeto de Documento, "es una interfaz de programación para los documentos HTML y XML" (Texto extrído de: [¿Qué es el DOM?](https://developer.mozilla.org/es/docs/Web/API/Document_Object_Model/Introduction#%C2%BFqu%C3%A9_es_el_dom))

2. **Describe brevemente la relación entre el DOM y JavaScript.**

    "El contenido de la pagina es almacenado en DOM y el acceso y la manipulación se hace vía JavaScript."
