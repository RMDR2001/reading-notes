# READ 01: Introducción a React y los Componentes

## Component_Based Architecture

1. ¿Qué es un componenten?

    Es una pieza que se podrá reutilizar durante el desarrollo de la interfaz, esto ayudará a segmentar la aplicación en bloques más peuqueños y así facilitará el diseño y mantenimiento.

2. ¿Cuáles son las caracterísiticas de los componentes?

    - Reutilizables
    - Sustituibles
    - No específicos del contexto
    - Escalables
    - Encapsulados
    - Independientes

3. ¿Cuáles son las ventajas de utilizar una arquitectura basada en componentes?

    Según la respuesta de Chat GPT, nos enlista las siguientes ventajas

    - Reutilización de Código
    - Modularidad    
    - Escalabilidad
    - Encapsulación
    - Mantenimiento Simplificado
    - Flexibilidad
    - Fácil Colaboración entre Equipos
    - Rendicimiento Optimizado
    - Pruebas y Depuración Simplificadas
    - Interoperabilidad
    - Mayor Legibilidad y Organización del Código
    Reducción de Costos y Tiempo

## What is Props and How to Use it in React

1. ¿Qué significa "props"?

    Viene de la abreviación de *properties*, refiriéndose al mecanismo que permite pasar datos de un componente padre a un componente hijo

2. ¿Cómo se utilizan los props en React?

    Para ver cómo se utiliza aquí un ejemplo:

    ```
    //Componente hijo
    function Saludo(props) {
        return (
            <h1> Hola {props.name}! </h1>;
        )
    }

    //Componente padre
    function App() {
        return <Saludo nome="Ricardo" />;
    }
    ```

3. ¿Cuál es el flujo de los Props?

    Primero recordas que dicho flujo es unidireccional, y sigue estos pasos:

    1. **Padre -> Hijo**: El componente padre pasa datos al hijo a través de los props

    2. **Inmutables**: El hijo no puede cambiar las props; si necesita cambios, se deben hacer en el padre.

    3. **Unidireccional**: Los datos fluyen siempre de arriba hacia abajo

    4. **Comunicación inversa (Hijo -> Padre)**: El hijo puede enviar datos al padre usando funciones pasadas como props.