
<p align="center">
  <img src="img/image1.png" alt="Logo de UPC" width="100%">
</p>

<div align="center">

# <span style="color:red">**Universidad Peruana de Ciencias Aplicadas**</span>
## Carrera de Ingeniería de Software

Ciclo: 2024 - 1

Curso: Aplicaciones Web

Sección: SW53

Profesor: Alex Humberto Sánchez Ponce

“Informe de Trabajo Final”

Startup: CargoWatch

Producto: CargoApp


|          Integrantes          |      Código      |
|:-----------------------------:|:-------------------:|
|   Delgado Corrales, Piero Gonzalo   |    U202210749    |
|  Matos Fernandez, Christian Andre   |    U202214162    |
|   Paredes Puente, Sebastián Roberto  |    U202217239    |
|  Salinas Torres, Salvador Antonio   |    U20221B127    |
|   Valverde Mozo, Andre Gabriel   |    U202218899    |

Abril 2024

</div>

<table>
  <thead>
    <tr>
        <th>Versión</th>
        <th>Fecha</th>
        <th>Autor</th>
        <th>Descripción de modificación</th>
    </tr>
  </thead>
  <tbody>
  <tr>
      <td><strong>TB1</strong></td>
      <td>Miércoles 10 de Abril</td>
      <td>
        <ul>
          <li>Delgado Corrales, Piero Gonzalo</li>
          <li>Matos Fernandez, Christian Andre</li>
          <li>Paredes Puente, Sebastián Roberto</li>
          <li>Salinas Torres, Salvador Antonio</li>
          <li>Valverde Mozo, Andre Gabriel</li>
        </ul>
      </td>
      <td>
        Se han incluído los siguientes capítulos:
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

# **Project Report Collaboration Insights**
URL Project Report (Github): [https://github.com/Grupo-2-Apps-Web/Project-Report](https://github.com/Grupo-2-Apps-Web/Project-Report)

# **Tabla de Contenido**

- [Registro de Versiones](#registro-de-versiones)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#Capítulo-I-Introducción)
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
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#Capítulo-II-Requirements-Elicitation--Analysis)
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
  - [2.4. Ubiquitous Language](#23-ubiquitous-language)
- [Capítulo III: Requirements Specification](#Capítulo-III-Requirements-Specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Product Design](#Capítulo-IV-Product-Design)
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
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
- [Capítulo V: Product Implementation, Validation & Deployment](#Capítulo-V-Product-Implementation-Validation--Deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint n](#521-sprint-n)
      - [5.2.1.1. Sprint Planning n](#5211-sprint-planning-n)
       -[5.2.1.2. Sprint Backlog n](#5212-sprint-backlog-n)
      - [5.2.1.3. Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
      - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
  - [5.4. Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)


# Capítulo I Introducción

# Capítulo II Requirements Elicitation & Analysis

## 2.1 Competidores

Para realizar el análisis competitivo hemos tomado en consideración competidores directos e indirectos:

* LogiNext Mile: empresa que ofrece un software de optimización de rutas y planificación de entregas que automatiza y mejora la eficiencia de las operaciones de entrega, garantizando entregas más rápidas y una experiencia superior para el cliente mediante la integración de preferencias del cliente. 

<div align="center">
  <img src="img/logo_loginext.jpg" alt="Logo de LogiNextMile" width="10%">
</div>

* Drivin: empresa que busca incrementar la eficiencia de operaciones logísticas como planificación de rutas, sistema de notificaciones y monitoreo a tiempo real.

<div align="center">
  <img src="img/logo_drivin.jpg" alt="Logo de Driv.in" width="10%">
</div>

* SimpliRoute: aplicación que utiliza tecnología IA para optimizar rutas de entrega incorporando variables como límite de carga por vehículo, horarios y restricciones territoriales.

<div align="center">
  <img src="img/logo_simpliroute.png" alt="Logo de SimpliRoute" width="10%">
</div>

### 2.1.1 Análisis competitivo

<table>
  <tr>
    <th colspan="6" valign="top">Competitive Analysis Landscape</th>
  </tr>
  <tr>
    <td colspan="2" valign="top">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="4" valign="top">El objetivo de este análisis es identificar las características de los competidores y encontrar maneras de diferenciarnos.</td>
  </tr>
  <tr>
    <td colspan="2" rowspan="2" valign="top">Startup y Competidores</td>
    <td valign="top">CargoWatch</td>
    <td valign="top">LogiNext Mile</td>
    <td valign="top">Drivin</td>
    <td valign="top">SimpliRoute</td>
  </tr>
  <tr>
    <td valign="top"><img src="img/logo.png" alt="Logo de CargoWatch" height="100px"></td>
    <td valign="top"><img src="img/logo_loginext.jpg" alt="Logo de LogiNext Mile" height="100px"></td>
    <td valign="top"><img src="img/logo_drivin.jpg" alt="Logo de Driv.in" height="100px"></td>
    <td valign="top"><img src="img/logo_simpliroute.png" alt="Logo de SimpliRoute" height="100px"></td>
  </tr>
  <tr>
    <td rowspan="2" valign="top">Perfil</td>
    <td valign="top">Overview</td>
    <td valign="top">Plataforma innovadora que ofrece seguimiento en tiempo real y transparencia en el transporte de carga para empresas</td>
    <td valign="top">Software integral para optimizar y automatizar operaciones de entrega, incluyendo planificación de rutas y seguimiento en tiempo real</td>
    <td valign="top">Plataforma para mejorar la eficiencia logística interconectando módulos como planificación de rutas y monitoreo en tiempo real</td>
    <td valign="top">Aplicación de optimización de rutas de entrega con enfoque en variables como límites de carga y horarios, utilizando tecnología IA</td>
  </tr>
  <tr>
    <td valign="top">Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
    <td valign="top">Seguimiento en tiempo real y reportes detallados de gastos como el cálculo de los costos de combustible durante el transporte de carga</td>
    <td valign="top">Entregas más rápidas, menores costos y una experiencia superior para el cliente</td>
    <td valign="top">Optimización operativa para entregas rápidas y precisas</td>
    <td valign="top">Optimización avanzada de rutas mediante IA para reducir costos y tiempos de entrega</td>
  </tr>
  <tr>
    <td rowspan="2" valign="top">Perfil de Marketing</td>
    <td valign="top">Mercado objetivo</td>
    <td valign="top">Empresas logísticas de transporte terrestre</td>
    <td valign="top">Empresas logísticas de transporte terrestre</td>
    <td valign="top">Empresas logísticas de transporte terrestre</td>
    <td valign="top">Empresas logísticas de transporte terrestre</td>
  </tr>
  <tr>
    <td valign="top">Estrategias de marketing</td>
    <td valign="top">Transparencia, seguridad e innovación</td>
    <td valign="top">Digitalización, optimización y automatización</td>
    <td valign="top">Empresa joven, dinámica y flexible</td>
    <td valign="top">Confianza, innovación y simple</td>
  </tr>
  <tr>
    <td rowspan="3" valign="top">Perfil de Producto</td>
    <td valign="top">Productos & Servicios</td>
    <td valign="top">Plataforma de seguimiento a tiempo real<br>Reporte detallado de gastos<br>Análisis de datos<br>Comunicación integrada</td>
    <td valign="top">Automatización de operaciones de entrega<br>Integraciones con terceros</td>
    <td valign="top">Distintos módulos interconectados como optimizador de ruta, gestión de documentos, disponibilidad de vehículos, etc.</td>
    <td valign="top">Algoritmo de optimización de rutas<br>Servicio de integración de herramientas de logística</td>
  </tr>
  <tr>
    <td valign="top">Precios & Costos</td>
    <td valign="top">20$ / mes</td>
    <td valign="top">50$ / mes</td>
    <td valign="top">35$ / mes</td>
    <td valign="top">Lite (40$ / mes)<br>Pro  (Personalizado)<br>Corporate (Personalizado)</td>
  </tr>
  <tr>
    <td valign="top">Canales de distribución (Web y/o Móvil)</td>
    <td valign="top">Web y/o móvil</td>
    <td valign="top">Web y/o móvil</td>
    <td valign="top">Web y/o móvil</td>
    <td valign="top">Web y/o móvil</td>
  </tr>
  <tr>
    <td rowspan="4" valign="top">Análisis SWOT</td>
    <td valign="top">Fortalezas</td>
    <td valign="top">Reportes detallados de gastos, lo que permite a los usuarios analizar y controlar sus costos operativos de manera efectiva</td>
    <td valign="top">Enfoque en entregas más rápidas, menores costos y una experiencia superior para el cliente</td>
    <td valign="top">Amplia gama de servicios para mejorar la eficiencia logística</td>
    <td valign="top">Utilización de tecnología IA para optimizar rutas de entrega</td>
  </tr>
  <tr>
    <td valign="top">Debilidades</td>
    <td valign="top">Funcionalidades similares a la competencia en el mercado de otras plataformas de seguimiento de carga</td>
    <td valign="top">Riesgo de dependencia tecnológica y vulnerabilidades a posibles fallas del sistema</td>
    <td valign="top">Dependencia de la tecnología para la entrega de sus servicios, lo que podría resultar en vulnerabilidades si hay fallas técnicas</td>
    <td valign="top">Dependencia de la tecnología IA, lo que puede generar preocupaciones sobre la confiabilidad y la precisión de las soluciones</td>
  </tr>
  <tr>
    <td valign="top">Oportunidades</td>
    <td valign="top">Creciente demanda de transparencia en la cadena de suministro al aumentar la preocupación por la seguridad</td>
    <td valign="top">Expansión internacional para atender a mercados globales en crecimiento</td>
    <td valign="top">Posibilidad de expandir sus servicios hacia nuevos segmentos del mercado logístico</td>
    <td valign="top">Desarrollo de alianzas estratégicas con otras empresas para ofrecer soluciones integradas de logística</td>
  </tr>
  <tr>
    <td valign="top">Amenazas</td>
    <td valign="top">Creciente amenaza de ataques cibernéticos podría comprometer la seguridad de los datos almacenados en la plataforma</td>
    <td valign="top">Rápida evolución de la tecnología que requiere una continua inversión en investigación y desarrollo para mantenerse competitivo</td>
    <td valign="top">Cambios en las regulaciones gubernamentales que podrían afectar la operación de sus servicios de logística</td>
    <td valign="top">Competidores que desarrollan tecnologías similares de optimización de rutas utilizando IA</td>
  </tr>
</table>

### 2.1.2 Estrategias y tácticas frente a competidores
**Estrategias**

<u>Diferenciación del producto</u>: desarrollaremos características únicas y valor agregado para destacarnos de la competencia en el mercado de seguimiento de carga. Por ejemplo, el reporte de gastos a partir del seguimiento a tiempo real.

<u>Diversificación de servicios</u>: ampliaremos la gama de servicios ofrecidos además del seguimiento a tiempo real como el reporte de gastos y comunicación con los proveedores de servicio.

<u>Personalización de servicios</u>: ofreceremos opciones personalizadas para satisfacer necesidades específicas de los clientes dentro de los planes de pago.


**Tácticas**

<u>Implementación de retroalimentación de usuarios</u>: Analizaremos los comentarios de los usuarios para identificar áreas de mejora y priorizar el desarrollo de características que satisfagan las necesidades del mercado.

<u>Monitoreo de la competencia</u>: Realizaremos un seguimiento de las estrategias y tácticas tomadas por los competidores para evaluar oportunidades y estándares en la industria.

<u>Optimización de los motores de búsqueda</u>: Usaremos palabras clave relevantes, metatags adecuadas y contenido de calidad además de campañas de marketing en los motores de búsqueda para posicionarnos mejor y aumentar la visibilidad.

## 2.2 Entrevistas

### 2.2.1 Diseño de entevistas

__Clientes que requieren servicios de transporte__:
  * ¿Qué tan importante es el servicio de transporte para la empresa donde trabaja?

  * ¿Qué tipos de transporte son necesarios para su empresa?

  * ¿Cuál cree que son los desafíos más grandes para encontrar un buen servicio de transporte para su empresa?

  * ¿Cree que una aplicación de seguimiento en tiempo real sería útil para usted en el proceso de transporte de carga?

  * ¿Considera que una aplicación de seguimiento en tiempo real agregaría valor a su experiencia con el servicio de transporte de carga?

  * ¿Cómo cree que una aplicación de seguimiento en tiempo real podría mejorar la transparencia y la confianza en el proceso de transporte de carga?

  * ¿Estaría dispuesto a probar una aplicación de seguimiento en tiempo real si se ofreciera como parte del servicio de transporte?

  * ¿Qué características adicionales le animaría a utilizar una aplicación de seguimiento en tiempo real para gestionar sus envíos de carga?

  * ¿Cómo cree que una aplicación de seguimiento en tiempo real podría simplificar o mejorar sus operaciones logísticas?

  * ¿Qué expectativas tendría respecto al diseño y la usabilidad de una aplicación de seguimiento en tiempo real para el transporte de carga?

__Empresas de gestión de logística de transporte__:

  * ¿Hace cuánto tiempo que ofrece servicios de transporte?

  * ¿Cuáles son los principales desafíos que enfrentan al proporcionar servicios de transporte de carga?

  * ¿Qué tecnologías o herramientas utilizan actualmente para gestionar y rastrear envíos de carga?

  * ¿Cómo garantizan la transparencia y visibilidad en el proceso de transporte de carga para sus clientes?

  * ¿Qué medidas toman para optimizar la eficiencia operativa y reducir los costos en el transporte de carga?

  * ¿Cuál es su enfoque en términos de sostenibilidad y reducción de emisiones en el transporte de carga?

  * ¿Qué tipo de clientes suelen atender y cuáles son sus requisitos específicos?

### 2.2.2 Registro de entevistas

### 2.2.3 Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

### 2.3.5. As-is Scenario Mapping

__Segmento Empresas de gestión logística de transporte__

<img src="img/scenario_as-is_empresa.jpg" alt="As-is Scenario Map Empresas de gestión" width="100%">

__Segmento Clientes que requieren servicios de transporte__

<img src="img/scenario_as-is_cliente.jpg" alt="As-is Scenario Map Clientes" width="100%">

## 2.4. Ubiquitous Language



# Capítulo III Requirements Specification

## 3.1. To-Be Scenario Mapping

__Segmento Empresas de gestión logística de transporte__

<img src="img/scenario_to-be_empresa.jpg" alt="To-be Scenario Map Empresas de gestión" width="100%">

__Segmento Clientes que requieren servicios de transporte__

<img src="img/scenario_to-be_cliente.jpg" alt="To-be Scenario Map Clientes" width="100%">

## 3.2. User Stories

<u>**EPICS:**</u>

<table><tr><th valign="top"><b>Epic ID</b></th><th valign="top"><b>Epic</b></th><th valign="top"><b>User story ID</b></th><th valign="top"><b>User stories</b></th></tr>
<tr><td rowspan="5" valign="top">E01</td><td rowspan="5" valign="top">Como cliente quiero recibir alertas automáticas para tomar medidas preventivas</td><td valign="top">US01</td><td valign="top">Alertas de retraso en entrega</td></tr>
<tr><td valign="top">US02</td><td valign="top">Alertas de cambio de ruta</td></tr>
<tr><td valign="top">US03</td><td valign="top">Alertas de paradas no programadas</td></tr>
<tr><td valign="top">US04</td><td valign="top">Alertas de condiciones climáticas adversas</td></tr>
<tr><td valign="top">US05</td><td valign="top">Alertas de detención no programada</td></tr>
<tr><td rowspan="3" valign="top">E02</td><td rowspan="3" valign="top">Como cliente quiero tener información detallada de mis envíos en tiempo real para tener una visibilidad completa del proceso.</td><td valign="top">US06</td><td valign="top">Seguimiento en tiempo real de envíos</td></tr>
<tr><td valign="top">US07</td><td valign="top">Notificaciones de eventos relevantes</td></tr>
<tr><td valign="top">US08</td><td valign="top">Acceso a detalles de entrega</td></tr>
<tr><td rowspan="4" valign="top">E03</td><td rowspan="4" valign="top">Como cliente quiero acceder a un historial completo de mis envíos anteriores para gestionar mis actividades pasadas</td><td valign="top">US09</td><td valign="top">Historial de envíos</td></tr>
<tr><td valign="top">US16</td><td valign="top">Búsqueda de envíos</td></tr>
<tr><td valign="top">US17</td><td valign="top">Estadísticas de envíos</td></tr>
<tr><td valign="top">US18</td><td valign="top">Exportación del historial de envíos</td></tr>
<tr><td rowspan="3" valign="top">E04</td><td rowspan="3" valign="top">Como usuario quiero una interfaz de usuario intuitiva y fácil de usar para tener una experiencia agradable</td><td valign="top">US10</td><td valign="top">Interfaz intuitiva y fácil de usar</td></tr>
<tr><td valign="top">US19</td><td valign="top">Soporte multidispositivo y multiplataforma</td></tr>
<tr><td valign="top">US20</td><td valign="top">Personalización de visualización</td></tr>
<tr><td rowspan="5" valign="top">E05</td><td rowspan="5" valign="top">Como cliente quiero tener acceso seguro a la aplicación para poder utilizar las funcionalidades acorde a mis necesidades</td><td valign="top">US11</td><td valign="top">Registro de usuario</td></tr>
<tr><td valign="top">US12</td><td valign="top">Inicio de sesión</td></tr>
<tr><td valign="top">US13</td><td valign="top">Cierre de sesión</td></tr>
<tr><td valign="top">US14</td><td valign="top">Elegir plan de suscripción</td></tr>
<tr><td valign="top">US15</td><td valign="top">Recuperación de cuenta</td></tr>
<tr><td rowspan="6" valign="top">E06</td><td rowspan="6" valign="top">Como cliente quiero poder acceder a una Landing Page estática para conocer tanto sobre la aplicación y sus funcionalidades como la startup.</td><td valign="top">US21</td><td valign="top">NavBar y Footer</td></tr>
<tr><td valign="top">US22</td><td valign="top"><p>Página de inicio</p><p></p></td></tr>
<tr><td valign="top">US23</td><td valign="top">Sección “Acerca De”</td></tr>
<tr><td valign="top">US24</td><td valign="top">Sección “Sobre Nosotros”</td></tr>
<tr><td valign="top">US25</td><td valign="top">Sección “Características”</td></tr>
<tr><td valign="top">US26</td><td valign="top">Sección “Contacto”</td></tr>
<tr><td rowspan="4" valign="top">EP07</td><td rowspan="4" valign="top"><p>Como empresario de gestión logística quiero que la aplicación me brinde diferentes funcionalidades como seguimiento real, registrar gastos y ver el historial de envíos para poder llevar un registro eficiente</p><p></p></td><td valign="top">US27</td><td valign="top">Registro de Gastos de Viaje</td></tr>
<tr><td valign="top">US28</td><td valign="top">Registro de Datos de la Unidad</td></tr>
<tr><td valign="top">US29</td><td valign="top">Seguimiento en Tiempo Real</td></tr>
<tr><td valign="top">US30</td><td valign="top">Historial de Envíos</td></tr>
</table>

**Se presentan las siguientes user stories:**

User Story ID|Título|Descripción|Criterios de Aceptación |Relacionado con (Epic ID)|
| :- | :- | :- | :- | :- |
|US01|Alertas de Retraso en Entrega|Como cliente quiero recibir una alerta si hay un retraso en la entrega para minimizar cualquier impacto en mi operación|<p>**Escenario 01: Alerta de Retraso:**</p><p></p><p>**Dado** **que** el sistema detecta un retraso en la entrega de la mercancía</p><p>**Cuando** se activa la alerta de retraso</p><p>**Entonces** el cliente recibirá una notificación inmediata</p><p></p><p>**Escenario 02: Entrega Anticipada**</p><p></p><p>**Dado que** la entrega se realiza antes de la fecha prevista</p><p>**Cuando** el sistema detecta que la mercancía llegará antes de lo esperado.</p><p>**Entonces** el cliente recibirá una alerta</p>|E01|
|US02|Alertas de Cambio de Ruta|Como cliente, quiero ser notificado si hay un cambio en la ruta para asegurarme de que la mercancía esté en un camino seguro|<p>**Escenario 01: Alerta de Cambio de Ruta**</p><p></p><p>**Dado que** la unidad de transporte cambia su ruta planificada de manera inesperada</p><p>**Cuando** se detecta el cambio no autorizado en la ruta</p><p>**Entonces** el cliente recibirá una alerta sobre el cambio</p><p></p><p>**Escenario 02: Cambio de Ruta Autorizado**</p><p></p><p>**Dado que** la unidad de transporte necesita ajustar su ruta debido a un cierre de carretera planificado</p><p>**Cuando** se detecta el cambio en la ruta</p><p>**Y** se confirma que es necesario y autorizado</p><p>**Entonces** el cliente recibirá una alerta sobre el cambio de ruta junto con una explicación sobre la razón del cambio</p><p></p>|E01|
|US03|Alertas de Paradas No Programadas|Como cliente, necesito ser alertado si la unidad de transporte realiza paradas no programadas durante el viaje para investigar la situación y asegurarse de que no haya demoras innecesarias que puedan afectar la entrega o la integridad de la mercancía|<p>**Escenario 01: Alerta de Parada No Programada**</p><p></p><p>**Dado que** la unidad de transporte realiza una parada no programada durante el viaje</p><p>**Cuando** se detecta una parada adicional fuera de las programadas</p><p>**Entonces** el cliente recibirá una alerta sobre la parada no programada</p><p></p><p>**Escenario 02: Parada No Programada Justificada**</p><p></p><p>**Dado que** la unidad de transporte realiza una parada no programada debido a una emergencia médica del conductor.</p><p>**Cuando** se detecta la parada adicional </p><p>**Y** se verifica que es justificada</p><p>**Entonces** el cliente recibirá una alerta sobre la parada no programada.</p>|E01|
|US04|Alertas de Condiciones Climáticas Adversas|Como cliente, quiero ser informado de inmediato si el transporte se ve afectado por condiciones climáticas adversas para tomar precauciones adecuadas y asegurar de que la mercancía esté protegida durante el transporte|<p>**Escenario 01: Alerta de Condiciones Climáticas Peligrosas**</p><p></p><p>**Dado que** el transporte se ve afectado por condiciones climáticas adversas</p><p>**Cuando** se activa la alerta debido a las condiciones meteorológicas peligrosas</p><p>**Entonces** el cliente recibirá una notificación sobre las condiciones climáticas.</p><p></p><p>**Escenario 02 Condiciones Climáticas Adversas Superadas:**</p><p></p><p>**Dado que** el transporte se enfrenta a condiciones climáticas adversas durante el viaje</p><p>**Cuando** se activa la alerta debido a las condiciones meteorológicas peligrosas.</p><p>**Entonces** el cliente recibirá una notificación sobre las condiciones climáticas adversas.</p><p></p>|E01|
|US05|Alertas de Detención No Programada|Como cliente quiero ser alertado si la unidad de transporte se detiene de manera no programada durante el viaje para investigar la situación y asegurarme de que la mercancía esté protegida y en movimiento según lo planeado|<p>**Escenario 01: Alerta de Detención No Autorizada**</p><p></p><p>**Dado que** la unidad de transporte se detiene de manera no programada durante el viaje</p><p>**Cuando** se detecta la detención no autorizada</p><p>**Entonces** el cliente recibirá una alerta sobre la detención.</p><p></p><p>**Escenario 02: Sin Detenciones No Programadas**</p><p></p><p>**Dado que** la unidad de transporte no se detiene de manera no programada durante el viaje</p><p>**Cuando** no se detecta ninguna detención no autorizada</p><p>**Entonces** el cliente no recibirá ninguna alerta.</p>|E01|
|US06|Seguimiento en Tiempo Real de Envíos|Como cliente de la empresa de transporte de carga, quiero poder ingresar el número de seguimiento de mi envío en una plataforma en línea, para poder obtener actualizaciones en tiempo real sobre la ubicación y el estado de mi mercancía durante el transporte.|<p>**Escenario 1: Registro de Número de Seguimiento**</p><p></p><p>**Dado** **que** el cliente tiene acceso a la plataforma en línea,</p><p>**Cuando** ingresa el número de seguimiento del envío,</p><p>**Entonces** la plataforma procesa la información, </p><p>**Y** muestra actualizaciones en tiempo real sobre la ubicación y estado de la mercancía durante el transporte.</p><p></p><p>**Escenario 2: Acceso a Actualizaciones Continuas**</p><p></p><p>**Dado** **que** el cliente ha registrado el número de seguimiento,</p><p>**Cuando** revisa la sección de seguimiento en la plataforma,</p><p>**Entonces** encuentra actualizaciones continuas sobre la ubicación y estado de su mercancía, incluyendo hitos y estimaciones de entrega.</p><p></p>|E02|
|US07|Notificaciones de Eventos Relevantes|Como cliente de la empresa de transporte de carga, quiero recibir notificaciones automáticas sobre eventos relevantes relacionados con mi envío, para estar informado sobre el progreso de mi mercancía sin tener que realizar un seguimiento constante.|<p>**Escenario 1: Recepción de Notificación al Inicio del Transporte**</p><p></p><p>**Dado** **que** el cliente registró el envío en la plataforma,</p><p>**Cuando** comienza el transporte,</p><p>**Entonces** recibe automáticamente una notificación con detalles relevantes sobre el envío.</p><p></p><p>**Escenario 2: Notificación de Llegada a Punto de Control Importante**</p><p></p><p>**Dado que** el envío está en tránsito, <br>**Y** se habilitó las notificaciones automáticas,</p><p>**Cuando** la mercancía llega a un punto de control importante,</p><p>**Entonces** se enviará una notificación instantánea que informará sobre este evento relevante</p>|E02|
|US08|Acceso a Detalles de Entrega|Como cliente de la empresa de transporte de carga, quiero poder acceder a detalles específicos sobre la entrega de mi envío, para tener una comprensión completa del proceso de entrega.|<p>**Escenario 1: Visualización de Fecha y Hora de Entrega Programada**</p><p></p><p>**Dado** **que** el cliente sigue su envío en línea,</p><p>**Cuando** ve los detalles de su envío,</p><p>**Entonces** encuentra fácilmente la fecha y hora programadas de entrega.</p><p></p><p>**Escenario 2: Acceso a Comentarios del Transportista**</p><p></p><p>**Dado** **que** el cliente espera un envío,</p><p>**Cuando** revisa los detalles en la plataforma,</p><p>**Entonces** podrá ver comentarios del transportista.</p><p></p>|E02|
|US09|<p>Historial de Envíos</p><p></p>|Como cliente de la empresa de transporte de carga, quiero tener acceso a un historial completo de mis envíos anteriores, para poder realizar un seguimiento de las actividades de envío pasadas y planificar futuros envíos de manera más eficiente.|<p>**Escenario 1: Acceso al Historial de Envíos Anteriores**</p><p></p><p>**Dado** **que** el cliente está registrado en la plataforma,</p><p>**Cuando** accede a su cuenta,</p><p>**Entonces** ve su historial de envíos con todos los detalles.</p><p></p><p>**Escenario 2: Búsqueda y Filtrado en el Historial de Envíos**</p><p></p><p>**Dado** **que** el cliente busca un envío en su historial,</p><p>**Cuando** usa la búsqueda en la plataforma,</p><p>**Entonces** ingresa detalles como número de seguimiento o fecha para hallarlo rápido.</p><p></p>|E03|
|US10|Interfaz Intuitiva y Fácil de Usar|Como usuario, quiero una plataforma de seguimiento fácil e intuitiva, para acceder rápidamente a la información sin complicaciones.|<p>**Escenario 1: Navegación Intuitiva en la Plataforma de Seguimiento**</p><p></p><p>**Dado** **que** el usuario accede a la plataforma de seguimiento, </p><p>**Cuando** inicia sesión, **Entonces** podrá ver una interfaz clara con navegación fácil y etiquetas claras.</p><p></p><p>**Escenario 2: Acceso Rápido a la Información de Envíos**</p><p></p><p>**Dado** **que** el usuario necesita detalles de un envío,</p><p>**Cuando** accede al panel de seguimiento,</p><p>**Entonces** ve de inmediato la ubicación actual del envío y eventos importantes, sin clics o búsquedas adicionales.</p>|E04|
|US11|Registro de usuario|Como cliente quiero poder registrarme en la aplicación para tener acceso autorizado y personalizado|<p>**Escenario 1: Registro de usuario exitoso**</p><p>**Dado que** el cliente se encuentra en apartado de “Registrarse”</p><p>**Cuando** llene todo el formulario de registro con su información personal</p><p>**Y** los datos sean validados</p><p>**Entonces** la cuenta se creará correctamente</p><p>**Y** recibirá una confirmación en su correo con un enlace para verificar su cuenta.</p><p></p><p>**Escenario 2: Registro de usuario fallido**</p><p>**Dado que** el cliente se encuentra en apartado de “Registrarse”</p><p>**Cuando** llene todo el formulario de registro con información incorrecta</p><p>**Entonces** la cuenta no se creará.</p><p>**Y** se mostrará el mensaje indicando el error.</p>|E05|
|US12|Inicio de sesión|Como cliente quiero acceder a mi cuenta registrada para acceder a las funciones de la aplicación|<p>**Escenario 1: Inicio de sesión exitoso**</p><p>**Dado que** el cliente se encuentra en el apartado de “Iniciar sesión”</p><p>**Cuando** introduzca sus credenciales</p><p>**Y** los datos sean validados</p><p>**Entonces** recibirá un mensaje de bienvenida</p><p>**Y** tendrá acceso a la vista del usuario</p><p></p><p>**Escenario 2: Inicio de sesión fallido**</p><p>**Dado que** el cliente se encuentra en el apartado de “Iniciar sesión”</p><p>**Cuando** introduzca sus credenciales</p><p>**Y** los datos sean invalidados</p><p>**Entonces** no se le permitirá acceso a su cuenta.</p><p>**Y** se mostrará el mensaje indicando el error.</p>|E05|
|US13|Cierre de sesión|Como cliente quiero cerrar sesión de forma segura en cualquier momento para garantizar la seguridad y privacidad de mis datos|<p>**Escenario 1: Cierre de sesión exitoso**</p><p>**Dado que** el cliente ha iniciado sesión en la aplicación</p><p>**Cuando** se dirija al apartado de configuración</p><p>**Y** seleccione la opción “Cerrar sesión”</p><p>**Entonces** se cerrará el acceso a la cuenta</p><p>**Y** se mostrará nuevamente el apartado “Iniciar sesión”</p>|E05|
|US14|Elegir plan de suscripción|Como cliente quiero elegir un plan de suscripción que se acomode a mis necesidades para acceder a las funcionalidades necesarias para mí.|<p>**Escenario 1: Elección de plan de suscripción exitosa**</p><p>**Dado que** el cliente se ha registrado en la aplicación</p><p>**Y** se le muestre los planes de suscripción disponibles</p><p>**Cuando** elija el plan de suscripción que desea</p><p>**Y** ingrese los datos de pago</p><p>**Y** sean validados</p><p>**Entonces** se asignará el tipo de suscripción a la cuenta</p><p>**Y** se le permitirá el acceso a las funcionalidades disponibles</p><p></p><p>**Escenario 2: Elección de plan de suscripción fallida**</p><p>**Dado que** el cliente se ha registrado en la aplicación</p><p>**Y** se le muestre los planes de suscripción disponibles</p><p>**Cuando** elija el plan de suscripción que desea</p><p>**Y** ingrese los datos de pago</p><p>**Y** sean invalidados</p><p>**Entonces** no se asignará el plan de suscripción elegido</p><p>**Y** se mostrará el mensaje de error.</p>|E05|
|US15|Recuperación de cuenta|Como cliente quiero poder recuperar mi cuenta en caso haya tenido algún inconveniente con las credenciales para recuperar el acceso de forma segura.|<p>**Escenario 1: Recuperación de cuenta exitosa**</p><p>**Dado que** el cliente se encuentra en el apartado “Iniciar sesión”</p><p>**Cuando** seleccione la opción “¿Olvidó su contraseña?”</p><p>**Y** realice correctamente los pasos indicados para recuperar la cuenta.</p><p>**Entonces** recibirá una confirmación por correo</p><p>**Y** recuperará el acceso a la cuenta</p><p></p><p>**Escenario 2: Recuperación de cuenta fallida**</p><p>**Dado que** el cliente se encuentra en el apartado “Iniciar sesión”</p><p>**Cuando** seleccione la opción “¿Olvidó su contraseña?”</p><p>**Y** realice correctamente los pasos indicados para recuperar la cuenta.</p><p>**Entonces** recibirá una confirmación por correo</p><p>**Y** recuperará el acceso a la cuenta</p>|E05|
|US16|Búsqueda de envíos|Como cliente quiero poder filtrar mis envíos anteriores mediante criterios de búsqueda para encontrar la información que necesito|<p>**Escenario 1: Búsqueda por fecha**</p><p></p><p>**Dado que** un cliente está en el historial de envíos</p><p>**Y** le da a ‘Filtrar’</p><p>**Cuando** seleccione una fecha de envío</p><p>**Entonces** la plataforma muestra una lista de todos los envíos realizados en esa fecha</p><p></p><p>**Escenario 2: Búsqueda por rango de fechas**</p><p></p><p>**Dado que** un cliente está en el historial de envíos</p><p>**Y** le da a ‘Filtrar’</p><p>**Cuando** seleccione una fecha de inicio</p><p>**Y** seleccione una fecha de fin</p><p>**Entonces** la plataforma muestra una lista de todos los envíos realizados en ese rango de fechas</p>|E03|
|US17|Estadísticas de envíos|Como cliente quiero tener acceso a estadísticas sobre mis envíos previos para comprender patrones y tomar decisiones informadas|<p>**Escenario 1: Visualización de envíos por mes**</p><p></p><p>**Dado que** un cliente está en el historial de envíos</p><p>**Cuando** seleccione ‘Visualización por mes’</p><p>**Entonces** la plataforma muestra un gráfico con el número de envíos por mes</p><p></p><p>**Escenario 2: Visualización de envíos por destino**</p><p></p><p>**Dado que** un cliente está en el historial de envíos </p><p>**Cuando** seleccione ‘Visualización por destino’</p><p>**Entonces** la plataforma muestra un gráfico con el número de envíos por destino</p>|E03|
|US18|Exportación del historial de envíos|Como cliente quiero poder exportar mi historial de envíos para realizar un análisis fuera de la plataforma|<p>**Escenario 1: Exportación en formato CSV**</p><p></p><p>**Dado que** un cliente está en el historial de envíos </p><p>**Cuando** seleccione ‘Exportar historial’</p><p>**Y** elija formato CSV</p><p>**Entonces** la plataforma generará un archivo CSV con los detalles de los envíos</p><p></p><p>**Escenario 2: Exportación en formato PDF**</p><p></p><p>**Dado que** un cliente está en el historial de envíos </p><p>**Cuando** seleccione ‘Exportar historial’</p><p>**Y** elija formato PDF</p><p>**Entonces** la plataforma generará un archivo PDF con los detalles de los envíos</p>|E03|
|US19|Soporte multidispositivo y multiplataforma|Como cliente quiero acceder a la plataforma desde cualquier dispositivo o sistema operativo para una experiencia consistente|<p>**Escenario 1: Acceso en dispositivo móvil**</p><p></p><p>**Dado que** un cliente está en dispositivo móvil </p><p>**Cuando** acceda a la plataforma</p><p>**Entonces** la plataforma se adaptará al tamaño del dispositivo</p><p></p><p>**Escenario 2: Acceso desde distintos navegador web**</p><p></p><p>**Dado que** un cliente usa distintos navegadores web </p><p>**Cuando** acceda a la plataforma</p><p>**Entonces** la plataforma cargará con normalidad y con todas las funcionalidades</p>|E04|
|US20|Personalización de visualización|Como cliente, quiero personalizar la presentación de la información para que se adapte a mis preferencias|<p>**Escenario 1: Personalización de la vista**</p><p></p><p>**Dado que** un cliente accede a la plataforma</p><p>**Y** este en la configuración </p><p>**Cuando** seleccione un tipo de vista específico</p><p>**Entonces** la plataforma cambiará la disposición de los elementos para adaptarse al tipo de vista</p><p></p><p>**Escenario 2: Personalización del tema**</p><p></p><p>**Dado que** un cliente accede a la plataforma</p><p>**Y** este en la configuración </p><p>**Cuando** seleccione un tema específico</p><p>**Entonces** la plataforma cambiará los colores para adaptarse al tema</p>|E04|
|US21|NavBar y Footer|Como usuario quiero usar visualizar una barra de navegación y pie de página para navegar fácilmente a través de la página.|<p>**Escenario 1: Visualización de Navbar y Footer**</p><p>**Dado que** el usuario desea conocer sobre la aplicación</p><p>**Cuando** ingresa al Landing Page</p><p>**Entonces** se mostrará el Navbar y el Footer que permitirán al usuario navegar de forma sencilla</p>|E06|
|US22|Página de inicio|Como usuario quiero ver una página de inicio para conocer la idea principal de la aplicación.|<p>**Escenario 1: Visualización de página de inicio**</p><p>**Dado que** el usuario desea conocer sobre la aplicación</p><p>**Cuando** ingresa al Landing Page</p><p>**Entonces** se mostrará la página de inicio sencilla que comprende la idea principal.</p>|E06|
|US23|Sección “Acerca De”|Como usuario quiero ver una página “Acerca De” para conocer la problemática principal y el propósito de la aplicación.|<p>**Escenario 1: Visualización de página Acerca De**</p><p>**Dado que** el usuario desea conocer sobre el problema que resuelve la aplicación</p><p>**Cuando** ingresa al Landing Page</p><p>**Y** ingresa a la sección “Acerca De”</p><p>**Entonces** se mostrará la página Acerca De, donde se muestra la problemática que resolverá la aplicación.</p>|E06|
|US24|Sección “Sobre Nosotros”|Como usuario quiero ver una página sobre la startup para conocer el propósito de la startup que está desarrollando la aplicación.|<p>**Escenario 1: Visualización de página Sobre Nosotros**</p><p>**Dado que** el usuario desea conocer sobre la empresa</p><p>**Cuando** ingresa al Landing Page</p><p>**Y** ingresa a la sección Sobre Nosotros</p><p>**Entonces** se mostrará la página Sobre Nosotros, donde se muestra información sobre la startup, su misión y visión.</p>|E06|
|US25|Sección “Características”|Como usuario quiero ver una página “Características” para conocer las funcionalidades que brinda la aplicación.|<p>**Escenario 1: Visualización de página Características**</p><p>**Dado que** el usuario desea conocer sobre las características de la aplicación</p><p>**Cuando** ingresa al Landing Page</p><p>**Y** ingresa a la sección “Características”</p><p>**Entonces** se mostrará la página Características, donde se muestra información sobre las principales funcionalidades que brinda la aplicación.</p>|E06|
|US26|Sección “Contacto”|Como usuario quiero acceder a una página “Contacto” para conocer los medios de contacto con la empresa para realizar preguntas sobre dudas, problemas o sugerencias.|<p>**Escenario 1: Visualización de página Contacto**</p><p>**Dado que** el usuario desea contactar con el área de soporte de la startup</p><p>**Cuando** ingresa al Landing Page</p><p>**Y** ingresa a la sección “Contacto”</p><p>**Entonces** se mostrará la página Contacto, donde se muestra los medios de contacto que puede usar el usuario para realizar consultas.</p>|E06|
|US27|Registrar de Gastos de Viaje|Como empresario de gestión logística, quiero poder registrar y modificar los gastos realizados durante los viajes para mantener un registro preciso y mantener informados a mis clientes sobre los costos asociados a sus servicios.|<p>**Escenario 1: Registrar gastos de viaje**</p><p>**Dado que** el empresario necesita mantener un registro detallado de los gastos relacionados con los viajes</p><p>**Cuando** accede a la plataforma y selecciona la opción "Registro de Gastos” </p><p>**Y** registra los datos requeridos</p><p>**Y** da click en “Registrar”</p><p>**Entonces** el sistema lo verificará</p><p>**Y** le permitirá registrar información acerca de los gastos correctamente</p><p></p><p>**Escenario 2: Modificar gastos de viaje**</p><p>**Dado que** el empresario necesita actualizar un registro detallado de los gastos relacionados con los viajes</p><p>**Cuando** accede a la plataforma y selecciona la opción "Registro de Gastos”</p><p>**Y** modifica los datos</p><p>**Y** da click en “Modificar”</p><p>**Entonces** el sistema lo verificará</p><p>**Y** le permitirá modificar los gastos correctamente</p>|E07|
|US28|Registro de Datos de la Unidad|Como empresario de gestión logística, quiero registrar los datos de la unidad que realizará el servicio para demostrar transparencia y generar confianza en mis clientes.|<p>**Escenario 1: Registrar datos de la unidad**</p><p>**Dado que** el empresario desea demostrar transparencia y confianza en la prestación de servicios de transporte</p><p>**Cuando** accede a la plataforma y selecciona la sección dónde encuentra la opción "Registrar Datos de la Unidad"</p><p>**Y** registra los datos requeridos</p><p>**Y** da click en “Registrar”</p><p>**Entonces** el sistema lo verificará</p><p>**Y** le permitirá registrar información acerca de la unidad correctamente</p><p></p>|E07|
|US29|Seguimiento en Tiempo Real|Como empresario de gestión logística, quiero poder visualizar el seguimiento en tiempo real de los servicios mediante la plataforma para identificar posibles imprevistos y tomar acciones correctivas de manera oportuna.|<p>**Escenario 1: Visualización de seguimiento en tiempo real**</p><p>**Dado que** el empresario necesita supervisar el progreso de los servicios en tiempo real</p><p>**Cuando** accede a la plataforma para verificar el estado de un servicio en curso</p><p>**Y** selecciona la sección GPS para el "Seguimiento en Tiempo Real"</p><p>**Entonces** se mostrará la ubicación y ruta trazada en un mapa</p>|E07|
|US30|Historial de Envíos|Como empresario de gestión logística, quiero tener un historial de envíos para llevar un registro detallado de todos los servicios que he realizado y poder acceder a esta información en cualquier momento.|<p>**Escenario 1: Visualización de historial de envíos**</p><p>**Dado que** el empresario necesita mantener un registro de todos los servicios realizados</p><p>**Cuando** accede a la plataforma para revisar los servicios previamente realizados</p><p>**Y** selecciona la sección Historial para visualizar el "Historial de Envíos"</p><p>**Entonces** se mostrará el listado de los envíos realizados</p><p>**Y** podrá ver los detalles de cada uno</p>|E07|

## 3.3. Impact Mapping

<img src="img/impact_mapping.jpg" alt="As-is Scenario Map Empresas de gestión" width="100%">

## 3.4. Product Backlog

El Product Backlog se gestiona a través de la herramienta Pivotal Tracker, el cual se puede visualizar en el enlace URL Project Report (Github): [https://www.pivotaltracker.com/n/projects/2699736](https://www.pivotaltracker.com/n/projects/2699736)

<img src="img/pivtoal.jpg" alt="As-is Scenario Map Empresas de gestión" width="100%">

<br>

|**# Orden**|**User Story Id**|**Título**|**Descripción**|**Story Points (1/2/3/5/8)**|
| :- | :- | :- | :- | :- |
|1|US21|NavBar y Footer|Como usuario quiero usar visualizar una barra de navegación y pie de página para navegar fácilmente a través de la página.|3|
|2|US22|Página de inicio|Como usuario quiero ver una página de inicio para conocer la idea principal de la aplicación.|3|
|3|US23|Sección “Acerca De”|Como usuario quiero ver una página “Acerca De” para conocer la problemática principal y el propósito de la aplicación.|3|
|4|US24|Sección “Sobre Nosotros”|Como usuario quiero ver una página sobre la startup para conocer el propósito de la startup que está desarrollando la aplicación.|3|
|5|US25|Sección “Características”|Como usuario quiero ver una página “Características” para conocer las funcionalidades que brinda la aplicación.|3|
|6|US26|Sección “Contacto”|Como usuario quiero acceder a una página “Contacto” para conocer los medios de contacto con la empresa para realizar preguntas sobre dudas, problemas o sugerencias.|3|
|7|US06|Seguimiento en Tiempo Real de Envíos|Como cliente de la empresa de transporte de carga, quiero poder ingresar el número de seguimiento de mi envío en una plataforma en línea, para poder obtener actualizaciones en tiempo real sobre la ubicación y el estado de mi mercancía durante el transporte.|8|
|8|US07|Notificaciones de Eventos Relevantes|Como cliente de la empresa de transporte de carga, quiero recibir notificaciones automáticas sobre eventos relevantes relacionados con mi envío, para estar informado sobre el progreso de mi mercancía sin tener que realizar un seguimiento constante.|5|
|9|US08|Acceso a Detalles de Entrega|Como cliente de la empresa de transporte de carga, quiero poder acceder a detalles específicos sobre la entrega de mi envío, para tener una comprensión completa del proceso de entrega.|5|
|10|US01|Alertas de Retraso en Entrega|Como cliente quiero recibir una alerta si hay un retraso en la entrega para minimizar cualquier impacto en mi operación|5|
|11|US02|Alertas de Cambio de Ruta|Como cliente, quiero ser notificado si hay un cambio en la ruta para asegurarme de que la mercancía esté en un camino seguro|5|
|12|US03|Alertas de Paradas No Programadas|Como cliente, necesito ser alertado si la unidad de transporte realiza paradas no programadas durante el viaje para investigar la situación y asegurarse de que no haya demoras innecesarias que puedan afectar la entrega o la integridad de la mercancía|5|
|13|US04|Alertas de Condiciones Climáticas Adversas|Como cliente, quiero ser informado de inmediato si el transporte se ve afectado por condiciones climáticas adversas para tomar precauciones adecuadas y asegurar de que la mercancía esté protegida durante el transporte|5|
|14|US05|Alertas de Detención No Programada|Como cliente quiero ser alertado si la unidad de transporte se detiene de manera no programada durante el viaje para investigar la situación y asegurarme de que la mercancía esté protegida y en movimiento según lo planeado|5|
|15|US09|<p>Historial de Envíos</p><p></p>|Como cliente de la empresa de transporte de carga, quiero tener acceso a un historial completo de mis envíos anteriores, para poder realizar un seguimiento de las actividades de envío pasadas y planificar futuros envíos de manera más eficiente.|8|
|16|US16|Búsqueda de envíos|Como cliente quiero poder filtrar mis envíos anteriores mediante criterios de búsqueda para encontrar la información que necesito|5|
|17|US17|Estadísticas de envíos|Como cliente quiero tener acceso a estadísticas sobre mis envíos previos para comprender patrones y tomar decisiones informadas|5|
|18|US18|Exportación del historial de envíos|Como cliente quiero poder exportar mi historial de envíos para realizar un análisis fuera de la plataforma|8|
|19|US27|Registro de gastos de viaje|Como empresario de gestión logística, quiero poder registrar los gastos realizados durante los viajes para mantener un registro preciso y mantener informados a mis clientes sobre los costos asociados a sus servicios.|8|
|20|US28|Registro de datos de la unidad|Como empresario de gestión logística, quiero registrar los datos de la unidad que realizará el servicio para demostrar transparencia y generar confianza en mis clientes.|8|
|21|US29|Seguimiento en tiempo real|Como empresario de gestión logística, quiero poder visualizar el seguimiento en tiempo real de los servicios mediante la plataforma para identificar posibles imprevistos y tomar acciones correctivas de manera oportuna.|5|
|22|US30|Historial de envíos|Como empresario de gestión logística, quiero tener un historial de envíos para llevar un registro detallado de todos los servicios que he realizado y poder acceder a esta información en cualquier momento.|3|
|23|US10|Interfaz Intuitiva y Fácil de Usar|Como cliente, quiero una plataforma de seguimiento fácil e intuitiva, para acceder rápidamente a la información sin complicaciones.|5|
|24|US19|Soporte multidispositivo y multiplataforma|Como cliente quiero acceder a la plataforma desde cualquier dispositivo o sistema operativo para una experiencia consistente|8|
|25|US20|Personalización de visualización|Como cliente, quiero personalizar la presentación de la información para que se adapte a mis preferencias|8|
|26|US11|Registro de usuario|Como cliente quiero poder registrarme en la aplicación para tener acceso autorizado y personalizado|3|
|27|US12|Inicio de sesión|Como cliente quiero acceder a mi cuenta registrada para acceder a las funciones de la aplicación|3|
|28|US13|Cierre de sesión|Como cliente quiero cerrar sesión de forma segura en cualquier momento para garantizar la seguridad y privacidad de mis datos|2|
|29|US14|Elegir plan de suscripción|Como cliente quiero elegir un plan de suscripción que se acomode a mis necesidades para acceder a las funcionalidades necesarias para mí.|5|
|30|US15|Recuperación de cuenta|Como cliente quiero poder recuperar mi cuenta en caso haya tenido algún inconveniente con las credenciales para recuperar el acceso de forma segura.|5|

# Capítulo IV Product Design

# Capítulo V Product Implementation, Validation & Deployment
