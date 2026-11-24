---
name: web-propia
description: Editar y publicar la web propia de un organizador de ZonaTandas: portada, marca, menú, SEO, flota, preguntas frecuentes, guías y textos legales.
---

# Tu web propia

1. `get_site` para ver el dominio y el borrador.
2. Cambia el borrador con `update_site_draft` (portada, flota, FAQ o guías). No se publica.
3. Enseña la vista previa (`get_site_preview_link`) en la página que se ha tocado.
4. Antes de publicar: avisa de que guardarás una copia de la web actual y pregunta cómo llamarla. `export_site` y guárdala en su equipo con ese nombre.
5. `publish_site` (delicada). Da los enlaces de cada página publicada.
6. Textos legales: `get_legal_text` y `update_legal_text` (se publica al confirmar).
