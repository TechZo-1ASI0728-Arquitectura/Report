<div align="center">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/UPC_logo.png?raw=true" alt="Logo-UPC" width="150">

## Universidad Peruana de Ciencias Aplicadas

**Ingeniería de Software**

**Ciclo:** 2025-2

**Curso:** Arquitecturas De Software Emergentes (1ASI0728)

**Sección:** 7281

**Profesor:** Richard Leonardo Berrocal Navarro

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
|TB1|10/09/25|Ian Haziel Donato Santisteban Palomino, Diego Anderson Criollo De La Cruz, Joseph Alexis Huamani Mandujano, Jeremy Joel Quispe Andia y Mathias Andre Mendoza Carrion | Capítulo I: Introducción, Capítulo II: Requirements Elicitation & Analysis, Capítulo III: Requirements Specification, Capítulo IV: Strategic-Level Software Design |


<br><br>

<div style="page-break-after: always;"></div>

# Project Report Collaboration Insights

### Entregable TB1:


| **Integrante** | **Tareas Designadas**
| - | - |
|Huamani Mandujano, Joseph Alexis| Elaboración del To-Be Scenario Mapping, redacción de User Stories e Impact Mapping, y desarrollo de las Conclusiones del entregable. |
|Mendoza Carrión, Mathias André| Desarrollo del Strategic-Level Domain-Driven Design, creación del Context Mapping y definición de la Software Architecture. |
|Quispe Andia, Jeremy Joel| Redacción del Startup Profile, Solution Profile y análisis de los Segmentos objetivo. |
|Criollo De la Cruz, Diego Anderson| Elaboración del Product Backlog, definición del Design Purpose y desarrollo de los Attribute-Driven Design Inputs. |
|Santisteban Palomino, Ian Haziel Donato| Investigación sobre Competidores, desarrollo de Entrevistas y Needfinding, y elaboración del Ubiquitous Language. |

<h3>Evidencias del Contribution Insights de los commits del informe.</h3>


<div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-I/Project-Report-Collaboration-Insights/Commits-Contributions-TP1.png?raw=true" alt="Contribution Insights TB1" /></div>

### Entregable TP1:


| **Integrante** | **Tareas Designadas**
| - | - |
|Huamani Mandujano, Joseph Alexis| Diseño del Bounded Context Donations, elaboración de Component Level Diagrams, Domain Layer Class Diagram y Database Design Diagram. |
|Mendoza Carrión, Mathias André| Diseño del Bounded Context Exchange, creación de Component Level Diagrams, Domain Layer Class Diagram y Database Design Diagram. |
|Quispe Andia, Jeremy Joel| Implementación del Bounded Context IAM, desarrollo de Component Level Diagrams, Domain Layer Class Diagram y Database Design Diagram. |
|Criollo De la Cruz, Diego Anderson| Desarrollo del Applications UX/UI Design, Applications User Flow y Applications Prototyping. |
|Santisteban Palomino, Ian Haziel Donato| Elaboración de las Style Guidelines, diseño de la Information Architecture y Landing Page UI Design. |

<h3>Evidencias del Insights Contributions de los commits del informe.</h3>

<div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-I/Project-Report-Collaboration-Insights/Commits-Contributions-TB1.png?raw=true" alt="Contribution Insights TP1" /></div>




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
    - [2.3.3. Empathy Mapping](#233-empathy-mapping)
    - [2.3.4. As-is Scenario Mapping](#234-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
  
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)

- [Capítulo IV: Strategic-Level Software Design](#capítulo-iv-strategic-level-software-design)  
  - [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)  
    - [4.1.1. Design Purpose](#411-design-purpose)  
    - [4.1.2. Attribute-Driven Design Inputs](#412-attribute-driven-design-inputs)  
      - [4.1.2.1. Primary Functionality (Primary User Stories)](#4121-primary-functionality-primary-user-stories)  
      - [4.1.2.2. Quality Attribute Scenarios](#4122-quality-attribute-scenarios)  
      - [4.1.2.3. Constraints](#4123-constraints)  
    - [4.1.3. Architectural Drivers Backlog](#413-architectural-drivers-backlog)  
    - [4.1.4. Architectural Design Decisions](#414-architectural-design-decisions)  
    - [4.1.5. Quality Attribute Scenario Refinements](#415-quality-attribute-scenario-refinements)  
  - [4.2. Strategic-Level Domain-Driven Design](#42-strategic-level-domain-driven-design)  
    - [4.2.1. EventStorming](#421-eventstorming)  
    - [4.2.2. Candidate Context Discovery](#422-candidate-context-discovery)  
    - [4.2.3. Domain Message Flows Modeling](#423-domain-message-flows-modeling)  
    - [4.2.4. Bounded Context Canvases](#424-bounded-context-canvases)  
    - [4.2.5. Context Mapping](#425-context-mapping)  
  - [4.3. Software Architecture](#43-software-architecture)  
    - [4.3.1. Software Architecture System Landscape Diagram](#431-software-architecture-system-landscape-diagram)  
    - [4.3.2. Software Architecture Context Level Diagrams](#432-software-architecture-context-level-diagrams)  
    - [4.3.3. Software Architecture Container Level Diagrams](#433-software-architecture-container-level-diagrams)  
    - [4.3.4. Software Architecture Deployment Diagrams](#434-software-architecture-deployment-diagrams)  

- [Conclusiones](#conclusiones)
  - [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

<div align="justify">
	
<div style="page-break-after: always;"></div>


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
ingeniería</td>
      <td colspan="3" align = "justify">
    <h3>Joseph Alexis Huamani Mandujano</h3> 
    <b>TB1</b> 
    <p>En mi participación me enfoqué en exponer con claridad los objetivos iniciales de la startup y describir los perfiles de los integrantes en el Capítulo I. Asimismo, presenté los avances técnicos relacionados con el análisis competitivo y la definición de los segmentos objetivo, estructurando la información de manera que fuera comprensible tanto para docentes como para compañeros, utilizando ejemplos prácticos que facilitaron la comprensión del proyecto.</p> 
    <h3>Mathias André Mendoza Carrión</h3>
    <b>TB1</b>
    <p>Mi aporte consistió en explicar los resultados de las entrevistas y el análisis de necesidades en el Capítulo II, empleando un lenguaje accesible para transmitir la información a diferentes públicos. Además, defendí la propuesta del grupo durante las sesiones de retroalimentación, lo que permitió clarificar nuestras decisiones de diseño, y elaboré conclusiones que fueron presentadas en un informe técnico comprensible para personas sin formación especializada en ingeniería.</p>
    <h3>Ian Haziel Donato Santisteban Palomino</h3>
    <b>TB1</b>
    <p>Durante el desarrollo del proyecto detallé el diseño de prototipos y la elaboración de wireframes y mock-ups en el Capítulo IV. Comunicar estos hallazgos exigió adaptar el nivel técnico según la audiencia, por lo que expliqué con objetividad la arquitectura propuesta, resolviendo dudas del grupo y de los docentes. De esta manera logré que tanto los aspectos visuales como los estructurales fueran entendidos con claridad en las diferentes presentaciones.</p>
    <h3>Jeremy Joel Quispe Andia</h3>
    <b>TB1</b>
    <p>Me encargué de exponer la problemática y justificación del proyecto en el Capítulo I, contextualizando adecuadamente la solución que planteamos. También presenté de manera oral y escrita los resultados parciales de la especificación de requisitos, incluyendo user stories y product backlog, con un lenguaje claro y estructurado. Para asegurar la comprensión, adapté términos técnicos de ingeniería de software a un nivel accesible para audiencias no especializadas.</p>
    <h3>Diego Anderson Criollo De La Cruz</h3>
    <b>TB1</b>
    <p>En mi caso, presenté el plan de trabajo del grupo y la organización de roles desde el inicio del proyecto. Posteriormente, en el Capítulo II y III, expuse el análisis competitivo y las estrategias frente a competidores utilizando gráficos claros para docentes y compañeros. Finalmente, argumenté las conclusiones del diseño arquitectónico en el Capítulo IV con un lenguaje objetivo y ordenado, transmitiendo de forma efectiva las ideas del grupo.</p>
    <td colspan="3">
    <b>TB1</b>
    <p>Como grupo logramos comunicar nuestras ideas y resultados con objetividad a diferentes públicos durante el desarrollo del proyecto. Cada integrante expuso avances y conclusiones en distintos capítulos, adaptando el nivel técnico de la información para que fuera comprendido tanto por docentes especializados como por compañeros y personas sin formación en ingeniería. A través de presentaciones orales, informes escritos y la defensa de propuestas, demostramos nuestra capacidad para transmitir de manera clara y estructurada los hallazgos y soluciones planteadas, cumpliendo con el Student Outcome 3 del criterio ABET.</p>
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
    <p>Contribuí en la redacción de la descripción de la startup y los perfiles de los integrantes en el Capítulo I, estructurando la información de manera clara y objetiva. Además, participé en la elaboración de documentos que explicaban el análisis competitivo, cuidando que fueran entendidos por públicos con diferentes niveles de conocimiento.</p>
    <h3>Mathias André Mendoza Carrión</h3>
    <b>TB1</b>
    <p>Me encargué de plasmar los resultados de entrevistas y el análisis de necesidades en el Capítulo II, redactando informes que transmitieron los hallazgos de forma comprensible para diferentes especialidades. También elaboré conclusiones escritas que resumieron de manera objetiva las propuestas del grupo.</p>
    <h3>Ian Haziel Donato Santisteban Palomino</h3>
    <b>TB1</b>
    <p>Desarrollé documentos relacionados con el diseño de prototipos y mock-ups en el Capítulo IV, explicando tanto aspectos técnicos como visuales. Mi redacción buscó ser precisa y entendible para públicos variados, desde compañeros hasta docentes con mayor nivel jerárquico.</p>
    <h3>Jeremy Joel Quispe Andia</h3>
    <b>TB1</b>
    <p>Elaboré textos que explicaban la problemática y justificación del proyecto en el Capítulo I, así como la especificación de requisitos en el Capítulo III. Redacté las secciones de user stories y backlog con un lenguaje estructurado y objetivo, facilitando la comprensión de audiencias con diferentes niveles técnicos.</p>
    <h3>Diego Anderson Criollo De La Cruz</h3>
    <b>TB1</b>
    <p>Redacté apartados vinculados al análisis competitivo y a las estrategias frente a competidores en el Capítulo II. También colaboré en la escritura de las conclusiones de diseño arquitectónico, cuidando que fueran presentadas con claridad y objetividad para docentes y compañeros.</p>
    </td>
      <td colspan="3">
    <b>TB1</b>
    <p>Como grupo logramos comunicar por escrito nuestras ideas y resultados de manera objetiva durante el desarrollo del proyecto. La redacción de los diferentes capítulos, desde la descripción de la startup hasta el diseño arquitectónico y las conclusiones finales, permitió que la información fuera entendida tanto por docentes especializados como por compañeros y personas sin formación técnica. A través de informes, documentos y reportes estructurados, demostramos nuestra capacidad de transmitir de forma clara y precisa los avances del proyecto, cumpliendo con el Student Outcome 3 en su dimensión escrita.</p>
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
| **Huamani Mandujano, Joseph Alexis - u20221a133**             |Mi nombre es Joseph Huamani, soy estudiante de 8vo ciclo en la carrera de Ingeniería de Software en la UPC. Apasionado por el desarrollo web y web, cuento con experiencia usando lenguajes como C++, Python, Java, C#, Javascript y Typescript. Además cuento con experiencia en desarrollo web con HTML5 y CSS3 usando frameworks para frontend como Angular, VueJs, React y Astro. En cuanto al backend frameworks  como Spring Boot, .Net y Flask. Manejo de base de datos como MySQL, MSSQL, PostgreSQL, Oracle, SQLite y MongoDB. Soy una persona que trabaja en equipo, responsable y que brinda soluciones creativas para la resolución de problemas adquiridas gracias a la programación competitiva. Espero poder seguir aprendiendo nuevas tecnologias y poder culminar este curso de manera satisfactoria.| <img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-I/Profiles/JosephHuamani.png?raw=true" alt="Imagen de Joseph Huamani" />|
| **Mendoza Carrión, Mathias André - u202216282** |Soy Mathias Andre Mendoza Carrión, un estudiante de 20 años de Ingeniería de Software en el octavo ciclo. Me caracterizo por ser organizado, trabajar bien en equipo y ser responsable. Actualmente, mi enfoque principal es el aprendizaje profundo y práctico en el desarrollo de software, con habilidades en lenguajes de programación como C++, Python, Java, C#, y JavaScript. También tengo conocimientos en frameworks como Angular y Vue, desarrollo web con HTML y CSS, así como en la gestión de bases de datos SQL y MongoDB. Aspiro a dominar nuevas tecnologías y comprender en detalle los principios fundamentales detrás del desarrollo de aplicaciones, con el objetivo de convertirme en un profesional capaz de crear soluciones innovadoras y eficientes en el campo del desarrollo de software.| <img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-I/Profiles/MathiasMendoza.png?raw=true" alt="Imagen de Mathias Mendoza"/> |
| **Quispe Andia, Jeremy Joel - u202216279** |Mi nombre es Jeremy Joel Quispe Andia, soy estudiante de 8vo ciclo de la carrera de Ingeniería de Software. Tengo una gran pasión por la programación competitiva y aspiro a convertirme en desarrollador Full Stack. Me gusta emplear soluciones creativas y eficientes para abordar cualquier desafío de la mejor manera posible. Como miembro del grupo, pretendo aportar todos mis conocimientos en el desarrollo web. Además, siempre colaboro con ideas y soluciones ante cualquier dificultad que se presente durante el desarrollo. Espero aprender mucho de mis compañeros y que todos juntos podamos emplear de manera adecuada las tecnologías que iremos aprendiendo a lo largo del proyecto.| <img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-I/Profiles/JeremyQuispe.png?raw=true" alt="Imagen de Jeremy Quispe"/>                 |
| **Santisteban Palomino, Ian Haziel Donato - u202214059**     |Mi nombre es Ian Haziel Donato Santisteban Palomino, tengo 20 años y estoy cursando el septimo ciclo de la carrera de Ingeniería de Software. Me apasiona la resolución de problemas mediante la aplicación de conceptos y tecnologías innovadoras. Tengo experiencia en desarrollo web utilizando HTML, CSS y JavaScript, y manejo frameworks como Vue y Angular. También tengo conocimientos en bases de datos con MySQL y en el uso de Figma para prototipado. Como miembro del equipo, aporto un sólido conocimiento en desarrollo de software y un compromiso constante con la excelencia en cada proyecto en el que participo. Estoy emocionado por aprender y colaborar con el equipo, así como por adquirir nuevas habilidades y conocimientos en las tecnologías que utilizaremos en nuestro trabajo.    | <img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-I/Profiles/IanSantisteban.png?raw=true" alt="Imagen de Ian Santisteban"/> |
| **Criollo De La Cruz, Diego Anderson - u202219639**     |Mi nombre es Diego Anderson Criollo De La Cruz, tengo 20 años y estoy cursando el 8vo ciclo de la carrera de Ingeniería de Software. Me apasiona la resolución de problemas mediante la aplicación de conceptos y tecnologías innovadoras. Tengo experiencia en desarrollo web utilizando HTML, CSS y JavaScript, y manejo frameworks como Vue y Angular. También tengo conocimientos en bases de datos con MySQL y en el uso de Figma para prototipado. Como miembro del equipo, aporto un sólido conocimiento en desarrollo de software y un compromiso constante con la excelencia en cada proyecto en el que participo. Estoy emocionado por aprender y colaborar con el equipo, así como por adquirir nuevas habilidades y conocimientos en las tecnologías que utilizaremos en nuestro trabajo.    | <img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-I/Profiles/DiegoCriollo.png?raw=true" alt="Imagen de Diego Criollo"/> |

<br><br>


## 1.2 Solution Profile

### 1.2.1 Antecedentes y problemática

La economía lineal actual, caracterizada por el modelo de producir, usar y desechar, está generando un aumento preocupante en la acumulación de residuos y el uso insostenible de recursos naturales. Morseletto (2023) destaca que esta estructura económica predominante contribuye significativamente al aumento de residuos y la degradación ambiental. 

Esta forma de consumo no solo incrementa la cantidad de desechos sólidos, contamina los océanos y provoca la pérdida de biodiversidad, sino que también intensifica el cambio climático debido a las emisiones significativas de gases de efecto invernadero asociadas con la fabricación, transporte y eliminación de productos (Madaan et al., 2024). 

Según Liu y Zhong (2023), la extracción intensiva de materias primas para la producción de nuevos bienes está agotando los recursos naturales a un ritmo alarmante, lo que agrava aún más la situación ambiental. A esto se suma el crecimiento continuo de la población mundial, que se espera que aumente en 2000 millones de personas para el año 2050, multiplicando aún más la generación de residuos (Kruse-Andersen, 2023). 

Frente a esta problemática, nuestra aplicación propone una solución basada en la economía circular, que busca mantener los productos, materiales y recursos en uso durante el mayor tiempo posible.

Para explicar con más detalle esta situación, como grupo, usaremos la metodología de las 5W y 2H para darle más énfasis a los antecedentes y problemáticas a las que se enfrenta nuestra iniciativa de cambio:


**5W's y 2H's**

* **WHAT?** <br>
La acumulación diaria de residuos a nivel global está generando un impacto negativo en el medio ambiente y en la conservación de los recursos naturales del planeta. Este problema se debe a la falta de iniciativas para dar una segunda vida a los objetos en lugar de desecharlos, lo que contribuye a la sobrecarga de vertederos y al agotamiento de recursos.<br><br>


* **WHY?**<br>
Muchas personas no toman la iniciativa de reutilizar o intercambiar objetos que ya no necesitan, y en lugar de eso, optan por desecharlos. Esta falta de conciencia sobre las consecuencias ambientales a largo plazo resulta en un aumento de desechos y en el agotamiento de recursos naturales..<br><br>

* **WHO?**<br>
El problema afecta al público en general, pero en particular a aquellos que más necesitan apoyo en términos de recursos y asistencia. La aplicación está dirigida a usuarios interesados en adoptar prácticas de reutilización y sostenibilidad.<br><br>

* **WHEN?**<br>
Esta problemática es una constante con el pasar de los años ya que recién es que se está popularizando la cultura de reutilización y desarrollo sostenible, debido a que desde siempre se ha optado en primera instancia por solo desechar y no reutilizar.<br><br>

* **WHERE?**<br>
Aunque la problemática de los residuos y la falta de reutilización es global, la aplicación se enfocará inicialmente en la población peruana, con planes de expansión a otras regiones en función de los resultados y la demanda.<br><br>

* **HOW?**<br>
Se implementará una propuesta de solución mediante el desarrollo de una aplicación web y movil que permita a los usuarios publicar posts de objetos que deseen intercambiar por otras pertenencias, además de permitir realizar donaciones a organizaciones benéficas. Todo ello en una plataforma intuitiva, fácil de manejar y con opciones de personalización.<br><br>

* **HOW MUCH?**<br>
El presupuesto para el desarrollo de la aplicación web y movil varía en función de los requisitos específicos del proyecto. Se estima que podría oscilar entre S/. 20,000 y S/. 50,000, dependiendo de la complejidad y las características de la aplicación.<br><br>

### 1.2.2 Lean UX Process
#### 1.2.2.1 Lean UX Problem Statement
**Problem Statement 1:**  El contexto actual en el que nos encontramos nos demuestra que a diario se ve mucho más en práctica modelos de vida sostenible y que incluso se popularizan de manera más rápida por las redes sociales. De acuerdo a esto, cada vez la población busca darle una nueva vida a sus pertenencias y así evitar el desechar tantos objetos y de este modo contribuir con la disminución de residuos en el planeta.

Sin embargo, hemos notado que hay una gran dificultad al que este sector de la población tiene, el cual es que no hay una forma sencilla y práctica de darle un segundo uso a sus pertenencias, en este caso, enfocándonos en el intercambio de bienes. 
¿Cómo implementamos de manera eficaz un modelo de intercambio de pertenencias?<br><br>


**Problem Statement 2:** En la actualidad, se puede observar que hay una base sólida de organizaciones benéficas que siempre apoyan a diversos sectores vulnerables de la población, ya sea con donaciones de víveres, ropa, objetos de primera necesidad y/o apoyo económico.

Pese a ello, hemos identificado un factor crítico que afecta a muchas de estas organizaciones, es que no hay un modelo sólido que organice toda la información de estos grupos y que permita a los contribuidores tener un fácil acceso a todos los detalles correspondientes, ya sean campañas de donación o de aporte monetario benéfico.

¿Cómo podemos desarrollar una funcionalidad que permita a los usuarios realizar aportes benéficos de manera sencilla e intuitiva, facilitando la conexión entre Donadores y organizaciones?

#### 1.2.2.2 Lean UX Assumptions

 + **User Assumptions:** 

    + **¿Quién es el usuario?** <br>Nuestros usuarios son personas interesadas en dar un nuevo uso a sus pertenencias mediante el intercambio o donación. Esto incluye tanto a individuos que desean intercambiar objetos como a aquellos que buscan apoyar a organizaciones benéficas registradas en la plataforma.<br><br>

    + **¿Dónde encaja nuestro producto en su trabajo o en su vida?**<br> El producto se integra en la vida de los usuarios como una herramienta para fomentar un estilo de vida sostenible, permitiéndoles participar activamente en la economía circular y contribuir a la reducción de residuos.<br><br>

    + **¿Cuándo y cómo se utiliza nuestro producto?**<br> Nuestro producto es usado cuando los usuarios sientan que ya no necesitan más una pertenencia y en vez de solo desecharla, darle un nuevo uso para alguien más, intercambiándose por algo que sí necesite o realizando donaciones a organizaciones benéficas para aquellos que más lo necesitan.<br><br>


    + **¿Qué problemas resuelve nuestro producto?**<br>Cambiazo simplifica el intercambio y la donación de objetos, ofreciendo una plataforma segura y conveniente que promueve la reutilización y reduce el desperdicio. Con medidas de seguridad integradas, aborda las preocupaciones sobre transacciones fraudulentas, proporcionando una solución completa para una experiencia de intercambio confiable y sostenible.<br><br>


    + **¿Qué características son importantes?**<br> Que sea fácil de usar, intuitiva y que contenga las funcionalidades necesarias para que la experiencia del usuario sea la mejor, con opción de filtros para la búsqueda de ciertos artículos y/o también la inclusión de un chat privado entre usuarios para que puedan comunicarse y coordinar el intercambio, si es que ambos están de acuerdo con las pertenencias que ofrecen y desean recibir.<br><br>

    + **¿Cómo debe verse y comportarse nuestro producto?**<br> Nuestro producto debe tener una interfaz amigable para todos el público en general, incluir solo funcionalidades básicas y necesarias para no saturar a los usuarios con demasiada información.Además de ello debe mantenerse siempre con actualizaciones que vayan mejorando la optimización del proyecto.<br><br>

 + **Business Outcomes:** 

    1. **Creo que nuestros usuarios necesitan** tener un medio seguro y fácil de usar para poder realizar intercambios y/o donaciones de manera sencilla y eficaz.

    2. **Estas necesidades se pueden resolver con** una aplicación movil que tenga una interfaz intuitiva y que ofrezca que usuarios del Perú puedan realizar publicaciones de intercambio de sus pertenencias y solicitar cierto producto a cambio.

    3. **Nuestros usuarios iniciales son** el público en general del Perú que desee ser parte del cambio por un estilo de vida sostenible.

    4. **El valor #1 que un cliente quiere de nuestro servicio es que** ofrezca una forma rápida y sencilla de realizar publicaciones de intercambio y que tenga un sistema sólido para que los involucrados puedan coordinar el proceso respectivo con facilidad.

    5. **El usuario también puede obtener beneficios adicionales como**  tener un número ilimitado de publicaciones sobre intercambios que pueda realizar, además de poder obtener un “Boost” diario para que sus publicaciones siempre tengan preferencia al momento que aparezca tras una búsqueda por algún otro usuario.

    6. **Vamos a adquirir la mayoría de nuestros clientes a través de** publicidad en redes sociales tales como Instagram, Tiktok y Facebook, con una estrategia que promocione principalmente el impacto positivo que generaría el aplicar esta práctica de reutilización en el medio ambiente a largo plazo.

    7. **Haremos dinero a través de** ofrecer una suscripción premium que ofrecerá ciertos beneficios que hagan de su experiencia en CambiaZo mucho más satisfactoria y fácil.

    8. **Nuestras competencias principales son** grupos de Facebook que se dedican al intercambio, Me Sirve, HazTruequing y Trueques.

    9. **Los venceremos debido a** las funcionalidades que incluimos en nuestra propuesta de solución, además de la propia diferenciación de CambiaZo que tiene como logo principal, el ser un impulso para un cambio en la sociedad, el tener un estilo de vida sostenible.

    10. **Nuestro mayor riesgo es** que los usuarios no encuentren intercambios justos y puedan llegar a frustrarse por ello.

    11. **Resolveremos esto a través de** un proceso de verificación y control sobre la información que cada usuario coloca al momento de hacer un intercambio, para que no haya inconvenientes de posibles intercambios injustos o de broma.


#### 1.2.2.3 Lean UX Hypothesis Statements
**Creemos que** al tener una plataforma sólida para  poder realizar publicaciones de intercambios, los usuarios podrán contribuir con la metodología de una economía cíclica y de formar parte de un estilo de vida sostenible.
**Sabremos que es cierto** cuando las estadísticas de cuántos intercambios se van realizando al día sean más de 30, esto demostrará que nuestra propuesta de solución realmente está fomentando la reutilización de los objetos de las personas en general.

**Creemos que**  permitir la interacción entre los usuarios al momento de mostrar interés por un artículo, ayudará a que puedan coordinar el intercambio de mejor manera <br>**Sabremos que lo habremos logrado**  cuando se refleje a través de los comentarios, que más del 50% de los usuarios resalte el sistema de comunicación entre usuarios, previo al intercambio.


**Creemos que**  al tener la opción de realizar donaciones a personas de escasos recursos económicos, facilitará a los usuarios que deseen donar objetos que ya no utilizan, a hacerlo y a contribuir con este acto solidario.<br>**Sabremos que esto es cierto**  cuando la cantidad de usuarios que han donado a través de nuestra plataforma, supere el 10% de usuarios registrados dentro de la aplicación cada mes.



#### 1.2.2.4 Lean UX Canvas
La aplicación **CambiaZo**  es una plataforma digital diseñada para que los usuarios puedan deshacerse de los objetos que ya no desean tener, intercambiándolos por otros artículos que desean de otros usuarios. Además, tiene como objetivo principal convertirse en la plataforma digital líder de intercambio de productos, promoviendo una vida consciente y sostenible a nivel mundial.

<table>
    <tr>
        <td valign="top">
            <div align="center"><br><b>Business Problem</b></div><br>
            <p>El modelo de economía lineal actual causa acumulación de residuos y un uso insostenible de recursos. Falta una solución accesible para el intercambio y donación de bienes.<br><br>¿Cómo podemos facilitar un sistema sencillo y eficiente para que las personas intercambien y donen bienes?</p><br>
        </td>
        <td rowspan="2" valign="top">
            <div align="center"><br><b>Solutions</b></div><br>
            <ul>
            <li>Desarrollar una aplicación web para facilitar el intercambio de objetos entre usuarios.</li><br>
            <li>Permitir la donación de bienes a organizaciones benéficas.</li><br>
            <li>Implementar opciones de búsqueda y comunicación entre usuarios para coordinar intercambios.</li><br>
            <li>Incluir funcionalidades para registrar donaciones y asegurar transacciones seguras.</li><br>
            </ul><br>
        </td>
        <td valign="top">
            <div align="center"><br><b>Business Outcomes</b></div><br>
            <ul>
              <li>Satisfacción del usuario en intercambios y donaciones.</li><br>
              <li>Obtener financiamiento para expandir la app.</li><br>
              <li>Aumentar la visibilidad y alcance con marketing en redes sociales.</li>
            </ul><br>
        </td>
    </tr>
    <tr>
        <td valign="top">
            <div align="center"><br><b>Users</b></div><br>
            <ul>
              <li>Personas interesadas en intercambiar bienes no necesarios</li><br>
              <li>Personas interesadas en donar a organizaciones benéficas.</li>
            </ul><br>
        </td>
        <td valign="top">
            <div align="center"><br><b>User Outcomes & Benefits</b></div><br>
            <ul><li>Ahorro de dinero al obtener productos sin costo</li><br>
            <li>Deshacerse de objetos no deseados de manera útil.</li><br>
            <li>Acceso a nuevos artículos a través del intercambio y contribución a causas benéficas.</li>
            </ul><br>
        </td>
    </tr>
    <tr>
        <td valign="top">
            <div align="center"><br><b>Hypotheses</b></div><br>
            <p>Creemos que nuestra aplicación promoverá la economía circular y un estilo de vida sostenible, facilitando el intercambio y la donación de bienes.<br><br>Sabemos que esto es cierto cuando los usuarios realicen más de 30 intercambios diarios y más del 10% de los usuarios registrados participen en donaciones mensuales.</p><br>
        </td>
        <td valign="top">
            <div align="center"><br><b>What's the most important thing we need to learn first?</b></div><br>
            <ul>
            <li>Comprender las necesidades y expectativas de los usuarios sobre el intercambio y la donación de bienes.</li><br>
            <li>Identificar las características más valoradas de la aplicación y cómo garantizar la seguridad en las transacciones.</li>
            <br>
            <li>Recopilar feedback sobre las funcionalidades y posibles mejoras.</li>
            </ul><br>
        </td>
        <td valign="top">
            <div align="center"><br><b>What's the least amount of work we need to do to learn the next most important thing?</b></div><br>
            <ul><li>Incorporar una función de comentarios y sugerencias. </li><br>
            <li>Realizar encuestas regulares para ajustar la app según el feedback.</li>
            </ul><br>
        </td>
    </tr>
</table>
<br>

</div>


## 1.3 Segmentos Objetivo

Esta sección incluye la descripción de los segmentos asociados al dominio del problema, incluyendo características geográficas y demográficas. Por lo tanto, con el fin de desarrollar un producto que satisfaga las necesidades de nuestros clientes, TechZo se enfocará en los siguientes segmentos de la población:

+ **Personas adultas que desean obtener nuevos artículos (Intercambiadores):**<br>
Estas personas buscan deshacerse de productos que ya no desean y adquirir nuevos artículos de su interés mediante intercambios.
  + **Características demográficas:** Personas entre 18 y 55 años, con artículos no deseados que están interesados en intercambiarlos por otros que necesitan. Este rango de edad fue seleccionado porque, según la distribución de la población por segmentos de edad mostrada en la [Imagen 1](#imagen-1), representa el 53.9% de la población total del país, equivalente a 18,037,900 personas (CPI Research, 2022).

    <div align="center">
	    <strong id="imagen-1">Imagen 1: Distribución de la población en Perú por segmentos de edad en 2022 (CPI Research, 2022)</strong><br><br>
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-I/Target-Segment/estadistica-segmentos.PNG?raw=true" alt="Estadistica Segmentos 2" style="width: 500px; height: auto;">
    </div><br><br>

  + **Características geográficas:** Personas que residen en Perú.<br>
  + **Motivaciones y Comportamientos:** A menudo motivados por la necesidad de actualizar sus pertenencias o por la falta de recursos para comprar nuevos artículos. En un estudio realizado por la Universidad Nacional del Altiplano en Puno, se identificó que una de las principales razones para realizar trueques es la falta de dinero. Este rango de edad fue seleccionado porque, según la información provista en la [Imagen 2](#imagen-2), se destacan diversas razones por las cuales las personas adultas participan en intercambios de artículos. La principal razón es la "Falta de dinero", representando el 56% de las respuestas, seguida de otros motivos como "Falta de trabajo" y "Por costumbre", entre otros.

     <div align="center">	
	     <strong id="imagen-2">Imagen 2: Motivos para Realizar Trueques según el Estudio de la Universidad Nacional del Altiplano</strong><br><br>
	 </div>

| **Motivo**                    | **Número respuestas** | **Valor relativo** |
|:------------------------------:|:---------------------:|:------------------:|
| Falta de dinero               | 56                    | 56%                |
| Falta de trabajo              | 7                     | 7%                 |
| Por costumbre                 | 5                     | 5%                 |
| Por conveniencia              | 5                     | 5%                 |
| Ahorro de dinero              | 2                     | 2%                 |
| Por no malograr alimentos     | 1                     | 1%                 |
| Recurso complementario        | 7                     | 7%                 |
| Tercera edad                  | 3                     | 3%                 |
| Fácil acceso                  | 1                     | 1%                 |
| Precio económico              | 1                     | 1%                 |
| Por sus hijos y por necesidad | 8                     | 8%                 |
| No respondió                  | 4                     | 4%                 |

	
+ **Preferencias de Uso:** Valoran una plataforma intuitiva que facilite la búsqueda y el intercambio de productos. Prefieren opciones que ofrezcan seguridad y transparencia en las transacciones.<br><br>
  
+ **Personas adultas que desean donar artículos que ya no utilizan (Donadores):**<br>
“Cambiazo” es fundamental como herramienta para realizar donaciones, ya que permite que personas de escasos recursos puedan recibir donaciones de objetos de personas que ya no utilizan sus artículos y desean donarlos.

    + **Características demográficas:** Personas entre 15 y 60 años de edad con la voluntad de donar objetos propios que ya no utilizan a personas de escasos recursos económicos.

    + **Características geográficas:** Personas que residen en Perú.

    + **Motivaciones y Comportamientos:** Buscan contribuir a la comunidad y ayudar a quienes están en situación de necesidad. Valoran plataformas que les permitan realizar donaciones de manera sencilla y eficiente.

    + **Preferencias de Uso:** Prefieren una aplicación que facilite el proceso de donación, ofreciendo una lista de organizaciones benéficas y un sistema fácil de utilizar para coordinar las donaciones.

<br><br>


<div style="page-break-after: always;"></div>


# Capítulo II: Requirements Elicitation & Analysis

## 2.1 Competidores

En esta sección se identificarán los mejores referentes para posteriormente realizar un análisis competitivo que nos ayudará a saber nuestro posicionamiento y el valor agregado que ofreceremos en el mercado. 

Según la investigación, se descubrieron aplicaciones webes y/o apps webs similares. Sin embargo, estamos considerando tres competidores directos o indirectos que se parezcan más a nuestra startup.

* **Trueques.com**<br>
Plataforma que ofrece una amplia gama de servicios de intercambio, incluidos intercambios de servicios y artículos de segunda mano. Los usuarios pueden buscar y publicar ofertas de intercambio, así como participar en eventos y actividades comunitarias relacionadas con el intercambio.<br><br>

* **HazTruequing**<br>
Plataforma en línea que permite a los usuarios intercambiar servicios y artículos de segunda mano de manera fácil y segura. Los usuarios pueden publicar lo que tienen disponible para el intercambio y buscar lo que necesitan, creando así una comunidad de intercambio activa y diversa.<br><br>


* **Me Sirve**<br>
Aplicación web que ofrece una forma conveniente de intercambiar y adquirir artículos de segunda mano. Los usuarios pueden publicar lo que tienen para intercambiar, buscar lo que necesitan y comunicarse directamente con otros usuarios para concretar los intercambios.<br><br>

### 2.1.1 Análisis Competitivo

En esta sección se realizará el análisis competitivo de los competidores identificados en la sección inicial con el objetivo de tener una idea más clara sobre nuestro producto frente a los competidores y aprender para mejorar nuestro producto.

<table>
<thead>
  <tr>
    <th colspan="6">Competitive Analysis Landscape<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td colspan="2">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="4">Este análisis se lleva a cabo para poder investigar, analizar y comparar el comportamiento de los competidores directos o indirectos en el mercado</td>
  </tr>
  <tr>
    <td colspan="2">
        <div align="center">Nombre</div>
    </td>
    <td>
		<div align="center">Cambiazo<br></div>
	</td>
    <td>
		<div align="center">Trueques.com</div>
	</td>
    <td>
		<div align="center">Haztruequing</div>
	</td>
    <td>
		<div align="center">Me Sirve</div>
	</td>
  </tr>
  <tr>
    <td colspan="2">
        <div align="center">Logo</div>
    </td>
    <td>
		<div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/logo-cambiazo.png?raw=true"alt="Cambiazo logo" /></div>
		</td>
    <td>
		<div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Competitors/logo-trueques.PNG?raw=true"alt="Trueques.com logo" /></div>
		</td>
    <td>
		<div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Competitors/logo-haztruequing.png?raw=true"alt="Haztruequing logo" /></div>
		</td>
    <td>
		<div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Competitors/logo-mesirve.png?raw=true"alt="Me sirve logo" /></div>
		</td>
  </tr>
  <tr>
    <td rowspan="2">Perfil</td>
    <td>Overview</td>
    <td>Aplicación web y móvil que conecta a personas interesadas en darle un nuevo uso a sus pertenencias mediante intercambios o donaciones, enfocándose en la sostenibilidad y la economía circular.
	</td>
    <td>Página Web para intercambio de bienes y servicios entre usuarios, fomentando la economía colaborativa y la reutilización de recursos.</td>
    <td>Plataforma para intercambiar servicios y artículos de segunda mano de manera gratuita, promoviendo un estilo de vida sostenible y consciente.</td>
    <td>App para intercambiar bienes y servicios de manera segura y eficiente, promoviendo la reutilización y la solidaridad entre usuarios.</td>
  </tr>
  <tr>
    <td>Ventaja Competitiva <br>¿Qué valor ofrece a los clientes?</td>
    <td>Intercambio de productos o servicios. <br><br>Donación de objetos a ONGs afiliadas</td>
    <td>Intercambio directo de bienes y servicios sin dinero, fomentando la reutilización y colaboración.</td>
    <td>Intercambio de servicios y artículos de segunda mano, promoviendo un estilo de vida sostenible.</td>
    <td>Intercambio bienes y servicios, promoviendo la reutilización y la solidaridad.
</td>
  </tr>
  <tr>
    <td rowspan="2">Perfiles de Marketing<br></td>
    <td>Mercado Objetivo<br></td>
    <td>Personas interesadas en  intercambiar o donar sus pertenencias.</td>
    <td>Personas que buscan intercambiar productos y servicios</td>
    <td>Personas interesados en intercambiar servicios y artículos de segunda mano</td>
    <td>Usuarios interesados en darle un nuevo propósito a sus pertenencias mediante intercambios.</td>
  </tr>
  <tr>
    <td>Estrategias de marketing</td>
    <td>Publicidad en Foros y Redes sociales</td>
    <td>Publicidad en redes sociales</td>
    <td>Publicidad en redes sociales</td>
    <td>Publicidad en redes sociales</td>
  </tr>
  <tr>
    <td rowspan="3">Perfil de Producto<br></td>
    <td>Productos &amp; Servicios</td>
    <td>Intercambiar bienes o servicios, donar a ONGs</td>
    <td>Intercambiar bienes o servicios</td>
    <td>Intercambiar bienes o servicios</td>
    <td>Intercambiar bienes o servicios</td>
  </tr>
  <tr>
    <td>Precios y Costos</td>
    <td>Free y Premium desde $2.99 por mes</td>
    <td>Free</td>
    <td>Free</td>
    <td>Free y Premium $2.99 por mes</td>
  </tr>
  <tr>
    <td>Canales de Distribución (Web y/o  Móvil)</td>
    <td>Web y Móvil</td>
    <td>Web</td>
    <td>Web</td>
    <td>web</td>
  </tr>
  <tr>
    <td rowspan="4">Análisis SWOT</td>
    <td>Fortalezas</td>
    <td>Conexión intuitiva para intercambiar o donar objetos.<br><br>Amplia variedad de opciones para los usuarios.<br><br>Posibilidad de personalización en los intercambios.<br><br>Incorporación de automatización e innovación en la plataforma.</td>
    <td>Plataforma intuitiva para intercambiar bienes y servicios.<br><br>Amplia variedad de opciones disponibles.<br><br>Posibilidad de personalizar los intercambios.</td>
    <td>Plataforma confiable y amplia con una gran base de usuarios.<br><br>Compromiso con la sostenibilidad y la economía circular.</td>
    <td>Plataforma intuitiva y segura para intercambiar bienes y servicios.<br><br>Variedad de opciones disponibles para los usuarios.<br><br>Interfaz fácil de usar para una experiencia positiva.</td>
  </tr>
  <tr>
    <td>Debilidades</td>
    <td>Limitaciones en la disponibilidad de objetos y servicios.<br><br>Posibles dificultades técnicas en la gestión de transacciones y seguridad de datos.</td>
    <td>Posibles dificultades para garantizar la equidad en los intercambios.<br><br>Limitaciones técnicas que puedan afectar la funcionalidad.</td>
    <td>Posibles desafíos relacionados con la competencia de otras plataformas y la seguridad de las transacciones.</td>
    <td>Posibles desafíos con seguridad de transacciones y gestión de reclamos.</td>
  </tr>
  <tr>
    <td>Oportunidades</td>
    <td>Aprovechar la conciencia creciente sobre sostenibilidad y consumo responsable.<br><br>Desarrollar alianzas con ONGs para ampliar el impacto social.<br><br>Expandir la plataforma a nivel nacional e internacional.</td>
    <td>Expandir la plataforma para incluir nuevas categorías de productos y servicios.<br><br>Establecer alianzas con organizaciones benéficas para ampliar el impacto social.</td>
    <td>Expandir la plataforma a nivel nacional e internacional.</td>
    <td>Aprovechar la conciencia creciente sobre economía colaborativa y sostenibilidad.<br><br>Expandir la plataforma con más servicios y funciones para mejorar la experiencia.</td>
  </tr>
  <tr>
    <td>Amenazas</td>
    <td>Al ser una aplicación nueva, puede que no tenga la demanda esperada.<br><br>Competencia de otras plataformas.<br>Cambios en las preferencias del usuario.</td>
    <td>Mejor organizacion del sitio web<br><br>Cambios en las preferencias del usuario.</td>
    <td>Mejor interfaz, mas amigable e intuitiva<br><br>Cambios en las preferencias del usuario.</td>
    <td>Mejorar la seguridad de datos y privacidad de usuarios.<br><br>Cambios en las preferencias del usuario.</td>
  </tr>
</tbody>
</table>


### 2.1.2 Estrategias y tácticas frente a competidores

En esta sección se analizarán las estrategias y tácticas que se usarán para aprovechas las debilidades de la competencia y afrontar sus fortalezas. De la misma forma con las amenazas y oportunidades de la competencia.

Hemos empleado el análisis FODA para identificar las oportunidades y amenazas en el mercado, así como para evaluar nuestras fortalezas y debilidades internas. Este enfoque nos ha permitido concebir estrategias y tácticas adecuadas en consonancia con nuestro entorno y los recursos disponibles en base a nuestros dos segmentos objetivos.


**Estrategia de Diferenciación:** 

+ Para satisfacer las necesidades del **Segmento de Intercambiadores**, nos enfocamos en ofrecer una plataforma de intercambio intuitiva y dinámica que permita a los usuarios encontrar fácilmente los artículos deseados y realizar intercambios de manera rápida y segura. Implementaremos funciones avanzadas de búsqueda y filtros personalizables para facilitar la búsqueda de nuevos artículos.

+ Para el **Segmento de Donadores**, nos distinguimos al proporcionar una experiencia de donación gratificante y transparente. Estableceremos alianzas con organizaciones benéficas para ampliar las opciones de donación.

**Estrategia de Liderazgo en Costos:** 

+ Para el **Segmento de Intercambiadores**, nos comprometemos a mantener tarifas de intercambio competitivas y transparentes, y a ofrecer promociones especiales y descuentos para incentivar la participación activa en la plataforma.

+ En cuanto al **Segmento de Donaciones**, nuestra estrategia se centra en ofrecer una plataforma de donación sin costos ocultos ni tarifas adicionales. Nos comprometemos a garantizar que el proceso de donación sea completamente gratuito y accesible para todos los usuarios.

**Estrategia de Marketing:**

Para ambos segmentos, implementaremos una estrategia de marketing centrada en la sensibilización y la educación sobre los beneficios del intercambio y la donación. Desarrollaremos contenido informativo y atractivo que destaque las ventajas económicas, ambientales y sociales de participar en nuestra plataforma.

**Tácticas:**
- Creación de campañas publicitarias dirigidas a cada segmento objetivo para resaltar los beneficios específicos de la plataforma de intercambio y donación.
- Implementación de programas de referidos para incentivar la participación de usuarios existentes y expandir nuestra base de usuarios.
- Desarrollo de funciones adicionales en la plataforma, como sistemas de valoración y comentarios, para aumentar la confianza y la participación de los usuarios.
- Establecimiento de alianzas con organizaciones locales y empresas para promover eventos de intercambio y donación, generando así mayor visibilidad y compromiso con la comunidad.


## 2.2 Entrevistas

En esta sección se abordará la investigación en base a la información que se obtendrá de los segmentos entrevistados con el objetivo de conocer mejor a nuestros segmentos objetivos y aprender de ellos y sus procesos.


### 2.2.1 Diseño de entrevistas

**Preguntas sobre información personal**

*	¿Cuál es su nombre completo?
*	¿Qué edad tienes?
*	¿A qué te dedicas?
*	¿Cuál es tu estado civil?
*	¿En qué ciudad resides?
*	¿Eres extrovertido o calmado?
*	¿Eres una persona que toma decisiones analizando los hechos o te dejas llevar por tus sentimientos?
*	¿Qué smartphone posee? ¿Android o IOS?
*	¿Usas aplicaciones o programas en especial? ¿Cuáles?<br><br>


**Segmento objetivo 1:** Personas adultas que desean obtener nuevos artículos (Intercambiadores)

**Introducción:**

Buenos días/tardes/noches, mi nombre es [Nombre del entrevistador], y en esta ocasión tengo el agrado de poder entrevistar a [Nombre del entrevistado], quien es una persona que le gusta obtener nuevos objetos a través del intercambio.
Desde ya quiero agradecerle por su presencia y tiempo que me está brindando.

**Inmersión:**

1. ¿De qué forma se contacta con otras personas al momento de querer intercambiar alguno de los objetos que ya no usa?
2. ¿Cómo ha sido su experiencia previa con aplicaciones de intercambio de productos?
3. ¿Qué tipo de productos considera más viables para intercambiar a través de una aplicación web/móvil?

**Indagación:**

4. ¿Cuáles son las principales preocupaciones o dudas que tendría al utilizar una aplicación de intercambio de productos por primera vez?
5. ¿Qué características o funciones consideraría primordiales para sentirse seguro y cómodo al realizar intercambios en línea?
6. ¿Cómo cree usted que una aplicación de intercambio de objetos podría fomentar la confianza entre los usuarios para realizar intercambios justos y seguros?
7. ¿Qué tipo de productos considera que tendrían mayor demanda por parte de personas de su edad y ubicación geográfica?

**Verificación:**

8. ¿Qué medidas tomaría para estar seguro de que los productos que está intercambiando cumplen con sus expectativas?
9. ¿Cómo cree que la comunidad de usuarios podría contribuir a garantizar la veracidad de los productos ofrecidos dentro de la aplicación?
10. ¿Qué fuentes utilizaría para verificar la confiabilidad de una aplicación de intercambios en línea como CambiaZo?

**Medición:**

11. ¿Qué beneficios espera obtener al utilizar una aplicación como CambiaZo en comparación con otros métodos de adquisición de productos?
12. ¿Cómo considera que las personas pueden contribuir al desarrollo de una comunidad más sostenible y consciente en su ciudad?
13. ¿Cuál considera que es el mayor desafío que enfrenta la sociedad en Lima en la actualidad para mantener un consumo consciente, y cómo cree que podría tratarse?

**Cierre:**

Bueno esto ha sido todo por esta ocasión, una vez más quisiera agradecerle por su tiempo, muchas gracias y hasta luego.<br><br>


**Segmento objetivo 2:** Personas adultas que desean donar artículos que ya no utilizan (Donadores)

**Introducción:**

Buenos días/tardes/noches, mi nombre es [Nombre del entrevistador], y en esta ocasión tengo el agrado de poder entrevistar a [Nombre del entrevistado], quien es una persona que le gusta realizar donaciones a personas de escasos recursos.
Desde ya quiero agradecerle por su presencia y tiempo que me está brindando.

**Inmersión:**

1. ¿De qué forma ha realizado donaciones a personas con escasos recursos económicos?
2. ¿Cómo ha sido su experiencia previa con la donación de artículos a personas necesitadas o a organizaciones benéficas?
3. ¿Qué tipo de artículos consideraría más adecuados para donar a través de una aplicación web/móvil como CambiaZo?

**Indagación:**

4. ¿Cuáles son las principales preocupaciones que tendría al utilizar una aplicación como CambiaZo por primera vez?
5. ¿Qué funciones o características buscaría en una aplicación web/móvil al momento de querer realizar una donación en línea?
6. ¿Cómo cree que una aplicación web/móvil como CambiaZo podría aumentar la cantidad de donaciones en el Perú?

**Verificación:**

7. ¿Cómo podría una aplicación como CambiaZo garantizar la transparencia y autenticidad de las donaciones realizadas?
8. ¿Qué importancia le otorgaría a la posibilidad de seguir el destino de sus donaciones y conocer el impacto que tienen en la comunidad receptora?
9. ¿Qué criterios utilizaría para verificar la confiabilidad y legitimidad de una plataforma de donaciones en línea como CambiaZo?

**Medición:**

10. ¿Qué beneficios espera obtener al realizar donaciones utilizando CambiaZo en comparación con otros métodos de donación tradicionales?
11. ¿Cómo mediría el impacto de sus donaciones a través de una aplicación web/móvil como CambiaZo en términos de ayudar a personas necesitadas?
12. ¿Qué cambios o mejoras le gustaría ver en la funcionalidad de CambiaZo para que se convierta en una herramienta más efectiva para donar artículos?
13. ¿Cómo cree que el uso de aplicaciones en las que puede donar, como CambiaZo, podría contribuir al desarrollo de una comunidad más solidaria y conectada en Lima?

**Cierre:**

Bueno esto ha sido todo por esta ocasión, una vez más quisiera agradecerle por su tiempo, muchas gracias y hasta luego.<br><br>


### 2.2.2 Registro de entrevistas

En esta sección presentamos los registros de las entrevistas que realizamos para cada segmento objetivo de nuestra aplicación movil.


### **Segmento Intercambiadores**<br>


<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #1<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Jorge Sebastian</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Valdivia Peceros</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>20 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Surco</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom</td>
  </tr>
  <tr>
    <td>Motivacion</td>
    <td>Intercambiar objetos promoviendo el desarrollo sostenible</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>Preocupación sobre posibles estafas</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>Computadora Windows, Smartphone iOS</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Diego Criollo De La Cruz</td>
  </tr>
   <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://raw.githubusercontent.com/AppMoviles-MobiLoom-SW63/Informe/refs/heads/main/Resources/cap3/Entrevista%20a%20Sebastian%20Valdivia.png" alt="Entrevista Jorge Valdivia"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216282_upc_edu_pe/EYGbE4KNDtNLjRh61XjXqP8BKWSBYGr98SNL7tmmXDY5RQ?e=FEq7xt" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>00:00 min - 06:50 min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>
      En la entrevista con Sebastián Valdivia, un estudiante de Ciencias de la Computación de 20 años, se reveló que suele realizar intercambios contactando a personas por WhatsApp o a través de chats en aplicaciones, aunque reconoce que estas opciones pueden generar desconfianza respecto a la seguridad y el estado real de los productos. Considera que una plataforma como CambiaZo le sería de gran ayuda para simplificar el proceso, siempre que cuente con funciones como verificación de identidad, reseñas entre usuarios y un sistema de reputación que fomente la confianza. Sebastián destacó que los productos más demandados por jóvenes de su edad serían ropa, zapatillas, accesorios tecnológicos y artículos relacionados con hobbies, y que su principal preocupación al usar una aplicación de este tipo sería la seguridad de los intercambios y la calidad de los objetos ofrecidos. Para reducir estos riesgos, confía en la utilidad de descripciones claras, fotos y la retroalimentación de la comunidad. Finalmente, resaltó que el mayor beneficio de CambiaZo estaría en facilitar una experiencia segura y variada de intercambio, a la vez que promueve un consumo más consciente y sostenible en Lima.
    </td>
  </tr>
</tbody>
</table><br>



<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #2<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Edu Orlando</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Gutierrez Vasquez</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>19 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>La Molina</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom, Discord</td>
  </tr>
  <tr>
    <td>Motivacion</td>
    <td>Seguridad y calidad en intercambios de productos</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>Limitaciones de seguridad y calidad en Facebook</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>Laptop Windows, Smartphone Android</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google Chrome, Firefox</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Ian Haziel Donato Santisteban Palomino</td>
  </tr>
    <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-II/Interviews/edugutierez_interview.PNG?raw=true" alt="Entrevista Edu Gutierrez"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216282_upc_edu_pe/EYGbE4KNDtNLjRh61XjXqP8BKWSBYGr98SNL7tmmXDY5RQ?e=FEq7xt" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duracion<br></td>
    <td>6:50 min - 11:47 min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>En la entrevista con Edu, se revelaron detalles sobre su experiencia y preferencias en cuanto a realizar intercambios de objetos. Edu suele contactarse con otras personas para intercambiar objetos a través de Facebook y WhatsApp, pero encuentra limitaciones en estas plataformas en términos de seguridad y calidad de los productos.Considera que una plataforma como Cambiazo sería de gran ayuda para simplificar este proceso. Además, mencionó que le gustaría que la plataforma implementara funciones como un sistema de verificación de identidad y calidad de los productos, así como un sistema de evaluaciones entre usuarios para garantizar la confianza y seguridad en los intercambios. Edu también señaló que los productos de ocio y entretenimiento tendrían mayor demanda entre personas de su edad y ubicación geográfica. <br>En cuanto a sus preocupaciones, destacó la seguridad de las transacciones y la calidad de los productos ofrecidos. Para garantizar la calidad de los productos, Edu se basaría en las descripciones detalladas, las fotos proporcionadas por los usuarios y las evaluaciones de otros usuarios. También considera que la comunidad de usuarios podría contribuir a garantizar la veracidad de los productos ofrecidos dentro de la plataforma mediante la retroalimentación honesta y la denuncia de prácticas fraudulentas.<br>En términos de beneficios esperados al utilizar una aplicación como Cambiazo, Edu espera una mayor variedad de productos y una experiencia de intercambio más segura. Además, considera que el intercambio de productos usados puede contribuir al desarrollo de una comunidad más sostenible y consciente en su ciudad.
</td>
  </tr>
</tbody>
</table>


<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #3<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Gonzalo David</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Espino Rojas</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>21 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Santiago de Surco</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom, Discord</td>
  </tr>
  <tr>
    <td>Motivacion</td>
    <td>Promover los modelos de vida con desarrollo sostenible, para impulsar una economía cíclica</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>Que sus productos publicados no tengan la relevancia necesaria</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>Smatphone Android, Laptop Windows</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Joseph Alexis Huamani Mandujano</td>
  </tr>
   <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Interviews/gonzaloespino_interview.png?raw=true" alt="Entrevista Gonzalo Espino"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216282_upc_edu_pe/EYGbE4KNDtNLjRh61XjXqP8BKWSBYGr98SNL7tmmXDY5RQ?e=FEq7xt" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>11:47 min - 16:16 min</td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>Durante la entrevista, Gonzalo David Espino Rojas, un estudiante de marketing de 21 años que reside en Lima y posee un smartphone Android, comparte su experiencia personal en el ámbito de los intercambios. Gonzalo señala que en sus intentos previos de realizar este tipo de transacciones, ha experimentado dificultades con la veracidad del estado de los productos ofrecidos y la fiabilidad de los usuarios involucrados, lo cual ha generado incertidumbre y preocupación. Para abordar estas inquietudes, Gonzalo destaca la necesidad de contar con una aplicación web que ofrezca diversas funciones y características, como un sistema de calificación y reseñas de los usuarios, un riguroso proceso de verificación de identidad y una sólida política de privacidad y seguridad de datos. Asimismo, Gonzalo enfatiza la importancia de tener una comunidad activa dentro de la plataforma, ya que esto le permitiría evaluar de manera más precisa la confiabilidad de los usuarios y la calidad de los productos antes de concretar cualquier intercambio. En general, Gonzalo se muestra interesado en probar una aplicación como CambiaZo, ya que espera obtener beneficios como ahorrar dinero, contribuir al cuidado del medio ambiente y formar parte de una comunidad que promueve un consumo más consciente y sostenible.
</td>
  </tr>
</tbody>
</table><br>

<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #4<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Freddy Alejandro</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Cuadros Contreras</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>19 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Santiago de Surco</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Google Chrome, Zoom</td>
  </tr>
  <tr>
    <td>Motivacion</td>
    <td>Obtener objetos deseados de manera más sencilla</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>Dificultades en obtener objetos de calidad a través de grupos de Facebook</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>Laptop Windows, Smartphone IOS</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Jeremy Joel Quispe Andia</td>
  </tr>
  <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Interviews/freddycuadros_interview.png?raw=true" alt="Entrevista Freddy Cuadros"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216282_upc_edu_pe/EYGbE4KNDtNLjRh61XjXqP8BKWSBYGr98SNL7tmmXDY5RQ?e=FEq7xt" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duracion<br></td>
    <td>16:16 min - 20:46 min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>Freddy Cuadros nos menciona que CambiaZo facilita el contacto entre usuarios mediante un sistema de mensajería interna, lo que ha hecho que su experiencia con aplicaciones de intercambio sea positiva, permitiéndole reutilizar objetos y adquirir otros de forma sostenible. Considera que los productos más viables para intercambiar a través de CambiaZo son libros, ropa y pequeños electrodomésticos. Sus principales preocupaciones al usar CambiaZo son la autenticidad de los productos y la seguridad en las transacciones. Para sentirse seguro, considera esenciales la verificación de identidad, métodos de pago seguros y un sistema de valoraciones. Los productos tecnológicos y de moda son muy demandados, y para asegurarse de que cumplan con sus expectativas, solicita fotos y descripciones detalladas. Un sistema de valoraciones y comentarios, junto con la consulta de opiniones en redes sociales, ayuda a verificar la confiabilidad de CambiaZo. 
    <br>Además, estos intercambios ofrecen beneficios como el ahorro económico y una forma más sostenible de consumir, promoviendo el reciclaje y la reutilización para abordar la acumulación de productos no utilizados.
</td>
  </tr>
</tbody>
</table><br>


### **Segmento Donadores**<br>

<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #1<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Carlos Arturo</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Adrianzen Flores</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>20 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Miraflores</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom, Discord</td>
  </tr>
  <tr>
    <td>Motivacion</td>
    <td>Donar a lo mas necesitados a traves de la iglesias</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>Experimenta dificultades al llevar un canasto lleno de ropa para donar.</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>Smatphone Android, Laptop Windows</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Firefox</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Mathias Andre Mendoza Carrion</td>
  </tr>
   <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-II/Interviews/entrevista-Arturo-Adrianzen.PNG?raw=true" alt="Entrevista Arturo Adrianzen"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216282_upc_edu_pe/EYGbE4KNDtNLjRh61XjXqP8BKWSBYGr98SNL7tmmXDY5RQ?e=FEq7xt" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>20:46 min - 25:59 min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>Durante nuestra conversación con Arturo, exploramos su experiencia en intercambios y los desafíos que ha enfrentado al no tener una plataforma dedicada para realizarlos. Arturo compartió sus vivencias al realizar donaciones a la iglesia, describiendo las dificultades que encontró al llevar un canasto lleno de ropa, lo cual consideró una tarea tediosa. Propuso la idea de que, para facilitar el proceso de donación de objetos, sería conveniente que alguien se encargará de recogerlos, evitando así la molestia de tener que trasladarse hasta el lugar de donación. Además, resaltó la importancia de garantizar seguridad para los usuarios, sugiriendo medidas como la presentación de una foto que confirme la realización de la donación, con el fin de evitar cualquier tipo de desconfianza. Arturo realiza una sugerencia final y significativa para Cambiazo, el cual, sería crear conciencia sobre la importancia de cada objeto donado para las personas necesitadas. Esto podría lograrse mediante la divulgación de testimonios conmovedores de aquellos que se han visto directamente afectados por estas donaciones, lo que, a su vez, podría inspirar a más personas a contribuir y seguir apoyando esta noble causa de forma continua.
</td>
  </tr>
</tbody>
</table>


<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #2<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Hernan Emilio</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Morales Calderon</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>19 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>San Juan de Lurigancho</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom,Word</td>
  </tr>
  <tr>
    <td>Motivacion</td>
    <td>Donar su ropa a personas necesitadas</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>Limitaciones de tiempo para buscar alguna ong</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>Laptop Windows, Smartphone Android</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Joseph Alexis Huamani Mandujano</td>
  </tr>
   <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-II/Interviews/entrevista-Hernan-Morales.PNG?raw=true" alt="Entrevista Hernan Morales"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216282_upc_edu_pe/EYGbE4KNDtNLjRh61XjXqP8BKWSBYGr98SNL7tmmXDY5RQ?e=FEq7xt" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duracion<br></td>
    <td>25:59 min - 29:45 min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>Durante la entrevista, Hernan compartió su experiencia y perspectiva sobre el proceso de donación a través de su participación en actividades de caridad y su interacción con plataformas dedicadas a esta causa. Destacó su compromiso con contribuciones significativas, incluyendo alimentos no perecederos, vestimenta en buen estado y juguetes, los cuales destinó a instituciones benéficas locales y hogares de acogida para niños desfavorecidos en su comunidad.Asimismo, Hernán enfatizó la importancia de la seguridad de los datos personales y la confiabilidad de los sistemas utilizados en estas plataformas, destacando la necesidad de contar con funcionalidades de protección que aseguren la integridad de la información personal y financiera de los donantes.Además, manifestó su interés en seguir de cerca el progreso de sus donaciones y su impacto en la comunidad, así como en mantenerse informado sobre el prestigio de la plataforma, su transparencia en la gestión de fondos y los testimonios de otros usuarios. Hernán expresó su deseo de una experiencia de donación más accesible y sencilla, y sugirió mejoras en la interfaz de usuario y una mayor variedad de opciones de donación específicas para fomentar la solidaridad y proporcionar un medio más fácil para ayudar a quienes más lo necesitan en la comunidad.
</td>
  </tr>
</tbody>
</table>


<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #3<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Mathias Adriano</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Hidalgo Lopez</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>19 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Santiago de Surco</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom</td>
  </tr>
  <tr>
    <td>Motivacion</td>
    <td>Donar su ropa a personas necesitadas</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>Limitaciones de tiempo para buscar alguna ong</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>Laptop Windows, Smartphone Android</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Mathias Andre Mendoza Carrion</td>
  </tr>
   <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Interviews/mathiashidalgo_interview.png?raw=true" alt="Entrevista Mathias Hidalgo"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216282_upc_edu_pe/EYGbE4KNDtNLjRh61XjXqP8BKWSBYGr98SNL7tmmXDY5RQ?e=FEq7xt" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duracion<br></td>
    <td>29:45 min - 41:17 min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>Mathias Hidalgo ha participado en donaciones a través de centros de caridad y páginas web, aunque siempre ha tenido cierta inseguridad debido a la posibilidad de estafas y a la falta de confianza que le generaban algunos lugares. A pesar de estas preocupaciones, Mathias está profundamente comprometido con causas benéficas y tiene la intención de seguir donando, específicamente ropa, recursos alimenticios y juguetes para ayudar a quienes lo necesitan. Para la aplicación Cambiazo, Mathias busca una mayor confiabilidad en todo el proceso de donación. Considera esencial que la aplicación ofrezca funcionalidades de seguridad robustas, como un sistema de mapeo o seguimiento en tiempo real de los productos donados, así como la certificación de las donaciones para garantizar su transparencia y autenticidad. Estas medidas no solo le darían mayor tranquilidad, sino que también incrementarían la confianza en la plataforma. Además, espera que Cambiazo le permita ahorrar tiempo en los trámites burocráticos y el papeleo, haciendo que el proceso sea más eficiente y fácil de manejar para cualquier usuario, independientemente de su nivel de experiencia con la tecnología. Mathias cree firmemente que, aunque el impacto de la aplicación podría no ser masivo, sí tiene el potencial de generar un cambio positivo y significativo en la vida de muchas personas, contribuyendo de manera valiosa al desarrollo social y económico del país. Considera que una plataforma como Cambiazo, con las características adecuadas, podría convertirse en una herramienta poderosa para canalizar la generosidad de la gente y facilitar el acceso a bienes esenciales para quienes más lo necesitan.
</td>
  </tr>
</tbody>
</table>
<br>

<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #4<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Claudio Sandro </td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Quispesivana Torres</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>20 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>San Miguel</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Google</td>
  </tr>
    <tr>
    <td>Motivacion</td>
    <td>Adquisición de nuevos artículos sin tener que comprarlos</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>Preocupaciones sobre el destino de las donaciones.</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>Smartphone Android</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Diego Anderson Criollo De La Cruz</td>
  </tr>
    <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://raw.githubusercontent.com/Desarrollo-de-Soluciones-IoT-2510-2942/Informe/refs/heads/main/Resources/Chapter%2003/To-Be/Captura%20de%20pantalla%202025-09-15%20144350.png" alt="Entrevista Claudio Sandro"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216282_upc_edu_pe/EYGbE4KNDtNLjRh61XjXqP8BKWSBYGr98SNL7tmmXDY5RQ?e=FEq7xt" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>41:17 min - 48:47 min</td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>Claudio Sandro, estudiante de 20 años que vive en San Miguel, comenta que ha donado mediante campañas universitarias y parroquiales, entregas directas coordinadas por WhatsApp y transferencias por Yape a organizaciones verificadas; su experiencia ha sido mayormente satisfactoria cuando recibe confirmación de entrega. Suele preferir donar ropa en buen estado, útiles y libros, juguetes completos, así como celulares y laptops básicas a través de plataformas como CambiaZo. Entre sus principales inquietudes al usar CambiaZo por primera vez están la protección de sus datos, la verificación de receptores y la logística de recojo. Por ello considera clave una interfaz intuitiva, perfiles e instituciones verificadas, puntos de acopio o recojo programado, chat seguro y comprobantes con fotos y recibos digitales, además de un panel para seguir el destino de sus donaciones. Destaca la transparencia como requisito para confiar en la plataforma con validación de identidad y RUC, trazabilidad del artículo y reportes periódicos de impacto. Valora que el proceso sea ágil, con menos fricción y mayor seguridad, y que pueda medir su impacto por artículos entregados, personas beneficiadas, tiempo hasta la entrega y kilos de residuos evitados. Señala que mejoras como etiquetas de urgencia, donaciones grupales por universidad y opciones de accesibilidad harían a CambiaZo más efectivo. Finalmente opina que la personalización de causas, el seguimiento visible del impacto y la posibilidad de interactuar con beneficiarios fortalecerán la cohesión social y una comunidad más solidaria y conectada en Lima, empezando por su distrito de San Miguel.
</td>
  </tr>
</tbody>
</table>



### 2.2.3 Análisis de entrevistas

En esta sección presentaremos el análisis de cada entrevista realizada por cada segmento objetivo. Con el fin de tener una información concisa para el desarrollo de nuestra aplicación.

### **Segmento objetivo 1:** Personas adultas que desean obtener nuevos artículos (Intercambiadores).<br>

Las personas que realizan intercambios de objetos tienen edades comprendidas entre 18 y 55 años y residen mayoritariamente en Lima, Perú. Los usuarios recurren a redes sociales como WhatsApp y Facebook para llevar a cabo este tipo de intercambios, pero su experiencia ha sido, en la mayoría de los casos, negativa debido a problemas de calidad con los productos intercambiados y a la falta de seguridad en el uso de dichos métodos.

**Hallazgos Claves:**

- El 100% de los entrevistados ha tenido malas experiencias al realizar intercambios a través de redes sociales. Esto se debe principalmente a problemas con la calidad de los productos y a la falta de garantías. La falta de confianza en estos métodos resalta la necesidad urgente de una plataforma más segura y confiable para intercambiar objetos.


- La mayoría de los intercambiadores realiza intercambios de manera regular, lo cual indica una alta demanda de una plataforma que facilite el proceso de manera más organizada y segura.


- Todos los entrevistados creen que CambiaZo podría resolver sus problemas actuales. Las principales funcionalidades deseadas incluyen un sistema de calificaciones robusto, un chat seguro, y herramientas para la verificación de identidad y la calidad de los productos intercambiados.<br><br>


**Análisis por medio de herramientas estadísticas:**


<div align="center">
	<img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-1-grafica-1.PNG?raw=true" alt="Estadistica 1" style="width: 600px; height: auto;">
</div>


Las respuestas de nuestros entrevistados evidencian que sería beneficioso y útil para una gran cantidad de la población, lo cual también se comprueba con un estudio realizado del año 2015 al 2017 por la Universidad Nacional del Altiplano, Puno, en el cuál se obtuvo que el motivo principal por el cual las personas realizan trueques es por la falta de dinero.


<div align="center">
	<img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-1-grafica-2.PNG?raw=true" alt="Estadistica 2" style="width: 600px; height: auto;"><br><br>
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-1-grafica-3.PNG?raw=true" alt="Estadistica 3" style="width: 600px; height: auto;"><br><br>
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-1-grafica-4.PNG?raw=truee" alt="Estadistica 4" style="width: 600px; height: auto;"><br><br>
</div>

El 100% de los entrevistados utiliza redes sociales para realizar intercambios. Sin embargo, todos los usuarios se sienten inseguros al utilizar estos métodos debido a malas experiencias previas, ya que el 100% ha tenido problemas al realizar intercambios a través de redes sociales. Estas malas experiencias reflejan claramente la necesidad de una plataforma más segura y confiable.


<div align="center">
	<img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-1-grafica-5.PNG?raw=true" alt="Estadistica 5" style="width: 600px; height: auto;"><br><br>
</div>

La mayoría de los intercambiadores realiza trueques con regularidad. Este dato subraya la demanda existente de una plataforma que pueda gestionar estos intercambios de manera más eficiente.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-1-grafica-6.PNG?raw=true" alt="Estadistica 6" style="width: 600px; height: auto;"><br><br>
</div>


Finalmente, todos los entrevistados expresan su disposición a usar CambiaZo como su principal medio para realizar intercambios. Este dato destaca el potencial de la plataforma para satisfacer una necesidad significativa en el mercado.<br><br>

**Estrategias para Abordar las Necesidades de los Intercambiadores:**

Para satisfacer las necesidades de los intercambiadores, CambiaZo debe enfocarse en proporcionar una plataforma segura y confiable que aborde los problemas que los usuarios han experimentado con las redes sociales. Implementar un sistema de calificaciones robusto es crucial, ya que permitirá a los usuarios evaluar y confiar en la calidad de los productos y en la reputación de los intercambiadores.

Es fundamental incorporar un chat seguro para facilitar las negociaciones y coordinar intercambios sin comprometer la privacidad. Además, ofrecer herramientas efectivas para la verificación de identidad y la calidad de los productos ayudará a minimizar el riesgo de fraudes y garantizar la integridad de los intercambios.

La plataforma debe ser intuitiva y fácil de usar, para que los intercambiadores puedan gestionar sus productos y realizar intercambios con eficiencia. El análisis muestra que la mayoría de los usuarios realiza intercambios con regularidad y que todos están dispuestos a adoptar una nueva plataforma que resuelva sus actuales problemas. Por lo tanto, CambiaZo debe diseñar una experiencia de usuario que no solo resuelva los inconvenientes actuales, sino que también se adapte a la alta demanda y expectativas del segmento.

Al implementar estas mejoras, CambiaZo estará bien posicionada para ofrecer una solución valiosa a los intercambiadores, promoviendo un entorno de intercambio seguro, eficiente y confiable.<br><br>


### **Segmento objetivo 2:** Personas adultas que desean donar artículos que ya no utilizan (Donadores).<br>

Los donadores tienen entre 15 y 60 años y residen mayoritariamente en Lima, Perú. Su principal motivación es el deseo genuino de ayudar a los demás. Sin embargo, enfrentan varios problemas que dificultan el proceso de donación, como la necesidad de llevar los artículos a lugares lejanos y la falta de evidencia de recepción.

**Hallazgos Claves:**

- Los donadores enfrentan dificultades significativas en el proceso de donación. Estos problemas incluyen la necesidad de transportar los artículos a ubicaciones distantes y la ausencia de evidencia de recepción, lo que hace que el proceso sea tedioso y poco satisfactorio.


- Todos los donadores consideran que CambiaZo podría simplificar el proceso de donación. Proponen funcionalidades como el rastreo de donaciones, la confirmación de recepción y la opción de programar la recolección de artículos. Estas características ayudarían a superar las dificultades actuales y mejorar la experiencia de donación.


- Los donadores sugieren la realización de campañas de sensibilización y colaboraciones con influencers para aumentar la participación y la frecuencia de las donaciones. Estas estrategias podrían amplificar el alcance de la plataforma y fomentar un mayor compromiso con la causa de la donación.<br><br>

**Análisis por medio de herramientas estadísticas:**

<div align="center">
	<img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-2-grafica-1.PNG?raw=true" alt="Estadistica 7" style="width: 600px; height: auto;"><br><br>
</div>

El gráfico de frecuencia de donaciones revela que los donadores realizan donaciones en intervalos que van de mensuales a anuales. Este patrón sugiere una disposición a donar con regularidad, siempre que el proceso sea simplificado y más accesible.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-2-grafica-2.PNG?raw=true" alt="Estadistica 8" style="width: 600px; height: auto;"><br><br>
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-2-grafica-3.PNG?raw=true" alt="Estadistica 9" style="width: 600px; height: auto;"><br><br>
</div>

El 100% de los donadores considera que el proceso de donación es complicado. Esta percepción subraya la necesidad de una plataforma que simplifique y facilite cada paso del proceso de donación. Además, todos creen que el proceso es complicado, lo que destaca la urgencia de implementar soluciones que aborden estos problemas y mejoren la experiencia general.

<div align="center">
	<img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-2-grafica-4.PNG?raw=true" alt="Estadistica 10" style="width: 600px; height: auto;"><br><br>
</div>

La mayoría de los donadores considera que los juguetes y la ropa son los objetos más adecuados para donar. Esta preferencia puede guiar a la plataforma en la priorización de categorías de donación.

<div align="center">
	<img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-2-grafica-5.PNG?raw=true" alt="Estadistica 11" style="width: 600px; height: auto;"><br><br>
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-2-grafica-6.PNG?raw=true" alt="Estadistica 12" style="width: 600px; height: auto;"><br><br>
</div>

Todos los entrevistados mostraron su disposición para utilizar CambiaZo como su principal medio de donación. Además, creen que CambiaZo podría aumentar la frecuencia de sus donaciones, lo que resalta el potencial de la plataforma para facilitar y promover la donación.<br><br>

**Estrategias para Abordar las Necesidades de los Donadores:**

Para atender las necesidades de los donadores, CambiaZo debe enfocarse en simplificar el proceso de donación mediante la implementación de funcionalidades esenciales como la confirmación de recepción de artículos. Esta característica no solo proporciona tranquilidad a los donadores, sino que también cierra el ciclo de la donación de manera satisfactoria.

Además, el rastreo de donaciones es fundamental para asegurar que los artículos lleguen a sus destinatarios y para proporcionar a los donadores visibilidad sobre el impacto de sus contribuciones. La programación de recolección de artículos es otra funcionalidad crucial que facilita el proceso logístico y elimina la necesidad de desplazamientos complicados.

Garantizar la transparencia en el destino de las donaciones es vital para mantener la confianza de los donadores, permitiéndoles ver claramente cómo y a quién se destinan los artículos donados. Igualmente importante es la protección de los datos personales, que asegura la seguridad y privacidad de la información de los usuarios.

La aplicación web debe ser intuitiva y fácil de usar para no agregar barreras tecnológicas adicionales. Además, la implementación de campañas de sensibilización y colaboraciones con influencers ayudará a ampliar el alcance de la plataforma y a fomentar una mayor participación en las donaciones.

Al abordar estos aspectos, CambiaZo no solo mejorará la experiencia de donación, sino que también incrementará la frecuencia y el impacto de las contribuciones, haciendo que la plataforma sea una solución eficaz y apreciada por la comunidad.<br><br>


### Análisis General para Ambos Segmentos

<div align="center">
	<img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/sistemas-operativos-grafica.png?raw=truee" alt="Estadistica Android vs IOS" style="width: 600px; height: auto;"><br><br>
</div>

Como podemos observar en la gráfica obtenida de las entrevistas sobre los sistemas operativos de los smartphones utilizados por los entrevistados, se evidencia una clara predominancia de Android. De acuerdo con los datos recopilados, el 80% de los entrevistados utiliza este sistema operativo. 

Este alto porcentaje subraya la necesidad crítica de que CambiaZo sea completamente compatible con Android. La plataforma debe estar optimizada para aprovechar al máximo las características y capacidades de este sistema operativo, garantizando un rendimiento fluido y una experiencia de usuario sin interrupciones para la mayoría de los usuarios.

En contraste, el 20% de los entrevistados utiliza iOS. Aunque esta proporción es menor, sigue siendo significativa y no debe ser pasada por alto. Para asegurar que la plataforma sea accesible para todos, CambiaZo debe desarrollar y mantener una versión optimizada para dispositivos Apple. Esta atención a ambos sistemas operativos es crucial para proporcionar una experiencia uniforme y satisfactoria a todos los usuarios.


<div align="center">
	<img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/android-ios.png?raw=true" alt="Imagen Android y IOS"><br><br>
</div>

Para abordar adecuadamente estas necesidades, CambiaZo debe enfocarse en ofrecer una plataforma completamente funcional tanto para Android como para iOS. Esta estrategia no solo garantizará que la aplicación funcione de manera efectiva en ambos sistemas operativos, sino que también permitirá que todos los entrevistados, independientemente del dispositivo que utilicen, accedan a todas las funcionalidades y características de CambiaZo.

Además, la interfaz de CambiaZo debe ser intuitiva y fácil de usar. La simplicidad en el diseño y una navegación fluida son cruciales para garantizar que todos los usuarios, independientemente de su nivel de experiencia tecnológica, puedan utilizar la plataforma de manera efectiva. Al ofrecer una experiencia de usuario accesible y libre de complicaciones, CambiaZo podrá satisfacer las necesidades y expectativas de todos los entrevistados.<br><br>

## 2.3 Needfinding

En CambiaZo, entendemos que para desarrollar una plataforma que realmente responda a las necesidades de nuestros usuarios, es crucial conocerlas a fondo. La sección de Needfinding refleja nuestro compromiso con este objetivo a través de una investigación detallada.

Nos dedicamos a identificar y analizar a nuestros usuarios mediante la creación de User Persona, User Task Matrix, User Journey Maps, Empathy , As-Is Scenario Mapping y To-Be Scenario Mapping. Este enfoque nos permite diseñar una experiencia de intercambio y donación que sea tanto efectiva como alineada con las expectativas de quienes utilizan nuestra plataforma.

A continuación, exploraremos cómo estos métodos nos ayudarán a construir una solución que satisfaga y supere las demandas de nuestros usuarios.

### 2.3.1 User Personas

Después de analizar las entrevistas de nuestro segmento objetivo, nuestra tarea es definir el perfil del usuario ideal con el que estamos tratando. Hemos elaborado los perfiles de usuario teniendo en cuenta las personalidades y cualidades identificadas en cada entrevista. A continuación, se presentan las user personas resultantes de la investigación:

<b>Usuario Intercambiador</b><br>

<div align="center">

![User Persona 1](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Needfinding/User-Persona/user-persona-1.PNG?raw=true)
</div>

<br><br>

<b>Usuario Donador</b><br>

<div align="center">

![User Persona 2](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Needfinding/User-Persona/user-persona-2.PNG?raw=true)
</div>

<br><br>

### 2.3.2 User Task Matrix

Para diseñar una plataforma que responda eficazmente a las necesidades de nuestros usuarios, en CambiaZo hemos desarrollado una User Task Matrix. 

En esta sección, presentamos un análisis detallado de las tareas que los usuarios, tanto Intercambiadores como Donadores, realizan para alcanzar sus objetivos. Cada tarea se evalúa en función de su frecuencia y la importancia que los usuarios le atribuyen, permitiéndonos enfocar el diseño de nuestra aplicación en lo que realmente importa para ellos.



<b>Usuario Intercambiador</b><br>

<div align="center">
<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th rowspan="2"><div align="center">USER TASK</div><br></th>
    <th colspan="2"><div align="center">Intercambiador <br>Carlos Flores<br></div></th>
   
  </tr>
  <tr>
    <th>Frecuencia</th>
    <th>Importancia</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Buscar objetos para intercambiar<br></td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Contactar Usuarios para Intercambiar<br></td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Coordinar Condiciones del Intercambio<br></td>
    <td>Alta</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Confirmar Acuerdo de Intercambio<br></td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Evaluar Experiencia de Intercambio<br></td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
</tbody>
</table>
</div><br><br>

<b>Usuario Donador</b><br>

<div align="center">
<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th rowspan="2"><div align="center">USER TASK</div><br></th>
    <th colspan="2"><div align="center">Donador <br>Mariana Okinawa<br></div></th>
   
  </tr>
  <tr>
    <th>Frecuencia</th>
    <th>Importancia</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Buscar organizaciones para donar<br></td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
     <td>Seleccionar Artículo para Donar<br></td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Coordinar Entrega de Donación<br></td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Preparar Artículos para Donación<br></td>
    <td>Media</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Entregar Donación a la Organización<br></td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
</tbody>
</table>
</div>

### 2.3.3 Empathy Mapping

Lo siguiente a evaluar como parte del needfinding es a nuestros segmentos objetivos a través de empathy maps, con el objetivo de conocer mejor a nuestros segmentos objetivos e identificar sus necesidades profundas.

<b>Segmento Intercambiadores</b><br>

<div align="center">

![Empathy Mapping.](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Needfinding/Empathy-Mapping/empathy-map-1.PNG?raw=true)
</div><br><br>

<b>Segmento Donadores</b><br>

<div align="center">

![Empathy Mapping.](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Needfinding/Empathy-Mapping/empathy-map-2.PNG?raw=true)
</div><br><br>

### 2.3.4 As-Is Scenario Mapping

En esta sección, exploraremos los escenarios actuales de los usuarios, mapeando cómo interactúan con los procesos y herramientas existentes. El As-Is Scenario Mapping nos permitirá entender las prácticas actuales y detectar áreas de mejora para optimizar la experiencia del usuario en nuestra plataforma.<br><br>

<b>Segmento Intercambiadores</b><br>


<div align="center">

![As-Is Scenario Mapping.](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Needfinding/As-Is-Scenario-Mapping/as-is-scenario-1.PNG?raw=true)
</div>


<br><br>

<b>Segmento Donadores</b><br>

<div align="center">

![As-Is Scenario Mapping.](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Needfinding/As-Is-Scenario-Mapping/as-is-scenario-2.PNG?raw=true)
</div>

<br><br>


## 2.4 Ubiquitous Language.
En esta sección, se establece un glosario de términos clave del dominio de negocio, conforme al enfoque de Ubiquitous Language propuesto por Eric Evans en Domain-Driven Design. Este glosario proporciona definiciones claras y sin ambigüedades de los conceptos utilizados en el ámbito específico del problema y la solución abordados, facilitando una comunicación efectiva entre todos los miembros del equipo.

+ **Subscription (Subscripción):** An arrangement where users sign up for a service or access to a product on a recurring basis, often for a specific duration, in exchange for certain benefits or features. Subscriptions typically involve the payment of a recurring fee, and they may offer various levels or tiers of access, each providing different features, benefits, or limitations. Users may subscribe to gain access to premium content, exclusive features, or enhanced functionality within the platform.<br><br>

+ **Plan (Plan):** Different tiers or levels of subscription offering varying features, benefits, or limitations. Plans are structured to cater to the diverse needs and preferences of users, providing options that align with their usage patterns, budget constraints, or desired level of engagement. These plans may be designed to cater to different user segments, such as casual users, power users, or businesses, and they often dictate the scope of access and available features within the platform.<br><br>

+ **Exchange (Intercambio):** The act of swapping objects between users, typically facilitated by the platform. Exchanges may involve the direct trade of items between users, where one user offers an object in exchange for another object offered by a different user. Alternatively, exchanges may involve indirect transactions facilitated by the platform, where users list objects they wish to exchange, and the platform matches them with other users interested in those items. Exchanges promote the circulation of goods within the community, fostering a collaborative and sustainable consumption model.<br><br>

+ **Guarantees (Garantías):** Assurances provided by the platform to users regarding the quality, authenticity, or condition of exchanged objects. Guarantees serve to instill confidence in users, assuring them that the objects they receive through exchanges meet certain standards and expectations. These guarantees may include policies for verifying the authenticity of items, conducting quality inspections, or providing recourse in the event of disputes or issues with exchanged objects.<br><br>

+ **Advertisements (Anuncios)** Promotional content displayed on the platform to generate interest or revenue. Advertisements may take various forms, including banner ads, sponsored content, or targeted promotions, and they are often tailored to the interests, preferences, or demographics of users. Advertisements may be used to promote relevant products, services, or events to users, and they may serve as a source of revenue for the platform through advertising partnerships or pay-per-click arrangements.<br><br>

+ **Donation (Donaciones):** Contributions made by users in the form of objects or monetary support to individuals or organizations. Donations reflect acts of generosity and altruism within the community, allowing users to support causes they care about or assist those in need. Users may donate objects they no longer need or use, providing them to individuals or organizations that can benefit from them. Additionally, users may make monetary donations to support charitable initiatives, nonprofit organizations, or community projects facilitated by the platform.<br><br>

+ **Physical Donation (Donación física):** Donating physical objects by providing an address for drop-off. Physical donations involve the transfer of tangible items from one user to another, typically through arrangements for pickup or delivery. Users may offer physical donations to other users directly, arranging for the exchange of objects through personal interactions or logistics coordinated within the platform. Physical donations contribute to resource sharing and waste reduction efforts, enabling users to repurpose or recycle items they no longer need.<br><br>

+ **Monetary Donation (Donación monetaria):** Contributing money to a specified account, typically belonging to a non-profit organization. Monetary donations involve the transfer of funds from one user to another, often in support of charitable causes, humanitarian efforts, or community initiatives. Users may donate money to nonprofit organizations, charitable foundations, or crowdfunding campaigns endorsed by the platform, providing financial support to causes aligned with their values or interests. Monetary donations may be used to fund various projects, programs, or activities that benefit the community or address societal needs.<br><br>

+ **Transaction (Transacción):** A financial exchange or operation carried out between users or involving the platform. Transactions encompass a wide range of interactions within the platform, including purchases, sales, exchanges, donations, or payments. Users engage in transactions to acquire, exchange, or transfer goods, services, or funds, utilizing the platform's features and functionalities to facilitate these exchanges securely and efficiently. Transactions may involve the transfer of virtual assets, such as digital currency or credits, as well as the exchange of physical goods or monetary payments.<br><br>

+ **Categories (Categorías):** Groupings or classifications used to organize objects, organizations, or content for easier navigation and searchability. Categories serve as a taxonomy or hierarchical structure within the platform, grouping related items or entities based on shared characteristics, attributes, or properties. Users can browse or filter content within specific categories to narrow down their search results and find relevant information more efficiently. Categories may be predefined by the platform or created dynamically based on user-generated content, reflecting the diverse interests and preferences of the community.<br><br>

+ **User Limit (Límite de usuario):** The maximum number of objects a user can publish or display on the platform within a given timeframe. User limits impose restrictions on the quantity or volume of content that individual users can contribute or showcase within the platform, preventing abuse, spam, or excessive clutter. These limits may be enforced to maintain a balanced and equitable distribution of resources among users, ensuring fair access to platform features and functionalities. Users may encounter user limits based on their subscription level, account status, or platform policies, with options to increase limits through upgrades or premium memberships.<br><br>

+ **Space Allocation (Asignación de espacio):** The allocation of virtual real estate or capacity on the platform for users to publish or display their objects. Space allocation involves the provision of digital resources, such as storage capacity, bandwidth, or display area, to accommodate user-generated content within the platform. Users are allotted a certain amount of space or resources based on their subscription plan, account settings, or platform privileges, dictating the extent to which they can contribute or showcase objects, advertisements, or other content. Space allocation may be managed dynamically to accommodate fluctuations in user activity or demand, optimizing resource utilization and user experience within the platform.<br><br>

+ **User (Usuario):** An individual who interacts with the platform, either by subscribing, publishing objects, or engaging in exchanges. Users represent the primary stakeholders and participants within the platform ecosystem, contributing content, generating activity, and shaping the community dynamics. Users may vary in their roles, behaviors, and preferences, ranging from content creators and contributors to consumers and participants. The platform's features, functionalities, and policies are designed to cater to the needs, interests, and expectations of users, fostering a positive and engaging user experience.<br><br>

# Capítulo III: Requirements Specification

###  3.1. To-Be Scenario Mapping

En esta sección, visualizaremos los escenarios futuros propuestos para nuestros usuarios, ilustrando cómo deberían evolucionar los procesos y herramientas para mejorar la experiencia en nuestra plataforma. El To-Be Scenario Mapping nos ayudará a diseñar soluciones optimizadas que respondan a las necesidades identificadas y faciliten un flujo de trabajo más eficiente y satisfactorio.


<b>Segmento Intercambiadores</b><br>

<div align="center">

![To-Be Scenario Mapping.](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Needfinding/To-Be-Scenario-Mapping/to-be-scenario-1.png?raw=true)
</div>

<br><br>

<b>Segmento Donadores</b><br>

<div align="center">

![To-Be Scenario Mapping.](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Needfinding/To-Be-Scenario-Mapping/to-be-scenario-2.png?raw=true)
</div>


<br><br>



## 3.2. User Stories

En esta sección, profundizaremos en la definición y elaboración de las User Stories relacionadas con nuestro proyecto. Las User Stories son una herramienta fundamental en el desarrollo de software y proyectos de diseño centrados en el usuario.

### EPICS

| **EP01: Gestión de Cuenta de Usuario** | Como usuario, quiero tener el control total sobre mi cuenta para gestionarla según mis necesidades. |
| :-- | :-- |
| **User Story ID** | **Título** |
| US01 | Registro de usuario |
| US02 | Editar perfil del usuario |
| US03 | Iniciar sesión en la aplicación |
| US04 | Cambiar Contraseña |
| US05 | Cerrar Sesión |
| US09 | Eliminación de cuenta |
| US20 | Adquirir la suscripción premium |
| US21 | Cancelar una suscripción |
| US23 | Gestionar mis favoritos en la aplicación |
| US24 | Ver reseñas recibidas |

<br>

| **EP02: Funcionalidades de Intercambio** | Como usuario de la aplicación, quiero acceder a una variedad de funcionalidades relacionadas con el intercambio de objetos, para facilitar la búsqueda, creación y gestión de publicaciones de intercambio. |
| :-- | :-- |
| **User Story ID** | **Título** |
| US06 | Filtrado de Objetos |
| US10 | Visualización de artículos publicados para intercambio |
| US11 | Realización de una oferta de intercambio |
| US12 | Crear publicación de intercambio |
| US13 | Editar publicación de intercambio |
| US14 | Eliminar publicación de intercambio |
| US15 | Gestión de intercambios |
| US16 | Visualización de objetos disponibles para intercambio |
| US18 | Aceptar o Rechazar un Intercambio |
| US19 | Ver la información detallada de un producto publicado |
| US31 | Aplicar sugerencias con IA |
| US32 | Rellenado automático con Gemini al subir nueva imagen |

<br>

| **EP03: Funcionalidades de Reseñas y ONGs** | Como usuario de la aplicación, quiero interactuar con las ONGs y gestionar reseñas para mejorar la experiencia de intercambio y donación. |
| :-- | :-- |
| **User Story ID** | **Título** |
| US07 | Visualización de ONGs registradas y filtrado |
| US08 | Brindar reseña sobre el Intercambiador |
| US17 | Visualizar el perfil del usuario que publique un producto |
| US22 | Visualizar el perfil de las ONG’s registradas |

<br>

| **EP04: Información y Navegación de la Landing Page** | Como usuario visitante de la landing page de la aplicación web, deseo acceder a información relevante y navegar fácilmente para obtener una comprensión clara de las características y funcionalidades ofrecidas. |
| :-- | :-- |
| **User Story ID** | **Título** |
| US25 | Visualización de la Historia de la Startup |
| US26 | Visualizar las características clave de la aplicación |
| US27 | Acceder a un formulario para llenar mis datos de contacto y recibir noticias relacionadas con CambiaZo |
| US28 | Descargar la aplicación de CambiaZo / Acceder a la página principal |
| US29 | Ver los planes y precios |
| US30 | Navegación en la Landing Page |

<br>

| **EP05: Desarrollo de Funcionalidades de la API de CambiaZo** | Como equipo de desarrollo, queremos implementar una serie de funcionalidades en la API de la aplicación para gestionar usuarios, reseñas, ONGs y suscripciones, con el fin de mejorar la experiencia del usuario y garantizar un funcionamiento eficiente de la plataforma. |
| :-- | :-- |
| **User Story ID** | **Título** |
| TS01 | API User |
| TS02 | API Exchanges |
| TS03 | API ONGs |
| TS04 | API Memberships |
| TS05 | API Products |

<br><br>

**USER STORIES**

|**Epic/User Story ID**|**Título**|**Descripción**|**Criterio de aceptación**|**Relación (EPIC ID)**|
| - | - | - | - | - |
|**US01**|Registro de usuario|Como nuevo usuario quiero completar el proceso de registro en la aplicación para establecer mi propia cuenta.|<p>**Escenario 1: Acceso del usuario a la página de registro**</p><p>**Dado** **que** el usuario ha accedido a la aplicación (web o móvil),<br>**Cuando** se encuentra en la sección de "Inicio de sesión"<br>**Y** opta por pulsar el botón "Registrarse",<br>**Entonces** la aplicación mostrará la página de registro.</p><p>**Escenario 2: Registro exitoso del usuario**</p><p>**Dado** **que** el usuario está en la página de registro,<br>**Cuando** introduce la información requerida<br>**Y** pulsa el botón "Registrarse",<br>**Entonces** la aplicación completará el proceso de registro<br>**Y** guardará la cuenta del usuario.</p><p>**Escenario 3: Registro con datos inválidos**</p><p>**Dado** **que** el usuario está en la página de registro,<br>**Cuando** proporciona información incompleta o no válida<br>**Y** pulsa el botón "Registrarse",<br>**Entonces** la aplicación mostrará un mensaje de error<br>**Y** no permitirá completar el registro.</p>|**EP01**|
|**US02**|Editar perfil del usuario|Como usuario ya registrado quiero realizar modificaciones en mi perfil para asegurarme de que mi información esté siempre actualizada.|<p>**Escenario 1: Acceso del usuario a "Mi perfil"**</p><p>**Dado** **que** el usuario ha iniciado sesión,<br>**Cuando** accede a la opción "Mi perfil" desde el menú principal,<br>**Entonces** la aplicación mostrará la página con la información del perfil.</p><p>**Escenario 2: El usuario elige editar su perfil**</p><p>**Dado** **que** el usuario está en la página "Mi perfil",<br>**Cuando** pulsa el botón "Editar perfil",<br>**Entonces** la aplicación mostrará la interfaz para modificar los datos personales.</p><p>**Escenario 3: Actualización exitosa de perfil**</p><p>**Dado** **que** el usuario se encuentra en la sección de edición de perfil,<br>**Cuando** introduce sus nuevos datos<br>**Y** pulsa el botón "Guardar cambios",<br>**Entonces** la aplicación actualizará su información correctamente.</p><p>**Escenario 4: Datos inválidos al editar perfil**</p><p>**Dado** **que** el usuario está editando su perfil,<br>**Cuando** ingresa información incompleta o inválida<br>**Y** pulsa "Guardar cambios",<br>**Entonces** la aplicación mostrará un mensaje de error<br>**Y** no guardará los datos.</p><p></p>|**EP01**|
|**US03**|Iniciar sesión en la aplicación|Como usuario registrado quiero iniciar sesión en la aplicación para poder acceder a todas sus funcionalidades.|<p>**Escenario 1: Acceso a la página de inicio de sesión**</p><p>**Dado** **que** el usuario accede a la aplicación sin haber iniciado sesión previamente,<br>**Cuando** selecciona la opción "Iniciar sesión",<br>**Entonces** se mostrará la página de autenticación.</p><p>**Escenario 2: Inicio de sesión exitoso**></p><p>**Dado** **que** el usuario está en la página de inicio de sesión,<br>**Cuando** introduce credenciales válidas<br>**Y** pulsa el botón "Iniciar sesión",<br>**Entonces** el sistema autenticará al usuario<br>**Y** lo redirigirá a la página principal.</p><p>**Escenario 3: Fallo en el inicio de sesión**</p><p>**Dado** **que** el usuario está en la página de inicio de sesión,<br>**Cuando** introduce credenciales incorrectas<br>**Y** pulsa "Iniciar sesión",<br>**Entonces** la aplicación mostrará un mensaje de error indicando que las credenciales son inválidas.</p>|**EP01**|
|**US04**|Cambiar Contraseña|Como usuario registrado, quiero realizar cambios en la contraseña de mi cuenta para reforzar la seguridad de mi cuenta.|<p>**Escenario 1: Acceso a la opción de cambio de contraseña**</p><p>**Dado que** el usuario ha iniciado sesión en la aplicación (web o móvil),<br>**Cuando** acceda a la sección de configuración de la cuenta,<br>**Entonces** la aplicación mostrará la opción para modificar la contraseña.</p><p>**Escenario 2: Cambio exitoso de la contraseña**</p><p>**Dado que** el usuario está en la página o sección de cambio de contraseña,<br>Cuando ingrese su contraseña actual y la nueva contraseña dos veces<br>**Y** pulse el botón "Cambiar Contraseña",<br>**Entonces** la aplicación ejecutará el cambio de contraseña<br>**Y** mostrará un mensaje de confirmación.</p><p>*Escenario 3: Intento de cambio fallido**</p><p>**Dado que** el usuario se encuentra en la sección de cambio de contraseña,<br>**Cuando** ingrese una contraseña actual incorrecta o incompleta, seguida de la nueva contraseña dos veces<br>**Y** pulse el botón "Cambiar Contraseña",<br>**Entonces** la aplicación mostrará un mensaje de error indicando que la contraseña actual es incorrecta.</p><p></p>|**EP01**|
|**US05**|Cerrar Sesión|Como usuario registrado quiero cerrar sesión en la aplicación para asegurarme de que mi cuenta no quede almacenada en mi dispositivo web.|<p><**Escenario 1: Acceso a la opción de cerrar sesión**</p><p>**Dado que** el usuario ha iniciado sesión en la aplicación (web o móvil),<br>**Cuando** acceda a la sección de configuración de la cuenta,<br>**Entonces** la aplicación mostrará la opción para cerrar sesión.</p><p>**Escenario 2: Cierre de sesión exitoso**</p><p>**Dado que** el usuario se encuentra en la página o sección de cierre de sesión,<br>**Cuando** seleccione el botón "Cerrar Sesión",<br>**Entonces**, la aplicación concluirá la sesión del usuario<br>**Y** lo redirigirá a la página de inicio de sesión.</p><p></p>|**EP01**|
|**US06**|Filtrado de Objetos|Como usuario Intercambiador, quiero la capacidad de filtrar los objetos disponibles de intercambio para encontrar la opción que mejor se adapte a mis preferencias de intercambio.|<p>**Escenario 1: Aplicación de filtros**</p><p>**Dado que** el usuario está en la sección de objetos disponibles para intercambio,<br>**Cuando** seleccione filtros específicos (como categoría, ubicación y precio)<br>**Y** pulse el botón "Aplicar Filtros",<br>**Entonces** la lista de objetos se ajustará automáticamente según los criterios seleccionados.</p><p>**Escenario 2: Visualización de resultados filtrados**</p><p>**Dado que** el usuario ha aplicado filtros,<br>**Cuando** la aplicación muestra únicamente los objetos que cumplen con los criterios seleccionados,<br>**Entonces** el usuario puede explorar los resultados filtrados según sus preferencias.</p><p>**Escenario 3: Sin resultados al aplicar filtros**</p><p>**Dado que** el usuario ha aplicado uno o varios filtros en la lista de objetos</p><p>**Cuando** no se encuentran objetos que cumplan con los criterios seleccionados</p><p>**Entonces** la aplicación mostrará un mensaje indicando que no hay resultados disponibles con esos filtros</p><p>Y sugerirá al usuario ajustar o eliminar algunos filtros para ampliar la búsqueda.</p>|**EP02**|
|**US07**|Visualización de ONGs registradas |Como usuario Donante, quiero visualizar la lista de ONGs registradas y poder filtrarlas por nombre usando el buscador, para encontrar la ONG específica en la cual me gustaría hacer mi donación.|<p>**Escenario 1: Visualización por defecto**<br>**Dado que** el usuario ha accedido a la sección de ONGs registradas,<br>**Cuando** no ha ingresado ningún término en la barra de búsqueda,<br>**Entonces** la aplicación mostrará por defecto una lista con la imagen de logo, nombre, tipo de organización y ubicación de cada ONG.</p><p>**Escenario 2: Búsqueda por nombre**<br>**Dado que** el usuario está en la sección de ONGs,<br>**Cuando** escribe el nombre o parte del nombre de una ONG en la barra de búsqueda<br>**Y** confirma la búsqueda (presionando "Enter" o haciendo clic en el icono de búsqueda),<br>**Entonces** la lista se actualizará mostrando únicamente las ONGs cuyo nombre coincida con el texto ingresado.</p><p></p>|**EP03**|
|**US08**|Brindar reseña sobre el Intercambiador|Como usuario intercambiador, deseo dejar una reseña sobre mi experiencia con el intercambiador para que otros usuarios puedan leer y considerar mi opinión antes de intercambiar|<p>**Escenario 1: Dejar una reseña**</p><p>**Dado que** el usuario ha completado un intercambio,<br>**Cuando** accede a la sección correspondiente a esa experiencia,<br>**Entonces** encontrará una opción para dejar una reseña sobre el otro usuario.</p><p>**Escenario 2: Visualización de reseñas**</p><p>**Dado que** otros usuarios exploran las experiencias de intercambio,<br>**Cuando** acceden a las reseñas dejadas por otros,<br>**Entonces** pueden leer y considerar las opiniones antes de iniciar un intercambio.</p>|**EP03**|
|**US09**|Eliminación de cuenta|Como usuario, quiero tener la opción de eliminar permanentemente mi cuenta para evitar que mi información persista en caso de que ya no desee utilizar la aplicación|<p>**Escenario 1: Acceso a la opción de eliminación**<br>**Dado que** el usuario está registrado en la aplicación,<br>**Cuando** desee eliminar su cuenta,<br>**Entonces** encontrará una opción claramente visible en la configuración de cuenta que le permita eliminarla.</p><p>**Escenario 2: Confirmación de eliminación**<br>**Dado que** el usuario selecciona la opción de eliminar su cuenta,<br>**Cuando** confirme su elección,<br>**Entonces** se mostrará un mensaje solicitando una segunda confirmación antes de proceder.</p><p>**Escenario 3: Eliminación exitosa**<br>**Dado que** el usuario ha confirmado la eliminación,<br>**Cuando** la acción es procesada,<br>**Entonces** todos los datos asociados a la cuenta son eliminados permanentemente y esta se desactiva en ambas versiones de la aplicación.</p>|**EP01**|
|**US10**|Visualización de artículos publicados para intercambio|Como usuario de la aplicación de intercambio, quiero ver los artículos que he publicado, para revisar cuáles están disponibles para intercambio.|<p>**Escenario 1: Sin artículos publicados**<br>**Dado que** el usuario no ha publicado artículos,<br>**Cuando** accede a la sección “Mis artículos”,<br>**Entonces** verá un mensaje que lo invita a publicar, junto a un botón destacado “+ Publicar”.</p><p>**Escenario 2: Con artículos publicados**<br>**Dado que** el usuario ya publicó artículos,<br>**Cuando** accede a “Mis artículos”,<br>**Entonces** visualizará sus artículos en tarjetas con imagen, nombre y estado.</p><p>**Escenario 3: Opciones de un artículo**<br>**Dado que** el usuario tiene uno o más artículos,<br>**Cuando** presiona el botón de opciones (tres puntos) en una tarjeta,<br>**Entonces** se desplegará un menú con acciones disponibles para ese artículo.</p>|**EP02**|
|**US11**|Realización de una oferta de intercambio|Como usuario de la aplicación de intercambio, quiero seleccionar uno de mis artículos y enviarlo como oferta de intercambio, para poder ofrecerlo a cambio de otro artículo publicado por otro usuario.|<p>**Escenario 1: Usuario con artículos publicados**<br>**Dado que** el usuario desea intercambiar un artículo,<br>**Cuando** presiona el botón “Ofertar”,<br>**Entonces** verá una lista de sus artículos disponibles y podrá seleccionar uno para la oferta.</p><p>**Escenario 2: Confirmación de oferta**<br>**Dado que** el usuario ha seleccionado un artículo,<br>**Cuando** confirme la oferta,<br>**Entonces** se le mostrará una pantalla con detalles del artículo ofrecido y solicitado,<br>**Y** podrá confirmar presionando “Listo”.</p><p>**Escenario 3: Oferta enviada con éxito**<br>**Dado que** la oferta fue confirmada,<br>**Cuando** se envíe correctamente,<br>**Entonces** se mostrará un mensaje “¡Oferta Enviada!”<br>**Y** se notificará al usuario que la otra parte recibirá la oferta.</p><p></p>|**EP02**|
|**US12**|Crear publicación de intercambio|Como usuario de la aplicación, quiero poder crear una nueva publicación de intercambio para ofrecer un artículo que deseo intercambiar|<p>**Escenario 1: Creación de publicación**<br>**Dado que** el usuario accede a la opción de crear una publicación,<br>**Cuando** complete el formulario con título, descripción, categoría y condición del artículo,<br>**Entonces** podrá adjuntar imágenes y enviar el formulario.</p><p>**Escenario 2: Publicación creada exitosamente**<br>**Dado que** el formulario está completo,<br>**Cuando** el usuario lo envíe,<br>**Entonces** la aplicación validará los campos<br>**Y** creará la publicación exitosamente.</p><p>**Escenario 3: Visualización de publicación**<br>**Dado que** la publicación ha sido creada,<br>**Cuando** el usuario acceda a su perfil y luego a “Mis artículos”,<br>**Entonces** verá la nueva publicación reflejada en la lista de artículos.</p>|**EP02**|
|**US13**|Editar publicación de intercambio|Como usuario, necesito la capacidad de editar una publicación de intercambio existente para realizar cambios en los detalles del artículo o actualizar la información relevante.|<p>**Escenario 1: Acceso a la edición de una publicación de intercambio**<br>**Dado que** el usuario ha iniciado sesión en la aplicación (web o mobile)<br>**Y** tiene una publicación existente,<br>**Cuando** el usuario pulsa la opción de editar la publicación desde la interfaz,<br>**Entonces** el sistema redirige a un formulario prellenado con los detalles actuales de la publicación para realizar cambios<br>**Y** se muestran dos botones: “Cancelar” y “Publicar”.</p><p>**Escenario 2: Edición de la publicación confirmada**<br>**Dado que** el usuario está en el formulario de edición de la publicación,<br>**Cuando** realiza cambios en los detalles del artículo como título, descripción, categoría o condición,<br>**Y** pulsa el botón “Publicar”,<br>**Entonces** el sistema guardará los cambios y la publicación actualizada será visible para los demás usuarios.</p><p>**Escenario 3: Edición cancelada**<br>**Dado que** el usuario está en el formulario de edición,<br>**Cuando** realiza cambios y pulsa el botón “Cancelar”,<br>**Entonces** el sistema lo redirige a la pantalla de inicio de la aplicación.</p>|**EP02**|
|**US14**|Eliminar publicación de intercambio|Como usuario, quiero tener la opción de eliminar una publicación de intercambio que ya no deseo ofrecer para intercambiar.|<p>**Escenario 1: Acceso a la eliminación**<br>**Dado que** el usuario ha iniciado sesión y tiene publicaciones,<br>**Cuando** accede a la opción de eliminar una publicación desde la interfaz (web o mobile),<br>**Entonces** el sistema mostrará un mensaje de confirmación.</p><p>**Escenario 2: Confirmación de eliminación**<br>**Dado que** el usuario ha seleccionado eliminar,<br>**Cuando** confirma la acción,<br>**Entonces** el sistema elimina la publicación de forma permanente<br>**Y** muestra un mensaje de confirmación.</p><p>` `**Escenario 3: Cancelación de eliminación**<br>**Dado que** el usuario ha iniciado la eliminación,<br>**Cuando** cancela la acción,<br>**Entonces** la publicación no se elimina<br>**Y** el sistema redirige al usuario al inicio.</p>|**EP02**|
|**US15**|Gestión de intercambios|Como usuario de la aplicación, quiero revisar el estado de los intercambios que he enviado, recibido o aceptado, para poder ver los detalles y gestionar mis transacciones de intercambio de manera eficiente.|<p>**Escenario 1: Revisión de enviados**<br>**Dado que** estoy en la sección de Intercambios,<br>**Cuando** selecciono la pestaña “Enviados”,<br>**Entonces** veré una lista con los objetos ofrecidos y su estado<br>**Y** podré ver más detalles al seleccionarlos.</p><p>**Escenario 2: Revisión de recibidos**<br>**Dado que** estoy en la misma sección,<br>**Cuando** selecciono “Recibidos”,<br>**Entonces** veré una lista de ofertas con detalles y opciones para aceptarlas o rechazarlas.</p><p>**Escenario 3: Revisión de aceptados**<br>**Dado que** estoy en la pestaña “Aceptados”,<br>**Cuando** selecciono un intercambio,<br>**Entonces** podré ver los detalles y dejar una reseña si lo deseo.</p>|**EP02**|
|**US16**|Visualización de objetos disponibles para intercambio|Como usuario, necesito poder ver objetos disponibles para intercambio, de manera que pueda navegar y seleccionar aquellos que me interesen.|<p>**Escenario 1: Visualización**<br>**Dado que** el usuario ha iniciado sesión,<br>**Y** accede a la sección de “Explorar o Home” (desde web o mobile),<br>**Cuando** entra a esa sección,<br>**Entonces** el sistema mostrará: barra de búsqueda, categorías y publicaciones con foto, valor, nombre, ubicación y descripción.</p><p>**Escenario 2: Búsqueda**<br>**Dado que** el usuario está en “Explorar o Home”,<br>**Cuando** usa la barra de búsqueda,<br>**Entonces** el sistema mostrará resultados que coincidan, con la misma información visual.</p>|**EP02**|
|**US17**|Visualizar el perfil del usuario que publique un producto|Como usuario, me gustaría tener la capacidad de visualizar el perfil de la persona que haya publicado un intercambio, para poder obtener información detallada de su confiabilidad.|<p>**Escenario 1: Acceso al perfil**<br>**Dado que** estoy en una publicación,<br>**Cuando** toco o hago clic en el recuadro del autor,<br>**Entonces** podré ver su nombre, tiempo en la app, intercambios exitosos y valoraciones.</p><p>**Escenario 2: Reseñas**<br>**Dado que** estoy en el perfil del usuario,<br>**Cuando** entro a la sección “Reseñas”,<br>**Entonces** podré ver todas las reseñas recibidas y datos relevantes.</p>|**EP03**|
|**US18**|Aceptar o Rechazar un Intercambio|Como usuario que ha recibido una oferta de intercambio, quiero poder revisar los detalles de la oferta y tomar una decisión para aceptar o rechazar el intercambio, para poder gestionar mis transacciones de manera eficiente y asegurada.|<p>**Escenario 1: Revisión de oferta**<br>**Dado que** estoy en “Intercambios”,<br>**Cuando** selecciono una oferta pendiente,<br>**Entonces** veré todos los detalles y opciones para aceptarla o rechazarla.</p><p>**Escenario 2: Aceptar oferta**<br>**Dado que** estoy viendo una oferta,<br>**Cuando** presiono “Aceptar”,<br>**Entonces** se muestra un popup de confirmación y la oferta pasa a “Aceptados”.</p><p>**Escenario 3: Rechazar oferta**<br>**Dado que** estoy viendo una oferta,<br>**Cuando** presiono “Rechazar”,<br>**Entonces** se muestra un popup con mensaje de advertencia.</p><p>` `**Escenario 4: Confirmación del rechazo**<br>**Dado que** he presionado “Rechazar oferta”,<br>**Cuando** confirmo la acción,<br>**Entonces** la oferta se elimina y no puede recuperarse.</p><p></p>|**EP02**|
|**US19**|Ver la información detallada de un producto publicado|Como usuario de la aplicación, quiero poder ver la información completa de un producto en el que estoy interesado, para poder decidir si quiero guardarlo en mis favoritos o proponer un intercambio.|<p>**Escenario 1: Ver detalles**<br>**Dado que** he seleccionado una publicación,<br>**Cuando** se abre la pantalla del artículo,<br>**Entonces** veré: imagen, valor, usuario, calificación, título, descripción, ubicación e intereses.</p><p>**Escenario 2: Ver perfil del usuario**<br>**Dado que** estoy en la pantalla de información,<br>**Cuando** selecciono el nombre o foto del usuario,<br>**Entonces** me redirige a su perfil.</p><p>**Escenario 3: Guardar en favoritos**<br>**Dado que** estoy en la información del producto,<br>**Cuando** presiono el ícono de favoritos,<br>**Entonces** el producto se guarda en mis favoritos y el ícono cambia.</p><p></p>|**EP02**|
|**US20**|Adquirir la suscripción premium|Como usuario, quiero poder adquirir una suscripción premium para poder obtener beneficios adicionales que mejoren mi experiencia.|<p>**Escenario 1: Localizar la sección para adquirir una suscripción**</p><p>**Dado que** el usuario desea adquirir una suscripción premium en CambiaZo,<br>**Cuando** accede a la sección de Memberships desde la versión web,<br>**Entonces** se le mostrarán los diferentes planes de suscripción disponibles.<br>**Y** desde la versión mobile, al acceder a la sección Mi Suscripción, se le mostrarán los planes disponibles.</p><p>**Cuando** el usuario selecciona un plan específico desde cualquiera de las versiones (web o mobile),<br>**Entonces** se abrirá la pasarela de pago de PayPal para proceder con el pago.</p><p></p><p>**Escenario 2: Realizar el pago de la suscripción**</p><p>**Dado que** el usuario ha seleccionado un plan de su interés,<br>**Cuando** pulsa el botón de “Suscribirse”**,**<br>**Entonces** será redirigido a PayPal para completar el pago y activar la suscripción premium.</p>|**EP01**|
|**US21**|Cancelar una suscripción|Como usuario quiero poder cancelar mi suscripción en cualquier momento para no pagar mensualmente|<p>**Escenario 1: Acceso a la ventana de suscripciones**</p><p>**Dado que** el usuario desea verificar la información del estado de su suscripción,<br>**Cuando** se dirige a la sección de configuración desde la versión web**,<br>Entonces** deberá acceder a su perfil y, dentro de este, en la sección de Detalles de perfil, encontrará una sección llamada “Mi membresía”**.**<br>**Y** al pulsar en esta sección, podrá ver los detalles de su suscripción.</p><p>**Cuando** accede a la versión mobile y entra a la sección de Mi suscripción**,<br>Entonces** podrá ver el estado de su suscripción actual y los detalles relacionados.</p><p>**Escenario 2: Verificación de los detalles de la suscripción**</p><p>**Dado que** el usuario se encuentra en la ventana que muestra el estado de su suscripción,<br>**Cuando** revisa los detalles,<br>**Entonces** podrá visualizar la fecha de renovación**,<br>Y** si se encuentra en un plan.</p><p></p><p>**Escenario 3: Proceder a la cancelación**</p><p>**Dado que** el usuario se encuentra en la ventana que muestra el estado de su suscripción,<br>**Cuando** ha decidido no continuar con la suscripción premium de CambiaZo,<br>**Entonces** podrá pulsar en el botón rojo que dice **“**Anular suscripción” desde la versión web en la sección Mi membresía dentro de Detalles de perfil**.<br>Y** así, la suscripción será cancelada y no se renovará hasta la próxima fecha de pago.</p><p>**Cuando** accede desde la versión mobile** a la sección Mi suscripción y selecciona Planes,<br>**Entonces** verá la opción de cambiar a Plan Lite, lo cual efectivamente cancela la suscripción premium y la coloca en un plan gratuito, eliminando los pagos mensuales.</p><p></p>|**EP01**|
|**US22**|Visualizar el perfil de las ONG’S registradas|Como usuario de la aplicación, quiero tener la opción de ver todas las ONG's disponibles para realizar donaciones.|<p>**Escenario 1: Acceso a la pestaña de ONG's**</p><p>**Dado que** el usuario se encuentra en la pestaña principal,<br>**Cuando** pulsa sobre la etiqueta "ONG's",<br>**Entonces** se mostrarán todas las ONG's registradas dentro de la aplicación, tanto en la app móvil como en la web.</p><p>**Escenario 2: Ver perfil de una ONG**</p><p>**Dado** **que** el usuario se encuentra dentro de la pestaña "ONG'S",<br>**Cuando** pulsa sobre el recuadro que muestra el perfil de la ONG que desea visualizar,<br>**Entonces** aparecerán los datos y características completas de la ONG seleccionada, que incluyen el nombre, la imagen, la descripción (misión, visión y objetivos), el horario de atención, la ubicación, los datos de contacto (teléfono y correo electrónico), los proyectos realizados, y los enlaces a redes sociales y página web de la ONG.</p>|**EP03**|
|**US23**|Gestionar mis favoritos en la aplicación|Como usuario de la aplicación, quiero poder acceder a los objetos que he guardado como favoritos, para poder visualizarlos y eliminar los que ya no me interesen.|**Escenario 1: Ver objetos guardados como favoritos**<br>**Dado que** estoy en mi perfil, **Cuando** selecciono la opción "Favoritos", <br>**Entonces** se me mostrará una lista de los objetos que he guardado como favoritos, incluyendo la imagen del objeto, el nombre del objeto, la descripción breve del objeto y el valor aproximado del objeto.<br>**Escenario 2: Eliminar un objeto de mis favoritos**<br>**Dado que** estoy visualizando la lista de favoritos, <br>**Cuando** selecciono el botón de favoritos (ícono de corazón) de un objeto para eliminarlo, <br>**Entonces** se mostrará un popup de confirmación con el mensaje: "¿Estás seguro de que deseas eliminar este objeto de tus favoritos?" Y podré seleccionar entre eliminar, que eliminará el objeto de mi lista de favoritos, o cancelar, que cerrará el popup sin realizar ninguna acción. <br>**Y** si selecciono "Eliminar", el objeto desaparecerá de la lista de favoritos después de la confirmación.|**EP01**|
|**US24**|Ver reseñas recibidas|Como usuario de la aplicación, quiero poder ver las reseñas que he recibido, para tener una referencia de mi reputación en la plataforma.|**Escenario 1: Ver la calificación general y reseñas recibidas**<br>**Dado que** estoy en mi perfil,<br>**Cuando** selecciono la opción "Mis Reseñas", <br>**Entonces** se me mostrará el número total de reseñas recibidas y una lista de las reseñas, mostrando el nombre del usuario que dejó la reseña  y el comentario de la reseña.|**EP01**|
|**US25**|Visualización de la Historia de la Startup|Como usuario visitante**,** quiero acceder a la sección “¿Quiénes somos?” de la landing page, para conocer la historia de CambiaZo y al equipo que lo hace posible.|<p>**Escenario 1: Visualizar la historia de la startup**</p><p>**Dado que** me encuentro en la landing page de CambiaZo,<br>**Cuando** accedo a la sección “¿Quiénes somos?”,<br>**Entonces** veré una breve presentación sobre la startup, que explica su propósito de promover el intercambio y la donación de objetos para fomentar un estilo de vida sostenible, junto a un video introductorio que refuerza esta visión.</p><p>**Escenario 2: Conocer al equipo de CambiaZo**</p><p>**Dado que** me encuentro en la sección “¿Quiénes somos?” de la landing page,<br>**Cuando** deslizo el carrusel o slider que aparece a continuación del video,<br>**Entonces** podré visualizar las fotos de los integrantes del equipo, junto con sus nombres y los roles o puestos que ocupan dentro del proyecto.</p>|**EP04**|
|**US26**|Visualizar las características clave de la aplicación|Como usuario visitante, quiero poder conocer sus características clave para saber qué es lo que incluye.|<p>**Escenario 1: Acceso a la sección de características**</p><p>**Dado** que el usuario es un visitante en la página principal,<br>**Cuando** hace clic en el botón o enlace de "Características",<br>**Entonces** es redirigido a la sección "Descubre las ventajas de ser parte de nuestra comunidad".</p><p>**Escenario 2: Visualización de beneficios principales**</p><p>**Dado** que el usuario está en la sección de características,<br>**Cuando** visualiza el contenido inicial,<br>**Entonces** se le muestran dos opciones destacadas de Intercambios y Donaciones</p><p>**Escenario 3: Exploración visual de productos intercambiables**</p><p>**Dado** que el usuario ha explorado los beneficios iniciales,<br>**Cuando** hace scroll hacia abajo,<br>**Entonces** ve un carrusel o cuadrícula de imágenes con ejemplos de productos que puede intercambiar.</p><p>**Escenario 4: Conocimiento de valores diferenciales y características específicas**<br>**Dado** que el usuario continúa navegando la sección de características,<br>**Cuando** llega al bloque "Intercambios Sostenibles, Simplificados",<br>**Entonces** visualiza un mensaje que promueve la sostenibilidad mediante el intercambio, la donación y la conexión comunitaria,<br>**Y** también identifica las siguientes características: seguridad, artículos, comunidad, sostenible.</p><p>**Escenario 5: Reconocimiento de alianzas solidarias**</p><p>**Dado** que el usuario ha leído las características,<br>**Cuando** llega al bloque final de la sección,<br>**Entonces** puede visualizar logotipos o imágenes de las ONGs afiliadas que trabajan junto a la app, entendiendo su compromiso social.</p>|**EP04**|
|**US27**|Acceder a un formulario para llenar mis datos de contacto y recibir noticias relacionadas con CambiaZo.|Como usuario visitante, quiero tener la opción de llenar un formulario con mi información de contacto, a través de la landing page, para recibir noticias y actualizaciones relevantes de CambiaZo.|**Escenario 1: Acceso al formulario de suscripción**<br>**Dado** que el usuario visitante hace clic en la opción "Contáctanos",<br>**Cuando** es redirigido a la sección "¡Únete a CambiaZo!" en la landing page,<br>**Entonces** puede visualizar un formulario con los campos requeridos para ingresar su nombre, apellido y correo electrónico, y un botón para suscribirse|**EP04**|
|**US28**|Descargar la aplicación de CambiaZo|Como usuario visitante, quiero encontrar botones o enlaces claramente visibles en la landing page que me dirijan a la descarga de la aplicación de CambiaZo, para poder registrarme, intercambiar o donar artículos directamente desde mi dispositivo web.|<p>**Escenario 1: Identificación de botones de acción en la landing page**<br>**Dado** que el usuario está navegando por la landing page de CambiaZo,<br>**Cuando** busca una forma de acceder a la aplicación,<br>**Entonces** encuentra dos botones claramente visibles: uno que dice “Iniciar ahora” y lo lleva a la aplicación web, y otro que dice “Descargar” y lo dirige a la Play Store para obtener la app móvil.</p><p>**Escenario 2: Acceso fluido a la plataforma desde los botones**<br>**Dado** que el usuario hace clic en uno de los botones disponibles,<br>**Cuando** selecciona “Iniciar ahora” o “Descargar”,<br>**Entonces** es redirigido correctamente a la versión web de CambiaZo o a la Play Store, permitiéndole comenzar a registrarse, intercambiar o donar artículos sin inconvenientes.</p><p></p>|**EP04**|
|**US29**|Ver los planes y precios|Como usuario visitante, quiero tener acceso a una sección que detalle los planes ofrecidos por la plataforma, para poder evaluar las opciones disponibles antes de descargar la aplicación.|<p>**Escenario 1: Visualización de planes y precios disponibles<br>Dado** que el usuario está en la landing page de CambiaZo,<br>**Cuando** hace clic en la sección de "Planes",<br>**Entonces** ve los diferentes planes con sus beneficios y precios</p><p>**Escenario 2: Acción de suscripción a planes**<br>**Dado** que el usuario está en la landing page de CambiaZo y ha visto los planes,<br>**Cuando** hace clic en el botón **“¡Empieza ahora!”** para cualquiera de los planes,<br>**Entonces** se le redirige a la aplicación web para completar el proceso de suscripción.</p><p></p>|**EP04**|
|**US30**|Navegación en la Landing Page|Como usuario visitante, quiero contar con un menú de navegación visible y funcional para que me permita desplazarme fácilmente por las diferentes secciones del sitio web.|<p>**Escenario 1: Acceder a la información acerca de la startup**<br>**Dado** que el usuario se encuentra en la Landing Page,<br>**Cuando** quiera acceder a la información acerca del equipo,<br>**Entonces** podrá darle clic a la etiqueta “**Nosotros**” de la barra de navegación,<br>**Y** lo redirigirá rápidamente a la parte de la Landing Page donde se encuentra la información correspondiente.</p><p>**Escenario 2: Ver las características de la aplicación**<br>**Dado** que el usuario se encuentra en la Landing Page,<br>**Cuando** quiera conocer las características clave de CambiaZo,<br>**Entonces** podrá darle clic a la etiqueta “**Características**” de la barra de navegación,<br>**Y** lo redirigirá rápidamente a la parte de la Landing Page donde se encuentran las funcionalidades destacadas de la aplicación.</p><p>**Escenario 3: Ver los planes y precios**<br>**Dado** que el usuario se encuentra en la Landing Page,<br>**Cuando** quiera ver los planes y precios de CambiaZo,<br>**Entonces** podrá darle clic a la etiqueta “**Planes**” de la barra de navegación,<br>**Y** lo redirigirá a la sección que describe los diferentes planes y beneficios disponibles.</p><p>**Escenario 4: Acceder a la sección de contacto**<br>**Dado** que el usuario se encuentra en la Landing Page,<br>**Cuando** quiera acceder a la sección para contactarse con la startup,<br>**Entonces** podrá darle clic a la etiqueta “**Contáctanos**” de la barra de navegación,<br>**Y** lo redirigirá rápidamente a la parte de la Landing Page donde se encuentra el formulario para recibir notificaciones de CambiaZo y el pie de página con los datos de contacto.</p><p>**Escenario 5: Descargar o iniciar la aplicación**<br>**Dado** que el usuario se encuentra en la Landing Page,<br>**Cuando** quiera descargar la aplicación de CambiaZo o acceder a la versión web,<br>**Entonces** podrá hacer clic en los botones claramente visibles de la barra de navegación de “**Iniciar ahora**” para acceder a la aplicación web o “**Descargar**” para ser redirigido a la Play Store y descargar la aplicación móvil.</p>|**EP04**|
|**US31**|Aplicar sugerencias con IA|Como usuario que está creando o editando una publicación, quiero aplicar sugerencias generadas por IA (Gemini) a partir de la imagen para completar automáticamente campos como título, descripción, categoría y precio estimado, con el fin de ahorrar tiempo y mejorar la calidad del anuncio.|<p>**Escenario 1: Botón “Rellenar con IA” habilitado**<br>**Dado** que seleccioné una imagen,<br>**Cuando** veo el botón “Rellenar con IA”,<br>**Entonces** el botón está habilitado y muestra estado de carga al iniciar el análisis.</p><p>**Escenario 2: Sugerencias aplicadas correctamente**<br>**Dado** que el análisis con Gemini finaliza sin errores,<br>**Cuando** aplico las sugerencias,<br>**Entonces** el sistema completa:<br>• Título (≤ 70 car.)<br>• Descripción (≤ 450 car.) incluyendo “Estado estimado: X/10” si existe<br>• Categoría (por clave externa o etiquetas)<br>• Precio estimado (1 a 50 000)<br>**Y** muestra “Sugerencias de IA aplicadas”.</p><p>**Escenario 3: Consejos de mejora**<br>**Dado** que hay tips de mejora y de foto,<br>**Cuando** se aplican las sugerencias,<br>**Entonces** aparece un modal con los tips y la acción “Entendido”.</p><p>**Escenario 4: Error en el análisis**<br>**Dado** que ocurre un error durante el análisis,<br>**Cuando** finaliza el intento,<br>**Entonces** se muestran mensajes de error (“No pude analizar la imagen / Intenta nuevamente”) y los campos no se alteran.</p>|**EP02**|
|**US32**|Rellenado automático con Gemini al subir nueva imagen|Como usuario, cuando cambio la imagen de mi publicación, quiero que automáticamente se realice un nuevo análisis con Gemini y se reemplacen los campos del formulario con las nuevas sugerencias, para mantener la coherencia entre la foto y la información publicada.|<p>**Escenario 1: Detección de nueva imagen y autollenado**<br>**Dado** que estoy en publicar/editar,<br>**Cuando** selecciono una nueva imagen distinta a la anterior,<br>**Entonces** el sistema lanza automáticamente el análisis con Gemini y al finalizar reemplaza título, descripción, categoría y precio con las nuevas sugerencias.</p><p>**Escenario 2: Indicadores de proceso**<br>**Dado** que el análisis está en curso,<br>**Cuando** se ejecuta el autollenado,<br>**Entonces** se muestra estado de cargando y, al aplicar cambios, “Sugerencias de IA aplicadas”.</p><p>**Escenario 3: Edición posterior del usuario**<br>**Dado** que las sugerencias ya reemplazaron los campos,<br>**Cuando** edito manualmente cualquier campo,<br>**Entonces** el sistema respeta mis cambios y no sobrescribe hasta que suba otra imagen o presione “Rellenar con IA” otra vez.</p><p>**Escenario 4: Falla o indisponibilidad de IA**<br>**Dado** que el servicio de IA falla mientras subo una nueva imagen,<br>**Cuando** termina el intento,<br>**Entonces** se informa el error y los campos no se alteran.</p>|**EP02**|

<br><br>

**Technical User Stories**

|**Technical story ID**|**Título**|**Descripción**|**Criterios de Aceptación**|**Relación (EPIC ID)**|
| :- | :- | :- | :- | :- |
|**TS01**|API User|Como usuario desarrollador que configura la plataforma quiero tener una API que facilite la gestión de usuarios en nuestra aplicación para administrar eficazmente la información de los usuarios.|**Escenario 1: Diseño de la API User**<br><br>**Dado que** el usuario developer configura la plataforma<br><br>**Cuando** diseñe la API para gestionar usuarios en nuestra aplicación movil,<br><br>**Entonces** definirá los endpoints y rutas necesarias para manejar operaciones como registro de usuarios, inicio de sesión, actualización de datos de usuario, y recuperación de contraseñas y establecerá los requisitos de autenticación y seguridad necesarios para proteger la información de los usuarios.<br><br>**Escenario 2: Selección de la tecnología para la API**<br><br>**Dado que** el usuario developer está diseñando la API para gestionar usuarios en nuestra aplicación movil,<br><br>**Cuando** elija la tecnología para implementar la API REST,<br><br>**Entonces** considerará los requisitos de la aplicación y las preferencias del equipo de desarrollo para tomar una decisión informada.<br><br>**Escenario 3: Obtener información del usuario**<br><br>**Dado que** el endpoint "/usuarios" está disponible,<br><br>**Cuando** se envía una solicitud GET con el identificador del usuario,<br><br>**Entonces** se recibe una respuesta con estado 200,<br><br>**Y** se obtienen los datos del usuario solicitado.<br><br>**Escenario 4: Obtener usuario no disponible**<br><br>**Dado que** el endpoint "/usuarios" está disponible,<br><br>**Cuando** se envía una solicitud GET con un identificador de usuario que no existe,<br><br>**Entonces** se recibe una respuesta con estado 404,<br><br>**Y** se muestra un mensaje que indica "No existe un usuario con este identificador".<br><br>**Escenario 5: Registro de un nuevo usuario**<br><br>**Dado que** el endpoint "/usuarios" está disponible,<br><br>**Cuando** se envía una solicitud POST con los detalles del usuario,<br><br>**Entonces** se recibe una respuesta con estado 201,<br><br>**Y** se incluye un usuario con un nuevo ID y los detalles registrados.<br><br>**Escenario 6: Registro de un usuario ya existente**<br><br>**Dado que** el endpoint "/usuarios" está disponible,<br><br>**Cuando** se envía una solicitud POST con los datos del usuario,<br><br>**Y** ya existe un usuario registrado con esos datos,<br><br>**Entonces** se recibe una respuesta con estado 400,<br><br>**Y** se muestra un mensaje que indica "Un usuario con estos datos ya existe".<br><br>**Escenario 7: Actualizar un usuario existente**<br><br>**Dado que** el endpoint "/usuarios" está disponible,<br><br>**Cuando** se envía una solicitud PUT con el id de un usuario,<br><br>**Y** ya existe un usuario registrado con ese id,<br><br>**Entonces** se recibe una respuesta con estado 202,<br><br>**Y** se muestra un mensaje que indica "Los datos del usuario han sido actualizados satisfactoriamente".<br><br>**Escenario 8: Actualizar un usuario no existente**<br><br>**Dado que** el endpoint "/usuarios" está disponible,<br><br>**Cuando** se envía una solicitud PUT con el id de un usuario,<br><br>**Y** no existe un usuario registrado con ese id,<br><br>**Entonces** se recibe una respuesta con estado 400,<br><br>**Y** se muestra un mensaje que indica "No existe ese usuario".<br><br>**Escenario 9: Eliminar un usuario existente**<br><br>**Dado que** el endpoint "/usuarios" está disponible,<br><br>**Cuando** se envía una solicitud DELETE con el id de un usuario,<br><br>**Y** ya existe un usuario registrado con ese id,<br><br>**Entonces** se recibe una respuesta con estado 202,<br><br>**Y** se muestra un mensaje que indica "Se borró al usuario satisfactoriamente".<br><br>**Escenario 10: Eliminar un usuario no existente**<br><br>**Dado que** el endpoint "/usuarios" está disponible,<br><br>**Cuando** se envía una solicitud DELETE con el id de un usuario,<br><br>**Y** no existe un usuario registrado con ese id,<br><br>**Entonces** se recibe una respuesta con estado 400,<br><br>**Y** se muestra un mensaje que indica "No existe ese usuario".|**EP05**|
|**TS02**|API Exchange|Como usuario developer que configura la plataforma quiero implementar una API que permita a los usuarios dejar intercambios a otros usuarios para mejorar la interacción entre usuarios y la plataforma.|**Escenario 1: Diseño de la API Exchange**<br><br>**Dado que** el usuario developer está configurando la plataforma,<br><br>**Cuando** diseña la API para permitir a los usuarios dejar intercambios en nuestra aplicación,<br><br>**Entonces** se definen los endpoints y rutas necesarias para que los usuarios puedan crear, leer, actualizar y eliminar intercambios y establecen los requisitos de autenticación y seguridad para proteger la privacidad.<br><br>**Escenario 2: Selección de la tecnología para la API**<br><br>**Dado que** el usuario developer está diseñando la API de intercambios en nuestra aplicación,<br><br>**Cuando** elige la tecnología para implementar la API REST,<br><br>**Entonces** se consideran los requisitos de la aplicación, incluyendo la escalabilidad, el rendimiento y la facilidad de mantenimiento.<br><br>**Escenario 3: Obtener información del intercambio**<br><br>**Dado que** el endpoint "/exchanges" está disponible,<br><br>**Cuando** se envía una solicitud GET con el identificador del intercambio,<br><br>**Entonces** se recibe una respuesta con estado 200,<br><br>**Y** se obtienen los datos del intercambio solicitado.<br><br>**Escenario 4: Obtener intercambio no disponible**<br><br>**Dado que** el endpoint "/exchanges" está disponible,<br><br>**Cuando** se envía una solicitud GET con un identificador de intercambio que no existe,<br><br>**Entonces** se recibe una respuesta con estado 404,<br><br>**Y** se muestra un mensaje que indica "No existe un intercambio con este identificador".<br><br>**Escenario 5: Agregar un nuevo intercambio**<br><br>**Dado que** el endpoint "/exchanges" está disponible,<br><br>**Cuando** se envía una solicitud POST con los valores del intercambio,<br><br>**Entonces** se recibe una respuesta con estado 201,<br><br>**Y** se incluye un intercambio con un nuevo ID y los valores registrados.<br><br>**Escenario 6: Agregar un intercambio ya existente**<br><br>**Dado que** el endpoint "/exchanges" está disponible,<br><br>**Cuando** se envía una solicitud POST con los datos del intercambio,<br><br>**Y** ya existe un intercambio registrado con esos datos,<br><br>**Entonces** se recibe una respuesta con estado 400,<br><br>**Y** se muestra un mensaje que dice "Un intercambio con estos datos ya existe".|**EP05**|
|**TS03**|API ONGs|Como usuario developer que configura la plataforma quiero diseñar una API que simplifique la obtención de información sobre las ONGs para integrarla de manera efectiva en la aplicación.|**Escenario 1: Diseño de la API ONGs**<br><br>**Dado que** el usuario developer configura la plataforma,<br><br>**Cuando** diseñe la API para obtener información sobre las ONGs,<br><br>**Entonces** define los endpoints y rutas necesarias para recibir detalles sobre las ONGs y establece los requisitos de autenticación y seguridad necesarios.<br><br>**Escenario 2: Selección de la tecnología para la API**<br><br>**Dado que** el usuario developer está diseñando la API para obtener información sobre las ONGs,<br><br>**Cuando** elija la tecnología para implementar la API REST,<br><br>**Entonces** considerará los requisitos y preferencias de la organización para tomar una decisión informada.<br><br>**Escenario 3: Obtener información de la ONG**<br><br>**Dado que** el endpoint "/ongs" está disponible,<br><br>**Cuando** se envía una solicitud GET con el identificador de la ONG,<br><br>**Entonces** se recibe una respuesta con estado 200,<br><br>**Y** se obtienen los datos de la ONG solicitada.<br><br>**Escenario 4: Obtener ONG no disponible**<br><br>**Dado que** el endpoint "/ongs" está disponible,<br><br>**Cuando** se envía una solicitud GET con un identificador de ONG que no existe,<br><br>**Entonces** se recibe una respuesta con estado 404,<br><br>**Y** se muestra un mensaje que indica "No existe una ONG con este identificador".<br><br>**Escenario 5: Agregar una nueva ONG**<br><br>**Dado que** el endpoint "/ongs" está disponible,<br><br>**Cuando** se envía una solicitud POST con los valores de la ONG,<br><br>**Entonces** se recibe una respuesta con estado 201,<br><br>**Y** se incluye una ONG con un nuevo ID y sus valores registrados.<br><br>**Escenario 6: Agregar una ONG ya existente**<br><br>**Dado que** el endpoint "/ongs" está disponible,<br><br>**Cuando** se envía una solicitud POST con los datos de la ONG,<br><br>**Y** ya existe una ONG registrada con esos datos,<br><br>**Entonces** se recibe una respuesta con estado 400,<br><br>**Y** se muestra un mensaje que dice "Una ONG con estos datos ya existe".|**EP05**|
|**TS04**|API Memberships|Como usuario developer que configura la plataforma quiero diseñar una API que facilite la gestión de membresías de usuarios para ofrecer beneficios al usuario.|**Escenario 1: Diseño de la API de Membresías**<br><br>**Dado que** el usuario developer está configurando la plataforma,<br><br>**Cuando** diseña la API de Membresías para gestionar las membresías de los usuarios,<br><br>**Entonces** define los endpoints y rutas necesarias para manejar las operaciones de membresías de usuarios y establece los requisitos de autenticación y seguridad necesarios para proteger la información de los usuarios.<br><br>**Escenario 2: Selección de la tecnología para la API**<br><br>**Dado que** el usuario developer está diseñando la API de Membresías en nuestra aplicación,<br><br>**Cuando** elige la tecnología para implementar la API REST,<br><br>**Entonces** considera los requisitos de la aplicación y las preferencias del equipo de desarrollo para tomar una decisión informada.<br><br>**Escenario 3: Obtener información de membresía del usuario**<br><br>**Dado que** el endpoint "/membresías" está disponible,<br><br>**Cuando** se envía una solicitud GET con el identificador de la membresía,<br><br>**Entonces** se recibe una respuesta con estado 200,<br><br>**Y** se obtienen los datos de la membresía solicitada.<br><br>**Escenario 4: Obtener membresía no disponible**<br><br>**Dado que** el endpoint "/membresías" está disponible,<br><br>**Cuando** se envía una solicitud GET con un identificador de membresía que no existe,<br><br>**Entonces** se recibe una respuesta con estado 404,<br><br>**Y** se muestra un mensaje que indica "No existe una membresía con este identificador".<br><br>**Escenario 5: Agregar una nueva membresía**<br><br>**Dado que** el endpoint "/membresías" está disponible,<br><br>**Cuando** se envía una solicitud POST con los valores de la membresía,<br><br>**Entonces** se recibe una respuesta con estado 201,<br><br>**Y** se incluye una membresía con un nuevo ID y los valores registrados.<br><br>**Escenario 6: Agregar una membresía ya existente**<br><br>**Dado que** el endpoint "/membresías" está disponible,<br><br>**Cuando** se envía una solicitud POST con los datos de la membresía,<br><br>**Y** ya existe una membresía registrada con esos datos,<br><br>**Entonces** se recibe una respuesta con estado 400,<br><br>**Y** se muestra un mensaje que dice "Una membresía con estos datos ya existe".|**EP05**|
|**TS05**|API Product|Como usuario developer que configura la plataforma quiero diseñar una API que facilite la gestión de productos para que los usuarios puedan subir sus productos que ya no utilizan.|**Escenario 1: Diseño de la API de Productos**<br><br>**Dado que** el usuario developer está configurando la plataforma,<br><br>**Cuando** diseña la API de Productos para gestionar los productos que suben los usuarios,<br><br>**Entonces** define los endpoints y rutas necesarios para permitir a los usuarios subir sus productos que ya no usan, cancelar la subida y obtener información sobre sus productos, y establece los requisitos de requerimiento y tipo de archivo.<br><br>**Escenario 2: Obtener información de un producto**<br><br>**Dado que** el endpoint "/products" está disponible,<br><br>**Cuando** se envía una solicitud GET con el identificador del producto,<br><br>**Entonces** se recibe una respuesta con estado 200,<br><br>**Y** se obtienen los detalles del producto solicitado.<br><br>**Escenario 3: Producto no encontrado**<br><br>**Dado que** el endpoint "/products" está disponible,<br><br>**Cuando** se envía una solicitud GET con un identificador de un producto que no existe,<br><br>**Entonces** se recibe una respuesta con estado 404,<br><br>**Y** se muestra un mensaje que indica "No se encontró el producto solicitado".<br><br>**Escenario 4: Creación de un nuevo producto**<br><br>**Dado que** el endpoint "/products" está disponible,<br><br>**Cuando** se envía una solicitud POST con los detalles del producto y el usuario asociado,<br><br>**Entonces** se recibe una respuesta con estado 201,<br><br>**Y** se registra el producto con un nuevo ID y los detalles registrados.<br><br>**Escenario 5: Crear un producto ya existente**<br><br>**Dado que** el endpoint "/products" está disponible,<br><br>**Cuando** se intenta crear un nuevo producto para un usuario que ya registró este producto,<br><br>**Entonces** se recibe una respuesta con estado 400,<br><br>**Y** se muestra un mensaje que indica "El usuario ya registró este producto".<br><br>**Escenario 6: Eliminar un producto**<br><br>**Dado que** el endpoint "/products" está disponible,<br><br>**Cuando** se envía una solicitud DELETE con los detalles del producto y el usuario asociado,<br><br>**Entonces** se recibe una respuesta con estado 200,<br><br>**Y** se elimina el producto con su ID y los detalles registrados.<br><br>**Escenario 7: Editar un producto**<br><br>**Dado que** el endpoint "/products" está disponible,<br><br>**Cuando** se envía una solicitud PUT con los detalles del producto y el usuario asociado,<br><br>**Entonces** se recibe una respuesta con estado 200,<br><br>**Y** se editarán los detalles previamente registrados del producto.|**EP05**|


## 3.3. Impact Mapping
En esta sección, presentaremos el Impact Mapping, una herramienta esencial para alinear nuestras iniciativas con los objetivos estratégicos del proyecto. El Impact Mapping nos permitirá identificar y conectar los impactos esperados de nuestras soluciones con los resultados deseados, asegurando que cada acción y decisión contribuyan a alcanzar los objetivos clave y maximizar el valor para nuestros usuarios.

<b>Segmento Intercambiadores</b><br>

<div align="center">

[![Impact Mapping.](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Needfinding/Impact-Map/impact-map-1.png?raw=true)]()
</div><br><br>



<b>Segmento Donadores</b><br>

<div align="center">

[![Impact Mapping.](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Needfinding/Impact-Map/impact-map-2.png?raw=true)]()
</div><br><br>



<br>

## 3.4. Product Backlog
En el Product Backlog presentamos una lista priorizada de nuestras user stories según el nivel de prioridad que acordamos en el equipo, esencial para el *enfoque ágil*. Para analizar el nivel de dificultad de las tareas, utilizamos la secuencia de Fibonacci (1,2,3,5,8).  
Tomamos como historia de usuario base la historia de usuario **US12**: *Como usuario de la aplicación, quiero poder crear una nueva publicación de intercambio para ofrecer un artículo que deseo intercambiar*.

<table>
  <tr>
    <th># Orden</th>
    <th>User Story Id</th>
    <th>Título</th>
    <th>Descripción</th>
    <th>Story Points (1 / 2 / 3 / 5 / 8)</th>
    <th>EPIC ID</th>
  </tr>
  <!-- EPIC01 -->
  <tr>
    <td>1</td>
    <td><strong>US20</strong></td>
    <td>Adquirir la suscripción premium</td>
    <td>Como usuario, quiero poder adquirir una suscripción premium para poder obtener beneficios adicionales que mejoren mi experiencia.</td>
    <td>8</td>
    <td rowspan="10"><strong>EP01</strong></td>
  </tr>
  <tr>
    <td>2</td>
    <td><strong>US09</strong></td>
    <td>Eliminación de cuenta</td>
    <td>Como usuario, quiero tener la opción de eliminar permanentemente mi cuenta para evitar que mi información persista en caso de que ya no desee utilizar la aplicación.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>3</td>
    <td><strong>US23</strong></td>
    <td>Gestionar mis favoritos en la aplicación</td>
    <td>Como usuario de la aplicación, quiero poder acceder a los objetos que he guardado como favoritos, para poder visualizarlos y eliminar los que ya no me interesen.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>4</td>
    <td><strong>US24</strong></td>
    <td>Ver reseñas recibidas</td>
    <td>Como usuario de la aplicación, quiero poder ver las reseñas que he recibido, para tener una referencia de mi reputación en la plataforma.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>5</td>
    <td><strong>US01</strong></td>
    <td>Registro de usuario</td>
    <td>Como nuevo usuario quiero completar el proceso de registro en la aplicación para establecer mi propia cuenta.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>6</td>
    <td><strong>US21</strong></td>
    <td>Cancelar una suscripción</td>
    <td>Como usuario quiero poder cancelar mi suscripción en cualquier momento para no pagar mensualmente.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>7</td>
    <td><strong>US02</strong></td>
    <td>Editar perfil del usuario</td>
    <td>Como usuario ya registrado quiero realizar modificaciones en mi perfil para asegurarme de que mi información esté siempre actualizada.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>8</td>
    <td><strong>US04</strong></td>
    <td>Cambiar Contraseña</td>
    <td>Como usuario registrado, quiero realizar cambios en la contraseña de mi cuenta para reforzar la seguridad de mi cuenta.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>9</td>
    <td><strong>US03</strong></td>
    <td>Iniciar sesión en la aplicación</td>
    <td>Como usuario registrado quiero iniciar sesión en la aplicación para poder acceder a todas sus funcionalidades.</td>
    <td>1</td>
  </tr>
  <tr>
    <td>10</td>
    <td><strong>US05</strong></td>
    <td>Cerrar Sesión</td>
    <td>Como usuario registrado quiero cerrar sesión en la aplicación para asegurarme de que mi cuenta no quede almacenada en mi dispositivo.</td>
    <td>1</td>
  </tr>
  <!-- EPIC02 -->
  <tr>
    <td>11</td>
    <td><strong>US06</strong></td>
    <td>Filtrado de Objetos</td>
    <td>Como usuario Intercambiador, quiero la capacidad de filtrar los objetos disponibles de intercambio para encontrar la opción que mejor se adapte a mis preferencias.</td>
    <td>5</td>
    <td rowspan="12"><strong>EP02</strong></td>
  </tr>
  <tr>
    <td>12</td>
    <td><strong>US12</strong></td>
    <td>Crear publicación de intercambio</td>
    <td>Como usuario de la aplicación, quiero poder crear una nueva publicación de intercambio para ofrecer un artículo que deseo intercambiar.</td>
    <td>5</td>
  </tr>
  <tr>
    <td>13</td>
    <td><strong>US16</strong></td>
    <td>Visualización de objetos disponibles para intercambio</td>
    <td>Como usuario, necesito poder ver objetos disponibles para intercambio, de manera que pueda navegar y seleccionar aquellos que me interesen.</td>
    <td>5</td>
  </tr>
  <tr>
    <td>14</td>
    <td><strong>US19</strong></td>
    <td>Ver la información detallada de un producto publicado</td>
    <td>Como usuario de la aplicación, quiero poder ver la información completa de un producto en el que estoy interesado, para poder decidir si quiero guardarlo en mis favoritos o proponer un intercambio.</td>
    <td>5</td>
  </tr>
  <tr>
    <td>31</td>
    <td><strong>US31</strong></td>
    <td>Aplicar sugerencias con IA</td>
    <td>Como usuario que está creando o editando una publicación, quiero aplicar sugerencias generadas por IA (Gemini) a partir de la imagen para completar automáticamente campos como título, descripción, categoría y precio estimado, con el fin de ahorrar tiempo y mejorar la calidad del anuncio.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>32</td>
    <td><strong>US32</strong></td>
    <td>Rellenado automático con Gemini al subir nueva imagen</td>
    <td>Como usuario, cuando cambio la imagen de mi publicación, quiero que automáticamente se realice un nuevo análisis con Gemini y se reemplacen los campos del formulario con las nuevas sugerencias, para mantener la coherencia entre la foto y la información publicada.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>15</td>
    <td><strong>US11</strong></td>
    <td>Realización de una oferta de intercambio</td>
    <td>Como usuario de la aplicación de intercambio, quiero seleccionar uno de mis artículos y enviarlo como oferta de intercambio, para poder ofrecerlo a cambio de otro artículo publicado por otro usuario.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>16</td>
    <td><strong>US13</strong></td>
    <td>Editar publicación de intercambio</td>
    <td>Como usuario, necesito la capacidad de editar una publicación de intercambio existente para realizar cambios en los detalles del artículo o actualizar la información relevante.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>17</td>
    <td><strong>US15</strong></td>
    <td>Gestión de intercambios</td>
    <td>Como usuario de la aplicación, quiero revisar el estado de los intercambios que he enviado, recibido o aceptado, para poder ver los detalles y gestionar mis transacciones de intercambio de manera eficiente.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>18</td>
    <td><strong>US18</strong></td>
    <td>Aceptar o Rechazar un Intercambio</td>
    <td>Como usuario que ha recibido una oferta de intercambio, quiero poder revisar los detalles de la oferta y tomar una decisión para aceptar o rechazar el intercambio, para poder gestionar mis transacciones de manera eficiente y asegurada.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>19</td>
    <td><strong>US10</strong></td>
    <td>Visualización de artículos publicados para intercambio</td>
    <td>Como usuario de la aplicación de intercambio, quiero ver los artículos que he publicado, para revisar cuáles están disponibles para intercambio.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>20</td>
    <td><strong>US14</strong></td>
    <td>Eliminar publicación de intercambio</td>
    <td>Como usuario, quiero tener la opción de eliminar una publicación de intercambio que ya no deseo ofrecer para intercambiar.</td>
    <td>2</td>
  </tr>
  <!-- EPIC03 -->
  <tr>
    <td>21</td>
    <td><strong>US07</strong></td>
    <td>Visualización de ONGs registradas y filtrado</td>
    <td>Como usuario Donante, quiero visualizar la lista de ONGs registradas y poder filtrarlas por nombre usando el buscador, para encontrar la ONG específica en la cual me gustaría hacer mi donación.</td>
    <td>5</td>
    <td rowspan="4"><strong>EP03</strong></td>
  </tr>
  <tr>
    <td>22</td>
    <td><strong>US08</strong></td>
    <td>Brindar reseña sobre el Intercambiador</td>
    <td>Como usuario intercambiador, deseo dejar una reseña sobre mi experiencia con el intercambiador para que otros usuarios puedan leer y considerar mi opinión antes de intercambiar.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>23</td>
    <td><strong>US17</strong></td>
    <td>Visualizar el perfil del usuario que publique un producto</td>
    <td>Como usuario, me gustaría tener la capacidad de visualizar el perfil de la persona que haya publicado un intercambio, para poder obtener información detallada de su confiabilidad.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>24</td>
    <td><strong>US22</strong></td>
    <td>Visualizar el perfil de las ONG’s registradas</td>
    <td>Como usuario de la aplicación, quiero tener la opción de ver todas las ONG's disponibles para realizar donaciones.</td>
    <td>3</td>
  </tr>
  <!-- EPIC04 -->
  <tr>
    <td>25</td>
    <td><strong>US27</strong></td>
    <td>Acceder a un formulario para llenar mis datos de contacto y recibir noticias relacionadas con CambiaZo</td>
    <td>Como usuario visitante, quiero tener la opción de llenar un formulario con mi información de contacto, a través de la landing page, para recibir noticias y actualizaciones relevantes de CambiaZo.</td>
    <td>5</td>
    <td rowspan="6"><strong>EP04</strong></td>
  </tr>
  <tr>
    <td>26</td>
    <td><strong>US30</strong></td>
    <td>Navegación en la Landing Page</td>
    <td>Como usuario visitante, deseo contar con un menú de navegación visible y funcional para que me permita desplazarme fácilmente por las diferentes secciones del sitio web.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>27</td>
    <td><strong>US29</strong></td>
    <td>Ver los planes y precios</td>
    <td>Como usuario visitante, quiero tener acceso a una sección que detalle los planes ofrecidos por la plataforma, para poder evaluar las opciones disponibles antes de descargar la aplicación.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>28</td>
    <td><strong>US26</strong></td>
    <td>Visualizar las características clave de la aplicación</td>
    <td>Como usuario visitante, quiero poder conocer sus características clave para saber qué es lo que incluye.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>29</td>
    <td><strong>US28</strong></td>
    <td>Acceder a la página principal de CambiaZo</td>
    <td>Como usuario visitante, quiero encontrar botones o enlaces claramente visibles que me dirijan a la descarga de la aplicación de CambiaZo, para poder registrarme, intercambiar o donar artículos directamente desde mi dispositivo.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>30</td>
    <td><strong>US25</strong></td>
    <td>Visualización de la Historia de la Startup</td>
    <td>Como usuario visitante, quiero poder acceder a la historia de la startup, su misión y visión desde la landing page para estar más informado acerca de TechZo.</td>
    <td>1</td>
  </tr>
  <!-- EPIC05 -->
  <tr>
    <td>31</td>
    <td><strong>TS01</strong></td>
    <td>API User</td>
    <td>Como usuario desarrollador que configura la plataforma, quiero tener una API que facilite la gestión de usuarios en nuestra aplicación para administrar eficazmente la información de los usuarios.</td>
    <td>5</td>
    <td rowspan="5"><strong>EP05</strong></td>
  </tr>
  <tr>
    <td>32</td>
    <td><strong>TS02</strong></td>
    <td>API Exchange</td>
    <td>Como usuario developer que configura la plataforma quiero implementar una API que permita a los usuarios dejar intercambios a otros usuarios para mejorar la interacción entre usuarios y la plataforma.</td>
    <td>5</td>
  </tr>
  <tr>
    <td>33</td>
    <td><strong>TS03</strong></td>
    <td>API ONGs</td>
    <td>Como usuario developer que configura la plataforma, quiero diseñar una API que simplifique la obtención de información sobre las ONGs para integrarla de manera efectiva en la aplicación.</td>
    <td>5</td>
  </tr>
  <tr>
    <td>34</td>
    <td><strong>TS04</strong></td>
    <td>API Memberships</td>
    <td>Como usuario developer que configura la plataforma, quiero diseñar una API que facilite la gestión de membresías de usuarios para ofrecer beneficios al usuario.</td>
    <td>5</td>
  </tr>
  <tr>
    <td>35</td>
    <td><strong>TS05</strong></td>
    <td>API Product</td>
    <td>Como usuario developer que configura la plataforma quiero diseñar una API que facilite la gestión de productos para que los usuarios puedan subir sus productos que ya no utilizan.</td>
    <td>5</td>
  </tr>
</table>

<br>

A continuación se presenta una representación gráfica del mismo en la plataforma Pivotal Tracker:

<div align="center">

[![Product Backlog.](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Product-Backlog/pivotal.png?raw=true)](https://www.pivotaltracker.com/n/projects/2699481)
</div>


Enlace: [Product Backlog en PivotalTracker](https://www.pivotaltracker.com/n/projects/2699481)<br><br>



# Capítulo IV: Strategic-Level Software Design

## 4.1 Strategic-Level Attribute-Driven Design

### 4.1.1 Design Purpose

El diseño de la aplicación web CambiaZo tiene como propósito principal asegurar que todas las funciones trabajen de manera organizada y coherente, para ofrecer una experiencia fluida a los usuarios. La aplicación permite a las personas intercambiar productos que ya no usan, como ropa, juguetes o artículos del hogar, y también donar objetos a organizaciones sin fines de lucro afiliadas. Para cumplir con este objetivo, es necesario planificar cuidadosamente cómo se conectan y funcionan las diferentes partes del sistema.

Para esto, se ha elegido utilizar una arquitectura basada en microservicios, que divide la aplicación en pequeños servicios independientes, cada uno responsable de una tarea específica. Por ejemplo, hay un servicio para manejar a los usuarios, otro para las publicaciones, uno más para las notificaciones, y otro para las donaciones. Esta separación permite que cada servicio se desarrolle, pruebe y actualice por separado, lo cual hace que el sistema sea más fácil de mantener y mejorar.

Además, esta arquitectura ayuda a que la aplicación sea más estable y resistente a fallos. Si un servicio deja de funcionar, los demás pueden seguir trabajando normalmente, lo que evita que toda la plataforma se caiga. También permite realizar cambios o añadir nuevas funciones sin afectar lo que ya existe. Por ejemplo, se puede mejorar el sistema de recomendaciones o integrar nuevas ONGs sin interrumpir el funcionamiento de los intercambios.

El diseño también tiene en cuenta la escalabilidad, es decir, la capacidad de crecer según la demanda de los usuarios. Si muchas personas están utilizando la app al mismo tiempo, los microservicios pueden adaptarse para seguir funcionando correctamente. Esto es muy útil en fechas especiales o campañas de donación, cuando la actividad dentro de la aplicación aumenta y se necesita mayor capacidad de respuesta.

Este enfoque también facilita la incorporación rápida de nuevas funciones o mejoras sin afectar el resto del sistema, lo que permite que CambiaZo evolucione continuamente y se adapte a las necesidades cambiantes de sus usuarios, promoviendo una cultura de reutilización, sostenibilidad y colaboración social.

<br><br>

### 4.1.2 Attribute-Driven Design Inputs

#### 4.1.2.1 Primary Functionality (Primary User Stories)

En esta parte se presentan los requisitos principales que definen cómo debe estar estructurada la aplicación CambiaZo. Estos requisitos están basados en historias de usuario y muestran las funciones más importantes que debe tener el sistema para que los usuarios puedan usarla correctamente.


|**User Story ID**|**Título**|**Descripción**|**Requisitos**|**Impacto en la Estructura**|
| :-: | :-: | :-: | :-: | :-: |
|US-01|Registro de usuario|Como nuevo usuario quiero completar el proceso de registro en la aplicación para crear mi propia cuenta.|<p>- Formulario de registro validado.</p><p>- Cifrado de contraseña.</p><p>- Verificación de email único. </p><p>- Mensajes de error y confirmación.</p>|<p>- Lógica de creación de usuarios en el backend.</p><p>- Componente visual de registro en frontend.</p><p>-Tabla de usuarios con campos seguros en base de datos.</p>|
|US-03|Iniciar sesión en la aplicación|Como usuario registrado quiero iniciar sesión en la aplicación para poder acceder a todas sus funcionalidades.|<p>- Formulario de login.</p><p>- Verificación de credenciales.</p><p>- Generación y uso de JWT.</p><p>- Almacenamiento temporal del token.</p>|<p>- Componente de autenticación en backend.</p><p>- Servicio de login en frontend.</p><p>- Protección de rutas según sesión activa.</p>|
|US-12|Crear publicación de intercambio|Como usuario de la aplicación, quiero poder crear una nueva publicación de intercambio para ofrecer un artículo que deseo intercambiar.|<p>- Formulario de publicación. </p><p>- Subida de imagen.</p><p>- Validación de campos.</p><p>- Asociación del producto con el usuario que publica.</p>|<p>- Servicio backend de publicaciones.</p><p>- Componente visual para crear nueva publicación.</p><p>- Registro en base de datos con relación al usuario.</p>|
|US-13|Editar publicación de intercambio|Como usuario, necesito la capacidad de editar una publicación de intercambio existente para realizar cambios en los detalles del artículo.|<p>- Formulario editable precargado.</p><p>- Validación de que el usuario sea el dueño del producto.</p><p>- Confirmación de cambios.</p>|<p>- Lógica de actualización en backend.</p><p>- Validación de propiedad.</p><p>- Componente visual de edición.</p><p>- Actualización de datos en base de datos.</p>|
|US-14|Eliminar publicación de intercambio|Como usuario, quiero tener la opción de eliminar una publicación de intercambio que ya no deseo ofrecer.|<p>- Botón de eliminar con confirmación.</p><p>- Verificación de propiedad del producto.</p><p>- Eliminación lógica o física.</p>|<p>- Eliminación controlada en backend.</p><p>- Actualización visual inmediata.</p><p>- Base de datos con flag de estado o eliminación definitiva.</p>|
|US-06|Filtrado de objetos|Como usuario Intercambiador, quiero la capacidad de filtrar los objetos disponibles para encontrar el que mejor se adapte a mis preferencias.|<p>- Controles de filtro (categoría, estado, ubicación).</p><p>- Lógica de búsqueda eficiente.</p><p>- Resultados dinámicos.</p>|<p>- Componente de búsqueda.</p><p>- Optimización de consultas en base de datos con índices adecuados.</p>|
|US-17|Visualizar perfil del usuario que publica|Como usuario, me gustaría ver el perfil de quien publicó un intercambio para evaluar su confiabilidad.|<p>- Interfaz para visualizar perfil.</p><p>- Consulta de reputación, número de intercambios, nombre de usuario.</p><p>- Protección de información sensible.</p>|<p>- Servicio para perfiles públicos.</p><p>- Componente visual de perfil.</p><p>- Control de visibilidad de datos.</p>|
|US-18|Aceptar o Rechazar un Intercambio  |Como usuario que ha recibido una oferta de intercambio, quiero poder revisar los detalles de la oferta y tomar una decisión para aceptar o rechazar el intercambio, para poder gestionar mis transacciones de manera eficiente y asegurada.  |<p>- Visualización de detalles de la oferta.</p><p>- Botones de aceptar o rechazar.</p><p>- Validación de acceso.</p><p>- Notificación al otro usuario según acción.</p>|<p>- Microservicio de ofertas. Lógica de decisión en backend. </p><p>- Registro del resultado.</p><p>- Componente visual para interacción.</p>|
|US-31|Aplicar sugerencias con IA|Como usuario que está creando o editando una publicación, quiero aplicar sugerencias generadas por IA (Gemini) a partir de la imagen para completar automáticamente campos como título, descripción, categoría y precio estimado, con el fin de ahorrar tiempo y mejorar la calidad del anuncio.|<p>- Botón “Rellenar con IA” habilitado tras subir imagen.</p><p>- Análisis con Gemini para generar sugerencias.</p><p>- Autocompletado de título, descripción, categoría y precio.</p><p>- Mensajes de éxito o error según resultado.</p>|<p>- Microservicio de IA (Gemini).</p><p>- Componente visual del formulario con botón “Rellenar con IA”.</p><p>- Lógica de validación de datos generados (longitud y rangos).</p><p>- Manejo de estados de carga y errores.</p>|
|US-32|Rellenado automático con Gemini al subir nueva imagen|Como usuario, cuando cambio la imagen de mi publicación, quiero que automáticamente se realice un nuevo análisis con Gemini y se reemplacen los campos del formulario con las nuevas sugerencias, para mantener la coherencia entre la foto y la información publicada.|<p>- Detección de nueva imagen en formulario.</p><p>- Ejecución automática de análisis con Gemini.</p><p>- Reemplazo de título, descripción, categoría y precio con nuevas sugerencias.</p><p>- Indicadores de proceso y mensajes de éxito o error.</p>|<p>- Microservicio de IA (Gemini).</p><p>- Detector de cambios en imágenes en el formulario.</p><p>- Lógica de reemplazo automático de campos.</p><p>- Manejo de errores y persistencia de cambios manuales.</p>|

<br><br>

#### 4.1.2.2 Quality attribute Scenarios

Los escenarios de atributos de calidad definen cómo debe comportarse un sistema en diferentes situaciones, garantizando el cumplimiento de los requisitos no funcionales. A continuación, se presentan escenarios que abordan atributos como seguridad, disponibilidad, desempeño y modificabilidad. Cada uno incluye la fuente y tipo de estímulo, el entorno, el artefacto afectado, la respuesta del sistema y su medida, lo que permite evaluar y asegurar el cumplimiento de los requisitos de calidad.

<table>
  <tr>
    <th><b>ID</b></th>
    <th><b>Atributo</b></th>
    <th><b>Fuente</b></th>
    <th><b>Estímulo</b></th>
    <th><b>Artefacto</b></th>
    <th><b>Entorno</b></th>
    <th><b>Respuesta</b></th>
    <th><b>Medida</b></th>
    <th><b>User Stories Relacionadas</b></th>
  </tr>
  <tr>
    <td rowspan="2">QA-01</td>
    <td><b>Seguridad</b></td>
    <td>Usuario</td>
    <td>Envío de datos sensibles</td>
    <td>Sistema de autenticación y gestión de usuarios</td>
    <td>Operación normal</td>
    <td>Validación del lado del servidor, JWT y cifrado con bcrypt</td>
    <td>Solicitud validada y segura en ≤ 2 seg</td>
    <td>US-01, US-03</td>
  </tr>
  <tr>
    <td colspan="8">
      El usuario podrá enviar datos sensibles, como credenciales de acceso o información de registro, en un entorno de operación normal, 
      obteniendo una validación segura del lado del servidor mediante autenticación JWT y almacenamiento cifrado con bcrypt, 
      todo en un tiempo máximo de 2 segundos.
    </td>
  </tr>
  <tr>
    <td rowspan="2">QA-02</td>
    <td><b>Disponibilidad</b></td>
    <td>Usuario</td>
    <td>Solicitudes concurrentes</td>
    <td>Backend distribuido + balanceador de carga</td>
    <td>Alta demanda</td>
    <td>Distribución eficiente del tráfico y respuesta continua</td>
    <td>99.9% de uptime mensual</td>
    <td>US-03, US-06, US-12, US-18, US-32</td>
  </tr>
  <tr>
    <td colspan="8">
      El usuario podrá interactuar con el sistema en momentos de alta demanda, como al iniciar sesión, explorar objetos o gestionar intercambios, 
      y recibirá una respuesta estable gracias a la distribución del tráfico mediante un balanceador de carga, 
      asegurando una disponibilidad continua del servicio del 99.9%.
    </td>
  </tr>
  <tr>
    <td rowspan="2">QA-03</td>
    <td><b>Performance</b></td>
    <td>Usuario</td>
    <td>Consultas a objetos o publicaciones</td>
    <td>Servicios de búsqueda y publicación</td>
    <td>Operación normal</td>
    <td>Respuesta rápida mediante caché, consultas optimizadas, paginación</td>
    <td>Tiempo de respuesta ≤ 2 seg</td>
    <td>US-06, US-12, US-17, US-31, US-32</td>
  </tr>
  <tr>
    <td colspan="8">
      El usuario podrá realizar búsquedas de objetos o aplicar autocompletado mediante IA (Gemini) y visualizar información relacionada 
      en un entorno de operación normal, obteniendo respuestas rápidas gracias a la caché, consultas optimizadas y paginación, 
      en un tiempo máximo de 2 segundos.
    </td>
  </tr>
  <tr>
    <td rowspan="2">QA-04</td>
    <td><b>Testeabilidad</b></td>
    <td>Equipo dev</td>
    <td>Ejecución de pruebas</td>
    <td>Sistema completo en entorno de pruebas</td>
    <td>Integración continua</td>
    <td>Uso de loggers, arquitectura modular y separación de responsabilidades</td>
    <td>Cobertura de pruebas ≥ 85%</td>
    <td>US-01, US-03, US-12, US-13, US-14</td>
  </tr>
  <tr>
    <td colspan="8">
      El equipo de desarrollo podrá detectar y depurar fallos mediante el uso de loggers centralizados que capturan en tiempo real 
      el comportamiento del sistema, permitiendo seguir la traza de ejecución, identificar errores recurrentes y realizar ajustes 
      sobre los casos de prueba para mejorar su efectividad.
    </td>
  </tr>
  <tr>
    <td rowspan="2">QA-05</td>
    <td><b>Modificabilidad</b></td>
    <td>Equipo dev</td>
    <td>Cambios en reglas o lógica del sistema</td>
    <td>Backend</td>
    <td>Mantenimiento</td>
    <td>Módulos desacoplados e interfaces para cambios sin afectar otras funcionalidades</td>
    <td>Tiempo de modificación ≤ 1 día</td>
    <td>US-12, US-13, US-14, US-18</td>
  </tr>
  <tr>
    <td colspan="8">
      El equipo de desarrollo podrá modificar la lógica o reglas del sistema relacionadas a publicaciones o intercambios, 
      sin afectar otras funcionalidades, gracias al desacoplamiento de módulos y uso de interfaces, aplicando los cambios 
      exitosamente en un tiempo no mayor a un día.
    </td>
  </tr>
  <tr>
    <td rowspan="2">QA-06</td>
    <td><b>Interoperabilidad</b></td>
    <td>Sistema externo</td>
    <td>Interacción con APIs de terceros</td>
    <td>Servicios externos integrados</td>
    <td>Operación normal</td>
    <td>Comunicación fluida mediante REST APIs, adaptadores y formato JSON</td>
    <td>Integración funcional sin errores</td>
    <td>US-01, US-03, US-18, US-31, US-32</td>
  </tr>
  <tr>
    <td colspan="8">
      El sistema podrá integrarse con servicios externos como Paypal o Gemini AI en un entorno de operación normal, 
      realizando comunicaciones correctas a través de APIs RESTful, utilizando adaptadores y el formato estándar JSON, 
      garantizando una integración sin errores.
    </td>
  </tr>
  <tr>
    <td rowspan="2">QA-07</td>
    <td><b>Usabilidad</b></td>
    <td>Usuario</td>
    <td>Interacción con interfaz</td>
    <td>Interfaz web (Angular)</td>
    <td>Navegación estándar</td>
    <td>Flujo guiado, retroalimentación inmediata, tareas completadas en pocos pasos</td>
    <td>Tareas completadas en ≤ 4 clics</td>
    <td>US-01, US-06, US-12, US-13, US-18, US-31, US-32</td>
  </tr>
  <tr>
    <td colspan="8">
      El usuario podrá completar tareas clave como registrarse, crear publicaciones o aceptar intercambios en un entorno de operación normal, 
      con una interfaz optimizada que permite completar cada acción en un máximo de 4 clics, con mensajes claros de confirmación o error.
    </td>
  </tr>
</table><br><br>

#### 4.1.2.3 Constraints


Los "Constraints" son limitaciones que deben tenerse en cuenta durante el desarrollo de un proyecto de software. Estas pueden provenir de factores técnicos, operativos, legales o de negocio, y afectan las decisiones de diseño y arquitectura del sistema. Es importante identificar estas restricciones desde el inicio del proyecto para asegurar que la solución final sea viable y cumpla con los requisitos establecidos.

A continuación, se presentan los "Constraints" que guiarán el desarrollo de nuestro sistema.

|**ID**|**Constraint**|
| :-: | :-: |
|CON-1|La autenticación se gestionará mediante JWT, generando tokens de acceso y refresco al iniciar sesión. Estos se almacenan de forma segura en el frontend y se envían en las solicitudes protegidas. El backend valida los tokens antes de permitir el acceso, asegurando sesiones seguras y facilitando una futura integración con OAuth 2.0.|
|CON-2|El sistema debe establecer conexión con una base de datos relacional MySQL alojada en Azure, utilizando JDBC como mecanismo de acceso desde el backend. Esto requiere definir correctamente el pool de conexiones, el manejo de credenciales seguras y el uso de queries optimizadas que respeten las restricciones de escalabilidad de Azure Database for MySQL.|
|CON-3|La arquitectura general del sistema debe seguir el estilo Cliente-Servidor, con una clara separación de responsabilidades. El frontend se desarrollará en Kotlin, enfocado en la presentación e interacción con el usuario, y el backend en Spring Boot, encargado de la lógica de negocio, seguridad y persistencia de datos.|
|CON-4|El frontend en Kotlin debe implementar el patrón de diseño Modelo-Vista-Controlador (MVC), donde la lógica de presentación (componentes), el modelo de datos (servicios) y el controlador (intermediarios) estén desacoplados para facilitar el mantenimiento, escalabilidad y pruebas unitarias.|
|CON-5|Las funcionalidades críticas del sistema como la gestión de usuarios, publicaciones, intercambios y notificaciones deben implementarse como microservicios independientes, que se comuniquen entre sí a través de un API Gateway. Esto facilitará la escalabilidad horizontal, el despliegue independiente y el aislamiento de fallos. Cada microservicio debe estar adecuadamente documentado y autenticado.|
|CON-6|Para las funciones de suscripción y pagos, el sistema deberá integrarse con un servicio externo mediante una API RESTful, como PayPal, usando autenticación segura (por ejemplo, tokens Bearer o OAuth 2.0) y cumpliendo estándares de seguridad como PCI DSS. Se debe garantizar el manejo adecuado de errores y la validación de las transacciones.|
|CON-7|El envío de correos electrónicos, como el cambio de contraseña, debe hacerse exclusivamente mediante EmailJS, configurado para trabajar con cuentas Gmail. Debe garantizarse la autenticidad del remitente, la correcta plantilla HTML/CSS de los correos y el cumplimiento de políticas anti-spam.|
|CON-8|Toda la lógica de acceso a datos en el backend desarrollado en Spring Boot debe implementarse bajo el patrón Repository, permitiendo una separación clara entre la lógica de negocio y la persistencia. Esto facilita el mantenimiento del código, la reutilización de consultas y la implementación de pruebas automatizadas.|
|CON-9|El sistema deberá aplicar el patrón Singleton en la clase InicioSesion para asegurar que solo exista una única instancia de esta clase durante la ejecución de la aplicación. Además, se debe usar el patrón Adapter para integrar las clases, garantizando compatibilidad estructural sin modificar sus interfaces originales.|


### 4.1.3 Architectural Drivers Backlog

En esta sección se presenta el conjunto de *Architectural Drivers* acordados por el equipo, como resultado del proceso iterativo llevado a cabo durante el Quality Attribute Workshop. El Architectural Drivers Backlog incluye los Functional Drivers más relevantes, los Quality Attribute Drivers priorizados y todas las Constraints que guían el diseño del sistema.  


| **Driver ID** | **Título de Driver** | **Descripción** | **Importancia para Stakeholders** | **Impacto en Architecture Technical Complexity** |
|---------------|----------------------|-----------------|-----------------------------------|-------------------------------------------------|
| F-01 | Registro de usuario | Permitir que un nuevo usuario se registre con validación de datos, email único y cifrado de contraseña. | High | Medium |
| F-02 | Iniciar sesión en la aplicación | Autenticación de usuarios registrados mediante login seguro con generación y validación de JWT. | High | Medium |
| F-03 | Crear publicación de intercambio | Posibilidad de que el usuario cree una publicación con imagen, descripción y validación de campos. | High | High |
| F-04 | Editar y eliminar publicaciones | Gestión de publicaciones existentes asegurando la validación de propiedad y persistencia correcta. | High | Medium |
| F-05 | Filtrado de objetos | Funcionalidad para que los usuarios filtren y busquen artículos de acuerdo con criterios definidos. | High | High |
| F-06 | Aceptar o rechazar intercambio | Gestión de ofertas de intercambio, permitiendo revisar detalles y registrar decisiones. | High | High |
| F-07 | Visualizar perfil del publicador | Consultar información pública y reputación del usuario que creó la publicación. | Medium | Medium |
| F-08 | IA con Gemini (autocompletado de publicaciones) | Generación de sugerencias automáticas de título, categoría y precio a partir de imágenes. | Medium | High |
| QA-01 | Seguridad en autenticación | Protección de datos sensibles mediante cifrado, validación de credenciales y uso de JWT. | High | Medium |
| QA-02 | Disponibilidad | Mantener el servicio accesible con 99.9% de uptime mediante balanceadores y backend distribuido. | High | High |
| QA-03 | Performance | Respuestas rápidas (≤ 2s) en búsquedas, publicaciones y uso de IA con caché y optimización de consultas. | High | High |
| QA-04 | Testeabilidad | Uso de loggers, pruebas unitarias y modularidad para lograr cobertura ≥ 85%. | Medium | Medium |
| QA-05 | Modificabilidad | Arquitectura modular que permita cambios en la lógica en ≤ 1 día sin afectar otras funcionalidades. | Medium | High |
| QA-06 | Interoperabilidad | Integración fluida con APIs externas (Gemini, PayPal, EmailJS) mediante REST y JSON. | High | High |
| QA-07 | Usabilidad | Garantizar que tareas clave puedan completarse en ≤ 4 clics con retroalimentación inmediata. | High | Medium |
| CON-01 | Autenticación con JWT | Toda la gestión de sesiones se hará mediante JWT con tokens de acceso y refresco. | High | Medium |
| CON-02 | Base de datos MySQL en Azure | Persistencia de datos en MySQL con acceso vía JDBC y optimización de queries. | High | High |
| CON-03 | Arquitectura Cliente-Servidor | Frontend en Kotlin y backend en Spring Boot con separación de responsabilidades. | High | High |
| CON-04 | MVC en frontend | Implementación del patrón MVC en Kotlin para mantener desacoplamiento. | Medium | Medium |
| CON-05 | Microservicios independientes | Funcionalidades críticas como usuarios, publicaciones y notificaciones serán microservicios separados con API Gateway. | High | High |
| CON-06 | Integración con PayPal | Pagos y suscripciones gestionados mediante API REST segura con cumplimiento PCI DSS. | High | High |
| CON-07 | Emails con EmailJS | Envío de notificaciones y recuperación de contraseñas a través de EmailJS. | Medium | Medium |
| CON-08 | Patrón Repository en backend | Separación entre lógica de negocio y acceso a datos en Spring Boot. | Medium | Medium |
| CON-09 | Patrones Singleton y Adapter | Uso de Singleton en InicioSesion y Adapter para compatibilidad de clases. | Low | Medium |


### 4.1.4 Architectural Design Decisions

<table border="1" cellspacing="0" cellpadding="5"> <thead> <tr> <th>Driver ID</th> <th>Título de Driver</th> <th colspan="2">Pattern 1</th> <th colspan="2">Pattern 2</th> <th colspan="2">Pattern 3</th> </tr> <tr> <th colspan="2"></th> <th>Pro</th> <th>Con</th> <th>Pro</th> <th>Con</th> <th>Pro</th> <th>Con</th> </tr> </thead> <tbody> <tr> <td rowspan="2">QA-01</td> <td rowspan="2">Seguridad</td> <td colspan="2">JWT Authentication</td> <td colspan="2">HTTPS + TLS</td> <td colspan="2">BCrypt Hashing</td> </tr> <tr> <td>Validación segura de usuarios.</td> <td>Gestión de tokens compleja.</td> <td>Protege la comunicación.</td> <td>Puede afectar performance si no se configura bien.</td> <td>Cifrado fuerte de contraseñas.</td> <td>Mayor tiempo de procesamiento en registro/login.</td> </tr> <tr> <td rowspan="2">QA-02</td> <td rowspan="2">Disponibilidad</td> <td colspan="2">Load Balancer</td> <td colspan="2">Database Replication</td> <td colspan="2">REST API</td> </tr> <tr> <td>Distribución de carga eficiente.</td> <td>Configuración y monitoreo adicional.</td> <td>Alta disponibilidad de datos.</td> <td>Complejidad en sincronización.</td> <td>Simplicidad en despliegue y mantenimiento.</td> <td>Puntos únicos de fallo si no hay redundancia.</td> </tr> <tr> <td rowspan="2">QA-03</td> <td rowspan="2">Performance</td> <td colspan="2">Caching</td> <td colspan="2">Database Indexing</td> <td colspan="2">Pagination</td> </tr> <tr> <td>Reduce tiempo de respuesta.</td> <td>Consistencia de datos puede complicarse.</td> <td>Consultas más rápidas.</td> <td>Mayor uso de almacenamiento.</td> <td>Evita sobrecarga de resultados.</td> <td>Más lógica en frontend/backend.</td> </tr> <tr> <td rowspan="2">QA-05</td> <td rowspan="2">Modificabilidad</td> <td colspan="2">Modular Architecture</td> <td colspan="2">Interface Segregation</td> <td colspan="2">Dependency Injection</td> </tr> <tr> <td>Cambios aislados.</td> <td>Mayor planificación inicial.</td> <td>Evita acoplamiento.</td> <td>Más clases/interfaces a mantener.</td> <td>Fácil reemplazo de dependencias.</td> <td>Curva de aprendizaje para el equipo.</td> </tr> </tbody> </table>



### 4.1.5 Quality Attribute Scenario Refinements

<table border="1" cellspacing="0" cellpadding="5">
  <caption><strong>Scenario Refinement for Scenario QA-01</strong></caption>

  <tr>
    <th colspan="2">Scenario(s)</th>
    <td>El usuario envía datos sensibles (credenciales o información de registro) y el sistema los valida de forma segura en ≤ 2 segundos.</td>
  </tr>
  <tr>
    <th colspan="2">Business Goals</th>
    <td>Garantizar seguridad en el acceso y protección de datos sensibles.</td>
  </tr>
  <tr>
    <th colspan="2">Relevant Quality Attributes</th>
    <td>Seguridad</td>
  </tr>
  <tr>
    <th colspan="2">Stimulus</th>
    <td>Envío de credenciales o información sensible.</td>
  </tr>
  <tr>
    <th rowspan="5">Scenario Components</th>
    <th>Stimulus Source</th>
    <td>Usuario</td>
  </tr>
  <tr><th>Environment</th><td>Operación normal</td></tr>
  <tr><th>Artifact (if Known)</th><td>Sistema de autenticación y gestión de usuarios</td></tr>
  <tr><th>Response</th><td>Validación con JWT y cifrado con bcrypt.</td></tr>
  <tr><th>Response Measure</th><td>Validación segura en ≤ 2 segundos.</td></tr>
  <tr><th colspan="2">Questions</th><td>¿Se necesitará OAuth 2.0 para terceros?</td></tr>
  <tr><th colspan="2">Issues</th><td>Riesgo de ataques de fuerza bruta si no se limita intentos.</td></tr>
</table>


<table border="1" cellspacing="0" cellpadding="5">
  <caption><strong>Scenario Refinement for Scenario QA-02</strong></caption>
  <tr>
    <th colspan="2">Scenario(s)</th>
    <td>El sistema responde de forma estable ante solicitudes concurrentes, asegurando 99.9% de uptime mensual.</td>
  </tr>
  <tr><th colspan="2">Business Goals</th><td>Garantizar disponibilidad continua del servicio.</td></tr>
  <tr><th colspan="2">Relevant Quality Attributes</th><td>Disponibilidad</td></tr>
  <tr><th colspan="2">Stimulus</th><td>Solicitudes simultáneas de múltiples usuarios.</td></tr>
  <tr>
    <th rowspan="5">Scenario Components</th>
    <th>Stimulus Source</th><td>Usuario</td>
  </tr>
  <tr><th>Environment</th><td>Alta demanda</td></tr>
  <tr><th>Artifact (if Known)</th><td>Backend distribuido y balanceador de carga</td></tr>
  <tr><th>Response</th><td>Distribución eficiente del tráfico y continuidad del servicio.</td></tr>
  <tr><th>Response Measure</th><td>99.9% de disponibilidad mensual.</td></tr>
  <tr><th colspan="2">Questions</th><td>¿Qué pasa si falla el balanceador de carga?</td></tr>
  <tr><th colspan="2">Issues</th><td>Dependencia de la infraestructura en la nube.</td></tr>
</table>


<table border="1" cellspacing="0" cellpadding="5">
  <caption><strong>Scenario Refinement for Scenario QA-03</strong></caption>
  <tr>
    <th colspan="2">Scenario(s)</th>
    <td>El usuario realiza consultas de objetos/publicaciones y recibe respuesta en ≤ 2 segundos.</td>
  </tr>
  <tr><th colspan="2">Business Goals</th><td>Ofrecer una experiencia fluida y rápida.</td></tr>
  <tr><th colspan="2">Relevant Quality Attributes</th><td>Performance</td></tr>
  <tr><th colspan="2">Stimulus</th><td>Consulta a objetos o publicaciones.</td></tr>
  <tr>
    <th rowspan="5">Scenario Components</th>
    <th>Stimulus Source</th><td>Usuario</td>
  </tr>
  <tr><th>Environment</th><td>Operación normal</td></tr>
  <tr><th>Artifact (if Known)</th><td>Servicios de búsqueda y publicación</td></tr>
  <tr><th>Response</th><td>Uso de caché, consultas optimizadas y paginación.</td></tr>
  <tr><th>Response Measure</th><td>Tiempo de respuesta ≤ 2 segundos.</td></tr>
  <tr><th colspan="2">Questions</th><td>¿Se necesitará indexación adicional para consultas complejas?</td></tr>
  <tr><th colspan="2">Issues</th><td>Riesgo de lentitud con alta concurrencia si no hay escalado.</td></tr>
</table>


<table border="1" cellspacing="0" cellpadding="5">
  <caption><strong>Scenario Refinement for Scenario QA-04</strong></caption>
  <tr>
    <th colspan="2">Scenario(s)</th>
    <td>El equipo ejecuta pruebas en un entorno de integración continua con cobertura ≥ 85%.</td>
  </tr>
  <tr><th colspan="2">Business Goals</th><td>Asegurar calidad y reducir defectos en producción.</td></tr>
  <tr><th colspan="2">Relevant Quality Attributes</th><td>Testeabilidad</td></tr>
  <tr><th colspan="2">Stimulus</th><td>Ejecución de pruebas automáticas.</td></tr>
  <tr>
    <th rowspan="5">Scenario Components</th>
    <th>Stimulus Source</th><td>Equipo de desarrollo</td>
  </tr>
  <tr><th>Environment</th><td>Integración continua</td></tr>
  <tr><th>Artifact (if Known)</th><td>Sistema completo en entorno de pruebas</td></tr>
  <tr><th>Response</th><td>Logs centralizados y arquitectura modular facilitan pruebas.</td></tr>
  <tr><th>Response Measure</th><td>Cobertura ≥ 85%.</td></tr>
  <tr><th colspan="2">Questions</th><td>¿Qué pruebas deben ser obligatorias (unitarias, integración, end-to-end)?</td></tr>
  <tr><th colspan="2">Issues</th><td>El aumento de cobertura puede ralentizar entregas.</td></tr>
</table>


<table border="1" cellspacing="0" cellpadding="5">
  <caption><strong>Scenario Refinement for Scenario QA-05</strong></caption>
  <tr>
    <th colspan="2">Scenario(s)</th>
    <td>El equipo modifica reglas de negocio sin afectar otras funcionalidades en ≤ 1 día.</td>
  </tr>
  <tr><th colspan="2">Business Goals</th><td>Reducir el tiempo y costo de mantenimiento.</td></tr>
  <tr><th colspan="2">Relevant Quality Attributes</th><td>Modificabilidad</td></tr>
  <tr><th colspan="2">Stimulus</th><td>Solicitud de cambio en reglas o lógica del sistema.</td></tr>
  <tr>
    <th rowspan="5">Scenario Components</th>
    <th>Stimulus Source</th><td>Equipo de desarrollo</td>
  </tr>
  <tr><th>Environment</th><td>Mantenimiento</td></tr>
  <tr><th>Artifact (if Known)</th><td>Backend</td></tr>
  <tr><th>Response</th><td>Aplicación de cambios en módulos desacoplados e interfaces.</td></tr>
  <tr><th>Response Measure</th><td>Cambio aplicado en ≤ 1 día.</td></tr>
  <tr><th colspan="2">Questions</th><td>¿Qué partes del backend necesitan mayor refactorización?</td></tr>
  <tr><th colspan="2">Issues</th><td>Riesgo de deuda técnica si no se mantiene modularidad.</td></tr>
</table>


<table border="1" cellspacing="0" cellpadding="5">
  <caption><strong>Scenario Refinement for Scenario QA-06</strong></caption>
  <tr>
    <th colspan="2">Scenario(s)</th>
    <td>El sistema se integra con servicios externos (ej. PayPal) mediante APIs RESTful sin errores.</td>
  </tr>
  <tr><th colspan="2">Business Goals</th><td>Garantizar interoperabilidad y ampliar funcionalidades del sistema.</td></tr>
  <tr><th colspan="2">Relevant Quality Attributes</th><td>Interoperabilidad</td></tr>
  <tr><th colspan="2">Stimulus</th><td>Solicitud de interacción con servicios externos.</td></tr>
  <tr>
    <th rowspan="5">Scenario Components</th>
    <th>Stimulus Source</th><td>Sistema externo</td>
  </tr>
  <tr><th>Environment</th><td>Operación normal</td></tr>
  <tr><th>Artifact (if Known)</th><td>Servicios externos integrados</td></tr>
  <tr><th>Response</th><td>Comunicación fluida con adaptadores y JSON.</td></tr>
  <tr><th>Response Measure</th><td>Integración funcional sin errores.</td></tr>
  <tr><th colspan="2">Questions</th><td>¿Cómo se manejarán los fallos en servicios externos?</td></tr>
  <tr><th colspan="2">Issues</th><td>Dependencia de terceros puede afectar disponibilidad.</td></tr>
</table>


<table border="1" cellspacing="0" cellpadding="5">
  <caption><strong>Scenario Refinement for Scenario QA-07</strong></caption>
  <tr>
    <th colspan="2">Scenario(s)</th>
    <td>El usuario completa tareas clave en la interfaz web en ≤ 4 clics.</td>
  </tr>
  <tr><th colspan="2">Business Goals</th><td>Mejorar la experiencia de usuario y reducir fricción en la navegación.</td></tr>
  <tr><th colspan="2">Relevant Quality Attributes</th><td>Usabilidad</td></tr>
  <tr><th colspan="2">Stimulus</th><td>Interacción del usuario con la interfaz.</td></tr>
  <tr>
    <th rowspan="5">Scenario Components</th>
    <th>Stimulus Source</th><td>Usuario</td>
  </tr>
  <tr><th>Environment</th><td>Navegación estándar</td></tr>
  <tr><th>Artifact (if Known)</th><td>Interfaz web Angular</td></tr>
  <tr><th>Response</th><td>Flujo guiado con retroalimentación inmediata.</td></tr>
  <tr><th>Response Measure</th><td>Tareas completadas en ≤ 4 clics.</td></tr>
  <tr><th colspan="2">Questions</th><td>¿Es necesario aplicar test de usabilidad con usuarios reales?</td></tr>
  <tr><th colspan="2">Issues</th><td>La complejidad de nuevas funcionalidades puede aumentar clics.</td></tr>
</table>



## 4.2 Strategic-Level Domain-Driven Design
### 4.2.1 EventStorming


El proceso de EventStorming se llevó a cabo en la herramienta MIRO de manera colaborativa, con el propósito de identificar y organizar los principales elementos del dominio. La dinámica consistió en ir construyendo el flujo de manera progresiva, comenzando por los eventos, luego los comandos, los agregados y finalmente los sistemas externos.

En primer lugar, se identificaron los eventos de dominio, los cuales representan hechos que ya ocurrieron y que son relevantes para el negocio. Estos eventos fueron organizados en un flujo temporal que permite comprender cómo se desarrolla el proceso dentro del sistema.

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/EventStorming/events.png?raw=true" alt="events" style="width: 600px; height: auto;"><br><br>
</div>


Los comandos fueron definidos como las acciones que inician el flujo de cambios en el sistema y que, al ejecutarse, generan uno o varios eventos de dominio. Estos comandos expresan decisiones o intenciones de los usuarios y del propio sistema, y resultan clave para entender la relación causa–efecto entre la interacción de los actores y el comportamiento observado en el dominio.


<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/EventStorming/commands.png?raw=true" alt="commands" style="width: 600px; height: auto;"><br><br>
</div>

Los agregados se identificaron como los elementos encargados de mantener la consistencia en el sistema, agrupando eventos y comandos que afectan a una misma entidad. Cada agregado concentra reglas de negocio e invariantes que deben cumplirse, asegurando que los cambios se realicen de forma válida y coherente dentro del dominio.

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/EventStorming/aggregates.png?raw=true" alt="aggregates" style="width: 300px; height: auto;"><br><br>
</div>

Se incluyeron también los sistemas externos, entendidos como los actores, aplicaciones o servicios que interactúan con el dominio sin pertenecer a él. Estos sistemas participan ya sea enviando comandos que generan eventos, consumiendo información producida por el sistema o desencadenando procesos específicos en conjunto con los agregados.

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/EventStorming/external-systems.png?raw=true" alt="external system" style="width: 300px; height: auto;"><br><br>
</div>

Este modelado permitió obtener una representación general y estructurada del dominio, en la cual se evidencia la interacción entre los distintos elementos y se sientan las bases para un análisis más detallado en etapas posteriores.

En el caso de la autenticación, se representó el recorrido de un usuario desde el registro inicial hasta la validación de sus credenciales, incorporando los puntos de decisión que determinan si el acceso es aprobado o rechazado. La secuencia permitió identificar momentos clave en los que el sistema debe garantizar la seguridad y consistencia del proceso, estableciendo un mecanismo confiable para el ingreso a la plataforma.

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/EventStorming/flow-1.png?raw=true" alt="registro de usuario" style="width: 600px; height: auto;"><br><br>
</div>

En el escenario de publicación, se reflejó la interacción que sigue un usuario al dar de alta un nuevo artículo, abarcando desde la definición de los datos esenciales hasta la disponibilidad final del objeto en la plataforma. Durante este recorrido se reconocieron los puntos donde es indispensable validar la información registrada y las condiciones que aseguran que el artículo pueda ser ofrecido sin inconsistencias.

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/EventStorming/flow-2.png?raw=true" alt="publicar objeto" style="width: 600px; height: auto;"><br><br>
</div>

La dinámica de intercambio quedó representada como una negociación entre dos usuarios, donde cada acción desencadena respuestas que determinan la viabilidad de continuar con la operación. El modelado permitió visualizar los momentos críticos en los que el sistema debe corroborar la disponibilidad de los artículos, gestionar las solicitudes y confirmar el depósito de los objetos en el locker asignado antes de dar por concluida la transacción.

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/EventStorming/flow-3.png?raw=true" alt="responder intercambio" style="width: 600px; height: auto;"><br><br>
</div>

En lo relativo a las donaciones, se capturó la secuencia en la que los usuarios exploran las ONGs disponibles y seleccionan aquellas con las que desean colaborar. El recorrido describe cómo el sistema facilita la elección, valida la existencia de la organización y formaliza el registro de la donación, asegurando que la contribución quede asociada correctamente al usuario y la entidad receptora.

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/EventStorming/flow-4.png?raw=true" alt="buscar ongs" style="width: 600px; height: auto;"><br><br>
</div>

Finalmente, la suscripción fue representada como el proceso mediante el cual un usuario accede a planes que extienden sus beneficios en la plataforma. La representación incluye desde la elección de la modalidad deseada hasta la confirmación de pago, destacando los momentos en los que se asegura la continuidad de la membresía y la disponibilidad de las funcionalidades exclusivas.

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/EventStorming/flow-5.png?raw=true" alt="realizar suscripcion" style="width: 600px; height: auto;"><br><br>
</div>


### 4.2.2 Candidate Context Discovery

A partir del EventStorming realizado en MIRO, se identificaron los bounded contexts que agrupan eventos y comandos de manera coherente con las funcionalidades principales del sistema. Cada contexto refleja un subdominio específico y organiza el flujo de interacciones de acuerdo con su propósito dentro de la solución.


#### Bounded Context: IAM

El contexto de IAM (Identity and Access Management) concentra todo lo relacionado con la gestión de usuarios. Aquí se encuentran los procesos de creación de cuentas, inicio de sesión, autenticación y control de permisos. Este contexto asegura que solo los usuarios válidos puedan interactuar con el sistema y que cada acción esté respaldada por un proceso de autorización bien definido.

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/Candidate-Context-Discovery/Bounded-Context-IAM.png?raw=true" alt="iam" style="width: 600px; height: auto;"><br><br>
</div>

#### Bounded Context: Exchange

El contexto de Exchange cubre el núcleo de las funcionalidades de intercambio de objetos. En él se modelan las acciones de publicar, editar y eliminar publicaciones, así como los procesos de negociación: desde realizar una oferta hasta aceptarla o rechazarla. Este contexto refleja los flujos que permiten a los usuarios concretar intercambios de manera estructurada y transparente.

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/Candidate-Context-Discovery/Bounded-Context-Exchange.png?raw=true" alt="exchange" style="width: 600px; height: auto;"><br><br>
</div>

#### Bounded Context: Subscription

El contexto de Suscripción gestiona las membresías de los usuarios. Incluye los procesos de activación, renovación y cancelación de suscripciones, así como el seguimiento de su estado vigente. Este contexto permite administrar los diferentes niveles de acceso o beneficios asociados a cada usuario en función de su plan de suscripción.

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/Candidate-Context-Discovery/Bounded-Context-Subscription.png?raw=true" alt="subscription" style="width: 600px; height: auto;"><br><br>
</div>

#### Bounded Context: Donation

El contexto de Donation aborda las funcionalidades relacionadas con la donación de objetos a ONGs u organizaciones. Aquí se representan los procesos de publicación de objetos donables, la coordinación para la entrega y la confirmación de recepción. Este contexto facilita el flujo de colaboración entre los usuarios y las entidades beneficiarias.

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/Candidate-Context-Discovery/Bounded-Context-Donation.png?raw=true" alt="donation" style="width: 600px; height: auto;"><br><br>
</div>

#### Bounded Context: Review

El contexto de Review reúne todo lo referente a la evaluación y retroalimentación entre usuarios y organizaciones. Comprende la creación de reseñas, la asignación de valoraciones y la posibilidad de editar o consultar opiniones. Este contexto refuerza la confianza dentro del sistema al ofrecer visibilidad sobre la reputación de los participantes.

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/Candidate-Context-Discovery/Bounded-Context-Review.png?raw=true" alt="review" style="width: 600px; height: auto;"><br><br>
</div>

Finalmente, se consolidó una vista general en MIRO que agrupa todos los bounded contexts identificados. En esta representación se aprecian las nubes que encapsulan los eventos y comandos de cada subdominio, mostrando cómo se conectan y delimitan dentro del dominio completo del sistema.

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/Candidate-Context-Discovery/Bounded-Context-General.png?raw=true" alt="General Context" style="width: 600px; height: auto;"><br><br>
</div>



**Enlace:** https://miro.com/app/board/uXjVJKmx4DA=/?share_link_id=336330417188

### 4.2.3 Domain Message Flows Modeling

En esta seccion, se identificaron y priorizaron los flujos de mensajería más relevantes para el funcionamiento de la plataforma, en especial aquellos relacionados con la gestión de lockers inteligentes y los permisos de los usuarios. Estos flujos son fundamentales para garantizar la seguridad, trazabilidad y control de acceso durante los procesos de intercambio y donación de productos.

**1. Inicio de sesión del usuario-cliente** 

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/Domain-Message-Flows-Modeling/message-flow-1.png?raw=true" alt="inicio sesion" style="width: 600px; height: auto;"><br><br>
</div>

**2. Registro del usuario-cliente** 

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/Domain-Message-Flows-Modeling/message-flow-2.png?raw=true" alt="registro" style="width: 600px; height: auto;"><br><br>
</div>

**3. Oferta de intercambio usuario-cliente** 

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/Domain-Message-Flows-Modeling/message-flow-3.png?raw=true" alt="ofertar" style="width: 600px; height: auto;"><br><br>
</div>


**4. 	Publicación del objeto del usuario-cliente** 

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/Domain-Message-Flows-Modeling/message-flow-4.png?raw=true" alt="publicar" style="width: 600px; height: auto;"><br><br>
</div>

**Enlace:** https://miro.com/app/board/uXjVJKmx4DA=/?share_link_id=336330417188
### 4.1.1.4 Bounded Context Canvases

De acuerdo con los bounded contexts definidos previamente, se desarrollaron sus respectivos Context Canvases, con el fin de profundizar en sus responsabilidades, relaciones, mensajes clave y decisiones estratégicas dentro del dominio de CambiaZo.

**1. Bounded Context: IAM** 

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/Bounded-Context-Canvases/canvas-iam.png?raw=true" alt="bounded-iam" style="width: 600px; height: auto;"><br><br>
</div>

**1. Bounded Context: Exchange** 

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/Bounded-Context-Canvases/canvas-exchange.png?raw=true" alt="bounded-exchange" style="width: 600px; height: auto;"><br><br>
</div>

**1. Bounded Context: Subscription** 

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/Bounded-Context-Canvases/canvas-suscription.png?raw=true" alt="bounded-subscription" style="width: 600px; height: auto;"><br><br>
</div>

**1. Bounded Context: Donation** 
<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/Bounded-Context-Canvases/canvas-donation.png?raw=true" alt="bounded-donation" style="width: 600px; height: auto;"><br><br>
</div>

**1. Bounded Context: Review** 
<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/Bounded-Context-Canvases/canvas-review.png?raw=true" alt="bounded-review" style="width: 600px; height: auto;"><br><br>
</div>

**Enlace:** https://miro.com/app/board/uXjVJKmx4DA=/?share_link_id=336330417188

### 4.2.5 Context Mapping
En esta sección explicamos y evidenciamos el proceso de elaboración de un conjunto de mapas de contexto aplicados a nuestro proyecto CambiaZo, los cuales representan visualmente las relaciones estructurales entre los bounded contexts identificados. Para ello, analizamos detalladamente la información recolectada a lo largo del diseño del sistema, proponiendo y refinando diseños candidatos que ilustran cómo interactúan los contextos. Este análisis nos permitió alinear estratégicamente las responsabilidades y colaboraciones entre contextos, garantizando así una arquitectura coherente con los objetivos operativos y sociales de CambiaZo.

**IAM Context ↔ Exchanges Context**

El Exchanges Context depende del IAM Context para validar la identidad y permisos de los usuarios antes de iniciar o aceptar un intercambio. Esto garantiza que todas las operaciones dentro de Exchange se realicen únicamente con usuarios autenticados y autorizados, fortaleciendo la seguridad y confiabilidad de las transacciones.

<div align="center"> <img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/Context-Mapping/iam-exchange.png?raw=true" alt="IAM ↔ Exchanges" style="width: 600px; height: auto;"><br><br> </div>

**Subscription Context ↔ Exchanges Context**

El contexto de Subscription permite habilitar funcionalidades adicionales dentro del Exchange Context, como acceso a ciertos tipos de intercambios o beneficios especiales asociados a planes activos. Esta relación asegura que los servicios premium o restringidos solo estén disponibles para usuarios con suscripción vigente.

<div align="center"> <img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/Context-Mapping/suscription-exchange.png?raw=true" alt="Exchanges ↔ Subscription" style="width: 600px; height: auto;"><br><br> </div>

**Exchanges Context ↔ Review Context**

Review depende de eventos generados en Exchange, como la finalización de un intercambio, para habilitar la creación de reseñas y calificaciones de los usuarios participantes. Esto permite mantener un historial confiable de reputación y retroalimentación entre usuarios.

<div align="center"> <img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/Context-Mapping/Exchange-Review.png?raw=true"  alt="Exchanges ↔ Review" style="width: 600px; height: auto;"><br><br> </div>

**Enlace:** https://miro.com/app/board/uXjVJKmx4DA=/?share_link_id=336330417188

### 4.3 Software Architecture

En esta sección emplearemos el modelo C4 para crear la arquitectura de software, considerando aspectos como el contexto, los recipientes, los elementos y la implementación. Este enfoque permite una comprensión sencilla de la arquitectura, tanto para los miembros del equipo como para las partes interesadas externas.

#### 4.3.1 Software Architecture System Landscape Diagram.

El Landscape Diagram ofrece una visión general de CambiaZo, destacando los actores externos que interactúan con la plataforma. En el diagrama se muestran los usuarios, administradores y soporte técnico como los principales actores que utilizan el sistema. Esta representación permite comprender de manera clara las relaciones y la interacción de la plataforma con sus actores externos a nivel global.

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/Software-Architecture/Landscape.png?raw=true" alt="System Landscape Diagram" style="width: 600px; height: auto;"><br><br>
</div>

**Enlace:** https://structurizr.com/share/94931/0aebea0c-f409-4937-aadc-a82317655e11/diagrams#Landscape

#### 4.3.2 Software Architecture Context Level Diagrams.

El Diagrama de Contexto define el alcance de CambiaZo y sus relaciones con actores y sistemas externos. En la siguiente imagen, se detallan las interacciones entre usuarios, administradores, servicios de autenticación, pagos, correo electrónico y Gemini, estableciendo los fundamentos de la arquitectura del sistema y mostrando cómo los distintos sistemas colaboran para brindar funcionalidad completa.


<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/Software-Architecture/Context.png?raw=true" alt="Container Diagram" style="width: 600px; height: auto;"><br><br>
</div>

**Enlace:** https://structurizr.com/share/94931/0aebea0c-f409-4937-aadc-a82317655e11/diagrams#Contexto

#### 4.3.3 Software Architecture Container Level Diagrams.

El Diagrama de Contenedores descompone CambiaZo en sus unidades tecnológicas principales. A continuación, se muestra cómo la aplicación web, móvil, API RESTful y bases de datos colaboran para entregar funcionalidades completas que facilita la interacción entre componentes y el procesamiento de datos.

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/Software-Architecture/Containers.png?raw=true" alt="Container Diagram" style="width: 600px; height: auto;"><br><br>
</div>

**Enlace:** https://structurizr.com/share/94931/0aebea0c-f409-4937-aadc-a82317655e11/diagrams#Contenedores


#### 4.3.4 Software Architecture Deployment Diagrams.

El Diagrama de Despliegue describe la configuración física de CambiaZo en un entorno de desarrollo. En la siguiente imagen, se visualiza la distribución de componentes entre dispositivos cliente, servidores y nodos, asegurando una implementación eficiente y escalable del sistema.

<div align="center">
	<img src="https://github.com/TechZo-1ASI0728-Arquitectura/Report/blob/tb1/Resources/Chapter-IV/Software-Architecture/Deployment.png?raw=true" alt="Deployment Diagram" style="width: 600px; height: auto;"><br><br>
</div>


**Enlace:** https://structurizr.com/share/94931/0aebea0c-f409-4937-aadc-a82317655e11/diagrams#Deployment

<div style="page-break-after: always;"></div>

# Conclusiones

## Conclusiones y Recomendaciones

### Capítulo I – Introducción

Iniciamos nuestro proyecto con la formulación del experimento central: validar una hipótesis relacionada con una necesidad del mercado dentro del contexto de la Ingeniería de Software. Utilizamos el marco **Lean UX** como metodología estructurada para definir el problema de investigación, generando suposiciones basadas en observaciones previas y estableciendo hipótesis que guiaron el diseño experimental. El uso del *Lean UX Canvas* permitió al equipo definir variables clave, identificar factores y condiciones del entorno, y plantear objetivos de validación enfocados. Este enfoque estructurado facilitó la identificación de problemas reales del usuario, alineando el diseño del experimento con las necesidades del mercado y los objetivos de nuestra startup.

### Capítulo II – Requirements Elicitation & Analysis

En esta fase, ejecutamos un estudio cualitativo de necesidad utilizando **entrevistas semiestructuradas** y **observación directa**, métodos válidos dentro del diseño de experimentos exploratorios. El análisis competitivo complementó los datos, permitiéndonos identificar **variables independientes** (diferenciadores de mercado) y **dependientes** (percepción del usuario). Estos datos sirvieron para refinar nuestras hipótesis y establecer un plan experimental más sólido. La recolección ética de datos y la interpretación responsable de los mismos aseguraron la validez del experimento y la relevancia de los factores considerados, alineando nuestras decisiones con el impacto social y profesional de la ingeniería de software.

### Capítulo III – Requirements Specification

Definimos la arquitectura del producto como parte del diseño experimental de la intervención tecnológica. Se diseñaron **interfaces controladas** (landing page y app móvil) y se estableció una **arquitectura de software modular** para facilitar pruebas por componente e integración. La estructura basada en el dominio permitió establecer unidades de prueba aisladas, facilitando la medición del rendimiento, usabilidad y escalabilidad como variables dependientes. Este diseño controlado del entorno experimental garantiza **replicabilidad**, **trazabilidad de resultados** y **validez interna** en el análisis de la solución propuesta.

### Capítulo IV – Strategic-Level Software Design

En este capítulo se consolidó el diseño estratégico de la arquitectura de *CambiaZo*, integrando principios de **Attribute-Driven Design (ADD)** y **Domain-Driven Design (DDD)** para garantizar una base técnica sólida y orientada al dominio de intercambios y donaciones de objetos. A partir de los **drivers arquitectónicos**, se definieron decisiones clave que priorizan la escalabilidad, seguridad y experiencia de usuario, incorporando ahora módulos de **IA para recomendaciones personalizadas, autocompletado en publicaciones y soporte conversacional mediante chat inteligente**. El modelado de contextos, flujos de mensajes y diagramas arquitectónicos permitió establecer límites claros entre componentes, facilitando la trazabilidad de responsabilidades y la evolución futura del sistema. De esta forma, el diseño estratégico asegura que la solución no solo atienda las funcionalidades centrales, sino que también se mantenga flexible y preparada para la integración de nuevas capacidades basadas en inteligencia artificial.


### Conclusión

El desarrollo de *CambiaZo* se estructuró mediante un proceso experimental riguroso que inició con la definición del problema y la formulación de hipótesis bajo el marco **Lean UX**, continuó con la **elicitation y análisis de requerimientos** mediante investigación cualitativa y análisis competitivo, y avanzó hacia la **especificación y diseño arquitectónico** con un enfoque modular y basado en el dominio. Finalmente, se consolidó un **diseño estratégico de software** que integra principios de ADD y DDD, garantizando escalabilidad, seguridad y flexibilidad, al tiempo que incorpora **inteligencia artificial** para recomendaciones, autocompletado de publicaciones y soporte conversacional. Este recorrido metodológico asegura que la solución no solo responda a las necesidades reales de los usuarios y a los objetivos de mercado, sino que también cuente con bases sólidas para evolucionar y sostenerse en el tiempo como un sistema innovador y socialmente relevante.

<div style="page-break-after: always;"></div>

# Bibliografía
  <br>

+ Conventional Commits. (2023). *A specification for adding human and machine readable meaning to commit messages*. Conventional Commits. https://www.conventionalcommits.org/en/v1.0.0/  <br><br>

+ CPI Research. (2022). *Perú: Población 2022*. CPI. https://cpi.pe/images/upload/paginaweb/archivo/23/poblacion%202022.pdf <br><br>

+ Georgiou, M. (2024). *The importance of mobile app maintenance cost*. Imaginovation. https://imaginovation.net/blog/importance-mobile-app-maintenance-cost/ <br><br>

+ Huarachi-Coila, L. (2022). Mercado de trueque y seguridad alimentaria en los distritos de Acora e Ilave de Puno-Perú: periodo 2015-2017. *Semestre Económico, 11*(1), 28–43. https://doi.org/10.26867/se.2022.v11i1.126 <br><br>

+ Indeed. (2024). *How to write SMART goals*. Indeed. https://www.indeed.com/career-advice/career-development/how-to-write-smart-goals <br><br>

+ Kruse-Andersen, P. K. (2023). Directed technical change, environmental sustainability, and population growth. *Journal of Environmental Economics and Management, 122*, 102885. https://doi.org/10.1016/j.jeem.2023.102885 <br><br>

+ Liu, S., & Zhong, C. (2023). Green growth: Intellectual property conflicts and prospects in the extraction of natural resources for sustainable development. *Resources Policy, 80*, 104588. https://doi.org/10.1016/j.resourpol.2023.104588 <br><br>

+ Madaan, G., Singh, A., Mittal, A., & Shahare, P. (2024). Reduce, reuse, recycle: Circular economic principles, sustainability and entrepreneurship in developing ecosystems. *Journal of Small Business and Enterprise Development, ahead-of-print*. https://doi.org/10.1108/JSBED-01-2023-0009 <br><br>

+ Morseletto, P. (2023). Sometimes linear, sometimes circular: States of the economy and transitions to the future. *Journal of Cleaner Production, 390*, 136138. https://doi.org/10.1016/j.jclepro.2023.136138 <br><br>

+ Pivotal Tracker. (2024). *Quick start guide*. Pivotal Tracker. https://www.pivotaltracker.com/help/articles/quick_start/ <br><br>

+ Wang, F., Nan, N., & Zhao, J. (2024). Configuring mobile app update strategy for growth: An empirical analysis of a landscape search model. *Industrial Management & Data Systems, 124*(3), 1155-1178. https://doi.org/10.1108/IMDS-03-2023-0181 <br><br>

+ Zhao, S., Chen, S. H., Wang, F., Wei, Z. L., Zhong, J. C., & Liang, J. B. (2024). A large-scale mobile traffic dataset for mobile application identification. *Computer Journal, 67*(4), 1501-1513. https://doi.org/10.1093/comjnl/bxad076 <br><br>


<div style="page-break-after: always;"></div>

# Anexos

+ Video de exposición TB1: [Ver el vídeo](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216279_upc_edu_pe/EVHxImFNJq5ChVx4gPQoxb4Bty8YpzGTyuI2u1Pa72mGhQe=lopGPs&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

+ Landing Page: [Ver Landing Page](https://cambiazo-website.netlify.app/)

+ Repositorio GitHub de la Organización: [Ver Organización](https://github.com/TechZo-1ASI0728-Arquitectura)

+ Repositorio GitHub del Informe: [Ver Repositorio](https://github.com/TechZo-1ASI0728-Arquitectura/Report)

+ Repositorio GitHub del Backend: [Ver Repositorio](https://github.com/TechZo-1ASI0728-Arquitectura/Cambiazo-Microservices)

+ Repositorio GitHub de la Landing Page: [Ver Repositorio](https://github.com/TechZo-1ASI0728-Arquitectura/Landing-Page-CambiaZo)

+ Repositorio GitHub del Frontend: [Ver Repositorio](https://github.com/TechZo-1ASI0728-Arquitectura/CambiaZo-Frontend)
