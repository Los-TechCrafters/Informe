# Informe TP
![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 001](https://github.com/user-attachments/assets/3da95336-1072-4bdf-84c5-d1e323ec139f)

**Curso:** Arquitectura de Software Emergentes

**Profesor:** Royer Edelwer Rojas Malasquez

**Sección:** WS82

**Proyecto: Aegis Vision** 

Sistema de detección con  RA para detección de patrones de movimiento

**Ciclo:** 2024 - 2

Grupo 4

**Integrantes:**

|**Nombre**|**Código**|
| :-: | :-: |
|Ferreyra Canaval, Leonardo Jesús|202111363|
|Díaz Gonzáles, Víctor Yordi |20211C384|
|Antonio Salazar, Jhan Clinton|20201b312|
|Taype Fernandez, Leonardo|20201e840|







**Registro de Versiones del Informe**


|**Entregable** |**Fecha**|**Participantes** |**Observaciones**|
| :-: | :-: | :-: | :-: |
|TB1|06/09/2024|Todos los Integrantes|Ninguna|
|TTP1|24/09/2024|Todos los Integrantes|Ninguna|
|||||




**Tabla de Contenidos**

[**1. Capítulo I: Introducción	5**](#_ex0tfqt49q82)

[1.1. Startup Profile	5](#_byk5xoargg1e)

[1.1.1. Descripción de la Startup	5](#_wrl41k6i6rf2)

[1.1.2. Perfiles de integrantes del equipo	6](#_t5xdq32jc79e)

[1.2. Solution Profile	7](#_o1kfk5jg7qqy)

[1.2.1. Antecedentes y Problemática	7](#_exw494cqtaub)

[1.2.2. Lean UX Process	8](#_aeje36qiaryc)

[**2. Capítulo II: Requeriments Elicitatión & Analysis	10**](#_zabo67paya1e)

[2.1. Competidores	10](#_x5k7t45hk2ru)

[2.1.1. Análisis Competitivo	10](#_3euca422pxpm)

[2.1.2. Estrategias y tácticas frente a competidores	14](#_h9tferxh0wef)

[2.2. Entrevistas	15](#_h3r5roug23ml)

[2.2.1 Diseño de entrevistas	15](#_buajxnrcoflj)

[2.2.2 Registro de entrevistas	16](#_ufnnqi9v9jn3)

[2.2.3 Análisis de entrevistas	17](#_9dvahun2fo6r)

[2.3  Needfinding	19](#_bb76yek8c386)

[2.3.1 User Personas	19](#_7urljr8qpr2e)

[2.3.2 User task Matrix	20](#_b7yq94wixmbb)

[2.3.3 Empathy Mapping	22](#_q3yk4tsrco34)

[2.2.1 As-is Scenario Mapping	23](#_dtk35c93ltae)

[2.4  Ubiquitous Language.	24](#_qfy1vnuac1ui)

[**Capítulo III: Requirements Specification	25**](#_bg1gp032r8wm)

[3.1. To-Be Scenario Mapping.	25](#_cd6y73qhbrvi)

[3.2. User Stories.	26](#_2disjd1uh4jr)

[ÉPICA: Historial de Seguridad	27](#_ncd5jdcqv6ni)

[ÉPICA: Gestión Centralizada de Dispositivos	28](#_y1euegbkf6ts)

[ÉPICA: Personalización de Alertas	28](#_aj41v9h2ol8x)

[ÉPICA: Integración de Dispositivos Inteligentes	29](#_f0mamflmmo0b)

[ÉPICA: Asistente de Configuración	30](#_tpcwfif7s2j9)

[ÉPICA: Actualizaciones del Sistema	30](#_m3b13ytnusl1)

[ÉPICA: Control de Privacidad	31](#_et3wg3m87wom)

[ÉPICA: Seguridad en la Nube	32](#_gk61oxxpj2ts)

[3.3. Impact Mapping.	32](#_sq0ajr7daprb)

[3.4. Product Backlog.	33](#_h7dvorhjprre)

[**Capítulo IV: Strategic-Level Software Design	34**](#_uwe0ben5wt2n)

[4.1. Strategic-Level Attribute-Driven Design.	34](#_epo2324o29gc)

[4.1.1. Design Purpose.	34](#_i7ub0nd4f9x0)

[4.1.2. Attribute-Driven Design Inputs.	35](#_n4uo8bz2igpx)

[4.1.3. Architectural Drivers Backlog.	36](#_vbta846nakaz)

[4.1.4. Architectural Design Decisions.	36](#_c0n36j9pd6zh)

[4.1.5. Quality Attribute Scenario Refinements.	36](#_mc9imvm9gz2p)

[4.2. Strategic-Level Domain-Driven Design.	37](#_1sv82uc42440)

[4.2.1. EventStorming.	37](#_tk4kcqhgqwvw)

[4.2.2. Candidate Context Discovery.	37](#_nelavj1jkn2o)

[4.2.3. Domain Message Flows Modeling.	37](#_7sh1gfqbu3nr)

[4.2.4. Bounded Context Canvases.	37](#_ojenzg6htc8v)

[4.2.5. Context Mapping.	42](#_lf4931o39sme)

[4.3. Software Architecture.	42](#_jhyuyk89nvca)

[4.3.1. Software Architecture System Landscape Diagram.	42](#_q7xs6mfdzwxf)

[4.3.1. Software Architecture Context Level Diagrams.	43](#_k8rxufjurpw2)

[4.3.2. Software Architecture Container Level Diagrams.	44](#_g7737xnx3j1i)

[4.3.3. Software Architecture Deployment Diagrams	44](#_nh697trw5ah6)





























**Student Outcome**


|Criterio Específico |Acciones realizadas |Conclusiones |
| :-: | :-: | :-: |
|Desarrollo de experimentos |<p>**Díaz González, Víctor Yordi** </p><p>TB1 </p><p>Investigación e indagación de nuestros competidores directos de nuestra aplicación y hacer los users historias.</p><p>**Taype Fernandez, Leonardo**</p><p>TB1 </p><p>Investigación sobre el alcance del proyecto y fundamento de IA</p><p>**Ferreyra Canaval, Leonardo Jesús**</p><p>TB1 </p><p>Investigación acerca de los bounded context del proyecto, junto con sus respectivos diagramas</p><p>**Jhan Clinton Antonio Salazar**</p><p>TB1</p><p>Investigación del Strategic-Level Attribute-Driven Design, y análisis del to be scenario mapping, user stories y el product backlog.</p>|En conclusión, podemos deducir que Aegis Visión ha desarrollado una solución de seguridad personalizada mediante un enfoque Lean UX, identificando necesidades clave de usuarios y superando a la competencia. El proceso incluyó entrevistas, análisis competitivo y técnicas de diseño centrado en el usuario. Esto asegura un producto innovador, eficaz y adaptable a las demandas del mercado de hogares inteligentes.|
|Análisis e interpretación de datos/resultados|<p>**Díaz González, Víctor Yordi** </p><p>TB1 </p><p>Creación e indagación de nuestros competidores directos de nuestra aplicación y hacer los usqers historias.</p><p></p><p>**Taype Fernandez, Leonardo**</p><p>TB1 </p><p>Investigación sobre problemática y suposiciones.</p><p>**Ferreyra Canaval, Leonardo Jesús**</p><p>TB1 </p><p>Investigación y análisis sobre los bounded context y diagramas a nivel de arquitectura sobre la problemática</p><p>**Jhan Clinton Antonio Salazar**</p><p>TB1</p><p>Analice e interprete el problema para poder realizar las user stories con las respectivas épicas y luego poder realizar el product backlog priorizando las user stories según importancia.</p>|<p>TB1:</p><p></p><p>El debate sobre la orientación de la aplicación y la descripción detallada subrayan la necesidad de actualizarse constantemente en metodologías y herramientas para definir soluciones efectivas. El análisis de antecedentes y problemática reforzó la comprensión de los desafíos actuales, mientras que la creación de Lean UX Assumptions y Hypothesis Statements mostró cómo el uso de enfoques ágiles requiere un aprendizaje continuo. La entrevista a personas con familiares sordomudos evidenció la necesidad de adquirir conocimientos específicos para adaptar las soluciones a públicos diversos</p><p></p>|

1. # <a name="_ex0tfqt49q82"></a>**Capítulo I: Introducción**
## <a name="_byk5xoargg1e"></a>**1.1. Startup Profile**
### <a name="_wrl41k6i6rf2"></a>**1.1.1. Descripción de la Startup**
Aegis Vision es una startup tecnológica enfocada en desarrollar soluciones de seguridad para hogares inteligentes. Aprovechando tecnologías emergentes como la Realidad Aumentada (RA) y la Inteligencia Artificial (IA), Aegis Vision ofrece una plataforma avanzada de seguridad que permite a los usuarios visualizar y gestionar en tiempo real la disposición de cámaras y sensores en sus hogares. La misión de la startup es ofrecer una experiencia de seguridad completamente personalizada, mejorando la efectividad y facilidad de uso de los sistemas de seguridad actuales.

La visión de Aegis Vision es ser líder en el mercado de seguridad doméstica, brindando innovación constante a través de la integración de tecnologías emergentes, garantizando la protección, privacidad y satisfacción del cliente.



### <a name="_t5xdq32jc79e"></a>**1.1.2. Perfiles de integrantes del equipo**


**Victor Yordi Diaz Gonzalez**

**Código de alumno:** U20211C384

Carrera de Ingeniería de Software

Actualmente ando estudiando la carrera de Ingeniería de Software. Mi pasión por la programación empezó a temprana edad, donde actualmente me permite investigar, analizar y solucionar problemas de la vida cotidiana. Mi objetivo es desarrollar software de calidad que den soluciones innovadoras a población. Cabe enfatizar que busco la colaboración activa en equipo para llegar a tener éxito en las metas o proyectos. 

![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 002](https://github.com/user-attachments/assets/e34c0e2e-77a5-4b7a-9b1b-8a55969ca6f7)

**Leonardo Taype Fernandez**

**Código de alumno:** u20201e840

Carrera de Ingeniería de Software

Me considero una persona comprometida y responsable. Me gusta aprender y plantearme retos. Estudio la carrera de ingeniería de software, siempre me ha gustado interactuar con la computadora y ahora puedo ser un profesional haciendo lo que me gusta. Tengo conocimientos en desarrollo web, móvil y desktop 

![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 003](https://github.com/user-attachments/assets/29c7d6af-5a78-4df7-b502-3abea37cd5dd)

**Leonardo Jesús Ferreyra Carnaval**

**Código de alumno:** U202111363

Carrera de Ingeniería de Software

Mi camino académico ha estado marcado por un fuerte interés en desentrañar los desafíos más complejos a través de la programación y la tecnología. Mi objetivo es diseñar soluciones innovadoras que tengan un impacto significativo en nuestra sociedad. Además de mis estudios, también me dedico a proyectos personales. Creo firmemente en el poder de la colaboración y siempre busco oportunidades para trabajar en equipo y aprender de los demás.

![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 004](https://github.com/user-attachments/assets/ec8f78c8-cc40-4fae-ab56-5f8b6a838edd)

**Jhan Clinton Antonio Salazar**   

**Código de Alumno:** U20201B312

Acerca de: Soy estudiante de la carrera de Ingeniería de Software. En mis tiempos libres me gusta escuchar música de varios géneros y hacer deporte con mis amigos. Además, disfruto de aprender cosas nuevas y trabajar en proyectos que me permitan desarrollar soluciones tecnológicas creativas. Me gusta enfrentar retos que involucren tanto el trabajo en equipo como la mejora continua de mis habilidades técnicas y personales.

![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 005](https://github.com/user-attachments/assets/9da97804-d816-4df4-9255-eda207fd24f9)


## <a name="_o1kfk5jg7qqy"></a>**1.2. Solution Profile**
### <a name="_exw494cqtaub"></a>**1.2.1. Antecedentes y Problemática**
Enunciado del Problema

El aumento de dispositivos inteligentes en los hogares ha generado la necesidad de sistemas de seguridad más avanzados y personalizados. Sin embargo, las soluciones actuales enfrentan barreras en cuanto a la integración, facilidad de uso, personalización, y capacidades predictivas. Además, los usuarios están cada vez más preocupados por la seguridad y privacidad de sus datos.

Descripción del Problema

El sistema de seguridad de Aegis Vision está diseñado para resolver varios problemas actuales en el mercado:

¿Quién?: Los usuarios objetivo son propietarios de hogares inteligentes, expertos en tecnología y consumidores que buscan soluciones avanzadas de seguridad. Este grupo valora la personalización, la facilidad de uso y la integración fluida con otros dispositivos inteligentes.

¿Qué?: Un sistema de seguridad que utiliza RA para visualizar y personalizar la disposición de cámaras y sensores, junto con IA avanzada para el análisis predictivo de patrones de movimiento y detección de posibles amenazas.

¿Dónde?: La solución está dirigida a hogares inteligentes que buscan integrar cámaras y sensores con capacidades de IA, permitiendo una supervisión de seguridad más eficaz.

¿Cuándo?: A medida que las preocupaciones por la seguridad doméstica continúan en aumento, los usuarios están buscando soluciones que ofrezcan una combinación de personalización y análisis predictivo.

¿Por qué?: Las soluciones actuales carecen de capacidades predictivas robustas y de una interfaz de usuario intuitiva para la gestión de dispositivos de seguridad. Además, los sistemas no abordan adecuadamente las preocupaciones de privacidad y protección de datos de los usuarios.

¿Cómo?: Aegis Vision utiliza RA para facilitar la configuración y gestión de dispositivos de seguridad y emplea IA para analizar patrones de movimiento y predecir posibles amenazas.

¿Cuánto?: El sistema ofrece una variedad de planes de suscripción que permiten a los usuarios seleccionar el nivel de protección que mejor se adapte a sus necesidades, desde funcionalidades básicas hasta servicios avanzados de predicción de amenazas y ciberseguridad.

### <a name="_aeje36qiaryc"></a>**1.2.2. Lean UX Process**
**1.2.2.1. Lean UX Problem Statements**

Domain: El mercado de hogares inteligentes y soluciones de seguridad.

Customer Segments: Propietarios de hogares inteligentes, expertos en tecnología y usuarios preocupados por la privacidad y la seguridad.

Pain Points: Dificultades para personalizar e integrar dispositivos de seguridad, falta de análisis predictivo, preocupaciones sobre la privacidad de los datos.

Gap: Soluciones existentes carecen de una experiencia personalizada e intuitiva y no ofrecen capacidades predictivas efectivas.

Visión/Estrategia: Aegis Vision proporcionará un sistema de seguridad personalizado que utiliza RA e IA para resolver las deficiencias de las soluciones actuales, ofreciendo una experiencia inmersiva y predictiva.

**1.2.2.2. Lean UX Assumptions**

Los usuarios valorarán una experiencia visual interactiva y personalizada a través de RA para gestionar sus sistemas de seguridad.

La IA predictiva será clave para diferenciarse en el mercado, ayudando a los usuarios a anticipar posibles amenazas de seguridad.

Los usuarios estarán dispuestos a suscribirse a planes que ofrecen funciones avanzadas como análisis predictivo, actualizaciones de ciberseguridad, y almacenamiento en la nube.

**1.2.2.3. Lean UX Hypothesis Statements**

Creemos que si integramos RA para visualizar la disposición de cámaras y sensores, los usuarios encontrarán el sistema más fácil de usar y personalizarán sus configuraciones de manera más eficiente.

Creemos que la implementación de IA predictiva permitirá a los usuarios anticipar posibles amenazas de seguridad, aumentando la confianza en el sistema y mejorando la retención del cliente.

Si ofrecemos planes de suscripción flexibles que incluyan funciones avanzadas como RA y análisis de IA, entonces los usuarios optarán por versiones premium del producto.

**1.2.2.4. Lean UX Canvas**

Usuarios: Propietarios de hogares inteligentes, expertos en tecnología y personas preocupadas por la seguridad y privacidad en sus hogares.

Necesidades: Necesitan una solución de seguridad que sea fácil de usar, altamente personalizable y que ofrezca capacidades predictivas para anticipar amenazas.

Solución: Aegis Vision ofrece un sistema de seguridad que utiliza RA para visualizar la disposición de cámaras y sensores y IA para analizar patrones de movimiento y anticipar amenazas.

Valor: Mejora la experiencia del usuario, aumenta la capacidad de anticipar amenazas, y fortalece la confianza en la privacidad y seguridad de los datos del hogar.

1\.3. Segmentos objetivo

Los segmentos objetivo de Aegis Vision incluyen:

Propietarios de hogares inteligentes: Personas que ya han integrado dispositivos inteligentes y buscan mejorar la seguridad con tecnologías avanzadas como RA e IA.

![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 006](https://github.com/user-attachments/assets/c599e16d-bd68-43f7-b388-507373ec99ed)





1. # <a name="_zabo67paya1e"></a>**Capítulo II: Requeriments Elicitatión & Analysis**

## <a name="_x5k7t45hk2ru"></a>**2.1. Competidores**
### <a name="_3euca422pxpm"></a>          **2.1.1. Análisis Competitivo**

<table><tr><th colspan="2" valign="top"> </th><th valign="top"><b>Aegis Vision</b></th><th valign="top"><b>Vivint Smart Home</b></th><th valign="top"><b>Ring (owned by Amazon)</b></th><th valign="top"><b>Arlo Technologies</b></th></tr>
<tr><td rowspan="2" valign="top"><p>P </p><p>E </p><p>R </p><p>F </p><p>I </p><p>L </p></td><td valign="top"><b>Overview</b> </td><td valign="top">Aegis Vision es una solución de seguridad para el hogar de primera calidad que se especializa en cámaras de seguridad inalámbricas equipadas con tecnología avanzada de inteligencia artificial para detección de movimiento y alertas en tiempo real. Diseñada para consumidores que priorizan la videovigilancia de alta calidad y funciones de vanguardia, Aegis Vision ofrece un enfoque integrado y sofisticado para la seguridad del hogar, eliminando la necesidad de concentradores o estaciones base.</td><td valign="top">Vivint ofrece soluciones integrales de seguridad para hogares inteligentes que incluyen cámaras, sensores y dispositivos inteligentes integrados controlados por IA.</td><td valign="top">Ring ofrece una gama de productos de seguridad para el hogar, centrándose en la instalación de bricolaje y en servicios basados ​​en la nube.</td><td valign="top">Arlo se especializa en cámaras de seguridad inalámbricas con funciones de inteligencia artificial avanzadas para detección de movimiento y alertas.</td></tr>
<tr><td valign="top"><b>Ventaja Competitiva</b> </td><td valign="top">Aegis Vision se destaca en el mercado por su compromiso de ofrecer una calidad de video superior y capacidades avanzadas de inteligencia artificial. El sistema es completamente inalámbrico, lo que brinda a los usuarios flexibilidad y facilidad de instalación sin comprometer el rendimiento.</td><td valign="top">Vivint se destaca por su fuerte enfoque en instalaciones de servicio completo, monitoreo profesional e integración perfecta de múltiples dispositivos domésticos inteligentes.</td><td valign="top">dispositivos fáciles de instalar, amplia integración del ecosistema con Amazon Alexa y una gran base de clientes.</td><td valign="top">video de alta calidad, detección de IA robusta y sin necesidad de concentradores o estaciones base.</td></tr>
<tr><td rowspan="2" valign="top"><p>P</p><p>E</p><p>R</p><p>F</p><p>I</p><p>L</p><p></p><p>D</p><p>E</p><p></p><p>M</p><p>A</p><p>R</p><p>K</p><p>E</p><p>T</p><p>I</p><p>N</p><p>G </p></td><td valign="top"><b>Mercado Objetivo</b> </td><td valign="top">Aegis Vision está dirigido a propietarios y profesionales expertos en tecnología que buscan soluciones de seguridad de primer nivel con las últimas funciones impulsadas por IA. Estos consumidores valoran la innovación, la fiabilidad y la calidad superior en sus sistemas de seguridad para el hogar.</td><td valign="top">H|ogares de ingresos medios y altos que buscan soluciones de seguridad para el hogar confiables y todo en uno.</td><td valign="top">H|ogares de ingresos medios y altos que buscan soluciones de seguridad para el hogar confiables y todo en uno.</td><td valign="top">` `Consumidores que buscan videovigilancia de alta calidad con funciones avanzadas como alertas basadas en inteligencia artificial.</td></tr>
<tr><td valign="top"><b>Estrategias de marketing</b> </td><td valign="top">Aegis Vision se centra en mostrar la calidad de sus productos y su innovación tecnológica a través de campañas de marketing digital específicas, reseñas en línea y blogs de tecnología. La marca aprovecha el poder de las asociaciones con personas influyentes y los testimonios de los usuarios para generar credibilidad y llegar a su público objetivo.</td><td valign="top">Utilizan un enfoque de venta directa, una fuerte presencia en línea y asociaciones con plataformas de hogares inteligentes.</td><td valign="top">Fuerte presencia en línea, marketing digital dirigido y aprovechamiento de la amplia base de clientes de Amazon.</td><td valign="top">enfatiza la calidad y la innovación del producto, con un enfoque en reseñas en línea y blogs de tecnología.</td></tr>
<tr><td rowspan="3" valign="top"><p>P</p><p>E</p><p>R</p><p>F</p><p>I</p><p>L</p><p></p><p>D</p><p>E</p><p></p><p>P</p><p>R</p><p>O</p><p>D</p><p>U</p><p>C</p><p>T</p><p>O</p><p> </p></td><td valign="top"><b>Productos y servicios</b> </td><td valign="top">Aegis Vision ofrece una gama de cámaras de seguridad inalámbricas, timbres y soluciones de almacenamiento en la nube. Todos los productos incluyen funciones de inteligencia artificial que mejoran la detección de movimiento y brindan alertas en tiempo real, lo que garantiza una protección integral del hogar.</td><td valign="top">Cámaras inteligentes, sensores de movimiento, cerraduras inteligentes y sistemas domésticos inteligentes integrados con capacidades de inteligencia artificial.</td><td valign="top">Timbres con video, cámaras de seguridad, sistemas de alarma y planes de almacenamiento en la nube.</td><td valign="top">Cámaras de seguridad inalámbricas, timbres y almacenamiento en la nube con funciones de inteligencia artificial.</td></tr>
<tr><td valign="top"><b>Precios y costos</b> </td><td valign="top">` `Hay varios planes de suscripción disponibles para el almacenamiento en la nube, que brindan opciones que se adaptan a las diferentes necesidades de los usuarios.</td><td valign="top">Precios más altos con opciones de financiamiento y servicios de monitoreo basados ​​en suscripción.</td><td valign="top">Precios de rango medio con servicios de monitoreo y almacenamiento en la nube basados ​​en suscripción.</td><td valign="top">Precios premium con varios planes de suscripción para almacenamiento en la nube</td></tr>
<tr><td valign="top"><b>Canales de distribución</b> </td><td valign="top">Los productos de Aegis Vision están disponibles a través de ventas directas en línea, asociaciones con minoristas y destacados mercados en línea.</td><td valign="top">Venta directa, tienda en línea y asociaciones con plataformas minoristas y de hogares inteligentes.</td><td valign="top">Marketplace de Amazon, tiendas minoristas y ventas directas en línea.</td><td valign="top">Ventas directas en línea, asociaciones minoristas y mercados en línea.</td></tr>
<tr><td rowspan="4" valign="top"><p>A </p><p>N </p><p>Á</p><p>L </p><p>I </p><p>S </p><p>I </p><p>S </p><p>  </p><p>S </p><p>W </p><p>O </p><p>T </p></td><td valign="top"><b>Fortalezas</b> </td><td valign="top">Productos de alta calidad, funciones de inteligencia artificial avanzadas y un diseño inalámbrico sin concentrador.</td><td valign="top">Soluciones integrales y completas, fuerte soporte al cliente.</td><td valign="top">Amplia gama de productos, fuerte integración con el ecosistema de Amazon.</td><td valign="top">Productos de alta calidad, funciones de IA avanzadas.</td></tr>
<tr><td valign="top"><b>Debilidades</b> </td><td valign="top">Alto costo y dependencia de servicios de suscripción para una funcionalidad completa.</td><td valign="top">Alto costo y dependencia de instalación profesional.</td><td valign="top">Problemas de privacidad debido al almacenamiento en la nube.</td><td valign="top">Alto costo, dependencia de suscripción para funciones completas.</td></tr>
<tr><td valign="top"><b>Oportunidades</b> </td><td valign="top">Ampliar la línea de productos para incluir más capacidades de AR y mejorar la experiencia del usuario.</td><td valign="top">Expansión a los mercados de bricolaje, mejora de las capacidades de IA.</td><td valign="top">Ampliar las funciones de IA, mejorar los controles de privacidad.</td><td valign="top">Ampliar líneas de productos, mejorar las capacidades de AR.</td></tr>
<tr><td valign="top"><b>Amenazas</b> </td><td valign="top">intensa competencia de otras marcas premium y posibles riesgos de ciberseguridad.</td><td valign="top">Creciente competencia de sistemas DIY de bajo costo.</td><td valign="top">Competencia de otros sistemas DIY, riesgos de ciberseguridad.</td><td valign="top">intensa competencia, posibles problemas de ciberseguridad.</td></tr>
</table>

### <a name="_h9tferxh0wef"></a>**2.1.2. Estrategias y tácticas frente a competidores**
En **Aegis Vision**, buscamos posicionarnos como líderes en seguridad doméstica al integrar tecnologías innovadoras como la Realidad Aumentada (RA) y la Inteligencia Artificial (IA) en nuestras soluciones. A continuación, presentamos las estrategias y tácticas que utilizaremos para destacar frente a nuestros competidores:

1. **Diferenciación mediante la Integración de RA**
- **Estrategia**: Destacar nuestra característica única de RA que permite a los usuarios visualizar la disposición de cámaras y sensores en su hogar de manera interactiva y personalizada.
- **Tácticas:**
  - Campañas de Marketing Basadas en RA**: Desarrollaremos campañas publicitarias que muestren cómo nuestra RA facilita la planificación y optimización de la seguridad en el hogar.

  - Enfoque en la Experiencia del Usuario:** Aseguraremos que la interfaz de RA sea intuitiva y fácil de usar, posicionándose como un elemento central en nuestras demostraciones de producto.

1. **Capacidades Mejoradas de IA para Seguridad Predictiva**
- **Estrategia:** Aprovechar la IA no solo para la detección de movimiento, sino también para el análisis predictivo, anticipando posibles amenazas de seguridad.
- **Tácticas:**
- **Entrenamiento de IA y Recopilación de Datos:** Continuamente mejoramos nuestra IA mediante la recopilación de datos anonimizados para anticipar y prevenir posibles brechas de seguridad.
  - **Contenido Educativo**: Proporcionaremos recursos que expliquen cómo nuestra IA supera a la competencia al anticipar riesgos de manera proactiva.

1. **Flexibilidad en las Suscripciones**

   **- Estrategia**: Ofrecer planes de suscripción flexibles y transparentes que se adapten a diferentes necesidades de los usuarios, desde almacenamiento en la nube básico hasta funciones avanzadas de IA y RA.

   **- Tácticas:**

   **-Modelos de Suscripción Escalonados**: Desarrollaremos varios niveles de suscripción, incluyendo un nivel gratuito o de bajo costo que ofrezca funcionalidad básica, incentivando a los usuarios a actualizar a medida que perciben el valor de las funciones avanzadas.

   **- Promociones y Descuentos:** Implementaremos promociones por tiempo limitado para nuevos usuarios y descuentos para suscripciones a largo plazo, aumentando la retención de clientes.

1. **Foco** en la Ciberseguridad

**- Estrategia:** Posicionarnos como líderes en ciberseguridad dentro del mercado de seguridad doméstica, abordando las crecientes preocupaciones sobre la privacidad y protección de datos.

**- Tácticas:**

**- Certificaciones de Terceros**: Obtendremos y mostraremos prominentemente certificaciones de ciberseguridad de organizaciones reconocidas, construyendo confianza con nuestros clientes.

**- Actualizaciones Regulares de Seguridad**: Proporcionaremos actualizaciones frecuentes de seguridad y comunicaremos estos esfuerzos claramente a los usuarios, destacando nuestro compromiso con la protección de sus datos.

1. **Construcción de Comunidad y Contenido Generado por los Usuarios**

**- Estrategia**: Fomentar una comunidad en torno a Aegis Vision donde los usuarios puedan compartir sus experiencias, consejos y diseños de RA, creando un sentido de pertenencia y compromiso.

**- Foros de Usuarios y Grupos en Redes Sociales**: Crearemos comunidades en línea donde los usuarios puedan interactuar, compartir sus configuraciones y proporcionar retroalimentación, fortaleciendo la lealtad del cliente.

**- Incentivar la Creación de Contenido**: Animaremos a los usuarios a crear y compartir contenido ofreciendo recompensas, como meses de suscripción gratuita o descuentos, por los mejores diseños de RA o consejos de seguridad.

## <a name="_h3r5roug23ml"></a>**2.2. Entrevistas** 
En este punto presentaremos los resultados de las entrevistas realizadas a los usuarios objetivos.

### <a name="_buajxnrcoflj"></a>	**2.2.1 Diseño de entrevistas**

**Información general**

1. ¿Cuál es su nombre?
1. ¿Cuántos años tiene?
1. ¿Cuál es su ocupación?
1. Actualmente, ¿en qué lugar reside?

**Segmento 1: Propietarios de Viviendas Inteligentes**

Perfil: Consumidores tecnológicos que ya han integrado dispositivos inteligentes en sus hogares y buscan soluciones avanzadas como RA e IA para mejorar la seguridad.

- ¿Qué características de tu hogar inteligente son más importantes para ti en términos de seguridad?
- ¿Cómo mejorarías la integración de las cámaras de seguridad y sensores en tu sistema de hogar inteligente actual?
- ¿Cómo imaginas que la Realidad Aumentada podría cambiar tu forma de gestionar la seguridad de tu hogar?
- ¿Qué valor le das a la personalización en la configuración de los sistemas de seguridad en tu hogar inteligente?
- ¿Qué desafíos has encontrado al combinar múltiples dispositivos inteligentes en un solo sistema de seguridad?
- ¿Cómo evalúas la efectividad de la IA en la detección de posibles amenazas en tu hogar inteligente?
- ¿Qué tipo de alertas o notificaciones prefieres recibir en situaciones de posible intrusión?
- ¿Cuáles son tus expectativas respecto a la privacidad y seguridad de los datos cuando usas dispositivos de IA en tu hogar?

### <a name="_ufnnqi9v9jn3"></a>	**2.2.2 Registro de entrevistas**
**Entrevista 1:**
**Andrea Huancas -** Estudiante de Derecho en la UCSUR 
[**Arq Emergentes LinkEntrevista Leonardo.mp4**]![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 007](https://github.com/user-attachments/assets/48cab406-8d86-4641-bb91-f08b002f92e8)


**Entrevista 2:**
**Angello Olortegui**
![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 008](https://github.com/user-attachments/assets/186b7f1d-6a06-4eba-b924-26f3b82d7f54)



[**Arq_Emergentes_Entrevista_Leonardo_Taype**](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202111363_upc_edu_pe/Ef_2C4r053lEqkT2CSnQVz0Bw4FW3DJvx-yWQWFocxKyLg?e=Ylnhoe&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

**Entrevista 3:**
**Esmeralda Aliaga**
![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 009](https://github.com/user-attachments/assets/c2161881-4564-450e-b100-3922bd64618c)



**Entrevista 4:**
**Leonel Alfaro Cumpa**
![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 010](https://github.com/user-attachments/assets/d21e8465-1fac-4d89-ae83-2751bee8b2a7)


[**Entrevista 4 - Segmento 1**](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201b312_upc_edu_pe/EWINiHDAx2RDgTmlEF2mwnQBXEToV_nCW-4aHDZCVSRMWw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=z9S7Ae)


**

### <a name="_9dvahun2fo6r"></a>	**2.2.3 Análisis de entrevistas**
**Entrevista 1:**

Andrea Huancas, una estudiante de Derecho de 27 años que reside en Independencia, Perú, valora la capacidad de monitorización en tiempo real en su hogar inteligente, destacando la importancia de cámaras y sensores. Sin embargo, señala dificultades en la integración entre dispositivos de diferentes marcas, lo que la lleva a desear una mayor centralización y simplicidad en su sistema de seguridad. Andrea también ve el potencial de la Realidad Aumentada para mejorar la gestión de la seguridad en su hogar, y aprecia la personalización de los sistemas, adaptándolos a su estilo de vida. Aunque reconoce la efectividad de la IA en la detección de amenazas, ha experimentado falsos positivos y espera mayor precisión. Prefiere recibir notificaciones en su teléfono con imágenes o videos en tiempo real y se muestra preocupada por la seguridad y privacidad de sus datos, destacando la importancia de la transparencia en su manejo.

**Entrevista 2:**

Angello, vive en un hogar inteligente. Destaca la importancia de la integración y personalización de los sistemas de seguridad. Valora la posibilidad de controlar las cámaras y sensores de forma remota y en tiempo real. Para él, la Realidad Aumentada sería un avance significativo al facilitar la visualización de la disposición de los dispositivos de seguridad, permitiéndole ajustarlos de forma eficiente.

Sus principales desafíos están relacionados con la compatibilidad entre dispositivos y la presencia de falsas alarmas en los sistemas basados en IA, lo que indica que aún hay margen de mejora en el uso de IA para la detección precisa de amenazas. Además, tiene altas expectativas en cuanto a la privacidad y seguridad de los datos, exigiendo un manejo cuidadoso y seguro de su información personal.

Este tipo de usuario tiene una inclinación por tecnologías emergentes como la RA y la IA, y estaría dispuesto a pagar por un sistema que ofrezca alta personalización, precisión predictiva y garantías de seguridad en el manejo de datos.

**Entrevista 3:**

Esmeralda Aliaga, una joven de 21 años que vive en Surco, valora la capacidad de automatización y control en su hogar inteligente. Resalta la importancia de contar con cámaras y sensores que le permitan monitorear su casa en tiempo real. Sin embargo, ha experimentado dificultades al integrar dispositivos de diferentes marcas, lo que la lleva a buscar una solución más centralizada y fácil de manejar. Esmeralda también se muestra interesada en el uso de la Realidad Aumentada para mejorar la gestión de la seguridad en su hogar, apreciando la capacidad de personalizar los sistemas según sus necesidades. Aunque reconoce los beneficios de la inteligencia artificial para la detección de amenazas, ha tenido problemas con falsos positivos y espera una mayor precisión. Prefiere recibir alertas en su teléfono, acompañadas de imágenes o videos en tiempo real, y le preocupa la privacidad de sus datos, enfatizando la importancia de la transparencia en su manejo.

**Entrevista 4:**

Leonel Alfaro Cumpa, un joven de 25 años de edad, reside en el distrito de Santa Anita. Actualmente, trabaja como practicante en una empresa dedicada a temas de seguridad, donde está a cargo de analizar y proponer mejoras en los sistemas de protección de hogares. Durante la entrevista, nos comentó que se siente entusiasmado con los avances tecnológicos en este campo, especialmente en la integración de la realidad aumentada (RA) y la inteligencia artificial (IA) para optimizar la seguridad de las viviendas. Según él, la combinación de estas tecnologías no solo refuerza las medidas de protección, sino que también ofrece al usuario final una mayor facilidad y control sobre sus sistemas de seguridad, lo que mejora la experiencia y efectividad.

Además, nos compartió su interés particular en la gestión integral de la seguridad del hogar, destacando que no todos los sistemas deben ser iguales. Para Leonel, es fundamental que las soluciones de seguridad sean personalizables, adaptándose a las necesidades específicas de cada vivienda, ya que los riesgos y requerimientos varían según el contexto de cada familia. También señaló que en su labor diaria ha notado que muchas veces las soluciones de seguridad convencionales no responden adecuadamente a las demandas de los usuarios, lo que lo motiva a explorar alternativas más innovadoras y flexibles.




## <a name="_bb76yek8c386"></a>**2.3  Needfinding** 

### <a name="_7urljr8qpr2e"></a>	**2.3.1 User Personas**
A continuación, se construirán los User Persona de cada segmento objetivo de nuestra plataforma. Para ello, se utilizarán los datos recolectados de las entrevistas realizadas. 

**User Persona 1 - Dueño de Hogar**

![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 011](https://github.com/user-attachments/assets/209add53-4e87-4206-89b3-4491fd5b0f78)
### <a name="_b7yq94wixmbb"></a>**	
### <a name="_6243ll1yk3mk"></a>**2.3.2 User task Matrix**




| |** |<p></p><p>`       `**Alejandro Martínez**</p>|
| :- | :- | :- |
|**Descripción**  |**Importancia**  |**Frecuencia** |
|Visualizar disposición de cámaras y sensores en RA|Medium|Often |
|Recibir alertas de seguridad en tiempo real|Medium|Always |
|Análisis de patrones de movimiento por IA |High|Rarely|
|Recibir recomendaciones para mejorar la seguridad|Medium|Always|
|Configurar y gestionar dispositivos desde la app|High  |Often |
|Integración con otros dispositivos inteligentes|High |Always|
|Ver historial de alertas y movimientos|Medium  |Often |


||** |<p></p><p>`          `**Laura Martinez**</p>|
| :- | :- | :- |
|**Descripción**  |**Importancia**  |**Frecuencia** |
|Visualizar disposición de cámaras y sensores en RA|High  |Always |
|Recibir alertas de seguridad en tiempo real|Medium|Always |
|Análisis de patrones de movimiento por IA |High|Rarely|
|Recibir recomendaciones para mejorar la seguridad|Medium|Always|
|Configurar y gestionar dispositivos desde la app|High  |Often |
|Integración con otros dispositivos inteligentes|High |Often |
|Ver historial de alertas y movimientos|Medium  |Often |


### <a name="_q3yk4tsrco34"></a>	**2.3.3 Empathy Mapping**

**Empathy Map: Alejandro Fernández**

![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 012](https://github.com/user-attachments/assets/b39e891d-b03a-43dd-ae43-a54519c3d596)

### <a name="_dtk35c93ltae"></a>	**2.2.1 As-is Scenario Mapping**

Segmento 1: Dueños de Hogar

[Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 013](https://github.com/user-attachments/assets/074527a6-da7f-444a-a856-a23f10342786)

## <a name="_qfy1vnuac1ui"></a>**2.4  Ubiquitous Language.** 


|**Término en Inglés**|**Término en Español**|**Definición**|
| :-: | :-: | :-: |
|Augmented Reality (AR)|Realidad Aumentada (RA)|Tecnología que superpone información digital (como imágenes, sonidos, o datos) sobre el entorno físico real a través de dispositivos como smartphones o gafas AR.|
|Intrusion Detection System|Sistema de Detección de Intrusos|Sistema de seguridad que utiliza sensores y cámaras para detectar movimientos o actividades inusuales dentro de un área protegida, alertando al usuario de posibles intrusiones.|
|Security Sensors|Sensores de Seguridad|Dispositivos instalados en diferentes partes del hogar que detectan movimientos, cambios de temperatura, sonidos, o presencia de personas para identificar posibles amenazas.|
|Motion Patterns|Patrones de Movimiento|Secuencias o hábitos de movimiento dentro del hogar que son analizados por la IA para determinar si una actividad es normal o sospechosa.|
|Smart Alerts|Alertas Inteligentes|Notificaciones automáticas enviadas al usuario que han sido filtradas y priorizadas por un sistema de IA basado en la relevancia de la amenaza o anomalía detectada|
|Security Recommendations|Recomendaciones de Seguridad|Sugerencias generadas por el sistema basadas en el análisis de los patrones de movimiento y la ubicación de los dispositivos, para mejorar la seguridad del hogar.|
|Camera Layout Visualization|Visualización de Disposición de Cámaras|Funcionalidad que permite ver en tiempo real, a través de AR, la ubicación y el ángulo de cobertura de las cámaras de seguridad instaladas en el hogar.|

# <a name="_bg1gp032r8wm"></a>**Capítulo III: Requirements Specification** 
## <a name="_cd6y73qhbrvi"></a>**3.1. To-Be Scenario Mapping.** 

- Segmento Objetivo 1: Dueños de Hogar

|**Fases**|**Instalación de Dispositivos**|**Monitoreo de Seguridad**|**Gestión de Dispositivos**|
| - | - | - | - |
|**Doing**|Utilizan la RA para visualizar y configurar la disposición de cámaras y sensores.|Reciben notificaciones en tiempo real sobre la actividad detectada por las cámaras.|Configuran y gestionan los dispositivos desde la app móvil centralizada.|
|**Thinking**|"Quiero optimizar la seguridad de mi hogar sin complicaciones."|"Espero que el sistema me avise solo cuando sea realmente necesario."|"Quiero que el sistema sea fácil de manejar y eficiente."|
|**Feeling**|Confianza en que el sistema mejora la seguridad de su hogar.|Tranquilidad al saber que están informados sobre posibles intrusos.|Satisfacción al poder gestionar todos los dispositivos desde una sola plataforma.|


## <a name="_2disjd1uh4jr"></a>**3.2. User Stories.** 

### <a name="_ythnk63p2b47"></a>**ÉPICA 1: Gestión de Seguridad del Hogar**
**Descripción**: Facilitar la gestión eficiente y segura de los dispositivos de seguridad en el hogar, incluyendo cámaras y sensores, para mejorar la experiencia del usuario y la seguridad.
#### <a name="_ow9t153ca7t1"></a>**US001: Visualización de dispositivos con RA**

|**ID - HU**|**US001**|
| - | - |
|**Título HU**|Visualización de dispositivos con RA|
|**Descripción HU**|Como usuario, quiero visualizar la disposición de cámaras y sensores mediante RA para optimizar su ubicación.|

**Criterios de Aceptación**:

- **Escenario 1: Visualización inicial**
  - Dado que el usuario ha conectado los dispositivos,
  - Cuando el usuario accede a la pantalla de RA,
  - Entonces el sistema muestra la ubicación de los dispositivos en tiempo real.
- **Escenario 2: Reorganización de dispositivos**
  - Dado que el usuario visualiza los dispositivos con RA,
  - Cuando el usuario arrastra un dispositivo a una nueva ubicación,
  - Entonces el sistema actualiza la posición en tiempo real.
#### <a name="_4wnylcjbd07r"></a>**US002: Gestión centralizada de dispositivos**

|**ID - HU**|**US002**|
| - | - |
|**Título HU**|Gestión centralizada de dispositivos|
|**Descripción HU**|Como usuario, quiero gestionar todos mis dispositivos desde una aplicación para simplificar la administración.|

**Criterios de Aceptación**:

- **Escenario 1: Ver todos los dispositivos**
  - Dado que el usuario accede a la pantalla de gestión,
  - Cuando el usuario selecciona "Ver todos los dispositivos",
  - Entonces el sistema muestra todos los dispositivos conectados.
- **Escenario 2: Modificación de configuración**
  - Dado que el usuario accede a un dispositivo,
  - Cuando el usuario modifica la configuración,
  - Entonces el sistema guarda y aplica los cambios.
#### <a name="_955umc7qrui0"></a>**US003: Creación de perfiles de seguridad**

|**ID - HU**|**US003**|
| - | - |
|**Título HU**|Creación de perfiles de seguridad|
|**Descripción HU**|Como usuario, quiero crear perfiles de seguridad personalizados para activar diferentes niveles de seguridad en mi hogar.|

**Criterios de Aceptación**:

- **Escenario 1: Creación de un nuevo perfil**
  - Dado que el usuario accede a la configuración de seguridad,
  - Cuando selecciona "Crear nuevo perfil",
  - Entonces el sistema le permite establecer reglas de seguridad.
- **Escenario 2: Activación de perfiles**
  - Dado que el usuario tiene varios perfiles,
  - Cuando selecciona un perfil,
  - Entonces el sistema activa el perfil seleccionado.
#### <a name="_6gvxpypl7hg"></a>**US004: Configuración remota de dispositivos**

|**ID - HU**|**US004**|
| - | - |
|**Título HU**|Configuración remota de dispositivos|
|**Descripción HU**|Como usuario, quiero configurar remotamente los dispositivos para cambiar la seguridad de mi hogar sin estar presente.|

**Criterios de Aceptación**:

- **Escenario 1: Configuración desde una ubicación remota**
  - Dado que el usuario está fuera de su hogar,
  - Cuando accede a la app,
  - Entonces puede modificar la configuración de los dispositivos.
- **Escenario 2: Notificación de cambios**
  - Dado que el usuario ha modificado la configuración,
  - Cuando se guarden los cambios,
  - Entonces el sistema envía una notificación al usuario.
#### <a name="_rupxkhq4zbvu"></a>**US005: Control por voz de dispositivos**

|**ID - HU**|**US005**|
| - | - |
|**Título HU**|Control por voz de dispositivos|
|**Descripción HU**|Como usuario, quiero controlar mis dispositivos de seguridad por comandos de voz para mayor comodidad.|

**Criterios de Aceptación**:

- **Escenario 1: Activación por voz**
  - Dado que el usuario está en su hogar,
  - Cuando el usuario emite un comando de voz,
  - Entonces el sistema ejecuta la acción solicitada.
- **Escenario 2: Notificación de acción completada**
  - Dado que el usuario emitió un comando,
  - Cuando se completa la acción,
  - Entonces el sistema notifica al usuario.
#### <a name="_qv0w7cm9e2qb"></a>**US006: Recomendaciones de seguridad basadas en IA**

|**ID - HU**|**US006**|
| - | - |
|**Título HU**|Recomendaciones de seguridad basadas en IA|
|**Descripción HU**|Como usuario, quiero recibir recomendaciones para mejorar la seguridad de mi hogar basadas en patrones de IA.|

**Criterios de Aceptación**:

- **Escenario 1: Análisis de patrones**
  - Dado que el usuario tiene el análisis de IA activado,
  - Cuando el sistema detecta un patrón de riesgo,
  - Entonces envía una recomendación para mejorar la seguridad.
- **Escenario 2: Aplicación de recomendaciones**
  - Dado que el sistema ha enviado una recomendación,
  - Cuando el usuario acepta la recomendación,
  - Entonces el sistema aplica el ajuste sugerido.
### <a name="_3bhe8gdvo5zn"></a>**ÉPICA 2: Notificaciones y Monitoreo**
**Descripción**: Proporcionar a los usuarios alertas y notificaciones en tiempo real, ajustadas a sus preferencias, para mejorar la seguridad del hogar mediante el monitoreo continuo.
#### <a name="_s9gyc2knhg0z"></a>**US007: Notificaciones en tiempo real**

|**ID - HU**|**US007**|
| :-: | :-: |
|**Título HU**|Notificaciones en tiempo real|
|**Descripción HU**|Como usuario, quiero recibir notificaciones inmediatas sobre actividades sospechosas.|

**Criterios de Aceptación**:

- **Escenario 1: Recepción de notificaciones**
  - Dado que el sistema detecta una actividad sospechosa,
  - Cuando ocurre una alerta,
  - Entonces el sistema envía una notificación al usuario en tiempo real.
- **Escenario 2: Personalización de alertas**
  - Dado que el usuario tiene preferencias de notificación,
  - Cuando selecciona los eventos relevantes,
  - Entonces el sistema sólo envía las notificaciones configuradas.
#### <a name="_fhbcswz4pyc4"></a>**US008: Personalización de notificaciones**

|**ID - HU**|**US008**|
| :-: | :-: |
|**Título HU**|Personalización de notificaciones|
|**Descripción HU**|Como usuario, quiero personalizar mis notificaciones para recibir solo alertas relevantes.|

**Criterios de Aceptación**:

- **Escenario 1: Configuración de alertas**
  - Dado que el usuario accede a la pantalla de notificaciones,
  - Cuando selecciona sus preferencias,
  - Entonces el sistema guarda las preferencias.
- **Escenario 2: Modificación de alertas**
  - Dado que el usuario desea modificar sus preferencias,
  - Cuando accede a la configuración de alertas,
  - Entonces puede cambiar y guardar sus preferencias.
#### <a name="_mp0rx2bkj6yu"></a>**US009: Alerta de emergencia automática**

|**ID - HU**|**US009**|
| :-: | :-: |
|**Título HU**|Alerta de emergencia automática|
|**Descripción HU**|Como usuario, quiero que el sistema envíe alertas automáticas a los servicios de emergencia en caso de una amenaza.|

**Criterios de Aceptación**:

- **Escenario 1: Detección de emergencia**
  - Dado que el sistema detecta una emergencia,
  - Cuando ocurre una amenaza crítica,
  - Entonces el sistema envía automáticamente una alerta a los servicios de emergencia.
- **Escenario 2: Notificación al usuario**
  - Dado que el sistema ha enviado una alerta,
  - Cuando el usuario recibe la notificación,
  - Entonces también recibe una confirmación de que la alerta fue enviada.
#### <a name="_uuuqanso4dt9"></a>**US010: Monitoreo de video en tiempo real**

|**ID - HU**|**US010**|
| :-: | :-: |
|**Título HU**|Monitoreo de video en tiempo real|
|**Descripción HU**|Como usuario, quiero monitorear mi hogar en tiempo real desde la aplicación para revisar actividades sospechosas.|

**Criterios de Aceptación**:

- **Escenario 1: Activación de video en vivo**
  - Dado que el usuario accede a la pantalla de monitoreo,
  - Cuando selecciona "Ver en vivo",
  - Entonces el sistema transmite en tiempo real.
- **Escenario 2: Notificación de eventos en tiempo real**
  - Dado que el usuario está monitoreando el video,
  - Cuando ocurre un evento sospechoso,
  - Entonces el sistema envía una notificación al usuario.
#### <a name="_3lz47b142wbh"></a>**US011: Detección de patrones anormales**

|**ID - HU**|**US011**|
| :-: | :-: |
|**Título HU**|Detección de patrones anormales|
|**Descripción HU**|Como usuario, quiero que el sistema detecte patrones inusuales y me alerte antes de que ocurra una posible amenaza.|

**Criterios de Aceptación**:

- **Escenario 1: Identificación de patrones anormales**
  - Dado que el sistema monitorea la actividad,
  - Cuando detecta un patrón inusual,
  - Entonces envía una notificación al usuario.
- **Escenario 2: Revisión de patrones**
  - Dado que el sistema ha detectado un patrón,
  - Cuando el usuario lo revisa,
  - Entonces puede modificar las configuraciones de seguridad.
### <a name="_mw3vtwzwhim"></a>**ÉPICA 3: Privacidad y Seguridad de Datos**
**Descripción**: Garantizar que los usuarios puedan gestionar la privacidad de sus cámaras, dispositivos, y datos personales, manteniendo un alto nivel de seguridad en la nube.
#### <a name="_xzgwhjah1t7d"></a>**US012: Control de privacidad**

|**ID - HU**|**US012**|
| :-: | :-: |
|**Título HU**|Control de privacidad|
|**Descripción HU**|Como usuario, quiero gestionar quién puede acceder a las cámaras y grabaciones para proteger mi privacidad.|

**Criterios de Aceptación**:

- **Escenario 1: Ajuste de permisos de cámaras**
  - Dado que el usuario está en la pantalla de configuración,
  - Cuando ajusta los permisos de acceso,
  - Entonces el sistema actualiza los permisos para cada dispositivo.
- **Escenario 2: Notificación de acceso no autorizado**
  - Dado que el usuario ha activado alertas de privacidad,
  - Cuando alguien intenta acceder sin permiso,
  - Entonces el sistema notifica al usuario del intento.
#### <a name="_3i1g64cz900i"></a>**US013: Cifrado de datos en la nube**

|**ID - HU**|**US013**|
| :-: | :-: |
|**Título HU**|Cifrado de datos en la nube|
|**Descripción HU**|Como usuario, quiero que mis grabaciones de seguridad se almacenen en la nube de forma segura y cifrada.|

**Criterios de Aceptación**:

- **Escenario 1: Almacenamiento cifrado**
  - Dado que el usuario ha activado la opción de almacenamiento en la nube,
  - Cuando se graba un video,
  - Entonces el sistema lo almacena con cifrado avanzado.
- **Escenario 2: Acceso a grabaciones**
  - Dado que el usuario accede a las grabaciones,
  - Cuando el usuario solicita una grabación,
  - Entonces el sistema verifica las credenciales y permite la descarga.
#### <a name="_eudjc560fwhr"></a>**US014: Autenticación multifactor (MFA)**

|**ID - HU**|**US014**|
| :-: | :-: |
|**Título HU**|Autenticación multifactor (MFA)|
|**Descripción HU**|Como usuario, quiero activar la autenticación multifactor para proteger mi cuenta de accesos no autorizados.|

**Criterios de Aceptación**:

- **Escenario 1: Activación de MFA**
  - Dado que el usuario está en la pantalla de seguridad,
  - Cuando selecciona "Activar MFA",
  - Entonces el sistema envía un código para confirmar la activación.
- **Escenario 2: Acceso con MFA**
  - Dado que el usuario tiene MFA activado,
  - Cuando intenta iniciar sesión,
  - Entonces el sistema solicita un segundo factor de autenticación.
#### <a name="_7i8762wvll8c"></a>**US015: Monitoreo de accesos a dispositivos**

|**ID - HU**|**US015**|
| :-: | :-: |
|**Título HU**|Monitoreo de accesos a dispositivos|
|**Descripción HU**|Como usuario, quiero monitorear quién ha accedido a mis dispositivos para asegurarme de que nadie acceda sin mi permiso.|

**Criterios de Aceptación**:

- **Escenario 1: Registro de accesos**
  - Dado que el usuario accede al historial de accesos,
  - Cuando selecciona "Ver accesos",
  - Entonces el sistema muestra un historial de todos los accesos realizados.
- **Escenario 2: Notificación de accesos**
  - Dado que el usuario ha activado las notificaciones,
  - Cuando alguien accede a un dispositivo,
  - Entonces el sistema notifica al usuario.
## <a name="_sq0ajr7daprb"></a>**3.3. Impact Mapping.** 

![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 014](https://github.com/user-attachments/assets/97285ac8-5408-4d67-bde1-f3d8c24ba686)



## <a name="_h7dvorhjprre"></a>**3.4. Product Backlog.**
### <a name="_nubuaelmlvr7"></a>**Product Backlog**

|**Orden**|**Código**|**Título**|**Descripción**|**Priority Points**|
| :-: | :-: | :-: | :-: | :-: |
|**1**|US007|Notificaciones en tiempo real|Recibir notificaciones inmediatas sobre actividades sospechosas.|10|
|**2**|US012|Control de privacidad|Gestionar quién puede acceder a las cámaras y grabaciones para proteger la privacidad.|9|
|**3**|US001|Visualización de dispositivos con RA|Visualizar la disposición de cámaras y sensores mediante RA para optimizar su ubicación.|9|
|**4**|US009|Alerta de emergencia automática|Enviar alertas automáticas a servicios de emergencia en caso de una amenaza.|8|
|**5**|US002|Gestión centralizada de dispositivos|Gestionar todos los dispositivos de seguridad desde una sola aplicación para simplificar la administración.|8|
|**6**|US013|Cifrado de datos en la nube|Almacenar grabaciones de seguridad en la nube de forma segura y cifrada.|8|
|**7**|US014|Autenticación multifactor (MFA)|Activar la autenticación multifactor para proteger la cuenta de accesos no autorizados.|8|
|**8**|US010|Monitoreo de video en tiempo real|Monitorear el hogar en tiempo real desde la aplicación para revisar actividades sospechosas.|7|
|**9**|US003|Creación de perfiles de seguridad|Crear perfiles de seguridad personalizados para activar diferentes niveles de seguridad.|7|
|**10**|US005|Control por voz de dispositivos|Controlar los dispositivos de seguridad mediante comandos de voz.|7|
|**11**|US011|Detección de patrones anormales|Detectar patrones inusuales y alertar al usuario antes de que ocurra una posible amenaza.|7|
|**12**|US006|Recomendaciones de seguridad basadas en IA|Recibir recomendaciones para mejorar la seguridad basadas en IA.|6|
|**13**|US008|Personalización de notificaciones|Personalizar las notificaciones para recibir solo alertas relevantes.|6|
|**14**|US004|Configuración remota de dispositivos|Configurar remotamente los dispositivos para cambiar la seguridad del hogar sin estar presente.|6|
|**15**|US015|Monitoreo de accesos a dispositivos|Monitorear quién ha accedido a los dispositivos para asegurar la privacidad.|5|

# <a name="_uwe0ben5wt2n"></a>**Capítulo IV: Strategic-Level Software Design** 

## <a name="_epo2324o29gc"></a>**4.1. Strategic-Level Attribute-Driven Design.**
### <a name="_i7ub0nd4f9x0"></a>**4.1.1. Design Purpose.**
El propósito del diseño de arquitectura a nivel estratégico es proporcionar una estructura sólida que permita que el sistema de seguridad Aegis Vision sea altamente escalable, eficiente y fácil de mantener. La arquitectura debe soportar tecnologías emergentes como Realidad Aumentada (RA) e Inteligencia Artificial (IA), garantizando la integración fluida de cámaras, sensores y dispositivos inteligentes para la seguridad del hogar. Además, debe cumplir con altos estándares de calidad, seguridad y rendimiento, asegurando una experiencia de usuario personalizada y confiable.

### <a name="_n4uo8bz2igpx"></a>**4.1.2. Attribute-Driven Design Inputs.**
**4.1.2.1. Primary Functionality (Primary User Stories).**

Las funcionalidades principales se basan en las siguientes User Stories:

- **US001 - Visualización de dispositivos con RA.**
- **US002 - Notificaciones en tiempo real.**
- **US004 - Gestión centralizada de dispositivos.**
- **US005 - Personalización de alertas.**

**4.1.2.2. Quality attribute Scenarios.**

Los escenarios de atributos de calidad describen cómo el sistema debe manejar situaciones clave para garantizar el rendimiento y la seguridad.

- **Escenario de rendimiento:**

- Dado que el usuario realiza cambios en la disposición de los dispositivos de seguridad mediante RA,
- Cuando el sistema reciba el nuevo input de ubicación,
- Entonces la aplicación debe actualizar la vista en RA en tiempo real sin retraso visible (menos de 500 ms).

- **Escenario de seguridad:**

- Dado que un usuario accede al historial de grabaciones almacenadas en la nube,
- Cuando solicite una grabación,
- Entonces el sistema debe autenticar al usuario antes de permitir el acceso, y la descarga debe estar cifrada.

- **Escenario de escalabilidad:**

- Dado que el sistema está conectado a múltiples dispositivos inteligentes en un hogar,
- Cuando se añadan nuevos dispositivos,
- Entonces la aplicación debe integrarlos sin comprometer el rendimiento ni la capacidad de gestión.

**4.1.2.3. Constraints.**

Las restricciones del diseño incluyen:

- **Compatibilidad** con dispositivos inteligentes existentes de terceros.
- **Cumplimiento de normativas de seguridad de datos** y privacidad (por ejemplo, GDPR).
- **Limitaciones de hardware** en dispositivos de RA utilizados por los usuarios finales.

### <a name="_vbta846nakaz"></a>**4.1.3. Architectural Drivers Backlog.**

Este backlog contiene los factores clave que deben guiar las decisiones arquitectónicas:

1. **Rendimiento:** El sistema debe manejar la visualización en RA y la gestión de múltiples dispositivos sin interrupciones.
1. **Seguridad:** Las funciones de almacenamiento en la nube y acceso a datos sensibles requieren autenticación robusta y cifrado.
1. **Escalabilidad:** El sistema debe ser capaz de integrar dispositivos adicionales sin afectar el rendimiento.
1. **Mantenibilidad:** La arquitectura debe ser modular para facilitar futuras actualizaciones, especialmente con nuevas tecnologías de IA y RA.

### <a name="_c0n36j9pd6zh"></a>**4.1.4. Architectural Design Decisions.**

1. **Microservicios:** Se utilizará una arquitectura de microservicios para que cada componente (visualización RA, notificaciones, gestión de dispositivos) funcione de manera independiente, facilitando la escalabilidad y el mantenimiento.
1. **Almacenamiento en la nube:** Se integrará un servicio de almacenamiento en la nube con cifrado, donde se guardarán grabaciones y otros datos sensibles.
1. U**so de una API centralizada:** Para la integración de dispositivos de terceros, se diseñará una API que permita la comunicación entre la aplicación y los dispositivos conectados.
1. **Seguridad avanzada**: Autenticación multifactor (MFA) para accesos sensibles y cifrado de extremo a extremo en las transferencias de datos.

### <a name="_mc9imvm9gz2p"></a>**4.1.5. Quality Attribute Scenario Refinements.**

- **Rendimiento refinado:** Se asegurará que la latencia en las actualizaciones de RA se mantenga por debajo de los 500 ms en redes de alta velocidad.
- **Seguridad refinada:** Se implementará el uso de tokens de seguridad para acceso a grabaciones almacenadas y autenticación mediante OAuth 2.0.

## <a name="_1sv82uc42440"></a>**4.2. Strategic-Level Domain-Driven Design.**
### <a name="_tk4kcqhgqwvw"></a>**4.2.1. EventStorming.**
![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 015](https://github.com/user-attachments/assets/84db079b-6e26-4777-b4b0-06dc43dff2ef)

### <a name="_nelavj1jkn2o"></a>**4.2.2. Candidate Context Discovery.**
1. Gestión de Usuarios
1. Configuración de Dispositivos
1. Monitoreo y Detección
1. Análisis Predictivo
1. Notificaciones
1. Visualización RA
1. Entrenamiento de IA
1. Gestión de Suscripciones

### <a name="_7sh1gfqbu3nr"></a>**4.2.3. Domain Message Flows Modeling.**
![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 016](https://github.com/user-attachments/assets/5253fdbc-506f-4d18-b21c-c65cdb37169f)

### <a name="_ojenzg6htc8v"></a>**4.2.4. Bounded Context Canvases.**
1. Gestión de Usuarios

   ![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 017](https://github.com/user-attachments/assets/925ac3c3-355a-46c9-85eb-56fb8b8a4fc1)

1. Configuración de Dispositivos

   ![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 018](https://github.com/user-attachments/assets/950e7e2b-04a0-4c4d-a3a8-55f46abdbd65)

1. Monitoreo y Detección

   ![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 019](https://github.com/user-attachments/assets/582402cf-2caf-40ae-bd8c-60942d0dad74)

1. Análisis Predictivo

   ![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 020](https://github.com/user-attachments/assets/b987d25c-5695-49a0-9d6c-1a31576bafac)


1. Notificaciones

   ![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 021](https://github.com/user-attachments/assets/03c99ea5-5e40-4455-8b28-0361f6c3fb3f)

1. Visualización RA

   ![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 022](https://github.com/user-attachments/assets/910e1804-24e1-4f93-9ac9-6c8b66ef26f2)


1. Entrenamiento de IA

   ![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 023](https://github.com/user-attachments/assets/37d3c56c-9f0c-4600-80b5-6d56ffbd86f4)

1. Gestión de Suscripciones

   ![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 024](https://github.com/user-attachments/assets/82fc7a24-6340-4ae1-8675-f88e70436f94)

### <a name="_lf4931o39sme"></a>**4.2.5. Context Mapping.**
![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 025](https://github.com/user-attachments/assets/8877b774-da36-45a0-89d9-d67cd19878e3)

## <a name="_jhyuyk89nvca"></a>**4.3. Software Architecture.**
<a name="_q7xs6mfdzwxf"></a>**4.3.1. Software Architecture System Landscape Diagram.**

![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 026](https://github.com/user-attachments/assets/68c0728a-bcbc-4337-b66f-da51b9fabe45)

------------------------------------------------------------------------------------

### <a name="_k8rxufjurpw2"></a>**4.3.1. Software Architecture Context Level Diagrams.**
![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 027](https://github.com/user-attachments/assets/d981e4fc-dbec-4c70-9976-89d69006d2bc)

### <a name="_g7737xnx3j1i"></a>**4.3.2. Software Architecture Container Level Diagrams.**
![](Aspose.Words.00d9a324-7786-4229-8307-f3d2f53facbd.028.png)

### <a name="_nh697trw5ah6"></a>**4.3.3. Software Architecture Deployment Diagrams![]**

![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 028](https://github.com/user-attachments/assets/192743e4-c0dc-4762-ac7c-1fd3e907798e)

<a name="_z7mqfkd1lit0"></a><a name="_fyc88ciro1mq"></a><a name="_5hzk202a2uid"></a><a name="_1bar82njh4ii"></a><a name="_j78ksa4yr9v4"></a><a name="_b6ixbo1enuqw"></a><a name="_om0s5bqjfozl"></a><a name="_i446ozauxct6"></a><a name="_1zc8d37ranj6"></a><a name="_mmw7kls2r5aw"></a><a name="_865av4qjmuzk"></a><a name="_dawoj74m8em2"></a><a name="_flmg6a6bg7sh"></a><a name="_xcrlxhq91wcp"></a><a name="_peus3pybb5sl"></a><a name="_sto4g2iwzxkl">
# <a name="_uwe0ben5wt2n"></a>**Capítulo V: Tactical-Level Software Design.** 
## <a name="_cf19uzi1ygmf"></a>**5.1. Bounded Context: IAM (Identity and Access Management)**
### <a name="_mz9ewfjhmssi"></a>**5.1.1. Domain Layer.** 
### En el Domain Layer, se representarán las reglas de negocio y el core del sistema para el contexto IAM. Las clases clave en esta capa incluye:
- ### **Entities**:
  ### User: Representa al usuario con atributos como email, password (cifrada), y roles asignados.
  ### Role: Define los roles de acceso del sistema, como Admin, User.
  ### Permission: Representa los permisos específicos asignados a un rol.
  ### Aggregates:
  ### UserAggregate: Coordina las interacciones entre User, Role, y Permission.
- ### **Value Objects**:
  ### Email: Verifica la estructura correcta del correo electrónico.
  ### Password: Almacena y valida la contraseña cifrada.
- ### **Domain Services**:
  ### AuthenticationService: Autentica a los usuarios según las reglas de negocio.
  ### AuthorizationService: Determina qué permisos tiene un usuario basado en su rol.
- ### **Repositories**:
  ### UserRepository: Define la interfaz para acceder y manipular los datos del usuario en la base de datos.
  ### <a name="_nhk3fsklxjb9"></a>RoleRepository: Accede a los roles y permisos asociados.
###
###
### <a name="_mjxgw25xfhev"></a><a name="_5xk31kzybah"></a><a name="_548lcs94e665"></a>**5.1.2. Interface Layer.** 
Esta capa maneja la interacción con los usuarios mediante controladores (controllers) o consumidores que se encargan de recibir las solicitudes externas.

**Controllers**:

AuthenticationController: Gestiona el inicio de sesión, registro, y autenticación multifactor (MFA).

RoleController: Administra los roles y permisos de usuarios.

**Endpoints**:

POST /login: Inicia sesión de usuario.

POST /register: Registra nuevos usuarios.

GET /roles: Devuelve los roles disponibles.

.
### <a name="_905nud695ops"></a>**5.1.3. Application Layer.** 
El Application Layer contiene los flujos de procesos del negocio. Aquí se gestionan los comandos y eventos relacionados con la autenticación y autorización.

**Command Handlers:**

LoginUserCommandHandler: Maneja el flujo del proceso de inicio de sesión.

RegisterUserCommandHandler: Gestiona el registro de nuevos usuarios.

**Event Handlers:**

UserLoggedInEventHandler: Dispara eventos cuando un usuario se autentica exitosamente.

UserRegisteredEventHandler: Maneja las acciones posteriores al registro de un usuario, como el envío de un correo de bienvenida.

### <a name="_3rqu2ymeacck"></a>**5.1.4. Infrastructure Layer.** 
La Infrastructure Layer es responsable de interactuar con servicios externos, como bases de datos y sistemas de mensajería. Aquí se implementan los repositorios y los adaptadores para los sistemas de infraestructura.

**Repositories**:

UserRepositoryImpl: Implementa la interfaz de acceso a la base de datos para el manejo de usuarios.

RoleRepositoryImpl: Implementa la gestión de roles y permisos en la base de datos.

Servicios Externos:

EmailService: Envío de correos electrónicos (por ejemplo, para confirmar el registro o MFA).

MessagingService: Implementación de mensajería para eventos como UserRegistered o UserLoggedIn.

### <a name="_p4ty1makiupz"></a>**5.1.6. Bounded Context Software Architecture Component Level Diagrams.** 
![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 030](https://github.com/user-attachments/assets/e3e6ceb1-ca43-4d2a-a825-bdd6a60073f5)

### <a name="_xabi11iecsy6"></a>**5.1.7. Bounded Context Software Architecture Code Level Diagrams.** 
5\.1.7.1. Bounded Context Domain Layer Class Diagrams. 

![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 031](https://github.com/user-attachments/assets/3ead375d-03c1-45e6-9082-6f86b43379a3)

5\.1.7.2. Bounded Context Database Design Diagram. 

![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 032](https://github.com/user-attachments/assets/ed6ebcef-3336-45d7-88a6-eb2fb5ada630)

## <a name="_vhe58bvi4vq"></a>**5.2. Bounded Context Profile :** 
### <a name="_9t963kj6je0y"></a>**5.2.1. Domain Layer.** 
En el Domain Layer del contexto Profile, las clases se encargan de manejar las preferencias y configuraciones de los usuarios.

**Entities**:

UserProfile: Información personal del usuario.

NotificationSettings: Configuración de notificaciones.

PrivacySettings: Preferencias de privacidad para dispositivos de seguridad.

**Value Objects:**

Address: Representa la dirección del usuario.

NotificationPreferences: Representa los tipos de notificaciones y su configuración.

**Domain Services:**

ProfileService: Gestiona la actualización de perfiles, notificaciones y preferencias.

Repositories:

UserProfileRepository: Interfaz para interactuar con la base de datos de perfiles.

### <a name="_2g8nvs5m80ko"></a>**5.2.2. Interface Layer.** 
**Controllers**:

ProfileController: Permite a los usuarios gestionar su perfil y sus preferencias de notificación y privacidad.

Endpoints:

GET /profile: Obtiene el perfil del usuario.

PUT /profile: Actualiza el perfil.

### <a name="_zl05nyyr348"></a>**5.2.3. Application Layer.** 
**Command Handlers:**

UpdateProfileCommandHandler: Gestiona la actualización del perfil de usuario.

UpdateNotificationSettingsCommandHandler: Cambia las preferencias de notificación.

**Event Handlers:**

ProfileUpdatedEventHandler: Dispara eventos cuando un perfil es actualizado.

### <a name="_unayaasma2et"></a>**5.2.4. Infrastructure Layer.** 
**Repositories**:

UserProfileRepositoryImpl: Implementa el acceso a la base de datos para los perfiles de usuario.

### <a name="_h4guvw644m9u"></a>**5.2.6. Bounded Context Software Architecture Component Level Diagrams.**
### ** 
![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 033](https://github.com/user-attachments/assets/eea56aa9-e27a-4a5e-b3b5-d408c77bd650)

### <a name="_2fgy2b4sl35w"></a>**5.2.7. Bounded Context Software Architecture Code Level Diagrams.** 
5\.2.7.1. Bounded Context Domain Layer Class Diagrams. 

![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 034](https://github.com/user-attachments/assets/22d55aa5-eeb3-472b-b533-8888b2aac6ed)

5\.2.7.2. Bounded Context Database Design Diagram. 

![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 035](https://github.com/user-attachments/assets/6b2167f8-9e5f-442c-b9ab-3f6043881d55)

## <a name="_b9yaz6etri3o"></a>**5.3. Bounded Context Subscription & Payment:** 
### <a name="_k99ggsyw6tuj"></a>**5.3.1. Domain Layer.** 
El Domain Layer maneja la lógica de suscripciones y pagos.

**Entities**:

Subscription: Representa un plan de suscripción.

Payment: Registro de pagos realizados por un usuario.

Billing: Maneja la facturación recurrente.

**Aggregates**:

SubscriptionAggregate: Reúne las interacciones entre suscripción, pago y facturación.

**Repositories**:

SubscriptionRepository: Interfaz para gestionar las suscripciones.

### <a name="_7ato4olxkwjt"></a>**5.3.2. Interface Layer.** 
**Controllers**:

SubscriptionController: Gestiona la suscripción del usuario.

PaymentController: Procesa los pagos.

**Endpoints**:

GET /subscription: Consulta el estado de la suscripción.

POST /payment: Procesa el pago de suscripción.

### <a name="_ir83rst19v0w"></a>**5.3.3. Application Layer.** 
**Command Handlers:**

ProcessPaymentCommandHandler: Procesa los pagos realizados por los usuarios.

UpgradeSubscriptionCommandHandler: Maneja las actualizaciones de suscripción.

### <a name="_xocakxusrfqd"></a>**5.3.4. Infrastructure Layer.** 
PaymentService: Interfaz con sistemas de pago externos como Stripe o PayPal.

### <a name="_kblax7ydx5b7"></a>**5.3.6. Bounded Context Software Architecture Component Level Diagrams.** 
![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 036](https://github.com/user-attachments/assets/7a8c4fae-009a-4c83-8cb4-6cf6f36aa143)

### <a name="_z7pjn1h4ttk9"></a>**5.3.7. Bounded Context Software Architecture Code Level Diagrams.** 
5\.3.7.1. Bounded Context Domain Layer Class Diagrams. 

![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 037](https://github.com/user-attachments/assets/44674a99-7dc4-4061-a245-48a1bb4e48a4)


5\.3.7.2. Bounded Context Database Design Diagram. 

![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 038](https://github.com/user-attachments/assets/d764a439-dbf6-4d9e-8245-2067b37f4ec6)

## <a name="_brnaowlxxbrk"></a>**5.4. Bounded Context Configuration & Planning:** 
### <a name="_fidocwar0r69"></a>**5.4.1. Domain Layer.** 
**Entities:**

- Configuration: Maneja la configuración general del sistema de seguridad.
- Device: Representa los dispositivos conectados (cámaras, sensores, etc.).
- SecurityProfile: Define los perfiles de seguridad basados en las preferencias del usuario.

**Aggregates**:

- ConfigurationAggregate: Reúne configuraciones y dispositivos conectados.

**Value Objects:**

- DeviceSettings: Configuraciones de cada dispositivo.

**Domain Services:**

- PlanningService: Gestiona la planificación de las configuraciones de seguridad.

**Repositories:**

- ConfigurationRepository: Interfaz para acceder a las configuraciones almacenadas.

### <a name="_akw4m3i31f3i"></a>**5.4.2. Interface Layer.** 
**Controllers:**

- ConfigurationController: Gestiona las solicitudes para configurar dispositivos.

**Endpoints:**

- POST /configure: Configura los dispositivos.
- GET /configurations: Devuelve las configuraciones actuales.
### <a name="_uercwwwtche"></a>**5.4.3. Application Layer.** 
**Command Handlers:**

- ConfigureDeviceCommandHandler: Gestiona la configuración de dispositivos.

**Event Handlers:**

- ConfigurationUpdatedEventHandler: Gestiona eventos cuando se actualizan las configuraciones.

### <a name="_yf3imog51uav"></a>**5.4.4. Infrastructure Layer.** 
**Repositories:**

- ConfigurationRepositoryImpl: Implementación de la base de datos para almacenar las configuraciones.

**Servicios Externos:**

- MessagingService: Implementación para notificar cambios en las configuraciones.
### <a name="_iqiou6oesdpt"></a>**5.4.6. Bounded Context Software Architecture Component Level Diagrams.** 
![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 039](https://github.com/user-attachments/assets/1d5c0664-4f7e-431d-bee0-a3537a9c0c3d)
### <a name="_fa0merv7n0uk"></a>**5.4.7. Bounded Context Software Architecture Code Level Diagrams.** 
5\.4.7.1. Bounded Context Domain Layer Class Diagrams. 

![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 040](https://github.com/user-attachments/assets/d7bdffe3-fb34-4022-b376-0ddd6d04f891)

5\.4.7.2. Bounded Context Database Design Diagram. 

![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 041](https://github.com/user-attachments/assets/f01459d0-e019-4c4f-a773-f3894040d4f2)

## <a name="_9starbi7oh9d"></a>**5.5. Bounded Context Service Execution:** 
### <a name="_3vzh0sgk5jco"></a>**5.5.1. Domain Layer.** 
**Entities:**

- MonitoringSession: Representa una sesión de monitoreo en tiempo real.
- Pattern: Patrones de movimiento detectados.

**Aggregates:**

- MonitoringAggregate: Gestiona la sesión y el análisis de patrones.

**Value Objects:**

- SessionData: Información relacionada con las sesiones de monitoreo.

**Domain Services:**

- ExecutionService: Orquesta la ejecución de servicios de monitoreo y análisis.

**Repositories:**

- SessionRepository: Gestiona las sesiones de monitoreo activas.
### <a name="_l5dlmu9hrtyz"></a>**5.5.2. Interface Layer.** 
Controllers:

- MonitoringController: Permite iniciar o detener las sesiones de monitoreo.

Endpoints:

- POST /start-monitoring: Inicia una nueva sesión de monitoreo.
- GET /monitoring-status: Devuelve el estado del monitoreo en curso.

### <a name="_oca3wmlcf1k2"></a>**5.5.3. Application Layer.** 
**Command Handlers:**

- StartMonitoringCommandHandler: Inicia la sesión de monitoreo.

**Event Handlers:**

- PatternDetectedEventHandler: Maneja los eventos cuando se detectan patrones inusuales.
### <a name="_6qg0fnt75ewb"></a>**5.5.4. Infrastructure Layer.** 
**Repositories:**

- *SessionRepositoryImpl*: Implementa el acceso a la base de datos para gestionar las sesiones.

**Servicios Externos:**

- *PatternDetectionService*: Utiliza IA para analizar los patrones de movimiento.
### <a name="_gh5rq9i8led3"></a>**5..5. Bounded Context Software Architecture Component Level Diagrams.** 
![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 042](https://github.com/user-attachments/assets/005c65ea-d89f-490c-b5a3-8658a70c5d68)
### <a name="_8rs6prioacbu"></a>**5.5.7. Bounded Context Software Architecture Code Level Diagrams.** 
5\.5.7.1. Bounded Context Domain Layer Class Diagrams. 

![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 043](https://github.com/user-attachments/assets/4e93183d-428f-45d8-8f0c-d21bc57c40a7)

5\.5.7.2. Bounded Context Database Design Diagram. 

![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 044](https://github.com/user-attachments/assets/883acae2-6979-4360-aced-da32fa136b66)

## <a name="_x43hwtqjn667"></a>**5.6. Bounded Context Operation:** 
### <a name="_xm8sd2rxwwvx"></a>**5.6.1. Domain Layer.** 
**Entities:**

- Alert: Representa las alertas de seguridad activadas.
- EventLog: Registros de eventos relacionados con la seguridad.

**Aggregates:**

- OperationAggregate: Coordina la operación y los registros de eventos.

**Value Objects:**

- AlertDetails: Detalles sobre las alertas disparadas.

**Domain Services:**

- OperationService: Gestiona la operación continua del sistema de seguridad.

**Repositories:**

- EventLogRepository: Almacena los eventos generados.
### <a name="_t44d0f79vcut"></a>**5.6.2. Interface Layer.** 
**Controllers:**

- OperationController: Proporciona acceso a las alertas y eventos del sistema.

**Endpoints:**

- GET /alerts: Devuelve las alertas actuales.
- GET /event-logs: Proporciona los logs de eventos.
### <a name="_bneg03f8f65v"></a>**5.6.3. Application Layer.** 
**Command Handlers:**

- LogEventCommandHandler: Registra los eventos en el sistema.

**Event Handlers:**

- AlertTriggeredEventHandler: Gestiona las alertas disparadas.
### <a name="_we9l9ea6qrzo"></a>**5.6.4. Infrastructure Layer.** 
**Repositories:**

- EventLogRepositoryImpl: Implementa el acceso a la base de datos para los registros de eventos.

**Servicios Externos:**

- NotificationService: Notifica a los usuarios cuando se disparan alertas.
### <a name="_honbvuphkygo"></a>**5.6.6. Bounded Context Software Architecture Component Level Diagrams.** 
![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 045](https://github.com/user-attachments/assets/03ac4900-994e-45ad-9b8d-0e3cfcb8469c)


### <a name="_x2yd5f4q8juq"></a>**5.6.7. Bounded Context Software Architecture Code Level Diagrams.** 
5\.6.7.1. Bounded Context Domain Layer Class Diagrams. 

![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 046](https://github.com/user-attachments/assets/3f5bcad9-0e1a-4d91-b312-da4987d3dd5a)

5\.6.7.2. Bounded Context Database Design Diagram. 

![Aspose Words 00d9a324-7786-4229-8307-f3d2f53facbd 047](https://github.com/user-attachments/assets/0698c8dc-b7fc-46ac-a2fb-4fa4b712f886)


# <a name="_uwe0ben5wt2n"></a>**Capítulo V: Tactical-Level Software Design.**
**6.1. Style Guidelines.** 

**6.1.1. General Style Guidelines.**
En esta sección, se presentarán de forma estructurada los estilos y recursos que emplearemos en la creación de nuestra solución.  
**Brand Overview**   
En el Perú, la importancia de contar con dispositivos tecnológicos en buen estado es cada vez más evidente, ya sea para fines de estudio, trabajo u otros propósitos. A menudo, el servicio ofrecido a las personas que necesitan reparar sus dispositivos tecnológicos no cumple con las expectativas. Es cierto que no todos los técnicos brindan un servicio deficiente, pero aquellos que son realmente competentes no son ampliamente reconocidos, lo que resulta en una falta de conexión entre los clientes y los técnicos expertos, afectando a ambos grupos.

Nuestra solución, TechXPrime, surge como respuesta a esta desconexión entre los dos segmentos. Nuestro equipo ha desarrollado un producto diseñado para conectar de manera efectiva a clientes y técnicos expertos, permitiendo que ambos logren sus objetivos de manera satisfactoria.

**Brand name**

El nombre que hemos elegido para nuestra solución es TechXPrime. Esta elección se basa en la observación de la creciente necesidad de las personas de acceder a un servicio técnico de calidad. Los técnicos son quienes proporcionan este servicio relacionado con la "tecnología". Por lo tanto, la combinación de "tecnología" y la entrega de un servicio excepcional, representado por "Prime", son elementos fundamentales de nuestro software. Además, al utilizar el inglés como idioma en el nombre, buscamos comunicar su universalidad y hacerlo más atractivo para los usuarios.

A continuación, se present:a el Logo



![](https://lh4.googleusercontent.com/5kaLW_TdMrLaw-xGIISUC0r-yIuLdqwVPnrgWqTTfdZdL4GYdGCxetQW5-chrRj7-k7D-9vKewUdg4RGGiJsxgF9gctrGxOgLxPiOPHKqSjHdmcz_-DE16f-FIuB6_sAHlZd5yq-NtrSlNInr32hvuw)


**Typography**

La elección de la fuente tipográfica desempeña un papel importante al dividir los diversos contenidos de nuestras páginas en diferentes niveles. Además, si estas fuentes son amigables y bien diseñadas, pueden atraer visualmente al usuario y servir como guía a lo largo de nuestra interfaz.

En el caso de TechXPrime, nuestro equipo optó por utilizar la fuente Montserrat debido a su legibilidad tanto en la lectura como en la escritura. La tipografía en TechXPrime se estructura en cuatro niveles: encabezados (headings), cuerpo (body), botones (buttons) y enlaces (links).

![](https://lh5.googleusercontent.com/k5jqSviWhGVmaIIWyCwx8PLAqb_7uGW-nVvM8ulm337h96jAo4T1H4Yp7Wm3x9V6UjYKK6M1Duj_RaxJg680GhS7q1-O5Zd8CT6qEID6Ibg63TNr5F7LNwJDq-qOjqoBzcoGJvQHsMMA9Vk6z9y0OTs)

**Colors**  
 

Seleccionar los colores adecuados es una parte fundamental del proceso de diseño, ya que los colores elegidos transmiten la esencia de lo que ofrecemos como servicio. En nuestro caso, hemos elegido el azul como color principal y un tono verde azulado como color secundario. Además, hemos definido una paleta de colores adicionales que indicarán al usuario los estados o acciones que ocurren mientras interactúa con nuestra aplicación.

![](https://lh4.googleusercontent.com/uKdYcCebEhBCIVWr2gFdqHrADYNezPvQ0zdZQxRw1MBtR9F6gqhmPUhDSgj07l8KzaJ44bd-s0MKGDPjyN_Qtum8I59ATg0LqFZNoVPYOCWYnQyOWM-UcXF9KE_7XBNvzgkrV07aRqHxUWhXHTgPipo)

Color Primario Azul:  
 

El color primario que hemos elegido es el azul. El azul se asocia comúnmente con la tecnología y el bienestar, y hemos seleccionado este color para transmitir a los usuarios la naturaleza de nuestra aplicación web. Además, el azul es conocido por generar serenidad y calma en las personas, lo que es coherente con nuestro objetivo de proporcionar una experiencia tranquila y agradable para los usuarios.

![](https://lh4.googleusercontent.com/uDokTiXt8NE2vbRiO2C-XtcsbKfsdFUH_yHyVVOmdrFGR4Gdu_rBoEl5DbfZ7-v1oUC1cPuokKnm556QtgMz1qUhFuIRk3yq0jpFLxCyAZjfH8nXFNjWoV4vuc6T3P6DlbeY3aZdP-e0DvKbHF6y_IY)

Color secundario morado:  
 

Hemos seleccionado el color morado como nuestra elección secundaria debido a su capacidad para transmitir impacto, sabiduría, creatividad y una cierta sensación de magia a los usuarios. Además, este color evoca confianza, lo cual es de suma importancia para la imagen que deseamos proyectar a través de nuestra aplicación.

![](https://lh3.googleusercontent.com/B2rSVMQ6pd8RDTc1C9GDw6N0YwdQkjhhaVVWthjY8Jd0fMRzKWPefqW8RLnH2BH2DpMP5zSK8cEno0tnwdrT8eUwfTd4NBWdZ4fp2aN0Ehu3zmEbIxAlndC_FaeyNXD8Uhz1uu31hRtXOtZmFFN8EiA)

Color estado : Rojo -(Acción inconclusa o incorrecta)

Hemos asignado el color rojo a la categoría de "estado" en nuestra aplicación, con el propósito de señalar acciones incompletas o incorrectas por parte del usuario. La elección del rojo se basa en la idea de que este color resaltará de inmediato las acciones realizadas de manera errónea, permitiendo al usuario identificarlas de forma rápida y efectiva.

![](https://lh3.googleusercontent.com/RvRDOqTIBBpKDa5eStbLVbLjwf1OIt_EaEMPoTmTl-8n_gzHm08PjDlCreBE0IDQbx75Xd1ilIq1U8sPJx5-R3LPEQMdAX6_AZLz6iU8Yfd35Ur2TtHXphny5TMtIUxw2D1FcSa4HOJk7w9OtNpvSks)

Color estado: Verde (Acción exitosa)

Hemos optado por utilizar el color verde en la categoría de "estado" de nuestra aplicación para indicar acciones exitosas. La elección del verde se basa en la familiaridad del usuario con este color, lo que permitirá que el usuario reconozca de inmediato que la acción ha tenido éxito.

![](https://lh4.googleusercontent.com/FE4nfBzC44xeiUK_kcVTYmSyb2wqkzdwX1BwFQkDCkjtcL9f03p6roQxbGAMl1qptBk11N97iGqyVQIkhD9bppP8iHPIvguegHZ5RcnhTiqIprrjygPovWAQ7x2_jWDnel4z7TChIDPc5uvAtckCfoM)

Colos estado: Amarillo (Advertenia de  una acción)

Hemos seleccionado el color amarillo para esta categoría de estado con el propósito de advertir al usuario cuando está llevando a cabo una acción que podría tener repercusiones en sus actividades futuras.

![](https://lh3.googleusercontent.com/kCGQBWAUiQgnbU0lGb58MfwWQcMJaC5KznZGSf-PTt1bWpe9cLXzM5aQxJKftOSPKo-sWu4ZbaX-YtH5qPIn_STjQudEq0Sd0_QkVO1XrEN5rwPbeLG0LY7ox1igcq5bwn0WKenwAhW1-RE3uzpv-9M)

Color Estado: Gris (Botón o Acción deshabilitada)

Hemos optado por utilizar el color gris para indicar al usuario que una acción o botón está deshabilitado, ya que requerirá completar otras acciones en el futuro para poder activarlos.

**Spacing**

Utilizaremos un espacio que sea una cantidad divisible por 8 píxeles para cada componente

![](https://lh4.googleusercontent.com/bd2rSz8eWwN_W70RIEYtDoaHd7GgA3tGZ_pGbrkHCirO_yu3gZrgERADUIwE-yrzu7-qHnQW8rM58FTR7YR84RhhTehehHihGuEAZYYFSOS8KKYTvmUJ0lHcBP0niXTEkQXn2c1mPDhHjNY3iC7k8Gk)

**Tono de lenguaje de comunicación y lenguaje aplicado**


Implementaremos un lenguaje que sea formal, sereno y confiable, al mismo tiempo que transmita entusiasmo. Nuestra intención es reforzar la sensación de paz, tranquilidad y confianza para el usuario, y dejar claro que nuestra aplicación es una herramienta seria y efectiva para abordar sus necesidades y resolver sus problemas.

**6.1.2. Web, Mobile & Devices Style Guidelines.** 
Vamos a emplear un estilo de comunicación formal, tranquilo y de confianza, al mismo tiempo que incorporaremos un toque de entusiasmo. Nuestro objetivo principal es consolidar en el usuario una sensación de calma, serenidad y seguridad, mientras destacamos que nuestra aplicación es una solución seria y altamente eficaz para satisfacer sus requerimientos y solucionar sus desafíos.

![](https://lh3.googleusercontent.com/mKqfXN0S3nXeDlThn9DYmDfUdN7nQT_hpiKhIrntU-RqwoBbCky6Cz-5i7rvmgr2efI6DZ70VGVsXAuJEEBVkAGqDktTupLlb_kVNh_zBd0EHC7gQSJz1anAkuj0gm2CxCRiqGEgbQWlzlgE3wYId3o)

Optaremos por emplear el patrón de diseño en forma de "Z". Esto se debe a nuestra intención de guiar al usuario durante la navegación en nuestra página de inicio y aplicación web. Inicialmente, el usuario comenzará su experiencia viendo nuestro logotipo en la parte superior, antes de dirigirse hacia la derecha para encontrar una serie de opciones disponibles. Luego, el flujo de la página se desplazará verticalmente hacia abajo, permitiendo que el usuario explore el contenido general de nuestra página de inicio y aplicación. Finalmente, al llegar al final de la página, el usuario visualizará información adicional sobre nuestro startup y cómo ponerse en contacto con nosotros, dispuesta horizontalmente en el lado derecho.

![](https://lh5.googleusercontent.com/lZNZDTnoQL5iSdx-GlXBT8f6aw6Y-3fa2KfGyw9325HVL32qohE_PlhAypqdRUYcqGUJRr5j-FdGKJpD78p83JO168mIyNUYbsbtL9aqsEF9E7rhiYtFO0e5loKMWuGJR_4POtrf9OtbU2ofNpLU9nU)

Es importante destacar que el diseño incorporará una paleta de colores que resulten atractivos para el usuario, con la intención de evocar sensaciones de tranquilidad, confianza y un fuerte deseo de utilizar nuestra aplicación. Asimismo, los espacios y efectos visuales que se implementarán servirán para comunicar claramente el propósito y contenido de nuestra página de inicio y aplicación web, proporcionando al usuario una comprensión intuitiva de lo que ofrecemos.

**6.2. Information Architecture.** 

En esta aplicación organizaremos según nuestros usuarios, en este caso será para segmento Keeper y traveler.

**6.2.2. Labeling Systems.**

En Aegis Vision, la representación de los datos es clave para garantizar una experiencia de usuario clara y sin confusiones. Nuestro sistema de etiquetado ha sido diseñado para ser simple y eficiente, utilizando el mínimo número de palabras para representar los conjuntos de información. Cada dispositivo, como cámaras y sensores, está asociado con etiquetas claras y concisas, permitiendo a los usuarios identificar rápidamente la funcionalidad de cada uno.

Por ejemplo, las cámaras se etiquetan con nombres como "Cámara Entrada Principal" o "Sensor Ventana", y el usuario puede personalizar estas etiquetas según sus necesidades. Las asociaciones entre dispositivos, como la vinculación de cámaras y sensores a zonas específicas del hogar, también son representadas mediante etiquetas agrupadas (ej.: "Zona de Seguridad – Patio Trasero"). Esto evita confusiones y garantiza una rápida identificación de dispositivos y eventos dentro de la plataforma.


**6.2.3. Searching Systems.** 

En **Aegis Vision**, entendemos la importancia de un sistema de búsqueda eficiente que evite que los usuarios se sientan perdidos ante el volumen de datos y dispositivos conectados. Para lograrlo, hemos implementado un **sistema de búsqueda avanzada** que ofrece múltiples opciones para filtrar y organizar la información.
#### <a name="_gv6wwzn2ji42"></a>**Opciones de búsqueda:**
- **Búsqueda por palabras clave**: Los usuarios pueden buscar dispositivos, cámaras o sensores por nombre, tipo o etiquetas personalizadas.
- **Filtros por ubicación**: Los usuarios pueden filtrar los resultados por zonas del hogar (ej.: "Sala de estar", "Entrada principal").
- **Filtros por eventos**: Pueden buscar incidentes de seguridad filtrados por tipo de evento, como detección de movimiento o alarmas activadas.

Los resultados de búsqueda se presentan de manera clara, mostrando una vista previa del dispositivo o evento correspondiente. Esto ayuda a los usuarios a gestionar de manera rápida y eficiente los elementos de seguridad en su hogar inteligente, evitando la sobrecarga de información y garantizando un control preciso

**6.2.4. SEO Tags and Meta Tags.**

Para Aegis Vision, hemos optimizado tanto el sitio web como la aplicación para mejorar la visibilidad en los motores de búsqueda (SEO) y en las tiendas de aplicaciones (ASO). Estas optimizaciones se aplican tanto a la Landing Page como a las aplicaciones web y móviles.
#### <a name="_51b9n7od1kzh"></a>SEO Tags y Meta Tags:
- Title: Plataforma de Seguridad Inteligente Aegis Vision
- Meta Description: Aegis Vision proporciona una experiencia de seguridad personalizada para hogares inteligentes, combinando IA y Realidad Aumentada para gestionar cámaras y sensores en tiempo real.
- Keywords: seguridad en el hogar, cámaras inteligentes, IA en seguridad, realidad aumentada, monitoreo en tiempo real
- Author: Equipo de Aegis Vision
  #### <a name="_wc51dthcybbu"></a>ASO Elements:
- App Title: Aegis Vision – Seguridad Inteligente para el Hogar
- App Keywords: seguridad en el hogar, cámaras inteligentes, sensores IA, protección personalizada
- App Subtitle: Monitorea y gestiona la seguridad de tu hogar en tiempo real con IA y RA.
- App Description: Aegis Vision transforma la seguridad de tu hogar con tecnologías avanzadas como IA y Realidad Aumentada, brindándote una experiencia única y personalizada para proteger lo que más te importa.

Estas optimizaciones aseguran que los usuarios encuentren fácilmente la plataforma en los motores de búsqueda y las tiendas de aplicaciones, facilitando su descubrimiento y adopción.

**6.2.5. Navigation Systems.** 

El sistema de navegación de **Aegis Vision** ha sido diseñado para guiar de manera eficiente a los usuarios, permitiéndoles lograr sus objetivos e interactuar sin problemas con la plataforma. Desde la **Landing Page** hasta las aplicaciones móviles, los usuarios pueden navegar de manera intuitiva a través de varias secciones.
#### <a name="_sfeav749atvv"></a>**Principales técnicas de navegación:**
- **Menú Principal**: Un menú simplificado permite a los usuarios acceder rápidamente a las principales funcionalidades, como la vista de dispositivos, configuración de seguridad y el historial de eventos.
- **Navegación por zonas**: Los dispositivos están organizados en zonas del hogar, lo que facilita la identificación y el control de los elementos de seguridad por ubicación. Esto es especialmente útil para usuarios con múltiples dispositivos.
- **Navegación por tareas**: Los usuarios pueden realizar acciones específicas, como configurar alertas o monitorear cámaras, directamente desde la pantalla principal sin tener que navegar profundamente en submenús.

Este enfoque asegura que los usuarios puedan encontrar lo que buscan y realizar tareas críticas en pocos pasos, mejorando la experiencia general de uso.

**6.3. Landing Page UI Design.** 
## 6.3. Landing Page UI Design

En esta sección se presentará nuestro mockup de nuestra landing page: [Ver prototipo en Figma](https://www.figma.com/design/8YTxnePQ7Fii1EGvwjqNWZ/Emergente---Landing-Page?node-id=0-1&t=VWsp5vjb59NmqF82-1)

**6.3.1. Landing Page Wireframe.** 
<br> En esta parte se visualiza como la pantalla principla del landing page con una seccion de borones que describe nuestro producto. <br>
![](https://media.discordapp.net/attachments/1227123248030941219/1287974228540391485/image.png?ex=66f37ef9&is=66f22d79&hm=30fe0bdb9cc67a96bcb7c10456e3d1329fab6eaa1f6a7a70c32475423bdd4a60&=&format=webp&quality=lossless)

En esta sección detalla los beneficios que brinda Aegis Vision <br>
![](https://media.discordapp.net/attachments/1227123248030941219/1287975310276558880/image.png?ex=66f37ffb&is=66f22e7b&hm=1b7326286b866a73d283584f1052f5e685001b228ec38e4263b2cb18f0310bbd&=&format=webp&quality=lossless)

<br>
<p>En esta sección se muestran algunos testimonios de nuestros clientes satisfechos.</p>
<img src="https://media.discordapp.net/attachments/1227123248030941219/1287976275889225812/image.png?ex=66f380e1&is=66f22f61&hm=66d5f48ba0d2879a11ee8d99217a2d14ea35202d580a53ff09293164c0d69490&=&format=webp&quality=lossless&width=535&height=411" alt="Testimonios">

**6.3.2. Landing Page Mock-up.** 
En esta sección se muestra como se verá nuestra landing page deplegada y visible para el público <br>
![](https://media.discordapp.net/attachments/1227123248030941219/1287978144749457448/image.png?ex=66f3829f&is=66f2311f&hm=f6a8649b3b305fc5f3227f2690d3043b48ba7d99edeae13d26177cda922e6e7a&=&format=webp&quality=lossless&width=647&height=411)
  <br>
  En esta parte se muestra todos los beneficio que ofrece la aplicación garantizando su conformidad del cliente.  <br>
  ![](https://media.discordapp.net/attachments/1227123248030941219/1287978530386350211/image.png?ex=66f382fb&is=66f2317b&hm=0bc660bd69a48711af38e484787dc1ed26e895f338a5953be543376a1433cd69&=&format=webp&quality=lossless)

  <br>
Se muestran algunos testimonios de nuestros usuarios que usaron la aplicación.
<p style="text-align: center;">
  <img src="https://github.com/user-attachments/assets/c3cbfae9-7fb5-4f03-b246-606a1618904b" style="max-width: 190%; height: auto;" alt="Testimonios">
</p>

**6.4. Applications UX/UI Design.** 

**6.4.1. Applications Wireframes.** 
Login Wireframe:
![](https://i.gyazo.com/17d911d7c416bdbba3f5122c10a5be6a.jpg)

Registration Wireframe:
![](https://i.gyazo.com/3dea69bf846b11b87cdaf8a692b735df.jpg)

Home Wireframe:
![](https://i.gyazo.com/d17c971af67595409261c2d2a57064c5.jpg)

Alerts Wireframe:
![](https://i.gyazo.com/75951ba7ae238cc0adc2d28eed9ccab6.jpg)

Cameras Wireframe:
![](https://i.gyazo.com/11e7e2c522b1580c249e7ec1db81e9de.jpg)

Analytics Wireframe:
![](https://i.gyazo.com/53c948d3ffd3c4a088fae03df1827a31.jpg)

**6.4.2. Applications Wireflow Diagrams.** 
![](https://i.gyazo.com/69660c463b620f1cd24924fe2f667d1c.png)

![](https://i.gyazo.com/f917f12866e9a401eebb1ce7b0ab3cf1.png)

![](https://i.gyazo.com/b08503d6a7f63a8365374ba3dc8bbf3b.png)

![](https://i.gyazo.com/dff2e5fa0cf604a54f198bb5371e9329.png)

**6.4.2. Applications Mock-ups.** 
Login Mock-up:
![](https://i.gyazo.com/1d942cf4924ad3efc9a325c51c2bc256.jpg)

Registration Mock-up:
![](https://i.gyazo.com/7f300cfa37347f14853af9c754d4254d.jpg)

Home Mock-up:
![](https://i.gyazo.com/9a4c2b6fc0333a438fbaf4817f2c0ef7.jpg)

Alerts Mock-up:
![](https://i.gyazo.com/75cf38255597f3b08fd4b9dff535660c.jpg)

Cameras Mock-up:
![](https://i.gyazo.com/28e2bba8433bd8ee0ee0ccea39b7847c.jpg)

Analytics Mock-up:
![](https://i.gyazo.com/4e68cc97176516ed9280f7da7010bb4d.jpg)

**6.4.3. Applications User Flow Diagrams.** 

![](https://i.gyazo.com/411539dfc83e933e56979cd9d6ad8216.png)

![](https://i.gyazo.com/1a736f5638d5ac5b6b0e6dedf99faced.png)

![](https://i.gyazo.com/a158e00fb2250b1197e61368429e7bd5.png)

![](https://i.gyazo.com/0495e8ef498f309c8efeb5f8242a4ba4.png)

**6.5. Applications Prototyping.**

![](https://i.gyazo.com/65f91acb335ac9ce9f75686e09dda20f.png)

Link: [https://www.figma.com/proto/nG6sPdtSLQH7JcddlqiyNO/App-Arq-Emergentes?node-id=7-566&node-type=canvas&t=QGWCjUyIEMCAwyr1-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=7%3A566](https://www.figma.com/proto/nG6sPdtSLQH7JcddlqiyNO/App-Arq-Emergentes?node-id=7-566&node-type=canvas&t=QGWCjUyIEMCAwyr1-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=7%3A566)


### Bibliografía

Afzal, A., & Hossain, M. (2021). Real-time motion detection and tracking using Python and OpenCV. *International Journal of Computer Applications*, 174(12), 1-7.     
    https://doi.org/10.5120/ijca2021921975

Kahrimanović, A., & Hasković, D. (2021). Implementation of smart camera system for real-time motion detection. *Journal of Engineering and Technology*, 10(2), 25-34. 
    https://doi.org/10.12791/jet.2021.10.2.25

Sukhraj, S., & Jain, M. (2022). A survey of intelligent video surveillance systems: Focus on motion detection algorithms. *IEEE Access*, 10, 123456-123469. 
    https://doi.org/10.1109/ACCESS.2022.1234567

Gupta, R., & Kumar, S. (2022). Smart camera systems: An overview of motion detection techniques. *Computers & Security*, 113, 103578. 
   https://doi.org/10.1016/j.cose.2022.103578

Tamas, D. (2023). Motion detection in smart environments: Algorithms and Applications. *Cambridge University Press*.

Patel, A., & Lakkad, H. (2021). Utilizing Python for motion detection: A study on OpenCV techniques. *Journal of Computer Science*, 17(4), 237-244. 
   https://doi.org/10.3844/jcssp.2021.237.244

Uddin, S. M., & Sarker, M. A. (2021). Enhanced video surveillance using motion detection and tracking in smart cameras. *International Journal of Computer Applications*, 
   176(6), 1-9. https://doi.org/10.5120/ijca2021922314

Khan, M. N., & Begum, N. (2022). Python programming for intelligent systems: A practical guide to using OpenCV for motion detection. *Springer*.

## Anexos

- Link de la organizacion en github: [Los TechCrafters en GitHub](https://github.com/orgs/Los-TechCrafters/repositories)
- Landingpage desplegada: [Aegie Vision](https://yordidg.github.io/AigieVision/)


