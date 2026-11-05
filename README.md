# deadlock

Mis mods para [Deadlock](https://store.steampowered.com/app/1422450/Deadlock/), hechos por hobby.

Todos son solo visuales o de sonido: no cambian el gameplay.

## Mods

| Mod | Tipo | Qué hace | Descarga |
|---|---|---|---|
| [estushealsound](estushealsound) | Sonido | Cambia el sonido al recoger la curación de la wave | Releases |

## Instalar

**Opción fácil:** [Deadlock Mod Manager](https://deadlockmods.app/).

**Manual:**
1. Descarga el `.vpk` desde [Releases](../../releases).
2. Cópialo a `Deadlock\game\citadel\addons\` (crea la carpeta si no existe) como `pak01_dir.vpk` (o `pak02_dir.vpk`, `pak03_dir.vpk`... si ya tienes otros).
3. Asegúrate de que tu `gameinfo.gi` cargue `citadel/addons`.

## Estructura

```
<mod>/
├── content/    # archivos fuente (misma ruta que en el juego)
└── README.md
```

## Herramientas

- Source 2 Viewer
- CSDK (herramientas de modding de la comunidad)
