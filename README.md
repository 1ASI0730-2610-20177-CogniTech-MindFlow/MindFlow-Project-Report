<div align="center">

<img src="assets/upc_logo.png" alt="UPC Logo" width="300"/>

# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS

### Carrera: Ingeniería de Software

### Periodo: 2026-10

### Nombre del curso: Aplicaciones Web (1ASI0730)

### NRC: 20177

### Nombre del profesor: Flores Ingaruca, Jose Miguel

## Informe de Trabajo Final

## Nombre del startup: CogniTech

## Nombre del producto: MindFlow

### Relación de integrantes:

<div style="text-align: center;">

|        Apellidos y Nombres         | Código de Alumno |
|:----------------------------------:|:----------------:|
|   Cabrera Sotelo, Camila Celeste   |    U202412462    |
|  Caisahuana Osores, Becker Junior  |    U202419462    |
| Díaz De la cruz, Sebastián Gabriel |    U202410421    |
|    Jáuregui Cerna, Jean Franco     |    U202410024    |
|    Rocca Mariaca, Angel Mathias    |    U20231E515    |

</div>

### Abril, 2026

---

</div>

# Registro de Versiones del Informe

---

| Versión | Fecha      | Autor                        | Descripción de modificación |
|---------|------------|------------------------------|-----------------------------|
| 1.0 | 10/04/2026 | Rocca Mariaca, Angel Mathias | Creación del reporte en formato Markdown. |

# Project Report Collaboration Insights

---

| Enlace del repositorio del informe del proyecto |
|-------------------------------------------------|
| https://github.com/1ASI0730-2610-20177-CogniTech-MindFlow/MindFlow-Project-Report.git                                                |

# Student Outcome

---

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 5**
Criterio: Trabaja efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo; crea un entorno colaborativo e inclusivo y establece metas, planifica tareas y cumple objetivos.

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 5.

| Criterio específico                                                                          | Acciones realizadas | Conclusiones |
|----------------------------------------------------------------------------------------------|---------------------|--------------|
| **5.c.1 Trabaja en equipo para proporcionar liderazgo en forma conjunta**  | **Cabrera Sotelo, Camila Celeste** <br> Lideró el diseño de interfaces y la experiencia visual mediante la creación de Style Guidelines, Information Architecture y Landing Page UI Design. <br><br> **Caisahuana Osores, Becker Junior** <br> Asumió el liderazgo en la definición del producto, ejecutando el Lean UX Process, estructurando los requerimientos funcionales (User Stories, Product Backlog) y el diseño de la base de datos (Database Diagrams). <br><br> **Díaz De la Cruz, Sebastián Gabriel** <br> Lideró la investigación gestionando el diseño, registro y análisis de entrevistas (Interviews), además de definir la arquitectura (Context, Container, Component Diagrams). <br><br> **Jáuregui Cerna, Jean Franco** <br> Dirigió el modelado de dominio colaborativo estructurando el Big Picture EventStorming y el Ubiquitous Language. <br><br> **Rocca Mariaca, Angel Mathias** <br> Proporcionó liderazgo técnico en la configuración del entorno (Software Configuration Management), prototipado web y la implementación integral del Sprint 1. | El equipo evidenció un nivel sobresaliente al liderar equipos multidisciplinarios y demostrar sus habilidades en todas las actividades, superando así los logros planteados. Cada miembro asumió el liderazgo de áreas críticas. Adicionalmente, el equipo demostró capacidad para trabajar de manera coordinada a través de evidencias claras como el diseño y registro de entrevistas (gestionadas por S. Díaz), garantizando la continuidad en la gestión de comunicaciones. |
| **5.c.2 Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos** | **Cabrera Sotelo, Camila Celeste** <br> Integró proactivamente las necesidades del equipo estandarizando la arquitectura de información para facilitar la navegación y etiquetado a sus compañeros. <br><br> **Caisahuana Osores, Becker Junior** <br> Planificó las metas del producto estableciendo el Impact Mapping y el Product Backlog, escuchando las necesidades del equipo para priorizar el alcance. <br><br> **Díaz De la Cruz, Sebastián Gabriel** <br> Fomentó la inclusión mediante herramientas de empatía (Empathy Mapping) y basó la arquitectura en las opiniones extraídas de la investigación. <br><br> **Jáuregui Cerna, Jean Franco** <br> Consolidó el entorno colaborativo definiendo un Lenguaje Ubicuo y organizando el EventStorming para unificar el entendimiento técnico del grupo. <br><br> **Rocca Mariaca, Angel Mathias** <br> Estableció metas, planificó tareas y definió roles mediante el Sprint Planning 1 y la asignación en el Sprint Backlog 1, supervisando la colaboración durante el sprint. | El grupo operó de manera proactiva, estando siempre dispuesto a escuchar las opiniones de sus compañeros. A través de sesiones conjuntas como el EventStorming y el Sprint Planning, el equipo demostró capacidad para analizar las críticas de los miembros del equipo y proponer soluciones. De esta forma, se garantizó la cooperación, participación e integración efectiva entre los miembros del grupo para el cumplimiento de las metas del proyecto. |
# Contenido

---

## Tabla de Contenidos

---

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Student Outcome](#student-outcome)
- [1.1. Startup Profile](docs/chapter-01.md#11-startup-profile)
    - [1.1. Startup Profile](docs/chapter-01.md#11-startup-profile)
        - [1.1.1. Descripción de la Startup](docs/chapter-01.md#111-descripción-de-la-startup)
        - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2. Solution Profile](#12-solution-profile)
        - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
        - [1.2.2. Lean UX Process](#122-lean-ux-process)
            - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
            - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
            - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
            - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
    - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](docs/chapter-02.md#capítulo-ii-requirements-elicitation--analysis)
    - [2.1. Competidores](docs/chapter-02.md#21-competidores)
        - [2.1.1. Análisis competitivo](docs/chapter-02.md#211-análisis-competitivo)
        - [2.1.2. Estrategias y tácticas frente a competidores](docs/chapter-02.md#212-estrategias-y-tácticas-frente-a-competidores)
    - [2.2. Entrevistas](docs/chapter-02.md#22-entrevistas)
        - [2.2.1. Diseño de entrevistas](docs/chapter-02.md#221-diseño-de-entrevistas)
        - [2.2.2. Registro de entrevistas](docs/chapter-02.md#222-registro-de-entrevistas)
        - [2.2.3. Análisis de entrevistas](docs/chapter-02.md#223-análisis-de-entrevistas)
    - [2.3. Needfinding](docs/chapter-02.md#23-needfinding)
        - [2.3.1. User Personas](docs/chapter-02.md#231-user-personas)
        - [2.3.2. User Task Matrix](docs/chapter-02.md#232-user-task-matrix)
        - [2.3.3. User Journey Mapping](docs/chapter-02.md#233-user-journey-mapping)
        - [2.3.4. Empathy Mapping](docs/chapter-02.md#234-empathy-mapping)
    - [2.4. Big Picture EventStorming](docs/chapter-02.md#24-big-picture-eventstorming)
    - [2.5. Ubiquitous Language](docs/chapter-02.md#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](docs/chapter-03.md#capítulo-iii-requirements-specification)
    - [3.1. User Stories](docs/chapter-03.md#31-user-stories)
    - [3.2. Impact Mapping](docs/chapter-03.md#32-impact-mapping)
    - [3.3. Product Backlog](docs/chapter-03.md#33-product-backlog)
- [Capítulo IV: Product Design](docs/chapter-04.md#capítulo-iv-product-design)
    - [4.1. Style Guidelines](docs/chapter-04.md#41-style-guidelines)
        - [4.1.1. General Style Guidelines](docs/chapter-04.md#411-general-style-guidelines)
        - [4.1.2. Web Style Guidelines](docs/chapter-04.md#412-web-style-guidelines)
    - [4.2. Information Architecture](docs/chapter-04.md#42-information-architecture)
        - [4.2.1. Organization Systems](docs/chapter-04.md#421-organization-systems)
        - [4.2.2. Labeling Systems](docs/chapter-04.md#422-labeling-systems)
        - [4.2.3. SEO Tags and Meta Tags](docs/chapter-04.md#423-seo-tags-and-meta-tags)
        - [4.2.4. Searching Systems](docs/chapter-04.md#424-searching-systems)
        - [4.2.5. Navigation Systems](docs/chapter-04.md#425-navigation-systems)
    - [4.3. Landing Page UI Design](docs/chapter-04.md#43-landing-page-ui-design)
        - [4.3.1. Landing Page Wireframe](docs/chapter-04.md#431-landing-page-wireframe)
        - [4.3.2. Landing Page Mock-up](docs/chapter-04.md#432-landing-page-mock-up)
    - [4.4. Web Applications UX/UI Design](docs/chapter-04.md#44-web-applications-uxui-design)
        - [4.4.1. Web Applications Wireframes](docs/chapter-04.md#441-web-applications-wireframes)
        - [4.4.2. Web Applications Wireflow Diagrams](docs/chapter-04.md#442-web-applications-wireflow-diagrams)
        - [4.4.3. Web Applications Mock-ups](docs/chapter-04.md#443-web-applications-mock-ups)
        - [4.4.4. Web Applications User Flow Diagrams](docs/chapter-04.md#444-web-applications-user-flow-diagrams)
    - [4.5. Web Applications Prototyping](docs/chapter-04.md#45-web-applications-prototyping)
    - [4.6. Domain-Driven Software Architecture](docs/chapter-04.md#46-domain-driven-software-architecture)
        - [4.6.1. Design-Level EventStorming](docs/chapter-04.md#461-design-level-eventstorming)
        - [4.6.2. Software Architecture Context Diagram](docs/chapter-04.md#462-software-architecture-context-diagram)
        - [4.6.3. Software Architecture Container Diagrams](docs/chapter-04.md#463-software-architecture-container-diagrams)
        - [4.6.4. Software Architecture Components Diagrams](docs/chapter-04.md#464-software-architecture-components-diagrams)
    - [4.7. Software Object-Oriented Design](docs/chapter-04.md#47-software-object-oriented-design)
        - [4.7.1. Class Diagrams](docs/chapter-04.md#471-class-diagrams)
    - [4.8. Database Design](docs/chapter-04.md#48-database-design)
        - [4.8.1. Database Diagrams](docs/chapter-04.md#481-database-diagrams)
- [Capítulo V: Product Implementation, Validation & Deployment](docs/chapter-05.md#capítulo-v-product-implementation-validation--deployment)
    - [5.1. Software Configuration Management](docs/chapter-05.md#51-software-configuration-management)
        - [5.1.1. Software Development Environment Configuration](docs/chapter-05.md#511-software-development-environment-configuration)
        - [5.1.2. Source Code Management](docs/chapter-05.md#512-source-code-management)
        - [5.1.3. Source Code Style Guide & Conventions](docs/chapter-05.md#513-source-code-style-guide--conventions)
        - [5.1.4. Software Deployment Configuration](docs/chapter-05.md#514-software-deployment-configuration)
    - [5.2. Landing Page, Services & Applications Implementation](docs/chapter-05.md#52-landing-page-services--applications-implementation)
        - [5.2.1. Sprint 1](docs/chapter-05.md#521-sprint-1)
            - [5.2.1.1. Sprint Planning 1](docs/chapter-05.md#5211-sprint-planning-1)
            - [5.2.1.2. Aspect Leaders and Collaborators](docs/chapter-05.md#5212-aspect-leaders-and-collaborators)
            - [5.2.1.3. Sprint Backlog 1](docs/chapter-05.md#5213-sprint-backlog-1)
            - [5.2.1.4. Development Evidence for Sprint Review](docs/chapter-05.md#5214-development-evidence-for-sprint-review)
            - [5.2.1.5. Execution Evidence for Sprint Review](docs/chapter-05.md#5215-execution-evidence-for-sprint-review)
            - [5.2.1.6. Services Documentation Evidence for Sprint Review](docs/chapter-05.md#5216-services-documentation-evidence-for-sprint-review)
            - [5.2.1.7. Software Deployment Evidence for Sprint Review](docs/chapter-05.md#5217-software-deployment-evidence-for-sprint-review)
            - [5.2.1.8. Team Collaboration Insights during Sprint](docs/chapter-05.md#5218-team-collaboration-insights-during-sprint)
    - [5.3. Validation Interviews](docs/chapter-05.md#53-validation-interviews)
        - [5.3.1. Diseño de Entrevistas](docs/chapter-05.md#531-diseño-de-entrevistas)
        - [5.3.2. Registro de Entrevistas](docs/chapter-05.md#532-registro-de-entrevistas)
        - [5.3.3. Evaluaciones según heurísticas](docs/chapter-05.md#533-evaluaciones-según-heurísticas)
    - [5.4. Video About-the-Product](docs/chapter-05.md#54-video-about-the-product)
- [Conclusiones](docs/chapter-05.md#conclusiones)
    - [Conclusiones y recomendaciones](docs/chapter-05.md#conclusiones-y-recomendaciones)
    - [Video About-the-Team](docs/chapter-05.md#video-about-the-team)
- [Bibliografía](docs/chapter-05.md#bibliografía)
- [Anexos](docs/chapter-05.md#anexos)
