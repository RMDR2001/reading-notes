# Read 06

## Promp sugerido para iniciar

```
Crea un artículo en español de aproximadamente 300 palabras sobre: "React - Pasar funciones como props".
Orientado a personas que ya tienen fundamentos sólidos en programación con Javascript.
Sin embargo, recién han iniciado a crear interfaces modernas con React y saben: Crear componentes con JSX, pasar props y gestionar el estado en componentes.
Incluye: ¿Por qué usarlo?, Ejemplo básico y Explicación a profundidad.
Evita sugerir o hablar sobre otros conceptos más avanzados.
```

### Respuesta de CHAT GPT 

    # React - Pasar funciones como props

    En React, pasar funciones como props permite la comunicación entre componentes, especialmente cuando un componente hijo necesita modificar el estado del padre o ejecutar una lógica definida en él.

    ## ¿Por qué usarlo?
    React maneja un flujo de datos unidireccional (de padres a hijos con props). Sin embargo, a veces un componente hijo necesita modificar el estado del padre. Para esto, el padre define una función y la pasa como prop, permitiendo que el hijo la invoque en respuesta a eventos.

    ## Ejemplo básico
    Supongamos que tenemos un componente `Contador` que muestra un número y un botón para incrementarlo. La lógica del estado está en el componente padre `Contador`, mientras que el botón está en el hijo `BotonIncrementar`.

    ```jsx
    import { useState } from "react";

    function BotonIncrementar({ incrementar }) {
        return <button onClick={incrementar}>Incrementar</button>;
    }

    function Contador() {
        const [contador, setContador] = useState(0);

        const incrementarContador = () => setContador(contador + 1);

    return (
        <div>
            <h1>Contador: {contador}</h1>
            <BotonIncrementar incrementar={incrementarContador} />
        </div>
    );
    }
    ```
    export default Contador;


    ## Explicación
    1. **Definir la función en el padre**: `incrementarContador` actualiza el estado.
    2. **Pasar la función como prop**: `incrementarContador` se pasa a `BotonIncrementar`.
    3. **Ejecutar la función en el hijo**: `BotonIncrementar` la recibe y la ejecuta en `onClick`.

    Esta técnica centraliza el estado y permite reutilizar componentes, clave para interfaces escalables en React.

## Reflexiones para Analizar Críticamente

### 1. Comunicación de datos vs comunicación de eventos

¿En qué se diferencian las props que envian datos estáticos de las funciones como props que envían eventos o decisiones?

### 2. Responsabilidad y flujo de control

Si un componente padre le pasa una función al hijo para que la use cuando el usuario haga clic, ¿quién realmente tiene el control de lo que pasa al final? ¿El padre o el hijo?

### 3. Estado centralizado vs estado local

Considera cuándo es mejor manejar el estado directamente en el hijo y cuándo conviene centralizarlo en el padre. ¿Cómo afecta esto la escalabilidad y el mantenimiento del código?

### 4. Funciones anónimas y de flecha

En muchos ejemplos de React, se usan funciones de flecha directamente dentro de un `onClick` o al pasar funciones como props. ¿Qué implicaciones tiene esto en términos de perfomance y re-denrizado? ¿Es siempre la mejor práctica o hay situaciones donde debría evitarse?

### 5. Delegación de responsabilidades

Imagina un componente hijo que necesita valida datos antes de llamar a la función del padre. ¿Dónde debería ocurrir esa validación: en el hijo o en el padre?

### 6. Escalabilidad y legabilidad

Si un componente padre pasa múltiples funciones como props a un componente hijo (seleccionar, eliminar, actualizar, etc.), ¿cómo afecta esto la legabilidad y mantenibilidad del código?
