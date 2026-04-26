
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

---

## Segmento 1: Estudiantes Universitarios

### Entrevista 1

| Campo | Detalle |
|------|--------|
| Segmento Objetivo | Estudiantes universitarios (18–25 años) |
| Fecha Entrevista | 18/04/2026 |
| Entrevistador | Sebastián Díaz |
| Entrevistado | Jiss Zerpa  |
| Edad | 18 años |
| Distrito | La Molina |
| Link del Video | [Ver video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202410421_upc_edu_pe/IQC6LCtoZRnfR4iKU3dIHCeYATI4FuIHWP1zmVrAm3H4_R8?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=jFGNLe) |
| Minuto de Inicio | 0:00 |
| Duración | 2:47 |
| Resumen | Jiss, estudiante de Ingeniería Petroquímica, presenta un nivel de estrés de 7/10 con picos de 9 en exámenes. Su comportamiento refleja evitación del estrés mediante distracciones como TikTok y videojuegos. Reconoce que estas actividades le generan alivio momentáneo, pero posteriormente incrementan su ansiedad. Ha probado apps, pero las abandona rápidamente por requerir esfuerzo adicional. Insight principal: comportamiento de evitación frente al estrés. Hallazgos clave: alta procrastinación, baja tolerancia al esfuerzo y falta de estructura. Citas relevantes: “Me distraigo… pero después me estreso más.”, “No usaría una app si tengo que escribir mucho.” Conclusión: requiere soluciones simples, automáticas y de mínima interacción. |

---

### Entrevista 2

| Campo | Detalle |
|------|--------|
| Segmento Objetivo | Estudiantes universitarios (18–25 años) |
| Fecha Entrevista | 19/04/2026 |
| Entrevistador | Sebastián Díaz |
| Entrevistado | Lucero |
| Edad | 19 años |
| Distrito | La Molina |
| Link del Video | [Ver video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202410421_upc_edu_pe/IQAp-_6iUOSJS4FRQuTW-F-9AdcZK5XV42aVZmzgo0PuIAw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=HwtMjV) |
| Minuto de Inicio | 0:00 |
| Duración | 2:41 |
| Resumen | Lucero, estudiante de Psicología, presenta un nivel de estrés de 6/10 con picos de 8. Tiene alta autoconciencia emocional y utiliza journaling, pero percibe que las herramientas actuales no generan cambios reales. Insight principal: perfil reflexivo con insatisfacción en el impacto de las soluciones actuales. Hallazgos clave: uso de journaling sin resultados, necesidad de análisis profundo y rechazo a la repetición. Citas relevantes: “Escribir me ayuda a entenderme, pero no cambia cómo me siento.”, “Las apps se vuelven repetitivas.” Conclusión: necesita soluciones que aporten análisis significativo y evolución emocional. |

---

### Entrevista 3

| Campo | Detalle |
|------|--------|
| Segmento Objetivo | Estudiantes universitarios (18–25 años) |
| Fecha Entrevista | 20/04/2026 |
| Entrevistador | Sebastián Díaz |
| Entrevistado | Jimena |
| Edad | 19 años |
| Distrito | San Isidro |
| Link del Video | [Ver video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202410421_upc_edu_pe/IQDiIjKmBwlYSY162dNCHfq1AcmQjaPB0B48xM6UgMCISww?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=ciHjIU) |
| Minuto de Inicio | 0:00 |
| Duración | 2:48 |
| Resumen | Jimena, estudiante de Ingeniería de Software, presenta un nivel de estrés de 6/10 con picos de 8–9. Experimenta frustración en tareas académicas que deriva en bloqueo cognitivo y procrastinación. Ha utilizado múltiples apps, pero las abandona por falta de valor inmediato. Insight principal: patrón frustración → bloqueo → evasión. Hallazgos clave: bloqueo cognitivo, uso de distracción como escape y abandono rápido de apps. Citas relevantes: “Me bloqueo… y termino dejando todo.”, “Las apps solo te hacen escribir, pero no te ayudan.” Conclusión: requiere intervenciones en tiempo real que ayuden en momentos críticos. |

---

## Segmento 2: Profesionales Jóvenes

### Entrevista 4

| Campo | Detalle |
|------|--------|
| Segmento Objetivo | Profesionales jóvenes (26–35 años) |
| Fecha Entrevista | 18/04/2026 |
| Entrevistador | Sebastián Díaz |
| Entrevistado | Alexandra Montenegro |
| Edad | 26 años |
| Distrito | Barranco |
| Link del Video | [Ver video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202410421_upc_edu_pe/IQBLlsZ3G-OZSLcOUS5eF6rQARMpWE6b_f3IIphyY7o3vlI?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=p0isA8) |
| Minuto de Inicio | 0:00 |
| Duración | 3:15 |
| Resumen | Alexandra, profesional en Recursos Humanos, presenta un nivel de estrés de 8/10 con picos de 9. Su principal limitación es la falta de energía tras la jornada laboral, lo que impide sostener hábitos. Insight principal: limitación de tiempo y energía. Hallazgos clave: dificultad para mantener rutinas, percepción de apps como costo de tiempo y preferencia por soluciones inmediatas. Citas relevantes: “Llego cansada del trabajo… no tengo energía para seguir una rutina.”, “Las apps me quitaban tiempo o no me daban algo útil en el momento.” Conclusión: requiere soluciones rápidas, de bajo esfuerzo y con valor inmediato. |

---

### Entrevista 5

| Campo | Detalle |
|------|--------|
| Segmento Objetivo | Profesionales jóvenes (26–35 años) |
| Fecha Entrevista | 19/04/2026 |
| Entrevistador | Sebastián Díaz |
| Entrevistado | Luciana Poma |
| Edad | 27 años |
| Distrito | Chorrillos |
| Link del Video | [Ver video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202410421_upc_edu_pe/IQAXQKz8cFuBRYmMRiluA61vAYFJfoUS8D6IibXF6VSNjnE?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=qxkwbB) |
| Minuto de Inicio | 0:00 |
| Duración | 3:06 |
| Resumen | Luciana, profesional de marketing digital, presenta un nivel de estrés de 8/10 con picos de 9. Usa apps frecuentemente, pero abandona aquellas que no se adaptan a su ritmo. Insight principal: necesidad de personalización dinámica. Hallazgos clave: frustración con apps rígidas, alta presión por resultados y relación entre bienestar y productividad. Citas relevantes: “Las apps no se adaptan a tu ritmo real.”, “Si no se adapta a mí, la dejo.” Conclusión: el producto debe ofrecer adaptación en tiempo real. |

---

### Entrevista 6

| Campo | Detalle |
|------|--------|
| Segmento Objetivo | Profesionales jóvenes (26–35 años) |
| Fecha Entrevista | 21/04/2026 |
| Entrevistador | Sebastián Díaz |
| Entrevistado | Nordie Sanabria|
| Edad | 29 años |
| Distrito | La Molina |
| Link del Video | [Ver video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202410421_upc_edu_pe/IQAu709K0qBWQZsvqeI53bCHAdB9HmsozDqHD-ua8jw6HjU?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=rM0yrn) |
| Minuto de Inicio | 0:00 |
| Duración | 2:52 |
| Resumen | Nordie, coordinadora de marketing, presenta un nivel de estrés constante de 9/10, cercano al burnout. Ha probado múltiples apps sin éxito. Insight principal: rechazo a cualquier esfuerzo adicional. Hallazgos clave: estrés constante, rechazo a interacción compleja y necesidad de automatización total. Citas relevantes: “Siento que estoy siempre en alerta.”, “Cuando ya estás agotada, no quieres hacer más cosas.”, “Necesito algo que me dé soluciones sin tener que pensar mucho.” Conclusión: requiere una solución altamente automatizada, predictiva y sin fricción. |

---

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

En esta sección se presentan los artefactos resultantes del proceso de análisis de la información recolectada a través de entrevistas. El objetivo del needfinding es transformar los hallazgos cualitativos en representaciones estructuradas que permitan comprender profundamente a los usuarios, sus necesidades, comportamientos y puntos de dolor.

A partir de los insights obtenidos, se desarrollan los siguientes artefactos:

- User Personas  
- User Task Matrix  
- User Journey Mapping  
- Empathy Mapping  
- Big Picture EventStorming  
- Ubiquitous Language  

Estos elementos permiten al equipo alinear la comprensión del problema, identificar oportunidades de diseño y establecer una base sólida para la definición de requerimientos del sistema.

El proceso de needfinding evidencia que los usuarios no solo buscan registrar su estado emocional, sino recibir apoyo activo, personalizado y en tiempo real, lo cual guía directamente la propuesta de valor de la solución MindFlow.

### 2.3.1. User Personas
#### Segmento Estudiantes Universitarios:
  <img src="../assets/User Persona1.png" alt="MindFlow" height="auto">
  
#### Segmento Profesionales jóvenes:
  <img src="../assets/User Persona2.png" alt="MindFlow" height="auto">

### 2.3.2. User Task Matrix

En esta sección se presenta la matriz de tareas de usuario (User Task Matrix), construida a partir de los User Personas definidos: **Jimena** (estudiante universitaria) y **Nordie** (profesional joven).  

La matriz identifica las tareas que ambos segmentos realizan para gestionar su bienestar emocional y productividad en su día a día, independientemente de la existencia de una solución tecnológica.  

Cada tarea se evalúa en función de:  
- **Frecuencia:** Número aproximado de veces que realiza la tarea (diaria/semanal)  
- **Importancia:** Nivel de relevancia para el usuario (Alta, Media, Baja)  

---

#### User Task Matrix

| Tareas del Usuario | Jimena (Frecuencia) | Jimena (Importancia) | Nordie (Frecuencia) | Nordie (Importancia) |
|------------------|---------------------|----------------------|---------------------|----------------------|
| Identificar que está estresado o abrumado | 2–3 veces al día | Alta | 3–5 veces al día | Alta |
| Intentar continuar con sus responsabilidades a pesar del estrés | Diario | Alta | Diario | Alta |
| Buscar distracciones (redes sociales, entretenimiento) | 2–4 veces al día | Media | 1–2 veces al día | Baja |
| Tomar pausas para despejarse | 1–2 veces al día | Alta | 1–2 veces al día | Alta |
| Intentar organizar tareas o responsabilidades | 3–4 veces por semana | Alta | Diario | Alta |
| Reflexionar sobre cómo se siente | 1–2 veces por semana | Media | 1 vez por semana | Media |
| Buscar soluciones rápidas para reducir el estrés | 1–2 veces al día | Alta | 2–3 veces al día | Alta |
| Intentar mantener hábitos de bienestar (ejercicio, descanso) | 2–3 veces por semana | Alta | 1–2 veces por semana | Alta |
| Usar herramientas digitales para organizarse o mejorar su bienestar | 3–4 veces por semana | Media | 2–3 veces por semana | Alta |
| Abandonar herramientas o rutinas por falta de resultados | 1 vez por semana | Alta | 1 vez por semana | Alta |

---

### Análisis de la matriz

Se observa que las tareas con mayor frecuencia e importancia en ambos segmentos están relacionadas con la **gestión inmediata del estrés**, especialmente:

- Identificación del estrés varias veces al día  
- Continuación de responsabilidades bajo presión  
- Búsqueda de soluciones rápidas para aliviar el malestar  

Esto confirma que el problema ocurre en **micro-momentos diarios**, no como eventos aislados.

---

### Coincidencias entre segmentos

- Ambos identifican el estrés múltiples veces al día  
- Buscan soluciones rápidas de forma recurrente  
- Presentan abandono semanal de herramientas que no aportan valor  
- Mantienen baja frecuencia en hábitos de bienestar  

---

### Diferencias clave

- **Jimena (Estudiante):**
  - Mayor frecuencia en distracciones (hasta 4 veces al día)  
  - Menor consistencia en organización (no diaria)  

- **Nordie (Profesional):**
  - Mayor constancia en organización (diaria)  
  - Menor uso de distracciones, pero mayor carga mental constante  

---

### Conclusión

Los datos evidencian que el problema ocurre varias veces al día, lo que requiere una solución capaz de responder en tiempo real. Además, la alta tasa de abandono semanal confirma que los usuarios priorizan herramientas que generen valor inmediato, sin requerir esfuerzo adicional.

### 2.3.3. User Journey Mapping

#### Segmento Estudiantes Universitarios:
  <img src="../assets/User Journey Mapping1.png" alt="MindFlow" height="auto">
  
#### Segmento Profesionales jóvenes:
  <img src="../assets/User Journey Mapping2.png" alt="MindFlow" height="auto">

### 2.3.4. Empathy Mapping

#### Segmento Estudiantes Universitarios:
  <img src="../assets/Empathy map1.png" alt="MindFlow" height="auto">
  
#### Segmento Profesionales jóvenes:
  <img src="../assets/Empathy map2.png" alt="MindFlow" height="auto">

## 2.4. Big Picture EventStorming

El Design-Level EventStorming de MindFlow representa la transición entre los requerimientos del negocio y el diseño técnico de la solución. A través de este modelo, se han mapeado los procesos críticos del sistema —desde el análisis de sentimientos mediante IA hasta la gestión proactiva del estrés— utilizando un lenguaje común entre el equipo de desarrollo y los expertos del dominio. Este diagrama permite visualizar no solo las acciones del usuario, sino también las reglas de negocio, las interacciones con sistemas externos y los cambios de estado en las entidades principales del software.

<img src="../assets/Big-Picture-Event-Storming.png" alt="Big Picture Event Storming">

<br>

El diseño se estructura en tres flujos principales que responden a las épicas del proyecto:

Módulo de Inteligencia Emocional: Se detalla el proceso en el cual una entrada de diario activa el motor de procesamiento de lenguaje natural (NLP Engine), derivando en retroalimentación empática o alertas de crisis según el sentimiento detectado.

Módulo de Bienestar Adaptativo: Muestra la lógica de intervención proactiva, donde el sistema evalúa el nivel de burnout del usuario y ajusta automáticamente la carga de hábitos diarios para evitar el agotamiento.

Módulo de Gestión y Monetización: Describe el ciclo de vida de la cuenta de usuario, integrando pasarelas de pago seguras y procesos de encriptación de datos para garantizar la privacidad y el acceso a funciones premium.

La identificación de Hotspots en estos flujos ha permitido anticipar desafíos técnicos, como los tiempos de respuesta de la IA y la seguridad de la información, asegurando una arquitectura robusta y escalable.


---

## 2.5. Ubiquitous Language

---
