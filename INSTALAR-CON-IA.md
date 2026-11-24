# Instrucciones para la IA: conectar ZonaTandas

Estás ayudando a un organizador de ZonaTandas a conectar su cuenta. Él sólo tiene que iniciar sesión; lo demás lo haces tú.

## 1. Si puedes ejecutar comandos (Claude Code)

```
claude plugin marketplace add ZonaTandas/claude-zonatandas
claude plugin install zonatandas@zonatandas
```

Eso trae el conector y las skills. Dile que reinicie Claude Code si hace falta y que, al usar la primera herramienta,
se abrirá el navegador para entrar en ZonaTandas. Ahí elige «Lectura y cambios» o «Solo lectura» y vuelve a entrar con
su contraseña o con Google.

## 2. Si no puedes (app de Claude, escritorio o web)

No puedes cambiar los ajustes de su cuenta. Dale este único paso, con la dirección lista para copiar:

1. Abre **Personalizar › Conectores › Añadir conector personalizado**.
2. Nombre: `ZonaTandas`. URL: `https://panel.zonatandas.es/mcp`
3. Pulsa **Conectar**, entra en ZonaTandas y elige el tipo de conexión.

En el plan gratuito de Claude sólo cabe un conector personalizado. En Team y Enterprise lo añade una vez el propietario
de la cuenta y cada persona pulsa «Conectar». En la app no hace falta instalar las skills: lo necesario llega desde el
propio conector.

## 3. Comprueba que funciona

Usa `list_organizations`. Si responde, dile con qué organizaciones estás conectado y ofrece un primer paso:
«¿Te enseño lo pendiente de hoy?».

## Reglas

- Nunca devuelves dinero ni tocas claves, certificados o el contrato: eso se hace en el panel y tú guías.
- Lo delicado (correo a los apuntados, cancelar, confirmar reservas, invitar, publicar, perfil de empresa, textos legales)
  se confirma en el panel con su contraseña. Avísale siempre antes.
- Cada vez que crees o cambies algo, enséñale el enlace de «Dónde verlo».
- Sirve igual para otras IA compatibles con MCP: la dirección es la misma.
