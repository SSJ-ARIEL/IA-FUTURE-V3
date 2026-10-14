# Versión anterior de IA FUTURE

El sitio editorial se mantiene en https://ssj-ariel.github.io/ y en SSJ-ARIEL/SSJ-ARIEL.github.io.

Estas rutas conservan avisos de traslado, canonical al destino y noindex. No cargan anuncios ni analítica. No solicites monetización de esta copia ni regeneres el sitio con las herramientas históricas de tools: reconstruirían páginas duplicadas.

Las páginas equivalentes enlazan al contenido principal; las fichas incompletas se trasladan al catálogo. El enlace de traslado funciona sin JavaScript y el aviso permanece legible mientras se abre el destino.

La consolidación reduce duplicación; no implica que Google haya aprobado el sitio principal. Sus guías y herramientas deben mantenerse en el repositorio principal.

## Publicación

El workflow `.github/workflows/pages.yml` publica la raíz estática y comprueba los 45 avisos, sus destinos y la ausencia de publicidad y analítica. El trabajo usa los permisos mínimos de lectura del repositorio, publicación de Pages e identidad de Actions, y serializa las publicaciones.

El primer despliegue migra Pages desde la publicación heredada por rama a GitHub Actions. Para la reparación identificada en el run `38596638385`, la opción `repair_stalled_deployment` solicita cancelar únicamente `1e146a815c00654d9f12904dc5183ae9bf81c9b5`; no acepta otros IDs ni cancela despliegues nuevos. Utiliza esa opción solo para dicho bloqueo.

Después de publicar, comprueba que `https://ssj-ariel.github.io/IA-FUTURE-V3/` muestra el aviso de traslado y coincide con `index.html`, y abre varias rutas anteriores. No regeneres los avisos con los antiguos scripts editoriales.
