# Universidad Peruana de Ciencias Aplicadas.
### Ingeniería de Software.
### Desarrollo de Aplicaciones Open Source.
### SW51

#### Angel Augusto Velasquez Nuñez

## Final Project REPORT

### StartUp Name : ArquiMentor

### Team Members : Open Developers

|            Members             |    User    |
|:------------------------------:|:----------:|
| López Huarcaya, Leonardo Paul  |  u202124304   |
|Kurt Puican Salas| u202016643 |
|  Luyo Ramirez, Rafael Arturo   | u202115348 |
| Ramirez Ortega, Diego Miguel| u202123548 |
| Juliana Alexandra Yauricasa Seguil| u20201B782 |

#### Ciclo 2023 - 02

<br><br>

## Registros de versiones del Informe

| Version |  Fecha   | Autor                                                                                      | Descripción de la modificación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|:-------:|:--------:|:-------------------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|    1    | 02/09/23 | Leonardo Lopez</br>Kurt Puican </br>Rafael Luyo</br>Diego Ramirez</br>Juliana Yauricasa    | Culminación de los siguientes capítulos:</br></br>Capítulo I: Introducción</br>Se presenta el proyecto, comenzando con una descripción detallada de la startup y sus miembros fundadores. Se exploran los desafíos y problemas actuales que enfrenta la startup, empleando un enfoque de Lean UX para identificar problemas, Assumptions e Hypothesis Statements . Además, se delinean los segmentos objetivo para la solución propuesta.</br></br>Capítulo II: As-Is Software Solution Requirements Elicitation & Analysis</br>Se realiza un análisis del entorno competitivo de la startup, investigando estrategias y tácticas frente a los competidores. Se llevan a cabo entrevistas con el fin de obtener información esencial de los usuarios. Varias técnicas, como el diseño de entrevistas, el registro y análisis de entrevistas, y la identificación de necesidades a través de la creación de User Personas, User Task Matrix, User Journey Mapping y Empathy Mapping, son empleadas para este propósito.</br></br>Capítulo III: As-Is Software Solution Requirements Specification</br>Se especifican los requisitos del software. Se crean los To-Be Scenario Mapping y las User Stories. Además, se utiliza el Impact Mapping para visualizar cómo las funcionalidades afectan a los objetivos del proyecto y se establece un Product Backlog.</br></br>Capítulo IV: Product Design</br>Se diseña el producto, incluyendo pautas de estilo, arquitectura de la información, diseño de la página de aterrizaje, UX/UI de aplicaciones web, prototipado, arquitectura de software, diseño orientado a objetos y diseño de base de datos.</br></br>Capítulo V: Product Implementation, Validation & Deployment</br>Se desarrolla la implementación, validación y despliegue del producto, incluyendo gestión de configuración, implementación de páginas y aplicaciones, validación a través de entrevistas y pruebas, y finalmente, el despliegue del software. |
|    2    | 26/09/23 | Leonardo Lopez</br>Kurt Puican </br>Rafael Luyo</br>Diego Ramirez</br>Juliana Yauricasa    | Mejora continua: Corrección de los siguientes capítulos: </br>  Capítulo III: As-Is Software Solution Requirements </br> Agregar user stories para la landing page y las technical stories, priorizar las user stories de acuerdo al core del negocio, mejora del impact mapping.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
<br>

# Project Report Collaboration Insights

URL del repositorio para el Project Report: https://github.com/Open-Developers-SW51/upc-pre-202302-SI729-SW51-ArquiMentor-report

La elaboración del proyecto se realizó mediante el github en formato Markdown usando la metodología GitFlow.

<img src="https://cdn.discordapp.com/attachments/1149549726748921942/1156263561753014342/image.png?ex=651455db&is=6513045b&hm=56dc6a2bd4255d1cc425ea3f91facc1eda01265ace660386407bc0c8192d0903&">

Para los commits se utilizo Conventional Commits.

<img src="https://cdn.discordapp.com/attachments/1149549726748921942/1156264608852607037/image.png?ex=651456d5&is=65130555&hm=0127e1211c246f901d004f67b4a3e23c3670cd85519fde38240e4e9b0160d9a1&">
<img src="https://cdn.discordapp.com/attachments/1149549726748921942/1156269150159781938/image.png?ex=65145b0f&is=6513098f&hm=c7eb7e66dba9cfe0078c690abf740ee57f168425ba27ddd40177fc285325eb61&">

Los colaboradores en el proyecto se muestra en la siguiente imagen, con las cantidades respectivas de commits.

<img src="https://cdn.discordapp.com/attachments/1149549726748921942/1156268138871128194/image.png?ex=65145a1e&is=6513089e&hm=4f3b87121aca23e7d234fcd2cb6e596b187a59f71d017e4b96c6d5a55f8d471a&">

<br><br>
# Contenido
## Tabla de contenidos

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

En Ingeniería de Software el logro de curso contribuye a alcanzar el:

**ABET - EAC - Student Outcome 3:**

**Criterio:** _Capacidad de comunicarse efectivamente con un rango de audiencias._

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 3.

| Criterio específico                                                                                                                                                                   | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Conclusiones                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería.    | López Huarcaya, Leonardo Paul </br>*TB1* </br> Entrevista a un estudiante de la carrerra de arquitectura para la elaboracion del proyecto.<br> Exposición del apartado Web Applications UX/UI Design.<br>*TP*<br> Corrección de la entrevista al estudiante de arquitectura.<br>Recoleccion de información con algunos estudiantes de arquitectura.<br><br>Kurt Puican </br>*TB1* </br> ... <br>*TP*</br>...<br>Rafael Luyo</br>*TB1* </br> Entrevista a un estudiante de la carrerra de arquitectura para la elaboracion del proyecto.<br> Exposición del apartado Web Landing Page UI Design, Database, Landing Page Deployment.<br>*TP*<br> Corrección de la entrevista al estudiante de arquitectura.</br> <br>Diego Ramirez</br></br>Juliana Yauricasa</br>*TB1*</br>Entrevista a un estudiante de arquitectura.</br>Exposición de la sección de especificación de requisitos.</br>*TP*</br>Corrección de la entrevista del estudiante de arquitectura. | 	Las entrevistas realizadas por todo el equipo nos ayudaron a poder plantear nuevas necesidades y elabaroar las funcionalidades del sitio web.<br><br>Las correcciones establecidas fueron de gran ayuda para mejorar nuestra vision de negocio, inclusive modificando algunas funcionalidades para la mejora del proyecto.</br> <br> Hablar con claridad y objetividad sobre nuestras ideas y logros fue clave en nuestro proyecto de ingeniería. Cuando tuvimos reuniones y presentaciones, nos ayudó a explicar nuestras ideas de manera directa a personas con diferentes conocimientos y roles. Esta comunicación fluida nos permitió obtener consejos valiosos y asegurarnos de que todos estuvieran en la misma página, lo que fue fundamental para el éxito de nuestro proyecto</br>                                                                                                                                                                           |
| Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. | López Huarcaya, Leonardo Paul </br>*TB1* </br> Elaboración del Web Aplications UX/UI Design.<br>Elaboración del Sprint 1.<br>Elaboración del Software Configuration Management.<br>*TP*<br> Corrección de mis partes elaboradas de la primera entrega.<br>Elaboración del sprint 2.<br><br>Kurt Puican </br>Rafael Luyo</br>*TB1*</br>Creación de Landing Page Ui Design, Database.</br>*TP*</br>Corrección de Database y Landing Page.<br>Mejora de redaccion de entrevista</br><br>Diego Ramirez</br></br>Juliana Yauricasa</br>*TB1*</br>Creación de las user stories y la especificación de requisitos.</br>*TP*</br>Corrección de la especificación de requisitos, priorización del Product Backlog y los criterios de aceptación.<br>Elaboración del Sprint 2                                                                                                                                                                                          | La elaboración del informe nos ayudo a idcar y organizar nuestro proyecto, tanto como las funcionalidades, los requisitos, las problematicas y diseños. Todo esto necesario para poner en marcha la elaboración del Web Aplications.<br><br>Las correcciones que se realizaron en el proyecto ayudaron a crear nuevas funcionalidades para el Web Applications. <br><br> El desarrollo del sprint facilita la organización para la creación del Sitio Web.</br><br>Expresar nuestras ideas y resultados por escrito de manera clara y objetiva fue esencial en nuestro proyecto de ingeniería. Cuando escribimos informes y documentos, nos ayudó a organizar la información de manera ordenada, lo que permitió que personas con diferentes antecedentes y roles la entendieran fácilmente. Esta comunicación por escrito precisa y objetiva fue fundamental para guiar nuestro trabajo y garantizar que todos estuvieran en la misma sintonía en nuestro equipo</br> |
<br><br>

# Capitulo 1: Introducción

A continuación, procederemos a informar sobre a lo que se dedica nuestra empresa “ArquiMentor”, así como la presentación del equipo de desarrollo del producto, software presentado anteriormente, “OpenDevelopers”

## 1.1 Startup Profile

### 1.1.1 Descripción de la Startup

 Como todos saben arquitectura es una de las carreras mas densas que se pueden llevar actualmente debido a los cursos y sobre todo a los trabajos que se tienen que realizar a lo largo de toda la carrera siendo las maquetas lo que mas destaca cuando se habla de este tema, debido a esto muchos de los estudiantes se estresan bastante ya que no saben como poder realizar estas maquetas o simplemente no pueden llegar a entender las clases que se dictan en la carrera haciendo que muchos de estos dejen la carrera y se estresen por este tema.
Es por eso que creamos Arquimentor una plataforma donde los estudiantes de arquitectura pueden pedir asesoramiento en diversas áreas de la carrera de arquitectura para facilitarles la culminación de esta. Los estudiantes pueden solicitar asesoría con los cursos donde se les dificulta como también recibir un asesoramiento en la creación de las maquetas por parte de gente que sabe del tema para así poder apoyar a los estudiantes.


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
      <img src="https://cdn.discordapp.com/attachments/1146639921830973515/1149466156269309983/image.png" alt="" width="60" height="50" style="border-radius: 25%;">
    </td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">López Huarcaya, Leonardo Paul</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Soy Leonardo Paul Lopez Huarcaya y estoy estudiando la carrera de Ingeniería de Software. Cuento con el conocimiento de los lenguajes HTML,java, C++, C#, pentesting y MySQL. Contando de igual manera con conocimientos y experiencia breve en arquitectura de software.</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">u202124304</td>
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
      <img src="https://cdn.discordapp.com/attachments/960601728330395718/1149629842468388914/image.png" alt="##" width="50" height="50" style="border-radius: 25%;">
    </td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Ramirez Ortega, Diego Miguel</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Mi nombre es Diego Ramirez, tengo 19 años y estoy en el quinto ciclo de la carrera de Ingeniería de Software. Tengo conocimiento en C++, python y edición de vídeo. Estoy comprometido a completar las tareas que se me asignen a tiempo y apoyar en lo que pueda en el proyecto.</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">u202123548</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://ibb.co/Df0H7ZW" alt="##" width="50" height="50" style="border-radius: 25%;">
    </td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Juliana Alexandra Yauricasa Seguil</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Mi nombre es Juliana estoy en la carrera de ingeniería de software, tengo conocimiento del lenguaje de programación C++ y he aprendido lo básico de HTML, tengo conocimiento de desarrollo en sitios web. </td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">u20201B782</td>
  </tr>
</table>

## 1.2 Solution Profile

En este punto del informe, daremos una explicación de nuestro producto de software, así como también la forma de generar ingresos.
 
**Product Name**
 
Hemos optado por el nombre de “ArquiMentor” hemos usado el nombre en inglés para generar más atractivo en los usuarios “ArquiMentor” se conforma por dos palabras en inglés que hacen referencia a lo que hace el software ‘Arqui’ quiere decir estudio haciendo referencia a los estudiantes que necesitan apoyo en los estudios que requieran y ‘Mentor’ que quiere decir Mentor que hace referencia a los asesores que ayudarán a los alumnos en los estudios.
 
**Product Description**

En esta web se les da a los usuarios la facilidad de poder encontrar mentores o profesores de diferentes áreas en la pagina podrán buscar tutores según el área de estudio que los estudiantes estén buscando podrán ver la valoración del tutor el costo que tiene y si es que se convence poder agendar una sesión de estudio. Los tutores por otra parte tienen la facilidad de poder subir sus datos para que los alumnos puedan encontrarlos y puedan elegirlos para esto tienen la facilidad de subir su CV y la experiencia que han tenido a lo largo de su carrera, como también la facilidad de poder incluir los datos para poder contactarlo.
 
**Monetization**

En nuestro servicio nosotros actuamos como un intermediario entre los alumnos y los tutores y al momento de que se genere una clase nosotros no llevamos una parte del pago de los asesoramientos.
 

 
## 1.2.1 Antecedentes y problemática del producto
Descripción de la problemática
 
Este software se enfoca en el sector educativo, ya que en los tiempos actuales donde muchas personas necesitan un pequeño asesoramiento para apoyar a los estudiantes para que se nivelen en los estudios “ArquiMentor” sirve de intermediario para poder encontrar gente con experiencia en los diversos ámbitos que se requieran cubrir por los alumnos.
 
Objetivos
Este software tiene el principal objetivo de apoyar al estudio de los estudiantes por medio de un intermediario con tutores que sepan de los temas que los alumnos quieren aprender, también buscamos ser una gran alternativa al momento en el que un usuario quiera buscar alguien que le enseñe temas que este no comprenda.
 
Restricciones
Una principal restricción que delimita el alcance del proyecto es que el equipo desarrollador es nuevo en estas tendencias o técnicas a aplicar para lanzar nuestra aplicación. Por ello, es que puede ser una restricción de alcanzar el mejor escenario. Sin embargo, el equipo pondrá de su parte para lograr alcanzar el nivel deseable de cada entregable.
 
Antecedentes
Como ya se ha mencionado a lo largo del informe nuestro producto tienen la capacidad de conectar tutores con estudiantes, sin embargo, hay algunos servicios que tienen características similares con nuestro producto es por eso hemos investigado a posibles competidores para poder mejorar nuestro producto.
TutorFinder:
Descripción: TutorFinder es una plataforma en línea que conecta a estudiantes con profesores en una amplia variedad de materias y niveles. Los usuarios pueden filtrar por ubicación, materia, nivel educativo y experiencia del profesor para encontrar el tutor perfecto.
 EduTutores:
Descripción: EduTutores es una comunidad en línea donde estudiantes pueden encontrar profesores para recibir ayuda en asignaturas específicas. Los profesores pueden establecer sus tarifas y horarios, y los estudiantes pueden reservar sesiones según su conveniencia.
 
 
 
 
 
Herramienta de 5W y 2H
o What - ¿Cuál es el problema?
▪ El problema identificado es la cantidad de estudiantes que necesitan asesoramiento en diversos temas de aprendizaje tratados en sus respectivas universidades y/o institutos ya que no se pudo llegar a comprender los temas tratados en clase
 
o When - ¿Cuándo sucede el problema?
▪ Cuando es un estudiante no llega a comprender alguna clase y se encuentre perdido ya sea porque el tema resulto ser demasiado difícil como también porque no se llegó a prestar la suficiente atención, como también algún trabajo que no sepa cómo realizar así como también cuando algún estudiante requiera un reforzamiento en los temas tratados en clase
 
o Where - ¿Dónde surge el problema?
▪ El problema surge en distintas áreas educativas ya sean universidades, institutos o instituciones privadas
 
o Who - ¿Quiénes son afectados por el problema?
▪ Los principales afectados son los jóvenes estudiantes que están cursando su carrera
 
o Why - ¿Cuál es la causa del problema?
▪ La causa del problema es principalmente se puede deber de diversos factores como que el tema resulto ser demasiado difícil no llegaron a explicar de una buena manera el tema abordado como también estuvieron distraídos en clase, o que el trabajo pedido resulta ser demasiado difícil o laborioso para el estudiante.
 
o How - ¿Cómo se llevan a cabo los hechos?
▪ Cuando un estudiante requiera asesoramiento en los temas que este prefiere se dirige a la página web www.ArquiMentor.com para poder conseguir algún profesional que le pueda dar el asesoramiento necesario para poder nivelarse y estar a la par que sus otros compañeros como también de lo esperado por la institución educativa, asi como también cumplir con los trabajos en la fecha estimada.
 
 
o How much - ¿Cuál es la magnitud del problema?
▪ La pandemia de COVID-19 ha llevado a un aumento en la educación a distancia y en línea, lo que puede hacer que algunos estudiantes se sientan más aislados y necesitan más apoyo en línea. Algunos estudiantes pueden tener dificultades particulares en ciertas materias o temas, lo que los lleva a buscar ayuda adicional tanto con sus trabajos como estudios ya que no es lo mismo aprender en presencial como en línea. Otro de los problemas es que varios alumnos se distraen en clases por lo que tampoco pueden entender las clases.

## 1.2.2 Lean Ux Process
### 1.2.2.1 Lean UX Problem Statement 

Problem Statement
En el panorama educativo actual, los estudiantes a menudo se enfrentan a desafíos al buscar profesores adecuados para recibir tutoría personalizada. A medida que la demanda de apoyo educativo fuera del aula sigue creciendo, surge la necesidad de una solución eficiente y confiable que conecte a los estudiantes con profesores calificados y compatibles. La falta de una plataforma integral y centralizada dificulta que los estudiantes encuentren profesores que se ajusten a sus necesidades y preferencias de aprendizaje.

Las búsquedas tradicionales de profesores a menudo implican una inversión significativa de tiempo y recursos, con resultados inciertos. Los estudiantes pueden encontrarse con problemas como la falta de información suficiente sobre los antecedentes y la experiencia de los profesores, la dificultad para coordinar horarios y ubicaciones, y la incertidumbre sobre la calidad de la enseñanza ofrecida. Además, el proceso de búsqueda y selección puede ser abrumador, especialmente para aquellos que buscan profesores en áreas específicas o con habilidades particulares.

La falta de una plataforma eficiente y confiable para conectar a estudiantes con profesores también puede afectar negativamente el rendimiento académico de los estudiantes. La ausencia de un acceso sencillo a tutores y mentores de calidad puede resultar en dificultades persistentes en el aprendizaje y una menor confianza en las propias habilidades académicas.
Por lo tanto ¿Como podemos hacer para que los estudiantes reciban una asesoria de los profesores de una manera facil tanto para los profesores como los alumnos para poder generar una clase?

### 1.2.2.2 Lean UX Assumptions

**Business Outcomes**

·         Generar una plataforma intuitiva, eficaz y óptima que genere ingresos a partir de la contratación de profesionales de diversos sectores educativos dispuestos a brindar sus servicios al estudiante

·         Causar interés en las empresas audiovisuales afiliadas de nuestra competencia, debido a nuestro alcance en los usuarios y su favoritismo, para ampliar nuestro alcance en publicidad, aumento de ingresos por el crecimiento de ventas, entre otros factores para el beneficio de la plataforma.

·         Producir una rentabilidad económica por los servicios de los profesionales educativos, con precios económicos y variables dependiendo de la necesidad del usuario, en el servicio de consultas vía sitio web o por un profesional, y la publicidad de nuestra plataforma con el fin de generar mayores ingresos que costos.

·         Sentar una tasa de retención por determinado periodo, para verificar si nuestros usuarios siguen utilizando nuestro servicio, con campañas de marketing, servicio que cumple sus necesidades con funciones de la plataforma, y si no se cumple, identificar cuáles serían las razones del abandono del servicio.

**Users**

·         Publico joven estudiantes de universidad o de instituto

·         Profesionales que sepan de los temas que los estudiantes quieran aprender
 
**User Outcomes**
 
**Faeatures**
1. **Creo que mis usuarios necesitan,** empezando por los estudiantes, recibir rápidamente variedad de profesores que puedan darle un asesoramiento para generar una clase. Por parte de los profesores tener la posibilidad de poner sus horarios y precios y las materias que dominan para poder ser escogidos por los alumnos.
2. **Estas necesidades se pueden resolver con** una plataforma que permita contactar a un profesional para que realice una asesoría  en nuestra plataforma de manera eficaz. Por otro lado, que le permita al estudiante coordinar la hora y los temas a desarrollar en la asesoria 
3. **Mis clientes iniciales son (o serán)** los estudiantes que necesiten o quieran una asesoria por un profesional  y, los profesionales que den estas asesorias. 
4. **El valor #1 que un cliente quiere de mi servicio es,** empezando por los estudiantes, recibir asesorías de manera cómoda, rápida y personalizada. Por otro lado, los profesionales desean conseguir asesorias para poder conseguir ingresos extra.
5. **El cliente también puede obtener beneficios adicionales,** Empezando por los estudiantes, podrían querer tener la oportunidad de calificar el servicio de los asesores por medio de un sistema de estrellas y comentarios, por otro lado los profesores quisieran tener la oportunidad de si es que son calificados de buena manera tener la posibilidad de ser encontrados más fácilmente en el buscador 
6. **Voy a adquirir la mayoría** de mis clientes a través de marketing en los medios de comunicación más frecuentados como Facebook, Instagram o entre otros; con la publicación de casos de éxito de los estudiantes que utilizan nuestra plataforma. Asimismo, demostrando las funcionalidades de las asesorías
7. **Haremos dinero a través** de la una comisión de las clases que se den en nuestra plataforma, ya que nosotros actuamos como un intermediario nosotros nos llevaremos un pequeño porcentaje de cada clase que se de en nuestra plataforma

---
1. **¿Quién es el usuario?**

Nuestros usuarios son aquellas personas que quieras mejorar o aprender diversos temas que se enseñan en los diversos sistemas educativos asi como tambien personas que proporcionen estas asesorías

2. **¿Dónde encaja nuestro producto en su trabajo o vida?**

En este caso encaja en cualquier momento de la vida de nuestros usuarios ya que pueden requerir los servicios en cualquier momento que estos lo vean necesario.

3. **¿Cómo y cuándo es usado nuestro producto?**

Para los estudiantes a través de nuestra página web a través de la cual van a contactar y a coordinar todo lo relacionado con las asesorías, y estas pueden ser en cualquier momento ya que al encontrar un profesor que sea del agrado del estudiante éste le mandará un mensaje al asesor con lo cual este solo tendrá que esperar a que el asesor le proporcione una respuesta y puedan coordinar de una mejor manera las asesorías.

 4. **¿Qué problema tendría nuestro producto y cómo se pueden resolver?**

Nuestro producto está desarrollado en plataformas digitales, por lo que, al ser personas de tercera edad la mayoría de profesores, se pueden generar complicaciones al momento de entender el correcto funcionamiento de ella. 

5. **¿Qué características son importantes?**

 Debe ser intuitiva, las opciones que tendrá la plataforma deben ser específicas y prácticas para que el usuario no tenga complicaciones en su uso. A su vez, el tiempo de respuesta en cuanto a la atención al cliente. 

 6. **¿Cómo debe verse nuestro servicio y cómo debe comportarse?**

www.Arquimentor.com  Nuestro producto debe verse práctico, moderno y con contrastes de colores suaves; todo esto con la finalidad de hacer más satisfactoria la experiencia de usuario. Asimismo, debe comportarse como una interfaz fluida y con un manejo eficaz de la información.

### 1.2.2.3 Lean UX HYpothesis Statements

1st Hypothesis Statement

**Creemos que** el uso de nuestra plataforma facilitará la comunicación entre el usuario y el asesor y asi desarrollar las clases 

**Sabremos que** hemos tenido éxito,

**Cuando** veamos que el 70% de los usuarios están satisfechos con la prontitud que se contacta a un asesor a través de sus reseñas positivas en nuestra plataforma.
 
2nd Hypothesis Statement

**Creemos que** publicar comentarios sobre experiencias con las asesorias para que otros usuarios puedan animarse a realizar una asesoria

**Sabremos que** hemos tenido éxito,

**Cuando** veamos que un 60% entrar a la plataforma y conseguir una asesoria 
 
3rd Hypothesis Statement

 **Creemos que** publicar los asesores mejor valorados para demostrar que nuestro servicio contrata a profesionales para apoyar a los alumnos.

**Sabremos que** hemos tenido éxito,

**Cuando** veamos que un 50% de nuestros usuarios utilizan las recomendacione los asesores para saber a quienes llamar

### 1.2.2.4 Lean UX Canvas

<table>
  <tr>
  <th style="border:1px solid #dddddd; padding: 8px; text-align:center;" colspan="2">Título: ArquiMentor</th>
    <th style="border:1px solid #dddddd; padding: 8px; text-align:center;">Fecha: 27/08/2023</th>
  </tr>
  <tr>
   <tr>
  <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Business problem

Hemos identificado una problemática en este proceso los estudiantes, necesitan un apoyo extra para poder entender los cursos como también realizar los trabajos que se piden a lo largo de varios cursos en toda la carrera. Y a su vez asesores quieren poder ganar algo de dinero extra prestando sus servicios como asesores de estos alumnos que requieran una asesoría con un curso o trabajo
</td>
  <td style="border:1px solid #dddddd; padding: 8px; text-align:center;" rowspan="2">Solutions

​​Plataforma que permita conectar a los asesores con los estudiantes para poder coordinar una asesoría.

Poder encontrar profesores de acuerdo a las necesidades de los estudiantes 
</td>
  <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Business Outcomes

Generar una plataforma intuitiva que genere ingresos a partir de comisiones de acuerdo a cada asesoría llevada a cabo en la plataforma.
Establecer nuestra posición en el mercado a través de resultados efectivos de los estudiantes generando confianza por nuestro servicio
 Causar interés en las empresas audiovisuales afiliadas de nuestra competencia, demostrando que los usuarios nos prefieren a nosotros, para así ampliar nuestro alcance en publicidad, aumento de ingresos por el crecimiento de ventas, entre varios otros factores en beneficio de la plataforma
</td>
</tr>

  </tr>
  <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Users 

Estudiantes que necesiten un asesoramiento en trabajos y cursos de la carrera

Profesionales en los cursos para darles asesoría
</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">User Outcomes & Benefits

Poder conseguir un asesor del curso que quieras de una manera rápida y sencilla.
Identificar el proceso de mejora en los usuarios que usen la plataforma
Producir una mejora económica en los asesores que usen nuestra plataforma 
</td>
  
  </tr>
  <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Hypotheses

Creemos que el uso de nuestra plataforma facilita la búsqueda de asesores para los estudiantes

sabremos que hemos tenido éxito cuando veamos que el 70% de los estudiantes está conforme con los resultados de las asesorías 

Creemos que la plataforma ayudará a los estudiantes con sus estudios 

Sabremos que hemos tenido éxito cuando veamos un 60% de de nuestros usuarios escribiendo comentarios en nuestra plataforma contando su experiencia que fue favorable
</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">What is the most important thing we need to learn first?

Conocer las estadísticas de los estudiantes que requieran de una asesoría 

Conocer las estadísticas de los asesores que quieran generar ingresos dando asesorías 
</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">What is the least amount of work we need to do to learn the next most important thing?

Entrevistas/ reuniones con nuestros clientes.

ver la conformidad de los usuarios al realizar las asesorías

inspeccionar la actividad de la plataforma para identificar errores en ella para poder solucionarlos
</td>
  </tr>
    
</table>

## Segmento Objetivo
Nuestra plataforma Arquimentor se dirige a un amplio segmento de estudiantes que buscan asesoramiento educativo en diversas áreas para mejorar su rendimiento académico y alcanzar sus objetivos educativos como pedir asesoramiento para la realización de trabajos como maquetas. Este segmento incluye:

**Estudiantes en Diferentes Niveles Educativos:**
Nuestro público objetivo abarca estudiantes de todos los niveles educativos, desde secundaria hasta universidad. Esto incluye estudiantes universitarios que buscan destacar en sus estudios, estudiantes de secundaria que se preparan para exámenes cruciales, y aquellos que buscan especialización en campos particulares.

**Profesionales Jóvenes en Búsqueda de Desarrollo Continuo:**

También nos dirigimos a profesionales jóvenes que desean mejorar sus habilidades y conocimientos para avanzar en sus carreras. Esta categoría incluye a aquellos que buscan adquirir nuevas habilidades relevantes para su campo laboral.

**Perfil de Profesores en ArquiMentor:**

Nuestra comunidad de profesores en ArquiMentor está formada por profesionales altamente calificados y comprometidos con el éxito educativo de los estudiantes. El perfil de nuestros profesores se caracteriza por:

Cada profesor en nuestra plataforma tiene una amplia experiencia en su campo académico o profesional. Muchos de ellos poseen títulos avanzados y han demostrado un historial sólido de éxito en la enseñanza y/o en su industria.

Flexibilidad y Personalización:
Nuestros profesores comprenden las diversas necesidades de los estudiantes y pueden adaptar su enfoque de enseñanza según el estilo de aprendizaje y los objetivos individuales de cada estudiante.

# 2. Requirements Elicitation & Analisis
## 2.1 Competidores 
## 2.1.1 Analisis Competitivo 
<table style="border-collapse: collapse; width: 100%;"> 
<tr>
  <th style="border:1px solid #dddddd; padding: 8px; text-align:center;" colspan="4">Competitive Analysis Landscape</th>
</tr>

  <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;" rowspan="2">¿por que hacer este análisis?</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;" colspan="3">¿Cómo identificar a nuestros principales competidores?
  </tr>
  <tr>
  <td colspan="3" style="border:1px solid #dddddd; padding: 8px; text-align:center;">Con este análisis, podemos identificar el FODA, es decir, las fortalezas, 
oportunidades, debilidades y amenazas de nuestros competidores. 
Asimismo, se evalúa su participación en el mercado y qué estrategias se 
pueden desarrollar para que nuestra aplicación surja en el mercado laboral. 
Pero ¿Cómo identificamos a nuestros principales competidores?, Debemos 
estudiar el mercado e identificar las aplicaciones más usadas por los 
contratantes del servicio de asesorias. Así se concluyó 
que los principales competidores son:
</td>

  </tr>
  <tr >
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Imagenes de Competidores</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;"><img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149393830894903296/image.png" alt="" width="" height="" />
</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;"><img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149393803376066651/image.png" alt="" width="" height="" /></td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;"><img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149393776276668496/image.png" alt="" width="" height="" /></td>
  </tr>
    <tr >
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Overview</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Tutor.com es una plataforma de tutoría en línea ampliamente utilizada que ofrece a los estudiantes la oportunidad de obtener ayuda con una variedad de materias académicas. Los estudiantes pueden conectarse con tutores en tiempo real a través de chat en vivo y pizarra interactiva, lo que les permite hacer preguntas, resolver problemas y recibir explicaciones en tiempo real. El servicio está disponible las 24 horas del día, los 7 días de la semana, por lo que los estudiantes pueden acceder a la ayuda que necesitan en cualquier momento. Tutor.com también ofrece recursos de aprendizaje, como ejercicios de práctica y lecciones pregrabadas.</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Chegg Tutors es una plataforma que conecta a estudiantes con tutores en línea en una amplia variedad de materias, desde matemáticas y ciencias hasta escritura y humanidades. Los estudiantes pueden buscar y seleccionar a un tutor basándose en sus necesidades específicas y programar sesiones de tutoría en línea a través de videoconferencia. Los tutores en Chegg Tutors son expertos en sus respectivos campos y pueden proporcionar explicaciones claras y ayudar a los estudiantes a resolver problemas académicos.</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Wyzant es un servicio de tutoría en línea y en persona que permite a los estudiantes encontrar tutores locales o en línea para recibir apoyo en sus estudios. Los estudiantes pueden buscar tutores basados en su ubicación, materias de interés y nivel de educación. Wyzant ofrece una amplia gama de materias, desde matemáticas y ciencias hasta idiomas y música. Los tutores de Wyzant establecen sus propias tarifas y horarios, lo que brinda flexibilidad a los estudiantes para encontrar un tutor que se adapte a sus necesidades y presupuesto.</td>
  </tr>  
  
  <tr >
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Ventajas de los competidores</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Disponibilidad 24/7: Una ventaja clave de Tutor.com es su disponibilidad las 24 horas del día, los 7 días de la semana, lo que permite a los estudiantes acceder a ayuda en cualquier momento, incluso en horarios nocturnos o durante las vacaciones
    Amplia gama de materias: Tutor.com ofrece ayuda en una amplia variedad de materias, desde matemáticas y ciencias hasta idiomas y humanidades, lo que lo hace atractivo para estudiantes de diferentes niveles y áreas de estudio.
    Recursos de aprendizaje adicionales: Además de la tutoría en vivo, Tutor.com ofrece recursos adicionales como ejercicios de práctica y lecciones pregrabadas, lo que proporciona un valor adicional a los estudiantes </td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Selección de tutores personalizada Chegg Tutors permite a los estudiantes buscar y seleccionar tutores basados en sus necesidades específicas, lo que les permite encontrar un tutor que se ajuste a su estilo de aprendizaje y materias de interés
    Sesiones de tutoría en línea en tiempo real: La plataforma ofrece sesiones de tutoría en línea a través de videoconferencia, lo que facilita la interacción en tiempo real con los tutores y la resolución de problemas de manera efectiva
    Expertos en campos específicos: Chegg Tutors se enfoca en proporcionar tutores que son expertos en sus respectivos campos, lo que garantiza una alta calidad de tutoría
</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Opciones de tutoría en línea y en persona: Wyzant ofrece la flexibilidad de encontrar tutores tanto en línea como en persona, lo que permite a los estudiantes elegir la modalidad de tutoría que mejor se adapte a sus necesidades y preferencias
    Personalización: Los tutores de Wyzant establecen sus propias tarifas y horarios, lo que brinda a los estudiantes la oportunidad de encontrar un tutor que se ajuste a su presupuesto y horario
    Evaluaciones y reseñas de tutores: Los estudiantes pueden revisar las evaluaciones y reseñas de otros estudiantes sobre los tutores de Wyzant, lo que les ayuda a tomar decisiones informadas sobre a quién elegir
</td>
  </tr>  
  
  <tr >
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Mercado Objetivo</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Estudiantes de todas las edades: Tutor.com atiende a una amplia variedad de estudiantes, desde escolares hasta universitarios y adultos que buscan mejorar sus habilidades académicas
    Personas que necesitan ayuda inmediata: Su disponibilidad las 24/7 lo hace atractivo para aquellos que necesitan asistencia en cualquier momento, como en la preparación de exámenes de último minuto o la resolución de problemas urgentes
    Aquellos que buscan una amplia gama de materias: Dado que ofrece tutoría en una amplia variedad de materias, atrae a estudiantes de diferentes áreas de estudio.</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Estudiantes universitarios y de nivel superior: Chegg Tutors se enfoca en proporcionar tutores expertos en campos específicos, lo que lo hace especialmente atractivo para estudiantes universitarios y de posgrado que buscan ayuda en materias más avanzadas
    Personas que prefieren tutoría en tiempo real: Aquellos que valoran las sesiones de tutoría en línea en tiempo real a través de videoconferencia pueden encontrar en Chegg Tutors una solución adecuada
    Estudiantes que buscan tutores Especializados: Los estudiantes que necesitan ayuda con materias específicas o desean trabajar con un tutor altamente calificado pueden beneficiarse de Chegg Tutors</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Estudiantes de todas las edades y niveles: Wyzant ofrece una amplia gama de tutores en línea y locales, lo que lo hace adecuado para estudiantes de todas las edades y niveles educativos, desde primaria hasta posgrado
    Personas que buscan flexibilidad y personalización: Aquellos que desean la flexibilidad de elegir tutores basados en sus necesidades y horarios específicos pueden encontrar en Wyzant una solución conveniente
    Estudiantes que valoran las reseñas y evaluaciones: Wyzant permite a los estudiantes revisar las evaluaciones y reseñas de los tutores, lo que les ayuda a tomar decisiones informadas sobre a quién contratar</td>
  </tr>
    <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Estrategias de Marketing</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Publicidad en línea: Utilizar anuncios pagados en motores de búsqueda (SEM) y en redes sociales para llegar a estudiantes que buscan ayuda en línea
    Marketing de contenidos: Crear blogs, artículos y recursos educativos de alta calidad para atraer a estudiantes y posicionarse como una fuente confiable de información y tutoría
    Programas de afiliados: Colaborar con sitios web y blogs relacionados con la educación para promocionar el servicio a cambio de comisiones por referencias
    Ofertas promocionales: Ofrecer descuentos o períodos de prueba gratuitos para atraer a nuevos usuarios y fomentar la retención</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Enfoque en tutores expertos: Destacar la experiencia y calificaciones de los tutores para atraer a estudiantes que buscan asistencia de alta calidad en materias específicas
    Marketing de boca a boca: Incentivar a los estudiantes satisfechos a recomendar el servicio a sus amigos y compañeros de clase
    Contenido educativo: Publicar videos, guías y recursos de aprendizaje en línea para mostrar la experiencia y conocimiento de la plataforma
    Colaboraciones con instituciones educativas: Establecer asociaciones con escuelas y universidades para promover el servicio como un recurso adicional para los estudiantes</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Listados locales y personalizados: Utilizar estrategias de SEO local para destacar en las búsquedas de estudiantes que buscan tutores en su área
    Programa de referencias: Recompensar a los tutores y estudiantes por referir nuevos usuarios a la plataforma
    Marketing de reseñas y testimonios: Mostrar reseñas y testimonios de tutores y estudiantes satisfechos para generar confianza en la plataforma
    Participación en ferias educativas y eventos locales: Promover la plataforma en eventos educativos locales y conferencias para llegar a la comunidad estudiantil
</td>
  </tr>
  </tr>
    <tr>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Precios y costos</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Precio para estudiantes: Tutor.com ofrece un servicio de suscripción que generalmente varía desde alrededor de $39.99 a $79.99 por mes, dependiendo del nivel de acceso y la cantidad de tiempo de tutoría en línea incluido en el plan. También ofrecen planes anuales con descuentos
    Costos para la plataforma: Los costos para la plataforma en sí incluyen la compensación para los tutores, el mantenimiento del sitio web y los servidores para brindar tutoría en línea en tiempo real
</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Precio para estudiantes: Chegg Tutors utiliza un modelo de precios por hora. El costo por hora de tutoría puede variar según la materia y la experiencia del tutor, pero generalmente oscila entre $30 y $75 por hora
    Costos para la plataforma: Los costos para la plataforma incluyen la compensación para los tutores, los gastos de marketing y publicidad, así como el mantenimiento de la plataforma en línea
</td>
    <td style="border:1px solid #dddddd; padding: 8px; text-align:center;">Precio para estudiantes: En Wyzant, los tutores establecen sus propias tarifas, por lo que los precios pueden variar ampliamente. El costo de las lecciones generalmente varía desde $30 hasta $80 o más por hora, dependiendo de la materia y la ubicación del tutor
    Costos para la plataforma: Wyzant cobra una tarifa de servicio a los estudiantes en función del precio de la lección. Además, la plataforma recauda una comisión de los ingresos de los tutores por cada lección
</td>
  </tr>
  
</table>


## 2.1.2 Estrategias y tacticas frente a competidores

a)       Aplicaremos una estrategia de supervisión de los indicadores de desempeño para evaluar el porcentaje de éxito en cada contratación de profesionales para medir las métricas de rendimiento de nuestra aplicación y sugerir cambios para el beneficio del usuario.

b)      La segunda estrategia es desarrollar un ataque en cadena, como estamos inmersos en un ámbito tecnológico, no puedes atacar directamente al competidor más potente, pues cuenta con más medios que nosotros y podría ser contraproducente. Entonces debemos ir obteniendo mayor participación en el mercado atacando los mercados más pequeños y posicionándonos directamente en ellos ofreciendo más modalidades que ellos para que los usuarios prefieran nuestro servicio al de ellos.

c)       Otra estrategia implica la implementación de una interfaz de búsqueda de cursos, de esta manera le permitimos al usuario poder conseguir las clases de ciertas áreas con mayor facilidad separando los cursos en áreas como las de matemáticas, física o comunicaciones para que los usuarios puedan encontrar más fácil algún curso que estén buscando o que quieran aprender y/o reforzar.

d)      Finalmente, emplearemos la estrategia competitiva de diferenciación, consta en ofrecer un producto diferente con una interfaz única y con mejoras totalmente pensadas en la satisfacción del usuario

## 2.2. Entrevistas

En este punto presentaremos los resultados de las entrevistas realizadas a los usuarios objetivos.

## 2.2.1 Diseño de Entrevistas
En esta sección, mostraremos las preguntas que hemos generado para realizar las entrevistas a los dos tipos de usuarios objetivos. Cabe destacar, que las preguntas realizadas son de tipo abierto, con el objetivo de recolectar información relevante que nos ayude a tener una idea más precisa de cómo solucionar problemas de nuestros usuarios objetivo.
Preguntas principales y complementarias para las entrevistas

### 1. Estudiantes

**a. Preguntas introductorias**

· ¿Cuál es su nombre?

. ¿Cuál es su género?

. ¿Cuál es su edad?

. ¿Cuál es su distrito de residencia?

. ¿Cuál es su estado civil?

· ¿A que se dedica actualmente?

. ¿Cuál es son sus frustraciones? 

. ¿Comó considera que es su personalidad?

. ¿Cúales son sus habilidades?

. ¿Qué marcas e influencias usa?

. ¿Que dispositivo usa en su vida diaria?

. ¿Con que canales digitales interactua?

. ¿Cúales son sus objetivos?

· ¿Qué tanta experiencia tienes en la elaboración de maquetas?

**b. Preguntas Principales:**

. 	¿Cuando empezaste con las maquetas, tuviste algunos problemas para crearlos?

.	¿Cuánto tiempo le dedicas a la elaboración de maquetas? ¿Por qué?

.	Si hubieras tenido un asesor en tus proyectos de maquetas ¿Tus trabajos hubieran sido más eficientes?

.	¿Alguna vez pediste ayuda a un profesor o estudiante con experiencia para la creación de las maquetas? ¿Por qué?

. ¿Te gustaría encontrar asesores con experiencia de diversos temas de maquetas en un solo sitio web, para que te brinden ayuda?
Se explica el proyecto del website  “ArquiMentor” 

.	¿Qué opinas de este proyecto?

·         ¿Qué funcionalidades adicionales que creas conveniente nos recomiendas agregar?


### 2. Asesores

**a. Preguntas introductorias**

· ¿Cuál es su nombre?

. ¿Cuál es su género?

. ¿Cuál es su edad?

. ¿Cuál es su distrito de residencia?

. ¿Cuál es su estado civil?

· ¿A que se dedica actualmente?

. ¿Cuál es son sus frustraciones?

. ¿Comó considera que es su personalidad?

. ¿Cúales son sus habilidades?

. ¿Qué marcas e influencias usa?

. ¿Que dispositivo usa en su vida diaria?

. ¿Con que canales digitales interactua?

. ¿Cúales son sus objetivos?

· ¿Qué tanta experiencia tienes en la elaboración de maquetas?

**b.       Preguntas Principales**

·         ¿Tenías dificultad cuando empezaste con la elaboración de 
maquetas?

·         ¿Alguna vez ayudaste a un estudiante a realizar una maqueta?

·         ¿Considera difícil el asesoramiento en este ámbito?

Se explica el proyecto del website  “ArquiMentor” 

.	¿Qué opinas de este proyecto?

·         ¿Qué funcionalidades adicionales que creas conveniente nos recomiendas agregar?

·         ¿Qué opina de que usted pueda poner su tarifa por sus servicios?

·         ¿Considera una ventaja para usted que luego de sus servicios sus estudiantes puedan ponerle calificación por su trabajo?

.	¿Cree que sería más ordenado el tener un horario impuesto por usted, para que los estudiantes separen su tiempo?


# 2.2.2 Entrevistas 


- Url del stream de las entrevistas:
- Timing:

### Segmento estudiante

Entrevista 1:

● Nombres y Apellidos:Renato Honorio

● Edad: 21 años

● Distrito: Chorrillos

● Evidencia de la reunión:

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149420106498191483/image.png" alt="" width="500" height="200" />

●	Url de stream: https://upcedupe-my.sharepoint.com/:v:/g/personal/u201919295_upc_edu_pe/ERFKUtqskD1OtBbwiRvhwS4BvnM_trAJLqQKySgFwqAY8g?e=0oaQRc


●	Resumen sobre la entrevista:

Hablamos con un dedicado estudiante de Arquitectura que invierte seis horas al día en sus estudios. Aunque inicialmente enfrentó desafíos al crear maquetas debido a su falta de experiencia, su entusiasmo por nuestra aplicación radica en la posibilidad de acceder a asesores personalizados. Ve en la aplicación una oportunidad invaluable para encontrar un mentor que se ajuste a sus necesidades de aprendizaje. Utiliza software crucial para arquitectos como , Revit y AutoCad, y se apoya en dispositivos como teléfonos, laptop y tablets. Para interactuar, confía en Discord, Google Meet, Zoom y ocasionalmente en reuniones presenciales, y su navegación web se realiza principalmente a través de Google Chrome y Opera. 

Entrevista 2:

●	Nombres y Apellidos: Roger Castillo

●	Edad: 20 Años

●	Distrito: San Miguel

●	Evidencia de la reunión


<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149420329861660692/image.png" alt="" width="600" height="250" />


●	Resumen de la entrevista:

Steve es un joven estudiante de arquitectura de los primeros ciclos, se considera una persona divertida y decidida en su futuro. Nos cuenta su experiencia con las maquetas que tuvo que realizar, además de los programas que usan para complementar. Al inicio sentía que no tenía mucha experiencia y afirma que un buen asesoramiento en los inicios hubieran hecho de sus trabajos de arquitectura más eficientes. Después de comentarle el proyecto “ArquiMentor” le pareció grandiosa la idea, y nos sugirió que agreguemos segmentos de ayuda en los diferentes programas de software que utilizan los arquitectos. Las marcas que mas usa es Archicad, Revit y AutoCAD, la tecnologia que usa por lo general son celulares, ordenadores o tablets, sus canales de interacción más usadas son Discord, Google Meet o reuniones presenciales. Por último punto los browser que usa son Brave y Google.  

Entrevista 3:

●	Nombres y Apellidos: Carlos Martinez

●	Edad: 20

●	Distrito: Lima

●	Evidencia de la reunión:

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149192262153158676/image.png" alt="" width="600" height="250" />

●	Url del Stream: https://youtu.be/xpjy7Ydvpe0

●	Resumen de la entrevista: El estudiante Carlos nos cuenta un poco de él y muestra interés sobre nuestro proyecto de ayuda para los estudiantes. Además, le preguntamos porqué es necesario tener ayuda en los temas que no logra entender.

Entrevista 4:

● Nombres y Apellidos: Marilyn Monrroy

● Edad: 20 años

● Distrito: Lima

● Evidencia de la reunión:

<img src="https://i.ibb.co/LzsfpZt/imageaaaa.png" alt="imageaaaa" border="0"></a><br /><a target='_blank' href='https://imgbb.com/' />

●	Url de stream: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201b782_upc_edu_pe/EfA6CYMjwC1Cqpy5t4SNtGgBMIBi8DQ5TUVX41tIyeAJuQ?e=aWfG9k&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19

●	Resumen sobre la entrevista: En la entrevista, la estudiante nos brinda información sobre sí misma y destaca que su principal desafío al crear maquetas ha sido la relación entre la forma y la función que deben cumplir en la construcción. También menciona que la construcción de la maqueta en sí le lleva aproximadamente dos días, pero lo que realmente consume la mayor parte de su tiempo es la planificación y la generación de ideas. Asimismo, está convencida de que si hubiera contado con un asesor, la ejecución de la idea habría sido mucho más rápida. Según su experiencia, suele buscar ayuda entre los arquitectos de la universidad, aunque no siempre están disponibles, por lo que acude a estudiantes en ciclos más avanzados. Considera que un recurso como Arquimentor sería muy útil para los estudiantes, ya que les proporcionaría mayor inspiración y soluciones. Además, nos sugiere incorporar una sección dedicada a la elaboración de planos y a los reglamentos de construcción. También propone incluir una funcionalidad para la construcción de mobiliario que a menudo se requiere como complemento de las maquetas.

### Segmento asesor 

Entrevista 1:

●	Nombres y Apellidos: Dora Villalobos

●	Edad: 51 Años

●	Distrito: Surco

●	Evidencia de la reunión

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149192195623092365/image.png" alt="" width="500" height="250" />

●	Url del Stream:

●	Resumen de la entrevista

La entrevista fue realizada a Dora Villalobos, tiene 51 años y reside en surco. Es una arquitecta con varios años de experiencia en el campo laboral, trabaja para la municipalidad de surco. Ha tenido experiencia capacitando a otras personas en el ámbito de la arquitectura pero no con alumnos. Luego de explicarle lo que hace nuestra startup le interesó el tema y dice que le gustaría poder experimentar lo que es dar asesorías a alumnos que lo requieran, le parece adecuado y perfecto que una de las características de la app sea que luego de las asesorías los alumnos puedan dar un feedback sobre qué es lo que les pareció la sesión dándoles una calificación.



Entrevistado 2:

●	Nombres y Apellidos: Liz Ramos

●	Edad: 30 Años

●	Provincia: La Plata

●	Evidencia de la reunión

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149192287943925780/image.png" alt="" width="350" height="" />

●	Url del stream: https://youtu.be/sfhP7M2MDk8

●	Resumen de la entrevista: 

Liz nos cuenta de su experiencia como asesora en fotografía, considera que las enseñanzas que se brindan en la aplicación web debe tener asesorías en tiempo real para que el estudiante pueda resolver sus dudas y el asesor le brinde retroalimentación. Así mismo le gustaría que existan foros de estudiantes para poder compartir ideas y dudas. Por otro lado, considera que la calificación de docentes genera competitividad en la plataforma y con esto un mejor desempeño en el servicio que brindan.


## 2.2.3 Analisis de Entrevistas
A continuación, se desarrolla una estrategia en conjunto con el equipo para identificar los puntos en común en base a las respuestas de cada entrevistado a cada pregunta. Esto nos ayuda a realizar un análisis más conciso y seguro para desarrollar nuestra aplicación en base a la información recolectada. 

**Segmento 1: Estudiantes que buscan Ayuda en sus estudios**

¿Qué tanta experiencia tienes en la elaboración de maquetas?

El 60% de los estudiantes informó su nivel de experiencia en la elaboración de maquetas, lo que indica diversidad en la audiencia, desde principiantes hasta aquellos con experiencia.

¿Cuando empezaste con las maquetas, tuviste algunos problemas para crearlos?

El 80% de los estudiantes admitió problemas iniciales al comenzar con las maquetas, destacando la naturaleza desafiante del aprendizaje.

¿Cuánto tiempo le dedicas a la elaboración de maquetas? ¿Por qué?

El 70% de los estudiantes compartió cuánto tiempo dedican a la elaboración de maquetas, lo que puede ayudar a determinar la demanda y el compromiso potencial.

Si hubieras tenido un asesor en tus proyectos de maquetas, ¿Tus trabajos hubieran sido más eficientes?

El 90% de los estudiantes expresó que sus trabajos podrían haber sido más eficientes con un asesor, resaltando la necesidad percibida de orientación.

¿Alguna vez pediste ayuda a un profesor o estudiante con experiencia para la creación de las maquetas? ¿Por qué?

El 50% de los estudiantes buscó ayuda de profesores o estudiantes con experiencia, destacando la importancia de la asistencia y el asesoramiento.

¿Te gustaría encontrar asesores con experiencia de diversos temas de maquetas en un solo sitio web, para que te brinden ayuda?

El 80% de los estudiantes mostró interés en encontrar asesores con experiencia en un solo lugar, respaldando la propuesta del proyecto de proporcionar una plataforma centralizada.

**Segmento 2: Asesores**

¿Qué tanta experiencia tienes en la elaboración de maquetas?

Los asesores en su totalidad (100%) demostraron experiencia sólida en la elaboración de maquetas, respaldando su capacidad para brindar asesoramiento efectivo.

¿Tenías dificultad cuando empezaste con la elaboración de maquetas?

El 50% de los asesores admitió dificultades iniciales, lo que indica que comprenden los desafíos que enfrentan los estudiantes.

¿Alguna vez ayudaste a un estudiante a realizar una maqueta?

El 100% de los asesores ha ayudado a estudiantes previamente, lo que sugiere que están dispuestos a compartir su conocimiento y experiencia.

¿Considera difícil el asesoramiento en este ámbito?

El 100% de los asesores percibe cierta dificultad en el asesoramiento, lo que indica que pueden estar interesados en herramientas que faciliten su labor.

Conclusión General:

El análisis detallado con porcentajes revela claramente que los estudiantes tienen una demanda considerable de asesoramiento en la elaboración de maquetas, y que los asesores están dispuestos a proporcionar este servicio. Ambos grupos muestran un gran interés en una plataforma centralizada que facilite la conexión y colaboración. La plataforma tiene un potencial significativo para satisfacer estas necesidades, pero es crucial abordar aspectos como la seguridad de los datos y la calidad del servicio para ganar la confianza de los usuarios. Además, tomar en cuenta las funcionalidades adicionales sugeridas por los entrevistados podría mejorar aún más la propuesta de valor de la plataforma.


## 2.3 NeedFinding
## 2.3.1 User Personas

A continuación, se construirán los User Persona de cada segmento objetivo de nuestra plataforma. Para ello, se utilizarán los datos recolectados de las entrevistas realizadas; principalmente, los que muestran los objetivos, motivaciones y frustraciones con las que cuentan cada uno de los sectores que conforman al público al que va dirigida la aplicación. Es decir, se presentará un estereotipo de un estudiante como de un asesor.

**User Persona- Asesores**

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149192370945011712/image.png" alt="" width="400" height="" />

**User Persona- Estudiantes**

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149195290138660874/image.png" alt="" width="400" height="" />

## 2.3.2 User Task Matrix 
En esta etapa nos enfocaremos en las tareas que los User Personas Estudiantes, representados por Mateo Aguirre. Asimismo, el segundo User Persona son los profesionales que dan las asesorías de los cursos, representados por Carlos Mendéz. realizan para alcanzar su propósito, teniendo como segmentos objetivos a los estudiantes jóvenes que quieran mejorar en su vida académica como los asesores que quieren generar un ingreso extra realizando estas asesorías

<table>
<tr>
    <th style="border:1px solid #dddddd; padding: 8px; text-align:center;" rowspan="2">User Task Matrix</th>
    <th style="border: 1px solid #dddddd; padding: 8px; text-align: center;" colspan="2">Mateo Aguirre</th>
    <th style="border: 1px solid #dddddd; padding: 8px; text-align: center;" colspan="2">Carlos Mendez</th>
</tr>

  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Frecuencia</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Importancia</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Frecuencia</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Importancia</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Registrarse</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Always</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">High</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Always</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">High</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Iniciar Sesion</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Always</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">High</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Always</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">High</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Buscar Asesoria</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Always</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">High</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Rarely</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Low</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Ver Perfil de Asesores</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Often</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Medium</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Rarely</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Low</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Programar una Asesoria</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Often</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Medium</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Often</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Medium</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Participar en una Asesoria</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Always</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">High</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Always</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">High</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Evaluar una asesoria</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Often</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Medium</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Rarely</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Low</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Actualizar Perfil</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Rarely</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Low</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Often</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Medium</td>
  </tr>
</table>
Tareas con mayor frecuencia e importancia: 

• Frecuencia: Las tareas con mayor frecuencia son aquellas relacionadas con el funcionamiento de la aplicación acciones como registrarse e iniciar sesión en la plataforma son las que más se realizan así como también el participar en una asesoría es una acción que es la que más se realizaría.

• Importancia: Como Tareas de mayor importancia son aquellas que son esenciales para que la plataforma pueda cumplir la función tareas como las de Buscar una asesoría son de las más importantes ya que la plataforma se base en eso otras acciones con una importancia importante son la de programar una sesión de asesoría ya que aquí es donde se decide cuando es que se va a llevar a cabo como el tema o el trabajo a tratar durante la asesoría como el tiempo y el pago de la asesoría 

Diferencias y Similitudes:
La principal diferencia entre los asesores y los estudiantes es que los que van a buscar son los estudiantes principalmente ya que ellos son los que van a escoger con quién quieren tener una asesoria otra diferencia es que a la hora de evaluar, esta sería una función pensada más para los estudiantes que para los asesores ya que aquí pueden decir si el asesor cunmplio con las expectativas y como se sintio en general con la asesoría. Y una similitud que tiene es a la hora de coordinar una asesoría ya que los dos se juntaran para decidir todo lo esencial para poder llevar a cabo la asesoría. 

## 2.3.3 User Journey Mapping
El User Journey Mapping es una herramienta de Design Thinking que nos ayuda a graficar un mapa con las etapas, canales, elementos e interacciones por las que pasa nuestro usuario durante el ciclo de uso del servicio. 

**Segmento 1-Estudiantes**

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149196650934456420/image.png" alt="" width="400" height="" />

**Segmento 2-Asesores**

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149196689094230157/image.png" alt="" width="400" height="" />

## 2.3.4 Empathy Mapping

En esta sección se presenta el Empathy Mapping de nuestros 2 segmentos objetivos. Esta herramienta se utilizó porque permite identificar nuestro público objetivo, conocer su entorno y sus necesidades, lo cual nos permite ver el mundo a través de su perspectiva.

**Segmento 1 : Estudiantes**

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149196720085946480/image.png" alt="" width="400" height="" />

**Segmento 2-Asesores**

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149196760254783488/image.png" alt="" width="400" height="" />

## 2.3.5 As-is Scenario Mapping
En esta sección, se identificó las fases que podría presentar a nuestros User persona, del cómo se afrontó, sus pensamientos, sus sentimientos para identificar qué soluciones son las más adecuadas para satisfacer sus inquietudes.

## Segmento 1- Estudiantes que requieren una asesoria

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149486010699362396/C72rYIXdaZDc1BP7utev1LrNJ5Zs3g8DKSRVOUJsxF89fsSzOvwTRwMpvse-MZuot-M_d3ToQ_6zHu4Y5SoVY4IYXzfUV0uC1ip8iZQR-irMKtH6UKRvtgniaLP2XfxN75jdhxoH1nCV9teBep_h3ik.png" alt="" width="" height="" />

## Segmento 2- Asesores 


<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149488074343055441/image.png" alt="" width="" height="" />


# Capitulo 3: Requirements Specification

## 3.1. To-Be Scenario Mapping
 
A continuación, se presenta el To Be Scenario Mapping para los segmentos, con el cual satisfacemos sus necesidades por medio del sitio web Arquimentor. Esta herramienta refleja cómo Arquimentor abordará y satisfará las necesidades de nuestros usuarios a través de su sitio web. Nuestro compromiso es ofrecer experiencias enriquecedoras y soluciones efectivas a medida que continuamos desarrollando y mejorando nuestros servicios.

### Segmento 1 - Estudiantes que requieren una asesoría

<img src="https://i.ibb.co/ncyTQj5/ESTUDENT.png" alt="ESTUDENT" border="0">

### Segmento 2 - Asesores

<img src="https://i.ibb.co/WvptZQy/ASESOR.png" alt="ASESOR" border="0">

## 3.2. User Stories

En el marco d el proyecto ArquiMentor, las User Stories emergen como pilares fundamentales para abordar las necesidades de una audiencia diversificada. Estas breves pero impactantes narrativas no solo nos permiten comprender las exigencias de nuestros usuarios de manera precisa, sino que también nos proveen el medio para diseñar soluciones educativas altamente personalizadas. En este segmento, exploraremos cómo esta metodología se convierte en un vehículo esencial para transformar conceptos abstractos en soluciones concretas y efectivas, en aras de enriquecer la experiencia educativa de nuestros usuarios.

| Epic / Story ID | Título | Descripción                                                                                                                                              | Criterios de aceptación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Relacionado con (Epic ID) |
|----------|----------|----------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|
| EP007 | Acceso a la Landing Page | 	Como usuario quiero acceder a la landing page para conocer a Arquimentor                                                                                | -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |-|
| EP008 |  Desarrollo de Funcionalidades de la Aplicación| Como desarrollador, quiero construir y optimizar la plataforma de Arquimentor para brindar a los usuarios una experiencia efectiva.                      | -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |-|
| EP004	| Gestión de proyectos	| Como usuario quiero compartir mis proyectos para que el asesor revise mis avances.                                                                       | -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |-|
| EP003	| Agendar reunión | Como usuario quiero programar una reunión con otro usuario para conversar sobre los detalles del proyecto.                                               | -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |-|
|EP002 | Búsqueda de asesores | Como usuario estudiante quiero encontrar asesores para que me dé tutorías.                                                                               | -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |-|
| EP005	| Gestión de la suscripción | Como usuario quiero obtener una suscripción de paga para acceder a beneficios en la plataforma.                                                          | -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |-|
| EP006	| Compartir reseñas y valoraciones | Como usuario quiero compartir reseñas y calificar a los asesores para compartir con otros usuarios mis experiencias.                                     | -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |-|
| EP001 | Gestión de cuenta | Como usuario quiero registrarme, acceder y configurar mi cuenta para buscar asesoría o asesorar.                                                         | -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |-|
|US019|Conocer a Arquimentor a través del landing page| 	Como visitante del landing page quiero conocer a Arquimentor para reforzar mi confianza en la plataforma.                                               | Escenario 1: Home<br/>Given: El usuario se encuentra en la landing page de Arquimentor.<br/>When: Presiona sobre "Home".<br/>Then: Se envía al usuario a la sección donde se describe brevemente a Arquimentor.<br/><br/>Escenario 2: Conocenos<br/>Given: El usuario se encuentra en la landing page de Arquimentor.<br/>When: Presiona sobre "Conócenos" (o "Know Us").<br/>Then: Se envía al usuario a la sección donde se describen los integrantes de la Startup.<br/><br/>Escenario 3: Contáctanos<br/>Given: El usuario se encuentra en la landing page de Arquimentor.<br/>When: Presiona sobre "Contáctanos" (o "Contact Us").<br/>Then: Se envía al usuario a la sección donde se encuentran los medios de comunicación de Arquimentor.                                                                                                                                                                                                                                                                                                                                            |EP007|
|US024|Configurar la Base de Datos| Como desarrollador, quiero configurar una base de datos para almacenar información de usuarios y propiedades.                                            | Escenario 1: Configuración de la Base de Datos de Usuarios<br/>Given: El desarrollador necesita configurar la base de datos para almacenar información de usuarios.<br/>When: El desarrollador configura la estructura de la base de datos.<br/>Then: La base de datos está configurada correctamente para almacenar información de usuarios.<br/><br/>Escenario 2: Configuración de la Base de Datos de Proyectos<br/>Given: El desarrollador necesita configurar la base de datos para almacenar información de proyectos.<br/>When: El desarrollador establece la estructura de la base de datos de proyectos.<br/>Then: La base de datos está lista para almacenar y gestionar información de proyectos.                                                                                                                                                                                                                                                                                                                                                                                 |EP008|
|US006|Búsqueda de asesor| 	Como usuario estudiante quiero buscar a un asesor para que me oriente en mi proyecto.                                                                   | Escenario 1: Búsqueda con éxito<br/>Given: El estudiante busca al asesor por nombre.<br/>And: El asesor está registrado.<br/>When: El estudiante realiza la búsqueda.<br/>Then: Encuentra el nombre del asesor que buscaba y otros nombres similares.<br/><br/>Escenario 2: Búsqueda sin éxito<br/>Given: El estudiante busca al asesor por nombre.<br/>And: El asesor no está registrado.<br/>When: El estudiante realiza la búsqueda.<br/>Then: Encuentra nombres similares al ingresado.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |EP002|
|US010|Recibir, aceptar o rechazar una solicitud de un estudiante| 	Como usuariobasesor quiero recibir una solicitud y poder aceptar o rechazar para enseñar y orientar a un estudiante.                                    | Escenario 1: Recibir una solicitud<br/>Given: El asesor recibe una solicitud de un estudiante.<br/>When: El asesor se determina a leer la solicitud.<br/>Then: Se muestran los detalles de la solicitud.<br/><br/>Escenario 2: Aceptar una solicitud<br/>Given: El asesor revisa los detalles de la solicitud recibida.<br/>When: El asesor acepta la solicitud.<br/>Then: Se envía información sobre la reunión al asesor y al estudiante.<br/><br/>Escenario 3: Rechazar una solicitud<br/>Given: El asesor revisa los detalles de la solicitud recibida.<br/>When: El asesor rechaza solicitud.<br/>Then: Se le informa al estudiante.                                                                                                                                                                                                                                                                                                                                                                                                                                                    |EP003|
|US011|Programar reuniones| 	Como usuario estudiante quiero programar las reuniones con el asesor para que me oriente y me de feedback.                                              | Escenario 1: Agendar una reunión<br/>Given: El usuario fija una fecha y la hora.<br/>And: Ingresa un mensaje(opcional).<br/>When: El usuario confirma la programación de la reunión.<br/>Then: La reunión se programa con éxito.<br/><br/>Escenario 2: Agendar una reunión incompleta<br/>Given: El usuario intenta programar la reunión con datos incompletos.<br/>When: La fecha y/o la hora de la reunión están incompletas.<br/>Then: La reunión no se programa.<br/><br/>Escenario 3: Agendar una reunión como visitante<br/>Given: Un visitante desea programar una reunión.<br/>When: El visitante intenta ingresar sus datos para programar la reunión.<br/>Then: No se programa la reunión.                                                                                                                                                                                                                                                                                                                                                                                         |EP003|
|US020|Reconocer las ventajas de Arquimentor a través del landing page| 	Como visitante del landing page quiero conocer las ventajas de la plataforma para saber si se ajusta a lo que necesito.                                 | Escenario 1: Visualizar ventajas de estudiante<br/>Given: El usuario se encuentra en la landing page de Arquimentor. <br/>When: Presiona sobre "Servicios" (o "Services"). <br/>Then: Se envía al usuario a la sección "Estudiantes" donde se muestran las ventajas para los estudiantes.<br/><br/>Escenario 2: Visualizar ventajas de asesor<br/>Given: El usuario se encuentra en la landing page de Arquimentor.<br/>When: Presiona sobre "Servicios" (o "Services").<br/>Then: Se envía al usuario a la sección "Asesores" donde se muestran las ventajas para los asesores.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |EP007|
|US021|Diseñar la interfaz de Usuario| Como desarrollador, quiero diseñar una interfaz de usuario atractiva y fácil de usar para una experiencia agradable.                                     | Escenario 1: Creación de la Interfaz de Inicio de Sesión<br/>Given: El desarrollador desea crear la interfaz de inicio de sesión.<br/>When: El desarrollador trabaja en el diseño de la pantalla de inicio de sesión.<br/>Then: La interfaz de inicio de sesión se ha diseñado con éxito.<br/><br/>Escenario 2: Diseño de la Interfaz del Perfil de Usuario<br/>Given: El desarrollador busca diseñar la interfaz del perfil de usuario.<br/>When: El desarrollador trabaja en el diseño del perfil de usuario.<br/>Then: La interfaz del perfil de usuario se ha diseñado de manera atractiva y fácil de usar.                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |EP008|
|US025|Optimizar el Rendimiento de la Aplicación| Como desarrollador, quiero optimizar el rendimiento de la aplicación para una experiencia rápida y fluida.                                               | Escenario 1: Mejora del Rendimiento de la Aplicación<br/>Given: El desarrollador busca optimizar el rendimiento de la aplicación.<br/>When: El desarrollador realiza mejoras en el código y la arquitectura.<br/>Then: La aplicación experimenta un rendimiento más rápido y fluido.<br/><br/>Escenario 2: Carga Rápida de Datos<br/>Given: El usuario inicia sesión en la aplicación.<br/>When: La aplicación carga datos de manera rápida y eficiente.<br/>Then: Los datos se muestran de manera instantánea, proporcionando una experiencia de usuario sin demoras.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |EP008|
|US004|Subir proyectos| 	Como usuario estudiante quiero subir mis proyectos actuales y pasados para encontrar al asesor que más se adapte a mi perfil.                           | Escenario 1: Cargar archivos de proyectos<br/>Given: El estudiante sube archivos en formatos .pdf, .jpg, .png, .doc.<br/>When: Se suben los archivos.<br/>Then: Los archivos se cargan exitosamente.<br/><br/>Escenario 2: Cargar archivos no válidos<br/>Given: El estudiante sube archivos que no son compatibles con los formatos permitidos.<br/>When: Se suben los archivos.<br/>Then: No se permite la carga.<br/><br/>Escenario 3: Cargar archivos pesados<br/>Given: El estudiante sube archivos que superan los 25MB de tamaño.<br/>When: Se suben los archivos.<br/>Then: No se permite la carga.<br/><br/>Escenario 4: Cargar archivos sobrepasando el límite del espacio proporcionado<br/>Given: El estudiante intenta subir varios archivos.<br/>When: Se intenta subir los archivos.<br/>Then: No se suben todos los archivos.                                                                                                                                                                                                                                                |EP004|
|US009|Envío de solicitud a un asesor| 	Como usuario estudiante quiero enviar una solicitud a un asesor para que me oriente con mi proyecto.                                                    | Escenario 1: Generar una solicitud<br/>Given: El usuario ingresa los detalles de la reunión (fecha, hora, resumen del proyecto).<br/>When: Se envía la solicitud.<br/>Then: La solicitud se envía correctamente.<br/><br/>Escenario 2: Generar una solicitud incompleta<br/>Given: El usuario ingresa detalles incompletos de la reunión (fecha, hora, resumen del proyecto).<br/>When: Intenta enviar la solicitud.<br/>Then: La solicitud no se envía debido a datos incompletos.<br/><br/>Escenario 3: Generar una solicitud como visitante<br/>Given: El usuario ingresa detalles incompletos o completos de la reunión (fecha, hora, resumen del proyecto).<br/>When: El visitante intenta enviar una solicitud.<br/>Then: La solicitud no se envía.                                                                                                                                                                                                                                                                                                                                    |EP003|
|US013|Registrar el avance del proyecto| 	Como usuario asesor quiero medir el avance del proyecto para tener un control de cada estudiante.                                                       | Escenario 1: Añadir avance<br/>Given: El usuario al término de una asesoría desea guardar el "Registrar avance".<br/>When: El usuario guarda el avance ingresa datos y añade notas.<br/>Then: Se registra el avance y las notas.<br/><br/>Escenario 2: Posponer añadir avance<br/>Given: El usuario al término de una asesoría desea guardar después de un tiempo o no registrar el "Registrar avance".<br/>When: El usuario decide guardar después de un tiempo o no registrar el "Registrar avance".<br/>Then: No se registrará el avance.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |EP004|
|US022|Funcionalidad de Búsqueda Avanzada| Como desarrollador, quiero desarrollar la funcionalidad de búsqueda avanzada con filtros.                                                                | Escenario 1: Implementación de Filtros de Búsqueda<br/>Given: El desarrollador desea agregar filtros avanzados a la funcionalidad de búsqueda.<br/>When: El desarrollador implementa filtros como opciones de búsqueda avanzada.<br/>Then: Los filtros de búsqueda avanzada están disponibles para los usuarios.<br/><br/>Escenario 2: Uso de Filtros de Búsqueda Avanzada<br/>Given: El usuario busca asesores específicos utilizando filtros avanzados.<br/>When: El usuario selecciona varios filtros y realiza una búsqueda.<br/>Then: Se muestran resultados de búsqueda que coinciden con los filtros seleccionados.<br/><br/>Escenario 3: Creación de la Interfaz de Registro de Usuarios<br/>Given: El desarrollador desea crear la interfaz de registro de usuarios.<br/>When: El desarrollador trabaja en el diseño de la pantalla de registro.<br/>Then: La interfaz de registro se ha diseñado de manera intuitiva y atractiva.                                                                                                                                                  |EP008|
|US023|Sistema de Autenticación y Registro| Como desarrollador, quiero implementar un sistema de autenticación y registro.                                                                           | Escenario 1: Implementación del Sistema de Autenticación<br/>Given: El desarrollador necesita implementar el sistema de autenticación.<br/>When: El desarrollador trabaja en la funcionalidad de autenticación.<br/>Then: Los usuarios pueden autenticarse con éxito en la aplicación.<br/><br/>Escenario 2: Desarrollo del Registro de Usuarios<br/>Given: El desarrollador debe crear la funcionalidad de registro de usuarios.<br/>When: El desarrollador trabaja en el proceso de registro.<br/>Then: Los usuarios pueden registrarse exitosamente en la plataforma.<br/><br/>Escenario 3: Recuperación de Contraseña<br/>Given: El usuario ha olvidado su contraseña y necesita recuperarla.<br/>When: El usuario solicita la recuperación de contraseña.<br/>Then: Se envía un enlace de recuperación a la dirección de correo electrónico del usuario.                                                                                                                                                                                                                                |EP008|
|US005|Subir Curriculum Vitae| 	Como usuario asesor quiero subir mi CV para que los estudiantes me conozcan mejor y confíen en mi experiencia.                                          | Escenario 1: Cargar CV<br/>Given: El asesor carga su CV en formato pdf.<br/>When: El asesor carga su CV en formato pdf.<br/>Then: El CV se sube y se muestra en su perfil.<br/><br/>Escenario 2: Cargar CV en formato incorrecto<br/>Given: El asesor carga su CV en otro formato diferente a pdf.<br/>When: El asesor carga su CV en otro formato diferente a pdf.<br/>Then: No se permite la carga del CV.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |EP004|
|US007|Filtrar la búsqueda de asesor| 	Como usuario estudiante quiero filtrar la búsqueda de asesor para encontrar al asesor que más se ajuste a mis horarios y necesidades                    | Escenario 1: Búsqueda con éxito<br/>Given: El estudiante busca al asesor por datos similares.<br/>When: El usuario decide buscar por datos similares.<br/>Then: No se encuentran nombres de asesores que cumplan los requisitos.<br/><br/>Escenario 2: Búsqueda sin éxito<br/>Given: El estudiante busca al asesor por datos similares.<br/>When: El usuario decide buscar por datos similares.<br/>Then: No se encuentran nombres de asesores que cumplan los requisitos.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |EP002|
|US008|Visualizar perfiles de asesores	| 5Como usuario estudiante quiero ingresar al perfil de los asesores para conocer su trayectoria.                                                          |Escenario 1: Ingreso al perfil completo del asesor<br/>Given: El usuario halla una lista de asesores.<br/>When: Opta visualizar los datos generales del asesor.<br/>Then: Se muestran los datos básicos, redes sociales, CV e información de contacto del asesor.<br/><br/>Escenario 2: Ingreso al CV del asesor<br/>Given: El usuario está interesado en obtener más información sobre el asesor.<br/>When: Determina que necesita información mas detalla que se localiza en su CV<br/>Then: Se muestra el CV del asesor.| EP002                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|US012|Visualizar las reuniones programadas	| Como usuario asesor quiero tener mis reuniones programadas en una agenda para ser más eficiente.                                                         | Escenario 1: Visualizar mis reuniones<br/>Given: El usuario desea recordar sus notas de agenda.<br/>When: Opta por recordar sus fechas anotadas.<br/>Then: Encuentra la lista de reuniones programadas de acuerdo con la hora y el día.<br/><br/>Escenario 2: Visualizar mis reuniones sin reuniones programadas<br/>Given: El usuario desea recordar sus notas de agenda.<br/>When: Opta por recordar sus fechas anotadas.<br/>Then: Se encuentra con una lista vacía.<br/><br/>Escenario 3: Visualizar detalles de una reunión<br/>Given: El usuario se encuentra la lista de reuniones programadas de acuerdo con la hora y el día.<br/>When: El usuario desea leer los detalles de la reunión.<br/>Then: El usuario se encuentra con la información detallada de la reunión.                                                                                                                                                                                                                                                                                                             |EP003|
|US014|Visualizar los avances del proyecto| 	Como usuario estudiante quiero visualizar los avances y el feedback recibido para conocer el estado de mi proyecto.                                     | Escenario 1: Revisar avance<br/>Given: El usuario desea revisar sus avances.<br/>When: El usuario ingresa a un proyecto actual.<br/>Then: Se muestran las métricas y notas subidas por el asesor.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |EP004|
|US015|Calificar a un asesor| 	Como usuario estudiante quiero calificar al asesor que me orientó para compartir mi experiencia con otros usuarios.                                     | Escenario 1: Evaluar al asesor<br/>Given: El usuario finaliza su proyecto y presiona en "Proyecto finalizado".<br/>When: Se muestra la opción de valorar y escribir un comentario (opcional) sobre el asesor, y el usuario envía su apreciación.<br/>Then: Se muestra un mensaje "Reseña enviada".<br/><br/>Escenario 2: Cancelar evaluar al asesor<br/>Given: El usuario finaliza su proyecto y presiona en "Proyecto finalizado".<br/>When: Se muestra la opción de valorar y escribir un comentario (opcional) sobre el asesor, y el usuario presiona sobre "Omitir".<br/>Then: Se muestra la pantalla principal.<br/><br/>Escenario 3: Valorar al asesor<br/>Given: El usuario finaliza su proyecto y presiona en "Proyecto finalizado".<br/>When: Se muestra la opción de valorar y escribir un comentario (opcional) sobre el asesor, y el usuario solo envía la valoración.<br/>Then: Se muestra un mensaje "Calificación enviada".                                                                                                                                                   |EP006|
|US017|Seleccionar un plan de suscripción	| Como usuario estudiante quiero seleccionar un plan de suscripción que se adecue a mis necesidades para acceder a otras funcionalidades de la plataforma. | Escenario 1: Obtener suscripción<br/>Given: El usuario selecciona un plan de suscripción y acepta los términos y condiciones.<br/>When: Ingresa sus datos personales y de métodos de pago.<br/>Then: Se envía un mensaje de confirmación a su correo.<br/><br/>Escenario 2: Términos de la suscripción<br/>Given: El usuario desea obtener una suscripción, pero no acepta los términos y condiciones.<br/>When: Intenta ingresar sus datos personales o de métodos de pago sin aceptar los términos y condiciones.<br/>Then: Se pausa el proceso.<br/>And: Se solicita al usuario que acepte los términos y condiciones antes de proceder.<br/><br/>Escenario 3: Obtener suscripción con datos incorrectos<br/>Given: El usuario ha seleccionado un plan de suscripción y aceptado los términos y condiciones.<br/>When: Ingresa información incorrecta en los campos de datos personales y/o de métodos de pago (por ejemplo, caracteres no permitidos o información incorrecta).<br/>Then: El proceso se anula.<br/>And: Se le solicita al usuario que verifique la información ingresada. |EP005|
|US001|Registrar cuenta| 	Como usuario quiero crear una cuenta para poder acceder a la plataforma.                                                                                | Escenario 1: Creación de cuenta<br/>Given: El usuario no está registrado.<br/>When: El usuario ingresa sus datos<br/>And: Elige su rol.<br/>Then: Se registra su cuenta con éxito.<br/><br/>Escenario 2: Creación de cuenta incorrecto<br/>Given: El usuario no está registrado.<br/>When: El usuario ingresa sus datos de forma incorrecta (caracteres no permitidos).<br/>Then: No se le permite continuar con el registro debido a un error en los datos ingresados.<br/><br/>Escenario 3: Creación de cuenta con correo de otra cuenta<br/>Given: El usuario cree que no está registrado.<br/>When: El usuario ingresa sus datos<br/>And: Elige su rol.<br/>Then: No se le permite registrarse porque su correo ya está en la base de datos.                                                                                                                                                                                                                                                                                                                                             |EP001|
|US002|Iniciar sesión| 	Como usuario quiero ingresar a mi cuenta para utilizar la plataforma                                                                                    | Escenario 1: Ingreso a la cuenta<br/>Given: El usuario está registrado.<br/>When: El usuario ingresa su correo y contraseña.<br/>Then: Ingresa con éxito a su cuenta.<br/><br/>Escenario 2: Ingreso a la cuenta incorrecto<br/>Given: El usuario está registrado.<br/>When: El usuario ingresa su correo y/o contraseña incorrecta.<br/>Then: No se permite el ingreso.<br/><br/>Escenario 3: Recuperación de contraseña<br/>Given: El usuario está registrado.<br/>When: El usuario ingresa su correo<br/>And: No recuerda su contraseña.<br/>Then: Se muestra un mensaje de recuperación de contraseña.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |EP001|
|US003|Cerrar sesión| 	Como usuario quiero cerrar mi sesión para mantener mis datos seguros.                                                                                   | Escenario 1: Cierre de Sesión Exitoso<br/>Given: El usuario está utilizando la plataforma.<br/>When: El usuario decide cerrar sesión.<br/>And: confirma su decisión.<br/>Then: La sesión se cierra exitosamente.<br/><br/>Escenario 2: Interrupción del Cierre de Sesión<br/>Given: El usuario está utilizando la plataforma.<br/>When: El usuario decide cerrar sesión, pero luego cambia de opinión.<br/>Then: La sesión actual sigue abierta sin cerrarse.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |EP001|
|US016|Visualizar las reseñas a los asesores| 	Como usuario estudiante quiero leer las opiniones de otros estudiantes para encontrar un asesor confiable.                                              | Escenario 1: Ver reseñas<br/>Given: El usuario está interesado en consultar las reseñas de un asesor en particular.<br/>When: El usuario busca las reseñas de ese asesor en su perfil.<br/>Then: Se despliega una lista de reseñas junto con las calificaciones proporcionadas por otros usuarios.<br/><br/>Escenario 2: Asesor sin reseñas<br/>Given: El usuario desea ver las reseñas de un asesor.<br/>When: El usuario accede al perfil del asesor, pero este no tiene reseñas disponibles.<br/>Then: Se le indica que el asesor no cuenta con reseñas hasta el momento.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |EP006|
|US018|Cambiar plan de suscripción| 	Como usuario estudiante quiero modificar mi plan de suscripción de acuerdo con mis necesidades para acceder a los beneficios de la aplicación.          | Escenario 1: Seleccionar otro plan de suscripción<br/>Given: El usuario desea cambiar su plan de suscripción actual por otro.<br/>When: Selecciona un nuevo plan de suscripción y acepta los términos y condiciones.<br/>And: Completa sus datos personales y de métodos de pago.<br/>Then: Se envía un mensaje de confirmación a su correo.<br/><br/>Escenario 2: Cancelar el cambio de plan de suscripción<br/>Given: El usuario desea cambiar su plan de suscripción.<br/>When: Inicia el proceso de cambio de plan, decide cancelarlo.<br/>Then: Anula la operación.<br/>And: Se regresa a la pantalla principal.<br/><br/>Escenario 3: Seleccionar el mismo plan de suscripción<br/>Given: El usuario quiere cambiar su plan de suscripción actual.<br/>When: Elige el mismo plan que ya tenía.<br/>Then: No procede la solicitud de cambio.                                                                                                                                                                                                                                                      |EP005|

A continuación, se presenta las imágenes de las User Stories y los Epics en Pivotal Tracker, dos componentes esenciales para la gestión ágil de proyectos, como parte de nuestro informe.

*Imagen de los User Stories en Pivotal Tracker*

<a href="https://imgbb.com/"><img src="https://i.ibb.co/QD5ZxDv/Screenshot-2023-09-24-195309.png" alt="Screenshot-2023-09-24-195309" border="0"></a>
<a href="https://imgbb.com/"><img src="https://i.ibb.co/FJCg02h/Screenshot-2023-09-24-195333.png" alt="Screenshot-2023-09-24-195333" border="0"></a>
<a href="https://imgbb.com/"><img src="https://i.ibb.co/ZhnmTm1/Screenshot-2023-09-24-195500.png" alt="Screenshot-2023-09-24-195500" border="0"></a>

*Imagen de los Epics en Pivotal Tracker*

<a href="https://imgbb.com/"><img src="https://i.ibb.co/Jk4jNjp/Screenshot-2023-09-24-200156.png" alt="Screenshot-2023-09-24-200156" border="0"></a>

## 3.3. Impact Mapping

En esta sección se desarrolla una comprensión más profunda de como los objetivos resultan ser claves y necesarios para lograr el éxito del proyecto. Además, se muestra una representación visual del impact mapping con ayuda de la herramienta UXPressia con la finalidad de facilitar la visualización de los business goals, personas, impacts, deliverables y los user stories que se relacionan.

**Segmento asesor**

<a href="https://ibb.co/kyQFmDf"><img src="https://i.ibb.co/CthFP9Z/Impact-map-1-1.png" alt="Impact-map-1-1" border="0"></a>

**Segmento estudiante**

<a href="https://ibb.co/DrsZhHR"><img src="https://i.ibb.co/J309Vws/Impact-map-1-2.png" alt="Impact-map-1-2" border="0"></a>

## 3.4. Product Backlog

En esta sección, se presenta el Product Backlog de Arquimentor, que incluye una lista priorizada de User Stories con sus títulos, descripciones y asignación de Story Points. Estas historias de usuario representan las funcionalidades clave que se desarrollarán en la plataforma, y el equipo las abordará siguiendo su prioridad y complejidad. Este Product Backlog es esencial para guiar el desarrollo de la plataforma según las necesidades de nuestros usuarios y los objetivos del proyecto.

| # Orden | User Story ID | Título                                                  | Descripción	                                                                                                                                              | Story Point (1/2/3/5/8)  |
|---------|--------|---------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------|
| 1       | US019  | 	Conocer a Arquimentor a través del landing page        | 	Como visitante del landing page quiero conocer a Arquimentor para reforzar mi confianza en la plataforma.	                                               | 8                        |
| 2       | US024  | 	Configurar la Base de Datos                            | Como desarrollador, quiero configurar una base de datos para almacenar información de usuarios y propiedades.                                             | 8                        |
| 3       | US006  | 	Búsqueda de asesor                                     | 	Como usuario estudiante quiero buscar a un asesor para que me oriente en mi proyecto.	                                                                   | 5                        |
| 4       | US010  | 	Recibir, aceptar o rechazar una solicitud de un estudiante | 	Como usuario asesor quiero recibir una solicitud y poder aceptar o rechazar para enseñar y orientar a un estudiante.                                     | 	5                       |
| 5       | US011  | 	Programar reuniones	                                   | Como usuario estudiante quiero programar las reuniones con el asesor para que me oriente y me de feedback. 	                                              | 5                        |
| 6       | US020  | Reconocer las ventajas de Arquimentor a través del landing page | 	Como visitante del landing page quiero conocer las ventajas de la plataforma para saber si se ajusta a lo que necesito.	                                 | 5                        |
| 7       | US021  | 	Diseñar la Interfaz de Usuario                         | Como desarrollador, quiero diseñar una interfaz de usuario atractiva y fácil de usar para una experiencia agradable.                                      | 5                        |
| 8       | US025  | 	Optimizar el Rendimiento de la Aplicación              | Como desarrollador, quiero optimizar el rendimiento de la aplicación para una experiencia rápida y fluida.                                                | 5                        |
| 9       | US004  | Subir proyectos	                                        | Como usuario estudiante quiero subir mis proyectos actuales y pasados para encontrar al asesor que más se adapte a mi perfil.                             | 	3                       |
| 10      | 	US009 | 	Enviar una solicitud a un asesor                       | 	Como usuario estudiante quiero enviar una solicitud a un asesor para que me oriente con mi proyecto.	                                                    | 3                        |
| 11      | 	US013 | 	Registrar el avance del proyecto	                      | Como usuario asesor quiero medir el avance del proyecto para tener un control de cada estudiante.	                                                        | 3                        |
| 12      | 	US022 | 	Funcionalidad de Búsqueda Avanzada                     | Como desarrollador, quiero desarrollar la funcionalidad de búsqueda avanzada con filtros.                                                                 | 3                        |
| 13      | 	US023 | 	Sistema de Autenticación y Registro                    | Como desarrollador, quiero implementar un sistema de autenticación y registro.                                                                            | 3                        |
| 14      | 	US005 | 	Subir Curriculum Vitae	                                | Como usuario asesor quiero subir mi CV para que los estudiantes me conozcan mejor y confíen en mi experiencia.	                                           | 2                        |
| 15      | 	US007 | 	Filtrar la búsqueda de asesor                          | 	Como usuario estudiante quiero filtrar la búsqueda de asesor para encontrar al asesor que más se ajuste a mis horarios y necesidades                     | 	2                       |
| 16      | 	US008 | 	Visualizar perfiles de asesores                        | 	Como usuario estudiante quiero ingresar al perfil de los asesores para conocer su trayectoria.                                                           | 2                        |
| 17      | 	US012 | 	Visualizar las reuniones programadas	                  | Como usuario asesor quiero tener mis reuniones programadas en una agenda para ser más eficiente.	                                                         | 2                        |
| 18      | 	US014 | 	Visualizar los avances del proyecto	                   | Como usuario estudiante quiero visualizar los avances y el feedback recibido para conocer el estado de mi proyecto.	                                      | 2                        |
| 19      | 	US015 | 	Calificar a un asesor	                                 | Como usuario estudiante quiero calificar al asesor que me orientó para compartir mi experiencia con otros usuarios.	                                      | 2                        |
| 20      | 	US017 | 	Seleccionar un plan de suscripción	                    | Como usuario estudiante quiero seleccionar un plan de suscripción que se adecue a mis necesidades para acceder a otras funcionalidades de la plataforma.	 | 2                        |
| 21      | US001  | Registrar cuenta                                        | Como usuario quiero crear una cuenta para poder acceder a la plataforma.                                                                                  | 	1                       |
| 22      | 	US002 | 	Iniciar sesión 	                                       | Como usuario quiero ingresar a mi cuenta para utilizar la plataforma.                                                                                     | 	1                       |
| 23      | 	US003 | 	Cerrar sesión	                                         | Como usuario quiero cerrar mi sesión para mantener mis datos seguros.	                                                                                    | 1                        |
| 24      | 	US016 | 	Visualizar las reseñas a los asesores.                 | 	Como usuario estudiante quiero leer las opiniones de otros estudiantes para encontrar un asesor confiable.	                                              | 1                        |
| 25      | 	US018 | 	Cambiar plan de suscripción	                           | Como usuario estudiante quiero modificar mi plan de suscripción de acuerdo con mis necesidades para acceder a los beneficios de la aplicación. 	          | 1                        |

*Imagen del Product Backlog en Pivotal Tracker*

<a href="https://imgbb.com/"><img src="https://i.ibb.co/QD5ZxDv/Screenshot-2023-09-24-195309.png" alt="Screenshot-2023-09-24-195309" border="0"></a>

Enlace: https://www.pivotaltracker.com/n/projects/2675481


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

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1156410791612919878/image.png?ex=6514def9&is=65138d79&hm=fd8e19d9d737c418aa9789594172a543e15cf3a9ab3cd5896d70f0a39f039c71&" alt="desktop-web-browser-header">

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

<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1156411080722096179/image.png?ex=6514df3e&is=65138dbe&hm=350efdfbff498c4ef33cdc3afba9987f08173b97711ae0605b5bbf2bab66dce1&" alt="mobile-web-browser-header">

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
## 4.4 Web Applications UX/UI Design.

### 4.4.1. Web Applications Wireframes 

Los wireframes de aplicaciones web para "Arquimentor" es una herramienta esencial en el proceso de diseño, ayudando a planificar la estructura y la disposición de elementos en la interfaz de usuario de manera eficiente y efectiva, lo que contribuye a la creación de una aplicación web atractiva y funcional para el servicio de bares.

<img src="https://cdn.discordapp.com/attachments/1149549726748921939/1149581858053574776/image.png" alt="desktop-web-browser-us">
<img src="https://cdn.discordapp.com/attachments/1149549726748921939/1149582981854400604/image.png" alt="desktop-web-browser-us">
<img src="https://cdn.discordapp.com/attachments/1149549726748921939/1149586040579969024/image.png" alt="desktop-web-browser-us">
<img src="https://cdn.discordapp.com/attachments/1149549726748921939/1149586058040852500/image.png" alt="desktop-web-browser-us">
<img src="https://cdn.discordapp.com/attachments/1149549726748921939/1149586398064685187/image.png" alt="desktop-web-browser-us">

### 4.4.2. Web Applications Wireflow Diagrams.

Los Wireflow Diagrams son una herramienta valiosa para planificar y visualizar la experiencia del 
usuario en una aplicación web de servicios de bares. Ayudan a garantizar que la navegación sea fluida,
las interacciones sean intuitivas y los usuarios puedan llevar a cabo tareas de manera eficiente 
dentro de la aplicación, contribuyendo a una experiencia de usuario positiva.

<img src="https://cdn.discordapp.com/attachments/1149549726748921940/1149598827356115005/image.png" alt="desktop-web-browser-us">
<img src="https://cdn.discordapp.com/attachments/1149549726748921940/1149598899003203585/image.png" alt="desktop-web-browser-us">
<img src="https://cdn.discordapp.com/attachments/1149549726748921940/1149599038644162592/image.png" alt="desktop-web-browser-us">
<img src="https://cdn.discordapp.com/attachments/1149549726748921940/1149599086534729778/image.png" alt="desktop-web-browser-us">
<img src="https://cdn.discordapp.com/attachments/1149549726748921940/1149599131833208832/image.png" alt="desktop-web-browser-us">

### 4.4.3. Web Applications Mock-ups.

Estas representaciones visuales son un paso crucial en el proceso de diseño antes de la implementación real, ayudando a garantizar que la interfaz sea atractiva, funcional y satisfactoria para los usuarios.

<img src="https://cdn.discordapp.com/attachments/1149549726748921939/1149587356706410567/image.png" alt="desktop-web-browser-us">
<img src="https://cdn.discordapp.com/attachments/1149549726748921939/1149587534565888070/image.png" alt="desktop-web-browser-us">
<img src="https://cdn.discordapp.com/attachments/1149549726748921939/1149587587485401088/image.png" alt="desktop-web-browser-us">
<img src="https://cdn.discordapp.com/attachments/1149549726748921939/1149587648151834665/image.png" alt="desktop-web-browser-us">
<img src="https://cdn.discordapp.com/attachments/1149549726748921939/1149587767186178049/image.png" alt="desktop-web-browser-us">

### 4.4.4. Web Applications User Flow Diagrams.

Estos diagramas permiten diseñar una experiencia de usuario fluida y eficiente, garantizando que los usuarios puedan navegar fácilmente por la aplicación para satisfacer sus necesidades de búsqueda y orden en establecimientos de bares.

<img src="https://cdn.discordapp.com/attachments/1149549726748921940/1149598363151499334/image.png" alt="desktop-web-browser-us">
<img src="https://cdn.discordapp.com/attachments/1149549726748921940/1149598454050463815/image.png" alt="desktop-web-browser-us">
<img src="https://cdn.discordapp.com/attachments/1149549726748921940/1149598625782038588/image.png" alt="desktop-web-browser-us">
<img src="https://cdn.discordapp.com/attachments/1149549726748921940/1149598678965821491/image.png" alt="desktop-web-browser-us">
<img src="https://cdn.discordapp.com/attachments/1149549726748921940/1149598735018512454/image.png" alt="desktop-web-browser-us">
<img src="https://cdn.discordapp.com/attachments/1149549726748921940/1149598776617611375/image.png" alt="desktop-web-browser-us">

## 4.5. Web Applications Prototyping

El prototipo del servio web viene a representar la versión más avanzada de los Mock-Ups con interactividad con el usuario, permitiendo presionar múltiples opciones con distintas funcionalidades
<img src="https://cdn.discordapp.com/attachments/1149549726748921939/1149621747222597642/image.png" alt="desktop-web-browser-us">
Link para el Aplicativo Web: https://www.figma.com/file/3tMZHofVJ936HBpiZAAxJf/Mockup-Web-Design-(ArquiMentor)?type=design&node-id=0-1&mode=design&t=Kti0KTQ7Yu07UXoM-0

## 4.6 Domain-Driven Software Architecture:

### 4.6.1 Software Architecture Context Diagram
<p align ="center">
   <img src="https://media.discordapp.net/attachments/1149549726748921942/1149634473428795502/structurizr-85951-Contexto.png?width=557&height=676" >
</p>

### 4.6.2 Software Architecture Container Diagram
<p align ="center">
   <img src="https://media.discordapp.net/attachments/1149549726748921942/1149634473139376158/structurizr-85951-Contenedor.png?width=521&height=676" >
</p>


## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams

<a href="https://ibb.co/PTBsW62"><img src="https://i.ibb.co/rbnKpwB/Clase-UML.png" alt="Clase-UML" border="0"></a>

### 4.7.2. Class Dictionary

#### Entidades del diagrama de clases:

**Class: Appointment (Cita)**

Esta clase representa una cita entre un estudiante y un mentor de arquitectura.

**Atributos:**

- **Time: Hora de la cita.**

- **Date: Fecha de la cita.**

- **Price: Precio de la cita.**

- **Meeting: Detalles de la cita**

**Class: Materials (Materiales)**

Esta clase representa los materiales utilizados en proyectos de arquitectura.

**Atributos:**

- **Name: Nombre o título del material.**

- **Price: Precio del material.**

- **Stock: Stock de los material.**

**Class: Adviser (Mentor o Asesor)**

Esta clase representa a los mentores o asesores en arquitectura disponibles para brindar orientación a los estudiantes.

**Atributos:**

- **CV: CV del mentor.**

- **Appointment: Cita del mentor con el estudiante.**

**Class: Student (Estudiante de Arquitectura)**

Esta clase representa a los mentores o asesores en arquitectura disponibles para brindar orientación a los estudiantes.

**Atributos:**

- **Address: Dirección del estudiante.**

- **Appointment: Cita del mentor con el estudiante.**

**Class: StudentProjectInfo (Información del proyecto)**

Esta entidad registra información de los proyectos realizados por el estudiante

**Atributos:**

- **Score: Avance del proyecto.**

- **Meeting: Detalles de la cita del mentor con el estudiante.**

**Class: Stores (Tiendas)**

Esta clase representa las tiendas que venden materiales de arquitectura.

**Atributos:**

- **Name: Nombre de la tienda.**

- **Location: Locación de la tienda.**

## 4.8. Database Design

### 4.8.1. Database Diagram
<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1156410043848204289/image.png?ex=6514de47&is=65138cc7&hm=d4bd3db87c47f689e40cb464b640c9bbba0bb4c811f4dc2d2dffe30be409250e&">



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

## 5. Capítulo V: Product Implementation, Validation & Deployment

### 5.1.1. Software Development Environment Configuration.
**Project Management:**

- Google Meet: es una aplicación web gratuita en la que los usuarios se pueden comunicar con llamada de voz, mensajería y cámara web. (Enlace de la app: https://meet.google.com)

- WhatsApp: es una aplicación de mensajería instantánea para teléfonos. Los usuarios se pueden comunicar con llamadas de voz, mensajería, chatear, mensajes de voz y videollamadas. (Enlace de la app: https://www.whatsapp.com)

**Requirements Management:**

-Markdown: lenguaje de marcado ligero que trata de conseguir la máxima legibilidad y facilidad de publicación tanto en su forma de entrada como de salida. (Enlace de la app: https://markdown.es/)

**ProductUX/UI Design:**

- Figma: es una aplicación web de diseño e editor de gráficos vectorial, con una gran variedad de herramientas de diseño, creación de prototipos y generación de código. Así mismo, con estas características y herramientas apoyan a los usuarios en la creación de sus proyectos. (Enlace de la app: https://www.figma.com)

**Software Development:**

- Visual Studio Code: es un editor de código fuente desarrollado por Microsoft. Así mismo, tiene una buena integración con Git, cuenta con soporte para depuración de código, y dispone de un sinnúmero de extensiones, que te da la posibilidad de escribir y ejecutar código en cualquier lenguaje de programación. (Enlace de la app: https://code.visualstudio.com)

- IntelliJ IDEA: es un entorno de desarrollo integrado para el desarrollo de programas informáticos. Es desarrollado por JetBrains, y está disponible en dos ediciones: edición para la comunidad​ y edición comercial. (Enlace de la app: https://www.jetbrains.com/idea/)

**Software Testing:**

- Lenguaje Gherkin: es un lenguaje específico de dominio diseñado en concreto para resolver un problema muy específico. El problema que quiere solucionar Gherkin es un problema de comunicación entre los perfiles de negocio y los perfiles técnicos a la hora de trabajar bajo un enfoque BDD.

### 5.1.2. Source Code Management.

Nosotros usaremos la metodología de Git Flow el cual es un modelo de Git branching(creación de ramas). El propósito de esto es para tener una rama Main el cual es donde nosotros tenemos nuestro html,css e imágenes. La segunda rama la cual tendrá los criterios de aceptación a realizar, con nuestros epics adjuntos para poder guiarnos y mejorar el trabajo. Nosotros escogimos GitHub porque es una de las páginas de código más reconocidas en todo el mundo lo cual nos da bastante seguridad, mejor organización y aparte vamos a poder seguir actualizando nuestro código a lo largo del tiempo

Enlace del repositorio GitHub:

https://github.com/Open-Developers-SW51/upc-pre-202302-SI729-SW51-ArquiMentor-report

### 5.1.3. Source Code Style Guide & Conventions

Para nuestro Style Guide & Conventions mostraremos y emplearemos elementos tradicionales de HTML con su estilo en CSS para poder editar a nuestra preferencia cada ítem en nuestra e nuestro Landing Page. En nuestra página se emplearon:


● Primero declaramos nuestro documento en HTML5

● El código fue hecho en español

● Al programar lo hacemos con minúsculas para evitar confusiones a la hora de usar las variables

● Tenemos un orden de nuestras variables finalizando todas

● Usamos comillas para especificar los atributos de manera ordenada

● Detallamos los tamaños de las imagen y sus respectivas posiciones

● Usamos la codificación UTF-8

● CSS(Lenguaje que es utilizado para diseñar y modificar la página web)

● Usaremos clases para poder llamar los atributos con mayor facilidad

● Se declaran las variables de formas individuales para tener mayor flexibilidad al hacer el diseño y usaremos variables juntas cuando su diseño sea igual

● usaremos comillas dobles al igual que en html

● Usaremos las comillas correctamente al realizar la programación para evitar confuciones

● Dejar espacios libres entre atributos o clases para tener un orden y que no se mezcle todo

● GitHub(es un sitio donde todos pueden publicar y editar los códigos de los demás para ser usado como almacenamiento de códigos, para ayudar a otras personas o para que otras personas te ayuden.)


### 5.1.4 Software Deployment Configuration

Como se ha mencionado previamente, la gestión de nuestro código fuente se llevará a cabo mediante GitHub. Además, haremos uso de GitHub Pages para la publicación y el despliegue de la página. Cada sección del Landing Page que hemos desarrollado deberá estar disponible en el siguiente enlace: https://open-developers-sw51.github.io/upc-pre-202302-SI729-SW51-ArquiMentor-landing-page/public/ 

En lo que respecta a la creación del Landing Page de ArquiMentor, hemos empleado las siguientes herramientas:

HTML: Este lenguaje de marcado se ha utilizado para estructurar nuestro Landing Page.
Evidencia: Los archivos HTML, siendo el principal denominado index.html, donde todos los miembros han integrado el contenido creado en sus respectivas ramas individuales.
<img src="https://media.discordapp.net/attachments/1149190528756363337/1149602952491835492/image.png?width=1440&height=238" alt="evidencia-html" >
Css: Es aquel que nos ayudó con el diseño gráfico para que el Landing Page sea agradable e interactúale. Evidencia: Se presenta el file styles.css, donde el grupo implemento el diseño de toda la estructura realizada con html. 
<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149607008304103434/image.png" alt="evidencia-css" >

JS: Nos ayudó a desarrollar la lógica necesaria para el Landing Page Evidencia: Se muestra el documento main.js.
<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149607779020050463/image.png" alt="evidencia-js" >
El despliegue del Landing Page de ArquiMentor no pudo ser posible sin utilizar las siguientes tecnologías: 

• Git: 
Sistema de control de versiones que está pensado en la eficiencia y compatibilidad de versiones. El cual nos ayudó a trabajar en equipo durante el desarrollo del Landing Page.

 • GitHub:
  Plataforma de desarrollo colaborativo.

•Git Flow: 
Nos permitió controlar el avance de cada uno de nuestros integrantes con respecto al desarrollo del Landing Page.

 • Git Hub Pages:
  Servicio de Github que nos permitió alojar nuestra Landing page.
  
Obtuvimos el siguiente enlace: https://open-developers-sw51.github.io/upc-pre-202302-SI729-SW51-ArquiMentor-landing-page/public/ 
Evidencia de Deployment
<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149604527352332349/image.png" alt="deployment" >
Se puede visualizar el link en la barra de búsqueda y que está en modo público desde un computador x. Se muestran las acciones realizadas en el github para el lanzamiento del Landing Page. 
<img src="https://cdn.discordapp.com/attachments/1149190528756363337/1149604423019024484/image.png" alt="github-actions" >

## 5.2. Landing Page, Services & Applications Implementation.

### 5.2.1. Sprint 1
|            Sprint #            |    Sprint 1    | | |||
|:------------------------------:|:----------:|:--:|:--:|:--:|:--:|
|  |  Work-Item / Task   |
|User Story ID| id |Description| Estimation(Hours) | Assigned To | Status(To-do/ In-Process/To-Review/Done)|
|US01 |T1 |Registrar cuenta |3 h |Leonardo Lopez| To do|
|US02 |T2 |Iniciar sesión |3 h |Diego Ramirez| To do|
|US03 |T3 |Cerrar sesión |3 h |Kurt Puican| To do|
|US04 |T4 |Subir proyectos |5 h |Leonardo Lopez| To do|
|US05 |T5 |Subir Curriculum Vitae |5 h |Yuliana Yauricasa| To do|
|US06 |T6 |Búsqueda de asesor |4 h |Yuliana Yauricasa| To do|
|US07 |T7 |Filtrar la búsqueda de asesor |5 h |Leonardo Lopez| To do|
|US08 |T8 |Visualizar perfiles de asesores |2 h |Rafael Luyo| To do|
|US09 |T9 |Enviar una solicitud a un asesor |3 h |Diego Ramirez| To do|
|US10 |T10 |Recibir, aceptar o rechazar una solicitud de un estudiante |5 h |Leonardo Lopez| To do|
|US11 |T11 |Programar reuniones |7 h |Rafael Luyo| To do|
|US12 |T12 |Visualizar las reuniones programadas |3 h |Kurt Puican| To do|
|US13 |T13 |Registrar el avance del proyecto |5 h |Diego Ramirez| To do|
|US14 |T14 |Visualizar los avances del proyecto |3 h |Rafael Luyo| To do|
|US15 |T15 |Calificar a un asesor |5 h |Yuliana Yauricasa| To do|
|US16 |T16 |Visualizar las reseñas a los asesores. |5 h |Leonardo Lopez| To do|
|US17 |T17 |Seleccionar un plan de suscripción |7 h |Kurt Puican| To do|
|US18 |T18 |Cambiar plan de suscripción |5 h |Rafael Luyo| To do|
|US19 |T19 |Conocer a Arquimentor a través del landing page |7 h |Yuliana Yauricasa| To do|
|US20 |T20 |Reconocer las ventajas de Arquimentor a través del landing page |9 h |Leonardo Lopez| To do|