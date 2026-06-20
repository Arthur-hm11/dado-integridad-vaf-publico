# Dado de la Integridad

Este repositorio es una copia separada del proyecto, preparada para publicarse sin tocar el sistema original de SABG.

## Publicar en GitHub Pages

1. Reautenticar GitHub CLI:
   `gh auth login -h github.com`

2. Entrar a esta carpeta:
   `cd /Users/arturohernandezmanzanarez/Documents/Codex/2026-06-19/tengo-este-proyecto-crees-que-me-2/outputs/dado-integridad-publico`

3. Crear el repositorio remoto:
   `gh repo create dado-integridad-publico --public --source=. --remote=origin --push`

4. Activar GitHub Pages desde la rama `main` y carpeta raíz:
   `gh api -X POST repos/USER/dado-integridad-publico/pages -f source[branch]=main -f source[path]=/`

5. El enlace público quedará así:
   `https://USER.github.io/dado-integridad-publico/`

Sustituye `USER` por tu usuario de GitHub.
