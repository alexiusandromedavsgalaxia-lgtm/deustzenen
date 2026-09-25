# Deustzenen™

**eine Sprache, die nicht so spricht, wie sie schreibt.**

Lengua construida/reconstruida en desarrollo activo a partir de un corpus.

## Estado actual

| Capa | Estado |
|---|---|
| Ortografía | parcialmente definida |
| Correspondencias | en expansión |
| Fonología | incompleta |
| Fonotáctica | UNKNOWN |
| Morfología | UNKNOWN / HYPOTHESIS |
| Sintaxis | HYPOTHESIS |
| Semántica | UNKNOWN |
| Léxico | experimental |

## Principio

Deustzenen™ no es «alemán con letras cambiadas».

La cadena de análisis es:

**ORTHOGRAPHY → CORRESPONDENCES → PHONOLOGY → MORPHOLOGY → SYNTAX → SEMANTICS**

El corpus tiene prioridad sobre cualquier teoría.

## Reglas fonológicas CONFIRMED

- `ß → s`
- `ßß → b`

Ejemplo:

`saßßen → seben`

Estas son las únicas reglas generales marcadas como CONFIRMED en este momento.

## Material documentado

Las frases completas y sus salidas se encuentran en `corpus/confirmed.md` y `examples/phrases.md`.

El léxico experimental está en `dictionary/`.

## Convenciones

- **CONFIRMED** — respaldado directamente por datos suficientes.
- **HYPOTHESIS** — análisis provisional que puede cambiar.
- **PENDING** — dato conservado sin análisis definitivo.
- **UNKNOWN** — todavía no determinado.

## Filosofía

No se borra una forma porque resulte rara.
No se arregla una frase para que encaje.
No se asigna un significado porque «parezca» obvio.
No se importa gramática de otra lengua sin evidencia.

Primero: **puten morten**.
Después: análisis.
Luego: reglas.

## Estructura

- `docs/` — especificación y metodología
- `orthography/` — escritura
- `phonology/` — sonido y correspondencias
- `morphology/` / `grammar/` — morfología y gramática
- `syntax/` — sintaxis
- `dictionary/` — léxico
- `corpus/` — corpus
- `examples/` — ejemplos legibles
- `data/` — datos estructurados

## Siguiente fase

1. ampliar el corpus;
2. construir tabla de correspondencias;
3. extraer pares mínimos;
4. proponer IPA;
5. separar morfología de fonología;
6. reconstruir sintaxis;
7. comenzar diccionario semántico;
8. escribir textos originales en Deustzenen cuando el sistema lo permita.

**Deustzenen™ está vivo.**
