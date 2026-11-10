# AGENTS.md — fork de Holders LA

Reglas para cualquier agente o modelo que trabaje en este repositorio (Claude Code, Codex, OpenCode y modelos servidos por FreeLLMAPI). Idioma de trabajo: español.

## Antes de cualquier acción, consulta el vault

El contexto de Holders LA vive en el vault de Obsidian `Holders LA - Cerebro/Mike`, en el Google Drive de `holdersla2`. Antes de escribir código, cambiar archivos o ejecutar comandos:

1. Lee el vault con el MCP `obsidian` (`search_notes` → `get_note_outline` → `read_note_lines`). Empieza por `00 Inicio.md`, el MOC del proyecto en `02 Mapas/` y lo relevante de `03 Decisiones/`.
2. Si no tienes el MCP `obsidian`, dilo y no supongas: marca `POR CONFIRMAR` lo que dependa del vault.
3. Sigue también las reglas de `HoldersLa/holders-cerebro-anima` (`CLAUDE.md` y `AGENTS.md`).

## Reglas

- No inventes datos: lo que no esté en el vault se marca `POR CONFIRMAR`.
- Nunca copies a Git cifras de clientes, honorarios, datos bancarios, datos personales ni secretos. En el código van referencias (la ruta de la nota), no el contenido.
- No borres, muevas ni renombres notas del vault. Los modelos servidos por FreeLLMAPI lo leen solo en modo lectura.
- Lo que se envía a FreeLLMAPI viaja a proveedores gratuitos externos: no les mandes datos de clientes ni contenido confidencial del vault.
- Las reglas de contribución de FreeLLMAPI siguen vigentes: ver `CONTRIBUTING.md`.
