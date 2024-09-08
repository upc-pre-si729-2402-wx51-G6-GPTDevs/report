# <center>COURSE PROJECT</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software - 2024-2</strong><br>
    <strong>Desarrollo de Aplicaciones Open Source - WX51</strong><br>
    <strong>Profesor: Alberto Wilmer Sanchez Seña</strong><br>
    <br><strong>Informe del Trabajo Final</strong>
</p>

</p>

<p align="center">
    <strong>Startup: GPTDevs</strong><br>
    <strong>Producto: TaskLinker </strong>
</p>

<div style="text-align:center;">
    <h3>Team Members:</h3>
    <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td>Ramos Najar, Tony Alexander</td>
            <td>U20211A153</td>
        </tr>
        <tr>
            <td>Sanchez Rios, Camila Cristina</td>
            <td>U202210973</td>
        </tr>
        <tr>
            <td>Durand Vera, Gianfranco Angel</td>
            <td>U20201F640</td>
        </tr>
        <tr>
            <td>Chávarri Zarzosa, Daniel Jhared</td>
            <td>U202211108</td>
        </tr>
         <tr>
            <td>Roque Tello, Jack Eddie</td>
            <td>U20221C448</td>
         </tr>
    </table>
</div>

<p align="center">
    <strong>Agosto, 2024</strong>
</p>
<br>

<h1 align="center">Registro de versiones del Informe</h1>
</br>
<table>
        <thead>
            <tr>
                <th>Versión</th>
                <th>Fecha</th>
                <th>Autor</th>
                <th>Descripción de modificaciones</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <th>TB1</th>
                <td>20/08/2024</td>
                <td>
                    <ul>
          <li>Tony Ramos</li>
          <li>Camila Sanchez</li>
          <li>Gianfranco Durand</li>
          <li>Daniel Chávarri</li>
          <li>Jack Roque</li>
                    <ul>
           </td>
      <td>            
             <ul>
          <li>Capítulo I: Introducción</li>
          <li>Capítulo II: Requirements Elicitation & Analysis</li>
          <li>Capítulo III: Requirements Specification</li>
          <li>Capítulo IV: Product Design</li>
          <li>Avance del Capítulo V: Product Implementation, Validation & Deployment hasta el punto 5.2.1.8</li>
          <li>Avance de Conclusiones, Bibliografía y Anexos</li>
        </ul>
      </td>
  </tr>
</tbody>
</table>

# Project Report Collaboration Insights

# Contenido
[Student Outcome](#student-outcome)

[Capítulo I: Introducción](#capítulo-i-introducción)
- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2 Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

[Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
- [2.1. Competidores](#21-competidores)
  - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
  - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-entrevistas)
  - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
  - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
  - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
  - [2.3.1. User Personas](#231-user-personas)
  - [2.3.2. User Task Matrix](#232-user-task-matrix)
  - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
  - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [2.4. Ubiquitous Language](#24-ubiquitous-language)

[Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

[Capítulo IV: Product Design](#capítulo-iv-product-design)
- [4.1. Style Guidelines](#41-style-guidelines)
  - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
  - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
- [4.2. Information Architecture](#42-information-architecture)
  - [4.2.1. Organization Systems](#421-organization-systems)
  - [4.2.2. Labeling Systems](#422-labeling-systems)
  - [4.2.3. SEO Tags and Meta Tag](#423-seo-tags-and-meta-tag)
  - [4.2.4. Searching Systems](#424-searching-systems)
  - [4.2.5. Navigation Systems](#425-navigation-systems)
- [4.3. Landing Page UI Design](#43-landing-page-ui-design)
  - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
  - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
- [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
  - [4.4.1. Web Applications Wireframes](#411-general-style-guidelines)
  - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
  - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
  - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
- [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
- [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
  - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
  - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
  - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
- [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
  - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.7.2. Class Dictionary](#472-class-dictionary)
- [4.8. Database Design](#48-database-design)
  - [4.8.1. Database Diagram](#481-database-diagram)

[Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
- [5.1. Software Configuration Management](#51-software-configuration-management)
  - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
  - [5.1.2. Source Code Management](#512-source-code-management)
  - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
  - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
  - [5.2.X. Sprint ](#52x-sprint)
    - [5.2.X.1. Sprint Planning n](#52x1-sprint-planning-n)
    - [5.2.X.2. Sprint Backlog n](#52x2-sprint-backlog-n)
    - [5.2.X.3. Development Evidence for Sprint Review](#52x3-development-evidence-for-sprint-review)
    - [5.2.X.4. Testing Suite Evidence for Sprint Review](#52x4-testing-suite-evidence-for-sprint-review)
    - [5.2.X.5. Execution Evidence for Sprint Review](#52x5-execution-evidence-for-sprint-review)
    - [5.2.X.6. Services Documentation Evidence for Sprint Review](#52x6-services-documentation-evidence-for-sprint-review)
    - [5.2.X.7. Software Deployment Evidence for Sprint Review](#52x7-software-deployment-evidence-for-sprint-review)
    - [5.2.X.8. Team Collaboration Insights during Sprint](#52x8-team-collaboration-insights-during-sprint)
- [5.3. Validation Interviews](#53-validation-interviews)
  - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
  - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
  - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
- [5.4. Video About-the-Product](#54-video-about-the-product)

[Conclusiones](#conclusiones)
- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)

[Bibliografía](#bibliografía)

[Anexos](#anexos)

# Student Outcome
ABET – EAC - Student Outcome 3

Criterio: Capacidad de comunicarse efectivamente con un rango de audiencias

Criterio: Capacidad de comunicarse efectivamente con un rango de audiencias

<table>
  <tr>
    <td><b>Criterio específico</b></td>
    <td><b>Acciones realizadas</b></td>
    <td><b>Conclusiones</b></td>
  </tr>
    </thead>
  <tbody>
    <tr>
      <td><b>Comunica oralmente con
efectividad a diferentes rangos
de audiencia.</b></td>
      <td>
        <p><b>Ramos Najar, Tony Alexander  </b></p>
        <p><b>TB1:</b></p>
        <p>Capítulo II: Requirements Elicitation & Analysis y User Stories<br> Realicé un optimo trabajo en equipo, para crear, visualizar y corregir detalles importantes, además fui flexible con el tiempo de entrega de los capítulos</p>
        <p><b>TP1:</b></p>
        <p>.</p>
        <p><b>TB2:</b></p>
        <p>.</p>
        <p><b>TF:</b></p>
        <p>.</p>
        <p><b>Sanchez Rios, Camila Cristina</b></p>
       <p><b>TB1:</b></p>
        <p>Realicé el Capítulo III: Product Design y User Stories; también realicé lo sieguiente del Capítulo IV: 4.1. Style Guidelines, General Style Guidelines, Web Style Guidelines, Information Architecture, Organization Systems, Labeling Systems, SEO Tags and Meta Tags, Searching Systems, Navigation Systems, Landing Page UI Design, Landing Page Wireframe, Landing Page Mock-up, Web Applications UX/UI Design, Web Applications Wireframes, Web Applications Wireflow Diagrams, Web Applications Mock-ups, Web Applications User Flow Diagrams, Web Applications Prototyping.</p>
        <p><b>TP1:</b></p>
        <p>.</p>
        <p><b>TB2:</b></p>
        <p>.</p>
        <p><b>TF:</b></p>
        <p>.</p>
        <p><b>Durand Vera, Gianfranco Angel</b></p>
        <p><b>TB1:</b></p>
        <p>Capítulo IV: Product Design y User Stories <br>Coordiné y realicé la reunión inicial del proyecto, explicando claramente los objetivos y el plan de trabajo. Cree diferentes reuniones para clarificar los roles de cada integrante del equipo.      
        </p>
        <p><b>TP1:</b></p>
        <p>.</p>
        <p><b>TB2:</b></p>
        <p>.</p>
        <p><b>TF:</b></p>
        <p>.</p>
        <p><b>Chávarri Zarzosa, Daniel Jhared</b></p>
       <p><b>TB1:</b></p>
        <p>Capítulo III: Requirements Specification</p>
        <p><b>TP1:</b></p>
        <p>.</p>
        <p><b>TB2:</b></p>
        <p>.</p>
        <p><b>TF:</b></p>
        <p>.</p>
        <p><b>Roque Tello, Jack Eddie</b></p>
       <p><b>TB1:</b></p>
        <p>Capítulo I: Introducción y User Stories</p>
        <p><b>TP1:</b></p>
        <p>.</p>
        <p><b>TB2:</b></p>
        <p>.</p>
        <p><b>TF:</b></p>
        <p>.</p>
      </td>
      <td>
        <p><strong>TB1:</strong></p>
        <p>En conclusión, en esta primera entrega se logró una buena comunicación entre los miembros del equipo. Cada participante estuvo activo y presento sus ideas de manera que todos pudieran entenderse entre sí. Concluimos que aún hay pequeñas dificultades para expresarnos con todos, pero que se puede solucionar con tiempo.</p>
        <p><strong>TP1:</strong></p>
        <p>En resumen, .</p>
        <p><strong>TB2:</strong></p>
        <p>En conclusión, </p>
        <p><strong>TF:</strong></p>
        <p>En conclusión, .</p>
      </td>
    </tr>
    <tr>
      <td>Comunica por escrito con
efectividad a diferentes rangos
de audiencia.</td>
      <td>
        <p><b>Ramos Najar, Tony Alexander  </b></p>
        <p><b>TB1:</b></p>
        <p>Capítulo II: Requirements Elicitation & Analysis y User Stories<br> Realicé correctamente lo establecido para esta entrega, además apoyé en otras definiciones a mi team Collab</p>
        <p><b>TP1:</b></p>
        <p>.</p>
        <p><b>TB2:</b></p>
        <p>.</p>
        <p><b>TF:</b></p>
        <p>.</p>
        <p><b>Sanchez Rios, Camila Cristina</b></p>
       <p><b>TB1:</b></p>
        <p>Realicé el Capítulo III: Product Design y User Stories; también realicé lo sieguiente del Capítulo IV: 4.1. Style Guidelines, General Style Guidelines, Web Style Guidelines, Information Architecture, Organization Systems, Labeling Systems, SEO Tags and Meta Tags, Searching Systems, Navigation Systems, Landing Page UI Design, Landing Page Wireframe, Landing Page Mock-up, Web Applications UX/UI Design, Web Applications Wireframes, Web Applications Wireflow Diagrams, Web Applications Mock-ups, Web Applications User Flow Diagrams, Web Applications Prototyping.</p>
        <p><b>TP1:</b></p>
        <p>.</p>
        <p><b>TB2:</b></p>
        <p>.</p>
        <p><b>TF:</b></p>
        <p>.</p>
        <p><b>Durand Vera, Gianfranco Angel</b></p>
        <p><b>TB1:</b></p>
        <p>Capítulo IV: Product Design y User Stories <br>Cree repositorios para almacenar nuestro informe con un registro de versiones constante, además de comenzar un registro de los puntos que nos falta completar.
        </p>
        <p><b>TP1:</b></p>
        <p>.</p>
        <p><b>TB2:</b></p>
        <p>.</p>
        <p><b>TF:</b></p>
        <p>.</p>
        <p><b>Chávarri Zarzosa, Daniel Jhared</b></p>
       <p><b>TB1:</b></p>
        <p>Capítulo III: Requirements Specification</p>
        <p><b>TP1:</b></p>
        <p>.</p>
        <p><b>TB2:</b></p>
        <p>.</p>
        <p><b>TF:</b></p>
        <p>.</p>
        <p><b>Roque Tello, Jack Eddie</b></p>
       <p><b>TB1:</b></p>
        <p>Capítulo I: Introducción y User Stories</p>
        <p><b>TP1:</b></p>
        <p>.</p>
        <p><b>TB2:</b></p>
        <p>.</p>
        <p><b>TF:</b></p>
        <p>.</p>
      </td>
       <td>
        <p><strong>TB1:</strong></p>
        <p>Se participó equitativamente el informe. En conclusión, estamos en camino para desempeñarnos de manera equitativa en el trabajo.</p>
        <p><strong>TP1:</strong></p>
        <p>En resumen, .</p>
        <p><strong>TB2:</strong></p>
        <p>En conclusión, </p>
        <p><strong>TF:</strong></p>
        <p>En conclusión, .</p>
      </td>
    </tr>
  </tbody>
</table>

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
"TaskLinker" es una innovadora plataforma web que facilita la conexión entre personas que buscan ingresos adicionales laborando por horas y quienes requieren contratar servicios temporales o para tareas específicas. Dirigida a estudiantes, amas de casa, jubilados y cualquier persona interesada en trabajos por horas, TaskLinker actúa como un puente efectivo y confiable entre la oferta y la demanda en el mercado laboral peruano. A través de nuestra plataforma, tanto individuos como organizaciones pueden encontrar soluciones rápidas y eficientes para sus necesidades, optimizando el uso de la fuerza laboral disponible y promoviendo la flexibilidad en el empleo.

La misión de TaskLinker es empoderar a las personas con oportunidades de trabajo flexible, permitiéndoles generar ingresos adicionales en sus propios términos. Al mismo tiempo, buscamos proporcionar a las organizaciones e individuos una herramienta eficiente para encontrar y contratar rápidamente talento adecuado para sus necesidades temporales o específicas.

Nuestra visión es convertirnos en la plataforma líder en Perú para la contratación de trabajos por horas y servicios temporales, siendo reconocidos por nuestra capacidad para conectar de manera efectiva a las personas con oportunidades de ingresos adicionales. Aspiramos a expandir nuestro impacto, promoviendo un mercado laboral más dinámico, inclusivo y flexible, donde cada persona pueda acceder fácilmente a oportunidades laborales que se ajusten a su estilo de vida y necesidades, mientras que las organizaciones logran satisfacer sus demandas con rapidez y precisión.

### 1.1.2. Perfiles de integrantes del equipo
<table>
  <tr>
    <th>
      <img src="assets/TonyRamos.png" alt="Foto de perfil de Tony" width="800px">
    </th>
    <td valign="top">
      <p><b>Ramos Najar, Tony Alexander</b></p>
      <p>
        Mi nombre es Tony Ramos, estoy cursando el 8vo ciclo de la carrera de Ingeniería de Software. Me considero hábil en el ámbito de la programación en los lenguajes, Python, Javascript, y últimamente estoy aprendiendo Angular. Con respeto a mi, me considero una persona responsable, con ganas de aprender y superarme a mí mismo
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="assets/fotocam.png" alt="Foto de perfil de Camila" width="800px">
    </th>
    <td valign="top">
      <p><b>Sánchez Ríos, Camila Cristina</b></p>
      <p>
        Soy estudiante de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas, actualmente me encuentro en el cuarto ciclo. Me gusta escuchar música y leer en los ratos libres y aprender más sobre la carrera.
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="assets/franco.jpg" alt="Foto de perfil de Gianfranco" width="800px">
    </th>
    <td valign="top">
      <p><b>Durand Vera, Gianfranco Ángel</b></p>
      <p>
        Soy estudiante de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas, actualmente me encuentro en el sexto ciclo, escogí esta carrera porque me gusta mucho la programación. Tengo experiencia en lenguajes de programación como C++, C#, Python, Kotlin y JavaScript.
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="assets/daniel.jpeg" alt="Foto de perfil de Daniel" width="800px">
    </th>
    <td valign="top">
      <p><b>Chávarri Zarzosa, Daniel Jhared</b></p>
      <p>
       Soy estudiante de la UPC, tengo 19 años. Estoy en la carrera de Ingeniería de Software, ya que, siempre me gustó la tecnología, los videojuegos, las páginas web, pero sobre todo cómo crearlos. Estoy cursando el 5 ciclo de la carrera y mis habilidades son C++, Python, HTML y JavaScript. También soy bueno en ser responsable con cada curso y organizar mi tiempo en ellos.
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="https://hackmd.io/_uploads/HyOVCdJ3C.jpg" alt="Foto de perfil de Jack" width="700px">
    </th>
    <td valign="top">
      <p><b>Roque Tello, Jack Eddie</b></p>
      <p>
        Mi nombre es Jack Eddie Roque Tello y tengo 20 años. Soy estudiante de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC) actualmente estoy en el quinto ciclo. Soy una persona competitiva, siempre en busca de nuevos aprendizajes, con un enfoque en la mejora continua. Tengo conocimientos en varios lenguajes de programación, incluyendo C++, JavaScript y Ruby.             <br>Fuera del ámbito académico, disfruto ver películas, leer y viajar, lo que me ayuda a expandir mis perspectivas y a mantener un equilibrio entre mis responsabilidades y mis pasiones. En este curso, estaré atento a cualquier eventualidad que surja, dispuesto a colaborar y aportar para el éxito del proyecto, siempre en beneficio de mi equipo y mi crecimiento profesional.
      </p>
    </td>
  </tr>
</table>
<br>

## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática
En el mercado laboral peruano, existe una creciente demanda de trabajos temporales y por horas, impulsada tanto por trabajadores que buscan flexibilidad como por empleadores que requieren soluciones rápidas para tareas específicas. No obstante, la falta de una plataforma centralizada ha dificultado la conexión eficiente entre ambas partes, lo que resulta en una subutilización del talento disponible y en procesos de contratación ineficaces.

**5W y 2H**

- **Who (Quién):** 

Los trabajadores objetivo de TaskLinker incluyen estudiantes, amas de casa, jubilados y personas con empleo parcial que buscan ingresos adicionales sin comprometer sus horarios. Por otro lado, los empleadores incluyen pequeñas y medianas empresas (PyMEs), particulares, organizadores de eventos, y startups que necesitan contratar personal temporal de manera rápida y eficiente.

- **What (Qué):**

TaskLinker es una plataforma web que facilita la conexión entre personas que buscan trabajo temporal por horas y empleadores que necesitan contratar servicios específicos. La plataforma ofrece una solución centralizada que permite a ambas partes encontrar rápidamente lo que necesitan, ya sea una oportunidad de trabajo flexible o personal temporal calificado.

- **Where (Dónde):**

La plataforma opera principalmente en el mercado laboral peruano, donde existe una alta demanda de trabajos temporales y por horas. TaskLinker está diseñada para ser accesible desde cualquier dispositivo con conexión a internet, lo que la hace disponible en cualquier lugar dentro del ámbito nacional.

- **When (Cuándo):**

La necesidad de TaskLinker surge en un contexto donde la economía y el mercado laboral están en constante cambio, con un aumento en la demanda de flexibilidad tanto por parte de trabajadores como de empleadores. Esta plataforma es especialmente útil en momentos de alta demanda laboral temporal, como durante eventos especiales o picos estacionales de trabajo.

- **Why (Por qué):**

La falta de una plataforma centralizada que conecte de manera efectiva a trabajadores temporales con empleadores ha llevado a una subutilización de la fuerza laboral disponible y a ineficiencias en el proceso de contratación. TaskLinker responde a esta problemática proporcionando una solución que simplifica y agiliza la búsqueda de trabajo temporal y la contratación de personal por horas, beneficiando a ambos lados del mercado.

-  **How (Cómo):**

TaskLinker funciona a través de una plataforma en línea intuitiva donde los trabajadores pueden crear perfiles, buscar y postularse a trabajos que se ajusten a sus habilidades y disponibilidad. Los empleadores pueden publicar tareas o proyectos específicos y acceder a una base de trabajadores calificados de manera rápida. La plataforma integra un sistema de evaluaciones y reputación para garantizar la confianza y transparencia en las interacciones. El modelo de negocio se sustenta en dos esquemas principales: una comisión por transacción, que se cobra cuando un trabajador es contratado y completa un trabajo, y un plan de suscripción premium, que elimina las comisiones y ofrece beneficios adicionales como priorización en los listados y acceso a tareas exclusivas.

- **How Much (Cuánto):**

En el esquema de comisión por transacción, TaskLinkera cobra una pequeña comisión proporcional al valor del trabajo, la cual se descuenta automáticamente una vez que el trabajo es completado y pagado. Por otro lado, el plan de suscripción premium tiene un costo fijo que elimina estas comisiones por transacción y brinda acceso a funcionalidades avanzadas, como la priorización en los listados, acceso a tareas exclusivas, y herramientas de gestión mejoradas. Este modelo de negocio está diseñado para ser accesible y rentable, permitiendo a los usuarios elegir la opción que mejor se adapte a sus necesidades y volumen de trabajo.

### 1.2.2 Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements

En el mercado laboral peruano, existe una desconexión significativa entre la oferta y la demanda de trabajos temporales y por horas. Por un lado, los trabajadores buscan flexibilidad para encontrar oportunidades que se ajusten a su disponibilidad. Por otro, los empleadores necesitan contratar personal de manera rápida y eficiente para tareas puntuales o picos de trabajo. Sin embargo, la falta de una plataforma centralizada que facilite esta conexión genera ineficiencias en ambos lados, creando barreras para la optimización del talento disponible y el acceso a oportunidades laborales.

Estudiantes, amas de casa, jubilados y personas con empleo parcial en Perú se enfrentan a un desafío constante: ¿cómo encontrar trabajos temporales o por horas que se ajusten a sus horarios y necesidades específicas? Actualmente, la falta de una plataforma centralizada y eficiente para acceder a estas oportunidades laborales limita su capacidad para generar ingresos adicionales, lo que lleva a una subutilización de su tiempo y potencial.  ¿Qué solución podría ofrecerse para permitirles encontrar trabajos de manera rápida y eficiente, maximizando su tiempo disponible?

La falta de un sistema eficiente que centralice estas oportunidades también deja en desventaja a los trabajadores que desean postularse a trabajos en los que tienen experiencia o competencias específicas. ¿Qué características debe tener una plataforma para asegurar que los trabajadores puedan filtrar y postularse solo a las oportunidades que realmente les interesan, sin comprometer su tiempo ni su disponibilidad para otras responsabilidades personales?

Pequeñas y medianas empresas (PyMEs), startups, organizadores de eventos y particulares en Perú se enfrentan a una necesidad urgente: ¿cómo contratar personal temporal para tareas específicas o picos de trabajo de manera rápida y efectiva? 

La falta de una solución adecuada provoca retrasos operativos, un aumento en los costos de contratación y una menor eficiencia en la gestión de recursos humanos. ¿Qué plataforma puede facilitar este proceso, reduciendo el tiempo de contratación y mejorando la eficiencia en la búsqueda de talento calificado? Además, ¿cómo se puede asegurar que los empleadores puedan acceder a una base confiable de trabajadores con las habilidades necesarias para sus tareas específicas sin incurrir en largos procesos de selección?

#### 1.2.2.2. Lean UX Assumptions
**Business Outcomes:**

1. Si ofrecemos una plataforma fácil de usar con un proceso de registro rápido y accesible, más trabajadores potenciales (estudiantes, amas de casa, jubilados) se inscribirán y utilizarán la plataforma para obtener ingresos adicionales.
2.  Si proporcionamos un sistema eficiente para la contratación rápida y confiable de trabajadores temporales, los empleadores recurrirán a la plataforma para cubrir tareas específicas de manera recurrente.
3.  Si simplificamos el proceso de contratación y comunicación entre empleadores y trabajadores, el número de trabajos realizados a través de la plataforma aumentará.
4.  Si mejoramos las herramientas de búsqueda y filtrado, los empleadores podrán encontrar candidatos adecuados de manera más eficiente.
5.  Si ofrecemos características premium valiosas como eliminación de comisiones, acceso a tareas exclusivas y visibilidad prioritaria, más usuarios optarán por suscribirse al plan premium.
6.  Si implementamos un sistema de evaluación transparente y confiable, tanto trabajadores como empleadores tendrán más confianza al usar la plataforma, lo que aumentará la satisfacción general.
7.  Si notificamos a los trabajadores de nuevas oportunidades relevantes para sus habilidades, aumentaremos su participación activa en la plataforma.
8.  Si lanzamos campañas de marketing dirigidas a nuevas regiones, podemos atraer a trabajadores y empleadores de otras ciudades, ampliando nuestro alcance geográfico.
9.  Si mejoramos la facilidad y seguridad en los métodos de pago, aumentará la confianza y la velocidad en las transacciones entre empleadores y trabajadores.
10. Si facilitamos la interacción entre los usuarios (trabajadores y empleadores) a través de herramientas de mensajería y soporte, mejoraremos la percepción de confianza y colaboración en la plataforma.

#### 1.2.2.3. Lean UX Hypothesis Statements

**Hipótesis 1:**

Creemos que si proporcionamos un proceso de registro rápido y fácil para los trabajadores, aumentará la tasa de inscripción en la plataforma. Sabremos que esto es verdad cuando veamos un  aumento del 25% en las inscripciones de nuevos usuarios dentro de los primeros 3 meses de optimizar el proceso de registro.

**Hipótesis 2:**

Creemos que las personas en Perú (estudiantes, amas de casa, jubilados, etc.) tienen dificultades para encontrar trabajos flexibles y por horas que se ajusten a sus necesidades y horarios. Si ofrecemos una plataforma que centraliza la oferta y demanda de trabajos por horas, las personas podrán encontrar oportunidades laborales de forma rápida y fácil. Observaremos un aumento en el número de personas registradas y en la frecuencia con la que encuentran trabajo a través de la plataforma.

**Hipótesis 3:**

Creemos que las pequeñas y medianas empresas (PyMEs) en Perú necesitan contratar servicios temporales de manera eficiente, pero enfrentan dificultades en el proceso de búsqueda y contratación. Si proporcionamos una plataforma donde puedan publicar tareas y contratar trabajadores de forma rápida, las PyMEs podrán cubrir sus necesidades temporales sin problemas. Veremos una alta tasa de satisfacción entre los empleadores y un aumento en el número de tareas publicadas en la plataforma.

**Hipótesis 4:**

Creemos que muchos usuarios en Perú valoran la flexibilidad y desean acceder a una plataforma gratuita para comenzar a trabajar inmediatamente. Si ofrecemos una opción gratuita con comisiones por tarea realizada y un plan premium que elimina esas comisiones, los usuarios podrán empezar a trabajar sin barreras económicas. Tendremos una alta conversión de usuarios del plan gratuito al plan premium a medida que generen más ingresos.

**Hipótesis 5:**

Creemos que un sistema de evaluaciones y reseñas mejorará la confianza entre empleadores y trabajadores, lo que resultará en más transacciones exitosas. Sabremos que esto es verdad cuando veamos un incremento en las evaluaciones en un 30% más de trabajos finalizados con reseñas positivas dentro del primer año de implementación del sistema de evaluaciones.

#### 1.2.2.4. Lean UX Canvas

<img src="assets/canva2.png">
*Imagen (N°1). Elaboración propia. Realizado en Canva*

## 1.3. Segmentos objetivo
**1. Trabajadores que buscan ingresos adicionales y flexibilidad:**
Este segmento incluye a estudiantes que necesitan ingresos para cubrir sus estudios o gastos personales sin afectar sus horarios académicos, amas de casa que desean contribuir económicamente sin comprometer sus responsabilidades en el hogar, jubilados que buscan mantenerse activos y generar ingresos extra, y personas con empleo parcial que desean complementar sus ingresos. Todos ellos valoran la flexibilidad que les ofrece TaskLinker, permitiéndoles encontrar oportunidades laborales que se adapten a su tiempo y necesidades específicas.

**2. Empleadores que requieren soluciones laborales temporales:**

Este segmento abarca a pequeñas y medianas empresas (PyMEs) que necesitan personal temporal para cubrir picos de trabajo o tareas específicas, particulares que requieren servicios domésticos, reparaciones, o tareas puntuales sin compromiso a largo plazo, organizadores de eventos que necesitan personal por horas para diferentes funciones como catering o atención al cliente, y startups que demandan flexibilidad en la contratación para adaptarse al ritmo dinámico de su crecimiento. Estos empleadores buscan soluciones rápidas, confiables y eficientes para satisfacer sus necesidades laborales temporales.


# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores
Comprender el panorama competitivo es crucial para el éxito de TaskLinker. En esta sección, identificaremos y describiremos a nuestros principales competidores directos e indirectos que operan en el ámbito de la gestión de deudas y la educación financiera. Analizaremos sus modelos de negocio, estrategias de marketing, productos y servicios, y los canales de distribución que utilizan. Además, realizaremos un análisis comparativo detallado de sus fortalezas, debilidades, oportunidades y amenazas (SWOT) en relación con TaskLinker. Este análisis nos permitirá entender mejor el entorno competitivo y ajustar nuestras estrategias para maximizar nuestra ventaja en el mercado.
### 2.1.1. Análisis competitivo

- **Bumeran**

Bumeran es una de las principales bolsas de trabajo en América Latina, con una fuerte presencia en países como Argentina, México, Perú y otros. La plataforma facilita la búsqueda de empleo en diversas categorías, incluyendo trabajos temporales y por horas.

[Bumeran Perú](https://www.bumeran.com.pe/)

- **Computrabajo**

Computrabajo es una de las bolsas de trabajo más grandes en América Latina, con una sólida presencia en Perú y otros países de la región. La plataforma ofrece una amplia gama de empleos, incluidos trabajos temporales y por horas

[Computrabajo](https://pe.computrabajo.com/)

- **Indeed**

Indeed es una plataforma global de búsqueda de empleo que agrega ofertas de trabajo de diversas fuentes, incluyendo bolsas de trabajo, sitios de empresa y anuncios clasificados. Fundada en 2004, Indeed se ha consolidado como uno de los motores de búsqueda de empleo más grandes del mundo, con una presencia significativa en numerosos países, incluyendo Perú y América Latina.

[Indeed](https://pe.indeed.com/)

#### **Comparativa con Competidores**

|               | TaskLinker                                                     | Bumeran                                                          | Computrabajo                                                      | Indeed                                                            |
|---------------|----------------------------------------------------------------|------------------------------------------------------------------|-------------------------------------------------------------------|-------------------------------------------------------------------|
| **Perfil**    | Plataforma web que conecta a personas que buscan ingresos adicionales con quienes necesitan contratar servicios temporales o específicos. | Bolsa de trabajo líder en América Latina con una amplia base de datos de empleos. | Bolsa de trabajo con fuerte presencia en Perú y otros países de América Latina. | Motor de búsqueda de empleo global con presencia significativa en América Latina. |
| **Overview**  | Facilita la conexión entre individuos interesados en trabajos por horas y organizaciones que requieren servicios temporales. | Plataforma que facilita la búsqueda y publicación de empleos en diversas categorías, incluyendo trabajos temporales y por horas. | Plataforma que ofrece una variedad de empleos, desde trabajos permanentes hasta temporales y por horas. | Agrega ofertas de empleo de diversas fuentes y permite buscar y aplicar a trabajos en una amplia gama de categorías. |
| **Ventaja competitiva** ¿Qué valor ofrece a los clientes? | Especialización en trabajos por horas y temporales, facilitando la conexión directa entre oferta y demanda. | Amplia red de usuarios y empleadores en varios países de América Latina, con una variedad de empleos disponibles. | Herramientas efectivas para empleadores y candidatos con una fuerte presencia local en Perú. | Búsqueda integral de empleos con una amplia base de datos y la capacidad de aplicar a trabajos globalmente. |
| **Perfil de Marketing** |                                                                  |                                                                  |                                                                   |                                                                   |
| **Mercado objetivo** | Estudiantes, amas de casa, jubilados y personas interesadas en trabajos por horas en Perú. | Empresas y candidatos en busca de empleos temporales y por horas en América Latina. | Empresas y candidatos en Perú buscando empleos temporales y por horas. | Candidatos y empleadores globales y locales en busca de una amplia gama de oportunidades laborales. |
| **Estrategias de Marketing** | Promoción a través de redes sociales y colaboraciones con instituciones educativas y organizaciones locales. | Publicidad en medios digitales y colaboraciones con empresas de recursos humanos y consultoras. | Marketing digital enfocado en la búsqueda de empleo local y colaboración con empresas. | Publicidad en línea y optimización para motores de búsqueda, así como herramientas avanzadas para empleadores. |
| **Perfil de Producto** |                                                                  |                                                                  |                                                                   |                                                                   |
| **Productos y Servicios** | Plataforma para encontrar y ofrecer trabajos temporales y por horas, con herramientas de gestión para empleadores y candidatos. | Publicación de ofertas de empleo, búsqueda y filtrado de trabajos en varias categorías. | Publicación de ofertas de empleo, herramientas de gestión para empleadores y alertas de empleo. | Agregación de ofertas de empleo, herramientas para publicación y promoción de anuncios, y recursos adicionales para candidatos. |
| **Precios y Costos** | Modelos de suscripción para empresas y opciones de publicación para trabajos específicos. | Precios varían según el tipo de publicación y servicios adicionales. | Costos para publicación de ofertas y servicios premium para empresas. | Costos de patrocinio de anuncios y servicios premium para empleadores. |
| **Canales de Distribución** | Página web. | Página web, aplicaciones móviles. | Página web, aplicaciones móviles. | Página web, aplicaciones móviles. |
| **Análisis FODA** |                                                                  |                                                                  |                                                                   |                                                                   |
| **Fortalezas** | Especialización en trabajos por horas y temporales, facilitando una conexión directa y eficiente. | Amplia cobertura en América Latina y variedad de empleos disponibles. | Fuerte presencia local en Perú con herramientas efectivas para búsqueda de empleo. | Amplia base de datos global y funcionalidad avanzada para la búsqueda y aplicación de empleos. |
| **Debilidades** | Limitada cobertura comparada con competidores más grandes; dependencia en la adopción local. | Competencia elevada y falta de especialización en trabajos por horas. | Competencia elevada y falta de especialización en nichos específicos. | Alta competencia global y menos enfoque en trabajos temporales específicos. |
| **Oportunidades** | Expansión en el mercado de trabajos temporales en Perú y potencial de crecimiento en América Latina. | Expansión en el mercado de trabajos temporales y por horas en América Latina. | Oportunidades para mejorar la especialización en trabajos temporales y por horas. | Expansión de servicios y optimización para la búsqueda de trabajos específicos por horas y temporales. |
| **Amenazas** | Competencia de plataformas globales y locales que ofrecen servicios similares. | Plataformas globales y locales que ofrecen servicios similares. | Competencia de otras bolsas de trabajo locales y globales. | Competencia de plataformas globales con amplias bases de datos y funcionalidades avanzadas. |

### 2.1.2. Estrategias y tácticas frente a competidores

Para destacar frente a la competencia, TaskLinker se enfocará en proporcionar una visibilidad clara y accesible de oportunidades laborales flexibles, ofrecer un modelo de remuneración competitivo para atraer tanto a trabajadores como a empleadores, colaborar con instituciones y organizaciones locales para ampliar su alcance, resaltar las ofertas más recientes y relevantes en la plataforma, y garantizar la confianza y transparencia mediante un sistema robusto de calificaciones y reseñas.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

**Preguntas para el segmento objetivo 1: Trabajadores que buscan ingresos adicionales y flexibilidad**

1. ¿Qué tipo de trabajos por horas te interesan más y por qué? <br>
Objetivo: Identificar las preferencias y áreas de interés laboral.

2. ¿Cuántas horas a la semana estás dispuesto/a a trabajar y qué horarios te resultan más convenientes? <br>
Objetivo: Entender la disponibilidad y flexibilidad.

3. ¿Qué factores consideras más importantes al elegir un trabajo por horas? <br>
Objetivo: Conocer los criterios clave en la toma de decisiones laborales.

4. ¿Has utilizado anteriormente plataformas similares para encontrar trabajos por horas? Si es así, ¿qué te gustó o no te gustó de ellas? <br>
Objetivo: Evaluar la experiencia previa y expectativas sobre plataformas de empleo.

5. ¿Qué tipo de apoyo o recursos te gustaría recibir de una plataforma de trabajos por horas para facilitar tu búsqueda de empleo? <br>
Objetivo: Identificar necesidades adicionales que podrían mejorar la experiencia.

6. ¿Cuáles son tus principales preocupaciones o desafíos al buscar trabajos por horas? <br>
Objetivo: Detectar barreras o problemas comunes en la búsqueda de empleo.

7. ¿Qué tan importante es para ti la posibilidad de calificar y dejar reseñas sobre las oportunidades laborales y empleadores? <br>
Objetivo: Evaluar la importancia de la transparencia y el feedback en la plataforma.

<br>

**Preguntas para el segmento objetivo 2: Empleadores que requieren soluciones laborales temporales**

1. ¿Qué tipo de servicios temporales o especializados sueles necesitar con mayor frecuencia? <br>
Objetivo: Identificar los tipos de servicios más demandados.

2. ¿Qué criterios utilizas para seleccionar a un trabajador o proveedor de servicios temporales? <br>
Objetivo: Comprender los factores clave en la selección de proveedores de servicios.

3. ¿Cuál es tu experiencia previa al contratar servicios temporales a través de plataformas digitales? ¿Qué aspectos fueron positivos o negativos? <br>
Objetivo: Obtener información sobre experiencias pasadas y expectativas sobre la plataforma.

4. ¿Qué nivel de flexibilidad esperas en cuanto a horarios y disponibilidad de los trabajadores que contratas?<br>
Objetivo: Entender las expectativas de flexibilidad y adaptabilidad.

5. ¿Qué importancia le das a la capacidad de revisar perfiles y leer reseñas antes de contratar a alguien?<br>
Objetivo: Evaluar la relevancia de la transparencia y la información de la plataforma.

6. ¿Qué problemas o desafíos has enfrentado al contratar servicios temporales y cómo te gustaría que una plataforma los resolviera?<br>
Objetivo: Identificar problemas comunes y posibles soluciones que la plataforma podría ofrecer.

7. ¿Cómo prefieres gestionar el proceso de contratación y pago (por ejemplo, a través de la plataforma, de forma directa, etc.)?<br>
Objetivo: Entender las preferencias en la gestión de la contratación y los pagos.

### 2.2.2. Registro de entrevistas 

**Segmento objetivo perteneciente: Trabajadores que buscan ingresos adicionales y flexibilidad**

**Entrevista #1**
- Nombre: Sebastian Silva
- Edad: 19 años
- Duracion de la entrevista: 5:50 minutos

![image](assets/Entrevista1.png)

[Entrevista 1 - video:](https://bit.ly/4dHXCYk) https://bit.ly/4dHXCYk

Resumen:

Sebastián Silva es un estudiante de ingeniero de software y tiene 20 años, debido a que actualmente se encuentra estudiando una carrera universitaria, Sebastián preferiblemente está decidido a buscar un trabajo part-time, para que no se descuide del estudio y pueda ganar experiencia siempre y cuando hayan vacantes de puestos de trabajos en el ámbito de su carrera, está dispuesto a trabajar mínimo 48 horas a la semana full time, y mínimo 24 horas part-time a la semana, considera que el factor mas importante es la actividad a realizar para ver si es conveniente con respecto a la paga, además tiene claro de que no debe arriesgar a aceptar un trabajo sobrexplotado para ganar muy menos de lo remunerado, le gustaría recibir ayuda de una sitio web especial encargado de búsqueda de trabajos por horas, además de la ubicación que sea cercana a su residencia actual. Le preocupa que al no laburar en un lugar tan céntrico, no exista un ámbito agradable y que se encuentre lejos de su hogar. Por ultimo, a él le fascina las opiniones, por ende necesita ver reseñas de una determinada aplicación o sitio web para poder confiar

**Entrevista #2**

- Nombre: Emilio Chávarri
- Edad: 54 años
- Duración de la entrevista: 3:24 minutos

![image](assets/Emilio.JPG)

[Entrevista 2 - video](https://shorturl.at/amDex): https://shorturl.at/amDex

Resumen:

Emilio Chávarri, un trabajador que busca ingresos adicionales, nos cuenta que los tipos de trabajos que más le interesan son de diseño de trabajo de plano y seguridad electrónica. Las horas con las que está dispuesto a trabajar a la semana es alrededor de 20 horas, los fines de semana a tiempo completo y en las noches. Los factores importantes al momento de elegir un horario por servicio es el horario a realizar el servicio. El tipo de apoyo que le gustaría recibir de una plataforma de trabajo por hora o servicio para facilitar la búsqueda de empleo es la geolocalización del sitio donde se va a hacer el trabajo como Google Maps. A su vez, las principales precauciones al buscar trabajo por horas o servicios sería el tiempo y el lugar en que se va a realizar. Finalmente, considera muy importante porque las personas pueden dar fé de que es un aplicativo confiable, ya que al ingresar y ver un historial bueno de personas que recibieron o han dado el servicio ayuda a la aplicación y le da confianza de que es una aplicación seria.


**Entrevista #3**

- Nombre: Melanie Oliva
- Edad: 18 años
- Duración de la entrevista: 7:05

![image](assets/entrevista4.png)

[Entrevista 3 - video](https://shorturl.at/02cai): https://shorturl.at/02cai

Resumen:

En la entrevista, Melanie Oliva, un estudiante de 18 años en cuarto ciclo de ingeniería de sistemas, expresa interés en trabajos por horas, especialmente en el área de niñera, debido a su afinidad con los niños y su deseo de ayudarlos en su aprendizaje. Prefiere trabajar en las tardes, con un máximo de cinco horas por semana, ya que tiene clases por la mañana y compromisos universitarios. Entre sus preocupaciones, menciona la necesidad de flexibilidad horaria y la dificultad de encontrar plataformas que ofrezcan trabajos por horas. Valora herramientas de búsqueda que filtren opciones según su disponibilidad y ocupación, así como la posibilidad de dejar reseñas sobre empleadores para ayudar a otros estudiantes.

**Segmento objetivo perteneciente: Empleadores que requieren soluciones laborales temporales**

**Entrevista #4**
- Nombre: Sandy Ingaruca
- Edad: 19 años
- Duración de la entrevista: 5:42

![image](assets/Entrevista2.png)

[Entrevista 4 - video](https://shorturl.at/q2F6e): https://shorturl.at/q2F6e

Resumen:

Sandy Ingaruca, empleadora, necesita con frecuencia servicios temporales de soporte administrativo como digitación de datos y atención al cliente durante temporadas altas, personal para eventos corporativos (asistentes logísticos, técnicos de sonido e iluminación), y trabajadores especializados en limpieza profunda o mantenimiento para proyectos específicos. Al seleccionar trabajadores, prioriza la experiencia comprobable, la flexibilidad horaria, la disponibilidad inmediata, y las reseñas positivas de otros empleadores. Su experiencia con plataformas digitales ha sido mixta: valora la facilidad y agilidad del proceso, pero ha enfrentado problemas como la falta de verificación de habilidades y cambios de última hora en la disponibilidad del personal. La flexibilidad es esencial, ya que necesita trabajadores dispuestos a trabajar en horarios no convencionales y a aceptar tareas con poca antelación. También otorga gran importancia a la revisión de perfiles detallados y reseñas antes de contratar. Entre los desafíos enfrentados, menciona la inconsistencia en la calidad del trabajo y la dificultad para gestionar cambios de última hora, por lo que preferiría que la plataforma ofreciera garantías de calidad y opciones de reemplazo. Además, prefiere gestionar la contratación y el pago completamente a través de la plataforma para garantizar seguridad y simplificación del proceso administrativo.

**Entrevista #5**
- Nombre: Monica Garcia
- Edad: 29 años
- Duración de la entrevista: 7:53

![image](assets/monica.png)

[Entrevista 5 - video:](https://shorturl.at/eM4S4) https://shorturl.at/eM4S4

Resumen:

Mónica García, de 29 años, trabaja en el área de Recursos Humanos en una empresa de transporte. Frecuentemente necesita servicios temporales, como conductores con licencia A3C para mover buses a talleres, personal para el comedor, y apoyo administrativo durante operaciones importantes. Al seleccionar trabajadores, Mónica prioriza competencias específicas, como la licencia adecuada para los conductores y estudios universitarios en el caso del personal administrativo. Su experiencia contratando a través de redes sociales ha sido poco efectiva, ya que no ha logrado cubrir la demanda de personal. Mónica considera que una plataforma digital podría facilitar la contratación de personal temporal. Para ella, es fundamental revisar perfiles detallados y reseñas antes de tomar una decisión. Entre los principales retos que ha enfrentado están la falta de personal disponible y los retrasos en las operaciones debido a la escasez de trabajadores. Mónica valora la flexibilidad en los horarios y prefiere gestionar tanto la contratación como el pago a través de la plataforma, buscando una solución más ágil y eficiente.

**Entrevista #6**
- Nombre: Estrella Ticona
- Edad: 19 años
- Duración de la entrevista: 3:35 minutos

 ![image](assets/entrevista6.png)

[Entrevista 5 - video:](https://bit.ly/3ZgruXh) https://bit.ly/3ZgruXh

Resumen:
La persona entrevistada, de 19 años y residente en el distrito de Rímac, menciona que suele contratar servicios temporales, especialmente en áreas técnicas y administrativas, para proyectos específicos o campañas. Los criterios que utiliza para seleccionar a los proveedores incluyen la experiencia previa, referencias, cumplimiento de plazos y una buena comunicación. Aunque su experiencia con plataformas digitales ha sido mayormente positiva, ha enfrentado problemas con la inconsistencia en la calidad del trabajo. Valora la flexibilidad horaria según el proyecto y considera esencial la capacidad de revisar perfiles y reseñas antes de contratar. Sugiere mejoras en la resolución de disputas y en el control de calidad, y prefiere gestionar los pagos a través de las plataformas para mayor seguridad.

### 2.2.3. Análisis de entrevistas

**Segmento objetivo perteneciente:** Trabajadores que buscan ingresos adicionales y flexibilidad

- **Flexibilidad Horaria:** Todos los entrevistados resaltan la necesidad de flexibilidad horaria, ya sea por motivos académicos o personales. Esto resalta la importancia de que TaskLinker facilite la búsqueda de trabajos que se ajusten a horarios específicos.
- **Reseñas y Confianza:** La confianza en la plataforma y los empleadores es clave. Un sistema robusto de reseñas será fundamental para atraer y retener usuarios.
- **Ubicación del Trabajo:** La proximidad del trabajo a la residencia del trabajador es un factor importante, por lo que sería beneficioso integrar herramientas de geolocalización.
- **Diversidad de Ofertas:** Los entrevistados tienen intereses laborales muy diversos, lo que sugiere la importancia de contar con una amplia gama de categorías de trabajo, desde tecnología hasta servicios personales.

**Segmento objetivo perteneciente:** Empleadores que requieren soluciones laborales temporales

- **Necesidad de flexibilidad:** Todas las personas entrevistadas valoran la flexibilidad en los horarios y disponibilidad del personal temporal según el proyecto. Los servicios requeridos abarcan tanto tareas especializadas como administrativas, lo que requiere personal adaptable.
- **Valoración de la experiencia y reseñas:** La revisión de perfiles detallados y las reseñas de otros empleadores son factores clave en la selección de trabajadores. Esta evaluación previa ofrece confianza en el proceso de contratación.
- **Preferencia por plataformas digitales:** Aunque las experiencias con plataformas digitales son mixtas, todas coinciden en que facilitan el acceso a trabajadores, aceleran el proceso de contratación y ofrecen seguridad en la gestión de pagos.
- **Inconsistencia en la calidad:** Un problema recurrente es la inconsistencia en la calidad del trabajo entregado. Todos los entrevistados sugieren que las plataformas deberían mejorar el control de calidad y ofrecer más garantías.
- **Gestión del proceso de contratación:** Los entrevistados prefieren gestionar tanto la contratación como el pago a través de las plataformas, ya que esto ofrece mayor seguridad, transparencia y simplicidad en el proceso administrativo.


## 2.3. Needfinding

### 2.3.1. User Personas
Para esta sección se han creado personajes ficticios, cada uno diseñado para representar a un segmento específico de usuarios. La información utilizada para desarrollar estos "User personas" proviene de entrevistas previas realizadas a cada segmento objetivo. Estas entrevistas tenían como objetivo comprender mejor a las personas a las que se dirige la aplicación. Se consideraron datos demográficos, metas, motivaciones frustraciones, marcas relacionadas con el tema de la aplicación canales digitales más utilizados, entre otros. 

**Segmento Objetivo: Trabajadores que buscan ingresos adicionales**

![image](assets/SebastiánSilva.png)
*Imagen (N°2). Elaboración propia. Realizado en UXPRESSIA*

**Segmento Objetivo: Empleadores que requieren soluciones laborales temporales** 

![image](assets/ValeriaGonzáles.png)
*Imagen (N°3). Elaboración propia. Realizado en UXPRESSIA*

### 2.3.2. User Task Matrix
En esta sección se presenta el user task matrix, herramienta centrada en los segmentos objetivos, que nos permitirá identificar las tareas y objetivos claves de los usuarios. Además, nos permitirá priorizar características y funcionalidades al momento de realizar el product backlog. Para la frecuencia se han considerado cinco opciones:nunca ,casi nunca, a veces, a menudo ,siempre; y para la importancia tres opciones: bajo, medio, alto". En relación con la matriz de tareas de los usuarios, podemos identificar tanto las tareas de mayor frecuencia como las de mayor importancia, así como las diferencias y similitudes entre los diferentes tipos de usuarios.

**Segmento Objetivo: Trabajadores que buscan ingresos adicionales**

| **User Tasks**                                              | **Prioridad** | **Frecuencia** | **Contexto de Uso**                                             | **Notas**                                                                 |
|-------------------------------------------------------------|---------------|----------------|------------------------------------------------------------------|----------------------------------------------------------------------------|
| **Buscar trabajos de medio tiempo relacionados con su carrera** | Alta          | Frecuente       | En su laptop o móvil, principalmente en su tiempo libre o fines de semana. | Sebastián está constantemente buscando oportunidades que le permitan obtener experiencia relevante sin interferir con sus estudios. |
| **Filtrar ofertas de trabajo por ubicación cercana**        | Alta          | Frecuente       | Al utilizar plataformas de búsqueda de empleo.                   | Prefiere trabajar cerca de su hogar para evitar largos desplazamientos.   |
| **Consultar reseñas de empleos o empleadores**              | Alta          | Frecuente       | Antes de postularse a un empleo, ya sea desde su laptop o móvil. | Confía en las opiniones de otros para asegurarse de que el lugar de trabajo tiene buenas condiciones y ambiente. |
| **Postularse a empleos**                                    | Media         | Ocasional       | Después de haber revisado y seleccionado una oferta adecuada.    | Solo aplica a empleos que cumplen con sus criterios de ubicación, horas y reseñas positivas. |
| **Comparar la remuneración ofrecida con el esfuerzo requerido** | Alta          | Ocasional       | Al revisar una oferta de trabajo.                                | Sebastián evalúa si la paga justifica el esfuerzo y las horas que dedicará al trabajo. |
| **Guardar trabajos interesantes para revisarlos más tarde** | Media         | Ocasional       | Cuando encuentra varias ofertas que le parecen interesantes.     | Le gusta guardar opciones para evaluar con calma y tomar una decisión informada. |
| **Configurar alertas para nuevas ofertas de trabajo**       | Baja          | Ocasional       | Cuando se inscribe en una plataforma de búsqueda de empleo.      | Le gustaría recibir notificaciones de nuevas ofertas que se ajusten a sus criterios. |
| **Investigar más sobre la empresa contratante**             | Media         | Ocasional       | Antes de aplicar o aceptar una oferta de trabajo.                | Quiere asegurarse de que la empresa tiene una buena reputación y ofrece un ambiente laboral saludable. |

**Segmento Objetivo: Empleadores que requieren soluciones laborales temporales**

| **User Task**                                            | **Prioridad** | **Frecuencia** | **Contexto de Uso**                                                                                     | **Notas**                                                                                                                                                    |
|----------------------------------------------------------|---------------|----------------|----------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Buscar trabajadores temporales calificados**           | Alta          | Alta           | Al inicio de cada temporada alta, evento o proyecto específico.                                           | Valeria usa plataformas digitales para filtrar candidatos por experiencia, habilidades y reseñas; necesita verificación de habilidades más rigurosa.           |
| **Contratar y coordinar personal temporal**              | Alta          | Alta           | Después de identificar candidatos potenciales; importante durante la planificación de eventos o picos de trabajo. | Requiere una plataforma que permita la coordinación eficiente de detalles como horarios y expectativas. Le gustaría tener opciones para manejar cambios inesperados. |
| **Gestionar pagos y evaluar el servicio**                | Media         | Media          | Una vez finalizado el servicio; crucial para garantizar calidad y eficiencia en los pagos.                 | Valeria prefiere realizar pagos a través de la plataforma, pero necesita un sistema de pago que brinde seguridad ante insatisfacción con el servicio.          |
| **Planificar y ajustar la contratación según necesidades**| Media         | Media          | Durante la planificación de personal para diferentes proyectos o temporadas de trabajo.                    | Necesita una herramienta que facilite la previsión de necesidades y ajuste de contrataciones de forma ágil y flexible.                                        |
| **Evaluar y mejorar el proceso de contratación**         | Baja          | Baja           | Periódicamente, después de varias contrataciones o al final de una temporada alta o evento.                | Requiere tiempo para analizar el proceso de contratación y evaluar experiencias pasadas; prefiere que la plataforma ofrezca resúmenes automáticos y sugerencias.|
| **Monitorear el desempeño durante el servicio**          | Alta          | Media          | Durante la ejecución del servicio, especialmente en eventos o proyectos críticos.                          | Necesita herramientas de seguimiento y reportes en tiempo real para asegurar la calidad del trabajo y corregir problemas rápidamente.                         |
| **Manejar cancelaciones o cambios de última hora**       | Alta          | Media          | Cuando hay cancelaciones inesperadas o cambios en la disponibilidad de los trabajadores.                   | Le gustaría una funcionalidad que facilite la búsqueda rápida de reemplazos y notificaciones automáticas de cambios.                                           |
| **Mantener comunicación constante con los trabajadores** | Media         | Alta           | Durante la contratación y el desarrollo del servicio; importante para coordinación y aclaraciones.         | Valeria valora una comunicación fluida y rápida para evitar malentendidos y asegurar que se cumplan los requisitos del trabajo.                               |
| **Gestionar documentación y contratos**                  | Media         | Baja           | Al contratar trabajadores y al finalizar proyectos; necesario para temas legales y administrativos.         | Necesita funcionalidades en la plataforma que permitan manejar documentación de contratos de forma segura y accesible.                                        |
| **Realizar reportes y análisis post-evento o temporada** | Baja          | Baja           | Al finalizar una temporada alta o evento; útil para planificar futuras contrataciones y mejoras.            | Valeria busca herramientas de análisis y reportes detallados que faciliten la evaluación del desempeño y eficiencia de los trabajadores.                      |

### 2.3.3. User Journey Mapping

En esta sección, explicaremos en detalle los user journey mapping para dos tipos de usuarios distintos: Empleadores que requieren soluciones laborales temporales y Trabajadores que buscan ingresos adicionales y flexibilidad. Estos mapas proporcionarán una visión exhaustiva de cómo cada segmento de usuario interactúa con la plataforma, desde su primer contacto hasta su uso continuo y el análisis de resultados. Mejoraremos la presentación de estos mapas, destacando las etapas clave y las necesidades específicas de cada usuario para garantizar una comprensión clara y concisa de su experiencia a lo largo de su viaje:

**Segmento Objetivo: Trabajadores que buscan ingresos adicionales** 

![image](assets/seg2Map.png)
*Imagen (N°4). Elaboración propia. Realizado en UXPRESSIA*

**Segmento Objetivo: Empleadores que requieren soluciones laborales temporales**

![image](assets/seg1Map.png)
*Imagen (N°5). Elaboración propia. Realizado en UXPRESSIA*

### 2.3.4. Empathy Mapping

**Segmento Objetivo: Trabajadores que buscan ingresos adicionales** 

![image](assets/EmpathySebastian.png)
*Imagen (N°6). Elaboración propia. Realizado en UXPRESSIA*

**Segmento Objetivo: Empleadores que requieren soluciones laborales temporales**

![image](assets/EmpathyValeria.png)
*Imagen (N°7). Elaboración propia. Realizado en UXPRESSIA*

### 2.3.5. As-is Scenario Mapping

**Segmento Objetivo: Trabajadores que buscan ingresos adicionales** 

![image](assets/AsIsSebastian.png)
*Imagen (N°8). Elaboración propia. Realizado en Miro*

**Segmento Objetivo: Empleadores que requieren soluciones laborales temporales**

![image](assets/AsIsValeria.png)
*Imagen (N°9). Elaboración propia. Realizado en Miro*

## 2.4. Ubiquitous Language

En esta sección se muestra el Ubiquitous Language, el cual es un lenguaje común que se utiliza en el desarrollo de software para garantizar una comunicación efectiva entre los miembros del equipo de desarrollo y los stakeholders. El Ubiquitous Language se basa en un conjunto de términos y conceptos compartidos que se utilizan de manera consistente en todo el proceso de desarrollo de software. A continuación, se presentan algunos términos y conceptos clave relacionados con TaskLinker:

1. **TaskLinker:**
Una plataforma web que conecta a personas que buscan ingresos adicionales laborando por horas con aquellos que necesitan contratar servicios temporales o para tareas específicas. Está dirigida al mercado laboral peruano, especialmente a estudiantes, amas de casa, jubilados y cualquier persona interesada en trabajos por horas.

2. **Task Seeker: (Buscador de Tareas):**
Individuos que buscan oportunidades de trabajo por horas para generar ingresos adicionales, ya sea para complementar sus ingresos actuales o para tener una mayor flexibilidad en su vida laboral.

3. **Task Provider: (Proveedora de Tareas):**
Organizaciones o individuos que necesitan contratar servicios temporales o tareas específicas, buscando soluciones rápidas y eficaces para satisfacer sus necesidades a corto plazo.

4. **Hourly Job: (Trabajo por Horas):**
Tareas o trabajos específicos que se remuneran por el tiempo dedicado, generalmente orientados a periodos cortos y de naturaleza temporal. Estas tareas pueden variar en duración y frecuencia según las necesidades del Task Provider

5. **Flexible Work: (Trabajo Flexible):**
Oportunidades laborales que permiten a los Task Seekers ajustar sus horarios y condiciones laborales según su disponibilidad y preferencias, ofreciendo un equilibrio entre vida personal y trabajo.

6. **Booking: (Reserva):**
El proceso mediante el cual los Task Providers seleccionan y reservan Task Seekers para realizar trabajos específicos, asegurando que el talento adecuado esté disponible cuando sea necesario.

7. **Review System: (Sistema de Reseñas):**
Una característica de TaskLinker que permite a los Task Seekers y Task Providers dejar opiniones y calificaciones sobre sus experiencias, ayudando a otros usuarios a tomar decisiones informadas al contratar o aceptar tareas.

8. **Transaction Fee: (Tarifa por Transacción):**
Una tarifa impuesta por TaskLinker a los Task Providers cada vez que se completa una tarea o se efectúa una contratación a través de la plataforma, garantizando un modelo de negocio sostenible.

9. **Commission Fee: (Tarifa de Comisión):**
Una tarifa aplicada por TaskLinker sobre los ingresos generados por los Task Seekers, asegurando una compensación justa por el uso de la plataforma y los servicios que ofrece.

10. **Job Matching: (Emparejamiento de Trabajos):**
El proceso mediante el cual TaskLinker conecta a los Task Seekers con los Task Providers de acuerdo con sus habilidades, disponibilidad y la naturaleza de las tareas ofrecidas, optimizando el proceso de contratación.

11. **Task Posting: (Publicación de Tareas):**
La acción de los Task Providers al listar tareas o trabajos disponibles en la plataforma, especificando los detalles y requisitos para atraer a los Task Seekers adecuados.
   
# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping
## 3.2. User Stories
## 3.3. Impact Mapping
## 3.4. Product Backlog

# Capítulo IV: Product Design
## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines
### 4.1.2. Web Style Guidelines
## 4.2. Information Architecture
### 4.2.1. Organization Systems
### 4.2.2. Labeling Systems
### 4.2.3. SEO Tags and Meta Tag
### 4.2.4. Searching Systems
### 4.2.5. Navigation Systems
## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
### 4.3.2. Landing Page Mock-up
## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.3. Web Applications Mock-ups
### 4.4.4. Web Applications User Flow Diagrams
## 4.5. Web Applications Prototyping
## 4.6. Domain-Driven Software Architecture
### 4.6.1. Software Architecture Context Diagram
### 4.6.2. Software Architecture Container Diagrams
### 4.6.3. Software Architecture Components Diagrams
## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
### 4.7.2. Class Dictionary
## 4.8. Database Design
## 4.8.1. Database Diagram

# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
### 5.1.2. Source Code Management
### 5.1.3. Source Code Style Guide & Conventions
### 5.1.4. Software Deployment Configuration
## 5.2. Landing Page, Services & Applications Implementation
### 5.2.X. Sprint 
#### 5.2.X.1. Sprint Planning n
#### 5.2.X.2. Sprint Backlog n
#### 5.2.X.3. Development Evidence for Sprint Review
#### 5.2.X.4. Testing Suite Evidence for Sprint Review
#### 5.2.X.5. Execution Evidence for Sprint Review
#### 5.2.X.6. Services Documentation Evidence for Sprint Review
#### 5.2.X.7. Software Deployment Evidence for Sprint Review
#### 5.2.X.8. Team Collaboration Insights during Sprint
## 5.3. Validation Interviews
### 5.3.1. Diseño de Entrevistas
### 5.3.2. Registro de Entrevistas
### 5.3.3. Evaluaciones según heurísticas
# 5.4. Video About-the-Product

# Conclusiones
## Conclusiones y recomendaciones
## Video About-the-Team.

# Bibliografía

# Anexos
