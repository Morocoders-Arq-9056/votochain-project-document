
<p align="center">
  <img src="./assets/upc-logo.png" alt="UPC Logo" width="200"/>
</p>

<p align="center">
  <strong>UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS</strong>
</p>

<p align="center">
  <strong>Ingeniería de Software</strong> <br>
  <strong> CURSO: 1ASI0728 – ARQUITECTURAS DE SOFTWARE EMERGENTES </strong> <br>
  <strong> NRC: 8056 </strong> <br>  
  <strong>PROFESOR(A): Valdivia Verde, Enrique Alejandro</strong> <br> <strong>
  INFORME DE TRABAJO FINAL </strong> <br>
  <strong> CICLO: 20260-20
  </strong>
  <br>
  <br>
  <strong> STARTUP: Morocoders  </strong> <br>
  <strong>
  PRODUCTO: VotoChain 
  </strong>
</p>

<br>

<p align="center"><strong>Relación de integrantes:</strong></p>

<table align="center">
  <thead>
    <tr>
      <th>Integrante</th>
      <th>Código</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Aliaga Aguirre, Ethan Matias</td>
      <td>U202318323</td>
    </tr>
    <tr>
      <td>Bueno Perales, Mathias Eduardo</td>
      <td>U202313433</td>
    </tr>
    <tr>
      <td>Paredes Santos, Fabrizio Alberto</td>
      <td>U202310914</td>
    </tr>
        <tr>
      <td>Rios Pacheco, Héctor Javier</td>
      <td>U20231c540</td>
    </tr>
    <tr>
      <td>Rodriguez Macedo, Sebastian</td>
      <td>U202310199</td>
    </tr>
  </tbody>
</table>

<br><br>

<p align="center">
  <strong>Setiembre, 2026</strong> <br>
  <strong>URL del proyecto:</strong>
  <a href="https://github.com/Morocoders-Arq-9056">
    https://github.com/Morocoders-Arq-9056
  </a>
</p>




## Registro de Versiones del Informe

| Versión | Fecha      | Autor                                              | Descripción de modificación                                                                                                                                                                |
| ------- | ---------- | -------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Vacio     | Vacio | Vacio                | Vacio                                                                                          |
| Vacio    | Vacio | Vacio                  | Vacio                                            |
| Vacio     | Vacio | Vacio                    | Vacio                                                           |



## Project Report Collaboration Insights

| URL del repositorio del reporte |
| :-----------------------------------: |
| [https://github.com/Morocoders-Arq-9056/votochain-project-document](https://github.com/Morocoders-Arq-9056/votochain-project-document) |


## Contenido

### Tabla de contenidos

- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process.](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements.](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions.](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo.](#13-segmentos-objetivo)

- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores.](#21-competidores)
    - [2.1.1. Análisis competitivo.](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores.](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas.](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas.](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas.](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas.](#223-análisis-de-entrevistas)
  - [2.3. Needfinding.](#23-needfinding)
    - [2.3.1. User Personas.](#231-user-personas)
    - [2.3.2. User Task Matrix.](#232-user-task-matrix)
    - [2.3.3. Empathy Mapping.](#233-empathy-mapping)
    - [2.3.4. As-is Scenario Mapping.](#234-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language.](#24-ubiquitous-language)

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping.](#31-to-be-scenario-mapping)
  - [3.2. User Stories.](#32-user-stories)
  - [3.3. Impact Mapping.](#33-impact-mapping)
  - [3.4. Product Backlog.](#34-product-backlog)

- [Capítulo IV: Strategic-Level Software Design.](#capítulo-iv-strategic-level-software-design)
  - [4.1. Strategic-Level Attribute-Driven Design.](#41-strategic-level-attribute-driven-design)
    - [4.1.1. Design Purpose.](#411-design-purpose)
    - [4.1.2. Attribute-Driven Design Inputs.](#412-attribute-driven-design-inputs)
      - [4.1.2.1. Primary Functionality (Primary User Stories).](#4121-primary-functionality-primary-user-stories)
      - [4.1.2.2. Quality attribute Scenarios.](#4122-quality-attribute-scenarios)
      - [4.1.2.3. Constraints.](#4123-constraints)
    - [4.1.3. Architectural Drivers Backlog.](#413-architectural-drivers-backlog)
    - [4.1.4. Architectural Design Decisions.](#414-architectural-design-decisions)
    - [4.1.5. Quality Attribute Scenario Refinements.](#415-quality-attribute-scenario-refinements)
  - [4.2. Strategic-Level Domain-Driven Design.](#42-strategic-level-domain-driven-design)
    - [4.2.1. EventStorming.](#421-eventstorming)
    - [4.2.2. Candidate Context Discovery.](#422-candidate-context-discovery)
    - [4.2.3. Domain Message Flows Modeling.](#423-domain-message-flows-modeling)
    - [4.2.4. Bounded Context Canvases.](#424-bounded-context-canvases)
    - [4.2.5. Context Mapping.](#425-context-mapping)
  - [4.3. Software Architecture.](#43-software-architecture)
    - [4.3.1. Software Architecture System Landscape Diagram.](#431-software-architecture-system-landscape-diagram)
    - [4.3.2. Software Architecture Context Level Diagrams.](#432-software-architecture-context-level-diagrams)
    - [4.3.3. Software Architecture Container Level Diagrams.](#433-software-architecture-container-level-diagrams)
    - [4.3.4. Software Architecture Deployment Diagrams.](#434-software-architecture-deployment-diagrams)

- [Capítulo V: Tactical-Level Software Design.](#capítulo-v-tactical-level-software-design)
  - [5.X. Bounded Context: &lt;Bounded Context Name&gt;](#5x-bounded-context-bounded-context-name)
    - [5.X.1. Domain Layer.](#5x1-domain-layer)
    - [5.X.2. Interface Layer.](#5x2-interface-layer)
    - [5.X.3. Application Layer.](#5x3-application-layer)
    - [5.X.4. Infrastructure Layer.](#5x4-infrastructure-layer)
    - [5.X.5. Bounded Context Software Architecture Component Level Diagrams.](#5x5-bounded-context-software-architecture-component-level-diagrams)
    - [5.X.6. Bounded Context Software Architecture Code Level Diagrams.](#5x6-bounded-context-software-architecture-code-level-diagrams)
      - [5.X.6.1. Bounded Context Domain Layer Class Diagrams.](#5x61-bounded-context-domain-layer-class-diagrams)
      - [5.X.6.2. Bounded Context Database Design Diagram.](#5x62-bounded-context-database-design-diagram)

- [Capítulo VI: Solution UX Design](#capítulo-vi-solution-ux-design)
  - [6.1. Style Guidelines.](#61-style-guidelines)
    - [6.1.1. General Style Guidelines.](#611-general-style-guidelines)
    - [6.1.2. Web, Mobile & Devices Style Guidelines.](#612-web-mobile--devices-style-guidelines)
  - [6.2. Information Architecture.](#62-information-architecture)
    - [6.2.1. Labeling Systems.](#621-labeling-systems)
    - [6.2.2. Searching Systems.](#622-searching-systems)
    - [6.2.3. SEO Tags and Meta Tags.](#623-seo-tags-and-meta-tags)
    - [6.2.4. Navigation Systems.](#624-navigation-systems)
  - [6.3. Landing Page UI Design.](#63-landing-page-ui-design)
    - [6.3.1. Landing Page Wireframe.](#631-landing-page-wireframe)
    - [6.3.2. Landing Page Mock-up.](#632-landing-page-mock-up)
  - [6.4. Applications UX/UI Design.](#64-applications-uxui-design)
    - [6.4.1. Applications Wireframes.](#641-applications-wireframes)
    - [6.4.2. Applications Wireflow Diagrams.](#642-applications-wireflow-diagrams)
    - [6.4.3. Applications Mock-ups.](#643-applications-mock-ups)
    - [6.4.4. Applications User Flow Diagrams.](#644-applications-user-flow-diagrams)
  - [6.5. Applications Prototyping.](#65-applications-prototyping)

- [Capítulo VII: Product Implementation, Validation & Deployment](#capítulo-vii-product-implementation-validation--deployment)
  - [7.1. Software Configuration Management.](#71-software-configuration-management)
    - [7.1.1. Software Development Environment Configuration.](#711-software-development-environment-configuration)
    - [7.1.2. Source Code Management.](#712-source-code-management)
    - [7.1.3. Source Code Style Guide & Conventions.](#713-source-code-style-guide--conventions)
    - [7.1.4. Software Deployment Configuration.](#714-software-deployment-configuration)
  - [7.2. Solution Implementation.](#72-solution-implementation)
    - [7.2.X. Sprint n](#72x-sprint-n)
      - [7.2.X.1. Sprint Planning n.](#72x1-sprint-planning-n)
      - [7.2.X.2. Sprint Backlog n.](#72x2-sprint-backlog-n)
      - [7.2.X.3. Development Evidence for Sprint Review.](#72x3-development-evidence-for-sprint-review)
      - [7.2.X.4. Testing Suite Evidence for Sprint Review.](#72x4-testing-suite-evidence-for-sprint-review)
      - [7.2.X.5. Execution Evidence for Sprint Review.](#72x5-execution-evidence-for-sprint-review)
      - [7.2.X.6. Services Documentation Evidence for Sprint Review.](#72x6-services-documentation-evidence-for-sprint-review)
      - [7.2.X.7. Software Deployment Evidence for Sprint Review.](#72x7-software-deployment-evidence-for-sprint-review)
      - [7.2.X.8. Team Collaboration Insights during Sprint.](#72x8-team-collaboration-insights-during-sprint)
  - [7.3. Validation Interviews.](#73-validation-interviews)
    - [7.3.1. Diseño de Entrevistas.](#731-diseño-de-entrevistas)
    - [7.3.2. Registro de Entrevistas.](#732-registro-de-entrevistas)
    - [7.3.3. Evaluaciones según heurísticas.](#733-evaluaciones-según-heurísticas)
  - [7.4. Video About-the-Product.](#74-video-about-the-product)



<br>


# **Student Outcome**

En Ingeniería de Software, un Student Outcome representa las capacidades, conocimientos y actitudes que un estudiante debe demostrar al graduarse, relacionadas con el diseño, desarrollo y gestión de sistemas de software de calidad. <br>

### Criterios especificos

- 7.c1. Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de ingeniería de software.

- 7.c2. Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de tecnologías de ingeniería de software. 

<br>


# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Morocoders es una startup peruana de transformación digital dedicada a construir herramientas de **gobernanza comunitaria verificable** para organizaciones que toman decisiones colectivas mediante votación en asamblea, principalmente juntas de propietarios de edificios multifamiliares y cooperativas de vivienda, pero cuyo modelo es extensible a otras formas de asociación (juntas vecinales, asociaciones civiles, colegios profesionales).

El producto insignia de la startup es **VotoChain**, una plataforma que combina verificación biométrica de identidad (reconocimiento facial con prueba de vida) con registro de votos en una red blockchain pública (Polygon), de modo que cada acuerdo de asamblea quede respaldado por un voto firmado individualmente y verificable de forma independiente por cualquier interesado, sin depender de actas físicas ni de la palabra de la directiva.

La propuesta de valor de la startup se resume en tres pilares:

- **Identidad verificada:** cada votante confirma su identidad mediante comparación facial contra su documento de identidad y una prueba de vida (liveness), evitando suplantación y voto múltiple.
- **Verificabilidad pública:** cada voto se firma individualmente (EIP-712) con una wallet derivada exclusivamente para ese usuario y se registra on-chain, de modo que el resultado de la asamblea puede auditarse por cualquier propietario sin depender de la directiva.
- **Accesibilidad:** el propietario vota desde su propio smartphone, sin necesidad de entender blockchain ni de custodiar claves privadas (modelo de wallet custodio, "Modelo B").

El modelo de negocio es de tipo **SaaS B2B2C**: la startup cobra una suscripción o tarifa por asamblea a administradoras de edificios y a juntas directivas (cliente pagador), mientras que el propietario final (usuario votante) accede sin costo directo.

### 1.1.2. Perfiles de integrantes del equipo

> Completar con los datos reales de cada integrante (nombre y apellidos, código de estudiante, carrera, foto, y un párrafo de resumen de conocimientos técnicos/habilidades que aporta al equipo), siguiendo la estructura pedida en el enunciado.

| Foto | Nombres y Apellidos | Código | Carrera | Resumen de habilidades |
|---|---|---|---|---|
| `[foto]` | `[Nombre Apellido 1]` | `[código]` | `[carrera]` | `[breve resumen de conocimientos técnicos/habilidades]` |
| `[foto]` | `[Nombre Apellido 2]` | `[código]` | `[carrera]` | `[breve resumen de conocimientos técnicos/habilidades]` |
| `[foto]` | `[Nombre Apellido 3]` | `[código]` | `[carrera]` | `[breve resumen de conocimientos técnicos/habilidades]` |
| `[foto]` | `[Nombre Apellido 4]` | `[código]` | `[carrera]` | `[breve resumen de conocimientos técnicos/habilidades]` |

---

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

**Antecedentes.** En Lima Metropolitana, la mayor parte de los edificios multifamiliares no cuenta con una junta de propietarios legalmente constituida e inscrita: se estima que alrededor del **95% de los edificios** no tiene su junta inscrita en Registros Públicos, en buena medida por el costo y la complejidad del trámite. Como consecuencia, cerca del **70% de los edificios multifamiliares** reporta conflictos de convivencia entre vecinos por falta de claridad en normas, deberes y derechos, y la morosidad llega a ser cercana al **40%** en los edificios donde la junta funciona de manera informal (Estudio Estrada, 2022; Alternativa SAC, 2020; Bienes Raíces, 2019). Incluso cuando la junta sí está constituida, el proceso de votación en asamblea (elección de directiva, aprobación de presupuesto y reglamento interno, autorización de obras, etc.) sigue apoyándose en mecanismos manuales: listas de asistencia en papel, actas físicas y conteo de votos a mano vigilado por la propia directiva.

**Problemática (5W + 2H).**

| Pregunta | Respuesta |
|---|---|
| **Who** (¿A quién afecta?) | Directivas y administradores de juntas de propietarios y cooperativas de vivienda; propietarios/socios que participan (o deberían participar) en las asambleas. |
| **What** (¿Cuál es el problema?) | No existe un mecanismo confiable, verificable y accesible para votar en asambleas: la identidad del votante no se valida de forma robusta, el conteo depende de la buena fe de quien lo realiza, y no queda una evidencia auditable e inmutable del resultado. |
| **Where** (¿Dónde ocurre?) | En asambleas presenciales y, cada vez más, virtuales/híbridas de juntas de propietarios y cooperativas en Lima Metropolitana. |
| **When** (¿Cuándo ocurre?) | En cada proceso de votación de acuerdos de asamblea, típicamente entre 1 y 4 veces al año (asambleas ordinarias y extraordinarias). |
| **Why** (¿Por qué ocurre?) | Los mecanismos actuales fueron diseñados para un contexto presencial y en papel; no incorporan verificación de identidad digital ni un registro criptográficamente verificable, lo que abre la puerta a suplantación, voto múltiple, y desconfianza sobre el conteo. |
| **How** (¿Cómo se propone resolverlo?) | Mediante una plataforma (VotoChain) que verifica biométricamente al votante antes de habilitarlo a votar, y que registra cada voto firmado individualmente en una blockchain pública, verificable con `ecrecover()` por cualquier interesado. |
| **How much** (¿Cuál es la magnitud/costo?) | El costo indirecto se refleja en impugnaciones de acuerdos, procesos de conciliación extrajudicial o judicial, morosidad asociada a la desconfianza en la gestión, y baja participación de propietarios que no logran asistir presencialmente y hoy no tienen una alternativa remota confiable para votar. |

Esta problemática constituye la base sobre la cual se desarrolla la solución de software descrita en este documento, y motiva directamente las decisiones de arquitectura ya tomadas por el equipo — en particular, la verificación biométrica pre-voto (OCR de DNI + liveness + comparación facial) y el modelo de wallet individual por usuario (Modelo B), que garantiza que cada voto pueda verificarse on-chain como perteneciente a una persona específica, y no a una única wallet que firme "por todos".

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

**Domain:** gobernanza comunitaria y votación digital verificable para organizaciones basadas en membresía (juntas de propietarios, cooperativas).

**Customer segments:** (a) directivas y administradores de juntas de propietarios/cooperativas; (b) propietarios/socios que participan en asambleas.

**Pain points:**
- Dificultad para verificar el cuórum y la identidad de quienes asisten y votan.
- Riesgo de suplantación o voto duplicado en asambleas numerosas.
- Actas y resultados que pueden impugnarse por falta de evidencia verificable.
- Propietarios que no pueden asistir presencialmente quedan fuera de la decisión.

**Gap:** no existe hoy una solución accesible para juntas de propietarios (no expertas en tecnología) que combine identidad verificada con un registro de votos públicamente auditable, sin exigirles administrar wallets ni claves privadas.

**Vision / strategy:** convertirse en el estándar de facto para votaciones verificables en organizaciones de membresía en Lima, comenzando por edificios multifamiliares medianos, y expandirse luego a cooperativas y asociaciones civiles.

**Initial segment:** juntas de propietarios de edificios multifamiliares de tamaño medio (aproximadamente 50 a 200 unidades) en Lima Metropolitana, gestionados por una administradora de edificios o por una directiva activa.

**Enunciado (Problem Statement):**

> Las juntas de propietarios y cooperativas de vivienda en Lima Metropolitana actualmente realizan sus votaciones de asamblea mediante actas físicas, listas de asistencia en papel y verificación de identidad manual a cargo de la propia directiva. Esto genera dificultad para comprobar el cuórum real, riesgo de suplantación de propietarios, impugnaciones de acuerdos por falta de evidencia verificable, y exclusión de propietarios que no pueden asistir presencialmente. Creemos que, si ofrecemos una plataforma de votación digital con verificación biométrica de identidad y registro de votos en una blockchain pública y verificable, lograremos incrementar la participación de los propietarios y reducir las impugnaciones de acuerdos de asamblea, dentro de los primeros meses de adopción por parte de una comunidad piloto.

#### 1.2.2.2. Lean UX Assumptions

- Los propietarios cuentan con un smartphone con cámara y conexión a internet suficiente para realizar la verificación biométrica.
- Los propietarios están dispuestos a compartir una foto de su documento de identidad y una selfie para verificar su identidad, siempre que se les explique el uso y no se almacenen las imágenes.
- Las directivas y administradoras de edificios están dispuestas a delegar (o co-gestionar) el proceso de votación a una plataforma externa a cambio de mayor transparencia y trazabilidad.
- El costo de los servicios de verificación biométrica de terceros (AWS Rekognition, Google Document AI) es asumible dentro de un modelo de suscripción o tarifa por asamblea.
- No existe una norma o reglamento interno que impida explícitamente el uso de un mecanismo de votación electrónico verificable en blockchain.
- Una directiva o propietario sin conocimientos técnicos de blockchain puede confiar en el sistema si se le explica en términos simples ("tu voto queda firmado y cualquiera puede comprobar que se contó correctamente"), sin necesidad de entender wallets ni claves privadas.
- La latencia y el costo de gas en una red como Polygon (relayer pagando el gas) son lo suficientemente bajos como para no afectar la experiencia de votación en tiempo real durante una asamblea.

#### 1.2.2.3. Lean UX Hypothesis Statements

**H1 — Confianza por verificación de identidad.** Creemos que, al ofrecer verificación biométrica de identidad antes de habilitar el voto, para los propietarios que participan en asambleas de su edificio, lograremos que perciban el resultado de la votación como más confiable frente al método anterior (lista de asistencia en papel). Lo sabremos porque, en la encuesta post-asamblea con la comunidad piloto, al menos el 80% de los propietarios encuestados calificará el proceso como "más confiable" o "mucho más confiable" que el método anterior.

**H2 — Reducción de impugnaciones por verificabilidad on-chain.** Creemos que, al registrar cada voto firmado individualmente en una blockchain pública y verificable, para las directivas de juntas de propietarios, lograremos reducir el número de impugnaciones o cuestionamientos sobre los resultados de asamblea. Lo sabremos porque, en la comunidad piloto, el número de impugnaciones o reclamos formales sobre un acuerdo se reducirá en al menos 50% respecto al histórico de asambleas previas gestionadas de forma manual.

**H3 — Aumento de participación por voto remoto.** Creemos que, al permitir votar remotamente desde un smartphone tras superar la verificación biométrica, para los propietarios que no pueden asistir presencialmente a la asamblea, lograremos aumentar la tasa de participación (cuórum efectivo). Lo sabremos porque la tasa de cuórum alcanzado en la comunidad piloto aumentará de un promedio histórico cercano al 45% a más de 65% en la primera asamblea realizada con VotoChain.

**H4 — Adopción por parte de directivas no técnicas.** Creemos que, al ocultar la complejidad de blockchain detrás de un flujo de "selfie + confirmación de voto" (modelo de wallet custodio), para directivas y administradores sin conocimientos técnicos, lograremos que adopten la plataforma sin capacitación extensa. Lo sabremos porque al menos el 70% de los administradores piloto completará la configuración de una asamblea sin soporte técnico adicional del equipo.

#### 1.2.2.4. Lean UX Canvas

| # | Elemento | Contenido |
|---|---|---|
| 1 | **Business Problem** | Las juntas de propietarios y cooperativas carecen de un mecanismo de votación confiable, verificable y accesible; esto genera desconfianza, impugnaciones y baja participación, y limita la disposición a pagar por soluciones de gestión digital para su comunidad. |
| 2 | **Business Outcomes** | Adopción de VotoChain por comunidades piloto en Lima; ingresos recurrentes por suscripción/tarifa por asamblea; reducción medible de impugnaciones y aumento de cuórum en las comunidades que usan la plataforma. |
| 3 | **Users** | (a) Directivas / administradores de juntas de propietarios y cooperativas; (b) propietarios / socios votantes. |
| 4 | **User Outcomes & Benefits** | Directivas: menos impugnaciones, menos trabajo manual de conteo y verificación, evidencia defendible ante conflictos. Propietarios: pueden votar de forma remota, confían en que su voto se contó correctamente, no necesitan entender blockchain. |
| 5 | **Solutions** | Verificación biométrica pre-voto (OCR de DNI + liveness + comparación facial); wallet individual derivada por usuario (Modelo B, HD/BIP-32); firma EIP-712 del voto server-side; envío de la transacción vía wallet relayer; verificación on-chain con `ecrecover()`. |
| 6 | **Hypotheses** | Ver H1–H4 en la sección 1.2.2.3. |
| 7 | **Lo más importante que aprender primero** | Si las directivas de juntas de propietarios están realmente dispuestas a delegar el control de la votación a una plataforma externa, y si los propietarios aceptan el paso de verificación biométrica sin fricción significativa. |
| 8 | **Mínimo esfuerzo para aprender lo siguiente más importante** | Entrevistas de Needfinding con directivas/administradores y propietarios de 2–3 edificios, seguidas de un prototipo navegable (sin blockchain real) que simule el flujo de selfie + confirmación de voto, para validar percepción de confianza y fricción de uso. |

---

## 1.3. Segmentos objetivo

### Segmento 1 — Directivas y administradores de juntas de propietarios / cooperativas

Este segmento agrupa a las personas que gestionan la comunidad y convocan/organizan las asambleas: presidentes y miembros de la directiva de la junta de propietarios, así como administradoras de edificios contratadas por la junta. Son quienes deciden adoptar (o no) una herramienta como VotoChain para sus asambleas.

- **Características demográficas:** adultos entre 30 y 65 años, en su mayoría propietarios de una unidad en el edificio o profesionales contratados como administradores externos; residen o gestionan comunidades en distritos de Lima Metropolitana con alta concentración de edificios multifamiliares (p. ej. Santiago de Surco, San Borja, Miraflores, San Isidro, Jesús María, Lince).
- **Contexto y magnitud:** el sector inmobiliario limeño construyó más de 128,000 departamentos entre 2010 y 2015, lo que —a un promedio estimado de 35 departamentos por edificio— representa un flujo cercano a 700 nuevas juntas de propietarios por año que eventualmente deben constituirse y empezar a votar acuerdos. Sin embargo, se estima que alrededor del 95% de los edificios en Lima Metropolitana no tiene su junta de propietarios formalmente inscrita, lo que constituye tanto una barrera (menor formalidad, menor disposición a pagar) como una oportunidad (mercado de comunidades que buscan formalizarse y necesitan herramientas de gestión confiables).
- **Necesidades clave:** reducir conflictos e impugnaciones derivados de procesos de votación poco transparentes; simplificar la organización de asambleas (convocatoria, verificación de cuórum, conteo); contar con evidencia defendible ante SUNARP, municipalidades o procesos de conciliación.

### Segmento 2 — Propietarios / socios votantes

Este segmento agrupa a los propietarios de unidades inmobiliarias (o socios, en el caso de cooperativas) que tienen derecho a voto en la asamblea, pero que no necesariamente participan activamente en la gestión de la comunidad.

- **Características demográficas:** adultos entre 25 y 70 años, propietarios de un departamento en un edificio multifamiliar o socios de una cooperativa de vivienda en Lima Metropolitana; nivel de alfabetización digital heterogéneo (desde jóvenes profesionales muy familiarizados con apps hasta propietarios de mayor edad con menor experiencia tecnológica), lo que exige que el flujo de verificación biométrica y voto sea extremadamente simple.
- **Contexto y magnitud:** en cerca del 70% de los edificios multifamiliares de Lima se reportan conflictos entre vecinos asociados a falta de claridad sobre normas y deberes, y la morosidad llega a cerca del 40% en comunidades con juntas informales — ambos síntomas de una gobernanza percibida como poco transparente, que VotoChain busca atender desde el proceso de votación mismo.
- **Necesidades clave:** poder votar sin necesariamente asistir presencialmente a la asamblea; confiar en que su voto se registró y contó correctamente; no exponerse a que alguien vote en su nombre (suplantación); no tener que entender ni gestionar tecnología blockchain o wallets.

# **Capítulo II: Requirements Elicitation & Analysis**


## **2.1. Competidores**

### **2.1.1. Análisis competitivo.**

### **2.1.2. Estrategias y tácticas frente a competidores.**

## **2.2. Entrevistas**

### **2.2.1. Diseño de entrevistas.**

### **2.2.2. Registro de entrevistas.**

### **2.2.3. Análisis de entrevistas.**

## **2.3. Needfinding**

### **2.3.1. User Personas.**

### **2.3.2. User Task Matrix.**

### **2.3.3. Empathy Mapping.**

### **2.3.4. As-is Scenario Mapping.**

## **2.4. Ubiquitous Language.**


# **Capítulo III: Requirements Specification**

## **3.1. To-Be Scenario Mapping.**

## **3.2. User Stories.**

## **3.3. Impact Mapping.**

## **3.4. Product Backlog.**

# **Capítulo IV: Strategic-Level Software Design.**

## **4.1. Strategic-Level Attribute-Driven Design.**

### **4.1.1. Design Purpose.**

### **4.1.2. Attribute-Driven Design Inputs.**

#### **4.1.2.1. Primary Functionality (Primary User Stories).**

#### **4.1.2.2. Quality attribute Scenarios.**

#### **4.1.2.3. Constraints.**

### **4.1.3. Architectural Drivers Backlog.**

### **4.1.4. Architectural Design Decisions.**

### **4.1.5. Quality Attribute Scenario Refinements.**

## **4.2. Strategic-Level Domain-Driven Design.**

### **4.2.1. EventStorming.**

### **4.2.2. Candidate Context Discovery.**

### **4.2.3. Domain Message Flows Modeling.**

### **4.2.4. Bounded Context Canvases.**

### **4.2.5. Context Mapping.**

## **4.3. Software Architecture.**

### **4.3.1. Software Architecture System Landscape Diagram.**

### **4.3.2. Software Architecture Context Level Diagrams.**

### **4.3.3. Software Architecture Container Level Diagrams.**

### **4.3.4. Software Architecture Deployment Diagrams.**

# **Capítulo V: Tactical-Level Software Design.**

## **5.X. Bounded Context: <Bounded Context Name>**

### **5.X.1. Domain Layer.**

### **5.X.2. Interface Layer.**

### **5.X.3. Application Layer.**

### **5.X.4. Infrastructure Layer.**

### **5.X.5. Bounded Context Software Architecture Component Level Diagrams.**

### **5.X.6. Bounded Context Software Architecture Code Level Diagrams.**

#### **5.X.6.1. Bounded Context Domain Layer Class Diagrams.**

#### **5.X.6.2. Bounded Context Database Design Diagram.**

# **Capítulo VI: Solution UX Design**

## **6.1. Style Guidelines.**

### **6.1.1. General Style Guidelines.**

### **6.1.2. Web, Mobile & Devices Style Guidelines.**

## **6.2. Information Architecture.**

### **6.2.1. Labeling Systems.**

### **6.2.2. Searching Systems.**

### **6.2.3. SEO Tags and Meta Tags.**

### **6.2.4. Navigation Systems.**

## **6.3. Landing Page UI Design.**

### **6.3.1. Landing Page Wireframe.**

### **6.3.2. Landing Page Mock-up.**

## **6.4. Applications UX/UI Design.**

### **6.4.1. Applications Wireframes.**

### **6.4.2. Applications Wireflow Diagrams.**

### **6.4.3. Applications Mock-ups.**

### **6.4.4. Applications User Flow Diagrams.**

### **6.5. Applications Prototyping.**

# **Capítulo VII: Product Implementation, Validation & Deployment**

## **7.1. Software Configuration Management.**

### **7.1.1. Software Development Environment Configuration.**

### **7.1.2. Source Code Management.**

### **7.1.3. Source Code Style Guide & Conventions.**

### **7.1.4. Software Deployment Configuration.**

## **7.2. Solution Implementation.**

### **7.2.X. Sprint n**

#### **7.2.X.1. Sprint Planning n.**

#### **7.2.X.2. Sprint Backlog n.**

#### **7.2.X.3. Development Evidence for Sprint Review.**

#### **7.2.X.4. Testing Suite Evidence for Sprint Review.**

#### **7.2.X.5. Execution Evidence for Sprint Review.**

#### **7.2.X.6. Services Documentation Evidence for Sprint Review.**

#### **7.2.X.7. Software Deployment Evidence for Sprint Review.**

#### **7.2.X.8. Team Collaboration Insights during Sprint.**

## **7.3. Validation Interviews.**

### **7.3.1. Diseño de Entrevistas.**

### **7.3.2. Registro de Entrevistas.**

### **7.3.3. Evaluaciones según heurísticas.**

## **7.4. Video About-the-Product.**


