# opengym-media

Media derivada para los **ejercicios personalizados** de una instancia self-hosted de
[openGym](https://gitlab.com/DuarteSantos8/opengym).

openGym deja sin animación los ejercicios que te creas tú (`Media.jsx`: *"Custom exercises
have no media — the animation stays blank by design"*). En la app de móvil la media se lee
**solo** desde `cdn.jsdelivr.net`, y jsDelivr solo sirve repositorios públicos de GitHub — de
ahí que este repo exista: es el único sitio del que el móvil puede leer un fichero propio.

## Contenido

| Fichero | Qué es | Origen |
|---|---|---|
| `prehab-hombro.gif` / `-6.jpg` | Complejo de prehab de hombro: 6 pasos rotulados, ~2 s cada uno, y los 6 en rejilla. | 3 fotos de dominio público + **3 ilustraciones propias** |
| `cuello-4vias.gif` | Las 4 direcciones del trabajo de cuello: flexión y extensión con disco tumbado, y las dos laterales. | fotos de dominio público |
| `push-press.gif` | Las 3 fases: barra en hombros → dip corto → extensión y bloqueo. | fotos de dominio público (el bloqueo, con otro modelo del mismo estudio) |
| `mele-remo.gif` | Posición de melé y remo a una mano, con el aviso de que el tronco no debe rotar. | fotos de dominio público |
| `hip-thrust-1-pierna.gif` / `.jpg` | Hip thrust a una pierna: abajo y arriba, con la cadera nivelada. | **ilustración propia** |
| `rhie.gif` / `.jpg` | Bloque RHIE: ida y vuelta de 20 m con acciones de contacto, y la estructura de 5 bloques 1:1. | **ilustración propia** |
| `lucha-contacto.gif` / `.jpg` | Lucha de agarre desde rodillas y la estructura 60 s / 60 s. | **ilustración propia** |

## Procedencia y licencia

Las fotos salen de [`erikpr1994/open-exercise-db`](https://github.com/erikpr1994/open-exercise-db),
publicado bajo **Unlicense (dominio público)**. Aquí están recortadas, rotuladas en español y
montadas en secuencia.

Varios movimientos (*pec stretch en foam roller*, *YW con disco*, *plancha lateral con
rotación externa*, *hip thrust a una pierna*, y los dos bloques de acondicionamiento)
**no tienen ninguna foto con licencia libre** — se buscó en open-exercise-db,
free-exercise-db, Everkinetic, Wikimedia Commons y Openverse. Esos tres son **ilustraciones
originales** hechas para este repo (SVG renderizado), y lo dicen en la propia imagen. Así ningún
fotograma enseña algo distinto de lo que pide el ejercicio.

Obra derivada liberada igualmente al **dominio público** (Unlicense), como el original.

No tiene relación con el proyecto openGym ni con sus autores.
