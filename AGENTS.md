# Instrucciones para la IA: conectar ZonaTandas

Estás ayudando a un organizador de ZonaTandas a conectar su cuenta a ti (Claude, ChatGPT, Gemini, Copilot, Cursor u
otra IA compatible con MCP). Él sólo tiene que iniciar sesión; lo demás lo haces tú o se lo das hecho.

El conector es un servidor MCP remoto con OAuth: **`https://panel.zonatandas.es/mcp`** (Streamable HTTP).

## 1. Si puedes escribir ficheros o ejecutar comandos

Añade el servidor a tu propia configuración de MCP, con el fichero de `configs/` que corresponda:

| Cliente | Dónde |
|---|---|
| Claude Code | `claude plugin marketplace add ZonaTandas/zonatandas-mcp` y `claude plugin install zonatandas@zonatandas` (trae también las skills) |
| VS Code / GitHub Copilot | `.vscode/mcp.json` del proyecto o la configuración de usuario, con `configs/vscode-mcp.json` |
| Cursor | `~/.cursor/mcp.json` con `configs/cursor-mcp.json` |
| Gemini CLI | `~/.gemini/settings.json` con `configs/gemini-cli-settings.json` |
| Otro cliente MCP | un servidor HTTP con la URL de arriba |

Al usar la primera herramienta se abrirá el navegador para entrar en ZonaTandas: ahí elige «Lectura y cambios» o «Solo
lectura» y vuelve a entrar con su contraseña o con Google.

## 2. Si no puedes (apps de chat en la web o en el móvil)

No puedes cambiar los ajustes de su cuenta. Dale el único paso, con la URL lista para copiar:

- **Claude** (web, app, escritorio): Personalizar › Conectores › Añadir conector personalizado → la URL → Conectar.
- **ChatGPT** u otra app de chat con conectores MCP: en sus ajustes de conectores, crea uno con la URL y conéctalo.
- Si la app dice que la dirección de vuelta no está permitida, que escriba a ZonaTandas: se añade en un minuto desde
  su panel, sin esperar a ninguna versión.

## 3. Comprueba que funciona

Usa `list_organizations`. Si responde, dile con qué organizaciones estás conectado y ofrece un primer paso: «¿Te
enseño lo pendiente de hoy?».

## Reglas

- Nunca devuelves dinero ni tocas claves, certificados o el contrato: eso se hace en el panel y tú guías.
- Lo delicado (correo a los apuntados, cancelar, confirmar reservas, invitar, publicar, perfil de empresa, textos
  legales) se confirma en el panel con su contraseña. Avísale siempre antes.
- Cada vez que crees o cambies algo, enséñale el enlace de «Dónde verlo».
- Las guías de cada tarea están en `skills/` (formato SKILL.md) y también te llegan desde el conector como prompts.
