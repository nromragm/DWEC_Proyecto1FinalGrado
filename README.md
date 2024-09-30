# Proyecto 1

## 1. Idea de la Aplicación
La aplicación web propuesta es un servicio de streaming de videos similar a **Netflix** o **Amazon Prime Video**. Esta plataforma permitirá a los usuarios:

- Ver una selección de películas y series en línea.
- Gestionar listas de reproducción.
- Recibir recomendaciones basadas en su historial de visualización.

Las funcionalidades básicas incluirán:

- Búsqueda de contenido.
- Reproducción de videos.
- Gestión de usuarios.

## 2. Audiencia Objetivo
La web está dirigida a usuarios que buscan una solución económica y personalizada para el streaming de contenido multimedia ya sean estudiantes, trabjadores o cualquier persona interesada en ver películas y serieres en su tiempo libre.

La relevancia de la aplicación se basa en la popularidad y creciente demanda de plataformas de streaming accesibles y adaptables a los gustos individuales de los usuarios.

## 3. Análisis de Mercado
Se han investigado plataformas de streaming similares como [**Netflix**](https://www.netflix.com/es/), [**Hulu**](https://www.hulu.com/) y [**Amazon Prime Video**](https://www.primevideo.com/
). Las características comunes incluyen:

- Capacidad para buscar contenido.
- Reproducción de videos en alta calidad.
- Gestión de listas de reproducción.

### Oportunidades de diferenciación:
- **Interfaz de usuario simple y personalizada**: Adaptable tanto para dispositivos móviles como de escritorio.
- **Sistema de recomendaciones basado en historial de visualización**: Utiliza un algoritmo sencillo para sugerir contenido relevante.
- **Integración de una comunidad**: Donde los usuarios puedan dejar comentarios y calificaciones en películas y series.

## 4. Funcionalidades Clave
1. **Sistema de autenticación y gestión de usuarios**:
   - Registro e inicio de sesión.
   - Administración de perfiles de usuario.

2. **Catálogo de contenido**:
   - Listado de películas y series con información detallada (sinopsis, género, calificación, etc.).

3. **Reproductor de video**:
   - Streaming en alta calidad con controles básicos (play, pausa, rebobinar, etc.).

4. **Búsqueda y filtrado**:
   - Funcionalidad para buscar contenido y filtrar por género, año, entre otros.

5. **Recomendaciones**:
   - Sistema que sugiere contenido basado en el historial de visualización del usuario.

6. **Listas de reproducción y favoritos**:
   - Los usuarios pueden guardar contenido para verlo más tarde.

## 5. Modelos de Ejecución (c.e. 1a)
### Descripcion de **Cliente**: 

El cliente es el componente que inicia las solicitudes de servicio. Funciona en el dispositivo del usuario, como un navegador web, una app de escritorio o una aplicación móvil. Su trabajo principal es mandar solicitudes al servidor y recibir las respuestas.

Los clientes suelen mostrar una interfaz que permite a las personas usar los recursos y servicios que ofrece el servidor. A veces pueden procesar datos por su cuenta, pero necesitan del servidor para obtener información más compleja.

### Ejecución de Código en el Cliente

### Características:
1. **Ubicación de Ejecución**: El código se ejecuta en el navegador del usuario, permitiendo la ejecución local.

2. **Lenguajes Comunes**: JavaScript, HTML y CSS.

3. **Interacción con el DOM**: Permite manipular el Documento Object Model (DOM) directamente, actualizando contenido sin recargar la página.

4. **Carga Inicial**: Se puede cargar una gran cantidad de código en el cliente al principio, lo que puede hacer que la interacción inicial sea más lenta.

5. **Limitaciones de Seguridad**: Más vulnerable a ataques como Cross-Site Scripting (XSS).

6. **Interacción Asincrónica**: Permite solicitudes asíncronas al servidor mediante AJAX o Fetch API, mejorando la experiencia del usuario.

### Ejemplo de Flujo:
1. El servidor envía una página web con HTML, CSS y JavaScript al cliente.

2. El navegador procesa y ejecuta el JavaScript, permitiendo interacciones sin solicitar al servidor.

3. El cliente puede hacer solicitudes asíncronas al servidor si necesita información adicional.


### Descripción de **Servidor**: 

El servidor es la parte que responde a las solicitudes que recibe del cliente. Se encarga de almacenar y gestionar recursos, como bases de datos, archivos y aplicaciones. 

Los servidores pueden tener distintas características y configuraciones según para qué se vayan a usar. Algunos están dedicados solo a servir páginas web, mientras que otros se enfocan en la gestión de bases de datos o archivos.

### Ejecución de Código en el Servidor

### Características:
1. **Ubicación de Ejecución**: El código se ejecuta en un servidor web (dedicado, en la nube, o en un entorno de alojamiento compartido).

2. **Lenguajes Comunes**: PHP, Python, Ruby, Java, Node.js.

3. **Interacción con la Base de Datos**: Acceso directo a la base de datos para realizar operaciones complejas de consulta, manipulación y almacenamiento de datos.

4. **Control de Seguridad**: Mantiene la seguridad y el control sobre el entorno, evitando la exposición de código y datos sensibles.

5. **Rendimiento**: Puede ser más lento, ya que cada interacción requiere una nueva solicitud al servidor y respuesta.

6. **Generación de Contenido Dinámico**: Genera contenido dinámico que se envía al cliente como respuesta a las solicitudes.

### Ejemplo de Flujo:
1. El cliente (navegador) envía una solicitud al servidor.
2. El servidor procesa la solicitud, ejecuta el código y accede a la base de datos si es necesario.
3. El servidor envía la respuesta al cliente, generalmente en forma de HTML.

## Ventajas y desventajas de la arquitectura cliente servidor

| **Ventajas**                            | **Desventajas**                           |
|-----------------------------------------|-------------------------------------------|
| Centralización de datos                 | Dependencia del servidor                  |
| Reducción de conflictos de información  | Impacto de fallos del servidor            |
| Reducción de conflictos de información  | Estrategias de mitigación                 |
| Seguridad mejorada                      | Gestión de actualizaciones                |
| Medidas de protección                   | Desafíos en la actualización de clientes  |
| Control de acceso                       | Planificación de despliegues              |
| Escalabilidad                           | Problemas de concurrencia                 |
| Desarrollo independiente                | Manejo de múltiples peticiones            |
| Incremento de capacidad del servidor    | Balanceo de carga                         |

### Referencias: 
https://www.daemon4.com/empresa/noticias/arquitectura-cliente-servidor/

https://www.arsys.es/blog/todo-sobre-la-arquitectura-cliente-servidor


## 6. Lenguajes de Programación Web (c.e. 1c, 1d)

## **JavaScript**: 

Es un lenguaje de programación utilizado para agregar interactividad y dinamismo a los sitios web.

### Características

1. **Lenguaje interpretado:** Se ejecuta directamente en el navegador sin necesidad de compilación previa.

2. **Lenguaje dinámico:** No es necesario definir el tipo de las variables, lo que permite mayor flexibilidad.

3. **Orientado a objetos y basado en prototipos:** Soporta la programación orientada a objetos, con un modelo basado en prototipos en lugar de clases tradicionales.

4. **Asincrónico y no bloqueante:** Soporta la ejecución de código asincrónico, permitiendo realizar varias tareas sin bloquear el flujo principal.

5. **Multiplataforma:** Funciona en casi todos los navegadores y sistemas operativos.

6. **Gran ecosistema de librerías y frameworks:** React, Angular, Vue.js, Node.js, amplían su funcionalidad.

7. **Lenguaje de scripting del lado del cliente y servidor:** Puede usarse tanto en frontend como en backend (con Node.js).

### Ventajas  

1. **Alta popularidad y demanda:** Facilita encontrar recursos, bibliotecas y comunidades de apoyo.

2. **Interactividad en la web:** Permite crear interfaces dinámicas y reactivas.

3. **Ejecución en el navegador:** No requiere software adicional para ejecutarse.

4. **Compatibilidad universal:** Soportado por todos los navegadores modernos.

5. **Asincronía:** Las operaciones asincrónicas mejoran la rapidez y fluidez de las aplicaciones.

6. **Amplia base de herramientas y frameworks:** Para acelerar el desarrollo de la web.

7. **Facilidad de aprendizaje:** Curva de aprendizaje accesible para principiantes.

### Desventajas

1. **Inconsistencia entre navegadores:** Aunque ha mejorado, algunas características pueden comportarse diferente según el navegador.

2. **Depuración complicada:** La depuración en aplicaciones grandes puede ser compleja.

3. **Lenguaje monohilo:** Aunque maneja operaciones asincrónicas, sigue siendo un lenguaje de un solo hilo, lo que puede generar cuellos de botella en situaciones concurridas.



## **TypeScript**: 
Es un lenguaje de programación que se basa en JavaScript usando un sistema de tipado estático.


### Características

1. **Superset de JavaScript:** TypeScript es un superset de JavaScript, lo que significa que todo código JavaScript es también código TypeScript.

2. **Tipado estático:** TypeScript permite definir tipos estáticos, lo que ayuda a detectar errores en tiempo de compilación.

3. **Compilado a JavaScript:** El código TypeScript se transpila a JavaScript, lo que garantiza su ejecución en cualquier navegador o entorno que soporte JavaScript.

4. **Soporte para ES6/ESNext:** TypeScript soporta las últimas características de JavaScript, incluso antes de que estén disponibles en todos los navegadores.

5. **Compatibilidad con herramientas modernas:** Funciona bien con editores de texto y entornos de desarrollo como Visual Studio Code, proporcionando autocompletado, refactorización y depuración mejorada.

6. **Modularidad y escalabilidad:** TypeScript soporta módulos, interfaces, y clases, lo que permite organizar y escalar aplicaciones de forma más eficiente.

7. **Código más mantenible:** Gracias a la detección temprana de errores y la claridad en el código, TypeScript favorece la creación de aplicaciones más robustas.

### Ventajas

1. **Detección de errores en tiempo de compilación:** Reduce los errores en el código al obligar a los desarrolladores a definir tipos claros y consistentes.

2. **Mayor mantenibilidad:** Facilita la lectura y mantenimiento de grandes bases de código.

3. **Compatibilidad con JavaScript:** Se puede integrar gradualmente en proyectos existentes de JavaScript, lo que facilita la transición.

4. **Ecosistema robusto:** Soporte para bibliotecas y frameworks populares como React, Angular, Node.js.

5. **Mejor rendimiento a largo plazo:** Reduce el tiempo de depuración y mejora la estabilidad del proyecto a largo plazo.

### Desventajas

1. **Curva de aprendizaje adicional:** Aprender TypeScript implica familiarizarse con el tipado estático y otras características nuevas.

2. **Compilación necesaria:** El código TypeScript debe ser compilado a JavaScript antes de ser ejecutado, lo que añade un paso adicional al flujo de trabajo.

3. **Configuración inicial:** Configurar TypeScript puede requerir más tiempo y esfuerzo.

4. **Posibles conflictos con bibliotecas:** Aunque muchas bibliotecas populares tienen definiciones de tipos para TypeScript, algunas más antiguas o menos mantenidas pueden no tenerlas, lo que puede generar problemas de integración.



## **HTML/CSS**: 
HTML es el lenguaje de marcado estándar para documentos diseñados para ser mostrados en un navegador web.

CSS es un lenguaje de hojas de estilo utilizado para describir la presentación de documentos escritos en HTML.

### Características de HTML

1. **Etiquetas predefinidas:** Utiliza una serie de etiquetas (`<div>`, `<p>`, `<h1>`, `<a>`, etc.) para definir los diferentes elementos de una página web.

2. **Estructura jerárquica:** Organiza el contenido de forma estructurada en un árbol DOM (Document Object Model), facilitando la accesibilidad y manipulación.

3. **Soporte multimedia:** Permite la inserción de imágenes, videos, audio y otros tipos de medios dentro de las páginas web.

4. **Ligero y fácil de usar:** No requiere compilación, y cualquier navegador web puede interpretarlo.

5. **Formularios y elementos interactivos:** Ofrece formularios, botones, checkboxes, etc, para la interacción con los usuarios.

### Características de CSS

1. **Estilo visual:** CSS (Cascading Style Sheets) define el aspecto visual de una página web, controlando el diseño, colores, tipografía, márgenes, etc.

2. **Separación de contenido y diseño:** Separa la estructura HTML del estilo visual, mejorando la organización y mantenibilidad.

3. **Diseño responsivo:** Con media queries, CSS permite diseñar sitios web adaptables a diferentes tamaños de pantalla (móvil, tablet, escritorio).

4. **Animaciones y transiciones:** Permite crear efectos de animación y transiciones.

6. **Herencia y cascada:** Los estilos en CSS se aplican de manera jerárquica, permitiendo la reutilización de estilos entre elementos.

### Ventajas de HTML

1. **Fácil de aprender:** Tiene una curva de aprendizaje accesible, con una sintaxis sencilla y lógica.

2. **Soporte para accesibilidad:** Bien estructurado, HTML puede mejorar la accesibilidad para usuarios con discapacidades.

3. **Compatibilidad universal:** Funciona en todos los navegadores y dispositivos, independientemente de su versión.

### Ventajas de CSS

1. **Control total sobre el diseño:** Permite crear sitios web visualmente atractivos y personalizar el diseño según las necesidades del proyecto.

2. **Separación de estilo y contenido:** Mejora la mantenibilidad y reusabilidad del código, permitiendo cambios globales de estilo sin tocar la estructura HTML.

3. **Responsive design:** Facilita la creación de diseños adaptables para diferentes dispositivos y tamaños de pantalla.

### Desventajas de HTML

1. **Limitaciones en la interactividad:** HTML por sí solo no puede manejar interactividad avanzada; requiere JavaScript para comportamientos dinámicos.

2. **No es un lenguaje de programación:** No tiene lógica ni funcionalidad de procesamiento, limitando lo que se puede hacer sin otros lenguajes como JavaScript.

3. **Estilo limitado sin CSS:** HTML no se encarga del aspecto visual del sitio web, lo que significa que sin CSS, las páginas pueden verse básicas o sin diseño.

### Desventajas de CSS

1. **Complejidad con proyectos grandes:** A medida que los proyectos crecen, manejar grandes archivos CSS puede volverse complicado sin una buena estructura.

2. **Inconsistencias entre navegadores:** Aunque el soporte ha mejorado, algunas propiedades de CSS aún pueden comportarse de manera diferente en distintos navegadores.


### Referencias: 
https://blog.hubspot.es/website/ventajas-y-desventajas-de-javascript

https://www.mytaskpanel.com/lenguaje-de-programacion-typescript/

https://www.dongee.com/tutoriales/ventajas-y-desventajas-de-html-y-css/

https://chatgpt.com


## 7. Tecnologías a Utilizar
Las tecnologías (lenguajes de programación, frameworks, herramientas de desarrollo) que se utilizarán para el desarrollo de la aplicación son:

- **HTML/CSS**: HTML se usará para estructurar el contenido y CSS para el diseño y el estilo de la interfaz de usuario.

- **JavaScript**: Se utilizará para la interacción del lado del cliente y la manipulación del DOM. Es esencial para la creación de un reproductor de video interactivo.

- **TypeScript**: Añadirá tipos estáticos a JavaScript, lo que ayuda a mejorar la mantenibilidad y a evitar errores comunes


## Evaluación de los mecanismos de integración de lenguajes de marcas con lenguajes de programación de clientes web (c.e. 1e)


### Integración de HTML/CSS con JavaScript

**JavaScript** es el lenguaje de programación que se integra con HTML para crear interactividad y dinamismo en el cliente. También permite modificar el contenido y la estructura de una página web dinámicamente, mediante la manipulación del DOM

**Ejemplo**:  
Un ejemplo común es la validacion de formularios con JavaScript antes de enviarlo al servidor.

## Evaluación de herramientas de programación para clientes web (c.e. 1f)

- Utilizare frameworks como **React** para la creacion de interfaces de usuario, algunas de sus ventajas son: Agilizar la creacion de una interfaz, ahorrar recursos y trafico, y una logica clara.


- Como IDE usaré **Visual Studio Code** para el uso de HTML/CSS, JavaScript y TypeScript. Sus ventajas respecto a otros editores son: Es codigo abierto, altamente personalizable, compatible con varios lenguajes de programacion y compatible con varias plataformas.

### Referencias:

https://vgst.net/blog/development/javascript-en-html

https://webdesigncusco.com/ventajas-y-desventajas-de-visual-studio-code/

https://ebac.mx/blog/que-es-react

https://vgst.net/blog/development/javascript-en-html

## 8. Compatibilidad en Navegadores (c.e. 1b)

- **Compatibilidad de JavaScript**: Los navegadores modernos como Chrome, Firefox, Safari, Edge... soportan la mayoría de las características avanzadas de JavaScript. Las versiones antiguas de algunos navegadores pueden tener problemas de compatibilidad con JavaScript

- **Soluciones a problemas de compatibilidad**: El uso de Polifills y Transpiladores son unas de las maneras mas efectivas de manejar la compatibilidad. Los polifills permiten que características modernas de JavaScript funcionen en navegadores más antiguos y los transpiladores como Babel convierten el código ES6+ en una versión que es comprensible por navegadores más antiguos. 

### Referencia:

https://ladivinaproporcion.es/javascript-y-cross-browser-buenas-practicas-para-evitar-problemas-de-compatibilidad/
