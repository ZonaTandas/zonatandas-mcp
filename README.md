# ZonaTandas para Claude

Conecta tu cuenta de organizador de [ZonaTandas](https://zonatandas.es) a Claude y lleva tu panel y tu web hablando:
lo pendiente de hoy, crear y ajustar actividades, el calendario de la temporada, escribir a los apuntados, responder
reseñas, invitar a tu equipo y editar tu web propia.

Claude trabaja con **tus permisos**. Nunca devuelve dinero ni toca cobros, claves o el contrato, y lo delicado te lo
pide confirmar con tu contraseña.

## La forma más rápida

Pega en Claude la dirección de este repositorio y dile «instálalo». Claude sigue
[`INSTALAR-CON-IA.md`](INSTALAR-CON-IA.md); tú sólo inicias sesión.

## A mano

**Claude (app, escritorio o web):** Personalizar › Conectores › Añadir conector personalizado → URL
`https://panel.zonatandas.es/mcp` → Conectar.

**Claude Code:**

```
claude plugin marketplace add ZonaTandas/claude-zonatandas
claude plugin install zonatandas@zonatandas
```

Al conectar eliges **Lectura y cambios** (caduca a las 12 horas sin uso) o **Solo lectura** (a la semana; ideal para un
informe programado). Ves y revocas tus conexiones en el panel: Perfil › Sesiones › Conexiones con IA.

## Qué trae

- `.mcp.json`: el conector.
- `skills/`: guías de trabajo para cada tarea (pendientes, crear y ajustar actividades, plantillas, calendario de
  temporada, apuntados y correo, informe semanal, reseñas, web propia, equipo, cobros y facturas).

---

**English.** Connect your ZonaTandas organizer account to Claude: paste this repository's URL into Claude and say
"install it", or add the custom connector `https://panel.zonatandas.es/mcp`. Claude works with your permissions, never
refunds money or touches payments or keys, and asks you to confirm sensitive actions with your password.

**Português.** Liga a tua conta de organizador da ZonaTandas ao Claude: cola o endereço deste repositório no Claude e
diz «instala», ou adiciona o conector personalizado `https://panel.zonatandas.es/mcp`. O Claude trabalha com as tuas
permissões, nunca devolve dinheiro nem mexe em pagamentos ou chaves, e pede-te confirmação com a palavra-passe para o
que for delicado.
