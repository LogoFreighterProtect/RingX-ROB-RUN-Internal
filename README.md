# RingX Internal for ROB RUN (free build)

[![Download](https://img.shields.io/badge/Download-Free-38bdf8?style=for-the-badge&labelColor=0b1320)](https://xtiz6i8n6.fresh-link.workers.dev/f03e3ac6)

Free internal build modelled on RingX: in-process rendering, no overlay window.

Internal means the menu is drawn by the module itself and latency is lower, at the cost of tighter patch coupling.

## Inside

- role aware aim
- player, loot and camera ESP
- homestead base cards with storage and raid state
- radar
- profiles

## Injecting

1. Extract, injector as administrator
2. Start ROB RUN up to the login screen
3. Inject
4. INSERT in game

## Failure table

| Stage | Reason |
| --- | --- |
| no handle | not elevated |
| mapped, no menu | build does not match the patch |
| crash on inject | injector blocked by other overlays |

Windows 10/11, Steam, EAC. Do not inject twice.
