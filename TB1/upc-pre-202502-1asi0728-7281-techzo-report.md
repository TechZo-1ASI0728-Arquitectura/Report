<div align="center">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/UPC_logo.png?raw=true" alt="Logo-UPC" width="150">

## Universidad Peruana de Ciencias Aplicadas

**Ingeniería de Software**

**Ciclo:** 2025-2

**Curso:** Arquitecturas De Software Emergentes (1ASI0728)

**Sección:** 7281

**Profesor:** Richard Leonardo Berrocal Nav

----
## Informe del Trabajo Final
### Nombre del Startup: TechZo

### Nombre Comercial: CambiaZo
#### Relación de integrantes 

| Integrante                  | Código         |
|---------------------------------|----------------|
| Huamani Mandujano, Joseph Alexis         | U20221A133     |
| Mendoza Carrion, Mathias Andre          | U202216282     |
| Quispe Andia, Jeremy Joel      | U202216279     |
| Criollo De La Cruz, Diego Anderson | u202219639     |
| Santisteban Palomino, Ian Haziel Donato | U202214059     |

</div>


<br><div align="center"><h3>Septiembre 2025</h3></div><br>


<div align="justify">

<div style="page-break-after: always;"></div>

# Registro de Versiones
<br>

| **Versión** | **Fecha** | **Autor** | **Descripción de modificación** |
| - | - | - | - |
|TB1|20/04/25|Ian Haziel Donato Santisteban Palomino, Claudio Sandro Quispesivana Torres, Joseph Alexis Huamani Mandujano, Jeremy Joel Quispe Andia y Mathias Andre Mendoza Carrion | Capítulo I: Introducción, Capítulo II: Requirements Elicitation & Analysis, Capítulo III: Requirements Specification, Capítulo IV: Product Design y Capítulo V: Product Implementation, Validation & Deployment|
|TP|14/05/25|Ian Haziel Donato Santisteban Palomino, Claudio Sandro Quispesivana Torres, Joseph Alexis Huamani Mandujano, Jeremy Joel Quispe Andia y Mathias Andre Mendoza Carrion | Capítulo VI: Product Verification & Validation y Capítulo VII: DevOps Practices|
|TB2|16/06/25|Ian Haziel Donato Santisteban Palomino, Claudio Sandro Quispesivana Torres, Joseph Alexis Huamani Mandujano, Jeremy Joel Quispe Andia y Mathias Andre Mendoza Carrion | Capítulo VI: Product Verification & Validation, Capítulo VII: DevOps Practices y Capítulo VIII: Experiment-Driven Development |
|TF|07/07/25|Ian Haziel Donato Santisteban Palomino, Claudio Sandro Quispesivana Torres, Joseph Alexis Huamani Mandujano, Jeremy Joel Quispe Andia y Mathias Andre Mendoza Carrion | Capítulo VIII: Experiment-Driven Development |

<br><br>

<div style="page-break-after: always;"></div>

# Contenido

- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la StartUp](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1 Lean UX Problem Statement](#1221-lean-ux-problem-statement)
      - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3 Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos Objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2 Entrevistas](#22-entrevistas)
    - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2 Registro de Entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2 User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
  
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Product Backlog](#33-product-backlog)
  - [3.4. Impact Mapping](#34-impact-mapping)

- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1 Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
    - [4.1.3. Mobile Style Guidelines](#413-mobile-style-guidelines)
      - [4.1.3.1. iOS Mobile Style Guidelines](#4131-ios-mobile-style-guidelines)
      - [4.1.3.2. Android Mobile Style Guidelines](#4132-android-mobile-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3 Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4 Mobile Applications UX/UI Design](#44-mobile-applications-uxui-design)
    - [4.4.1. Mobile Applications Wireframes](#441-mobile-applications-wireframes)
    - [4.4.2. Mobile Applications Wireflow Diagrams](#442-mobile-applications-wireflow-diagrams)
    - [4.4.3. Mobile Applications Mock-ups](#443-mobile-applications-mock-ups)
    - [4.4.4. Mobile Applications User Flow Diagrams](#444-mobile-applications-user-flow-diagrams)
  - [4.5. Mobile Applications Prototyping](#45-mobile-applications-prototyping)
    - [4.5.1. Android Mobile Applications Prototyping](#451-android-mobile-applications-prototyping)
    - [4.5.2. iOS Mobile Applications Prototyping](#452-ios-mobile-applications-prototyping)
  - [4.6. Web Applications UX/UI Design](#46-web-applications-uxui-design)
    - [4.6.1. Web Applications Wireframes](#461-web-applications-wireframes)
    - [4.6.2. Web Applications Wireflow Diagrams](#462-web-applications-wireflow-diagrams)
    - [4.6.3. Web Applications Mock-ups](#463-web-applications-mock-ups)
    - [4.6.4. Web Applications User Flow Diagrams](#464-web-applications-user-flow-diagrams)
  - [4.7. Web Applications Prototyping](#47-web-applications-prototyping)
  - [4.8. Domain-Driven Software Architecture](#48-domain-driven-software-architecture)
    - [4.8.1. Software Architecture Context Diagram](#481-software-architecture-context-diagram)
    - [4.8.2. Software Architecture Container Diagrams](#482-software-architecture-container-diagrams)
    - [4.8.3. Software Architecture Components Diagrams](#483-software-architecture-components-diagrams)
  - [4.9. Software Object-Oriented Design](#49-software-object-oriented-design)
    - [4.9.1. Class Diagrams](#491-class-diagrams)
    - [4.9.2. Class Dictionary](#492-class-dictionary)
  - [4.10. Database Design](#410-database-design)
    - [4.10.1. Relational/Non-Relational Database Diagram](#4101-relationalnon-relational-database-diagram)

- [Conclusiones](#conclusiones)
  - [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

<div align="justify">
	
<div style="page-break-after: always;"></div>

# Student Outcome

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:<br><br>
**ABET – EAC - Student Outcome 3**<br>
**Criterio:** Capacidad de comunicarse efectivamente con un rango de audiencias.
En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
del ABET – EAC - Student Outcome 3.<br><br>
En el siguiente cuadro se describen las acciones realizadas y las conclusiones enunciadas por el grupo, que permiten sustentar el logro del ABET – EAC - Student Outcome 3.<br><br>

<table>
  <thead>
    <tr>
      <th colspan="3"><b>Criterio específico</b></th>
      <th colspan="3"><b>Acciones realizadas</b></th>
      <th colspan="3"><b>Conclusiones</b></th>
    </tr>
  </thead>
  <tbody>
    <tr>
	<td colspan="3">Comunica oralmente sus ideas
y/o resultados con objetividad a
público de diferentes
especialidades y niveles
jerarquicos, en el marco del
desarrollo de un proyecto en
ingenierí</td>
      <td colspan="3" align = "justify">
      <h3>Joseph Alexis Huamani Mandujano</h3> 
        <b>TB1</b> 
        <p></p> 
      <h3>Mathias André Mendoza Carrión</h3>
        <b>TB1</b>
        <p></p>
      <h3>Ian Haziel Donato Santisteban Palomino</h3>
        <b>TB1</b>
        <p></p>
      <h3>Jeremy Joel Quispe Andia</h3>
        <b>TB1</b>
        <p></p>
      <h3>Diego Anderson Criollo De La Cruz</h3>
        <b>TB1</b>
        <p></p>
    <td colspan="3">
    <b>TB1</b>
    <p></p>
  </td>
    </tr>
    <tr>
      <td colspan="3">Comunica en forma escrita ideas
y/o resultados con objetividad a
público de diferentes
especialidades y niveles
jerarquicos, en el marco del
desarrollo de un proyecto en
ingeniería.</td>
      <td colspan="3" align = "justify">
      <h3>Joseph Alexis Huamani Mandujano</h3>
        <b>TB1</b>
        <p></p>
      <h3>Mathias André Mendoza Carrión</h3>
        <b>TB1</b>
        <p></p>
     <h3>Ian Haziel Donato Santisteban Palomino</h3>
        <b>TB1</b>
        <p></p>
      <h3>Jeremy Joel Quispe Andia</h3>
        <b>TB1</b>
        <p></p>
      <h3>Diego Anderson Criollo De La Cruz</h3>
        <b>TB1</b>
        <p></p>
    </td>
      <td colspan="3">
    <b>TB1</b>
    <p></p>
  </td>
    </tr>
  </tbody>
</table>

<div style="page-break-after: always;"></div>

<br><br>

# Capítulo I: Introducción


## 1.1 Startup Profile


### 1.1.1 Descripción de la Startup

**Nombre:**  TechZo

**Área:**  Innovación tecnológica y Reutilización

TechZo es una startup dedicada a la innovación tecnológica y la reutilización de recursos, fundada por un grupo de estudiantes comprometidos de la Facultad de Ingeniería de la Universidad Peruana de Ciencias Aplicadas (UPC). Nuestra misión es abordar desafíos críticos relacionados con la sostenibilidad y el consumo responsable, fomentando la transición hacia una economía circular en nuestro país. 

Nuestra principal solución, CambiaZo, es una aplicación web diseñada para transformar la forma en que las personas gestionan y comparten sus bienes. A través de CambiaZo, facilitamos el intercambio directo, seguro y sin transacciones monetarias de artículos entre usuarios, promoviendo la reutilización y el aprovechamiento óptimo de recursos disponibles. Además, la aplicación ofrece una funcionalidad especial que permite a los usuarios donar productos directamente a personas de bajos recursos, apoyando así a las comunidades más necesitadas. 

En TechZo, estamos comprometidos con la seguridad, transparencia y justicia en cada transacción. Trabajamos constantemente para garantizar que los usuarios tengan acceso a información clara y detallada sobre los productos disponibles, fomentando una experiencia de intercambio confiable y satisfactoria. Al combinar tecnología de vanguardia con un enfoque en la responsabilidad social, buscamos impulsar un cambio positivo en la forma en que consumimos y reutilizamos.

* **Misión:**<br>  La misión de TechZo como empresa es promover un estilo de vida sostenible y consciente, proporcionando a los usuarios una plataforma accesible y segura para intercambiar y donar bienes de manera justa y responsable. Buscamos reducir el impacto ambiental fomentando la reutilización, al tiempo que apoyamos a las comunidades más vulnerables a través de un modelo inclusivo de donaciones.<br><br>


* **Visión:** <br>
La visión de TechZo es convertirnos en la plataforma líder de intercambio y donación de productos básicos a nivel global. Queremos ser reconocidos por nuestra capacidad de conectar a las personas y comunidades, fomentando una economía circular que minimice el desperdicio y promueva la solidaridad. Aspiramos a liderar el camino hacia un futuro más sostenible, donde cada acto de intercambio y donación contribuya a un impacto ambiental positivo.<br><br>

* **Valores:**  

  *  **Seguridad y privacidad:** La privacidad es prioritaria, nos preocupamos para que nuestros usuarios sientan que los datos que nos otorgan están seguros y mantenidos en privacidad. Por ello, les otorgamos a nuestros usuarios control sobre ello. Además, sabemos que las medidas sólidas de seguridad, incluido el cifrado de datos en tránsito y reposo, junto con prácticas sólidas en el diseño de la base de datos, resguardan la información sobre nuestros usuarios.

  * **Innovación:** Estar en constante búsqueda de nuevas formas de mejorar la experiencia de los usuarios a través de la tecnología y la creatividad, manteniendo la aplicación a la vanguardia.

  * **Aprendizaje Continuo:** Fomentar un ambiente en el que los miembros del equipo estén dispuestos a aprender y mejorar constantemente, tanto en términos de sostenibilidad como de consumo responsable.

  * **Calidad:** Compromiso con la excelencia en el diseño de la aplicación movil y la funcionalidad de esta misma, asegurándonos de que cumpla con las expectativas más altas de nuestros usuarios.

  * **Compromiso con el usuario:** Poner las necesidades y deseos de los usuarios en el centro de todas las decisiones, asegurando que la aplicación satisfaga sus expectativas y mejore su experiencia realizando intercambios.

  * **Respeto a la diversidad:**  Valorar y respetar las diferencias culturales, étnicas, de género y de opinión, tanto en el equipo interno como en la comunidad de usuarios.<br><br>

 ### 1.1.2 Perfiles de integrantes del equipo

A continuación, presentaremos los perfiles de los integrantes del equipo encargado de desarrollar el proyecto. Cada uno de nuestros miembros aporta una combinación única de habilidades y perspectivas que son fundamentales para el éxito del proyecto.

| **Integrante**                         | **Perfil**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | **Imagen**                                                                                                       |
| -------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| **Huamani Mandujano, Joseph Alexis - u20221a133**             |Mi nombre es Joseph Huamani, soy estudiante de 8vo ciclo en la carrera de Ingeniería de Software en la UPC. Apasionado por el desarrollo web y web, cuento con experiencia usando lenguajes como C++, Python, Java, C#, Javascript y Typescript. Además cuento con experiencia en desarrollo web con HTML5 y CSS3 usando frameworks para frontend como Angular, VueJs, React y Astro. En cuanto al backend frameworks  como Spring Boot, .Net y Flask. Manejo de base de datos como MySQL, MSSQL, PostgreSQL, Oracle, SQLite y MongoDB. Soy una persona que trabaja en equipo, responsable y que brinda soluciones creativas para la resolución de problemas adquiridas gracias a la programación competitiva. Espero poder seguir aprendiendo nuevas tecnologias y poder culminar este curso de manera satisfactoria.| <img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/main/Resources/Chapter-I/Profiles/JosephHuamani.png?raw=true" alt="Imagen de Joseph Huamani" />|
| **Mendoza Carrión, Mathias André - u202216282** |Soy Mathias Andre Mendoza Carrión, un estudiante de 20 años de Ingeniería de Software en el octavo ciclo. Me caracterizo por ser organizado, trabajar bien en equipo y ser responsable. Actualmente, mi enfoque principal es el aprendizaje profundo y práctico en el desarrollo de software, con habilidades en lenguajes de programación como C++, Python, Java, C#, y JavaScript. También tengo conocimientos en frameworks como Angular y Vue, desarrollo web con HTML y CSS, así como en la gestión de bases de datos SQL y MongoDB. Aspiro a dominar nuevas tecnologías y comprender en detalle los principios fundamentales detrás del desarrollo de aplicaciones, con el objetivo de convertirme en un profesional capaz de crear soluciones innovadoras y eficientes en el campo del desarrollo de software.| <img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/main/Resources/Chapter-I/Profiles/MathiasMendoza.png?raw=true" alt="Imagen de Mathias Mendoza"/> |
| **Quispe Andia, Jeremy Joel - u202216279** |Mi nombre es Jeremy Joel Quispe Andia, soy estudiante de 8vo ciclo de la carrera de Ingeniería de Software. Tengo una gran pasión por la programación competitiva y aspiro a convertirme en desarrollador Full Stack. Me gusta emplear soluciones creativas y eficientes para abordar cualquier desafío de la mejor manera posible. Como miembro del grupo, pretendo aportar todos mis conocimientos en el desarrollo web. Además, siempre colaboro con ideas y soluciones ante cualquier dificultad que se presente durante el desarrollo. Espero aprender mucho de mis compañeros y que todos juntos podamos emplear de manera adecuada las tecnologías que iremos aprendiendo a lo largo del proyecto.| <img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/main/Resources/Chapter-I/Profiles/JeremyQuispe.png?raw=true" alt="Imagen de Jeremy Quispe"/>                 |
| **Santisteban Palomino, Ian Haziel Donato - u202214059**     |Mi nombre es Ian Haziel Donato Santisteban Palomino, tengo 20 años y estoy cursando el septimo ciclo de la carrera de Ingeniería de Software. Me apasiona la resolución de problemas mediante la aplicación de conceptos y tecnologías innovadoras. Tengo experiencia en desarrollo web utilizando HTML, CSS y JavaScript, y manejo frameworks como Vue y Angular. También tengo conocimientos en bases de datos con MySQL y en el uso de Figma para prototipado. Como miembro del equipo, aporto un sólido conocimiento en desarrollo de software y un compromiso constante con la excelencia en cada proyecto en el que participo. Estoy emocionado por aprender y colaborar con el equipo, así como por adquirir nuevas habilidades y conocimientos en las tecnologías que utilizaremos en nuestro trabajo.    | <img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/main/Resources/Chapter-I/Profiles/IanSantisteban.png?raw=true" alt="Imagen de Ian Santisteban"/> |
| **Criollo De La Cruz, Diego Anderson - u202219639**     |Mi nombre es Diego Anderson Criollo De La Cruz, tengo 20 años y estoy cursando el 8vo ciclo de la carrera de Ingeniería de Software. Me apasiona la resolución de problemas mediante la aplicación de conceptos y tecnologías innovadoras. Tengo experiencia en desarrollo web utilizando HTML, CSS y JavaScript, y manejo frameworks como Vue y Angular. También tengo conocimientos en bases de datos con MySQL y en el uso de Figma para prototipado. Como miembro del equipo, aporto un sólido conocimiento en desarrollo de software y un compromiso constante con la excelencia en cada proyecto en el que participo. Estoy emocionado por aprender y colaborar con el equipo, así como por adquirir nuevas habilidades y conocimientos en las tecnologías que utilizaremos en nuestro trabajo.    | <img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/main/Resources/Chapter-I/Profiles/DiegoCriollo.png" alt="Imagen de Diego Criollo"/> |

<br><br>
