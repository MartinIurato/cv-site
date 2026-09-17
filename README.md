# Martín Iurato

**Especialista en Datos y Analytics**
Data Architecture · Analytics Engineering · SQL Server · Power BI

[Ver el CV en el sitio](https://martiniurato.github.io/cv-site/) · [CV completo en PDF](cv-base-es.pdf) · [CV de una página en PDF](cv-short-es.pdf) · [LinkedIn](https://linkedin.com/in/martin-iurato) · [GitHub](https://github.com/MartinIurato)

## Cómo está hecho

Este CV es código. Lo que sigue es el flujo completo, de la fuente a esta página.

**La fuente es única.** Los hechos viven una sola vez, en archivos YAML: cada puesto con sus líneas de experiencia, sus tecnologías y sus categorías, más formación, idiomas y competencias. Nada se escribe dos veces, y ningún texto visible nace fuera de ahí.

**Un validador corre antes de cada generación y corta el build si algo no cierra:** un término de competencias sin una línea de experiencia que lo respalde, un identificador repetido o inexistente, un texto sin traducir, una fecha con formato inválido, un caso de estudio referenciado que no existe. Si hay un error, no se genera nada.

**Los perfiles seleccionan y ordenan.** Cada versión del CV —la completa, la de una página— es una lista explícita de qué entra y en qué orden, más opciones de presentación. Un perfil no puede agregar ni modificar un hecho: si algo tiene que aparecer, primero se carga en la fuente.

**Las plantillas ponen la forma y nunca el contenido:** layout, tipografía y color. Cambiar de plantilla cambia cómo se ve el CV, jamás lo que dice.

**Del mismo contexto salen las tres salidas:** el PDF, el HTML de pantalla y este Markdown. Por eso dicen exactamente lo mismo y no pueden desincronizarse.

**La publicación es un paso más del build.** Un script genera la salida, la copia a este repositorio y deja los cambios a la vista para revisarlos antes del push.

**Las decisiones se registran como ADR** —14 hasta hoy— con su contexto, sus consecuencias y las alternativas descartadas. Un ADR publicado no se edita: una decisión que se reemplaza se escribe de nuevo.

**El build no llama a ninguna IA.** Es determinístico: el mismo dato produce siempre la misma salida.

**Este repositorio es la salida, no el proyecto.** El código, la fuente en YAML, los perfiles y las decisiones viven en un repositorio privado. Acá llega solo lo que se publica, y no se edita a mano: un cambio hecho acá se pierde en la próxima publicación.

## Qué contiene

| Archivo | Qué es |
|---|---|
| `index.html` | El CV para pantalla |
| `cv-base-es.pdf` | CV completo en PDF |
| `cv-short-es.pdf` | CV de una página en PDF |
| `.gitattributes` | Marca los PDF como binarios para que no se corrompan al clonarlos |
| `.nojekyll` | Indica a GitHub Pages que sirva los archivos tal cual, sin procesarlos |

Se publica con GitHub Pages desde la rama `main`, carpeta raíz.

## CV

Buenos Aires, Argentina · <martiniurato@gmail.com>

### Perfil profesional

Profesional de tecnología y datos con trayectoria en desarrollo de software, sistemas empresariales, gestión de proyectos y arquitectura de datos.

Foco en arquitectura de datos, calidad, trazabilidad y gobierno, con atención a que las soluciones no solo funcionen: que se entiendan, se puedan mantener y se presenten de forma clara para quien las usa.

### Core Expertise

- **Datos:** Data Warehousing · Modelado dimensional · SQL Server · T-SQL · ETL · Python · Calidad y conciliación de datos
- **Analytics:** Power BI · Microsoft Fabric · Modelo semántico · DAX · RLS · Dataflows
- **Gobierno técnico:** ADRs · GitHub · Versionado de esquemas · Trazabilidad de cambios
- **Gestión:** Coordinación de proveedores · Mercado de capitales

### Experiencia

#### DA Valores

Coordinador de TI · Data Architecture & Analytics Engineering · Buenos Aires · 05/2025 – actualidad

Referente de IT, responsable de la evolución de la plataforma de datos y de las soluciones tecnológicas de la compañía, coordinando proveedores y equipos tercerizados en un entorno financiero regulado.

- Diseñé e implementé el Data Warehouse corporativo sobre SQL Server: capas, modelo en estrella y vistas que alimentan más de 40 reportes en Power BI.
- Definí e implementé el gobierno técnico del área: ADRs, documentación como código, GitHub, versionado de esquemas, trazabilidad de cambios y estándares de arquitectura.
- Construí y opero ETLs productivos en Python y SQL Server que integran información transaccional, administrativa y de mercado.
- Rediseñé la arquitectura analítica hacia un modelo semántico centralizado en Power BI sobre Microsoft Fabric.
- Diseñé e implementé una plataforma productiva de conciliación bilateral entre datos internos y de mercado.
- Implementé mecanismos de historización de atributos que el sistema origen no conserva, utilizando vigencias para reconstruir correctamente relaciones y segmentaciones sobre períodos históricos ya cerrados.
- Automaticé procesos operativos y de control.
- Diseñé e implementé un sistema productivo de control de riesgo crediticio, con aplicación en C# y tablero de seguimiento en Power BI.

*Tecnologías: SQL Server, T-SQL, Power BI, Git, GitHub, Python, SQL Agent, DAX, Dataflows, Microsoft Fabric, C#*

#### L'Oréal Argentina

Analista Funcional Sr. · Buenos Aires · 10/2011 – 05/2025

Trayectoria en análisis funcional, gestión de proyectos, sistemas empresariales, Business Intelligence e integraciones en un entorno regional e internacional.

- Gestioné proyectos de sistemas empresariales, principalmente SAP y sistemas satélite, y de datos con Power BI.
- Coordiné equipos y stakeholders de Argentina, Chile, Uruguay, México y Estados Unidos.
- Participé en implementaciones e integraciones sobre SAP, SQL Server y Power BI.
- Coordiné ciclos de testing, UAT, gestión de incidentes, troubleshooting y resolución de problemas productivos.
- Participé en iniciativas de DRP, articulando negocio, equipos técnicos y proveedores.

*Tecnologías: SAP, Power BI, SQL Server*

#### Telecom Argentina (vía Pragma Consultores)

SharePoint & Project Server Developer · 01/2011 – 10/2011

- Desarrollo y administración sobre SharePoint 2007 y Project Server 2007.

#### Atento Argentina

Desarrollador C# / SQL Server · 03/2009 – 01/2011

- Desarrollo de aplicaciones con C#, ASP.NET, Visual Studio y SQL Server.

#### Grupo Hasar

Desarrollador C# · 08/2007 – 03/2009

- Desarrollo de aplicaciones para Windows Mobile con C# y SQL Server.

#### Tecnodata Sistemas Informáticos

Soporte técnico · 05/2006 – 08/2007

- Soporte, mantenimiento y resolución de problemas de infraestructura y estaciones de trabajo.

### Formación

#### Educación

- **Técnico Superior en Programación** — Universidad Tecnológica Nacional (UTN) · 2003 – 2005

#### Formación complementaria

- **Full Stack Python** — Ministerio de Educación de la Ciudad de Buenos Aires · 2022
- **Arquitectura de software: Diseño de sistemas de software esencial** — LinkedIn Learning · 03/2024
- **GitHub para programadores** — LinkedIn Learning · 03/2024
- **Aprende gobernanza de datos** — LinkedIn Learning · 07/2024
- **Fundamentos de la ingeniería de datos** — LinkedIn Learning · 07/2024
- **Python esencial** — LinkedIn Learning · 09/2024
- **Descubre las capacidades de Microsoft Power Apps** — LinkedIn Learning · 09/2024

### Idiomas

- Inglés (intermedio, B1)
