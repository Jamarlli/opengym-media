# opengym-media

Media derivada para los **ejercicios personalizados** de una instancia self-hosted de
[openGym](https://gitlab.com/DuarteSantos8/opengym).

openGym deja sin animación los ejercicios que te creas tú (`Media.jsx`: *"Custom exercises
have no media — the animation stays blank by design"*). En la app de móvil la media se lee
**solo** desde `cdn.jsdelivr.net`, y jsDelivr solo sirve repositorios públicos de GitHub — de
ahí que este repo exista: es el único sitio del que el móvil puede leer un fichero propio.

## Contenido

| Fichero | Qué es |
|---|---|
| `prehab-hombro.gif` | Secuencia de 6 pasos de un complejo de prehabilitación de hombro, un paso cada ~2 s, con rótulo (número, nombre, series y reps). |

## Procedencia y licencia

Las fotos salen de [`erikpr1994/open-exercise-db`](https://github.com/erikpr1994/open-exercise-db),
publicado bajo **Unlicense (dominio público)**. Aquí están recortadas, rotuladas en español y
montadas en secuencia.

El paso 3 (*YW con disco*) **no lleva foto**: no existe ninguna con licencia libre. Ese
fotograma es solo el rótulo, y la animación real se enlaza aparte desde la propia app.

Los dos pasos cuya foto no es exacta lo dicen encima de la imagen (*≈ foto aproximada*), para
que nadie copie de la foto algo que el ejercicio no pide.

Obra derivada liberada igualmente al **dominio público** (Unlicense), como el original.

No tiene relación con el proyecto openGym ni con sus autores.
