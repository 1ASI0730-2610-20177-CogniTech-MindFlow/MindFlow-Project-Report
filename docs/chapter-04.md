# Capítulo IV: Product Design

---
## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines

#### Typography

La tipografía utilizada en MindFlow fue seleccionada considerando criterios de legibilidad, claridad visual y consistencia en interfaces digitales. Se priorizó el uso de una tipografía sans-serif moderna, optimizada para entornos web y aplicaciones móviles.

La fuente principal elegida es Inter, debido a su alta legibilidad en pantallas, su diseño limpio y su uso extendido en aplicaciones tecnológicas modernas.

Inter permite mantener una jerarquía tipográfica clara para títulos, subtítulos y contenido, facilitando la lectura del usuario dentro de la plataforma.

Tipografía seleccionada

- Primary Font: Inter  
- Tipo: Sans-serif  
- Uso: Títulos, subtítulos, botones e interfaz general  

![Typography](../assets/interFont.png)

---

#### Primary Colors

Los colores primarios de MindFlow representan los valores centrales de la plataforma: calma emocional, confianza tecnológica y bienestar.

Se seleccionaron tonos fríos y suaves para generar una experiencia visual relajante que reduzca la fatiga visual y transmita estabilidad.

Colores primarios

- Primary Blue — #4F8DF5  
- Soft Green — #6ED3A3  

Estos colores se utilizan principalmente en:

- botones principales  
- elementos interactivos  
- indicadores de estado positivo  
- elementos clave de branding  

![Primary Colors](../assets/primaryColors.png)

---

#### Secondary Colors

Los colores secundarios complementan la identidad visual del sistema y permiten crear jerarquía visual dentro de la interfaz.

Se utilizan para elementos de apoyo, secciones informativas y componentes secundarios de la interfaz.

Colores secundarios

- Accent Purple — #8A7CF6  
- Neutral Gray — #F5F7FA  
- Dark Gray — #2F2F2F  

Estos colores se utilizan en:

- fondos de secciones  
- tarjetas informativas  
- textos secundarios  
- elementos decorativos de interfaz  

![Secondary Colors](../assets/secundaryColors.png)

---

#### Wireframe Colors

Para el diseño de wireframes se utilizan colores neutros que permiten concentrarse en la estructura de la interfaz y no en el diseño visual final.

Estos colores facilitan la representación de layouts, jerarquías de información y distribución de componentes.

Colores utilizados en wireframes

- Light Gray — #E5E5E5  
- Medium Gray — #BDBDBD  
- Dark Gray — #828282  
- White — #FFFFFF  

Estos colores permiten diferenciar:

- contenedores  
- secciones  
- elementos interactivos  
- placeholders de contenido  

![Wireframe Colors](../assets/wireframesColors.png)

### 4.1.2. Web Style Guidelines

Las Web Style Guidelines consideran principios de diseño responsive, accesibilidad y usabilidad, con el objetivo de que la plataforma pueda adaptarse correctamente a distintos tamaños de pantalla y dispositivos, manteniendo siempre claridad visual y facilidad de interacción.

#### Layout and Grid System

El diseño de las interfaces web utiliza un sistema de grid flexible que permite organizar los elementos de forma consistente y adaptable a diferentes resoluciones de pantalla.

El sistema de grid se basa en:

- Grid de 12 columnas  
- Margen lateral adaptable  
- Espaciado consistente basado en múltiplos de 8px  

Este enfoque facilita la construcción de interfaces responsivas y permite distribuir componentes como tarjetas, formularios y paneles de manera equilibrada dentro del layout.

#### Buttons

Los botones representan uno de los elementos interactivos principales dentro de la plataforma. Se definen estilos consistentes para mantener una interacción clara y reconocible.

Tipos de botones definidos:

Primary Button  
Utilizado para acciones principales como guardar registros emocionales o iniciar procesos importantes dentro de la aplicación.

Secondary Button  
Utilizado para acciones complementarias o alternativas dentro de una misma interfaz.

Text Button  
Utilizado en acciones secundarias o navegación ligera dentro de la aplicación.

#### Forms and Input Fields

Los formularios permiten al usuario interactuar con el sistema ingresando información, como registros emocionales o configuración de hábitos.

Los campos de entrada siguen un diseño simple y claro, con etiquetas visibles y retroalimentación visual en caso de error o validación.

Elementos incluidos en formularios:

- Text input  
- Dropdown selectors  
- Text areas  
- Validation messages  

#### Cards and Content Containers

Las tarjetas (cards) se utilizan para organizar información dentro de la interfaz de manera clara y estructurada. Este componente es especialmente útil para mostrar registros emocionales, estadísticas o recomendaciones del sistema.

Las cards incluyen:

- fondo neutro  
- bordes suaves  
- sombra ligera para jerarquía visual  

#### Responsive Behavior

La interfaz web de MindFlow fue diseñada siguiendo principios de diseño responsive, permitiendo que el contenido se adapte correctamente a diferentes dispositivos.

Se consideran tres tamaños principales de visualización:

Desktop  
Pantallas mayores a 1024px.

Tablet  
Pantallas entre 768px y 1024px.

Mobile  
Pantallas menores a 768px.

Cada layout reorganiza los componentes para mantener la legibilidad y facilidad de navegación.

## 4.2. Information Architecture

La arquitectura de información tiene como propósito facilitar la comprensión de la estructura del producto digital, permitiendo que los visitantes y usuarios puedan adaptarse rápidamente a su funcionamiento y encontrar la información o funcionalidades que necesitan sin esfuerzo innecesario.

Para lograrlo, se han definido distintos sistemas que estructuran la experiencia digital:

- Organization Systems  
- Labeling Systems  
- Navigation Systems  
- Searching Systems  

Estos sistemas permiten organizar la información, definir la forma en que se nombran los contenidos, estructurar la navegación dentro de la plataforma y facilitar la localización de información específica cuando el usuario la requiere.

---

## 4.2.1. Organization Systems

Los Organization Systems definen la manera en que la información se agrupa y estructura dentro del Landing Page y las aplicaciones del sistema.

En el proyecto se consideran distintos tipos de organización visual del contenido, dependiendo del contexto de uso y del tipo de información que se presenta:

- organización jerárquica 
- organización secuencial
- organización matricial  

### Organización jerárquica

La organización jerárquica se utiliza principalmente en el Landing Page y en los dashboards principales de la aplicación, donde es necesario destacar la información más relevante y guiar la atención del usuario.

Este tipo de organización establece distintos niveles de importancia dentro de la interfaz mediante el uso de tamaño, contraste, posición y agrupación de elementos, permitiendo que los usuarios identifiquen rápidamente los contenidos o acciones más importantes.

### Organización secuencial

La organización secuencial se aplica en aquellas funcionalidades donde el usuario debe seguir una serie de pasos para completar una tarea dentro del sistema.

Este enfoque permite estructurar procesos de manera clara y ordenada, facilitando la comprensión del flujo de interacción y reduciendo la probabilidad de errores durante la ejecución de las tareas.

### Organización matricial

La organización matricial se utiliza en aquellas secciones donde la información debe visualizarse considerando diferentes variables o dimensiones al mismo tiempo.

Este tipo de estructura permite relacionar distintos tipos de datos dentro de una misma vista, facilitando la comparación de información y el análisis de resultados.

### Esquemas de categorización del contenido

Además de la organización visual, el sistema también utiliza diferentes esquemas de categorización para estructurar el contenido de acuerdo con su naturaleza:

- organización alfabética  
- organización cronológica  
- organización por tópicos  
- organización según audiencia  

La organización alfabética permite localizar elementos de manera rápida dentro de listados extensos. La organización cronológica se utiliza cuando la información está asociada a registros históricos o eventos que ocurren a lo largo del tiempo. La organización por tópicos agrupa los contenidos según áreas funcionales del sistema. Finalmente, la organización según audiencia considera los distintos tipos de usuarios que interactúan con la plataforma, permitiendo adaptar la estructura de la información de acuerdo con sus necesidades y contexto de uso.

La combinación de estos sistemas permite estructurar el contenido del producto digital de manera clara y coherente, facilitando la navegación y mejorando la experiencia general de los usuarios.

## 4.2.2. Labeling Systems

Las etiquetas utilizadas en el sistema se caracterizan por ser simples, directas y consistentes a lo largo de toda la experiencia digital. Se busca emplear el menor número posible de palabras para representar cada conjunto de información, permitiendo que los usuarios identifiquen rápidamente el propósito de cada sección o funcionalidad.

El sistema de etiquetado también busca mantener coherencia entre las distintas partes del producto digital, de modo que los mismos conceptos se representen siempre con la misma terminología. Esto contribuye a generar familiaridad en el uso de la plataforma y facilita la navegación entre las diferentes secciones.

Entre las principales etiquetas utilizadas para representar los conjuntos de información dentro del sistema se encuentran:

- Dashboard  
- Assets  
- Maintenance  
- Failures  
- Reports  
- Notifications  
- Settings  

Estas etiquetas permiten organizar los módulos principales del sistema y establecer relaciones claras entre los distintos tipos de información. Asimismo, contribuyen a que los usuarios comprendan rápidamente la función de cada sección y puedan acceder a las herramientas necesarias para realizar sus tareas dentro de la plataforma.

## 4.2.3. SEO Tags and Meta Tags

La plataforma TexCheck incorpora metaetiquetas que permiten mejorar la identificación del contenido por parte de los motores de búsqueda y estructurar correctamente la información para navegadores y sistemas de indexación.

Las meta tags definidas para la experiencia digital se utilizan tanto en el Landing Page como en la Web Application, permitiendo describir el propósito del sistema y facilitar su posicionamiento en buscadores.

Las principales meta tags utilizadas son las siguientes:

- **Title:** Define el título principal de la página que aparece en la pestaña del navegador y en los resultados de búsqueda.

![Title Tag](../assets/titleTag.png)

- **Codificación de caracteres:** Permite que los caracteres especiales se muestren correctamente en todos los navegadores.

![Charset Tag](../assets/charsetTag.png)

- **Description:** Proporciona un resumen breve del contenido del sitio que puede aparecer en los resultados de búsqueda.

![Description Tag](../assets/descriptionTag.png)

- **Keywords:** Define palabras clave relacionadas con el contenido del sistema para facilitar su indexación en motores de búsqueda.

![Keywords Tag](../assets/keywordsTag.png)

- **Author:** Identifica al autor o equipo responsable del contenido del sitio.

![Author Tag](../assets/authorTag.png)

Estas metaetiquetas permiten describir adecuadamente el contenido de las páginas principales del sistema, facilitando su indexación en motores de búsqueda y mejorando la visibilidad de la plataforma.

## 4.2.4. Searching Systems

El sistema de búsqueda define los mecanismos que permiten a los usuarios localizar información dentro de la plataforma de manera rápida y eficiente. Estas funcionalidades buscan facilitar la exploración del contenido y evitar que los usuarios se sientan desorientados cuando interactúan con grandes volúmenes de información.

Las aplicaciones incorporan herramientas de búsqueda que permiten encontrar registros específicos dentro de los distintos módulos del sistema. Estas búsquedas se complementan con filtros que ayudan a refinar los resultados según diferentes criterios, permitiendo a los usuarios acceder de forma más precisa a la información que necesitan.

Las principales opciones de búsqueda disponibles en el sistema incluyen:

- búsqueda por palabra clave  
- filtros por categoría o tipo de información  
- filtros por estado  
- filtros por fecha  

Una vez realizada la búsqueda, los resultados se presentan en vistas organizadas que facilitan la lectura y comparación de la información. Los datos se muestran en tablas o listas estructuradas, permitiendo visualizar los registros encontrados junto con los atributos más relevantes asociados a cada elemento.

Este sistema de búsqueda contribuye a mejorar la eficiencia de la interacción con la plataforma, ya que permite acceder rápidamente a la información requerida y facilita la gestión de los datos dentro de las diferentes funcionalidades del sistema.

## 4.2.5. Navigation Systems

La navegación en MindFlow permite a los usuarios recorrer el Landing Page y las aplicaciones de manera clara mientras interactúan con las diferentes funcionalidades de la plataforma.

En la Web Application se utiliza un menú principal que agrupa los módulos más importantes, permitiendo acceder directamente a las principales secciones de trabajo. Este menú mantiene una estructura consistente en todas las pantallas, lo que facilita la identificación rápida de las funcionalidades disponibles.

Dentro de cada módulo se incorporan elementos de navegación contextual que permiten desplazarse entre distintas vistas o acciones relacionadas. Estos elementos se presentan mediante botones, enlaces y accesos directos que apoyan la interacción con las funcionalidades de la aplicación.

En el Landing Page, la navegación se organiza mediante un menú superior que dirige a los visitantes hacia las secciones principales del sitio, permitiendo recorrer la información del producto de forma ordenada.

Esta estructura facilita la orientación dentro de MindFlow y permite acceder de manera directa a las funcionalidades necesarias durante la interacción con la plataforma.

## 4.3. Landing Page UI Design

---

### 4.3.1. Landing Page Wireframe

### 4.3.2. Landing Page Mock-up

## 4.4. Web Applications UX/UI Design

---

### 4.4.1. Web Applications Wireframes

### 4.4.2. Web Applications Wireflow Diagrams

### 4.4.3. Web Applications Mock-ups

### 4.4.4. Web Applications User Flow Diagrams

## 4.5. Web Applications Prototyping

---

## 4.6. Domain-Driven Software Architecture

---

### 4.6.1. Design-Level EventStorming

### 4.6.2. Software Architecture Context Diagram

### 4.6.3. Software Architecture Container Diagrams

### 4.6.4. Software Architecture Components Diagrams

## 4.7. Software Object-Oriented Design

---

### 4.7.1. Class Diagrams

## 4.8. Database Design

---

### 4.8.1. Database Diagrams
