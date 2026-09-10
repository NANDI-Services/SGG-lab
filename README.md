# SGG-lab

Repo de **ensayo** del auto-update de SGG. **No instalar desde acá.**

Lo alimentan los mismos workflows que publican `NANDI-Services/SGG-releases`,
con el input `releases_repo` apuntando a este repo y versiones del rango
reservado `9.9.x`. Cada release imita la forma del repo real (los mismos
assets y `SHA256SUMS`) para que una VM de laboratorio instale y se actualice
como una instalación de campo, contra versiones deliberadamente rotas.

Detalle: `docs/specs/e2e-autoupdate.md` y `docs/ops/e2e-autoupdate.md` en el
repo privado.
