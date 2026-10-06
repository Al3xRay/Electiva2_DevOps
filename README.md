# Electiva2 DevOps - Hola Mundo

Este repositorio publica una página estática de **Hola Mundo** en GitHub Pages con despliegue automático desde GitHub Actions.

## URLs

- Repositorio: https://github.com/Al3xRay/Electiva2_DevOps
- Sitio GitHub Pages: https://al3xray.github.io/Electiva2_DevOps/

## Despliegue automático

El workflow se encuentra en `.github/workflows/deploy-pages.yml` y se ejecuta:

- Automáticamente en cada `push` a la rama `main`
- Manualmente desde la pestaña **Actions** (`workflow_dispatch`)

El flujo usa las acciones recomendadas para GitHub Pages:

- `actions/configure-pages`
- `actions/upload-pages-artifact`
- `actions/deploy-pages`

> Importante: GitHub Pages debe estar habilitado en el repositorio para usar **GitHub Actions** como origen de despliegue (según la configuración permitida por tu cuenta u organización).
