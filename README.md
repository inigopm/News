# News

Un periodico personal hecho con ayuda de un LLM.

La idea de este repo es reunir resumenes semanales de noticias y lecturas para entender mejor el mundo sin caer en el ciclo de la noticia rapida, el sensacionalismo o el ruido del dia. Cada semana se genera un archivo `.md` con una seleccion equilibrada de piezas para leer en unas 1-2 horas.

## Objetivo

Construir un sistema de informacion semanal que combine:

- mundo y sistemas
- sociedad y politica cercana
- cultura y artes
- una capa local y humana

No se busca cubrir "todo". Se busca una seleccion util, legible y con criterio.

## Principios editoriales

- Priorizar analisis, contexto y piezas con algo de duracion.
- Evitar noticias sensacionalistas o irrelevantes a los pocos dias.
- Mezclar escalas: global, europea, estatal, euskaldun o local.
- Mantener una lectura razonable: el resumen semanal debe poder recorrerse en 1-2 horas.
- El `.md` no tiene que contener todo el desarrollo: puede ser un mapa de lectura con enlaces y una sintesis breve de cada pieza.
- Se pueden incluir imagenes, graficos, portadas o capturas si aportan contexto.

## Capas del resumen semanal

### 1. Mundo y sistemas

Para seguir cambios estructurales en:

- geopolitica
- economia global
- tecnologia
- energia
- demografia

### 2. Sociedad y politica cercana

Para entender el entorno politico, social y cultural mas proximo:

- Euskadi
- Cataluña
- España
- Europa

Bastan 2-3 articulos buenos por semana.

### 3. Cultura y artes

Una capa importante para no reducir la informacion a politica y economia.

Temas:

- cine
- literatura
- cultural
- arte contemporaneo

Este se puede combinar con sociedad y politica cercana.

### 4. Cercano y cotidiano

Incluir una pieza o nota mas proxima y concreta:

- una mejora urbana
- un cambio en el barrio o la ciudad
- una iniciativa cultural local

## Formato del repo

Sugerencia de estructura:

```text
News/
  README.md
  PROMPT_SEMANAL.md
  semanas/
    2026/
      2026-04-05.md
  media/
    2026/
```

Cada archivo semanal puede incluir:

- un resumen inicial de 5-10 lineas
- una seleccion de enlaces por secciones
- una nota breve por articulo explicando por que merece la pena
- una seccion final de ideas o patrones de la semana

## Flujo de trabajo

1. Reunir articulos y piezas de la semana.
2. Generar un archivo semanal en `semanas/YYYY/YYYY-MM-DD.md`.
3. Revisar el tono, quitar ruido y anadir o eliminar enlaces.
4. Opcionalmente, guardar imagenes o graficos relevantes en `media/`.

## Prompt

El prompt base para generar cada edicion esta en `PROMPT_SEMANAL.md`.
