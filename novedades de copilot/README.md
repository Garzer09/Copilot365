# Novedades de Copilot

Esta carpeta es la base de conocimiento de novedades de **Microsoft Copilot** dentro del ecosistema Microsoft 365, construida a partir de la [Microsoft 365 Roadmap](https://www.microsoft.com/es-es/microsoft-365/roadmap).

## Metodología

- **Fuente de datos:** API pública de comunicaciones de lanzamiento de Microsoft 365 (la misma que alimenta la Microsoft 365 Roadmap), filtrada a elementos cuyo título contiene "Copilot".
- **Cadencia:** cada actualización crea o revisa un archivo mensual (`YYYY-MM.md`) con los elementos nuevos o modificados desde la última pasada.
- **Estados que se siguen:** `Launched`, `Rolling out`, `In development` y `Cancelled` (se excluyen ítems retirados sin relevancia).
- **Identificación:** cada elemento conserva su ID de la Roadmap para poder localizarlo de nuevo en el sitio oficial.

## Archivos

| Archivo | Periodo cubierto |
|---|---|
| [`2026-07.md`](./2026-07.md) | Elementos de Copilot modificados entre 2026-06-13 y 2026-07-13 (primera carga del knowledge base) |

## Cómo se usa

Cada archivo mensual agrupa los elementos por **estado** y, dentro de cada estado, por **producto** (Microsoft Copilot (Microsoft 365), Word, Excel, PowerPoint, Outlook, Viva, SharePoint, etc.). Para cada elemento se incluye:

- Título (sin el prefijo de producto, ya agrupado)
- ID de la Roadmap y enlace de búsqueda en el sitio oficial
- Fecha de disponibilidad pública declarada por Microsoft
- Descripción resumida

## Próximas actualizaciones

En cada actualización posterior, comparar el `modified` de los elementos contra la fecha de la última carga registrada en este README y añadir solo lo nuevo o materialmente cambiado en un archivo del mes correspondiente.

**Última actualización:** 2026-07-13
