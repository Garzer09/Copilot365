# Novedades de Copilot — Base de conocimiento del roadmap de Microsoft 365

Esta carpeta recopila, de forma estructurada y consultable, las novedades del [Roadmap público de Microsoft 365](https://www.microsoft.com/es-es/microsoft-365/roadmap) relacionadas con **Microsoft 365 Copilot**, agentes de IA e integraciones de inteligencia artificial en el ecosistema Microsoft 365.

## Contenido

- **`roadmap-microsoft-365-copilot.md`** — Base de conocimiento "viva" con el estado actual de las funcionalidades de Copilot/IA más relevantes, organizadas por área (Copilot Chat, Agentes/Copilot Studio, Office, Teams, SharePoint, Outlook, Edge, Seguridad/Purview, Administración, Viva/Analytics). Se actualiza en cada revisión del roadmap.
- **`actualizaciones/`** — Histórico de cada revisión: una entrada por fecha con lo que cambió desde la revisión anterior (elementos nuevos, cambios de estado, cambios de fecha de disponibilidad).

## Fuente de datos

Los datos se obtienen del feed público de Microsoft:
`https://www.microsoft.com/releasecommunications/api/v1/m365`

Cada elemento del roadmap incluye: título, descripción, estado (*En desarrollo* / *Desplegando* / *Lanzado* / *Cancelado*), fecha estimada de disponibilidad y fecha de última modificación en el roadmap. El identificador numérico (**ID Microsoft**) permite localizar el elemento exacto en el roadmap público.

## Criterio de selección

Se incluyen elementos etiquetados con el producto "Microsoft Copilot (Microsoft 365)" o cuyo título menciona explícitamente "Copilot", cubriendo también integraciones de IA en Word, Excel, PowerPoint, OneNote, Teams, SharePoint, Outlook, Edge, Viva, Purview y el centro de administración de Microsoft 365.

## Mantenimiento

Esta base de conocimiento se actualiza periódicamente (rutina automatizada). Cada actualización:
1. Descarga el estado actual del roadmap de Microsoft 365.
2. Filtra los elementos relevantes para Copilot/IA.
3. Compara con la última revisión registrada en `actualizaciones/`.
4. Actualiza `roadmap-microsoft-365-copilot.md` y añade una nueva entrada en `actualizaciones/` si hay cambios materiales.

Última actualización: **2026-07-20**.
