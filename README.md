
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

  * ¿Considera que esta aplicación agregaría valor a su experiencia con el servicio de transporte de carga?

  * ¿Cómo cree que esta aplicación podría mejorar la transparencia y la confianza en el proceso de transporte de carga?

  * ¿Estaría dispuesto a probar una aplicación de seguimiento en tiempo real si se ofreciera como parte del servicio de transporte?

  * ¿Qué características adicionales le animaría a utilizar una aplicación de seguimiento en tiempo real para gestionar sus envíos de carga?

  * ¿Cómo cree que esta aplicación podría simplificar o mejorar sus operaciones logísticas?

  * ¿Qué expectativas tendría respecto al diseño y la usabilidad de la aplicación?

__Empresas de gestión de logística de transporte__:

  * ¿Hace cuánto tiempo que ofrece servicios de transporte?

  * ¿Cuáles son los principales desafíos que enfrentan al proporcionar servicios de transporte de carga?

  * ¿Qué tecnologías o herramientas utilizan actualmente para gestionar y rastrear envíos de carga?

  * ¿Cómo garantizan la transparencia y visibilidad en el proceso de transporte de carga para sus clientes?

  * ¿Qué medidas toman para optimizar la eficiencia operativa y reducir los costos en el transporte de carga?

  * ¿Cuál es su enfoque en términos de sostenibilidad y reducción de emisiones en el transporte de carga?

  * ¿Qué tipo de clientes suelen atender y cuáles son sus requisitos específicos?
  
  * ¿Cómo manejan las situaciones de emergencia o imprevistos durante el transporte de carga?
  
  * ¿Cuáles son los criterios que utilizan para evaluar y seleccionar socios o proveedores en su cadena de suministro?


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

## 3.3. Impact Mapping

## 3.4. Product Backlog

# Capítulo IV Product Design

# Capítulo V Product Implementation, Validation & Deployment
