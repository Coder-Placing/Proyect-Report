
<div align="center">

<p align="center">
  <img src="Assets/UPC_logo.png" alt="logo" width="200"/>
</p>

<h3 align="center">
Universidad Peruana de Ciencias Aplicadas
</h3>

<h3 align="center">
Ingeniería de Software  
<br><br>
Periodo: 202610 
<br><br>
1ACC0238 - Aplicaciones para Dispositivos Móviles
<br><br>
NRC: 3667  
<br><br>
Docente: Eduardo Martin Reyes Rodriguez  
<br><br>
<strong>Informe de TB1</strong>  
<br><br>
Startup: Coder-Placing
<br><br>
Producto: SpacePulse
<br><br>
<br><br>
<strong>Integrantes</strong>  
<br><br>
Aliaga Urbina, Wilder Gonzalo (U202222001)
<br><br>
Via Luna, Bruce (U202313403)
<br><br>
 (U) 
<br><br>
 (U) 
<br><br>
 (U)
<br><br>
2026
</h3>
</div>



## Registro de Versiones del Informe


| Versión | Fecha      | Autor    | Descripción de modificación |              
| ------- |------------| -------- | ----------------------------|
| 1.0  | 09/04/2026 | Bruce Via Luna | Creacion del documento |
| 1.01 | 20/04/2026 | Bruce Via      | Creacion de Epicas y correccion del documento|
| 1.02 | 22/04/2026 |                |         |
| 1.03 | 22/04/2026 |                |             |
| 1.04 | 22/04/2026 |                |    |


## Project Report Collaboration Insights

**AUTHORS:**

- Bruce Via Luna

|  URL del repositorio del reporte  |
| :-----------------------------------: |
| [https://github.com/Coder-Placing/Proyect-Report](https://github.com/Coder-Placing/Proyect-Report) |

**TB1:**

## Contenido

- [Student Outcome](#student-outcome)

- [Objetivos SMART](#objetivos-smart)

- [Capítulo I: Presentación](#capítulo-i:-presentacion)
    - [1.1. Startup Profile](#11-startup-profile)
        - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
        - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2. Solution Profile](#12-solution-profile)
        - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
        - [1.2.2. Lean UX Process](#122-lean-ux-process)
            - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
            - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
            - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
            - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
    - [1.3. Segmentos Objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation-analysis)
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
        - [2.3.5. As-Is Scenario Mapping](#235-as-is-scenario-mapping)
    - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements specification](#capítulo-iii-requirements-specification)
    - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
    - [3.2. User Stories](#32-user-stories)
    - [3.3. Impact Mapping](#33-impact-mapping)
    - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
    - [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
        - [4.1.1. EventStorming](#411-eventstorming)
            - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
            - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
            - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
        - [4.1.2. Context Mapping](#412-context-mapping)
        - [4.1.3. Software Architecture](#413-software-architecture)
            - [4.1.3.1. Software Architecture Context Level Diagrams](#4131-software-architecture-context-level-diagrams)
            - [4.1.3.2. Software Architecture Container Level Diagrams](#4132-software-architecture-container-level-diagrams)
            - [4.1.3.3. Software Architecture Deployment Level Diagrams](#4133-software-architecture-deployment-level-diagrams)
    - [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
        - [4.2.1. Bounded Context: NOMBRE](#421-bounded-context-registro-y-autenticación-de-usuario)
            - [4.2.1.1. Domain Layer](#4211-domain-layer)
            - [4.2.1.2. Interface Layer](#4212-interface-layer)
            - [4.2.1.3. Application Layer](#4213-application-layer)
            - [4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)
            - [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
            - [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
                - [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
                - [4.2.1.6.2. Bounded Context Database Design Diagrams](#42162-bounded-context-database-design-diagrams)

- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

## Student Outcome
El curso contribuye al cumplimiento del Student Outcome ABET:
**ABET - EAC - Student Outcome 7 Criterio**: La capacidad de adquirir y aplicar nuevos conocimientos según sea
necesario, utilizando estrategias deaprendizaje apropiadas.
En elsiguiente cuadro se describe las accionesrealizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado los criterios especificos.

| Criterio específico | Acciones realizadas  | Conclusiones |
|--------|----------|------|
| Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software. | - **Aliaga Urbina, Wilder Gonzalo – TB1**<br>  |         |
| Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software. | - **Aliaga Urbina, Wilder Gonzalo – TB1**<br>|         |
<hr>

## Objetivos SMART

<h3> Wilder Gonzalo Aliaga Urbina </h3>




## Capítulo I: Presentación
### 1.1. Startup Profile


#### 1.1.1. Descripción de la Startup


**Objetivo:**

**Misión**

**Visión**

#### 1.1.2. Perfiles de integrantes del equipo
|  Foto   | Miembros del equipo        | Código de Estudiante |   Descripción          |
|---------| -------------------------- |----------------------| ---------------------- |
| ![Imagen1](Assets/TB1/eric.png) |Wilder Gonzalo Aliaga Urbina |U202222001    |     |
| ![Imagen2]()                    |Via Luna Bruce|U202313403|  |
| ![Imagen3]()                    |   |                      |  |
| ![Imagen4]()                    |   |                      |  |
| ![Imagen5]()                    |   |                      |  |


### 1.2. Solution Profile



#### 1.2.1. Antecedentes y problemática

#### 1.2.2. Lean UX Process


##### 1.2.2.1. Lean UX Problem Statements

##### 1.2.2.2. Lean UX Assumptions

##### 1.2.2.3. Lean UX Hypothesis Statements

##### 1.2.2.4. Lean UX Canvas


### 1.3. Segmentos Objetivos


## Capítulo II: Presentación


### 2.1. Competidores


#### 2.1.1. Análisis competitivo

#### 2.1.2. Estrategias y tácticas frente a competidores


### 2.2. Entrevistas


#### 2.2.1. Diseño de entrevistas

#### 2.2.2. Registro de entrevistas

#### 2.2.3. Análisis de entrevistas


### 2.3. Needfinding


#### 2.3.1. User Personas

User Persona 1:

![User_Persona_1](Assets/User_Persona_1.png)

User Persona 2:

![User_Persona_2](Assets/User_Persona_2.png)

#### 2.3.2. User Task Matrix

#### 2.3.3. User Journey Map

User Journey Map Segmento objetivo 1:

![User_Journey_Map_1](Assets/Journey_map_1.png)

User Journey Map Segmento objetivo 2:

![User_Journey_Map_2](Assets/Journey_map_2.png)

#### 2.3.4. Empathy Mapping

Empathy Map Segmento Objetivo 1:

![Empathy_Map_1](Assets/Empathy_map_1.png)

Empathy Map Segmento Objetivo 2:

![Empathy_Map_2](Assets/Empathy_map_2.png)

#### 2.3.5. As-Is Scenario Mapping


### 2.4. Ubiquitous Language


## Capitulo III: Requirements specification

### 3.1. To-Be Scenario Mapping

### 3.2. User Stories

En esta seccion detallaremos la existencia, escenarios y diferentes historias de usuarios o 
User Stories que usaremos a lo largo del proyecto, para mejor orden se iniciara con la creacion de 
Epicas para poder agrupar a todas las historias de usuario en categorias para su posterior
cumplimiento

|Epic ID | Titulo | Descripción|
|--------|--------|------------|
|EP01    | Landing Page | Como usuario de SpacePulse quiero navegar por una Landing Page con una experiencia de usuario fluida y agil, para verificar y experimentar sus funcionalidades y el acceso a la informacion util del producto.
|EP02    |Gestion de usuarios|Como usuario de SpacePulse, quiero crear un perfil, modificarlo, abrir y cerrar sension en cualquier dispositivo y recuperar la contraseña de mi cuenta para crear mi identidad dentro de la aplicacion y acceder a sus funcionalidades.
|EP03    |Gestion de espacios| Como usuario de SpacePulse, quier crear, eliminar y editar espacios para tener un control de su remodelacion en tiempo real y actualizado usando las funcionalidades de SpacePulse.|
|EP04    |Funcionalidades Avanzadas de Cliente|Como usuario de SpacePulse, quiero acceder a funcionalidades apegadas a mi rol como usuario para saber que herramientas poseo para la remodelacion de mi espacio|
|EP05    |Monitoreo de Remodelaciones| Como usuario de SpacePulse, quiero analizar y evaluar el proceso de mi espacio para su control durante el proceso de remodelacion|
|EP06    |Funcionalidades Avanzadas| Como usuario de SpacePulse, quiero ver las funcionalidades y acceder a ellas en todo momento para mejorar el flujo de la aplicacion y optimizarlo|
|EP07    |Seguridad de informacion| Como administrador de SpacePulse, quiero gestionar y cuidar el perfil de mis usuario, para asegurar su estadia dentro de la aplicacion y no sientan un riesgo de sus datos al navegar dentro de ella.|
|EP08    | Accesibilidad|Como usuario de SpacePulse, quiero funcionalidades que ayuden a que la aplicacion sea mas accesible en aspectos como color, configuracion y optimizacion para no tener problemas durante su uso.

Una vez concluidas las epicas, ahora podemos proceder a encapsular las multiples historias de usuario que poseemos para definir los requerimientos de nuestra aplicacion y saber como desarrollarla correctamente

| Epic / Story ID | Titulo | Descripción | Criterios de Aceptación | Epic ID | 
|-----------------|--------|-------------|-------------------------|--------------------------|
|Landing Page / US01|Visualizacion de Landing Page|Como usuario de SpacePulse, quiero acceder a una Landing Page informativa para ver los beneficios y lo que ofrece la aplicacion | Dado que el usuario accede a la web pública<br> Cuando abre la sección de servicios <br> Entonces el sistema muestra los servicios que ofrece. |EP01|
|Landing Page / US02| Acceso a la aplicacion | Como usuario de SpacePulse, quiero acceder a la aplicacion desde la Landing Page para acceder a la aplicacion desde otros medios|  Dado que el usuario accede a la Landing Page <br> Cuando acceda al boton "Ingresar" <br> Entonces sera redirigido a la aplicacion | EP01|
|Gestion de Usuarios / US03| Registro de Usuarios | Como usuario de SpacePulse, quiero crear una cuenta para acceder a la aplicacion|Dado que el usuario accede a la aplicacion <br> Cuando llene el formulario con su informacion personal <br> Y los datos sean permitidos <br> Entonces la aplicacion creara una cuenta para el usuario | EP02|
| Gestion de Usuarios / US04 | Inicio de Sesion | Como usuario de SpacePulse, quiero iniciar sesion con mis datos personales para acceder a la aplicacion con una cuenta personalizada para mi | Escenario 1: <br> Dado que el usuario esta en la ventana de "Iniciar Sesion" <br> Cuando llene el formulario de inicio de sesion <br> Y los datos sean correctos <br> Entonces acceder con el inicio de sesion <br> <br> Escenario 2: <br> Dado que el usuario esta en la ventana de "Iniciar Sesion" <br> Cuando llene el formulario de inicio de sesion <br> Y los datos sean incorrectos <br> Entonces no podra acceder al inicio de sesion | EP02|
Gestion de Usuarios / US05 | Recuperar Contraseña | Como usuario de SpacePulse, quiero recuperar la contraseña de mi cuenta, para recuperar el acceso a mi cuenta en caso se me olvide | Dado el usuario no recuerde la contraseña de su cuenta <br> Cuando el usuario presione el boton de "Recuperar contraseña" <br> Entonces el sistema iniciaria el proceso para recuperar o reemplazar su anterior contraseña | EP02|
|Gestion de Usuarios/ US06| Editar Perfil | Como usuario de SpacePulse, quiero editar mi perfil en ciertos aspectos para mayor personalizacion de mi cuenta |Escenario 1: <br> Dado el usuario esta en al seccion "Mi Perfil" <br> Cuando el usuario presione el boton "Editar Perfil" <br> Entonces el sistema iniciara el formulario de datos editables del perfil de usuario <br><br> Escenario 2: Edicion de Perfil <br> Dado que el usuario esta en el formulario de editar perfil <br> Cuando el usuario modifique los datos que desee <br> Entonces el sistema lo actualizara y su perfil mostrara los nuevos datos | EP02|
| Gestion de Usuarios / US07 | Seleccion de Roles | Como usuario de Space Pulse, quiero seleccionar el rol que sere para acceder a las funcionalidades de dicho rol para evitar problemas a futuro | Dado que el usuario esta creando su cuenta <br> Cuando vea la opcion de seleccionar rol <br> Entonces podra seleccionar si es dueño o remodelador | EP02|
|US08 | Visualización de servicios de remodelación | | | |
|US09 | Recibir notificaciones IoT | | | |
|US10 | Reportes de remodelación | | | |
|US11 | Personalización de perfil | | | |
|US12 | Seguridad de datos | | | |
|US13 | Historial de proyectos | | | |
|US14 | Dejar opiniones | | | |
|US15 | Alertas de seguridad | | | |
|US16 | Seguimiento en tiempo real | | | |
|US17 | Comparación de presupuestos | | | |
|US18 | Gestión de pagos | | | |
|US19 | Recordatorios de pago | | | |
|US20 | Registro de incidencias | | | |
|US21 | Confirmación de entrega de materiales | | | |
|US22 | Descarga de reportes | | | |
|US23 | Panel de control de dispositivos IoT | | | |
|US24 | Sugerencias de mejoras | | | |
|US25 | Calificación del servicio | | | |
|US26 | Control de acceso de usuarios (RBAC) | | | |
|US27 | Recuperación de contraseña | | | |
|US28 | Configuración de notificaciones | | | |
|US29 | Multilenguaje | | | |
|US30 | Filtrado de proyectos | | | |
|US31 | Gestión de documentos | | | |
|US32 | Reportes personalizados | | | |
|US33 | Vista de progreso en gráfico | | | |
|US34 | Carga de fotos de avance | | | |
|US35 | Chat en tiempo real | | | |
|US36 | Integración con facturación electrónica | | | |
|US37 | Roles de usuario | | | |
|US38 | API para integración externa | | | |
|US39 | Auditoría de cambios | | | |
|US40 | Modo oscuro | | | |
|US41 | Autenticación de usuario | | | |
|US42 | Creación de Espacio | | | |
|US43 | Consulta de Espacios | | | |
|US44 | Actualización de Espacio | | | |
|US45 | Eliminación de Espacio | | | |
|US46 | Creación de Pago | | | |
|US48 | Consulta de Pagos | | | |
|US49 | Flujo de Iniciación y Confirmación | | | |
|US50 | Flujo de Reversión (Cancelación y Reembolso) | | | |
|US51 | Registro de Proyecto de Monitoreo | | | |
|US52 | Consulta de Proyecto por ID | | | |
|US53 | Ingesta de Lecturas de Sensores | | | |
|US54 | Creación de Tarea de Monitoreo | | | |
|US55 | Consulta de Tarea por ID | | | |
|US56 | Registro de Dispositivo IoT | | | |
|US57 | Consulta de Dispositivos por Proyecto | | | |
|US58 | Consulta de Incidentes por Proyecto | | | |
|US59 | Reconocimiento (Acknowledge) de Incidente | | | |
|US60 | Consulta de Notificaciones por Proyecto | | | |

### 3.3. Impact Mapping

Impact Mapping Segmento Objetivo 1:

![Impact_Mapping_1](Assets/Impact_map_1.png)

Impact Mapping Segmento Objetivo 2:

![Impact_Mapping_2](Assets/Impact_map_2.png)

### 3.4. Product Backlog

## Capitulo IV: Solution Software Design


## 4.1. Strategic-Level Domain-Driven Design
Esta sección describe cómo el diseño orientado al dominio (DDD) guio la arquitectura estratégica de nuestra solución. Nos enfocamos en segmentar el sistema en contextos delimitados (Bounded Contexts) para mejorar la organización del desarrollo. Mediante el uso de Event Storming y Bounded Context Canvases, definimos con precisión el alcance y las interacciones de cada componente. Como resultado, logramos una estructura de software totalmente alineada con las necesidades reales del negocio.

### 4.1.1. EventStorming
El proceso de modelado comenzó con una fase de descubrimiento deliberado mediante una dinámica de lluvia de ideas. Durante esta actividad, se utilizaron notas adhesivas de color naranja para representar los Domain Events (eventos de dominio). Estos elementos son fundamentales, ya que capturan hechos significativos que ocurren dentro del sistema y reflejan cambios de estado críticos para el negocio. Esta identificación visual permitió al equipo mapear la cronología de los procesos e identificar los puntos de interacción más relevantes de la aplicación.
<img width="717" height="875" alt="image" src="https://github.com/user-attachments/assets/f60d67f0-8666-41f3-94b0-7a99eb3042c9" />

### 4.1.1.1. Candidate Context Discovery
Esta sección describe la dinámica de los procesos de negocio mediante el flujo de eventos. Al identificar los pivotal events, logramos detectar los puntos de cambio donde una responsabilidad termina y otra comienza, lo que resulta fundamental para la creación de los Bounded Contexts. Esta delimitación estratégica permite estructurar el dominio de forma coherente, facilitando el desarrollo modular y permitiendo que el software escale de manera ordenada según las necesidades de la organización.

<img width="967" height="171" alt="image" src="https://github.com/user-attachments/assets/5e0e8f3c-e23d-469e-a6d4-37b258531a65" />
<img width="585" height="295" alt="image" src="https://github.com/user-attachments/assets/0d9c5bc5-931e-41d2-b00a-c366db0469e8" />
<img width="1060" height="115" alt="image" src="https://github.com/user-attachments/assets/eec10c38-8661-42e0-9cc9-c96e5b556ec0" />
<img width="828" height="304" alt="image" src="https://github.com/user-attachments/assets/52f8e616-d8b0-4175-8f30-c708a81dba4d" />
<img width="853" height="430" alt="image" src="https://github.com/user-attachments/assets/36faae71-9321-41f2-8c0a-d6b3ba6f7512" />

### 4.1.2 Context Mapping
El Context Mapping de SpacePulse permite representar la organización general del dominio del sistema y la manera en que sus distintas partes se relacionan entre sí. Esta vista ayuda a delimitar responsabilidades, reducir el acoplamiento y entender con mayor claridad cómo se distribuyen los procesos principales de la solución.
Se identificaron los siguientes bounded context en el sistema:

**Identity & Access Management**

Se encarga del registro, autenticación y control de acceso de los usuarios. Su función principal es permitir que el usuario cree su cuenta, inicie sesión y acceda al sistema de forma segura según su rol. A partir de este contexto se habilita el ingreso a las demás funcionalidades de la plataforma. 

**Space Management**

Se encarga de la gestión de espacios dentro de la plataforma. Aquí se registran, publican, actualizan y administran los espacios que formarán parte del flujo principal del negocio. También concentra la lógica base sobre la cual se conectan los procesos de remodelación, monitoreo y contratación de servicios. 

**Payment Management**

Administra los pagos, cobros, suscripciones y comprobantes relacionados con los servicios contratados en SpacePulse. Su función es controlar la parte financiera del sistema y dar trazabilidad a las operaciones económicas asociadas a remodelaciones o servicios del espacio. 

**IoT Monitoring & Notifications**

Se encarga del monitoreo de lecturas, detección de incidentes y envío de notificaciones. Su objetivo es registrar eventos relacionados con el espacio o con el proceso de remodelación, identificar anomalías y comunicar alertas a los usuarios cuando sea necesario. 

**Reports & Advanced Features**

Se encarga de la generación de reportes, métricas e información analítica. Su función es tomar datos producidos por otros contextos y transformarlos en información útil para seguimiento, supervisión y apoyo a la toma de decisiones.

|Destino |Origen |Tipo de relación |Comentario |
|-------|----------|-------------|------------|
|Space Management |Identity & Access Management |Shared Kernel |La gestión de espacios requiere que el usuario esté autenticado y tenga un rol válido dentro del sistema. Por ello, ambos contextos comparten una base mínima de identidad sin mezclar sus responsabilidades. |
|Payment Management |Space Management |Customer/Supplier |Payment Management necesita información generada en Space Management, como espacios, servicios contratados o remodelaciones asociadas, para procesar los cobros y pagos del sistema. |
|IoT Monitoring & Notifications |Space Management |Customer/Supplier |El monitoreo y las notificaciones dependen de un espacio previamente registrado en la plataforma. Por eso, Space Management provee la base del espacio y IoT Monitoring & Notifications usa esa información para gestionar lecturas, alertas e incidentes. |
|Reports & Advanced Features |Payment Management |Conformist |Reports & Advanced Features consume la información financiera generada por Payment Management para construir reportes e indicadores sin modificar el modelo original. |
|Reports & Advanced Features |IoT Monitoring & Notifications |Conformist |Reports & Advanced Features también consume la información producida por IoT Monitoring & Notifications, como alertas, incidentes o eventos, para generar análisis y vistas de seguimiento. |

![Context_Mapping](Assets/Context_Mapping.png)

### 4.1.3 Software Architecture
La arquitectura de software de SpacePulse ha sido planteada para soportar los procesos principales del negocio de forma organizada y desacoplada. La solución parte de una aplicación móvil desde la cual los usuarios interactúan con la plataforma para gestionar espacios, contratar servicios de remodelación, monitorear el avance del proyecto, recibir alertas y consultar reportes. Para responder a estas necesidades, el sistema se apoya en un backend centralizado que concentra la lógica del negocio y coordina la interacción con los distintos módulos funcionales, como autenticación, gestión de espacios, pagos, monitoreo IoT, notificaciones y reportes. Además, la arquitectura contempla la integración con servicios externos necesarios para el procesamiento de pagos, la generación de comprobantes electrónicos, el envío de correos y la recepción de lecturas o eventos provenientes del entorno monitoreado. Esta organización permite que la solución mantenga una estructura clara, facilite la evolución de sus funcionalidades y soporte de manera consistente el flujo principal de SpacePulse.

#### 4.1.3.1. Software Architecture Context Level Diagram
El diagrama de contexto de SpacePulse muestra la solución como un sistema central que se relaciona directamente con sus actores principales y con los servicios externos requeridos para su funcionamiento. En este caso, los usuarios que interactúan con la plataforma son el Owner, quien administra espacios, contrata remodelaciones, realiza pagos y supervisa el progreso, y el Remodeler, quien actualiza avances, registra procesos y da seguimiento al trabajo realizado. A su vez, el sistema se conecta con un Payment Gateway para procesar transacciones, con un E-Invoicing Service para generar comprobantes electrónicos, con un Email Service para enviar correos de verificación y notificaciones, y con IoT Devices / IoT Broker para recibir lecturas, eventos e información operativa del espacio monitoreado. De esta manera, el diagrama permite identificar de forma clara el alcance de SpacePulse dentro del ecosistema general de la solución y su relación con los elementos externos que complementan el servicio.

![Software_Architecture_Context_Level_Diagram](Assets/Software_Architecture_Context_Level_Diagram.png)

#### 4.1.3.2 Software Architecture Container Level Diagrams
En el nivel de contenedores se desglosan los principales componentes internos de SpacePulse, mostrando cómo se organiza el sistema a nivel tecnológico. Aquí se incluyen la Mobile App, la Landing Page, el API Gateway como punto central de comunicación, los distintos servicios internos que representan la lógica principal de la plataforma y una base de datos relacional común. Además, se consideran las integraciones con servicios externos para pagos, facturación electrónica, envío de correos y recepción de datos de monitoreo IoT. Cada uno de estos contenedores cumple una función específica y se relaciona con los demás para permitir el funcionamiento integrado de la solución. integraciones externas. 

![Software_Architecture_Container_Level_Diagrams](Assets/Software_Architecture_Container_Level_Diagrams.png)

#### 4.1.3.3. Software Architecture Deployment Diagrams.
En el diagrama de despliegue se representa cómo los principales componentes de SpacePulse se distribuyen en el entorno de producción. En este caso, la Mobile App se ejecuta en los dispositivos móviles de los usuarios, mientras que la Landing Page se publica en un servicio de hosting estático. Por otro lado, el API Gateway se aloja en una plataforma cloud como punto central de acceso al backend, y la Relational Database se ubica en un servidor administrado que permite el almacenamiento persistente de la información. Esta organización permite una arquitectura más clara y escalable, separando la capa de acceso, el procesamiento principal del sistema y el almacenamiento de datos.

![Software_Architecture_Deployment_Diagrams](Assets/Software_Architecture_Deployment_Diagrams.png)


## 4.2.4. Bounded Context: Space Management

### 4.2.4.1. Domain Layer

La Domain Layer es el núcleo que gestiona las reglas de negocio relacionadas con la administración de espacios dentro de la plataforma SpacePulse. En este contexto, entidades como Space y LinkedIoTDevice, junto con objetos de valor y servicios de dominio, permiten registrar espacios, actualizar su información, controlar su disponibilidad y vincular dispositivos IoT para el monitoreo posterior.

Objetivo:

La capa de dominio tiene como objetivo representar los elementos fundamentales para la gestión de espacios, cubriendo desde la publicación de un nuevo espacio hasta la actualización de sus detalles y el control de su disponibilidad dentro de la plataforma.

## 1. Aggregate: Space

**Descripción:**

El agregado Space actúa como la raíz del modelo y encapsula la información principal de un espacio registrado en SpacePulse. Representa el ambiente físico que será publicado, editado, pausado o monitoreado dentro del sistema.

### Atributos

| Atributo           | Tipo   | Descripción                                                                 |
|--------------------|--------|-----------------------------------------------------------------------------|
| id                 | Guid   | Identificador único del espacio.                            |
| ownerId          | Guid   | Identificador del usuario propietario del espacio.               |
| name             | String  | Nombre del espacio registrado.                    |
| description             | String | Descripción general del espacio.                    |
| location  | SpaceLocation | Objeto de valor que representa la ubicación del espacio.           |
| dimensions          | SpaceDimensions   | Objeto de valor que representa las dimensiones físicas del espacio.                                   |
| status  | String | Estado actual del espacio: publicado, pausado o no disponible.                 |
| createdAt          | DateTime   | Fecha de creación del registro del espacio.                                  |
### Métodos

- `publish()` : Cambia el estado del espacio a publicado cuando contiene la información necesaria.
- `updateDetails(name, description, location)`: Actualiza los datos principales del espacio.
- `pauseAvailability()`: Pausa temporalmente la disponibilidad del espacio.
- `linkIoTDevice(device)` : Asocia un dispositivo IoT al espacio para permitir su monitoreo.

---

## 2. Value Object: SpaceLocation

**Descripción:**

El objeto de valor SpaceLocation representa la ubicación del espacio registrado. Permite mantener agrupados los datos relacionados con dirección, distrito y ciudad.

### Atributos

| Atributo | Tipo    | Descripción                     |
|----------|--------|---------------------------------|
| address   | String | Dirección principal del espacio.     |
| district | String  | Distrito donde se ubica el espacio. |
| city | String  | Ciudad correspondiente al espacio. |

### Métodos

- `getFullAddress()` : Retorna la dirección completa del espacio en formato legible.
- `isValid()` : Valida que la ubicación cuente con los datos mínimos requeridos.

---

## 3. Value Object: SpaceDimensions

**Descripción:**

El objeto de valor SpaceDimensions representa las medidas físicas del espacio. Esta información permite describir mejor el ambiente y apoyar decisiones relacionadas con remodelación o monitoreo.

### Atributos

| Atributo      | Tipo   | Descripción                                                   |
|---------------|--------|---------------------------------------------------------------|
| width            | Decimal   | Ancho del espacio.                          |
| length     | Decimal   | Largo del espacio.         |
| area | Decimal | Área total calculada del espacio.              |

### Métodos

- `calculateArea()` : Calcula el área total del espacio a partir del ancho y largo.
- `isValid()` : Verifica que las dimensiones ingresadas sean mayores a cero.

---

## 4. Entity: LinkedIoTDevice

**Descripción:**

La entidad LinkedIoTDevice representa un dispositivo IoT vinculado a un espacio específico. Su función es registrar qué dispositivo está asociado al espacio para permitir el monitoreo operativo desde otro bounded context.

### Atributos

| Atributo      | Tipo   | Descripción                                                   |
|---------------|--------|---------------------------------------------------------------|
| id            | Guid   | Identificador único del vínculo.                          |
| spaceId     | Guid   | Identificador del espacio asociado.         |
| deviceId | Guid | Identificador del dispositivo IoT vinculado.              |
| deviceType            | String   | Tipo de dispositivo o sensor asociado.                          |
| status     | String   | Estado del dispositivo vinculado.         |
| linkedAt | DateTime | Fecha en que el dispositivo fue asociado al espacio.              |

### Métodos

- `activate()` : Activa el dispositivo vinculado al espacio.
- `deactivate()` : Desactiva el dispositivo vinculado.
- `isLinkedTo(spaceId)` : Verifica si el dispositivo pertenece al espacio indicado.
---

## 5.Domain Service: SpaceCommandService

**Descripción:**

El servicio SpaceCommandService encapsula reglas de negocio relacionadas con la publicación, actualización y disponibilidad de espacios dentro de SpacePulse.

### Métodos

- `publishSpace(Space space)` : Valida y publica un nuevo espacio en la plataforma.
- `updateSpaceDetails(Space space)` : Coordina la actualización de información del espacio.
- `pauseSpaceAvailability(Guid spaceId)` : Cambia el estado del espacio a pausado.
- `linkDeviceToSpace(Guid spaceId, Guid deviceId)` : Valida y vincula un dispositivo IoT al espacio.
---

## 6. Repository: ISpaceRepository

**Descripción:**

El ISpaceRepository es una abstracción para la persistencia de espacios dentro de la base de datos, permitiendo realizar operaciones de consulta y guardado de manera ordenada.

### Métodos

- `save(Space space)` : Guarda un nuevo espacio o actualiza uno existente.
- `findById(Guid id)` : Recupera un espacio por su identificador único.
- `findByOwnerId(Guid ownerId)` : Recupera los espacios asociados a un propietario.
- `delete(Guid id)` : Elimina o desactiva un espacio registrado.

En la Domain Layer de SpacePulse, específicamente dentro del bounded context Space Management, se define la lógica principal para registrar, publicar, actualizar y pausar espacios dentro de la plataforma. La clase Space actúa como agregado raíz, mientras que SpaceLocation, SpaceDimensions y LinkedIoTDevice complementan la información necesaria para representar el espacio y su relación con el monitoreo IoT. Finalmente, las operaciones principales se coordinan mediante el servicio SpaceCommandService y la persistencia se abstrae a través de ISpaceRepository.

## 4.2.4.2. Interface Layer

a Interface Layer es la capa que expone los endpoints de la aplicación, permitiendo la interacción entre los usuarios y la gestión de espacios dentro de SpacePulse. Los controladores son responsables de recibir las peticiones, validarlas y coordinar con los servicios correspondientes para registrar espacios, actualizar su información, controlar su disponibilidad y vincular dispositivos IoT.

En esta capa no se implementan reglas de negocio, sino que se coordina la comunicación entre las solicitudes de los usuarios y la lógica del dominio.

---

## Controlador: SpacesController

**Descripción:**

El SpacesController maneja los endpoints relacionados con la creación, consulta, actualización y control de disponibilidad de los espacios registrados en la plataforma.

### Endpoints

| Método | Ruta                                   | Descripción |
|--------|----------------------------------------|-------------|
| POST   | /api/v1/spaces                       | Maneja la solicitud para publicar un nuevo espacio. Recibe un objeto CreateSpaceResource, lo convierte en un comando y llama al servicio de aplicación. |
| GET    | /api/v1/spaces/{spaceId}           | Recupera la información detallada de un espacio específico mediante su identificador. |
| GET    | /api/v1/owners/{ownerId}/spaces  | Obtiene la lista de espacios registrados por un propietario específico. |
| PUT    | /api/v1/spaces/{spaceId}           | Permite actualizar los datos principales de un espacio, como nombre, descripción, ubicación o dimensiones. |
| PATCH    | /api/v1/spaces/{spaceId}/pause  | Cambia el estado del espacio para pausar temporalmente su disponibilidad. |

### Dependencias

- **ISpaceCommandService**: Servicio que maneja los comandos de creación, actualización y pausa de espacios.
- **ISpaceQueryService**: Servicio encargado de gestionar las consultas de espacios registrados.
- **CreateSpaceCommandFromResourceAssembler**: Utilidad para convertir el recurso de creación en un comando procesable.
- **UpdateSpaceCommandFromResourceAssembler**: Utilidad para transformar el recurso de actualización en un comando.
- **SpaceResourceFromEntityAssembler**: Utilidad para convertir la entidad de dominio Space en un recurso de respuesta para la API.

---

## Controlador: SpaceDevicesController

**Descripción:**

El SpaceDevicesController maneja los endpoints relacionados con la vinculación y consulta de dispositivos IoT asociados a un espacio. Este controlador permite conectar la gestión del espacio con el posterior monitoreo IoT.

### Endpoints

| Método | Ruta                                   | Descripción |
|--------|----------------------------------------|-------------|
| POST    | /api/v1/spaces/{spaceId}/devices           | Permite vincular un dispositivo IoT a un espacio específico para habilitar su monitoreo. |
| GET    | /api/v1/spaces/{spaceId}/devices        | Recupera los dispositivos IoT asociados a un espacio registrado. |
| PATCH    | /api/v1/spaces/{spaceId}/devices/{deviceId}/deactivate        | Desactiva la vinculación de un dispositivo IoT cuando ya no será utilizado para el monitoreo del espacio. |


### Dependencias

- **ISpaceDeviceCommandService**: Servicio encargado de procesar comandos relacionados con la vinculación de dispositivos IoT.
- **ISpaceDeviceQueryService**: Servicio encargado de consultar dispositivos vinculados a espacios.
- **LinkIoTDeviceCommandFromResourceAssembler**: Utilidad para convertir el recurso de vinculación en un comando procesable.
- **LinkedIoTDeviceResourceFromEntityAssembler**: Utilidad para transformar la entidad LinkedIoTDevice en un recurso de respuesta.

---

## Flujo de Trabajo

### Gestión de Espacios
Los usuarios propietarios pueden registrar un nuevo espacio a través de la API, lo que invoca los servicios de comando para validar la información, crear la entidad correspondiente y persistirla en el sistema.

### Actualización y Disponibilidad
Una vez creado el espacio, el propietario puede modificar sus datos principales o pausar temporalmente su disponibilidad. Estas operaciones son recibidas por el controlador y delegadas a la capa de aplicación para mantener la consistencia del dominio.

### Vinculación de Dispositivos IoT
Cuando un espacio requiere monitoreo, el sistema permite vincular dispositivos IoT mediante endpoints específicos. Esta información queda asociada al espacio y sirve como base para que el contexto de IoT Monitoring and Notifications pueda procesar lecturas posteriormente.

---

En esta capa de SpacePulse, los controladores se encargan de recibir las solicitudes HTTP, dirigirlas a los servicios apropiados y devolver una respuesta adecuada.

Estos controladores no contienen reglas de negocio, sino que delegan el procesamiento a la capa de dominio o a los servicios de aplicación, actuando como una interfaz entre los usuarios propietarios y la gestión interna de espacios.

Los controladores presentados permiten gestionar la publicación, actualización, disponibilidad y vinculación de dispositivos IoT dentro del contexto Space Management.

### 4.2.4.3. Application Layer

Esta capa actúa como un orquestador. Recibe comandos y consultas desde la capa de interfaz y coordina la ejecución de la lógica asociada a la gestión de espacios dentro de SpacePulse. Es el intermediario que traduce las solicitudes de los usuarios en acciones del dominio, asegurando que la creación, actualización, consulta y control de disponibilidad de los espacios se apliquen correctamente.

### Commands & Queries Handlers

| **Nombre** | **Descripción**  |   Resumen de Lógica  |
| ------------ | --------- | --------- | 
| CreateSpaceCommandHandler        | Gestiona la creación de un nuevo espacio dentro del sistema.    | Valida los datos básicos del espacio, instancia el agregado Space y lo persiste mediante el repositorio correspondiente. | 
| UpdateSpaceDetailsCommandHandler        | Procesa la actualización de la información principal de un espacio.  | Recupera el espacio por su identificador, actualiza sus atributos permitidos y guarda los cambios en el repositorio. | 
| PauseSpaceAvailabilityCommandHandler        | Orquesta el cambio de estado de disponibilidad de un espacio.  | Busca el espacio, ejecuta la operación de pausa de disponibilidad en el dominio y persiste el nuevo estado. | 
| LinkIoTDeviceCommandHandler        | Gestiona la vinculación de un dispositivo IoT a un espacio.     | Valida que el espacio exista, registra la relación con el dispositivo IoT y actualiza la información persistente. | 
| GetSpaceByIdQueryHandler        | Recupera la información detallada de un espacio específico.   | Consulta el repositorio utilizando el identificador único y devuelve el DTO correspondiente. | 
| GetSpacesByOwnerIdQueryHandler        | Obtiene la lista de espacios asociados a un propietario.   | Consulta los espacios registrados por un usuario y devuelve una colección resumida para visualización. | 


### Internal DTOs (Data Transfer Objects)

| **Nombre** | **Descripción**  |  
| ------------ | --------- | 
| SpaceDto        | Contiene la información principal del espacio, incluyendo identificador, nombre, tipo, estado y datos generales para uso interno.    | 
| SpaceAvailabilityDto        | Encapsula la información relacionada con la disponibilidad del espacio, incluyendo su estado actual y observaciones asociadas.   | 
| LinkedIoTDeviceDto        | Representa la información básica de un dispositivo IoT vinculado a un espacio para su consulta interna.     | 
| SpaceSummaryDto        | Provee una vista simplificada de los espacios registrados por un propietario, útil para listados y paneles de consulta.    | 

En la Application Layer de SpacePulse, los handlers orquestan los flujos de gestión de espacios, asegurando que cada operación sea validada y ejecutada correctamente antes de persistirse. La lógica se coordina a través de servicios de aplicación y repositorios, permitiendo mantener separado el dominio de la infraestructura y de la presentación.

### 4.2.4.4. Infrastructure Layer

En la Infrastructure Layer de SpacePulse, específicamente para el contexto de Space Management, se implementan los detalles técnicos necesarios para la persistencia de espacios, dispositivos vinculados y reseñas asociadas. Esta capa permite almacenar la información del espacio, configurar su mapeo con la base de datos y dar soporte técnico a las operaciones de creación, actualización, consulta y pausa de disponibilidad.

Esta capa se encarga de:

- La gestión de datos mediante Entity Framework Core (EFC).
- La configuración del mapeo de espacios y dispositivos vinculados con la base de datos MySQL.
- La implementación de servicios técnicos de apoyo para la administración de disponibilidad e información del espacio.

Estos componentes permiten que la lógica de gestión de espacios se ejecute sobre una infraestructura organizada y mantenible.

### Persistence (Repositories Implementation)

| **Nombre** | **Descripción**  |   Tecnologías / Herramientas  |
| ------------ | --------- | --------- | 
| SpaceRepository        | Implementación concreta de ISpaceRepository que utiliza EFC para gestionar el almacenamiento, consulta y actualización de espacios registrados.     | Entity Framework Core, LINQ | 
| LinkedIoTDeviceRepository        | Implementación de ILinkedIoTDeviceRepository encargada de persistir los dispositivos IoT vinculados a un espacio.    | Entity Framework Core | 
| ReviewRepository        | Implementación de IReviewRepository encargada de almacenar y consultar reseñas asociadas a espacios publicados.    | Entity Framework Core | 
| SpaceConfiguration        | Define el mapeo entre la entidad Space y la tabla spaces, incluyendo restricciones, tipos de datos y relaciones principales.  | Fluent API (EFC) | 
| LinkedIoTDeviceConfiguration        | Configura el esquema de base de datos para los dispositivos vinculados a espacios.   | Fluent API (EFC) | 
| ReviewConfiguration        | Configura el mapeo de reseñas asociadas a espacios, incluyendo la relación con el usuario y el espacio.     | Fluent API (EFC) | 

### Technical Services Implementation

| **Nombre** | **Descripción**  |   Resumen de Implementación  |
| ------------ | --------- | --------- | 
| SpaceAvailabilityService      | Servicio técnico de apoyo para actualizar el estado de disponibilidad de un espacio.     | Gestiona cambios de estado como publicado, pausado o no disponible, persistiendo la actualización mediante el repositorio. | 
| SpaceDeviceLinkingService        | Servicio encargado de apoyar la vinculación técnica entre espacios y dispositivos IoT.   |Registra la asociación entre un espacio y un dispositivo, dejando la información lista para que sea utilizada por el contexto de monitoreo IoT. | 

En la Infrastructure Layer de SpacePulse, dentro del bounded context Space Management, se implementan los repositorios y configuraciones necesarias para almacenar espacios, dispositivos vinculados y reseñas. Asimismo, los servicios técnicos permiten apoyar la disponibilidad del espacio y su relación con dispositivos IoT, manteniendo separados los detalles de infraestructura de la lógica principal del dominio.

### 4.2.4.5. Bounded Context Software Architecture Component Level Diagrams

![SpaceManagementComponents_Software_Architecture_Component_Level_Diagram](Assets/SpaceManagementComponents_Software_Architecture_Component_Level_Diagram.png)

### 4.2.4.6. Bounded Context Software Architecture Code Level Diagrams

### 4.2.4.6.1. Bounded Context Domain Layer Class Diagrams

![SpaceManagementComponents_Domain_Layer_Class_Diagram](Assets/SpaceManagementComponents_Domain_Layer_Class_Diagram.png)

### 4.2.4.6.2. Bounded Context Database Design Diagrams

![SpaceManagementComponents_Database_Design_Diagram](Assets/SpaceManagementComponents_Database_Design_Diagram.png)

## 4.2.5. Bounded Context: IoT Monitoring and Notifications

### 4.2.5.1 Domain Layer

La capa de dominio de IoT Monitoring and Notifications encapsula la lógica principal para la supervisión de dispositivos IoT, recepción de lecturas, validación de datos y generación de alertas cuando se detectan valores fuera de rango.

### Aggregates

| **Atributo** | **Nombre**  | **Descripción**                                       |
| ------------ | --------- | ----------------------------------------------------- |
| Aggregate Root         | IoTDevice     | Representa el dispositivo IoT registrado en el sistema, asociado a un espacio específico y encargado de emitir lecturas para el monitoreo.       |


**Métodos:**
- IoTDevice.activate: Cambia el estado del dispositivo a activo para permitir la recepción de lecturas.
- IoTDevice.deactivate: Desactiva el dispositivo y evita que siga enviando información al sistema.
- IoTDevice.isActive: Verifica si el dispositivo se encuentra habilitado para operar.

### Entities

| **Atributo** | **Nombre**  | **Descripción**                                       |
| ------------ | --------- | ----------------------------------------------------- |
| ReadingId, DeviceId, MetricType, Value, Unit, ReceivedAt, Status       | Reading      | Entidad que representa una lectura enviada por un dispositivo IoT, incluyendo el tipo de métrica, valor registrado y estado de validación.      |
| AlertId, ReadingId, Severity, Status, CreatedAt          | Alert              | Entidad que representa una alerta generada cuando una lectura se encuentra fuera de los límites permitidos.                  |

### Value Objects

| **Atributo** | **Nombre**  | **Descripción**                                       |
| ------------ | --------- | ----------------------------------------------------- |
| MinValue, MaxValue, Unit  |  ThresholdRange   | Define el rango permitido para una métrica monitoreada.  |
| Value        | SeverityLevel      | Representa el nivel de gravedad de una alerta: baja, media, alta o crítica.      |
| Value        | ReadingStatus      | Indica el estado de una lectura: recibida, validada o fuera de rango.      |
| Value        | AlertStatus      | Indica el estado de una alerta: creada, enviada, reconocida o cerrada.      |

### Commands & Queries

| **Atributo** | **Nombre**  | **Tipo**                                       |
| ------------ | --------- | ----------------------------------------------------- |
| DeviceId, MetricType, Value, Unit       | IngestReadingCommand     | Command      |
| AlertId       | AcknowledgeAlertCommand      | Command      |
| AlertId       | CloseAlertCommand      | Command      |
| SpaceId       | GetAlertsBySpaceQuery      | Query      |
| SpaceId       | GetReadingsBySpaceQuery      | Query      |

### Domain Services

| **Nombre** | **Funcion**  | **Metodos**                                       |
| ------------ | --------- | ----------------------------------------------------- |
| IMonitoringDomainService        |Define las reglas para validar lecturas, detectar valores fuera de rango y generar alertas.      | ValidateReading, DetectOutOfRange, CreateAlert     |
| IAlertPolicyService        | Define criterios para clasificar la severidad de una alerta según el valor detectado.      | EvaluateSeverity, CanDispatchAlert      |

**Métodos:**

- IMonitoringDomainService.ValidateReading: Verifica que la lectura provenga de un dispositivo registrado y activo.
  
- IMonitoringDomainService.DetectOutOfRange: Evalúa si el valor recibido está fuera del rango permitido.
  
- IMonitoringDomainService.CreateAlert: Genera una alerta cuando se detecta una lectura anómala.
  
- IAlertPolicyService.EvaluateSeverity: Determina la severidad de la alerta según la métrica y el valor registrado.
  
- IAlertPolicyService.CanDispatchAlert: Valida si una alerta puede ser enviada al usuario responsable.

### Repositories

| **Nombre** | **Descripción**  | 
| ------------ | --------- |
| IIoTDeviceRepository        |Interfaz para la persistencia y recuperación de dispositivos IoT registrados.      |
| IReadingRepository        | Interfaz para almacenar y consultar lecturas recibidas desde los dispositivos.      |
| IAlertRepository        | Interfaz para gestionar el almacenamiento y consulta de alertas generadas.      |

En la Domain Layer de SpacePulse, dentro del bounded context IoT Monitoring and Notifications, se define la lógica central para monitorear dispositivos, procesar lecturas y generar alertas ante condiciones fuera de rango. La clase IoTDevice actúa como el agregado raíz, mientras que Reading y Alert representan los eventos operativos principales del monitoreo. Finalmente, la validación de lecturas, detección de anomalías y persistencia de información se gestionan mediante servicios de dominio y repositorios especializados.

### 4.2.5.2. Interface Layer

En la Interface Layer de SpacePulse, específicamente para el contexto de IoT Monitoring and Notifications, se definen los puntos de entrada que permiten la comunicación externa con las funcionalidades de monitoreo. Esta capa utiliza controladores REST, recursos DTOs y ensambladores para recibir lecturas IoT, consultar información de monitoreo y gestionar alertas, desacoplando el modelo de dominio de las representaciones externas.

### Resources

| **Nombre** | **Descripción**  |  
| ------------ | --------- | 
| IngestReadingResource        | DTO que encapsula los datos de entrada de una lectura IoT, incluyendo DeviceId, MetricType, Value y Unit.      | 
| ReadingResource        | DTO de salida que representa la información de una lectura registrada, como identificador, dispositivo, métrica, valor, unidad, fecha y estado.      | 
| AlertResource        | DTO de salida que representa una alerta generada por una lectura fuera de rango, incluyendo identificador, severidad, estado y mensaje.     | 
| AcknowledgeAlertResource        | DTO que transporta la información necesaria para reconocer una alerta pendiente.     | 
| CloseAlertResource        | DTO que permite cerrar una alerta luego de haber sido revisada o atendida.     | 

### Controllers

| **Nombre** | **Método HTTP**  | **Parámetro / Resource**  | **Descripción** |
| ------------ | --------- | --------- | --------- |
| IoTMonitoringController        | POST    |IngestReadingResource   | Expone el endpoint para recibir una nueva lectura enviada por un dispositivo IoT.   |
| IoTMonitoringController        | GET     |  SpaceId |  Recupera las lecturas registradas para un espacio monitoreado.  |
| AlertController        | GET      | SpaceId  |  Recupera las alertas asociadas a un espacio específico.  |
| AlertController        | PATCH     |  AcknowledgeAlertResource |  Permite marcar una alerta como reconocida por el usuario responsable.  |
| AlertController        | PATCH     |  CloseAlertResource |  Permite cerrar una alerta cuando ya fue atendida.  |

### Transformers / Assemblers

| **Nombre** | **Descripción**  |  
| ------------ | --------- | 
| IngestReadingCommandFromResourceAssembler        | Transforma los datos recibidos en IngestReadingResource en un comando IngestReadingCommand procesable por la capa de aplicación.   | 
| ReadingResourceFromEntityAssembler        | Convierte la entidad de dominio Reading en un objeto ReadingResource para su envío a través de la API.      | 
| AlertResourceFromEntityAssembler        | Convierte la entidad de dominio Alert en un objeto AlertResource para mostrar la información de la alerta en la aplicación.     | 
| AcknowledgeAlertCommandFromResourceAssembler        | Convierte el recurso AcknowledgeAlertResource en un comando para reconocer una alerta.    | 
| CloseAlertCommandFromResourceAssembler        | Convierte el recurso CloseAlertResource en un comando para cerrar una alerta.     | 

En la Interface Layer de SpacePulse, específicamente para el contexto de IoT Monitoring and Notifications, los controladores reciben las solicitudes HTTP relacionadas con lecturas y alertas, las transforman mediante recursos y ensambladores, y las delegan a los servicios correspondientes. Esta capa no contiene reglas de negocio, sino que actúa como puente entre la aplicación móvil, los dispositivos IoT y la lógica interna del sistema de monitoreo.

### 4.2.5.3. Application Layer

En la Application Layer de SpacePulse, específicamente para el contexto de IoT Monitoring and Notifications, los handlers se encargan de procesar los comandos y consultas relacionados con la recepción de lecturas IoT, la validación de datos y la gestión de alertas. Esta capa actúa como intermediaria entre la interfaz y el dominio, coordinando las operaciones necesarias para registrar lecturas, detectar valores fuera de rango, generar alertas y consultar información de monitoreo sin incluir directamente detalles de infraestructura.

### Commands & Queries Handlers

| **Nombre** | **Descripción**  |   Resumen de Lógica  |
| ------------ | --------- | --------- | 
| IngestReadingCommandHandler        | Procesa la recepción de nuevas lecturas enviadas por dispositivos IoT.      | Valida que el dispositivo exista y esté activo, registra la lectura recibida, evalúa si el valor está fuera del rango permitido y, si corresponde, genera una alerta asociada. | 
| AcknowledgeAlertCommandHandler        | Gestiona el reconocimiento de una alerta pendiente.     | Busca la alerta por su identificador, valida que pueda ser reconocida y actualiza su estado para indicar que el usuario ya tomó conocimiento del evento. | 
| CloseAlertCommandHandler        | Gestiona el cierre de una alerta atendida.  | Recupera la alerta registrada, valida su estado actual y la marca como cerrada cuando ya fue revisada o solucionada. | 
| GetReadingsBySpaceQueryHandler        | Recupera las lecturas asociadas a un espacio monitoreado.     | Consulta el repositorio de lecturas usando el identificador del espacio y devuelve la información organizada para su visualización. | 
| GetAlertsBySpaceQueryHandler        | Recupera las alertas generadas dentro de un espacio específico.   | Consulta las alertas asociadas al espacio, filtrando eventos pendientes, reconocidos o cerrados según sea necesario. | 


### Internal DTOs (Data Transfer Objects)

| **Nombre** | **Descripción**  |  
| ------------ | --------- | 
| ReadingDto        | Objeto que transporta la información principal de una lectura IoT, incluyendo dispositivo, tipo de métrica, valor, unidad, fecha de recepción y estado.    | 
| AlertDto        | DTO que representa una alerta generada por el sistema, incluyendo identificador, mensaje, severidad, estado y fecha de creación.    | 
| MonitoringSummaryDto        | Estructura resumida que agrupa información de monitoreo de un espacio, como cantidad de lecturas recientes, alertas activas y estado general del monitoreo.     | 

### 4.2.5.4. Infrastructure Layer

En la Infrastructure Layer de SpacePulse, específicamente para el contexto de IoT Monitoring and Notifications, se implementan los detalles técnicos necesarios para persistir dispositivos, lecturas y alertas, así como para integrarse con servicios externos relacionados con la recepción de datos IoT y el envío de notificaciones. Esta capa permite que la lógica del dominio se ejecute sobre una infraestructura concreta, manteniendo separadas las reglas de negocio de los mecanismos técnicos de almacenamiento y comunicación.

### Persistence (Repositories Implementation)

| **Nombre** | **Descripción**  |   Tecnologías / Herramientas  |
| ------------ | --------- | --------- | 
| IoTDeviceRepository        | Implementación concreta de IIoTDeviceRepository encargada de registrar, actualizar y consultar dispositivos IoT asociados a los espacios monitoreados.     | Entity Framework Core, LINQ | 
| ReadingRepository        | Implementación de IReadingRepository encargada de almacenar las lecturas recibidas desde los dispositivos y consultarlas por espacio, dispositivo o fecha.    | Entity Framework Core, LINQ | 
| AlertRepository        | Implementación de IAlertRepository encargada de persistir alertas generadas, actualizar su estado y recuperar alertas pendientes o históricas.    | Entity Framework Core, LINQ | 
| IoTDeviceConfiguration        | Define el mapeo entre la entidad IoTDevice y la tabla correspondiente en la base de datos, incluyendo restricciones y relaciones.  | Fluent API | 
| ReadingConfiguration        | Configura el esquema de base de datos para las lecturas IoT, incluyendo tipos de datos, relación con dispositivos y fecha de recepción.   | Fluent API | 
| AlertConfiguration        | Configura el mapeo de las alertas, sus estados, severidad y relación con la lectura que originó la alerta.     | Fluent API | 

### Security Services Implementation

| **Nombre** | **Descripción**  |   Resumen de Implementación  |
| ------------ | --------- | --------- | 
| IoTBrokerAdapter      | Adaptador encargado de recibir datos provenientes del broker IoT o dispositivos externos.     | Recibe lecturas externas, normaliza su formato y las transforma en datos procesables por la capa de aplicación. | 
| NotificationDispatcherService        |Servicio técnico encargado de enviar alertas o mensajes hacia los usuarios cuando ocurre un evento importante.   |Integra el sistema con un servicio externo de correo o notificaciones para comunicar alertas generadas por el monitoreo. | 
| ReadingNormalizerService        |Servicio de apoyo encargado de limpiar y estandarizar los valores recibidos desde sensores.    | Convierte unidades, valida estructura básica de datos y prepara la lectura antes de ser enviada al dominio. | 

### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams

![IoT_Monitoring_and_Notifications_Software_Architecture_ Component_Level_Diagram](Assets/IoT_Monitoring_and_Notifications_Software_Architecture_Component_Level_Diagram.png)

### 4.2.5.6. Bounded Context Software Architecture Code Level Diagrams

### 4.2.5.6.1. Bounded Context Domain Layer Class Diagrams

![IoT_Monitoring_and_Notifications_Domain_Layer_Class_Diagram](Assets/IoT_Monitoring_and_Notifications_Domain_Layer_Class_Diagram.png)

### 4.2.5.6.2. Bounded Context Database Design Diagrams

![IoT_Monitoring_and_Notifications_Database_Design_Diagram](Assets/IoT_Monitoring_and_Notifications_Database_Design_Diagram.png)

## Conclusiones

### Conclusiones:

#### Conclusiones TB1:

### Recomendaciones:

#### Recomendaciones TB1:

## Bibliografía

## Anexos
