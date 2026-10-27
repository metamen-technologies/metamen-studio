# MetaMen Studio

Sistema de generación documental y editorial de MetaMen Technologies.

Estado: planificación.

## Estructura

| Ruta | Contenido |
|---|---|
| `metamen-studio_blueprint-template.md` | Blueprint Enterprise: índice de las 19 secciones del sistema |
| `mstudio.pipeline.md` | Pipeline de ejecución (`/init-mstudio`) — pendiente |
| `rules-template.md` | Reglas operativas del sistema — pendiente |
| `AGENTS-template.md` | Instrucciones para agentes |
| `document_manifest-template.md` | Manifiesto y gobierno documental |
| `docs/architecture/` | Diagramas de flujos y ciclo de vida (fuente JSON + HTML) |
| `scripts/` | Automatización |

## Diagramas

Los flujos se proyectan con [Archify](https://github.com/tt-a1i/archify). Cada diagrama vive en
`docs/architecture/<flujo>/` con su `candidate.json` (fuente editable y diffeable) y su `.html`
autocontenido para presentar.

Obsidian es la fuente de conocimiento del sistema. Los diagramas son una vista de presentación,
no un artefacto que se mantiene a mano.
