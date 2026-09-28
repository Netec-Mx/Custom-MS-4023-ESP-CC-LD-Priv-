# Diseño y refinamiento de prompts para analizar una situación de negocio

Esta práctica utiliza Microsoft Copilot Chat (Básico) para comparar una indicación inicial con versiones progresivamente más precisas. El objetivo es observar cómo el contexto, las fuentes, la audiencia, la extensión y el formato modifican la utilidad del resultado.

## Metadatos

| Campo | Detalle |
|---|---|
| Duración | 12 min |
| Complejidad | Básica |
| Nivel de Bloom | Aplicar / Analizar |
| Tipo de actividad | Práctica guiada individual |
| Aplicaciones | Microsoft Copilot Chat (Básico) |
| Modalidad | Individual |
| Insumos previos | No requiere archivos ni información interna |
| Resultado | Comparación entre un prompt inicial y uno refinado, con identificación de los elementos que mejoran precisión, contexto y utilidad |

## Distribución de tiempo

| Fase | Actividad | Tiempo |
|---|---|---:|
| 1 | Ejecutar y revisar un prompt inicial | 2 min |
| 2 | Construir y ejecutar un prompt refinado | 4 min |
| 3 | Modificar audiencia, extensión y formato | 3 min |
| 4 | Comparar resultados y cerrar la práctica | 3 min |
|  | **TOTAL** | **12 min** |

## Descripción general

Trabajarás sobre una necesidad del equipo comercial de CIBEST CAPITAL: comprender qué factores están influyendo actualmente en las decisiones de inversionistas latinoamericanos que buscan diversificar internacionalmente su patrimonio. No utilizarás archivos ni datos internos. La actividad se concentra en diseñar y refinar prompts, no en realizar una investigación exhaustiva.

## Objetivos de aprendizaje

- Comparar la respuesta obtenida con una indicación simple frente a una indicación estructurada.
- Incorporar contexto, objetivo, fuentes, audiencia y formato esperado en un prompt.
- Revisar si la respuesta diferencia información respaldada de inferencias o generalizaciones.
- Observar cómo cambios pequeños en audiencia, extensión y formato alteran la salida.

## Escenario de la práctica

El equipo comercial de CIBEST CAPITAL desea comprender qué factores están influyendo actualmente en las decisiones de inversionistas latinoamericanos que buscan diversificar internacionalmente su patrimonio, con el propósito de identificar temas que podrían resultar relevantes en futuras conversaciones comerciales.

No se utilizará información interna de CIBEST CAPITAL. Toda consulta deberá apoyarse en información pública.

## Prerrequisitos

- Acceso a Microsoft Copilot Chat con una cuenta de trabajo o educativa autorizada.
- Conexión a Internet.
- Conocimientos básicos para iniciar una conversación y enviar prompts.

## Preparación del entorno

1. Inicia sesión en Microsoft Copilot Chat con la cuenta asignada para la capacitación.
2. Abre una conversación nueva.
3. Si la interfaz muestra opciones de búsqueda o conexión a la web, utiliza la opción que permita consultar información pública.
4. No cargues archivos ni pegues información interna de CIBEST CAPITAL.

## Desarrollo de la práctica

### Fase 1 — Ejecutar y revisar un prompt inicial

**Tiempo:** 2 min  
**Aplicación:** Microsoft Copilot Chat  
**Objetivo:** Identificar las limitaciones de una petición poco específica.

### Paso 1. Envía una indicación simple

> **PROMPT 1 — CONSULTA INICIAL**

```text
¿Qué factores están influyendo actualmente en las decisiones de inversionistas latinoamericanos que buscan diversificar internacionalmente su patrimonio?
```

### Paso 2. Revisa la respuesta

Sin intentar corregirla todavía, comprueba si la respuesta:

- indica de dónde proviene la información;
- diferencia hechos de interpretaciones;
- define un periodo de análisis;
- está adaptada a una audiencia comercial;
- presenta un formato que permita comparar factores.

**Criterio de finalización:** puedes identificar al menos dos limitaciones concretas del Prompt 1.

### Fase 2 — Construir y ejecutar un prompt refinado

**Tiempo:** 4 min  
**Aplicación:** Microsoft Copilot Chat  
**Objetivo:** Incorporar contexto, fuentes y características verificables del resultado.

### Paso 1. Ejecuta el prompt refinado

> **PROMPT 2 — ANÁLISIS REFINADO**

```text
Analiza qué factores económicos y de mercado están influyendo actualmente en las decisiones de inversionistas latinoamericanos que buscan diversificar internacionalmente su patrimonio.

Contexto: el resultado será revisado por un ejecutivo comercial de CIBEST CAPITAL para identificar temas que podrían resultar relevantes en futuras conversaciones comerciales. No utilices ni infieras información interna de CIBEST CAPITAL.

Usa información pública reciente y prioriza fuentes originales u organizaciones reconocidas. Para cada factor, indica:
1. factor identificado;
2. evidencia o dato público que lo respalda;
3. por qué podría ser relevante para una conversación comercial;
4. fuente u organización;
5. fecha o periodo de la información;
6. enlace cuando esté disponible.

Distingue hechos respaldados por fuentes de interpretaciones. Si una afirmación no puede verificarse con la información disponible, indícalo como "Pendiente de confirmar".

Entrega una tabla breve con un máximo de seis factores y termina con tres preguntas que un ejecutivo comercial debería validar antes de utilizar los hallazgos con un cliente.
```

### Paso 2. Revisa la salida

Comprueba que Copilot haya:

- incluido fuentes o enlaces cuando estén disponibles;
- separado evidencia de interpretación;
- evitado atribuir necesidades o preferencias a CIBEST CAPITAL;
- mantenido el análisis en un nivel exploratorio.

**Criterio de finalización:** existe una salida estructurada que permite rastrear cada factor hasta una fuente o marcarlo como pendiente de confirmar.

### Fase 3 — Modificar audiencia, extensión y formato

**Tiempo:** 3 min  
**Aplicación:** Microsoft Copilot Chat  
**Objetivo:** Observar el efecto de pequeños cambios en las instrucciones.

### Paso 1. Reutiliza el mismo análisis con nuevas restricciones

> **PROMPT 3 — CAMBIO DE AUDIENCIA Y FORMATO**

```text
Reformula el análisis anterior para una audiencia comercial no técnica.

Mantén únicamente los cinco factores mejor respaldados por fuentes. Para cada uno usa una frase de máximo 25 palabras y conserva la fuente y la fecha o periodo. Después agrega una sección titulada "Qué no podemos concluir" con tres límites del análisis.

No añadas nuevos datos ni nuevas conclusiones.
```

### Paso 2. Observa los cambios

Compara con la respuesta del Prompt 2 y señala mentalmente o en una nota breve qué cambió en:

- audiencia;
- longitud;
- estructura;
- nivel de detalle.

**Criterio de finalización:** puedes explicar cómo al menos dos cambios del Prompt 3 modificaron la respuesta sin cambiar el objetivo del análisis.

### Fase 4 — Comparar resultados y cerrar la práctica

**Tiempo:** 3 min  
**Aplicación:** Microsoft Copilot Chat  
**Objetivo:** Identificar qué elementos del refinamiento aportaron valor.

### Paso 1. Completa esta comparación

| Criterio | Prompt 1 | Prompt 2 | Prompt 3 |
|---|---|---|---|
| Contexto explícito | ☐ | ☐ | ☐ |
| Fuentes solicitadas | ☐ | ☐ | ☐ |
| Audiencia definida | ☐ | ☐ | ☐ |
| Formato definido | ☐ | ☐ | ☐ |
| Límites o incertidumbre | ☐ | ☐ | ☐ |

### Paso 2. Registra la conclusión

Identifica los **tres elementos** que más mejoraron la precisión, el contexto o la utilidad del resultado.

**Criterio de finalización:** la comparación permite distinguir claramente el prompt inicial del refinado y justificar qué cambios aportaron valor.

## Validación y pruebas finales

| # | Criterio | Estado |
|---|---|---|
| 1 | Se ejecutaron los tres prompts | ☐ |
| 2 | El Prompt 2 solicita información pública reciente y fuentes | ☐ |
| 3 | El resultado diferencia evidencia de interpretación o marca incertidumbre | ☐ |
| 4 | No se utilizó información interna de CIBEST CAPITAL | ☐ |
| 5 | Se identificaron tres elementos que mejoraron el prompt | ☐ |
| 6 | La comparación evidencia cambios de audiencia, extensión o formato | ☐ |

## Solución de problemas

| Situación | Qué hacer |
|---|---|
| Copilot no muestra fuentes | Pide que indique organización, fecha o periodo y enlace para cada afirmación verificable. Si no puede respaldarla, márcala como pendiente de confirmar. |
| La respuesta inventa información sobre CIBEST CAPITAL | Descarta esas afirmaciones y repite la instrucción indicando que no debe utilizar ni inferir información interna de la organización. |
| El resultado es demasiado extenso | Repite el Prompt 3 y conserva el límite de cinco factores y 25 palabras por factor. |
| La búsqueda web no está disponible | Realiza únicamente el ejercicio de estructura de prompts y marca la verificación de fuentes como pendiente. |

## Limpieza y conservación

- No es necesario conservar archivos.
- Puedes conservar la conversación para comparar las tres versiones del prompt durante la sesión.
- No copies información confidencial, personal o interna en la conversación.

## Resumen de la práctica

Partiste de una consulta general, añadiste contexto, fuentes, audiencia, formato y criterios de verificación, y después modificaste la salida para una audiencia comercial. El producto final es la comparación entre las tres indicaciones y la identificación de los elementos que hicieron la respuesta más precisa y útil.
