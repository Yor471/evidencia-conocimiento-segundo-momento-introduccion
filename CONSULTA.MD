# Cuestionario: Frameworks de CSS y Metodología BEM

*A continuación, responde cada una de las siguientes preguntas. Recuerda hacer un commit por cada pregunta principal que completes.*

### Pregunta 1: Fundamentos de los Frameworks de CSS

* **1.1.** ¿Qué es un **Framework de CSS**? Explícalo con una analogía del mundo real que no sea de programación (por ejemplo, un kit de bloques de construcción, una plantilla para dibujar, etc.) para facilitar su comprensión.
* **1.2.** ¿Qué problemas principales vienen a solucionar los frameworks de CSS en el desarrollo web? Menciona y explica al menos dos ventajas clave de utilizarlos.

**[ESPACIO PARA TU RESPUESTA 1]**
1. ¿Qué es?
Un Framework de CSS es como un kit de Lego ya preparado para construir páginas web. En lugar de hacer cada pieza de diseño desde cero (escribir mucho CSS), ya tienes botones, menús, colores y formas listos para usar, solo tienes que unirlos.

1.1 Para qué sirve?
Resuelve dos problemas principales:

Hacerlo Rápido: Acelera la creación de la página. Usas clases predefinidas (como botón-azul) en lugar de escribir 20 líneas de código cada vez

Que se Vea Bien y Uniforme: Asegura que todos los botones, títulos y secciones se vean exactamente iguales y profesionales en todas las páginas.

### Pregunta 2: Bootstrap CSS - El Ecosistema Basado en Componentes

* **2.1.** Describe la filosofía principal de **Bootstrap**, centrada en **componentes pre-diseñados** (component-based).
* **2.2.** Investiga en la documentación de Bootstrap y crea una lista con **10 clases** fundamentales. Incluye el nombre de la clase y una breve definición de lo que hace. (Ej: `.container` - Centra y ajusta el ancho del contenido). Procura que la lista incluya clases de layout (grid), componentes y utilidades.
* **2.3.** Basado en tu investigación, menciona dos **ventajas** y dos **desventajas** claras de usar Bootstrap en un proyecto.

**[ESPACIO PARA TU RESPUESTA 2]**
2.1 Filosofía (¿Qué busca?)
La idea de Bootstrap es que tú puedas hacer una web súper rápido usando piezas que ya están hechas (los componentes). Piensa en esto:

Es Mobile-First: Primero piensa en cómo se verá tu web en el celular. Si funciona bien ahí, solo tiene que crecer para verse bien en una tablet o computadora. 📱

Kit de Componentes: Te da botones, menús, tarjetas... todo listo. Solo pones las clases (.btn-success) y ya se ven geniales.

2.2 Clases Fundamentales (10 Ejemplos Clave)Clase¿Qué Hace?.containerPone tu contenido en el centro y le da un ancho fijo para que se vea ordenado..rowCrea una fila para organizar cosas horizontalmente..col-6Divide una fila en 12 partes, y esta clase ocupa 6 (la mitad)..btn-primaryConvierte algo en un botón azul bonito y con estilo..navbarCrea la barra de navegación (el menú superior) lista para usarse..cardCrea un recuadro bonito para agrupar información (como una ficha o tarjeta)..d-flexPrepara el elemento para que puedas alinear cosas fácilmente (como centrar texto)..mt-4Añade un margen (espacio) arriba para que el elemento no esté pegado al de arriba..text-centerCentra el texto..form-controlEstiliza un campo de formulario para que se vea moderno y uniforme.

2.3 Pros y Contras
Ventajas (Lo bueno de usar Bootstrap)

Súper Rápido: Puedes armar una web responsiva (que se adapta a móviles) en horas, no en días, porque ya tienes casi todo hecho. (Ahorro de Tiempo ⏱️)

Todo se ve igual: Los estilos son consistentes, así que el diseño se ve profesional y ordenado en todas las páginas.

Desventajas (Lo no tan bueno de usar Bootstrap)

Código Extra (Bloat): A veces, el kit trae cosas que no usas y eso hace la web un poco más pesada de cargar.

Se ven parecidas: Muchas webs usan los estilos por defecto de Bootstrap, así que tu web puede verse "genérica" si no la personalizas mucho.

---

### Pregunta 3: Tailwind CSS - El Enfoque "Utility-First"

* **3.1.** Describe la filosofía **"Utility-First"** (clases de utilidad) de **Tailwind CSS** y en qué se diferencia fundamentalmente del enfoque de Bootstrap.
* **3.2.** Investiga en la documentación de Tailwind y crea una lista con **10 clases** de utilidad. Incluye el nombre de la clase y el estilo CSS que aplica. (Ej: `.text-center` - Aplica `text-align: center;`). Procura que la lista incluya clases para manejo de colores, espaciado, tipografía y flexbox.
* **3.3.** Basado en tu investigación, menciona dos **ventajas** y dos **desventajas** claras de usar Tailwind CSS en un proyecto.

**[ESPACIO PARA TU RESPUESTA 3]**

---

### Pregunta 4: BEM - Organizando CSS Puro

* **4.1.** ¿Qué es la metodología **BEM** (Block, Element, Modifier)? Explica con tus propias palabras qué representa cada una de sus partes (Bloque, Elemento y Modificador).
* **4.2.** ¿Qué problema clave viene a solucionar BEM en el desarrollo con CSS puro? ¿Cómo ayuda a prevenir colisiones de estilos y a hacer el código más mantenible?
* **4.3.** Muestra un ejemplo de código HTML y CSS para un componente de "tarjeta de producto" (`product-card`) utilizando la sintaxis BEM. El bloque debe tener elementos como un título, una imagen y un botón, y el botón debe tener un modificador para un estado primario (ej. `product-card__button--primary`).

**[ESPACIO PARA TU RESPUESTA 4]**

---

### Pregunta 5: Frameworks y CSS Puro - Conflictos y Convivencia

* **5.1.** ¿Es posible usar hojas de estilos personalizadas (CSS puro) junto a un framework? Explica las implicaciones y el orden en que deberían cargarse los archivos CSS en el HTML.
* **5.2.** Investiga sobre la **especificidad de CSS**. ¿Qué es y cómo puede generar conflictos al intentar sobreescribir un estilo de un framework? ¿Qué regla de estilo es más específica: la de una clase del framework (ej. `.btn-primary`) o una regla que tú escribas en tu CSS (ej. `#mi-boton-especial`)?
* **5.3.** ¿Es técnicamente posible y/o recomendable usar Bootstrap, Tailwind CSS y una hoja de estilos propia en un mismo proyecto? Argumenta sobre los posibles conflictos (ej. reseteo de estilos, colisión de nombres de clases) y problemas de rendimiento que esto podría causar.

**[ESPACIO PARA TU RESPUESTA 5]**

---

### Pregunta 6: Comparación y Veredicto Final

* **6.1.** Crea una comparativa simple que resuma las diferencias clave entre Bootstrap, Tailwind CSS y una metodología como BEM para CSS puro. Considera al menos los siguientes criterios: **Curva de Aprendizaje**, **Nivel de Personalización**, **"Limpieza" del HTML** y **Velocidad de prototipado**.
* **6.2.** ¿En qué tipo de proyecto recomendarías usar **Bootstrap**? ¿En cuál **Tailwind CSS**? ¿Y en cuál optarías por **CSS Puro + BEM**? Justifica tu respuesta basándote en las fortalezas y debilidades de cada enfoque.

**[ESPACIO PARA TU RESPUESTA 6]**