
# Capítulo II: Requirements Elicitation & Analysis
El presente capítulo tiene como objetivo identificar y analizar los requerimientos del sistema MindFlow mediante un enfoque centrado en el usuario. Para ello, se emplean técnicas como el análisis competitivo, entrevistas y needfinding, las cuales permiten comprender las necesidades reales de los usuarios en relación con la gestión del estrés, la ansiedad y los hábitos de bienestar.

A través de este proceso, se busca obtener información clave que permita validar los supuestos del proyecto y definir funcionalidades alineadas con el contexto y expectativas del público objetivo. De este modo, se asegura que la solución propuesta sea relevante, diferenciada y orientada a generar valor real en la experiencia del usuario.

---

## 2.1. Competidores

En el contexto actual del mercado digital de bienestar, existen diversas aplicaciones que abordan la gestión emocional y el desarrollo de hábitos desde distintos enfoques. A continuación, se presentan los principales competidores de MindFlow, considerando su propuesta de valor y alcance funcional:

- Daylio: Aplicación enfocada en el registro diario del estado de ánimo mediante interfaces simples y estadísticas visuales. Su principal fortaleza radica en su facilidad de uso, aunque carece de retroalimentación inteligente o análisis profundo.

- Reflectly: Plataforma de journaling digital que utiliza inteligencia artificial básica para guiar reflexiones personales. Destaca por su experiencia de usuario, pero su nivel de personalización es limitado.

- Habitica: Aplicación de seguimiento de hábitos con un enfoque gamificado que incentiva la constancia mediante recompensas. Sin embargo, no considera el estado emocional del usuario en sus recomendaciones.

Estas soluciones representan enfoques parciales del problema, lo que evidencia una oportunidad para MindFlow de integrar análisis emocional, personalización dinámica y acompañamiento en tiempo real.

---

### 2.1.1. Análisis competitivo

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <th colspan="7">Competitive Analysis Landscape</th>
  </tr>

  <tr>
    <td colspan="2" rowspan="2"><b>¿Por qué llevar a cabo este análisis?</b></td>
    <td colspan="5">
      Identificar las fortalezas, debilidades y oportunidades de las aplicaciones actuales de bienestar digital, con el fin de comprender el posicionamiento de MindFlow dentro del mercado.
    </td>
  </tr>
  <tr>
    <td colspan="5">
      Comparar funcionalidades, estrategias y propuestas de valor para validar el uso de inteligencia artificial como elemento diferenciador en la gestión emocional y de hábitos.
    </td>
  </tr>

   <tr>
    <td colspan="3"></td>
    <td align="center">
      <b>MindFlow</b><br>
      <img src="../assets/MindFlow_logo.png" alt="MindFlow" height="80">
    </td>
    <td align="center">
      <b>Daylio</b><br>
      <img src="../assets/Daylio.png" alt="Daylio" height="80">
    </td>
    <td align="center">
      <b>Reflectly</b><br>
      <img src="../assets/Reflectly.png" alt="Reflectly" height="80">
    </td>
    <td align="center">
      <b>Habitica</b><br>
      <img src="../assets/Habitica.png" alt="Habitica" height="80">
    </td>
  </tr>

  <tr>
    <td rowspan="2"><b>Perfil</b></td>
    <td colspan="2">Overview</td>
    <td>Plataforma de salud mental con IA que integra diario emocional, análisis de sentimiento y hábitos dinámicos.</td>
    <td>Aplicación de registro de emociones con estadísticas simples.</td>
    <td>Diario digital guiado con inteligencia artificial básica.</td>
    <td>Aplicación de hábitos basada en gamificación.</td>
  </tr>

  <tr>
    <td colspan="2">Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
    <td>Personalización en tiempo real y acompañamiento emocional inteligente basado en IA.</td>
    <td>Facilidad de uso y rapidez en el registro de emociones.</td>
    <td>Experiencia de usuario atractiva enfocada en la reflexión personal.</td>
    <td>Motivación mediante recompensas y mecánicas de juego.</td>
  </tr>

  <tr>
    <td rowspan="2"><b>Perfil de Marketing</b></td>
    <td colspan="2">Mercado objetivo</td>
    <td>Jóvenes (18–35) con estrés académico o laboral.</td>
    <td>Público general.</td>
    <td>Usuarios interesados en journaling y bienestar.</td>
    <td>Personas orientadas a productividad.</td>
  </tr>

  <tr>
    <td colspan="2">Estrategias de marketing</td>
    <td>Modelo freemium, contenido educativo y crecimiento en redes sociales.</td>
    <td>Posicionamiento como app simple y accesible.</td>
    <td>Enfoque en diseño emocional y experiencia visual.</td>
    <td>Gamificación y comunidad activa.</td>
  </tr>

  <tr>
    <td rowspan="3"><b>Perfil de Producto</b></td>
    <td colspan="2">Productos & Servicios</td>
    <td>Diario emocional IA, hábitos adaptativos, intervenciones inteligentes.</td>
    <td>Registro de estado de ánimo.</td>
    <td>Diario guiado.</td>
    <td>Seguimiento de hábitos.</td>
  </tr>

  <tr>
    <td colspan="2">Precios & Costos</td>
    <td>Freemium + funciones premium.</td>
    <td>Freemium.</td>
    <td>Suscripción premium.</td>
    <td>Freemium con compras opcionales.</td>
  </tr>

  <tr>
    <td colspan="2">Canales de distribución (Web y/o Móvil)</td>
    <td>Web y aplicación móvil.</td>
    <td>Aplicación móvil.</td>
    <td>Aplicación móvil.</td>
    <td>Web y aplicación móvil.</td>
  </tr>

  <tr>
    <td rowspan="5"><b>Análisis SWOT</b></td>
  </tr>

  <tr>
    <td colspan="2">Fortalezas</td>
    <td>IA emocional, personalización dinámica, enfoque integral.</td>
    <td>Simplicidad y rapidez.</td>
    <td>Diseño atractivo.</td>
    <td>Gamificación efectiva.</td>
  </tr>

  <tr>
    <td colspan="2">Debilidades</td>
    <td>Dependencia tecnológica, necesidad de generar confianza.</td>
    <td>Sin inteligencia ni personalización.</td>
    <td>IA limitada.</td>
    <td>No aborda salud emocional.</td>
  </tr>

  <tr>
    <td colspan="2">Oportunidades</td>
    <td>Crecimiento del mercado de salud mental digital.</td>
    <td>Usuarios nuevos.</td>
    <td>Expansión del journaling.</td>
    <td>Crecimiento del mercado de productividad.</td>
  </tr>

  <tr>
    <td colspan="2">Amenazas</td>
    <td>Competidores consolidados y preocupaciones por privacidad.</td>
    <td>Apps más avanzadas.</td>
    <td>Competencia con mayor innovación.</td>
    <td>Integración de funciones en apps más completas.</td>
  </tr>

</table>

### 2.1.2. Estrategias y tácticas frente a competidores

A partir del análisis competitivo y del análisis SWOT realizado, se definen estrategias y tácticas preliminares que permitirán a MindFlow afrontar las fortalezas de sus competidores, aprovechar sus debilidades y capitalizar las oportunidades del entorno, mitigando a su vez las amenazas del mercado.

#### Estrategias

- **Estrategia de diferenciación frente a fortalezas de competidores:**
  Mientras aplicaciones como Daylio destacan por su simplicidad y Habitica por su gamificación, MindFlow propone una diferenciación basada en inteligencia artificial, integrando análisis emocional y personalización dinámica, lo cual permite ofrecer una experiencia más profunda y significativa.

- **Estrategia de aprovechamiento de debilidades del mercado:**
  Se identificó que los competidores carecen de retroalimentación en tiempo real y adaptación al estado emocional. MindFlow capitaliza esta debilidad mediante un sistema que responde activamente al usuario, incrementando la retención.

- **Estrategia de explotación de oportunidades:**
  El crecimiento del mercado de salud mental digital y la aceptación de soluciones basadas en IA representan una oportunidad clave. MindFlow se posiciona como una solución innovadora alineada con estas tendencias.

- **Estrategia de mitigación de amenazas:**
  Frente a la presencia de competidores consolidados, se prioriza la innovación continua, la experiencia de usuario y la generación de confianza mediante políticas de privacidad y transparencia en el uso de datos.

#### Tácticas

- **Frente a fortalezas de competidores:**
  - Diseñar una interfaz simple e intuitiva similar a Daylio, pero con mayor valor agregado.
  - Incorporar elementos motivacionales (inspirados en gamificación) sin perder el enfoque emocional.

- **Frente a debilidades de competidores:**
  - Implementar retroalimentación empática en tiempo real mediante IA.
  - Desarrollar un sistema de hábitos adaptativos basado en el estado emocional del usuario.

- **Frente a oportunidades del entorno:**
  - Crear contenido educativo sobre salud mental en redes sociales.
  - Promover el uso de la app en comunidades universitarias y profesionales jóvenes.

- **Frente a amenazas del mercado:**
  - Garantizar la seguridad y privacidad de los datos mediante encriptación.
  - Diferenciar la propuesta mediante innovación constante en funcionalidades.
  - Generar confianza comunicando claramente que la app no reemplaza terapia profesional.


#### Enfoque estratégico

MindFlow adopta una estrategia de diferenciación centrada en la innovación tecnológica y la experiencia del usuario. A diferencia de los competidores que abordan el problema de manera fragmentada, la plataforma integra múltiples funcionalidades en un sistema adaptativo, lo que le permite posicionarse como una solución más completa, inteligente y alineada con las necesidades actuales del usuario.

---

## 2.2. Entrevistas

La presente sección aborda la recolección de información cualitativa mediante entrevistas aplicadas a usuarios representativos de los segmentos objetivo definidos para MindFlow. Estas entrevistas tienen como propósito identificar patrones de comportamiento, necesidades emocionales, frustraciones y expectativas relacionadas con la gestión del estrés, la ansiedad y los hábitos de bienestar.

La información obtenida permitirá validar los supuestos planteados en el proyecto y servirá como base para el diseño de una solución centrada en el usuario.


### 2.2.1. Diseño de entrevistas

Se han diseñado dos bloques de preguntas dirigidos a los principales segmentos objetivo: estudiantes universitarios y profesionales jóvenes. Las preguntas han sido estructuradas para recopilar información cualitativa relevante en torno a aspectos demográficos, hábitos digitales, gestión del estrés y percepción sobre el uso de herramientas tecnológicas para el bienestar emocional.

Asimismo, se incluyen preguntas complementarias orientadas a la construcción de arquetipos de usuario (User Personas), considerando variables demográficas, psicográficas y de comportamiento digital.

---

A. Entrevistas a Segmento 1: Estudiantes Universitarios (18–25 años)

Objetivo: Comprender cómo los estudiantes gestionan su estrés académico, qué herramientas utilizan actualmente y cuáles son sus principales dificultades para mantener hábitos de bienestar.

**Preguntas principales:**

- ¿Podrías contarnos un poco sobre ti? (edad, carrera, ciclo, ciudad, etc.)
- ¿Cómo describirías tu nivel de estrés durante el ciclo académico?
- ¿En qué momentos sueles sentir más ansiedad o presión?
- ¿Qué haces actualmente para manejar el estrés o la ansiedad?
- ¿Has utilizado alguna aplicación para registrar tus emociones o hábitos?
- ¿Qué dificultades tienes para mantener hábitos saludables?
- ¿Qué tan cómodo(a) te sientes usando apps para tu bienestar?
- ¿Con qué dispositivos accedes más a aplicaciones? (móvil, laptop, etc.)
- ¿Qué aplicaciones usas con mayor frecuencia en tu día a día?
- ¿Qué redes sociales utilizas más?
- ¿Cuáles son tus principales objetivos personales o académicos?
- ¿Qué situaciones te generan mayor frustración actualmente?
- ¿Cómo describirías tu personalidad? (organizado, impulsivo, etc.)
- ¿Sueles seguir recomendaciones de influencers o contenido sobre bienestar?

---

B. Entrevistas a Segmento 2: Profesionales Jóvenes (26–35 años)

Objetivo: Identificar los retos relacionados con el estrés laboral, la gestión del tiempo y la adopción de herramientas digitales para el bienestar personal.

**Preguntas principales:**

- ¿Podrías contarnos un poco sobre ti? (edad, profesión, tipo de trabajo, etc.)
- ¿Cómo describirías tu nivel de estrés laboral?
- ¿Qué situaciones te generan mayor agotamiento?
- ¿Qué haces actualmente para reducir el estrés?
- ¿Has utilizado apps de productividad o bienestar?
- ¿Qué dificultades tienes para equilibrar trabajo y vida personal?
- ¿Qué dispositivos utilizas con mayor frecuencia?
- ¿Qué herramientas digitales usas para organizar tu día?
- ¿Qué canales digitales utilizas con mayor frecuencia?
- ¿Cuáles son tus principales objetivos profesionales y personales?
- ¿Qué factores te generan mayor frustración en tu rutina?
- ¿Qué valoras más en una aplicación digital?
- ¿Qué te generaría confianza o desconfianza al usar una app de salud mental?

---

### 2.2.2. Registro de entrevistas

### 2.2.3. Análisis de entrevistas

A partir de las entrevistas realizadas a los dos segmentos objetivo, se identificaron patrones de comportamiento, necesidades y frustraciones diferenciadas. Este análisis permite validar los supuestos planteados y orientar el diseño de la solución.

---

### Segmento 1: Estudiantes Universitarios (18–25 años)

**Entrevistados:** Jiss, Lucero, Jimena  

#### Nivel de estrés y comportamiento

- Nivel promedio: 6–7/10  
- Picos en evaluaciones: 8–9/10  

El estrés en este segmento es situacional, asociado principalmente a exámenes, carga académica y dificultad en cursos.

#### Patrones de comportamiento

1. **Procrastinación como respuesta al estrés**
   - Uso de redes sociales como mecanismo de escape  
   - Incremento del estrés posterior por acumulación de tareas  

   > “Me distraigo… pero después me estreso más.” (Jiss)  
   > “Me bloqueo… y termino dejando todo.” (Jimena)

2. **Baja adherencia a hábitos**
   - Intentos de organización que no se sostienen en el tiempo  
   - Uso de apps limitado a corto plazo  

   > “He probado apps… pero las dejo rápido.” (Jimena)

3. **Rechazo a esfuerzo adicional**
   - Baja disposición a escribir o registrar emociones  
   - Percepción de apps como una tarea extra  

   > “No usaría una app si tengo que escribir mucho.” (Jiss)

4. **Búsqueda de guía**
   - Necesidad de orientación clara ante situaciones de estrés  

   > “Que me diga qué hacer en ese momento.” (Jiss)

#### Frustraciones principales

- Aplicaciones centradas solo en registro  
- Falta de retroalimentación útil  
- Experiencias repetitivas  

> “Era como hablar sola.” (Jimena)  
> “Siempre era lo mismo.” (Lucero)

#### Necesidades clave

- Interacción simple y rápida  
- Bajo esfuerzo cognitivo  
- Recomendaciones claras  
- Apoyo en momentos críticos  

#### Insight del segmento

Los estudiantes requieren una herramienta que intervenga en momentos de bloqueo emocional, ofreciendo guía inmediata sin aumentar la carga cognitiva.

---

### Segmento 2: Profesionales Jóvenes (26–35 años)

**Entrevistados:** Alexandra, Luciana, Nordie  

#### Nivel de estrés y comportamiento

- Nivel promedio: 8/10  
- Picos: 9/10  
- Presencia de estrés constante en algunos casos  

El estrés es continuo y está vinculado a presión laboral, responsabilidad y cumplimiento de objetivos.

#### Patrones de comportamiento

1. **Fatiga mental**
   - Reducción de energía al final del día  
   - Dificultad para sostener hábitos  

   > “No tengo energía para seguir una rutina.” (Alexandra)

2. **Rechazo a pérdida de tiempo**
   - Evaluación constante del valor de las aplicaciones  
   - Abandono rápido si no generan impacto  

   > “Las apps me quitaban tiempo.” (Alexandra)

3. **Necesidad de personalización**
   - Contextos variables que requieren adaptación  

   > “Si no se adapta a mí, la dejo.” (Luciana)

4. **Orientación a resultados**
   - Búsqueda de soluciones prácticas y eficientes  

   > “Necesito soluciones prácticas.” (Alexandra)

5. **Burnout y automatización**
   - Rechazo a cualquier esfuerzo adicional en estados de agotamiento  

   > “Cuando ya estás agotada, no quieres hacer más cosas.” (Nordie)  
   > “Necesito algo que me dé soluciones sin tener que pensar mucho.” (Nordie)

#### Frustraciones principales

- Aplicaciones genéricas  
- Falta de personalización  
- Falta de resultados inmediatos  

> “Las apps no se adaptan a tu ritmo.” (Luciana)  
> “Son muy genéricas.” (Nordie)

#### Necesidades clave

- Personalización en tiempo real  
- Interacción de bajo esfuerzo  
- Recomendaciones prácticas  
- Valor inmediato  

#### Insight del segmento

Los profesionales requieren soluciones que optimicen su bienestar sin demandar tiempo ni esfuerzo adicional, integrándose de forma eficiente en su rutina.

---

### Comparación entre segmentos

| Factor | Estudiantes | Profesionales |
|--------|------------|--------------|
| Tipo de estrés | Situacional | Crónico |
| Nivel promedio | 6–7 | 8–9 |
| Problema principal | Procrastinación | Fatiga mental |
| Barrera | Falta de disciplina | Falta de tiempo |
| Rechazo | Esfuerzo cognitivo | Pérdida de tiempo |
| Necesidad clave | Guía | Eficiencia |

---

### Insight estratégico general

Ambos segmentos coinciden en que las soluciones actuales fallan por ser pasivas, genéricas y demandar demasiado esfuerzo. Esto evidencia la oportunidad de desarrollar una plataforma que proporcione respuestas en tiempo real, minimice el esfuerzo del usuario y ofrezca recomendaciones personalizadas con impacto inmediato.

## 2.3. Needfinding

---

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

## 2.4. Big Picture EventStorming

---

## 2.5. Ubiquitous Language

---
