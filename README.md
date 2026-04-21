
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


## Conclusiones

### Conclusiones:

#### Conclusiones TB1:

### Recomendaciones:

#### Recomendaciones TB1:

## Bibliografía

## Anexos