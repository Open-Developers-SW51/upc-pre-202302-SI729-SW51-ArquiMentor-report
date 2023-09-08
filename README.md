# Universidad Peruana de Ciencias Aplicadas.
### Ingeniería de Software.
### Desarrollo de Aplicaciones Open Source.
### SW51
#### Angel Augusto Velasquez Nuñez
---

# Proyecto del Curso.

## TB1 REPORT

### StartUp Name
#### Open Developers
### Team Members

|   Members     |   User    |
|:-------------:|:---------:|
|---, ---                           |u202112936|
|---, ---                           |u202114140|
|Luyo Ramirez, Rafael Arturo        |u202115348|
|----, ----                         |u202110458|
|--, ---                            |u20201b895|

#### Ciclo 2023 - 02

<br><br>

## Registros de versiones del Informe

|   Version     |   Fecha   |   Autor   |   Descripción de la modificación|
|:-------------:|:---------:|:---------|:------------------------|
|1              |           |----|- Implementó  |
|1              |           |---|- Implementó  |
|1              | 31/08/23  |Luyo Ramirez |- Implementó 4.1, 4.2, 4.3, 4.8  |
|1              |           |--|- Implementó  |
|1              |           |--|- Implementó  |

<br><br>
# Índice

## 1. Capítulo I: Introducción

- [1.1 Startup Profile](#11-startup-profile)
    - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2 Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
        - [1.2.2.1 Lean UX Problem Statements](#1221-lean-ux-problem-statements)
        - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)
        - [1.2.2.3 Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
        - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3 Segmentos objetivo](#13-segmentos-objetivo)

## 2. Capítulo II: Requirements Elicitation & Analysis

- [2.1 Competidores](#21-competidores)
    - [2.1.1 Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2 Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2 Entrevistas](#22-entrevistas)
    - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2 Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3 Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3 Needfinding](#23-needfinding)
    - [2.3.1 User Personas](#231-user-personas)
    - [2.3.2 User Task Matrix](#232-user-task-matrix)
    - [2.3.3 User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4 Empathy Mapping](#234-empathy-mapping)
    - [2.3.5 As-is Scenario Mapping](#235-as-is-scenario-mapping)

## 3. Capítulo III: Requirements Specification

- [3.1 To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2 User Stories](#32-user-stories)
- [3.3 Impact Mapping](#33-impact-mapping)
- [3.4 Product Backlog](#34-product-backlog)

## 4. Capítulo IV: Product Design

- [4.1 Style Guidelines](#41-style-guidelines)
    - [4.1.1 General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2 Web Style Guidelines](#412-web-style-guidelines)
- [4.2 Information Architecture](#42-information-architecture)
    - [4.2.1 Organization Systems](#421-organization-systems)
    - [4.2.2 Labeling Systems](#422-labeling-systems)
    - [4.2.3 SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4 Searching Systems](#424-searching-systems)
    - [4.2.5 Navigation Systems](#425-navigation-systems)
- [4.3 Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1 Landing Page Wireframe](#431-landing-page-wireframeS)
    - [4.3.2 Landing Page Mock-up](#432-landing-page-mock-up)
- [4.4 Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1 Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2 Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3 Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4 Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
- [4.5 Web Applications Prototyping](#45-web-applications-prototyping)
- [4.6 Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1 Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2 Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3 Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
- [4.7 Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1 Class Diagrams](#471-class-diagrams)
    - [4.7.2 Class Dictionary](#472-class-dictionary)
- [4.8 Database Design](#48-database-design)
    - [4.8.1 Database Diagram](#481-database-diagram)

## 5. Capítulo V: Product Implementation, Validation & Deployment

- [5.1 Software Configuration Management](#51-software-configuration-management)
    - [5.1.1 Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2 Source Code Management](#512-source-code-management)
    - [5.1.3 Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4 Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2 Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.X Sprint n](#52x-sprint-n)
        - [5.2.X.1 Sprint Planning n](#52x1-sprint-planning-n)
        - [5.2.X.2 Sprint Backlog n](#52x2-sprint-backlog-n)
        - [5.2.X.3 Development Evidence for Sprint Review](#52x3-development-evidence-for-sprint-review)
        - [5.2.X.4 Testing Suite Evidence for Sprint Review](#52x4-testing-suite-evidence-for-sprint-review)
        - [5.2.X.5 Execution Evidence for Sprint Review](#52x5-execution-evidence-for-sprint-review)
        - [5.2.X.6 Services Documentation Evidence for Sprint Review](#52x6-services-documentation-evidence-for-sprint-review)
        - [5.2.X.7 Software Deployment Evidence for Sprint Review](#52x7-software-deployment-evidence-for-sprint-review)
        - [5.2.X.8 Team Collaboration Insights during Sprint](52x8-team-collaboration-insights-during-sprint)

<br>

# Student Outcome
| Criterio específico | Acciones Realizadas | Conclusiones |
|:--------------------|:-------------------:|:------------:|
|Comunica oralmente con efectividad a diferentes rangos de audiencia|Tareas| Conclusion de Student Outcome|
|Comunica por escrito con efectividad a diferentes rangos de audiencia|Tareas|Conclusion de Student Outcome|
<br><br>

# Capitulo 1: Introducción

## 1.1 Startup Profile

### 1.1.1 Descripción de la Startup


 #### Misión



#### Visión



### 1.1.2 Perfiles de integrantes del equipo

<table style="border-collapse: collapse; width: 100%;">
  <tr>
    <th style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Foto</th>
    <th style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Miembro</th>
    <th style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Habilidades</th>
    <th style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Codigo</th>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="" alt="" width="60" height="50" style="border-radius: 25%;">
    </td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">##</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">##</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">##</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149207235973632050/foto.jpg" alt="##" width="50" height="50" style="border-radius: 25%;">
    </td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Kurt Puican Salas</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Soy Kurt Puican Soy un estudiante de la carrera de ingeniería de software y a lo largo de toda la carrera he ido aprendiendo diversos temas como los lenguajes de programación, los patrones de diseño entre varias otras cosas y es una carrera que me gusta bastante ya que desde pequeño siempre me ha gustado lo que tiene que ver con la tecnología.</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">U202016643</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://cdn.discordapp.com/attachments/1149190528756363338/1149190749762637884/FotoRafaelLuyo.jpg" alt="FotoRafaelLuyo" width="50" height="50" style="border-radius: 25%;">
    </td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Luyo Ramirez, Rafael Arturo</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Mi nombre es Rafael Luyo, tengo 21 años. Me considero una persona agradable, puntual y respetuosa. Elegí mi profesión actual porque disfruto haciendo varios ejercicios o problemas relacionados con el uso de la programación, además de interesarme mucho la malla curricular. Me motiva aprender cosas nuevas y también la futura estabilidad económica.  </td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">u201919295</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="##" alt="##" width="50" height="50" style="border-radius: 25%;">
    </td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">##</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">##</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">##</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="##" alt="##" width="50" height="50" style="border-radius: 25%;">
    </td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">##</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">##</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">##</td>
  </tr>
</table>

# Capitulo 2: Requirements Elicitation & Analysis

# Capitulo 3: Requirements Specification

# Capitulo 4: Product Design

## 4.1 Style Guidelines
En esta sección, se establecen las pautas de estilo y desarrollo coherentes para garantizar que la solución "ArquiMentor" tenga un enfoque unificado y consistente en su implementación.
### 4.1.1 General Style Guidelines
#### Brand Overview
La atención integral y efectiva a estudiantes universitarios que enfrentan desafíos académicos se vuelve esencial en nuestra sociedad. Las necesidades de los estudiantes de arquitectura requieren un enfoque especializado, por lo que nuestra solución, "ArquiMentor", surge como respuesta a la necesidad de asesoría en el ámbito educativo específico de la arquitectura. Ofrecemos acceso virtual a profesionales y especialistas en cursos relacionados con la arquitectura, asegurando una calidad excepcional en la asesoría. Tenemos conocimiento de que la atención personalizada es crucial en la educación para el éxito académico en esta disciplina. Con "ArquiMentor", estamos comprometidos en brindar un entorno donde los estudiantes de arquitectura puedan obtener la ayuda necesaria para comprender los temas, prepararse para exámenes y desarrollar habilidades clave. Nuestra visión es ser la plataforma líder para estudiantes de arquitectura que buscan mejorar su rendimiento académico y alcanzar sus objetivos educativos en esta carrera.

#### Brand Name
El software ha sido bautizado como "ArquiMentor". Este nombre surge directamente de nuestra visión de proporcionar orientación académica especializada y personalizada a estudiantes universitarios. Al optar por el idioma inglés, hemos buscado crear una identidad amigable y atractiva para nuestros usuarios potenciales. La palabra "ArquiMentor" fusiona perfectamente el acto de estudiar y el concepto de guía, transmitiendo la idea de un mentor que brinda dirección y apoyo en el ámbito educativo. Nuestra esperanza es que este nombre se convierta en sinónimo de excelencia educativa y se asocie con una herramienta confiable para el crecimiento y el éxito académico.
A continuación, se presenta el logo o marca de nuestra solución propuesta.
<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149509281952051220/image.png" alt="icons">
#### Typography
La selección de tipografías resulta esencial para dar forma y orden al aspecto visual de todas las plataformas que se crearán con el fin de satisfacer las características fundamentales de la aplicación. Se ha considerado primordial que las fuentes sean fácilmente legibles y contribuyan a la experiencia del usuario, por lo cual se han escogido estos estilos de letras con especial atención.

<table>
  <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Francois One Google Fonts</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Roboto Google Fonts</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Lato
Google Fonts
</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Inter
Google Fonts
</td>
  </tr>
</table>

# Head

<table>
  <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Name</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Font size</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Line Height</tr>
     <tr>
  <td style="border:1px solid #dddddd; padding: 8px; text-align:center;"><h1>Heading 1</h1></td>
  <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">56 px</td>
  <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">61.6 px</td>
</tr>
      <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;"><h2>Heading 2</h2></td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">48 px</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">52.8 PX</tr>
      <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;"><h3>Heading 3</h3></td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Font size</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Line Height</tr>
      <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;"><h4>Heading 4</h4></td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">32 px</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">35.2 px</tr>
      <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;"><h5>Heading 5</h5></td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">24 px</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">26.4 px</tr>
      <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;"><h6>Heading 6</h6></td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">20 px</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">22 px</tr>
</table>

#### Colors
<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149509920341889034/image.png" alt="colors">

#### Spacing
<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149510151909412864/image.png" alt="spacing">

### 4.1.2 Web Style Guidelines
Daremos forma a una aplicación que se adapte a cualquier dispositivo tecnológico, asegurando que el diseño del contenido no se vea afectado. Por consiguiente, consideraremos cada tipo de dispositivo para organizar el contenido de manera óptima en cada caso.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149510537466626048/disenCC83o20responsive-1.png" alt="responsive-image" width="300" height="200" style="border-radius: 25%;">

Aplicaremos el patrón Z en nuestra interfaz, lo que permitirá destacar nuestro logo o marca en la esquina superior izquierda, marcando el inicio de la interacción del usuario. Luego, el recorrido se desplazará hacia la derecha, revelando las diversas opciones disponibles como "Acerca de", "Reserva tu sesión" o el área de configuración. Enseguida, el usuario se desplazará verticalmente hacia abajo, continuando su interacción con el contenido de la aplicación. Finalmente, la trayectoria lo llevará a la esquina inferior derecha, donde podrá acceder a nuestras redes sociales y medios de contacto.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149511335265194034/eyetrackingpatronz.png" alt="z-pattern" width="300" height="230" style="border-radius: 25%;">

Consecuentemente, el diseño de nuestra aplicación incorporará colores que inspiren al usuario a explorar la plataforma con entusiasmo. También implementaremos sombras y espacios adecuados para mejorar la legibilidad de la información y para mantener el contenido en un formato que no abrume al navegante. Utilizaremos varios de los siguientes elementos en el diseño para lograr estos objetivos.
Se emplearán algunos de los siguientes elementos:

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149511726430158888/image.png" alt="selection-box-and-buttons" >

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149512062825938954/image.png" alt="big-elements" >

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149512103393247252/image.png" alt="cards" >

Link para visualizar el figma con el Style Guidelines general:
https://www.figma.com/file/eC8KKKc4IrBb7cBpM99D5L/Web-%26-Mobile-Style-Guidelines-(Arquisesor)?type=design&node-id=0%3A1&mode=design&t=WJhpZvwG1b4skT37-1 

## 4.2 Information Architecture
En esta sección, detallaremos la estructura de nuestra solución "ArquiMentor" para satisfacer las necesidades de nuestros usuarios. Abordaremos varios aspectos que permitirán a los estudiantes organizar y acceder al contenido de manera eficiente: Sistemas de Organización, Sistemas de Etiquetado, Etiquetas de SEO y Metaetiquetas, Sistemas de Búsqueda y Sistemas de Navegación
### 4.2.1 Organization Systems
En las siguientes líneas, describiremos cómo se implementarán diferentes métodos de organización visual para cada uno de nuestros segmentos de usuarios, asegurándonos de que el contenido esté estructurado de manera coherente y accesible.

### Segmento 1: Estudiantes que buscan Ayuda en sus estudios:

#### Jerárquica:

#### Materias y Cursos:
- Los estudiantes podrán acceder a diferentes materias y cursos disponibles de la carrera de Arquitectura. La información se organizará por categorías de materias y secciones, permitiendo a los estudiantes explorar y elegir áreas de interés.

#### Asesores y Profesores:
- Se mostrará una lista de asesores y profesores disponibles en cada materia de la carrera de Arquitectura. La organización se realizará en función de la especialidad y la experiencia de cada asesor.

#### Sesiones de Asesoría:
- Los estudiantes podrán programar sesiones de asesoría con sus profesores y asesores elegidos. Las fechas y horarios se mostrarán en orden cronológico.

#### Perfil del profesional:
- El usuario podrá acceder al perfil del profesional para hacer una selección de preferencia más íntegra. Los datos del profesional estarán organizados de acuerdo con su relevancia.

#### Sesiones de Asesoría:
- Los estudiantes podrán programar sesiones de asesoría con sus profesores y asesores elegidos. Las fechas y horarios se mostrarán en orden cronológico.
Claro, aquí tienes el texto formateado en Markdown con viñetas y subtítulos:

### Secuencial:

#### Programación de Sesiones:
 Los estudiantes seguirán pasos para programar una sesión de asesoría. Esto incluirá la selección de un asesor, elección de fecha y hora, y confirmación de la reserva.

## Segmento 2: Profesores y Asesores: 

### Jerárquica:

#### Lista de Estudiantes: 
 - Los profesores verán una lista de estudiantes que han solicitado asesoría. La información se organizará en función de las fechas de solicitud.

#### Sesiones Programadas:
- Los profesores accederán a sus sesiones programadas, organizadas por fechas y horarios.

#### Perfil del estudiante: 
- El profesional podrá acceder al perfil del estudiante para revisar que está solicitando. Esta información estará organizada de acuerdo con su relevancia.

#### Contenido de Asesoría:
- Los recursos y materiales que los profesores comparten con los estudiantes se organizarán por temas y categorías.

**Jerárquica:**

- **Landing Page:** En esta sección, presentaremos información esencial de nuestro proyecto para cualquier interesado. Esto abarcará detalles sobre nuestros servicios y nuestra información de contacto, entre otros aspectos. Esta información se estructurará de manera que lo más relevante aparezca en primer lugar y se organizará en categorías temáticas.

- **Reseñas:** En esta sección, los usuarios tendrán la oportunidad de evaluar la calidad del servicio brindado por profesionales o asesores. Estas evaluaciones se organizarán cronológicamente (las opiniones más recientes se mostrarán primero).

**Matricial:**

- **Menú de opciones:** Ambos segmentos tendrán acceso a un menú principal desde donde podrán acceder a las funciones necesarias, organizadas por categorías.

- **Noticias y Recomendaciones:** Ambos segmentos encontrarán noticias y recomendaciones organizadas en base a temas.

Esta arquitectura de información optimizará la experiencia del usuario, facilitando la exploración y el acceso a recursos relevantes para cada segmento de usuarios en nuestra plataforma "ArquiMentor".

### 4.2.2 Labeling Systems

A continuación, presentaremos el sistema de categorización que permitirá a nuestros visitantes acceder a la información de nuestra landing page mediante una única palabra.

Tenemos cuatro “headings” con una fuente sans-serif ubicadas en la parte superior de la Landing page:

- **Home:** La sección preseleccionada en la que los usuarios encontrarán la información más importante, diseñada para llamar su atención.

- **About:** La sección en la que los clientes pueden conocer nuestra misión, visión, identidad y actividades.

- **Services:** Una sección dedicada a enumerar y describir los servicios que proporcionamos.

- **Contact:** La sección donde se proporciona información detallada sobre nuestros canales de comunicación y ubicación.

Para la versión de la Web Aplication dirigida a estudiantes de Arquitectura, disponemos de cinco “headings” con fuente  Lato, ubicados en el menú principal de la parte izquierda.

- **Home** Área predeterminada donde se presentan noticias de alta relevancia junto con las opciones clave dirigidas al estudiante.

- **My profile:** Sección donde los datos personales del estudiante están disponibles.

- **News:** Espacio donde el estudiante puede ver noticias relacionadas con los cursos de Arquitectura.

- **Prescription:** Zona donde el estudiante puede revisar todas las prescripciones que ha recibido hasta ahora.

- **Configuration:** Sección donde el estudiante puede ajustar la configuración por defecto de la plataforma.

Para la Web Application dirigida a asesores, tenemos cinco "headings" con fuente Lato ubicados en el menú principal en el lateral izquierdo.

- **Home:** Sección predeterminada donde se presentan noticias relevantes junto con las opciones clave dirigidas al profesional o asesor.

- **My profile:** Sección donde se encuentran los detalles personales del profesional o asesor.

- **News:** Sección donde el asesor puede acceder a noticias relacionadas con los cursos.

- **Reviews:** Sección donde se muestran las opiniones recibidas de los estudiantes a los que el asesor ha atendido.

- **Configuration:** Sección donde el asesor puede realizar ajustes en la configuración estándar de la plataforma.

### 4.2.3 SEO Tags and Meta Tags
A continuación, se presentarán los SEO Tags y Meta Tags empleados en la Landing Page con el objetivo de mejorar su visibilidad en los motores de búsqueda.

## Landing Page:
<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149519910364520509/image.png" alt="SEO-tags-and-Meta-Tags" >

### 4.2.4 Searching Systems
En las próximas secciones, se presentarán los sistemas de búsqueda incorporados para facilitar a nuestros usuarios la localización de la información que necesitan.
Para la Landing Page, no se ha integrado un sistema de búsqueda, dado que la información se encuentra segmentada y enlazada en el menú principal. En consecuencia, los visitantes podrán acceder a toda la información esencial de nuestra solución, como nuestra dedicación, servicios y, sobre todo, podrán encontrar los detalles de contacto para comunicarse con nosotros.
Para el caso del Web Application:

#### Segmento 1: Estudiantes que buscan ayuda en los cursos de Arquitectura
- **Seguimiento del Proceso de la Maqueta:**
 Esta sección permitirá a los estudiantes de arquitectura visualizar el progreso de sus proyectos de maquetas de manera detallada. Si un estudiante desea verificar los detalles de un proyecto en particular, puede aplicar filtros según el curso y el estado del proyecto (En Progreso, Completado). Una vez aplicados los filtros, o incluso si no se aplican, los proyectos se mostrarán en formato de lista con información resumida. Al hacer clic en un proyecto específico, se mostrarán todos los detalles, incluyendo los materiales necesarios, el profesor asignado y el tiempo estimado de finalización. Además, si un estudiante necesita encargar una maqueta a un asesor, podrá ver el tiempo estimado de finalización, los materiales requeridos y el costo asociado a dicho servicio.
 
- **Mentores Disponibles:** Los estudiantes podrán aplicar filtros basados en diferentes criterios como materia, preferencia de idioma, experiencia, etc. La información filtrada se mostrará en formato de lista, mostrando detalles clave sobre cada mentor, como su nombre, especialización y calificación con estrellas (5 estrellas indican un servicio de alta calificación).
#### Segmento 2: Profesores y Asesores
- **Lista de Estudiantes:** Los mentores tendrán la capacidad de buscar estudiantes específicos utilizando una barra de búsqueda. También podrán utilizar filtros como género y fecha de interacción para reducir la lista. La información filtrada se mostrará en formato de lista, mostrando detalles básicos de cada estudiante, como su nombre y curso.
- **Resumen de Ganancias:** Los mentores académicos pueden filtrar transacciones según su estado (Completadas, Pendientes, Canceladas) para administrar eficazmente sus ganancias.
- **Horario de Citas:** Los mentores tendrán un calendario donde podrán ver y gestionar sus citas con los estudiantes en días específicos. Al hacer clic en una fecha, podrán ver una lista de citas ordenadas cronológicamente (primeras citas próximas). Si los mentores necesitan acceder a información específica de un estudiante, pueden usar la función de búsqueda por nombre, que incluye autocompletado para evitar errores.
- **Proyectos de maquetas pendientes:** En esta sección, los asesores de ArquiMentor podrán revisar los proyectos de maquetas que los estudiantes les han solicitado. Aquí, tendrán la oportunidad de ver en detalle cada solicitud, incluyendo la descripción del proyecto, los materiales necesarios y la fecha límite para su finalización. Los asesores tendrán la opción de aceptar o rechazar cada proyecto según su disponibilidad y experiencia. Esta función brinda a los asesores la flexibilidad de seleccionar los proyectos que mejor se adapten a sus habilidades y horarios, permitiéndoles brindar un servicio de alta calidad a los estudiantes de arquitectura.
#### Ambos segmentos

- **Sección de noticias:** Es esta sección, tanto los grupos objetivo podrán explorar las noticias relevantes mediante una barra de búsqueda, en la cual deberán introducir el título de la noticia o términos clave. Las noticias serán seleccionadas en función de las palabras clave proporcionadas o si el título exacto de la noticia de los cursos es ingresado correctamente.

### 4.2.5 Navigation Systems
A continuación, se expondrán los sistemas de navegación diseñados para permitir que nuestros usuarios naveguen a través de las diferentes partes de contenido e información.

Como se mencionó previamente en los sistemas de etiquetado, tenemos cuatro "encabezados" en la Landing Page: Home, About, Services y Contact. Estas secciones están dispuestas como un menú horizontal global en la parte superior de la Landing Page. Esta división en cuatro secciones tiene la intención de evitar que los clientes tengan que desplazarse verticalmente a través de una cantidad considerable de información. Esta disposición facilita la navegación por nuestro contenido. La estrategia es que los usuarios primero revisen la sección Home, donde encontrarán la información más relevante que captará su atención, y luego exploren el resto del menú de izquierda a derecha.

Por otro lado, en el caso del Web Application, contamos con una barra de navegación global lateral-vertical donde se encuentran las principales secciones de la interfaz del usuario. Estas secciones se navegan de la siguiente manera:

- **Home**: Esta sección es la que aparece automáticamente al iniciar sesión y muestra noticias relevantes y opciones específicas para cada grupo objetivo. Los estudiantes tienen opciones como buscar asesores, ver su perfil, explorar noticias relacionadas con los cursos y configurar preferencias.
- **My profile:** Si el usuario desea editar su perfil, solo necesita acceder a esta sección ubicada en la barra de navegación lateral-vertical global.
- **News:** Si el usuario desea ver noticias relacionadas con los cursos, puede ingresar a esta sección que se encuentra en la barra de navegación lateral-vertical global y seleccionar la noticia de su interés.
- **Configuration:** Si el usuario desea ajustar la configuración de la interfaz, puede ingresar a esta sección que se encuentra en la barra de navegación lateral-vertical global y realizar los cambios pertinentes.
- **Learning Resources:** Si el paciente desea revisar sus recursos de aprendizaje, puede acceder a esta sección ubicada en la barra de navegación lateral-vertical global y seleccionar el recurso que estaba buscando.
- **Reviews:** Si el estudiante desea revisar las reseñas de los asesores, solo debe ingresar a esta sección ubicada en la barra de navegación lateral-vertical global.

## 4.3 Landing Page UI Design

Las Landing Pages son herramientas utilizadas con el propósito de convertir a los visitantes en potenciales clientes, empleando estrategias como mensajes impactantes y presentación de información sobre el producto, entre otros enfoques. Por esta razón, se tomó la decisión de aprovechar esta herramienta y crear versiones preliminares tanto para dispositivos móviles como para computadoras.

En la versión móvil, se mantiene el mismo contenido que en la versión para computadoras, pero con un diseño reorganizado para ajustarse al tamaño de los dispositivos móviles. También se incluye un botón que facilita la navegación cómoda a través de la Landing Page en estos dispositivos. Este diseño práctico mejora la usabilidad de las opciones y ofrece una presentación visual amigable para los usuarios.

Por otro lado, en la versión para computadoras, se diseñaron ventanas con opciones específicas que buscan facilitar la comprensión por parte del usuario. Cada opción del sitio web está acompañada de una descripción detallada para evitar confusiones. Además, la barra de navegación se mantiene en una posición fija, lo que garantiza que esté siempre disponible para el usuario y le permite explorar la Landing Page de manera cómoda en todo momento.

## 4.3.1 Landing Page Wireframe

En esta sección, se presentará la estructura fundamental para el diseño del sitio web de nuestra aplicación. Se establecerán bases que brindarán una comprensión más clara del contenido que será exhibido en la plataforma, tanto en la versión para computadoras como en la versión móvil.

La Landing Page debe ser dimensionada de manera adecuada para adaptarse a las distintas pantallas de los dispositivos, asegurando que la información se encuentre centrada en la pantalla para una visualización cómoda por parte del usuario.
Nuestro enfoque es proporcionar información precisa sin generar abrumamiento al usuario. Para lograr esto, ofrecemos una barra de navegación estática que simplifica la exploración a través de la Landing Page, brindando al usuario una experiencia de navegación fluida y accesible.

**Desktop Web**

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149523301002117232/image.png" alt="wireframe-desktop-web-header" >

Diseño del menú de la plataforma web: Se expone la estructura fundamental que contendrá las opciones de mayor relevancia para la comodidad y satisfacción del usuario.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149523358027874314/image.png" alt="wireframe-desktop-web-know-us" >

Opción que muestra datos para conocer mejor la plataforma. Servicios para ambos segmentos:

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149523400910458890/image.png" alt="wireframe-desktop-web-student-services-and-services-for-teachers" >

Sección de contacto y novedades, donde se proporciona información sobre cómo comunicarse y las últimas actualizaciones de la plataforma.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149523422599204874/image.png" alt="us" >

Link: https://www.figma.com/file/ufQ5LuwcCMQsMrdKTsZ0ps/WireFrame-Landing-Page-(Arquisesor)?type=design&node-id=0%3A1&mode=design&t=r66VTlN2RvqSzZDb-1 

**Mobile Web** 

Se visualiza la estructura del menú de inicio diseñado para la comodidad del usuario, presentando el icono que despliega las alternativas de navegación.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149523488118415370/image.png" alt="wireframe-mobile-web-header" >

Se muestra un conjunto de opciones en un bloque que forma parte de la lista de herramientas del servidor, presentando información específica de la aplicación en ciertas situaciones.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149524974185500672/image.png" alt="wireframe-mobile-web-know-us-part-1" width="" height="548">
<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149525001050005524/image.png" alt="wireframe-mobile-web-know-us-part-2" >

Se exhiben los servicios disponibles para ambas audiencias objetivo.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149525616534753300/image.png" alt="services-for-teachers" width="" height="548">
<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149525603121369228/image.png" alt="student-services" height="548" >

Se presenta el último bloque de la aplicación, describiendo el contenido relacionado con la comunicación entre el servicio y el usuario.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149525636629671996/image.png" alt="us" height="548" >
<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149525653297827981/image.png" alt="contact-us" width="370" height="420" >

Link: https://www.figma.com/file/ufQ5LuwcCMQsMrdKTsZ0ps/WireFrame-Landing-Page-(Arquisesor)?type=design&node-id=0%3A1&mode=design&t=r66VTlN2RvqSzZDb-1 

### 4.3.2 Landing Page Mock-up
Se muestra una vista inicial que representa la estructura fundamental de nuestro sitio web, describiendo su contenido en detalle, aplicando los colores correspondientes de acuerdo con nuestras directrices de estilo e incorporando imágenes pertinentes para mejorar la comprensión de las ideas que deseamos comunicar al usuario de manera más efectiva.

**Desktop Web Browser**

Se presenta la variante del menú de la plataforma, describiendo de manera minuciosa los contenidos fundamentales y las opciones que brindan al usuario un mayor entendimiento de nuestro sistema.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149527787456172144/image.png" alt="desktop-web-browser-header">

Cuando se selecciona la alternativa "Know Us" en la barra de herramientas del menú principal, se despliegan tres alternativas para que el usuario pueda optar por aquella que mejor se ajuste a sus necesidades y así obtener información detallada sobre nuestro proyecto.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149527810629718117/image.png" alt="desktop-web-browser-know us">

Se presenta los servicios que posee el usuario a lo largo del consumo del software.

**Usuario: Estudiantes**


<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149527834344296568/image.png" alt="desktop-web-browser-student-services">

**Usuario: Asesores**

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149527849041141770/image.png" alt="desktop-web-browser-services-for-teachers">

En el último segmento de la plataforma, se exhibe una breve descripción de contacto, junto con la alternativa de comunicarse con nosotros para compartir sus preguntas y requerimientos.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149527871770079383/image.png" alt="desktop-web-browser-us">

Link: https://www.figma.com/file/Ms6aOfFa9ov67GDl7Un5So/Mockup-Landing-Page-(Arquisesor)?type=design&node-id=0%3A1&mode=design&t=inLwmbPWyN4MqUTC-1

**Mobile Web Browser**

Se muestra la sección de menú principal en la versión móvil de la Landing Page, con las opciones más relevantes para nuestra audiencia objetivo y un resumen conciso de nuestro software.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149528833091969065/image.png" alt="mobile-web-browser-header">

Se presenta la sección de "Know Us", que proporciona detalles sobre el proceso de nuestros servicios según el profesional de salud designado, responde consultas sobre el funcionamiento del sistema, comparte información sobre nuestra misión y brinda detalles de nuestras consultas.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149528858266189825/image.png" alt="mobile-web-browser-know-us">

Se presenta el conjunto de servicios disponibles para los estudiantes y los profesionales interesados en nuestra aplicación de software.

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149528881544568862/image.png" alt="mobile-web-browser-service">

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149528904785199144/image.png" alt="mobile-web-browser-student-services">

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149528927337975890/image.png" alt="mobile-web-browser-services-for-teachers" width="350">

Se muestra como último bloque de la plataforma, un resumen breve de información de contacto, así como la posibilidad de comunicarse con nosotros y compartir cualquier pregunta o necesidad que puedan tener.


<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149530985420042300/image.png" alt="mobile-web-browser-us">
<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149531000670519297/image.png" alt="mobile-web-browser-contact-us" height="540">

Link: https://www.figma.com/file/Ms6aOfFa9ov67GDl7Un5So/Mockup-Landing-Page-(Arquisesor)?type=design&node-id=0%3A1&mode=design&t=inLwmbPWyN4MqUTC-1 
## 4.4 
## 4.5 
## 4.6 
## 4.7 
## 4.8 Database Design
### 4.8.1 Database Diagram
<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149533834908540978/image.png" alt="database-diagram">

## Entidades de la base de datos:

### Tabla: Appointment (Cita)

Esta entidad representa una cita entre un estudiante y un mentor de arquitectura.

**Atributos:**

- **Id: Identificador único de la cita.**

- **StudentId: Identificador del estudiante que solicita la cita.**

- **MentorId: Identificador del mentor o asesor de arquitectura asignado a la cita.**

- **Date: Fecha de la cita.**

- **Time: Hora de la cita.**

- **Description: Descripción detallada de la cita.**

- **MaterialId: Identificador del material asociado a la cita (si aplica).**

- **PaymentId: Identificador del detalle de pago asociado a la cita.**

### Tabla: Materials (Materiales)

Esta entidad almacena información sobre los materiales utilizados en proyectos de arquitectura.

**Atributos:**

- **Id: Identificador único del material.**

- **Name: Nombre o título del material.**

- **Price: Precio del material.**

- **Description: Descripción detallada del material.**


### Tabla: Mentor (Mentor o Asesor)

Esta entidad representa a los mentores o asesores en arquitectura disponibles para brindar orientación a los estudiantes.

**Atributos:**

- **Id: Identificador único del mentor o asesor.**

- **FirstName: Nombre del mentor.**

- **LastName: Apellido del mentor.**

- **Specialty: Especialidad o área de expertise del mentor.**

### Tabla: Payment (Pago)

Esta entidad registra información sobre los pagos realizados en relación con las citas de asesoría.

**Atributos:**

- **Id: Identificador único del registro de pago.**

- **PaymentDetailId: Identificador del detalle de pago.**

- **AppointmentId: Identificador de la cita asociada al pago.**

### Tabla: PaymentDetail (Detalle de Pago)

Esta entidad almacena detalles específicos sobre los pagos relacionados con los servicios de asesoría.

**Atributos:**

- **Id: Identificador único del detalle de pago.**

- **Subtotal: Monto subtotal del pago.**

- **Discount: Descuento aplicado al pago.**

- **RetentionPercentage: Porcentaje de retención en el pago.**

- **RetentionAmount: Monto retenido.**

- **MaterialId: Identificador del material relacionado con el pago.**

### Tabla: ProjectRecord (Registro de Proyecto)

Esta entidad registra información sobre proyectos o trabajos realizados por estudiantes de arquitectura.

**Atributos:**

- **Id: Identificador único del registro de proyecto.**

- **Date: Fecha del registro.**

- **Time: Hora del registro.**

- **Description: Descripción detallada del proyecto o trabajo.**

- **StudentArchitectureId: Identificador del estudiante de arquitectura relacionado con el proyecto.**

### Tabla: Score (Puntaje)

Esta entidad registra puntajes otorgados en el contexto de las citas de asesoría.

**Atributos:**

- **Id: Identificador único del puntaje.**

- **Score: Puntuación otorgada.**

- **Comment: Comentario relacionado con el puntaje.**

- **Date: Fecha del puntaje.**

- **AppointmentId: Identificador de la cita asociada al puntaje.**

### Tabla: Service (Servicio)

Esta entidad almacena información sobre los servicios de asesoría disponibles.

**Atributos:**
- **Id: Identificador único del servicio.**

- **Name: Nombre o título del servicio.**

- **Description: Descripción del servicio.**

- **Price: Precio del servicio.**

### Tabla: StudentArchitecture (Estudiante de Arquitectura)

Esta entidad representa a los estudiantes de arquitectura.

**Atributos:**
- **Id: Identificador único del estudiante de arquitectura.**

- **FirstName: Nombre del estudiante.**

- **LastName: Apellido del estudiante.**

- **Age: Edad del estudiante.**

