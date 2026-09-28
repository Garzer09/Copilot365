# Novedades de Microsoft 365 Copilot — Roadmap

Base de conocimiento con las novedades relevantes del [Microsoft 365 Roadmap](https://www.microsoft.com/es-es/microsoft-365/roadmap) relacionadas con Copilot, capacidades de IA e integración en Microsoft 365. Se actualiza periódicamente añadiendo las entradas nuevas o modificadas más recientes en la parte superior de cada sección.

> Última revisión: 2026-09-28

---

## Modelos de IA disponibles en Copilot

| Modelo | Estado | Fecha | Dónde está disponible |
|---|---|---|---|
| Claude Fable 5.1 (Anthropic) | En despliegue (opt-in, admin-controlled) | sept 2026 | Copilot Cowork, Copilot Studio |
| Claude Opus 5 (Anthropic) | Disponible con carácter general | 24-25 jul 2026 | Word, Excel, PowerPoint, Copilot Chat, Copilot Cowork, Copilot Studio |
| GPT-5.6 (OpenAI) | Disponible con carácter general | 9 jul 2026 | Word, Excel, PowerPoint, Chat, Copilot Cowork |
| Claude Sonnet 5 (Anthropic) | Disponible con carácter general | 2 jul 2026 | Copilot Cowork, PowerPoint (optimizado para trabajo multi-paso/agéntico) |
| Claude Opus 4.8 / Sonnet 4.6 | Modelos base de Cowork en su GA | 16 jun 2026 | Copilot Cowork |

Es la primera vez que un modelo que no es de OpenAI (Claude) está disponible como opción estándar en toda la suite de productividad de Microsoft 365, dentro de la licencia Copilot de 30 $/usuario/mes.

En septiembre de 2026, el selector de modelo se integró directamente en el cuadro de prompts de Cowork, dividido en una sección GPT y una sección Claude.

**Claude Fable 5.1** está pensado para tareas complejas y de larga duración. Es un modelo opt-in controlado por el administrador, desactivado por defecto, con requisito de retención de datos: si la organización lo activa, Anthropic no retiene ni prompts ni resultados. Work IQ lo fundamenta en archivos, reuniones y chats del usuario (dentro de sus permisos existentes), de forma que razona sobre el trabajo real y no solo sobre el prompt.

Fuentes: [Microsoft Community Hub — Claude Opus 5](https://techcommunity.microsoft.com/blog/microsoft365copilotblog/available-today-anthropic-claude-opus-5-in-microsoft-365-copilot/4540524), [Microsoft Community Hub — Claude Fable 5](https://techcommunity.microsoft.com/blog/microsoft365copilotblog/available-today-anthropic-claude-fable-5-in-microsoft-365-copilot/4526832), [Redmondmag](https://redmondmag.com/articles/2026/06/16/microsoft-makes-copilot-cowork-generally-available-worldwide.aspx)

---

## Copilot Cowork

- **16 jun 2026** — Disponibilidad general en todo el mundo tras 3 meses en el programa de preview "Frontier". Más de la mitad de las Fortune 500 lo usó durante la preview (Accenture, Avanade, Capital Group, Koch, Ooredoo Qatar, Zurich Insurance, entre otros).
  - Ejecuta tareas largas y multi-herramienta de extremo a extremo ("no solo un borrador o una recomendación, sino un resultado completado").
  - Facturación por Copilot Credits (pay-as-you-go, 0,01 $/crédito), según uso de modelo, recuperación de contexto, llamadas a herramientas y tiempo de ejecución.
- **ago 2026** — Control de **nivel de esfuerzo** (effort level): Light, Medium (por defecto), High, Extra High y Max, para equilibrar calidad, velocidad y consumo de créditos. El selector de modelo y de esfuerzo pasan a integrarse en el propio cuadro de prompts.
- **sept 2026** — Nuevas capacidades:
  - Visibilidad de costes y **skills compartibles** (reusable skills) entre usuarios.
  - Rediseño completo de la interfaz de **Notebooks**.
  - El panel de navegación izquierdo pasa a llamarse "Automations" en lugar de "Scheduled" para los prompts programados.
  - **Slider de esfuerzo de razonamiento**: de una respuesta rápida y económica ("faster") a un análisis más lento y profundo ("smarter") con más contexto.
  - **Capacidades de Planner**: Cowork puede ver y actualizar planes, buckets, objetivos y tareas de Microsoft Planner, y ejecutar el trabajo correspondiente en Microsoft 365 previa aprobación del usuario. Disponibilidad general prevista para septiembre de 2026.
  - Rollout de **Claude Fable 5.1** como opción adicional de modelo (ver sección de modelos).
- **nov 2026** *(previsto)* — **Copilot Cowork para Government Clouds**: extensión de Cowork a entornos GCC y GCC High, con el mismo modelo de delegación de tareas fundamentado en correos, reuniones, mensajes, archivos y datos de la organización.

Fuentes: [Microsoft 365 Blog](https://www.microsoft.com/en-us/microsoft-365/blog/2026/06/16/copilot-cowork-is-now-generally-available/), [IT Pro](https://www.itpro.com/technology/artificial-intelligence/copilot-cowork-is-now-generally-available-everything-you-need-to-know-including-pricing-usage-limits-and-new-features), [Neowin](https://www.neowin.net/news/here-are-all-the-new-features-added-to-microsoft-365-copilot-in-august-2026/), [Microsoft 365 Roadmap — ID 571637](https://www.microsoft.com/en-us/microsoft-365/roadmap?id=571637)

---

## Work IQ APIs

- **Anuncio:** 2 jun 2026 · **GA:** 16 jun 2026.
- Acceso programático a la capa de inteligencia semántica del entorno de trabajo (personas, contenido, actividad, relaciones organizativas) que ya usan Copilot y los agentes internos de Microsoft.
- Permite a desarrolladores construir agentes propios "conscientes del contexto" de la organización, sin tener que reconstruir esa capa de contexto desde cero.
- Facturación pay-as-you-go dentro del ecosistema de Copilot.

Fuentes: [Microsoft 365 Blog](https://www.microsoft.com/en-us/microsoft-365/blog/2026/06/02/announcing-the-new-work-iq-apis/), [Microsoft 365 Developer Blog](https://devblogs.microsoft.com/microsoft365dev/work-iq-production-ready-intelligence-for-every-agent/)

---

## Copilot Chat — Conectores

- **oct 2026** *(previsto)* — Los **conectores federados de Copilot** (Federated Copilot Connectors), hasta ahora de solo lectura, pasan a soportar acciones de **escritura, actualización y borrado** de contenido en servicios de terceros sin salir de Copilot Chat. Cada acción de crear, modificar o eliminar contenido requiere **confirmación explícita del usuario**, y los administradores gestionan los conectores desde el centro de administración de Microsoft 365.

Fuente: [Microsoft 365 Roadmap — ID 570964](https://www.microsoft.com/en-us/microsoft-365/roadmap?id=570964)

---

## Microsoft Copilot Studio

- **sept 2026** — **Visibilidad de costes** en tres puntos del ciclo de vida de un agente:
  - En la pestaña de vista previa (Preview Chat) y en el historial de conversaciones de prueba.
  - En las **evaluaciones de agentes** (Agent Evaluations), con desglose de uso por generación de evaluaciones, ejecuciones de test y "model grading".
  - En la pestaña **Monitor**, con coste por agente y desglose estimado por fase del ciclo de vida (autoría, pruebas, evaluaciones, uso en producción).
- **sept 2026 (preview) / nov 2026 (GA prevista)** — **Maker Guidelines**: los administradores pueden compartir directamente con los creadores de agentes ("makers") indicaciones sobre herramientas, modelos, conectores y canales aprobados por la organización. El mensaje aparece en el panel de revisión (Review pane), junto a los bloqueos y advertencias del agente.

Fuentes: [Microsoft 365 Roadmap — ID 571194](https://www.microsoft.com/en-us/microsoft-365/roadmap?id=571194), [ID 571195](https://www.microsoft.com/en-us/microsoft-365/roadmap?id=571195), [ID 571196](https://www.microsoft.com/en-us/microsoft-365/roadmap?id=571196), [ID 570967](https://www.microsoft.com/en-us/microsoft-365/roadmap?id=570967)

---

## Copilot Notebooks

Ampliación progresiva de los tipos de referencia que se pueden aportar como fuente de conocimiento en un Notebook, para fundamentar mejor (grounding) resúmenes, informes y presentaciones generados por Copilot:

- **Informes de Power BI** como referencia (RM569928).
- **Archivos CSV / TSV** como fuente de datos estructurados.
- **Imágenes (JPG/PNG)** como referencia visual (en despliegue durante los meses siguientes).
- **sept 2026** — Rediseño de la interfaz de Notebooks dentro de Copilot Cowork.

Fuente: [M365 Admin – Power BI en Notebooks](https://m365admin.handsontek.net/microsoft-copilot-microsoft-365-power-bi-reports-references-copilot-notebooks/), [M365 Admin – CSV/TSV en Notebooks](https://m365admin.handsontek.net/microsoft-copilot-microsoft-365-csv-tsv-references-copilot-notebooks/)

---

## Deep Citations (citas profundas)

- Permite saltar directamente al fragmento exacto de un documento de origen (no solo abrir el archivo completo) para verificar de dónde sale una respuesta de Copilot.
- **Alcance inicial:** referencias a Word y PowerPoint. Está prevista la ampliación a reuniones, web y PDF.
- **Calendario:** preview en agosto de 2026, disponibilidad general en septiembre de 2026, para Escritorio, Mac y Web (clientes multi-tenant estándar, Worldwide). Las fechas de roadmap son objetivos y pueden variar.

Fuentes: [Windows Forum](https://windowsforum.com/windows-news.4/microsoft-365-copilot-deep-citations-preview-in-august-2026.436081/)

---

## SharePoint y OneDrive

- **Skills reutilizables** que acompañan al usuario entre SharePoint y OneDrive; Copilot puede medirlas y mejorarlas mediante evaluaciones.
- Nuevas guías para que los agentes de IA construyan experiencias en vivo "SharePoint-safe" (respetando permisos existentes).
- Los administradores de SharePoint pueden configurar una **política de acceso restringido** a un sitio, de forma que su contenido solo sea visible para Copilot para el grupo de usuarios especificado.
- Si un usuario no tiene acceso a un sitio de SharePoint, canal de Teams o buzón, el agente no puede mostrar contenido de esas fuentes ("no new privileges").

---

## Microsoft Teams

- **Resúmenes multilingües** (multilingual recaps): se puede elegir el idioma al que traducir el resumen automático de una reunión.

## Word y Outlook

- Copilot puede **insertar hiperenlaces** directamente en documentos de Word.
- En móvil, se puede describir el correo que se quiere redactar y enviar ese borrador directamente desde el chat de Copilot a Outlook mobile.

## PowerPoint

- **Brand Kit**: disponible con carácter general desde finales de junio de 2026. Permite generar presentaciones con Copilot que parten de las plantillas, activos visuales y directrices de marca aprobadas por la organización, con controles de política para administradores.
- **Skills de Brand Kit** *(novedad)*: los gestores de marca ("Brand Managers") pueden subir skills de presentación personalizadas como archivos Markdown al Brand Kit, para que Copilot en PowerPoint (Desktop) las use como guía de creación consistente y aprobada por la organización. Despliegue iniciado a mediados de septiembre de 2026.
- **oct 2026** *(previsto, Mac)* — **Notificaciones asíncronas de Copilot en PowerPoint**: permite salir de PowerPoint, cambiar de dispositivo, desconectarse o terminar la jornada con la confianza de que Copilot avisará cuando el trabajo esté terminado o requiera atención.

Fuentes: [Microsoft Support — Brand Kit](https://support.microsoft.com/en-us/microsoft-365-copilot/create-and-manage-official-brand-kits-in-the-microsoft-365-copilot-app), [Microsoft 365 Message Center — MC1473166, Brand Skill support en PPT Copilot Desktop](https://mc.merill.net/message/MC1473166), [Microsoft 365 Roadmap — ID 570436](https://www.microsoft.com/en-us/microsoft-365/roadmap?id=570436)

## Excel

- **jun 2026** — Funcionalidades de Copilot orientadas a finanzas: uso de datos financieros de confianza y control total sobre cada cambio, ajustado a los estándares del equipo.
- **"Excel Canvas"**: convierte los datos de un libro en una vista tipo panel/dashboard en vivo con gráficos, métricas e insights generados por Copilot, sincronizados con los datos subyacentes. Disponibilidad general prevista para septiembre de 2026 en Excel para Windows y Excel para la Web *(fecha de roadmap objetivo, puede variar)*.

Fuentes: [Windows Forum — Excel Canvas](https://windowsforum.com/windows-news.4/excel-canvas-what-microsofts-2026-roadmap-promises.443985/)

---

## Gobernanza, seguridad y administración

- **Microsoft Purview**: controles de ciclo de vida "Adaptive Scope" y retención específica para **Copilot Memory**.
- Uso de etiquetas de confidencialidad junto con **DLP de Purview** para impedir que determinados archivos sean utilizados por agentes.
- Los administradores pueden gestionar agentes desde el **centro de administración de Microsoft 365**, con controles de seguridad de datos de IA/agentes en Purview y gestión de coste de agentes.
- Los cambios de instalación de apps y agentes aplicados desde el centro de administración de M365/Teams se aplican de forma consistente en Teams, Outlook y Microsoft 365 Copilot.
- Nuevo ajuste en el centro de administración para controlar el acceso a funciones de **generación de vídeo con IA** en Copilot y apps compatibles.
- **Claude Fable 5.1** requiere activación explícita del administrador (opt-in) y conlleva un requisito de retención de datos que garantiza que Anthropic no retiene prompts ni resultados cuando la organización lo activa.
- **dic 2026** *(previsto)* — **Local inferencing** (procesamiento local/soberano): amplía los controles de soberanía de datos permitiendo que la inferencia de IA de determinadas interacciones de Copilot se ejecute dentro de la geografía local aplicable. Se lanza inicialmente en Australia, India, Emiratos Árabes Unidos, Reino Unido y Estados Unidos, dando a las organizaciones mayor control sobre dónde se procesa la IA para cumplir requisitos de soberanía y regionalidad.

Fuente: [Microsoft 365 Roadmap — ID 571886](https://www.microsoft.com/en-us/microsoft-365/roadmap?id=571886)

---

## Interfaz de usuario

- **ago 2026** — Nueva pantalla de inicio del chat, diseño de respuesta más depurado y panel de navegación rediseñado en la app de Microsoft 365 Copilot (web y escritorio).
- Selección de texto en una respuesta del Chat (frase, párrafo o tabla) para pedir a Copilot que trabaje solo sobre ese fragmento.

---

## Fuentes consultadas

- [Microsoft 365 Roadmap](https://www.microsoft.com/es-es/microsoft-365/roadmap)
- [Microsoft 365 Blog — Work IQ APIs](https://www.microsoft.com/en-us/microsoft-365/blog/2026/06/02/announcing-the-new-work-iq-apis/)
- [Microsoft 365 Blog — Copilot Cowork GA](https://www.microsoft.com/en-us/microsoft-365/blog/2026/06/16/copilot-cowork-is-now-generally-available/)
- [Microsoft Community Hub — Claude Opus 5 en M365 Copilot](https://techcommunity.microsoft.com/blog/microsoft365copilotblog/available-today-anthropic-claude-opus-5-in-microsoft-365-copilot/4540524)
- [Microsoft Community Hub — Claude Fable 5 en M365 Copilot](https://techcommunity.microsoft.com/blog/microsoft365copilotblog/available-today-anthropic-claude-fable-5-in-microsoft-365-copilot/4526832)
- [Microsoft Community Hub — What's new in Copilot (agosto 2026)](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/what%E2%80%99s-new-in-microsoft-copilot--august-2026/4551960)
- [Microsoft Community Hub — What's new in Copilot in SharePoint (septiembre 2026)](https://techcommunity.microsoft.com/blog/spblog/whats-new-in-copilot-in-sharepoint-september-2026/4535422)
- [Neowin — Novedades de agosto 2026](https://www.neowin.net/news/here-are-all-the-new-features-added-to-microsoft-365-copilot-in-august-2026/)
- [M365 Admin — Power BI y CSV/TSV en Copilot Notebooks](https://m365admin.handsontek.net/microsoft-copilot-microsoft-365-power-bi-reports-references-copilot-notebooks/)
- [Windows Forum — Deep Citations](https://windowsforum.com/windows-news.4/microsoft-365-copilot-deep-citations-preview-in-august-2026.436081/)
- [Windows Forum — Excel Canvas](https://windowsforum.com/windows-news.4/excel-canvas-what-microsofts-2026-roadmap-promises.443985/)
- [Microsoft Support — Brand Kit en Copilot](https://support.microsoft.com/en-us/microsoft-365-copilot/create-and-manage-official-brand-kits-in-the-microsoft-365-copilot-app)
- [Microsoft 365 Message Center — MC1473166](https://mc.merill.net/message/MC1473166)
- [Microsoft 365 Roadmap — ID 571886, Local inferencing](https://www.microsoft.com/en-us/microsoft-365/roadmap?id=571886)
- [Microsoft 365 Roadmap — ID 571637, Copilot Cowork para Government Clouds](https://www.microsoft.com/en-us/microsoft-365/roadmap?id=571637)
- [Microsoft 365 Roadmap — ID 570964, Federated Copilot Connectors (escritura/borrado)](https://www.microsoft.com/en-us/microsoft-365/roadmap?id=570964)
- [Microsoft 365 Roadmap — ID 570436, Notificaciones asíncronas de Copilot en PowerPoint](https://www.microsoft.com/en-us/microsoft-365/roadmap?id=570436)
- [Microsoft 365 Roadmap — ID 570967, Maker Guidelines en Copilot Studio](https://www.microsoft.com/en-us/microsoft-365/roadmap?id=570967)
- [Microsoft 365 Roadmap — ID 571194/571195/571196, Visibilidad de costes en Copilot Studio](https://www.microsoft.com/en-us/microsoft-365/roadmap?id=571194)

---

## Historial de actualizaciones de este documento

- **2026-09-28**: Nueva sección "Microsoft Copilot Studio" (visibilidad de costes en Preview Chat/History, Agent Evaluations y Monitor tab; Maker Guidelines para makers). Nueva sección "Copilot Chat — Conectores" (conectores federados con soporte de escritura/actualización/borrado). Añadido **Local inferencing** (procesamiento de IA en la geografía local, previsto dic 2026) a Gobernanza. Añadido **Copilot Cowork para Government Clouds** (GCC/GCC High, previsto nov 2026) a Copilot Cowork. Añadidas **notificaciones asíncronas de Copilot en PowerPoint para Mac** (previsto oct 2026).
- **2026-09-21**: Añadido Claude Fable 5.1 como nuevo modelo en Copilot Cowork/Studio, capacidades de Planner en Copilot Cowork, nueva sección de PowerPoint (Brand Kit y Skills de Brand Kit en Markdown) y actualización de Excel Canvas con calendario de disponibilidad general (septiembre 2026).
- **2026-09-14**: Creación inicial del documento a partir de la revisión del roadmap de Microsoft 365 (novedades de junio a septiembre de 2026: modelos Claude/GPT, Copilot Cowork GA, Work IQ APIs, Copilot Notebooks, Deep Citations, SharePoint/OneDrive, Teams, Word/Outlook, Excel, gobernanza y UI).
