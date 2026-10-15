# Diplomado Agéntico · Transformación Digital

Nivelación agéntica del **Diplomado en Transformación Digital** del Instituto Luterano Latinoamericano, impartido por Yæl Méndez (cuenta institucional ÆL). Martes, 7 pm hora Texas. Pensado para el celular.

> 🤳 Cada alumno publica un proyecto útil para su comunidad, construido con ayuda de IA, comprobado y revisado por una persona.

**Ciclo:** el agente propone → el alumno comprueba → el humano decide → la comunidad aprende ♻️

**Regla de ejecución:** Descubrir → preparar → revisión humana → ejecutar → conservar evidencia.

**Principio:** La evidencia no es autoridad: la supervisión informa, el humano decide.

## Ruta

| Módulo | Antes | Ahora | Pieza que deja |
|---|---|---|---|
| [1](modulos/modulo-1.md) | Fundamentos de ChatGPT | De conversar a dirigir agentes | Bitácora de supervisión |
| [2](modulos/modulo-2.md) | Arte del prompting | Contexto e instrucciones | Ficha de contexto (borrador de `AGENTS.md`) |
| [3](modulos/modulo-3.md) | Productividad y creatividad | Agentes con herramientas | Flujo automatizado y revisado |
| [4](modulos/modulo-4.md) | IA para la comunidad | Construir, revisar y enseñar desde el celular | Proyecto publicado en GitHub |

## Dos agentes, una misma lección

| | Hark | Hermes Agent |
|---|---|---|
| Para quién | Alumnos, desde el celular | Docente y alumnos avanzados |
| Dónde vive | App iOS, Android y web | Servidor propio (VPS); app de escritorio |
| Costo | Plan gratuito | Software libre (MIT) + modelo (Nous Portal) |
| Lección | Las piezas de un agente | Soberanía y control |

Ambos comparten las mismas piezas: meta, contexto, memoria, habilidades, herramientas y permiso humano.

## Ayudante de cátedra: æ

`æ` es la instancia de Hermes Agent del docente. Con Composio (MCP) lee Classroom y GitHub, prepara retroalimentación en borrador y espera aprobación. Ver [`AGENTS.md`](AGENTS.md) y [`hermes/`](hermes/).

> La configuración está revisada contra la documentación, pero todavía no se ha probado en la instalación.

## Estructura del repo

Organizado como [Missing Semester](https://github.com/missing-semester/missing-semester): clases, prácticas, recursos e historial.

| Carpeta o archivo | Qué contiene |
|---|---|
| `index.html` | Portal 9:16 para el celular (fuente en `_src/`) |
| `_clases/` | Una página por clase: idea, práctica, biblioteca y entrega |
| `modulos/` | Visión general de cada módulo y rúbricas |
| `clases.md` | Índice de clases |
| `AGENTS.md` | Reglas para el ayudante æ |
| `hermes/` | Configuración de ejemplo Hermes + Composio |
| `CHANGELOG.md` | Historial de mejoras |
| `license.md` | Licencia y atribución |

Plantilla para alumnos: [mi-diplomado](https://github.com/LutheranInstitute/mi-diplomado).

## Atribución y licencia

Adaptado de [*The Missing Semester of Your CS Education* (MIT, 2026)](https://missing.csail.mit.edu/2026/). **Cambios:** traducción al español, enfoque móvil y de baja conectividad, integración con Google Classroom, agentes Hark y Hermes, y proyecto comunitario.

Este material se comparte bajo [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
