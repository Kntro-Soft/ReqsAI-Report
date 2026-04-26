<body>
    <div style="text-align: center; font-weight: bolder">
        <p>Universidad Peruana de Ciencias Aplicadas - Ingeniería de Software - 8 Ciclo</p>
        <img src="assets/cover/logo-upc.png" alt="logo of UPC"/>
        <p>1ASI0732 - Arquitectura de Software Emergentes</p>
        <p>Sección - 11821</p>
        <p>Docente: Christian Luis De Los Rios Fernandez</p>   
        <p>Informe de Trabajo Final<p>
        <p>Startup: Kntro-Soft</p>
        <p>Producto: Reqs-AI</p>
    </div>
    <div style="text-align: center; display: flex; flex-direction: column; align-items: center">
        <h3 style="font-weight: bolder">Integrantes del equipo:</h3>
        <table style="width: fit-content">
            <tr>
                <th style="text-align:start;">Estudiante</th>
                <th style="text-align:center;">Código</th>
            </tr>
            <tr>
                <td style="text-align:start;">Gutiérrez Soto, Jhosepmyr Orlando</td>
                <td>202317638</td>
            </tr>
            <tr>
                <td style="text-align:start;">Hernández Tuiro, Eric Ernesto</td>
                <td>20221C857</td>
            </tr>
            <tr>
                <td style="text-align:start;">Ramirez Mestanza, Salim Ignacio</td>
                <td>20201E843</td>
            </tr>
            <tr>
                <td style="text-align:start;">Varela Bustinza, Marcelo Alessandro</td>
                <td>202319668</td>
            <tr>
              <td style="text-align:start;">Sulca Gonzales, Paul Fernando</td>
              <td>20221C486</td>
            </tr>
        </table>
    </div>
    <p style="text-align: center">Abril 2026</p>
</body>

<div style="page-break-before: always"></div>


# Registro de Versiones del Informe

| Versión | Fecha      | Autor                             | Descripción de modificación |
|---------|------------|-----------------------------------|-----------------------------|

<div style="page-break-before: always"></div>

# Project Report Collaboration Insights

En esta sección se documenta la colaboración del equipo en la elaboración del informe, mostrando evidencias gráficas de la actividad en GitHub y su coherencia con el registro de versiones.

* URL del repositorio del Project Report en la organización de GitHub del equipo:
* [https://github.com/Kntro-Soft/Report](https://github.com/Kntro-Soft/Report)

<div style="page-break-before: always"></div>

# Contenido

<!-- TOC -->
* [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
* [Project Report Collaboration Insights](#project-report-collaboration-insights)
* [Contenido](#contenido)
* [Student Outcome](#student-outcome)
* [Capítulo I: Introducción](#capítulo-i-introducción)
  * [1.1. Startup Profile](#11-startup-profile)
    * [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    * [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  * [1.2. Solution Profile](#12-solution-profile)
    * [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    * [1.2.2. Lean UX Process](#122-lean-ux-process)
      * [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      * [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      * [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      * [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  * [1.3. Segmentos objetivos](#13-segmentos-objetivos)
* [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  * [2.1. Competidores](#21-competidores)
    * [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    * [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  * [2.2. Entrevistas](#22-entrevistas)
    * [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    * [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    * [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  * [2.3. Need finding](#23-need-finding)
    * [2.3.1. User personas](#231-user-personas)
    * [2.3.2. User Task Matrix](#232-user-task-matrix)
    * [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    * [2.3.4. Empathy Mapping](#234-empathy-mapping)
    * [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  * [2.4. Ubiquitous Language](#24-ubiquitous-language)
* [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  * [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  * [3.2. User Stories](#32-user-stories)
  * [3.3. Product Backlog](#33-product-backlog)
  * [3.4. Impact Mapping](#34-impact-mapping)
* [Capítulo IV: Strategic-Level Product Design](#capítulo-iv-strategic-level-product-design)
  * [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
    * [4.1.1.	Design Purpose](#411-design-purpose)
    * [4.1.2.	Attribute-Driven Design Inputs](#412-attribute-driven-design-inputs)
      * [4.1.2.1.	Primary Functionality (Primary User Stories)](#4121-primary-functionality-primary-user-stories)
      * [4.1.2.2.	Quality attribute Scenarios](#4122-quality-attribute-scenarios)
        * [4.1.2.3.	Constraints](#4123-constraints)
    * [4.1.3.	Architectural Drivers Backlog](#413-architectural-drivers-backlog)
    * [4.1.4.	Architectural Design Decisions](#414-architectural-design-decisions)
    * [4.1.5.	Quality Attribute Scenario Refinements](#415-quality-attribute-scenario-refinements)
  * [4.2.	Strategic-Level Domain-Driven Design](#42-strategic-level-domain-driven-design)
    * [4.2.1.	EventStorming](#421-eventstorming)
    * [4.2.2.	Candidate Context Discovery](#422-candidate-context-discovery)
    * [4.2.3.	Domain Message Flows Modeling](#423-domain-message-flows-modeling)
    * [4.2.4.	Bounded Context Canvases](#424-bounded-context-canvases)
    * [4.2.5.	Context Mapping](#425-context-mapping)
  * [4.3.	Software Architecture](#43-software-architecture)
    * [4.3.1.	Software Architecture System Landscape Diagram](#431-software-architecture-system-landscape-diagram)
    * [4.3.1.	Software Architecture Context Level Diagrams](#431-software-architecture-context-level-diagrams)
    * [4.3.2.	Software Architecture Container Level Diagrams](#432-software-architecture-container-level-diagrams)
    * [4.3.3.	Software Architecture Deployment Diagrams](#433-software-architecture-deployment-diagrams)
* [Capítulo V: Tactical-Level Software Design](#capítulo-v-tactical-level-software-design)
  * [5.X.	Bounded Context: <Bounded Context Name>](#5x-bounded-context-bounded-context-name)
    * [5.X.1.	Domain Layer](#5x1-domain-layer)
    * [5.X.2.	Interface Layer](#5x2-interface-layer)
    * [5.X.3.	Application Layer](#5x3-application-layer)
    * [5.X.4.	Infrastructure Layer](#5x4-infrastructure-layer)
    * [5.X.6.	Bounded Context Software Architecture Component Level Diagrams](#5x6-bounded-context-software-architecture-component-level-diagrams)
    * [5.X.7.	Bounded Context Software Architecture Code Level Diagrams](#5x7-bounded-context-software-architecture-code-level-diagrams)
      * [5.X.7.1.	Bounded Context Domain Layer Class Diagrams](#5x71-bounded-context-domain-layer-class-diagrams)
      * [5.X.7.2.	Bounded Context Database Design Diagram](#5x72-bounded-context-database-design-diagram)
* [Capítulo VI: Solution UX Design](#capítulo-vi-solution-ux-design)
  * [6.1.	Style Guidelines](#61-style-guidelines)
    * [6.1.1.	General Style Guidelines](#611-general-style-guidelines)
    * [6.1.2.	Web, Mobile & Devices Style Guidelines](#612-web-mobile--devices-style-guidelines)
  * [6.2.	Information Architecture](#62-information-architecture)
    * [6.2.2.	Labeling Systems](#622-labeling-systems)
    * [6.2.3.	Searching Systems](#623-searching-systems)
    * [6.2.4.	SEO Tags and Meta Tags](#624-seo-tags-and-meta-tags)
    * [6.2.5.	Navigation Systems](#625-navigation-systems)
  * [6.3.	Landing Page UI Design](#63-landing-page-ui-design)
    * [6.3.1.	Landing Page Wireframe](#631-landing-page-wireframe)
    * [6.3.2.	Landing Page Mock-up](#632-landing-page-mock-up)
  * [6.4.	Applications UX/UI Design](#64-applications-uxui-design)
    * [6.4.1.	Applications Wireframes](#641-applications-wireframes)
    * [6.4.2.	Applications Wireflow Diagrams](#642-applications-wireflow-diagrams)
    * [6.4.2.	Applications Mock-ups](#642-applications-mock-ups)
    * [6.4.3.	Applications User Flow Diagrams](#643-applications-user-flow-diagrams)
  * [6.5.	Applications Prototyping](#65-applications-prototyping)
* [Capítulo VII: Product Implementation, Validation & Deployment](#capítulo-vii-product-implementation-validation--deployment)
  * [7.1.	Software Configuration Management](#71-software-configuration-management)
    * [7.1.1.	Software Development Environment Configuration](#711-software-development-environment-configuration)
    * [7.1.2.	Source Code Management](#712-source-code-management)
    * [7.1.3.	Source Code Style Guide & Conventions](#713-source-code-style-guide--conventions)
    * [7.1.4.	Software Deployment Configuration](#714-software-deployment-configuration)
  * [7.2.	Solution Implementation](#72-solution-implementation)
    * [7.2.X.	Sprint n](#72x-sprint-n)
      * [7.2.X.1.	Sprint Planning n](#72x1-sprint-planning-n)
      * [7.2.X.2.	Sprint Backlog n](#72x2-sprint-backlog-n)
      * [7.2.X.3.	Development Evidence for Sprint Review](#72x3-development-evidence-for-sprint-review)
      * [7.2.X.4.	Testing Suite Evidence for Sprint Review](#72x4-testing-suite-evidence-for-sprint-review)
      * [7.2.X.5.	Execution Evidence for Sprint Review](#72x5-execution-evidence-for-sprint-review)
      * [7.2.X.6.	Services Documentation Evidence for Sprint Review](#72x6-services-documentation-evidence-for-sprint-review)
      * [7.2.X.7.	Software Deployment Evidence for Sprint Review](#72x7-software-deployment-evidence-for-sprint-review)
      * [7.2.X.8.	Team Collaboration Insights during Sprint](#72x8-team-collaboration-insights-during-sprint)
  * [7.3.	Validation Interviews](#73-validation-interviews)
    * [7.3.1.	Diseño de Entrevistas](#731-diseño-de-entrevistas)
    * [7.3.2.	Registro de Entrevistas](#732-registro-de-entrevistas)
    * [7.3.3.	Evaluaciones según heurísticas](#733-evaluaciones-según-heurísticas)
  * [7.4.	Video About-the-Product](#74-video-about-the-product)
* [Conclusiones](#conclusiones)
* [Bibliografía](#bibliografía)
* [Anexos](#anexos)
<!-- TOC -->

<div style="page-break-before: always"></div>

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

****ABET - EAC - Student Outcome ****

**Criterio:** 

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 4.

| **Criterio específico** | **Acciones realizadas** | **Conclusiones** |
|-------------------------|-------------------------|------------------|  
| **.**                   |                         |                  |
| **.**                   |                         |                  |

<div style="page-break-before: always"></div>

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Kntro-Soft es una startup tecnológica peruana dedicada a la innovación en ingeniería de software mediante el uso de Inteligencia Artificial Generativa y procesamiento de lenguaje natural en tiempo real.
Nuestra misión es potenciar la productividad de los equipos de desarrollo y analistas de sistemas, eliminando la pérdida de información durante el levantamiento de requisitos, asegurando que cada necesidad del cliente se convierta en una historia de usuario precisa y completa.

**Propuesta de Valor**

* Documentación Instantánea: Generación automática de User Stories con criterios de aceptación en formato Gherkin mediante LLMs de última generación
* Asistencia Consultiva en Vivo: Sugerencias inteligentes de preguntas durante las reuniones para evitar vacíos de información y considerar casos de borde
* Contexto Inteligente (RAG): Integración con el historial del proyecto para detectar duplicados y asegurar que los nuevos requisitos sean consistentes con la arquitectura existente
* Privacidad Empresarial: Arquitectura multitenancy robusta con Row Level Security, garantizando que los datos y el conocimiento de cada organización permanezcan estrictamente aislados

**Visión**

Convertirnos en la plataforma estándar de gestión de requisitos para empresas de software en Latinoamérica, liderando la transición hacia un desarrollo de software asistido por IA que sea transparente, eficiente y libre de errores de comunicación.

**Valores**

* Precisión Técnica: Compromiso con la entrega de requisitos listos para el desarrollo.
* Agilidad: Reducción drástica del tiempo entre la reunión y el inicio de la codificación.
* Seguridad: Protección absoluta de la propiedad intelectual de nuestros clientes.
* Innovación Adaptativa: Evolución constante de nuestros modelos para entender los dialectos y modismos técnicos de la región.

### 1.1.2. Perfiles de integrantes del equipo

| Foto del participante                                                                       | Nombres y apellidos               | Código de estudiante | Carrera                | Conocimientos técnicos y habilidades                                                                                                                                                                                                                                            |
|---------------------------------------------------------------------------------------------|-----------------------------------|----------------------|------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![erick.png](assets/1.introduction/1.1.startup-profile/1.1.2.team-member/erick.png)         | Eric Ernesto Hernández Tuiro      | 20221C857            | Ingeniería de Software | Especialista en desarrollo backend con Java/Spring Boot y diseño de arquitecturas de sistemas. Enfocado en tecnologías empresariales y soluciones eficientes.                                                                                                                   |
| ![marcelo.png](assets/1.introduction/1.1.startup-profile/1.1.2.team-member/marcelo.jpg)     | Marcelo Alejandro Varela Bustinza | 202319668            | Ingeniería de Software | Desarrollador con experiencia en Angular/Spring Boot y Vue.js/ASP.NET, enfocado en arquitecturas monolíticas y desarrollo de aplicaciones.                                                                                                                                      | 
| ![jhosepmyr.png](assets/1.introduction/1.1.startup-profile/1.1.2.team-member/jhosepmyr.png) | Jhosepmyr Orlando Gutiérrez Soto  | 202317638            | Ingeniería de Software | Especialista en desarrollo full-stack con Java/Spring Boot y frameworks frontend como Angular y Vue.js. Experiencia en microservicios y servicios cloud (AWS, Azure, GCP). Aporta habilidades de liderazgo técnico, toma de decisiones y coordinación de equipos de desarrollo. | 
| ![paul.png](assets/1.introduction/1.1.startup-profile/1.1.2.team-member/paul.png)           | Paul Fernando Sulca Gonzales      | 20221C486            | Ingeniería de Software | Conocimiento en diseño de software orientado a objetos y modelado UML. Experiencia en implementación de interfaces web adaptativas. Amante de los desafíos de la vida universitaria.                                                                                            |
| ![salim.jpg](assets/1.introduction/1.1.startup-profile/1.1.2.team-member/salim.jpg)         | Salim Ignacio Ramirez Mestanza    | 20201E843            | Ingeniería de Software | Conocimiento en arquitectura de software y control de versiones con Git. Experiencia en documentación técnica y colaboración en equipos ágiles. Desarrollo backend con Java/Spring Boot y Domain-Driven Design.                                                                 |

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

Esta sección analiza la desconexión entre la captura de información y la ejecución en el desarrollo de software. Se utiliza la técnica de las 5W2H para desglosar cómo la gestión deficiente de requisitos impacta la rentabilidad y el éxito de los proyectos de TI, estableciendo la base fáctica que justifica la implementación de Kntro-Soft.

**Análisis mediante la técnica de las 5 W's y 2 H's:**

* WHO - ¿Quién está afectado?: El problema afecta principalmente a los Analistas de Sistemas, Product Owners y Business Analysts, quienes deben alternar entre la escucha activa y la toma de notas. Secundariamente, impacta a los equipos de desarrollo, startups de software, y a las empresas de software en el Perú.

* WHAT - ¿Cuál es el problema?: La pérdida de información crítica durante las reuniones de descubrimiento. A los analistas se les puede dificultar el procesar y documentar simultáneamente la información que brinda el cliente, generando requisitos incompletos y casos de borde ignorados. Esto deriva en una deuda técnica desde la concepción del producto.

* WHERE - ¿Dónde ocurre?: En el entorno de las empresas de servicios de software y startups de desarrollo de software en Perú y Latinoamérica. Se manifiesta tanto en reuniones presenciales como en videollamadas, donde el flujo de información es rápido y desestructurado.

* WHEN - ¿Cuándo sucede?: Ocurre durante la fase de Elicitación de Requisitos. La crisis de documentación se agrava después de la reunion, cuando el analista intenta reconstruir lo conversado, perdiendo varios detalles específicos y dándose cuenta de dudas y preguntas importantes que no resolvió con el cliente durante la reunión.

* WHY - ¿Por qué persiste?: Por la dependencia en métodos manuales. La captura de requisitos sigue siendo un proceso artesanal en una industria automatizada. Según el Project Management Institute (PMI), la comunicación deficiente es la razón principal del fracaso en 1 de cada 3 proyectos de TI.

* HOW - ¿Cómo se manifiesta el problema?: Se evidencia en el retrabajo. Las historias de usuario mal definidas obligan a los desarrolladores a detenerse para pedir aclaraciones o, peor aún, a construir funcionalidades que no cumplen con la expectativa del cliente, generando ciclos de feedback infinitos.

* HOW MUCH - ¿Cuál es la magnitud del impacto?: * Costo de Fallas: El 47% de los proyectos de software fallan o se ven comprometidos debido a una mala gestión de requisitos (Standish Group, 2020). Impacto Económico: Corregir un error de requisitos durante la fase de desarrollo cuesta hasta 10 veces más que hacerlo durante la fase de diseño. Si el error llega a producción, el costo se eleva a 100 veces más (Ver Anexos 1). Desperdicio Financiero: Las organizaciones pierden, en promedio, US$ 97 millones por cada 1,000 millones invertidos debido a un desempeño deficiente de los proyectos (PMI, 2018).

### 1.2.2. Lean UX Process

Esta sección aplica el Proceso Lean UX para estructurar la visión del negocio del proyecto WasteTrack. Se inicia con la formulación del problema, se desglosan las suposiciones fundamentales que sostienen el modelo de negocio y de producto, y finalmente se traducen estas suposiciones en hipótesis comprobables que guiarán el ciclo de desarrollo y validación.

#### 1.2.2.1. Lean UX Problem Statements

El estado actual de la ingeniería de requisitos en el desarrollo de software depende principalmente en la captura pasiva de información a través de grabaciones de video y transcripciones automáticas, las cuales funcionan como una memoria histórica para que el analista de sistemas revise el contenido después de la reunión.

Lo que los servicios y flujos de trabajo existentes no logran abordar es el desafío del razonamiento y la validación en tiempo real. Actualmente, el analista suele descubrir ambigüedades, casos de borde no considerados y vacíos de lógica recién cuando procesa la grabación horas o días después. Esto genera un ciclo ineficiente de reuniones de seguimiento para aclarar dudas que pudieron resolverse en el momento si se hubiera contado con un soporte analítico inmediato.

Nuestro producto, Reqs-AI, abordará esta brecha mediante un motor de inteligencia artificial que procesa el audio en vivo para generar historias de usuario estructuradas mientras la reunión ocurre. Su valor diferencial reside en un asistente de consulta activa que proporciona sugerencias de preguntas críticas al analista en tiempo real, asegurando que toda duda técnica o de negocio sea resuelta mientras el cliente aún está presente.

Nuestro enfoque inicial serán las Startups tecnológicas y empresas de desarrollo de software que operan bajo metodologías ágiles y necesitan una transición inmediata y sin errores desde la fase de descubrimiento hasta el inicio de la codificación.

Sabremos que hemos tenido éxito cuando observemos una reducción del 40% en las reuniones de seguimiento para aclaración de requisitos, una disminución significativa en el tiempo que el analista dedica al post-procesamiento de la información y una tasa de aceptación de historias de usuario superior al 80% en la primera iteración de revisión con el equipo de desarrollo.


#### 1.2.2.2. Lean UX Assumptions

Esta sección presenta las suposiciones fundamentales del proyecto Reqs-AI, estructuradas bajo el marco de Lean UX. Aquí definimos los resultados de negocio esperados, los perfiles de usuario que enfrentan el problema y los beneficios tangibles que estos obtendrán al utilizar nuestra solución.

**Business Outcomes (Resultados de Negocio):**

Utilizamos el framework AARRR (Pirate Metrics) para cuantificar el impacto estratégico de Reqs-AI en el mercado de startups y empresas:
* Acquisition (Adquisición): El 25% de las empresas contactadas se registrarán para una prueba gratuita de 14 días.
* Activation (Activación): El 40% de los usuarios registrados procesará al menos 3 reuniones reales y generará un set de User Stories en su primera semana.
* Retention (Retención): El 60% de las Startups que completen la prueba gratuita optarán por una suscripción mensual activa.
* Revenue (Ingresos): Se proyecta un Ingreso Mensual Recurrente (MRR) promedio de $49 por Startup y contratos anuales de 4,000+ para Empresas.
* Referral (Recomendación): 1 de cada 4 usuarios activos recomendará la herramienta a otros colegas en comunidades de Product Management o Ingeniería.

**Users (Usuarios)**
Hemos identificado dos perfiles clave que enfrentan el reto de transformar la voz del cliente en código, adaptados a la realidad de una Startup y una organización corporativa:

| Usuario                           | Perfil                                                      | Objetivos                                                                                                                              | Obstáculos                                                                                              |
|:----------------------------------|:------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------|
| **Alex (Tech Leader)**            | 32 años, Desarrollador Senior que lidera el equipo técnico. | Traducir visiones de negocio a especificaciones técnicas, evitar deuda técnica por requisitos ambiguos, agilizar el inicio del sprint. | Alta carga de trabajo técnico, dificultad para documentar mientras lidera la discusión técnica.         |
| **Claudia (Analista Enterprise)** | 35 años, Business Analyst en una corporación.               | Estandarizar requisitos en Gherkin, asegurar que nada quede ambiguo, cumplir con normas de seguridad.                                  | Reuniones largas y densas, dificultad para procesar horas de grabación, burocracia en la documentación. |

**User Outcomes (Resultados de Usuario)**
Estos son los resultados esperados por nuestros usuarios, divididos según el valor que perciben al usar Reqs-AI:

* Startup Lead:
Funcional: Obtener historias de usuario en Gherkin y restricciones técnicas listas para el backlog inmediatamente al finalizar la sesión.
Emocional: Sentir la seguridad de que la arquitectura y los casos críticos están alineados con la expectativa del cliente antes de escribir una sola línea de código
Aspiracional: Ser el facilitador de una cultura de ingeniería de alto rendimiento donde la documentación nunca es un cuello de botella para la innovación.

* Analista Enterprise:
Funcional: Eliminar el trabajo manual de transcribir grabaciones y redactar Gherkin desde cero.
Emocional: Sentirse empoderada durante la reunión al recibir sugerencias de preguntas que exponen vacíos de lógica del cliente.
Aspiracional: Posicionarse como una analista estratégica que garantiza la precisión del proyecto, reduciendo el retrabajo del equipo.

#### 1.2.2.3. Lean UX Hypothesis Statements

**Test (Alto valor, alto riesgo)**

* Hipótesis 1 (Riesgo de Valor y Comportamiento):
El equipo cree que proporcionar sugerencias automáticas de preguntas sobre casos de borde en tiempo real para el Analista de Sistemas logrará una captura de requisitos exhaustiva durante la primera interacción. Se sabrá que esto es cierto cuando el analista plantee al menos el 60% de las sugerencias generadas por la IA durante la sesión en vivo con el cliente, reduciendo la necesidad de reuniones de aclaración posteriores.

* Hipótesis 2 (Riesgo de Confianza Técnica):
El equipo cree que la generación instantánea de historias de usuario en formato Gherkin utilizando contexto previo (RAG) para el Líder Técnico de una Startup logrará acelerar el ciclo de inicio del desarrollo (discovery-to-delivery). Se sabrá que esto es cierto cuando el tiempo promedio dedicado por el rol a la edición y corrección manual de las historias generadas sea menor a 15 minutos por sesión.

**Ship & Measure (Alto valor, bajo riesgo)**

* Hipótesis 3 (Riesgo de Adopción Funcional):
El equipo cree que la integración de un botón de exportación directa hacia herramientas de gestión para el Líder Técnico de una Startup logrará una mayor retención de uso de la plataforma. Se sabrá que esto es cierto cuando el 80% de las historias de usuario validadas en Reqs-AI sean sincronizadas con el backlog del proyecto en los primeros 10 minutos posteriores al cierre de la reunión.

* Hipótesis 4 (Riesgo de Cumplimiento y Seguridad):
El equipo cree que la implementación de una arquitectura de aislamiento de datos mediante Row Level Security (RLS) para el Analista de Sistemas Enterprise logrará mitigar las preocupaciones de privacidad de la información corporativa. Se sabrá que esto es cierto cuando las organizaciones interesadas completen el proceso de registro y configuración del perfil organizacional tras revisar la documentación de seguridad y multitenancy del sistema.

#### 1.2.2.4. Lean UX Canvas

![lean-ux-canvas](assets/1.introduction/1.2.solution-profile/1.2.2.lean-ux-process/LEAN-UX-CANVAS-Reqs-AI.png)

## 1.3. Segmentos objetivos

**Segmento 1: Líder Técnico de Startup**

**Descripción:**

Este segmento representa al motor técnico y estratégico de empresas tecnológicas en etapa de crecimiento. Son profesionales que cumplen roles híbridos entre la gestión de producto y el desarrollo.
Su principal motivación es la velocidad de entrega y la precisión técnica. Se frustran al perder tiempo valioso en la documentación manual tras reuniones intensas y al descubrir "deuda de requisitos" solo cuando ya están en plena fase de codificación. Buscan una herramienta que les permita pasar de la conversación al código sin fricciones.

**Características Demográficas (Perfil Inferido):**

| Aspecto                  | Detalle                                                                    |
|--------------------------|----------------------------------------------------------------------------|
| Rango de Edad            | 30 - 35 años                                                               |
| Nivel Educativo          | Universitario o Postgrado (Ingeniería de Software, Sistemas o Computación) |
| Entorno Laboral          | Startups, ambientes ágiles, trabajo remoto o híbrido                       |
| Familiaridad Tecnológica | Nativo digital; uso experto de APIs, LLMs, y herramientas como Jira/Notion |

**Segmento 2: Analista de Sistemas Enterprise**

**Descripción:**

Este segmento representa al profesional encargado de la gobernanza de requisitos en grandes corporaciones o Software Factories. Su enfoque principal es la estandarización y la mitigación de riesgos.
Deben asegurar que cada requerimiento del cliente esté perfectamente documentado en formatos rigurosos como Gherkin para su posterior pase a desarrollo y testing (QA). Actualmente, su mayor dolor es la carga operativa de procesar horas de grabaciones para extraer criterios de aceptación, enfrentando el riesgo de malinterpretar la visión del cliente por falta de validación inmediata en la reunión.

**Características Demográficas (Perfil Inferido):**

| Aspecto                  | Detalle                                                                                             |
|--------------------------|-----------------------------------------------------------------------------------------------------|
| Rango de Edad            | 30 - 45 años                                                                                        |
| Nivel Educativo          | Universitario o Postgrado (Gestión de Proyectos, Business Analysis)                                 |
| Entorno Laboral          | Corporativo, grandes departamentos de TI, procesos bajo marcos CMMI o SAFe                          |
| Familiaridad Tecnológica | Alta; manejo de herramientas de modelado y gestión empresarial (Azure DevOps, Enterprise Architect) |

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

### 2.2.2. Registro de entrevistas

### 2.2.3. Análisis de entrevistas

## 2.3. Need finding

### 2.3.1. User personas

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

### 2.3.5. As-is Scenario Mapping

## 2.4. Ubiquitous Language

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

## 3.2. User Stories

## 3.3. Product Backlog

## 3.4. Impact Mapping

# Capítulo IV: Strategic-Level Product Design

## 4.1. Strategic-Level Attribute-Driven Design

### 4.1.1.	Design Purpose

El propósito del proceso de diseño de Reqs-AI es establecer una arquitectura de software capaz de resolver tecnológicamente la desconexión y pérdida de información que ocurre durante el levantamiento de requisitos. El diseño está concebido como un sistema creado desde cero orientado a construir una solución robusta, escalable y en tiempo real que traduzca la voz del cliente directamente en especificaciones técnicas de alto valor.

Este diseño está directamente orientado a satisfacer las necesidades críticas de nuestros dos segmentos objetivos:
* **Para el Líder Técnico de Startup:** La arquitectura priorizará el rendimiento y la integración (flujos automatizados hacia herramientas como Jira), asegurando agilidad y la reducción del tiempo entre el *discovery* y el desarrollo.
* **Para la Analista Enterprise:** El diseño se centrará en la seguridad y la privacidad de los datos, estableciendo una arquitectura *Multitenancy* con aislamiento de datos estricto (*Row Level Security*), cumpliendo así con las exigencias corporativas y mitigando los riesgos de fuga de información.

A nivel de negocio para la startup Kntro-Soft, el diseño tiene el propósito de habilitar el modelo de distribución SaaS (Software as a Service). La arquitectura debe soportar el sistema de suscripciones y facturación, gestionar los límites de consumo de los motores de IA (LLMs) para mantener la rentabilidad, y asegurar que la plataforma pueda escalar el procesamiento de múltiples organizaciones concurrentes sin degradar la experiencia de usuario.

### 4.1.2.	Attribute-Driven Design Inputs

En esta sección se presentan las entradas fundamentales requeridas para ejecutar el proceso de diseño arquitectónico basado en el método Attribute-Driven Design (ADD). Estos inputs proporcionan el contexto, las metas y los límites que guiarán la toma de decisiones técnicas para la plataforma Reqs-AI. A continuación, el contenido se divide en tres categorías principales dictadas por la metodología: la funcionalidad primaria, los escenarios de atributos de calidad y las restricciones.

#### 4.1.2.1.	Primary Functionality (Primary User Stories)

A continuación, se detallan las Historias de Usuario primarias que tienen el mayor impacto arquitectónico en el diseño de Reqs-AI. Estas funcionalidades han sido seleccionadas porque introducen requerimientos complejos de procesamiento asíncrono (análisis de audio en tiempo real), integración con servicios de Inteligencia Artificial (LLMs) y aislamiento estricto de datos (Multitenancy), elementos que dictarán la topología base del sistema.

| Epic / User Story ID | Título                             | Descripción                                                                                                                                                                                     | Criterios de Aceptación                                                                                                                                                                                                                                                          | Relacionado con (Epic ID) |
|:---------------------|:-----------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------------------|
| **US05**             | Crear organización                 | Como usuario autenticado sin organización, quiero crear un espacio de trabajo con el nombre de mi empresa, para centralizar proyectos en un entorno separado.                                   | **Given** un usuario autenticado sin organización<br>**When** crea una organización con un nombre válido<br>**Then** el sistema genera el espacio de trabajo<br>**And** asigna al usuario el rol inamovible de 'Propietario'                                                     | EP02                      |
| **US16**             | Cargar documentos del cliente      | Como miembro, quiero subir documentos del cliente al proyecto, para que las historias generadas reflejen el vocabulario del negocio (RAG).                                                      | **Given** un usuario configurando un proyecto<br>**When** sube un glosario en PDF válido<br>**Then** el sistema debe fragmentar (chunking), vectorizar y persistir el documento en una base de datos vectorial en menos de 10 segundos                                           | EP04                      |
| **US29**             | Generación automática de historias | Como analista, quiero que el sistema procese el audio en vivo y redacte automáticamente historias de usuario estructuradas con criterios de aceptación, para ahorrar horas de redacción manual. | **Given** una sesión de captura de audio activa<br>**When** el sistema recibe y transcribe el flujo de voz<br>**Then** el motor de IA procesa el texto generado<br>**And** redacta una historia de usuario en formato Gherkin<br>**And** la añade al backlog de la sesión actual | EP06                      |

#### 4.1.2.2.	Quality attribute Scenarios

En esta sección se definen los escenarios de atributos de calidad más críticos que guiarán las decisiones arquitectónicas de Reqs-AI. Se ha priorizado el Rendimiento (necesario para el procesamiento de audio en tiempo real), la Seguridad (aislamiento de datos), la Disponibilidad (para tolerar fallas externas) y la Modificabilidad (cambio de proveedores de IA).

| Atributo                            | Fuente                              | Estímulo                                                                                                | Artefacto                                | Entorno                                           | Respuesta                                                                                                                        | Medida                                                                               |
|:------------------------------------|:------------------------------------|:--------------------------------------------------------------------------------------------------------|:-----------------------------------------|:--------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------|
| **Performance (Streaming)**         | Líder Técnico / Analista Enterprise | El usuario habla durante la sesión de levantamiento de requerimientos.                                  | Motor de Transcripción (STT)             | Operación normal del sistema.                     | El sistema procesa el flujo de audio continuo y renderiza el texto en la interfaz del cliente.                                   | La transcripción parcial debe aparecer en pantalla en **menos de 2 segundos**.       |
| **Performance (Consolidación)**     | Líder Técnico / Analista Enterprise | El usuario detiene la grabación de la sesión para generar el Gherkin final.                             | Motor de Procesamiento e Integración LLM | Operación normal del sistema.                     | El sistema procesa la transcripción, consulta al LLM y retorna el documento estructurado.                                        | El documento final se entrega en **menos de 20 segundos** tras finalizar la sesión.  |
| **Security (Seguridad)**            | Usuario autenticado del Tenant A    | Intenta acceder a través de la API a un ID de proyecto o archivo de audio del Tenant B.                 | API Gateway / Base de Datos              | Operación normal del sistema.                     | El sistema intercepta la petición, verifica el contexto de seguridad (Row Level Security) y deniega el acceso.                   | El acceso se bloquea el **100% de las veces** y se registra el intento en auditoría. |
| **Availability (Disponibilidad)**   | Proveedor externo de IA (API)       | El servicio del LLM no responde (Timeout) o devuelve un error 500 durante una sesión en vivo.           | Motor de Integración de IA               | Entorno degradado (Falla de dependencia externa). | El sistema encola la transcripción en un Message Broker persistente (ej. RabbitMQ), notifica al usuario y reintenta la conexión. | Se recupera la operación con **0 bytes perdidos**.                                   |
| **Modifiability (Modificabilidad)** | Arquitecto de Software              | El negocio decide cambiar de proveedor de LLM (ej. de OpenAI a Anthropic) por un incremento de precios. | Módulo de Integración de IA              | Tiempo de diseño/desarrollo.                      | El desarrollador implementa un nuevo adaptador (Adapter) para la nueva API sin alterar la lógica de negocio core.                | El cambio se completa e integra en **menos de 16 horas de desarrollo**.              |

##### 4.1.2.3.	Constraints

Esta sección describe las restricciones innegociables impuestas por el modelo de negocio, las capacidades técnicas del equipo y la viabilidad del proyecto. Las principales restricciones incluyen la dependencia de APIs de LLMs externos y el uso del stack tecnológico (Java/Spring Boot y Angular/Vue.js). A continuación, se detallan como Technical Stories:

| Technical Story ID | Título                               | Descripción                                                                                                                                                            | Criterios de Aceptación                                                                                                                                                                              | Relacionado con (Epic ID) |
|:-------------------|:-------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------------------|
| **TS01**           | Stack Tecnológico Backend y Frontend | Como equipo de desarrollo, debemos utilizar Java (Spring Boot) para el backend y Angular o Vue.js para el frontend, debido a la experiencia técnica previa del equipo. | **Given** un nuevo componente a desarrollar<br>**When** el equipo inicie su construcción<br>**Then** el código debe estar escrito en Java 17+ usando Spring Boot o TypeScript usando Angular/Vue.js. | EP01, EP02                |
| **TS02**           | Uso de APIs de LLM externas          | Como Arquitecto de Software, debo integrar el sistema con APIs de modelos de terceros (ej. OpenAI, Anthropic), ya que no alojaremos modelos propios.                   | **Given** la necesidad de generar Gherkin<br>**When** el sistema realice una inferencia<br>**Then** la petición debe enrutarse hacia la API REST del proveedor seleccionado.                         | EP04                      |
| **TS03**           | Despliegue en Cloud Pública          | Como responsable de infraestructura, debo asegurar que los componentes sean desplegados en la nube (AWS, Azure o GCP), para evitar costos *on-premise*.                | **Given** la liberación de una nueva versión<br>**When** se ejecute el pipeline de despliegue<br>**Then** los artefactos deben aprovisionarse en la nube pública seleccionada.                       | Todas                     |

### 4.1.3.	Architectural Drivers Backlog

En esta sección se establece el conjunto de Architectural Drivers acordados por el equipo, resultado del proceso iterativo en nuestro Quality Attribute Workshop (QAW). El Architectural Drivers Backlog consolida los Functional Drivers seleccionados (provenientes de las historias de usuario críticas), los Quality Attribute Drivers seleccionados (Performance, Security, Availability, Modifiability) y todos los Constraints del negocio y la tecnología. Todos los Drivers se presentan a continuación, habiendo sido priorizados de forma descendente colocando primero aquellos que representan una Alta importancia para los Stakeholders y un Alto impacto en la Complejidad Técnica de la Arquitectura.

| Driver ID | Título de Driver                                          | Descripción                                                                                                                                                                            | Importancia para Stakeholders (High, Medium, Low) | Impacto en Architecture Technical Complexity (High, Medium, Low) |
|:----------|:----------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------|:-----------------------------------------------------------------|
| **AD-01** | Procesamiento de Audio en Tiempo Real e Integración LLM   | El sistema debe ingestar flujos continuos de audio (STT) en <2s y consolidar la inferencia del modelo LLM (Gherkin) en <20s, gestionando operaciones asíncronas durante las reuniones. | High                                              | High                                                             |
| **AD-02** | Arquitectura Multitenancy y Aislamiento de Datos          | El diseño debe garantizar la separación estricta de la información (Row Level Security) entre organizaciones corporativas, denegando el 100% de los accesos cruzados.                  | High                                              | High                                                             |
| **AD-03** | Tolerancia a Fallos en Servicios de IA Externos           | El sistema debe ser capaz de soportar caídas de las APIs de IA (Timeout/5xx) sin perder datos, encolando el procesamiento de las sesiones mediante Message Brokers.                    | High                                              | High                                                             |
| **AD-04** | Dependencia Estricta de APIs de LLM Externas              | Todo el procesamiento de inteligencia generativa dependerá de proveedores externos, lo que obliga al diseño a gestionar *rate limits* y costos operativos.                             | High                                              | High                                                             |
| **AD-05** | Ingesta de Contexto del Cliente y Motor RAG               | El sistema debe fragmentar (chunking) y vectorizar los PDFs de contexto de las empresas en <10s para proveer Retrieval-Augmented Generation en las inferencias.                        | High                                              | Medium                                                           |
| **AD-06** | Modificabilidad de Proveedores de Inteligencia Artificial | La arquitectura debe ser agnóstica al proveedor del LLM, permitiendo el reemplazo de la API de IA (ej. de OpenAI a Anthropic) en <16 horas de desarrollo mediante adaptadores.         | High                                              | Medium                                                           |
| **AD-07** | Despliegue en Cloud Pública                               | Todos los componentes deben ser contenerizados y desplegados en una nube pública como AWS o Azure para minimizar costos *on-premise* y permitir la escalabilidad.                      | Medium                                            | Medium                                                           |
| **AD-08** | Stack Tecnológico Base de Desarrollo                      | El backend debe desarrollarse en Java (Spring Boot) y el frontend en Angular/Vue.js debido al conocimiento técnico previo del equipo, limitando la adopción de otros lenguajes core.   | Medium                                            | Low                                                              |

### 4.1.4.	Architectural Design Decisions

En esta sección se detalla el proceso seguido durante las iteraciones (Stages) del *Quality Attribute Workshop* para definir la arquitectura de Reqs-AI. En cada etapa, el equipo enfrentó un conjunto específico de *Architectural Drivers* y evaluó distintos patrones o tácticas de diseño, sopesando sus pros y contras (Trade-offs) para asegurar que la solución cumpla con los atributos de calidad exigidos sin incurrir en *over-engineering* para la etapa actual de la startup.

**Iteración 1: Topología Base y Multitenancy (Drivers: AD-02, AD-07, AD-08)**
En esta primera iteración se evaluó la estructura general del backend y cómo gestionar el aislamiento de datos. Se descartó la arquitectura de Microservicios por su alta complejidad operativa, optando por un **Monolito Modular** en Spring Boot (AD-08). Para resolver la separación de datos entre empresas (AD-02), se debatió entre *Database-per-Tenant* y *Shared-Database*. Se eligió la base de datos compartida aplicando políticas estrictas de **Row Level Security (RLS)** a nivel de base de datos (ej. PostgreSQL), lo que garantiza el aislamiento del 100% de la información mientras se optimizan los costos de despliegue en la nube (AD-07).

**Iteración 2: Ingesta de Audio en Tiempo Real y Tolerancia a Fallos (Drivers: AD-01, AD-03)**
El reto principal fue cumplir con la latencia <2s para la transcripción en vivo (AD-01). Se evaluó REST Polling, Server-Sent Events (SSE) y WebSockets. Se eligió **WebSockets** por permitir una comunicación bidireccional continua (necesaria para mandar fragmentos de audio al server y recibir texto del STT simultáneamente). Para la tolerancia a fallos ante caídas de las APIs de IA (AD-03), se descartaron colas en memoria volátil y se adoptó el uso de un **Message Broker persistente (ej. RabbitMQ)** para garantizar 0 bytes perdidos en caso de falla externa.

**Iteración 3: Integración RAG y Modificabilidad de IA (Drivers: AD-04, AD-05, AD-06)**
Finalmente, el equipo abordó cómo evitar el acoplamiento con las APIs de IA de terceros y cómo lograr el RAG rápido (AD-05). Se descartó la Arquitectura en Capas tradicional a favor de una **Arquitectura Hexagonal (Ports and Adapters)**. Esto permite encapsular las reglas de negocio del *Prompt Engineering* en el dominio, dejando a OpenAI o Anthropic como simples "adaptadores", cumpliendo la meta de intercambiabilidad en <16h (AD-06). Para el almacenamiento del contexto del cliente, se eligió una **Base de Datos Vectorial** (ej. pgvector) superando las limitaciones de búsqueda semántica de las BD relacionales tradicionales.

**Candidate Pattern Evaluation Matrix**

La siguiente matriz resume la evaluación de los patrones candidatos considerados para los Drivers más críticos, justificando técnica y económicamente la decisión final del equipo.

| Driver ID | Título de Driver                          | Pattern 1                                                                                                                                                                                                                                       | Pattern 2                                                                                                                                                                                                                                                                                      | Pattern 3                                                                                                                                                                                                                |
|:----------|:------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **AD-01** | Procesamiento de Audio en Tiempo Real     | **REST Long Polling**<br>**Pro:** Fácil implementación inicial.<br>**Con:** Genera una alta latencia de red e interrumpe el flujo continuo del audio, incumpliendo la meta de <2s. *(Descartado)*                                               | **WebSockets** *(Elegido)*<br>**Pro:** Comunicación bidireccional y persistente, latencia casi nula para *streaming* de audio a texto.<br>**Con:** Añade complejidad al manejo de estados y balanceo de carga.                                                                                 | **Server-Sent Events (SSE)**<br>**Pro:** Excelente para enviar texto del servidor al cliente con soporte HTTP nativo.<br>**Con:** Es unidireccional. No sirve para que el cliente envíe su audio en vivo. *(Descartado)* |
| **AD-02** | Arquitectura Multitenancy y Aislamiento   | **Database per Tenant**<br>**Pro:** Aislamiento físico de datos impecable. Fácil restauración.<br>**Con:** Costos exorbitantes para una startup si la plataforma escala a miles de pequeñas empresas. *(Descartado)*                            | **Shared Database con Row Level Security** *(Elegido)*<br>**Pro:** Maximiza la economía de infraestructura. El motor (PostgreSQL) asegura que un inquilino jamás vea datos ajenos.<br>**Con:** Un error en la configuración de la política expone a todos.                                     | *(No se evaluó un 3er patrón)*                                                                                                                                                                                           |
| **AD-03** | Tolerancia a Fallos en Servicios Externos | **Cola en Memoria RAM local**<br>**Pro:** Muy rápido (latencia mínima), no requiere infraestructura extra.<br>**Con:** Si el contenedor/servidor se reinicia, todos los audios encolados se pierden para siempre. *(Descartado)*                | **Message Broker Persistente (ej. RabbitMQ / Kafka)** *(Elegido)*<br>**Pro:** Garantiza la durabilidad de los mensajes. Permite reintentar (Retry Policy) si la API de OpenAI cae.<br>**Con:** Requiere aprovisionar y mantener otro componente en el cloud.                                   | *(No se evaluó un 3er patrón)*                                                                                                                                                                                           |
| **AD-06** | Modificabilidad de Proveedores IA         | **Arquitectura Monolítica en Capas**<br>**Pro:** Modelo mental simple para el equipo (Controllers, Services, Repositories).<br>**Con:** Lógica de negocio altamente acoplada al SDK del proveedor de IA. Tomaría semanas migrar. *(Descartado)* | **Arquitectura Hexagonal (Ports & Adapters)** *(Elegido)*<br>**Pro:** El dominio ignora qué IA se usa. Cambiar a Anthropic solo exige escribir un nuevo Adapter para el Port correspondiente en <16h.<br>**Con:** Exige escribir más código *boilerplate* y dominar Inyección de Dependencias. | *(No se evaluó un 3er patrón)*                                                                                                                                                                                           |

### 4.1.5.	Quality Attribute Scenario Refinements



## 4.2.	Strategic-Level Domain-Driven Design

### 4.2.1.	EventStorming

Para establecer una base sólida en el diseño guiado por el dominio (DDD) y facilitar el descubrimiento de nuestros Bounded Contexts, el equipo de Kntro-Soft llevó a cabo una sesión de **Design-Level Event Storming** utilizando la herramienta colaborativa Miro. La sesión tuvo una duración aproximada de 2 horas. El objetivo principal fue transicionar del espacio del problema (entendido en los capítulos anteriores) al espacio de la solución, mapeando la línea de tiempo completa del negocio de Reqs-AI. Al utilizar un enfoque de nivel de diseño, pudimos no solo explorar los eventos que ocurren en el sistema (como la captura de audio o la generación de Gherkin), sino también agrupar lógicamente las reglas de negocio para descubrir los Agregados (Aggregates) estructurales del código antes de definir las fronteras de los subdominios.

La sesión se estructuró siguiendo una agenda iterativa para construir el modelo de forma progresiva:

1. **Domain Events (Eventos de Dominio):** Iniciamos la sesión identificando y ordenando cronológicamente en post-its naranjas los hechos relevantes que ya han ocurrido en el sistema (verbos en participio pasado). La línea de tiempo abarcó desde Organización Registrada y Suscripción Pagada, pasando por el núcleo operativo, hasta eventos de cierre como Historias Exportadas a Jira.

![Event Storming](assets/4.Strategic-Level-Product-Design/4.2.Strategic-Level-DDD/4.2.1.EventStorming/Domain-Events.jpg)

2. **Commands (Comandos):** A la izquierda de cada evento naranja, colocamos post-its azules que representan la acción o intención que provocó dicho evento. Por ejemplo, el comando Procesar Audio precede al evento Audio Transcrito, y el comando Generar Historia de usuario precede a Historia de Usuario Generada.

![Event Storming](assets/4.Strategic-Level-Product-Design/4.2.Strategic-Level-DDD/4.2.1.EventStorming/Commands.jpg)

5. **Actors and Policies (Actores y Políticas):** Identificamos qué o quién ejecuta los comandos. Utilizamos post-its amarillos pequeños para los actores humanos, destacando a nuestros roles principales: Líder Técnico, Analista Enterprise. Para las acciones automatizadas de nuestro SaaS, usamos post-its lilas (Políticas), redactadas como reacciones.

![Event Storming](assets/4.Strategic-Level-Product-Design/4.2.Strategic-Level-DDD/4.2.1.EventStorming/Actors-and-Policies.jpg)

5. **Blank stickies for Read models and UX mockups:** Para garantizar que el diseño de software contemple la experiencia del usuario, insertamos post-its verdes y blancos vacíos justo antes de las decisiones (comandos) de los actores, marcando los lugares donde el usuario necesita información antes de actuar.

![Event Storming](assets/4.Strategic-Level-Product-Design/4.2.Strategic-Level-DDD/4.2.1.EventStorming/Blank-stickies.jpg)

6. **Read models and UX Mockups:** Llenamos los post-its vacíos detallando la información necesaria (post-its verdes), como Estado de Transcripción en Vivo o Dashboard de Consumo de Tokens, y agregamos bocetos rápidos (wireframes en post-its blancos) para visualizar la interfaz de la consola de captura de Reqs-AI.

![Event Storming](assets/4.Strategic-Level-Product-Design/4.2.Strategic-Level-DDD/4.2.1.EventStorming/RM-and-UX.jpg)

7. **External systems (Sistemas Externos):** Mapeamos las dependencias críticas de Reqs-AI utilizando post-its rosados. Los colocamos entre los comandos y los eventos cuando la acción delegaba responsabilidad a un tercero. Fue fundamental para diagramar llamadas a la API de IA (generación de historias), a la pasarela de pago (facturación) y a la API de Jira (exportación).

![Event Storming](assets/4.Strategic-Level-Product-Design/4.2.Strategic-Level-DDD/4.2.1.EventStorming/External-services.jpg)

8. **Aggregates and Business Rules (Agregados y Reglas de Negocio):** Esta fue la etapa más crítica del diseño. Añadimos post-its amarillos rectangulares entre los comandos y los eventos para documentar las Reglas de Negocio (Business Rules) requeridas, definiendo precondiciones, postcondiciones e invariantes

![Event Storming](assets/4.Strategic-Level-Product-Design/4.2.Strategic-Level-DDD/4.2.1.EventStorming/Aggregates.jpg)

El resultado de la sesión de Design-Level Event Storming fue un mapa exhaustivo y altamente estructurado del dominio de Reqs-AI. Pasamos de una simple línea de tiempo a un conjunto de Agregados claramente definidos, destacando Aggregates críticos como Organization (para el multitenancy), Subscription, Session y UserStory.

### 4.2.2.	Candidate Context Discovery

A partir del dominio modelado en nuestra sesión de EventStorming, el equipo llevó a cabo un taller colaborativo de descubrimiento de contextos de aproximadamente 2 horas. El objetivo de esta fase fue trazar fronteras lógicas alrededor de los Agregados identificados previamente, con el fin de descomponer el sistema en módulos altamente cohesivos y con bajo acoplamiento (Bounded Contexts).

Para lograr esto, no nos basamos en corazonadas técnicas, sino que aplicamos rigurosamente tres heurísticas de Domain-Driven Design recomendadas por la industria (Alberto Brandolini y Nick Tune) sobre nuestro tablero de Miro. A continuación, se explica la aplicación progresiva de cada heurística y los resultados obtenidos:

1. Aplicación de "Start-with-value" (Identificando el Core Domain)
   Comenzamos el análisis preguntándonos: *¿Por qué partes del sistema pagarían nuestros clientes?* La propuesta de valor y ventaja competitiva de Reqs-AI radica exclusivamente en la transcripción en vivo y la inferencia de Inteligencia Artificial para generar historias de usuario estructuradas.
*   Al analizar la complejidad del tablero, notamos que agrupar esta "magia" en un solo contexto generaría un "monolito de contexto", ya que el flujo del audio y el procesamiento del texto en LLMs manejan ciclos de vida, lenguajes ubicuos y requisitos de rendimiento distintos.
*   **Decisión:** Dividimos el Core Domain en dos Bounded Contexts. Por un lado, el **Meeting Capture**, encargado del manejo de WebSockets y Speech-to-Text. Por el otro lado, **Requirement Generation** se encarga del manejo de los Prompts, el LLM y la gestión del formato Gherkin.

2. Aplicación de "Look-for-pivotal-events" (Fronteras por Cambio de Estado B2B)
   Posteriormente, buscamos en la línea de tiempo los Eventos Pivote que marcan "un antes y un después" crítico en la vida de un cliente dentro de la plataforma.
*   *Evento: "Account Validated" vs "Organization Created":* Observamos que la autenticación de un usuario es un problema genérico, mientras que gestionar a qué empresa pertenece y qué roles tiene es un problema organizativo B2B. **Decisión:** Extraímos el agregado *User* hacia un **IAM** independiente, y el agregado *Organization* hacia el **Workspace**.
*   *Evento: "Upgraded to Pro Plan":* Este evento cambia radicalmente los límites operativos del sistema (cuotas). Involucra pasarelas de pago y facturación. **Decisión:** Aislamos el agregado *Subscription* en el **Billing & Subscription**.

3. Aplicación de "Start-with-simple" (Fronteras por Secuencia de Soporte)
   Finalmente, agrupamos los agregados restantes evaluando su función en los pasos "antes" y "después" del proceso principal de captura de requisitos.
*   Antes de que la IA pueda operar, el Analista necesita crear un entorno y subir documentos PDF de contexto. Esto pertenece al agregado *Project*. **Decisión:** Agrupado en el **Project Configuration**.
*   Después de que las historias son aprobadas, deben enviarse a plataformas externas. Aquí decidimos aplicar el patrón *Anti-Corruption Layer (ACL)* aislando el agregado *ExternalConnection* para que los cambios en las APIs de terceros no contaminen el Core de Reqs-AI, aislandolo en **Integration Gateway**.


**Resumen de Bounded Contexts Descubiertos**
A través de este proceso analítico y evolutivo, el sistema quedó dividido arquitectónicamente en los siguientes 7 Candidate Bounded Contexts:

| Bounded Context | Tipo de Subdominio | Agregado(s) Principal(es) | Responsabilidad Principal |
| :--- | :--- | :--- | :--- |
| **1. Meeting Capture** | Core Domain | Session | Ingesta de audio en tiempo real (WebSockets), control de estado de la reunión (iniciar/pausar) e integración con el servicio de Speech-to-Text. |
| **2. Requirement Generation** | Core Domain | User Story | Inferencia mediante LLMs, fragmentación de contexto (RAG), generación y estructuración del formato Gherkin, y gestión de similitudes. |
| **3. IAM** | Generic Subdomain | User | Autenticación, registro, validación de correo y gestión de credenciales seguras. |
| **4. Workspace** | Generic Subdomain | Organization | Aislamiento Multitenant (Row Level Security), gestión de espacios de trabajo, invitación de miembros y roles corporativos. |
| **5. Billing & Subscription** | Generic Subdomain | Subscription | Integración con pasarelas de pago (ej. Stripe), upgrades/downgrades de planes y monitoreo de consumo de cuotas/tokens. |
| **6. Project Configuration** | Supporting Subdomain | Project | Estructura local de iniciativas del cliente, almacenamiento de parámetros técnicos y alojamiento de PDFs de glosario. |
| **7. Integration Gateway** | Supporting Subdomain | ExternalConnection | Capa Anticorrupción (ACL) para autorizar credenciales (OAuth) y exportar historias hacia herramientas externas como Jira. |

![CCD](assets/4.Strategic-Level-Product-Design/4.2.Strategic-Level-DDD/4.2.2.Candidate-Context-Discovery/Bounded-Contexts.jpg)

### 4.2.3.	Domain Message Flows Modeling

En esta sección, explicamos y evidenciamos el proceso seguido para visualizar cómo deben colaborar los Bounded Contexts para resolver el caso principal del negocio. Para ello, aplicamos una variante técnica de Domain Storytelling enfocada en el flujo de mensajes. 

Utilizamos una notación específica para modelar la interacción:
*   **Actor:** Persona interactuando con el sistema.
*   **Bounded Context:** Módulo lógico de nuestro dominio.
*   **System:** Sistemas o dependencias externas.
*   **Command:** Intención de hacer algo en color azul.
*   **Event:** Hecho que ya ocurrió en color naranja.
*   **Query:** Solicitud de información en color verde.
*   **Direction of message:** Flecha que indica el flujo del emisor al receptor.

A continuación, detallamos el paso a paso del diagrama elaborado para el flujo principal de Reqs-AI.

**Escenario Core: Captura de Sesión y Generación de Requerimientos**

Este flujo describe la colaboración desde que el usuario inicia la grabación hasta que se generan las historias de usuario estructuradas.

1. **Inicio de Sesión:** El Actor **Analyst** utiliza el System **Website** para enviar el Command **Start Session** al Bounded Context **Meeting Capture**, el cual confirma el inicio emitiendo el Event **Recording Started**.
2. **Procesamiento de Audio:** **Meeting Capture** delega la carga de trabajo enviando el Command **Divide Audio** al System **STT Service**, que retorna progresivamente el Event **Speech segments identified**.
3. **Recopilación de Contexto:** Al finalizar, se emite el Command **Send Transcript** hacia **Requirement Generation**. Este contexto necesita el glosario del cliente, por lo que envía un Query **Request Project Data** a **Project Configuration**, recibiendo como respuesta el Event **Project data sent**.
4. **Inferencia IA:** Con el texto y el contexto listos, **Requirement Generation** envía el Command **Generate User story** al System **LLM Service**. Una vez procesado, se consolida el flujo emitiendo el Event final **User story generated**.

![Scenario1](assets/4.Strategic-Level-Product-Design/4.2.Strategic-Level-DDD/4.2.3.Domain-Message-Flows-Modeling/Scenario1.jpg)

**Escenario: Creación de Organización y Suscripción**

Este flujo detalla el onboarding B2B, donde un líder técnico registra su empresa, realiza el pago de un plan Pro y el sistema prepara su entorno de trabajo inicial.

1. **Creación del Espacio:** El Actor **Tech Lead** usa el System **Website** para enviar el Command **Create organization** al Bounded Context **Workspace**, el cual notifica el éxito de la operación con el Event **Organization Created**.
2. **Gestión del Pago:** Para desbloquear los límites de IA, se emite el Command **Request Pro plan Upgrade** hacia **Billing & Subscription**. Este contexto se comunica con el System **Payment Gateway** mediante el Command **Start Payment** y espera el Event **Payment Validated**.
3. **Activación y Onboarding:** Tras el pago exitoso, se notifica a Workspace con el Event **Upgraded to Pro plan**. Como parte del onboarding automático, Workspace envía el Command **Generate Demonstration Project** a **Project Configuration**, finalizando el flujo con el Event **Demonstration Project Generated**.

![Scenario2](assets/4.Strategic-Level-Product-Design/4.2.Strategic-Level-DDD/4.2.3.Domain-Message-Flows-Modeling/Scenario2.jpg)

### 4.2.4.	Bounded Context Canvases

En esta sección el equipo diseña sus candidate bounded contexts, detallando los criterios de diseño. El equipo seleccionó cada bounded context, por orden de importancia, para elaborar su Bounded Context Canvas basándose en la plantilla de Domain Storytelling. 

A continuación, presentamos los lienzos diseñados para los siete Bounded Contexts de Reqs-AI.

**1. Meeting Capture**

Este contexto es responsable de la ingesta de audio en tiempo real y la transcripción mediante WebSockets.

![Canvas1](assets/4.Strategic-Level-Product-Design/4.2.Strategic-Level-DDD/4.2.4.Bounded-Context-Canvases/Meeting-Capture.jpg)

**2. Requirement Generation**

Este contexto es el motor de inteligencia artificial que estructura las transcripciones en formato Gherkin usando estrategias de prompting.

![Canvas2](assets/4.Strategic-Level-Product-Design/4.2.Strategic-Level-DDD/4.2.4.Bounded-Context-Canvases/Requirement-Generation.jpg)

**3. Identity and Access Management**

Este contexto asegura el acceso a la plataforma mediante autenticación y gestión de usuarios.

![Canvas3](assets/4.Strategic-Level-Product-Design/4.2.Strategic-Level-DDD/4.2.4.Bounded-Context-Canvases/IAM.jpg)

**4. Workspace**

Este contexto administra el aislamiento de datos multitenant, las organizaciones y los roles B2B.

![Canvas4](assets/4.Strategic-Level-Product-Design/4.2.Strategic-Level-DDD/4.2.4.Bounded-Context-Canvases/Workspace.jpg)

**5. Billing & Subscription**

Este contexto monitorea el uso de las cuotas de IA y gestiona los pagos recurrentes integrando pasarelas externas.

![Canvas5](assets/4.Strategic-Level-Product-Design/4.2.Strategic-Level-DDD/4.2.4.Bounded-Context-Canvases/Billing-and-subscription.jpg)

**6. Project Configuration**

Este contexto almacena la estructura de las iniciativas del cliente y sus glosarios para contextualizar la IA.

![Canvas6](assets/4.Strategic-Level-Product-Design/4.2.Strategic-Level-DDD/4.2.4.Bounded-Context-Canvases/Project-configuration.jpg)

**7. Integration Gateway**

Este contexto actúa como capa anticorrupción para exportar las historias de usuario hacia herramientas ágiles externas como Jira.

![Canvas7](assets/4.Strategic-Level-Product-Design/4.2.Strategic-Level-DDD/4.2.4.Bounded-Context-Canvases/Integration-Gateway.jpg)

### 4.2.5.	Context Mapping

En esta sección evidenciamos el proceso de elaboración de nuestro Context Map. Para llegar al diseño estructural definitivo de nuestros Bounded Contexts, el equipo evaluó el modelo sometiéndolo a un análisis crítico, respondiendo a las preguntas estratégicas de diseño sugeridas. Además, aplicamos rigurosamente los patrones de integración definidos por el repositorio oficial de Context Mapping de DDD Crew.

**Evaluación de Alternativas y Diseños Candidatos**

*   **¿Qué pasaría si aislamos los core capabilities y movemos los otros a un context aparte?**
    Inicialmente consideramos que la generación de la historia de usuario y su posterior exportación a Jira ocurrieran en el mismo módulo. Sin embargo, al aplicar esta pregunta, nos dimos cuenta de que exportar tickets es una capacidad de soporte. Aislamos el core de IA en **Requirement Generation** y movimos la integración externa al **Integration Gateway** para evitar que cambios en APIs de terceros contaminen nuestro motor de inferencia.
*   **¿Qué pasaría si duplicamos una funcionalidad para romper la dependencia?**
    Evaluamos la validación de cuotas. Si **Requirement Generation** tuviera que preguntar sincrónicamente a **Billing & Subscription** si un usuario tiene saldo de IA antes de cada inferencia, el sistema sería lento y frágil. Decidimos romper esta dependencia directa. **Billing & Subscription** emite eventos asíncronos cuando una cuota se acaba, y **Requirement Generation** duplica y almacena localmente un indicador de bloqueo, permitiendo inferencias rápidas sin consultas de red.
*   **¿Qué pasaría si tomamos un capability de estos contexts y lo usamos para formar un nuevo context?**
    Al analizar la autenticación de usuarios y la gestión de empresas, notamos que estaban fuertemente acopladas. Tomamos la capacidad de registro y login y formamos el contexto **IAM**, separándolo de **Workspace**. Esto nos permite evolucionar la seguridad genérica independientemente de la compleja lógica de roles corporativos multitenant.

**Patrones de Relación DDD Establecidos**

Tras este debate, definimos formalmente los patrones de integración estratégicos entre nuestros módulos y los sistemas de terceros. Las relaciones indican quién es el proveedor Upstream U y quién es el consumidor Downstream D.

1.  **Integration Gateway D hacia External PM Service (Jira) U**
    *   **Patrón:** Anti-Corruption Layer ACL
    *   **Justificación:** El Integration Gateway actúa como una barrera traductora. Consume nuestros eventos internos y los transforma a los complejos modelos de datos de Atlassian. Nuestro Core jamás se entera de los esquemas propietarios de Jira.
2.  **Requirement Generation D hacia External LLM Service U**
    *   **Patrón:** Anti-Corruption Layer ACL
    *   **Justificación:** Para evitar el vendor lock-in con OpenAI o Anthropic. Traducimos nuestros Prompts genéricos al esquema JSON específico de la API del proveedor, protegiendo nuestro modelo de dominio de cambios en la IA externa.
3.  **Meeting Capture D hacia External STT Service U**
    *   **Patrón:** Anti-Corruption Layer ACL
    *   **Justificación:** Al igual que con el LLM, el servicio de Speech-to-Text externo dicta un formato de streaming propio. El ACL aísla a Meeting Capture de la tecnología de transcripción subyacente.
4.  **Requirement Generation D hacia Project Configuration U**
    *   **Patrón:** Customer / Supplier
    *   **Justificación:** Requirement Generation Customer exige que el glosario se le entregue en un formato limpio de texto para el RAG. Project Configuration Supplier adapta su entrega de documentos PDFs para satisfacer esta necesidad.
5.  **Workspace D hacia IAM U y Workspace D hacia Billing & Subscription U**
    *   **Patrón:** Conformist CF
    *   **Justificación:** Workspace conforma ciegamente a los modelos de Identidad de IAM y a los eventos de Cuotas de Billing, sin exigirles cambios a esos dominios genéricos.
6.  **Workspace U hacia Requirement Generation D y Project Configuration D**
    *   **Patrones:** Open Host Service OHS y Published Language PL
    *   **Justificación:** Workspace emite eventos de dominio indicando si una organización tiene permisos o cuotas válidas. Contextos como Requirement Generation y Project Configuration consumen estos eventos estandarizados PL para saber si deben procesar o rechazar las peticiones de IA o creación de proyectos.
7.  **Comunicación Core Interna Event-Driven**
    *   **Patrones:** Open Host Service OHS y Published Language PL
    *   **Justificación:** Las conexiones asíncronas entre los contextos **Meeting Capture U -> Requirement Generation D** y **Requirement Generation U -> Integration Gateway D** se realizan publicando eventos en un broker, funcionando como un OHS.

**Diagrama de Context Map Final**

A continuación presentamos la visualización de las relaciones estructurales consolidadas tras aplicar los patrones descritos. Las líneas conectan los Bounded Contexts indicando los roles U y D y los patrones aplicados sobre ellas.

![Context Map](assets/4.Strategic-Level-Product-Design/4.2.Strategic-Level-DDD/4.2.5.Context-Mapping/ContextMapping.png)

## 4.3.	Software Architecture

### 4.3.1.	Software Architecture System Landscape Diagram

### 4.3.1.	Software Architecture Context Level Diagrams

### 4.3.2.	Software Architecture Container Level Diagrams

### 4.3.3.	Software Architecture Deployment Diagrams

# Capítulo V: Tactical-Level Software Design

## 5.X.	Bounded Context: <Bounded Context Name>

### 5.X.1.	Domain Layer

### 5.X.2.	Interface Layer

### 5.X.3.	Application Layer

### 5.X.4.	Infrastructure Layer

### 5.X.6.	Bounded Context Software Architecture Component Level Diagrams

### 5.X.7.	Bounded Context Software Architecture Code Level Diagrams

#### 5.X.7.1.	Bounded Context Domain Layer Class Diagrams

#### 5.X.7.2.	Bounded Context Database Design Diagram

# Capítulo VI: Solution UX Design

## 6.1.	Style Guidelines

### 6.1.1.	General Style Guidelines

### 6.1.2.	Web, Mobile & Devices Style Guidelines

## 6.2.	Information Architecture

### 6.2.2.	Labeling Systems

### 6.2.3.	Searching Systems

### 6.2.4.	SEO Tags and Meta Tags

### 6.2.5.	Navigation Systems

## 6.3.	Landing Page UI Design

### 6.3.1.	Landing Page Wireframe

### 6.3.2.	Landing Page Mock-up

## 6.4.	Applications UX/UI Design

### 6.4.1.	Applications Wireframes

### 6.4.2.	Applications Wireflow Diagrams

### 6.4.2.	Applications Mock-ups

### 6.4.3.	Applications User Flow Diagrams

## 6.5.	Applications Prototyping

# Capítulo VII: Product Implementation, Validation & Deployment

## 7.1.	Software Configuration Management

### 7.1.1.	Software Development Environment Configuration

### 7.1.2.	Source Code Management

### 7.1.3.	Source Code Style Guide & Conventions

### 7.1.4.	Software Deployment Configuration

## 7.2.	Solution Implementation

### 7.2.X.	Sprint n

#### 7.2.X.1.	Sprint Planning n

#### 7.2.X.2.	Sprint Backlog n

#### 7.2.X.3.	Development Evidence for Sprint Review

#### 7.2.X.4.	Testing Suite Evidence for Sprint Review

#### 7.2.X.5.	Execution Evidence for Sprint Review

#### 7.2.X.6.	Services Documentation Evidence for Sprint Review

#### 7.2.X.7.	Software Deployment Evidence for Sprint Review

#### 7.2.X.8.	Team Collaboration Insights during Sprint

## 7.3.	Validation Interviews

### 7.3.1.	Diseño de Entrevistas

### 7.3.2.	Registro de Entrevistas

### 7.3.3.	Evaluaciones según heurísticas

## 7.4.	Video About-the-Product

# Conclusiones

# Bibliografía

>Pulse of the Profession (2018) Success in Disruptiive Times. Project Management Institute. Recuperado el 15 de Abril de 2025, de https://www.pmi.org/learning/thought-leadership/pulse/pulse-of-the-profession-2018

>Jhonson J (2020) CHAOS Report: Beyond Infinity. Standish Group. Recuperado el 15 de Abril de 2025, de https://www.standishgroup.com/products/copy-of-chaos-report-beyond-infinity-digital-version


# Anexos

1. Relative Cost of Fixing Defects (IBM System Science Institute) ![IBM.png](assets/annexes/IBM.png)  