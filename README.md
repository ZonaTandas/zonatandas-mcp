# ZonaTandas para tu IA

Conecta tu cuenta de organizador de [ZonaTandas](https://zonatandas.es) a la IA que uses —Claude, ChatGPT, Gemini,
GitHub Copilot, Cursor u otra compatible con MCP— y lleva tu panel y tu web hablando: lo pendiente de hoy, crear y
ajustar actividades, el calendario de la temporada, escribir a los apuntados, responder reseñas, invitar a tu equipo y
editar tu web propia.

La IA trabaja con **tus permisos** y sólo en tus organizaciones. Nunca devuelve dinero ni toca cobros, claves o el
contrato, y lo delicado te lo pide confirmar con tu contraseña. Cada cambio viene con el enlace para verlo.

## La forma más rápida

Pega en tu IA la dirección de este repositorio y dile «conéctame a ZonaTandas». Sigue [`AGENTS.md`](AGENTS.md); tú sólo
inicias sesión.

## A mano

La dirección del conector es la misma para todas: **`https://panel.zonatandas.es/mcp`**

- **Claude** (web, app, escritorio): Personalizar › Conectores › Añadir conector personalizado → la URL → Conectar.
- **ChatGPT** y otras apps de chat con conectores MCP: crea un conector con la URL en sus ajustes.
- **Claude Code:** `claude plugin marketplace add ZonaTandas/zonatandas-mcp` y `claude plugin install zonatandas@zonatandas`.
- **VS Code / GitHub Copilot:** [`configs/vscode-mcp.json`](configs/vscode-mcp.json) en `.vscode/mcp.json`.
- **Cursor:** [`configs/cursor-mcp.json`](configs/cursor-mcp.json) en `~/.cursor/mcp.json`.
- **Gemini CLI:** [`configs/gemini-cli-settings.json`](configs/gemini-cli-settings.json) en `~/.gemini/settings.json`.

Al conectar eliges **Lectura y cambios** (caduca a las 12 horas sin uso) o **Solo lectura** (a la semana; ideal para un
informe programado). Ves y revocas tus conexiones en el panel: Perfil › Sesiones › Conexiones con IA.

¿Tu IA dice que la dirección de vuelta no está permitida? Escríbenos y la añadimos: no hace falta esperar a una versión
nueva.

## Qué trae

- `AGENTS.md`: las instrucciones para que la IA te conecte sola.
- `configs/`: la configuración lista para cada cliente.
- `skills/`: guías de trabajo por tarea en formato SKILL.md (pendientes, actividades, plantillas, calendario,
  apuntados y correo, informe semanal, reseñas, web propia, equipo, cobros y facturas). Las mismas guías llegan desde
  el conector como prompts, así que no hace falta instalarlas.
- `.claude-plugin/` y `.mcp.json`: el plugin para Claude Code.

Privacidad: https://zonatandas.es/privacy

---

**English.** Connect your ZonaTandas organizer account to any MCP-compatible AI (Claude, ChatGPT, Gemini, Copilot,
Cursor…): paste this repository's URL into your AI and say "connect me to ZonaTandas", or add the remote MCP server
`https://panel.zonatandas.es/mcp`. The AI works with your permissions, never refunds money or touches payments or keys,
and asks you to confirm sensitive actions with your password.

**Português.** Liga a tua conta de organizador da ZonaTandas a qualquer IA compatível com MCP (Claude, ChatGPT, Gemini,
Copilot, Cursor…): cola o endereço deste repositório na tua IA e diz «liga-me à ZonaTandas», ou adiciona o servidor MCP
remoto `https://panel.zonatandas.es/mcp`. A IA trabalha com as tuas permissões, nunca devolve dinheiro nem mexe em
pagamentos ou chaves, e pede-te confirmação com a palavra-passe para o que for delicado.
