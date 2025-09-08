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
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-I/Target-Segment/cuadro-estadistica-1.PNG?raw=true" alt="Estadistica Segmentos" style="width: 500px; height: auto;"><br><br>
	
    </div>
  + **Preferencias de Uso:** Valoran una plataforma intuitiva que facilite la búsqueda y el intercambio de productos. Prefieren opciones que ofrezcan seguridad y transparencia en las transacciones.<br><br>


+ **Personas adultas que desean donar artículos que ya no utilizan (Donadores):**<br>
“Cambiazo” es fundamental como herramienta para realizar donaciones, ya que permite que personas de escasos recursos puedan recibir donaciones de objetos de personas que ya no utilizan sus artículos y desean donarlos.

    + **Características demográficas:** Personas entre 15 y 60 años de edad con la voluntad de donar objetos propios que ya no utilizan a personas de escasos recursos económicos.

    + **Características geográficas:** Personas que residen en Perú.

    + **Motivaciones y Comportamientos:** Buscan contribuir a la comunidad y ayudar a quienes están en situación de necesidad. Valoran plataformas que les permitan realizar donaciones de manera sencilla y eficiente.

    + **Preferencias de Uso:** Prefieren una aplicación que facilite el proceso de donación, ofreciendo una lista de organizaciones benéficas y un sistema fácil de utilizar para coordinar las donaciones.

<br><br>


<div style="page-break-after: always;"></div>