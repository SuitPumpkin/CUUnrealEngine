# CUUnrealEngine

Proyecto de clase de programacion de videojuegos con **Unreal Engine 5** y materiales **PBR**.

> ⚠️ **El proyecto esta incompleto y puede no recibir actualizaciones.** Esta publicado como
> evidencia de trabajo, no como producto terminado.

## Qué incluye

- Proyecto de Unreal Engine 5 con materiales PBR.
- Scripts y assets del coursework de programacion de videojuegos.

## Stack

- **Motor:** Unreal Engine 5
- **Materiales:** PBR
- **Lenguaje:** C++ y Blueprints

## ⚠️ Sobre el tamaño del repositorio

Este repositorio pesa alrededor de **580 MB**, casi todo en archivos binarios de Unreal Engine
(texturas, mallas y assets compilados). **La decision de no usar Git LFS es intencional**: el
proyecto se publico sin depender de un servidor externo.

Consecuencias practicas:

- `git clone` descarga varios cientos de megabytes y puede tardar en Windows por el antivirus.
- Si alguna vez hace falta aligerarlo, el camino es `git filter-repo` para purgar caches y assets
  regenerables. **No lo hagas sin motivo.**

## Licencia

MIT. Ver [LICENSE](LICENSE).