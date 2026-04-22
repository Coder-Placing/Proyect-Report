
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
Coder-Placing es una startup orientada a la digitalización de espacios privados, principalmente viviendas y oficinas, mediante un modelo que integra alquiler, remodelación y monitoreo IoT en una sola solución. La propuesta nace ante una necesidad concreta del mercado: 
actualmente, gran parte del proceso de remodelación y gestión de espacios todavía se maneja con comunicación dispersa, cotizaciones aisladas, poca trazabilidad del avance y escasa visibilidad del estado real de los trabajos. En paralelo, el contexto tecnológico ya permite una solución mobile-first, 
ya que en el Perú el acceso a internet en el hogar alcanzó 92.6% en 2024 y la telefonía móvil llegó a 99.3% de los hogares, lo que vuelve viable una plataforma digital para coordinar servicios, pagos y seguimiento remoto



#### 1.1.1. Descripción de la Startup

Nuestra empresa desarrolla soluciones digitales para conectar a propietarios, remodeladores y técnicos en torno a un mismo espacio físico. Su propuesta combina marketplace, contratación por suscripción, seguimiento operativo de remodelaciones y monitoreo mediante dispositivos IoT, permitiendo una gestión más ordenada, medible y transparente.
Dentro de este ecosistema, se propone como producto principal SpacePulse, una aplicación móvil/web que permite publicar espacios, contratar combos de remodelación, gestionar procesos y materiales, monitorear avances, recibir alertas y controlar pagos recurrentes desde una sola plataforma.


**Objetivo:**

Brindar a propietarios y empresas remodeladoras una plataforma centralizada para alquilar, remodelar y monitorear espacios privados, integrando procesos operativos, pagos y seguimiento IoT en tiempo real.


**Misión**

Simplificar la transformación y gestión de espacios privados mediante tecnología accesible, conectando a los actores del proceso de remodelación con información centralizada, trazabilidad operativa y monitoreo inteligente.

**Visión**

Convertirse en una startup referente en Latinoamérica en soluciones digitales para espacios inteligentes, destacando por integrar marketplace, remodelación y monitoreo IoT en una experiencia confiable y escalable.

#### 1.1.2. Perfiles de integrantes del equipo
|  Foto   | Miembros del equipo        | Código de Estudiante |   Descripción          |
|---------| -------------------------- |----------------------| ---------------------- |
| ![Imagen1](Assets/TB1/eric.png) |Wilder Gonzalo Aliaga Urbina |U202222001    |     |
| ![Imagen2]()                    |Via Luna Bruce|U202313403|  |
| ![Imagen3]()                    |   |                      |  |
| ![Imagen4]()                    |   |                      |  |
| ![Imagen5]()                    |   |                      |  |


### 1.2. Solution Profile

SpacePulse es una plataforma digital orientada a dos segmentos principales: clientes que desean contratar un servicio de remodelación o acondicionamiento para su casa u oficina, y empresas remodeladoras que necesitan gestionar sus servicios, proyectos y seguimiento operativo desde un mismo entorno. La solución integra cuatro frentes principales: publicación del espacio, contratación del servicio, seguimiento del proyecto y monitoreo de incidencias mediante IoT.

La propuesta toma valor porque los espacios inteligentes no se limitan a automatización: según Deloitte, los smart buildings combinan automatización operativa y gestión inteligente del espacio para mejorar la experiencia del usuario, elevar la productividad, reducir costos y mitigar riesgos. Además, el uso de sensores y medidores inteligentes puede generar ahorros eléctricos promedio de 4% a 12% cuando se brinda retroalimentación en tiempo real al usuario.

#### 1.2.1. Antecedentes y problemática

Actualmente, la remodelación de viviendas y oficinas suele gestionarse con herramientas separadas: mensajes por WhatsApp, hojas de cálculo, cotizaciones manuales, llamadas, evidencias dispersas y seguimiento informal del avance. Esto dificulta saber qué se contrató, cuánto se ha ejecutado, qué materiales faltan, cuánto se debe pagar y si existe alguna incidencia en el espacio intervenido.

A esto se suma un contexto en el que los espacios de trabajo están cambiando. JLL señala que los diseños de oficina actuales priorizan layouts abiertos, flexibles y adaptables al trabajo híbrido, y que los costos globales de fit-out aumentaron aproximadamente entre 2% y 6% en el último año. En ese escenario, la gestión precisa del presupuesto, del alcance de la remodelación y del avance real del proyecto se vuelve más importante.

#### 1. ¿Qué?

Existe una falta de integración en la gestión del alquiler, remodelación y monitoreo de espacios privados. Los propietarios no cuentan con una plataforma unificada para publicar su espacio, contratar remodelación, controlar pagos, revisar avances e identificar incidentes técnicos en tiempo real.

#### 2. ¿Cuándo?

El problema aparece durante todo el ciclo de atención del espacio: desde la publicación inicial del inmueble, pasando por la cotización y contratación del servicio, hasta la ejecución de la remodelación, el control de materiales, los cobros mensuales y el seguimiento de incidentes o cambios solicitados.

#### 3. ¿Dónde?

Se presenta principalmente en viviendas, departamentos, oficinas y pequeños espacios privados urbanos, donde el proceso de mejora o reacondicionamiento requiere coordinación remota, control presupuestal y comunicación constante entre varios actores.

#### 4. ¿Quién?

Los afectados principales son:
- **Clientes que desean el servicio**, como propietarios o administradores de casas y oficinas que buscan remodelar, modernizar o acondicionar un espacio con mayor control, visibilidad y confianza.
- **Empresas remodeladoras**, que necesitan captar clientes, organizar catálogos, gestionar proyectos, coordinar personal técnico, controlar materiales y mantener trazabilidad sobre tiempos, costos e incidencias.

#### 5. ¿Por qué?

Porque el proceso sigue siendo altamente manual y fragmentado. Aunque el contexto digital ya es favorable, muchas decisiones operativas todavía dependen de seguimiento informal. En el Perú, 31.35 millones de líneas móviles accedieron a internet al cierre de 2024, lo que demuestra que existe una base tecnológica suficiente para operar una solución de seguimiento móvil y en tiempo real.

#### 6. ¿Cómo?

La problemática puede abordarse mediante una aplicación que centralice:
- el catálogo de espacios y combos de remodelación,
- la contratación por suscripción,
- la facturación y emisión de comprobantes,
- el registro de proyectos, procesos y materiales,
- el monitoreo de lecturas IoT,
- la generación de alertas e incidencias,
- y la creación de tareas correctivas hasta el cierre del servicio.

#### 7. ¿Cuánto?

El problema impacta en tiempo, costos y control. No solo se pierde visibilidad del avance, sino también eficiencia en la toma de decisiones. En un contexto donde los costos de fit-out siguen subiendo y donde los edificios inteligentes buscan reducir costos operativos y riesgos, trabajar sin una plataforma integrada representa mayor probabilidad de retrasos, sobrecostos y mala experiencia para el propietario.

#### 1.2.2. Lean UX Process

##### 1.2.2.1. Lean UX Problem Statements

**Problema 1**  
Los propietarios de casas y oficinas necesitan una forma más simple de contratar y seguir remodelaciones, porque actualmente el proceso depende de múltiples canales y no ofrece trazabilidad clara del avance, los costos ni las incidencias.

**Problema 2**  
Las empresas remodeladoras necesitan una plataforma para organizar catálogos, proyectos, materiales, procesos y cobros, porque la gestión dispersa reduce eficiencia operativa y dificulta brindar una experiencia confiable al cliente.

**Problema 3**  
Tanto clientes como empresas remodeladoras necesitan monitoreo centralizado del estado del espacio, porque los cambios, alertas y problemas técnicos suelen detectarse tarde o comunicarse de forma desordenada.

##### 1.2.2.2. Lean UX Assumptions

**Business Assumptions (Suposiciones de Negocio)**

- Creo que mis clientes tienen la necesidad de: Contar con una plataforma que centralice la contratación, planificación, seguimiento y monitoreo de remodelaciones para casas y oficinas, evitando la desorganización, la poca visibilidad del avance y la dependencia de medios informales de comunicación.

- Estas necesidades se pueden resolver con: Una aplicación móvil que conecte al cliente y a la empresa remodeladora en un mismo entorno digital, permitiendo visualizar el progreso, registrar procesos, materiales, tiempos, pagos, incidentes y alertas del espacio intervenido.

- Mis clientes iniciales son (o serán): Propietarios de casas u oficinas pequeñas que desean remodelar con mayor control y transparencia, así como empresas remodeladoras que necesitan ordenar sus operaciones y ofrecer un servicio más confiable.

- El valor principal que los clientes quieren obtener de mi servicio es: Tener control, visibilidad y seguimiento del proceso de remodelación en tiempo real. Beneficios adicionales que también pueden obtener: Mejor comunicación, trazabilidad de cambios, mayor control de costos, respuesta rápida ante incidentes y una experiencia más ordenada.

- Adquiriré a la mayoría de mis clientes a través de: Redes sociales, campañas dirigidas a propietarios y pequeñas empresas, alianzas con remodeladoras, demostraciones del producto y recomendaciones de clientes satisfechos.

- Ganaré dinero mediante: Cobros por servicios contratados dentro de la plataforma, suscripciones para empresas remodeladoras y comisiones por paquetes de remodelación o monitoreo IoT.

- Mi principal competencia en el mercado será: Empresas tradicionales de remodelación y plataformas de servicios que no integran seguimiento del proceso. Los superaremos debido a: Nuestra propuesta reúne marketplace, gestión de remodelación, monitoreo IoT, alertas automáticas y trazabilidad en una sola solución móvil.

- Mi mayor riesgo de producto es: Que los usuarios perciban la plataforma como algo más complejo que gestionar todo por WhatsApp, llamadas o visitas. Lo resolveremos mediante: Una interfaz simple, información clara, alertas útiles y una propuesta enfocada en reducir incertidumbre y aumentar la confianza.

- Otras suposiciones que, si resultan falsas, harán que nuestro proyecto fracase:
    - Que los clientes valoren monitorear el avance de la remodelación desde una aplicación móvil.
    - Que las empresas remodeladoras estén dispuestas a registrar procesos, materiales e incidencias de forma constante.
    - Que el componente IoT sea visto como una ventaja diferencial.
    - Que exista disposición a pagar por un servicio más transparente, trazable y apoyado en tecnología.

**User Assumptions (Suposiciones de Usuario)**

- ¿Quién es el usuario?: Nuestros usuarios serán, por un lado, clientes que desean remodelar una casa u oficina con mayor confianza; y, por otro lado, empresas remodeladoras que ejecutan el servicio y coordinan personal, materiales, tiempos y seguimiento operativo.

- ¿Dónde encaja nuestro producto en su trabajo o vida?: Para el cliente, encaja como una herramienta de seguimiento y control del estado de su espacio. Para la empresa, encaja como una herramienta de gestión operativa y comunicación con el cliente durante el proyecto.

- ¿Qué problemas resuelve nuestro producto?: Nuestro producto resuelve los siguientes problemas:
    - La falta de visibilidad sobre el estado real de una remodelación.
    - La desorganización en el registro de procesos, materiales, tiempos y costos.
    - La dependencia de llamadas, mensajes o visitas para conocer avances.
    - La poca trazabilidad de cambios o incidentes.
    - La falta de alertas oportunas frente a retrasos o problemas en el espacio.

- ¿Cuándo y cómo se usa nuestro producto?: Se utiliza antes, durante y después de contratar el servicio. El cliente lo usa para revisar avances, aceptar cambios, visualizar pagos, recibir alertas y confirmar incidentes. La empresa lo usa para registrar procesos, actualizar estados, gestionar materiales, controlar tareas y mantener informado al cliente desde dispositivos móviles.

- ¿Qué características son importantes?: Las características más importantes de nuestro producto son:
    - Visualización del avance de la remodelación en tiempo real.
    - Registro de procesos, materiales, costos y tiempos.
    - Alertas automáticas e incidentes asociados al espacio.
    - Historial de cambios durante la remodelación.
    - Gestión de pagos, contratos o suscripciones.
    - Marketplace inicial para conectar espacios y servicios.
    - Monitoreo IoT aplicado al seguimiento del espacio.

- ¿Cómo debería verse y comportarse nuestro producto?: Debe tener una interfaz moderna, intuitiva y tecnológica, con navegación simple, paneles claros, indicadores fáciles de entender y alertas visibles. Además, debe transmitir confianza, orden y control sobre el espacio y la inversión del usuario.

##### 1.2.2.3. Lean UX Hypothesis Statements

**Hypothesis Statement 01:**

- Creemos que centralizar en una sola aplicación la contratación, el seguimiento de la remodelación, el monitoreo IoT y los pagos permitirá que el cliente tenga una mayor percepción de control sobre su espacio.
- Sabremos que estamos en lo correcto cuando la mayoría de usuarios indique en entrevistas o pruebas que la plataforma reduce la incertidumbre y les permite entender mejor el estado de su proyecto.

**Hypothesis Statement 02:**

- Creemos que permitir a la empresa remodeladora registrar procesos, materiales, tiempos y avances dentro de la plataforma mejorará la organización operativa del servicio.
- Sabremos que estamos en lo correcto cuando las empresas usuarias afirmen que pueden ordenar mejor sus actividades y reducir pérdidas de información durante la ejecución de la remodelación.

**Hypothesis Statement 03:**

- Creemos que mostrar el avance de la remodelación en tiempo real desde el celular aumentará la confianza del cliente en el servicio contratado.
- Sabremos que estamos en lo correcto cuando los usuarios manifiesten que revisar el progreso desde la aplicación les genera mayor tranquilidad que depender de mensajes o reportes manuales.

**Hypothesis Statement 04:**

- Creemos que incorporar alertas automáticas e incidentes relacionados con el espacio permitirá una atención más rápida frente a problemas o anomalías durante el proceso.
- Sabremos que estamos en lo correcto cuando los usuarios consideren útiles las notificaciones y perciban que estas mejoran la capacidad de respuesta ante eventos inesperados.

**Hypothesis Statement 05:**

- Creemos que ofrecer un historial de cambios, costos y procesos completados mejorará la transparencia del servicio para el cliente.
- Sabremos que estamos en lo correcto cuando los usuarios indiquen que la trazabilidad de la información les ayuda a confiar más en la empresa remodeladora.

**Hypothesis Statement 06:**

- Creemos que un marketplace inicial donde se publiquen espacios y servicios de remodelación facilitará la conexión entre la necesidad del cliente y la oferta de la empresa.
- Sabremos que estamos en lo correcto cuando los usuarios entiendan fácilmente el flujo de publicación, contratación y seguimiento sin necesidad de recurrir a canales externos.

**Hypothesis Statement 07:**

- Creemos que permitir modificaciones sobre muebles, procesos o elementos aún no finalizados hará que la solución sea percibida como más flexible y personalizada.
- Sabremos que estamos en lo correcto cuando los clientes valoren positivamente la posibilidad de ajustar su remodelación y visualizar el impacto de esos cambios en tiempo y costo.

**Hypothesis Statement 08:**

- Creemos que integrar monitoreo IoT dentro del servicio de remodelación diferenciará nuestra propuesta frente a empresas tradicionales del rubro.
- Sabremos que estamos en lo correcto cuando tanto clientes como empresas reconozcan el componente tecnológico como un valor agregado importante al momento de comparar alternativas.

**Hypothesis Statement 09:**

- Creemos que diseñar la solución principalmente para dispositivos móviles incrementará la frecuencia de interacción de los usuarios con la plataforma.
- Sabremos que estamos en lo correcto cuando observemos que los usuarios revisan con frecuencia avances, alertas, cambios y estados del proyecto desde sus celulares.

**Hypothesis Statement 10:**

- Creemos que una interfaz intuitiva, visual y fácil de usar reducirá la barrera de adopción tanto para clientes como para empresas remodeladoras.
- Sabremos que estamos en lo correcto cuando nuevos usuarios puedan comprender las funciones principales de la aplicación sin necesidad de capacitación extensa.

**Hypothesis Statement 11:**

- Creemos que permitir al cliente visualizar el detalle de materiales y procesos de su remodelación aumentará su percepción de transparencia en el servicio.
- Sabremos que estamos en lo correcto cuando los usuarios indiquen que tener acceso a esa información les da más seguridad al momento de continuar con el proyecto.

**Hypothesis Statement 12:**

- Creemos que mostrar actualizaciones frecuentes del estado del espacio remodelado motivará al cliente a revisar la aplicación de manera constante.
- Sabremos que estamos en lo correcto cuando observemos que los usuarios ingresan repetidamente a consultar avances, cambios o nuevas alertas del proyecto.

**Hypothesis Statement 13:**

- Creemos que ofrecer a la empresa remodeladora una vista centralizada de todos sus proyectos facilitará la gestión simultánea de varias remodelaciones.
- Sabremos que estamos en lo correcto cuando las empresas usuarias afirmen que pueden supervisar mejor múltiples espacios sin perder información relevante de cada uno.

**Hypothesis Statement 14:**

- Creemos que incorporar notificaciones sobre retrasos, cambios de estado o problemas detectados mejorará la comunicación entre el cliente y la empresa.
- Sabremos que estamos en lo correcto cuando los usuarios reporten menos confusiones o consultas repetitivas sobre el estado de la remodelación.

**Hypothesis Statement 15:**

- Creemos que una propuesta enfocada en casas y oficinas pequeñas permitirá validar más rápido la utilidad de la solución antes de escalar a proyectos de mayor tamaño.
- Sabremos que estamos en lo correcto cuando logremos que los primeros usuarios de ese segmento adopten la plataforma y destaquen su utilidad en el seguimiento de remodelaciones.

##### 1.2.2.4. Lean UX Canvas



### 1.3. Segmentos Objetivos

#### Segmento Objetivo 1: Cliente que desea el servicio

Este segmento corresponde a personas o responsables de un inmueble que buscan remodelar, acondicionar o modernizar una casa, departamento u oficina. Su principal necesidad es contar con un servicio claro, confiable y fácil de seguir, que les permita revisar opciones, conocer costos, aprobar cambios y monitorear el avance del proyecto sin depender de mensajes dispersos o seguimiento informal.

**Características Demográficas:**  
Generalmente, este segmento está conformado por adultos entre 28 y 55 años, con capacidad de decisión sobre su vivienda u oficina, ubicados principalmente en zonas urbanas. Además, suelen estar familiarizados con el uso del celular para realizar consultas, coordinar servicios y hacer seguimiento a procesos importantes de su vida diaria.

**Información Estadística de Sustento:**  
Este segmento resulta relevante porque el uso de herramientas digitales en el país es cada vez mayor. En el primer trimestre de 2025, el 58,9% de los hogares del país contó con acceso a Internet y el 95,2% tuvo al menos un integrante con telefonía móvil. Esto respalda la viabilidad de una aplicación móvil orientada al seguimiento de remodelaciones y monitoreo de espacios.

#### Segmento Objetivo 2: Empresa remodeladora

Este segmento corresponde a empresas o negocios que ofrecen servicios de remodelación, implementación o mejora de espacios privados. Su principal interés es contar con una plataforma que les permita publicar sus servicios, captar clientes, administrar proyectos, registrar materiales, coordinar actividades técnicas y llevar un mejor control de pagos, avances e incidencias.

**Características Demográficas:**  
Este segmento está conformado principalmente por micro y pequeñas empresas ubicadas en zonas urbanas, dirigidas por dueños, gerentes o encargados operativos que necesitan ordenar sus procesos y brindar una atención más profesional. Además, suelen requerir herramientas digitales simples e intuitivas que les ayuden a gestionar varios proyectos sin recurrir únicamente a registros manuales o aplicaciones de mensajería.

**Información Estadística de Sustento:**  
Según PRODUCE, en el Perú existen 2,2 millones de Mipyme formales, de las cuales el 94,7% son microempresas y el 5,0% pequeñas empresas. Esta composición empresarial respalda que una solución como SpacePulse puede enfocarse en negocios remodeladores pequeños y medianos que necesitan digitalizar su operación sin adoptar sistemas complejos o costosos.
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