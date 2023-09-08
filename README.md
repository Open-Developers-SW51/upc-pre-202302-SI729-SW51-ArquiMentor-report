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
