# Actualización del roadmap — 7 de septiembre de 2026

Fuente: [Microsoft 365 Roadmap](https://www.microsoft.com/es-es/microsoft-365/roadmap) (API pública de Microsoft Release Communications).

Esta es la línea base inicial de esta base de conocimiento: recoge los elementos relacionados con Copilot, agentes e IA publicados o modificados en el roadmap entre el **20 de julio y el 2 de septiembre de 2026** (42 elementos). Las próximas ejecuciones programadas añadirán solo lo que sea nuevo respecto a esta fecha.

## Destacados

- **MCP (Model Context Protocol) como eje de integración**: varias novedades de Copilot Studio y de M365 Copilot usan MCP para conectar agentes con herramientas y fuentes de datos externas en tiempo real, sin indexar datos en Microsoft (*Federated Copilot Connectors*, *Copilot Studio: rich interactive app experiences vía MCP Apps*).
- **Aprobación humana para acciones de agentes**: Copilot Studio permitirá exigir aprobación humana antes de que un agente ejecute herramientas sensibles (enviar correos, cerrar tickets, procesar pagos), con la solicitud apareciendo en Teams o M365 Copilot.
- **Memoria de Copilot**: se extiende a Researcher (contexto de interacciones pasadas) y Purview añade retención/versionado para los ítems de memoria (guardados en una carpeta oculta del buzón de Exchange), pensado para cumplimiento e investigación.
- **Copilot Notebooks gana fuentes de conocimiento**: ahora admite Power BI, imágenes (JPG/PNG) y datos estructurados (CSV/TSV) como referencias, además de una nueva versión para nubes gubernamentales (DoD, GCC, GCC High).
- **Chat de Copilot en bloques editables**: "Writing blocks" y "Code blocks" permiten editar texto, código, gráficos y diagramas directamente en línea dentro del chat, sin salir a un canvas aparte.
- **Expansión a nubes gubernamentales**: Copilot Chat (Teams) y Viva Insights/Copilot Analytics llegan a GCC, GCC High y DoD.

## Microsoft 365 Copilot (Chat, Notebooks, conectores)

| Estado | Función | Descripción | Disponibilidad general |
|---|---|---|---|
| En desarrollo | Bloques de escritura (*Writing blocks*) | Edita borradores, memos y correos en línea dentro del Chat. | Septiembre 2026 |
| En desarrollo | Bloques de código (*Code blocks*) | Previsualiza código, gráficos y diagramas en línea en el Chat (antes solo en canvas). | Septiembre 2026 |
| En desarrollo | Publicación delegada de prompts de organización | Los admins pueden delegar en usuarios/grupos la creación de prompts corporativos desde el Prompt Lab. | Septiembre 2026 |
| En desarrollo | Conectores federados de Copilot | Conecta Copilot a fuentes de terceros en tiempo real vía MCP, sin indexar datos en Microsoft; disponible en Researcher y M365 Chat. | Septiembre 2026 |
| En desarrollo | Conectores de sincronización autoservicio | Los usuarios conectan sus propias fuentes externas (Jira, Confluence Cloud) con sus propias credenciales. | Septiembre 2026 |
| En desarrollo | Añadir Agentes y Skills desde el menú "+" | Inserta agentes y skills especializados con `/` y `@` desde el prompt. | Septiembre 2026 |
| En desarrollo | Nuevas tarjetas de respuesta enriquecidas | Tarjetas dinámicas para clima, deportes, finanzas, imágenes, vídeo, lugares y noticias. | Agosto 2026 |
| En desarrollo | Agente de Workforce Insights | Ayuda a líderes y managers a explorar estructura, equipos y competencias de la organización desde Copilot o Teams. | Septiembre 2026 |
| En desarrollo | Memoria de Copilot en Researcher | Trae contexto de interacciones pasadas para personalizar los resultados de investigación. | Noviembre 2026 |
| Implementándose | Integración con Power BI | Copilot razona sobre datos empresariales de Power BI y responde en lenguaje natural con datos reales de informes/modelos semánticos. | Agosto 2026 |
| En desarrollo | Power BI como referencia en Copilot Notebooks | Añade informes de Power BI como fuente de contexto en los notebooks. | Septiembre 2026 |
| En desarrollo | Referencias JPG/PNG en Copilot Notebooks | Usa imágenes (texto, gráficos, diagramas) como contexto para generar informes y presentaciones. | Octubre 2026 |
| En desarrollo | Referencias CSV/TSV en Copilot Notebooks | Usa datos estructurados como contexto adicional en los notebooks. | Octubre 2026 |
| En desarrollo | Revisión de PDF en el menú contextual de Copilot (OneDrive iOS) | Selecciona texto de un PDF y pide explicar, resumir, traducir o preguntar, igual que en escritorio. | Octubre 2026 |
| En desarrollo | Capacidades de archivos mejoradas en OneDrive Web | De archivo a resultado final (resúmenes, dashboards, presentaciones) sin salir del chat. | Diciembre 2026 |

## Microsoft Copilot Studio (creación de agentes)

| Estado | Función | Descripción | Disponibilidad general |
|---|---|---|---|
| En desarrollo | Experiencias de app interactivas vía MCP Apps | Los agentes renderizan UI interactiva (tablas, drilldowns) en la conversación al llamar herramientas MCP compatibles. | Noviembre 2026 |
| En desarrollo | Creación de agentes "app e intención primero" | Rediseño para que el creador empiece por la aplicación de destino y configure las capacidades necesarias. | Octubre 2026 |
| En desarrollo | Alineación de la experiencia de agentes con M365 Copilot Chat | Las respuestas de agentes en Copilot Chat tendrán el mismo formato, streaming y citas que el chat nativo. | Septiembre 2026 |
| En desarrollo | Aprobación humana para llamadas a herramientas | Permite exigir aprobación por herramienta/agente antes de ejecutar acciones sensibles. | Septiembre 2026 |
| En desarrollo | Compartir agentes entre creadores | Roles de "Viewer" (analíticas/evaluaciones) o "Editor" (ver, editar, publicar) con permisos de seguridad automáticos. | Octubre 2026 |
| En desarrollo | Configuración conversacional de conectores | Configura los conectores del agente con un simple inicio de sesión en el chat. | Septiembre 2026 |
| En desarrollo | Integración con Dataverse | Dataverse como fuente de conocimiento nativa para fundamentar agentes en datos empresariales. | Septiembre 2026 |
| En desarrollo | Soporte de SQL Server (Azure SQL) | Azure SQL como nueva fuente de conocimiento para agentes. | Septiembre 2026 |
| En desarrollo | Mejoras en evaluaciones de agentes | Explicaciones más detalladas, trazas de razonamiento, citas, comparación de ejecuciones y generación de datasets de prueba. | Septiembre 2026 |
| En desarrollo | Agent Readiness | Indicador de estado en tiempo real que detecta bloqueos (políticas, evaluaciones faltantes) antes de publicar un agente. | Septiembre 2026 |
| En desarrollo | Compartir agentes autónomos en modo solo ejecución | Los usuarios finales pueden usar agentes autónomos sin permisos de edición. | Enero 2027 |

## Teams

| Estado | Función | Descripción | Disponibilidad general |
|---|---|---|---|
| En desarrollo | Copilot Chat en chats, canales, llamadas y reuniones (GCC, GCC High, DoD) | Disponibilidad de Copilot Chat en todos los canales de comunicación de Teams para nubes gubernamentales. | Octubre 2026 |
| En desarrollo | Habilitar agentes para apps existentes desde el Teams Admin Center | Los admins descubren y habilitan agentes de terceros ya usados en la organización, con recomendaciones guiadas. | Octubre 2026 |
| Implementándose | Recaps inteligentes de llamadas en la app Queues | Resúmenes generados por IA con puntos clave y acciones de seguimiento en llamadas grabadas. | Septiembre 2026 |
| Implementándose | Copilot Chat tras una llamada en la app Queues | Genera resúmenes o responde preguntas sobre una llamada grabada sin revisar la transcripción manualmente. | Septiembre 2026 |
| Implementándose | Gestión unificada de instalación de agentes y apps (M365 admin center + Teams admin center) | Un solo cambio de instalación se aplica de forma consistente en Teams, Outlook y M365 Copilot. | Agosto 2026 |

## Outlook

| Estado | Función | Descripción | Disponibilidad general |
|---|---|---|---|
| En desarrollo | Copilot Chat flotante en Outlook para Mac e iPad | Copilot Chat se puede desacoplar y flotar sobre la ventana principal de Outlook. | Agosto 2026 |
| En desarrollo | Nuevo punto de entrada de Copilot en Outlook clásico | Entrada consistente de Copilot, ya disponible en otros endpoints de Outlook, Word, Excel y PowerPoint, ahora en Outlook clásico. | Septiembre 2026 |

## SharePoint / OneDrive / OneNote

| Estado | Función | Descripción | Disponibilidad general |
|---|---|---|---|
| En desarrollo | Site Skills en Copilot en SharePoint | Edición, control de versiones, publicación, restauración y duplicación de skills entre sitios. | Septiembre 2026 |
| En desarrollo | Páginas HTML en SharePoint | Crea HTML con Copilot en SharePoint o sube el tuyo propio; renderízalo como página junto a las páginas ASPX existentes. | Octubre 2026 |
| En desarrollo | Nuevo diseño de Copilot Notebooks en la app M365 Copilot (DoD, GCC, GCC High) | Espacio de trabajo de IA persistente que organiza chats, resultados y referencias entre sesiones. | Septiembre 2026 |
| En desarrollo | Captura multimodal en Copilot Notebooks (Android) | Transcribe audio, captura imágenes y escribe notas en una sola sesión, generando una página estructurada. | Septiembre 2026 |

## Viva

| Estado | Función | Descripción | Disponibilidad general |
|---|---|---|---|
| En desarrollo | Viva Insights y Copilot Analytics en GCC-High | Analítica de adopción, uso e impacto de Copilot, y comportamiento colaborativo, para GCC High. | Septiembre 2026 |
| Implementándose | Viva Glint: asistencia de configuración con Copilot | Asistente conversacional integrado en la administración de Viva Glint, con enlaces directos a páginas de configuración. | Septiembre 2026 |
| En desarrollo | Copilot Dashboard: encuestas de audiencia dirigida | Lanza encuestas de pulso de Copilot desde el dashboard a audiencias específicas, combinando adopción y sentimiento. | Septiembre 2026 |

## Gobernanza, cumplimiento y administración

| Estado | Función | Descripción | Disponibilidad general |
|---|---|---|---|
| En desarrollo | Retención de memoria de Copilot (Purview – Data Lifecycle Management) | Políticas de retención y versionado para los ítems de memoria de Copilot, con fines de seguridad y cumplimiento. | Septiembre 2026 |

## Otros (Planner)

| Estado | Función | Descripción | Disponibilidad general |
|---|---|---|---|
| En desarrollo | Informes de estado generados por IA en Planner Agent | Convierte los datos de un plan en un informe narrativo (estado, progreso, riesgos, próximos pasos), personalizable por audiencia y tono. | Septiembre 2026 |

---

*Generado automáticamente a partir de la API pública del Microsoft 365 Roadmap. Las fechas de disponibilidad general son estimaciones de Microsoft y pueden cambiar.*
