# chekpoint 11

## 1. ¿Por qué usamos ramas en Git?

**Qué es**  
Las ramas en Git son versiones paralelas de un proyecto. Permiten trabajar en nuevas funcionalidades, correcciones de errores o experimentos de manera aislada, sin afectar la versión principal del proyecto.

**Beneficios**  
- **Aislamiento**: Permite trabajar en nuevas características o correcciones de errores sin interferir con el código en la rama principal.
- **Colaboración**: Varios desarrolladores pueden trabajar en diferentes ramas simultáneamente sin conflictos.
- **Historial limpio**: Facilita un historial de cambios organizado y más comprensible.

**Cuándo lo usarás**  
Cuando estés desarrollando una nueva funcionalidad, trabajando en correcciones de errores, o probando nuevas ideas que no quieres que afecten el código de producción.

**Por qué lo usarás**  
Para mantener un entorno de desarrollo ordenado, seguro y colaborativo, evitando que los cambios experimentales o incompletos afecten al código que está en producción o en otras ramas.

## 2. ¿Cuál es el comando para crear un repositorio Git?

**Comando** 
bash
git init

 ### Qué hace
Este comando inicializa un nuevo repositorio Git en el directorio actual, creando una carpeta oculta llamada .git que contiene toda la información necesaria para gestionar versiones del proyecto.

# 3. ¿Qué es un conflicto de fusión?
### Qué es
Un conflicto de fusión ocurre cuando Git no puede combinar automáticamente los cambios de dos ramas porque hay modificaciones en las mismas líneas de código en ambas ramas. Git requiere intervención manual para resolver qué cambios deben conservarse.

### Beneficios de resolverlo correctamente

Integridad del código: Asegura que los cambios finales sean correctos y no se pierda ninguna modificación importante.
Colaboración efectiva: Resuelve diferencias entre desarrolladores que trabajan en el mismo archivo.
Cuándo lo resolverás
Durante una fusión (merge) de ramas, especialmente cuando ambas ramas han realizado cambios en las mismas líneas de código.

### Por qué lo resolverás
Para garantizar que la fusión resulte en un código funcional que incluya todos los cambios necesarios sin errores.

# 4. ¿Qué es el DOM?
### Qué es
El DOM (Document Object Model) es una representación estructurada de un documento HTML o XML. Permite a los lenguajes de programación, como JavaScript, acceder y manipular el contenido, estructura y estilo del documento.

### Beneficios

Interactividad: Facilita la creación de aplicaciones web interactivas manipulando elementos en tiempo real.
Accesibilidad: Permite acceder y modificar cualquier parte del documento a través de scripts.
Estructura organizada: Representa el documento como un árbol de nodos, donde cada nodo corresponde a una parte del documento.
##Cuándo lo usarás
Cada vez que necesites interactuar con el contenido o la estructura de una página web mediante JavaScript.

### Por qué lo usarás
Para crear aplicaciones web dinámicas y responsivas, donde el contenido pueda cambiar sin recargar la página.

5. ¿Qué es un Event Listener?
### Qué es
Un event listener (escuchador de eventos) es una función que espera un evento específico, como un clic o una pulsación de tecla, en un elemento de la página. Cuando ocurre el evento, ejecuta una función específica.

### Beneficios

Interactividad: Permite que la página web responda a las acciones del usuario.
Modularidad: Separa la lógica del evento de la lógica de la aplicación, facilitando el mantenimiento.
Flexibilidad: Puede ser utilizado para múltiples tipos de eventos y en múltiples elementos.
Cuándo lo usarás
Cuando necesites que tu aplicación web responda a las acciones del usuario, como clics, movimientos de ratón, o entrada de teclado.

### Por qué lo usarás
Para mejorar la experiencia del usuario haciendo la página web interactiva y dinámica.

Ejemplo

```javascript
document.getElementById("miBoton").addEventListener("click", function() {
    alert("¡Botón clickeado!");
});
 ```
1. ¿Qué es un Query Selector?
Qué es
El querySelector es un método de JavaScript que permite seleccionar el primer elemento del DOM que coincida con un selector CSS especificado.

### Beneficios

Precisión: Selecciona elementos de manera precisa usando los mismos selectores que en CSS.
Flexibilidad: Puede seleccionar elementos por clase, id, atributo, o cualquier otro selector CSS.
Simplicidad: Facilita el acceso a elementos específicos del DOM sin necesidad de recorrer toda la estructura.
Cuándo lo usarás
Cuando necesites acceder a un elemento específico en el DOM para modificarlo o para agregarle un event listener.

### Por qué lo usarás
Para manipular elementos en el DOM de manera precisa y efectiva, utilizando un método sencillo y flexible.
```javascript	
let elemento = document.querySelector(".miClase");
```