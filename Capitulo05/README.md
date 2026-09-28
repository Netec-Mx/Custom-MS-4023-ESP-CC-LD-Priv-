# Análisis de incidencias operativas y generación de un reporte ejecutivo

Esta práctica utiliza un conjunto ficticio de observaciones operativas para identificar patrones, mejorar una indicación con Prompt Coach, priorizar incidencias, proponer acciones y consolidar un resumen ejecutivo en una Página de Copilot.

## Metadatos

| Campo | Detalle |
|---|---|
| Duración | 22 min |
| Complejidad | Intermedia |
| Nivel de Bloom | Analizar / Evaluar / Crear |
| Tipo de actividad | Análisis de incidencias y síntesis ejecutiva |
| Aplicaciones | Microsoft Copilot Chat (Básico), Prompt Coach, Páginas de Copilot |
| Modalidad | Individual |
| Insumos previos | Entre 20 y 30 observaciones operativas ficticias proporcionadas para la sesión |
| Resultado | Clasificación, priorización, plan de acción, resumen ejecutivo y versión final en una Página de Copilot |

## Distribución de tiempo

| Fase | Actividad | Tiempo |
|---|---|---:|
| 1 | Ejecutar una indicación inicial y revisar limitaciones | 3 min |
| 2 | Mejorar la indicación con Prompt Coach | 4 min |
| 3 | Ejecutar el análisis optimizado y priorizar incidencias | 6 min |
| 4 | Generar plan de acción y resumen ejecutivo | 5 min |
| 5 | Consolidar el resultado en una Página de Copilot | 4 min |
|  | **TOTAL** | **22 min** |

## Descripción general

Analizarás un conjunto de observaciones relacionadas con información incompleta, datos inconsistentes, solicitudes duplicadas, aclaraciones pendientes, errores de captura y otras situaciones recurrentes detectadas durante la operación diaria. Primero usarás una indicación inicial, después Prompt Coach te ayudará a mejorarla y finalmente compararás la calidad del análisis antes de producir un reporte ejecutivo.

## Objetivos de aprendizaje

- Identificar patrones y categorías en observaciones operativas.
- Utilizar Prompt Coach para revisar y mejorar una indicación.
- Diferenciar hallazgos respaldados por el conjunto de datos de interpretaciones que requieren información adicional.
- Priorizar incidencias mediante criterios explícitos.
- Proponer acciones inmediatas, de seguimiento y de investigación adicional.
- Consolidar el resultado en una Página de Copilot.

## Escenario de la práctica

Un responsable operativo de CIBEST CAPITAL ha identificado un incremento de solicitudes que requieren correcciones antes de poder continuar su procesamiento.

### Conjunto de observaciones

El temario define que deben utilizarse **aproximadamente 20 a 30 observaciones ficticias**, pero no proporciona el contenido concreto. El conjunto debe prepararse antes de iniciar el tiempo de práctica y pegarse en el bloque siguiente.

```text
[PEGAR AQUÍ ENTRE 20 Y 30 OBSERVACIONES OPERATIVAS FICTICIAS PROPORCIONADAS PARA LA SESIÓN]
```

El conjunto debe incluir suficiente variedad para que existan:

- categorías recurrentes;
- casos aislados;
- distintos niveles de impacto;
- diferencias de prioridad.

> No inventes observaciones adicionales durante la práctica para completar el volumen. Si el conjunto no fue proporcionado, marca el insumo como pendiente de confirmar y solicita el material antes de iniciar.

## Prerrequisitos

- Acceso a Microsoft Copilot Chat.
- Acceso a Prompt Coach.
- Acceso a Páginas de Copilot y almacenamiento habilitado en el entorno de Microsoft 365.
- Conjunto ficticio de observaciones preparado para la sesión.

## Preparación del entorno

1. Cuenta las observaciones recibidas y confirma que el conjunto contiene entre 20 y 30 elementos.
2. Abre Microsoft Copilot Chat y una conversación nueva.
3. Comprueba que Prompt Coach esté disponible en la sección de agentes.
4. Comprueba que puedes crear o editar una Página de Copilot.
5. No sustituyas las observaciones ficticias por casos reales del cliente.

## Desarrollo de la práctica

### Fase 1 — Ejecutar una indicación inicial y revisar limitaciones

**Tiempo:** 3 min  
**Aplicación:** Microsoft Copilot Chat  
**Objetivo:** Obtener un primer análisis y detectar qué le falta a la indicación.

### Paso 1. Ejecuta el prompt inicial

> **PROMPT 1 — ANÁLISIS INICIAL**

```text
Analiza las siguientes observaciones operativas. Identifica patrones, clasifica los casos en categorías y resume los principales problemas observados.

OBSERVACIONES:
[PEGA AQUÍ EL CONJUNTO DE 20 A 30 OBSERVACIONES]
```

### Paso 2. Revisa la respuesta

Comprueba si Copilot:

- define criterios de clasificación;
- cuenta la frecuencia de cada categoría;
- diferencia datos del conjunto de interpretaciones;
- explica cómo prioriza;
- indica información faltante.

**Criterio de finalización:** puedes identificar al menos dos aspectos que deberían mejorarse en el Prompt 1.

### Fase 2 — Mejorar la indicación con Prompt Coach

**Tiempo:** 4 min  
**Aplicación:** Prompt Coach  
**Objetivo:** Obtener una indicación más precisa y evaluable.

### Paso 1. Abre Prompt Coach

No asumas que el agente conoce la conversación de Copilot Chat.

### Paso 2. Solicita una mejora del prompt

> **PROMPT 2 — REVISIÓN CON PROMPT COACH**

```text
Revisa y mejora esta indicación para analizar un conjunto de observaciones operativas:

"Analiza las siguientes observaciones operativas. Identifica patrones, clasifica los casos en categorías y resume los principales problemas observados."

La versión mejorada debe obligar al análisis a:
- definir criterios de clasificación;
- asignar cada observación a una categoría primaria;
- identificar recurrencias y casos aislados;
- contar la frecuencia por categoría;
- diferenciar hallazgos respaldados por las observaciones de interpretaciones o supuestos;
- priorizar usando frecuencia, impacto potencial, urgencia y posible afectación al proceso;
- indicar información pendiente de validar;
- entregar una tabla estructurada y un resumen breve.

No inventes datos que no estén presentes en las observaciones. Devuelve un prompt final listo para copiar en Copilot Chat.
```

### Paso 3. Revisa el prompt propuesto

Antes de reutilizarlo, confirma que incluya todos los criterios solicitados. Si falta alguno, pídele a Prompt Coach que lo incorpore.

Copia el prompt final mejorado.

**Criterio de finalización:** dispones de un prompt optimizado que especifica criterios, formato y límites de interpretación.

### Fase 3 — Ejecutar el análisis optimizado y priorizar incidencias

**Tiempo:** 6 min  
**Aplicación:** Microsoft Copilot Chat  
**Objetivo:** Comparar el resultado mejorado y crear una priorización trazable.

### Paso 1. Regresa a Copilot Chat

Abre una conversación nueva o continúa en la anterior. Pega primero el prompt final de Prompt Coach y, donde corresponda, añade el conjunto completo de observaciones.

### Paso 2. Comprueba la consistencia de los conteos

Verifica que:

- todas las observaciones estén consideradas;
- la suma de las frecuencias de categorías primarias sea igual al número total de observaciones;
- Copilot no haya creado observaciones nuevas.

### Paso 3. Solicita una priorización explícita

> **PROMPT 3 — PRIORIZACIÓN DE INCIDENCIAS**

```text
A partir exclusivamente del análisis anterior, prioriza las categorías o incidencias utilizando estos criterios:
- frecuencia observada;
- impacto potencial sobre el proceso;
- urgencia de atención;
- posible afectación al avance o procesamiento de la solicitud.

Para cada elemento indica:
1. evidencia disponible en las observaciones;
2. frecuencia;
3. impacto potencial;
4. urgencia;
5. prioridad propuesta: Alta, Media o Baja;
6. justificación de máximo 25 palabras;
7. información adicional que debe validarse.

No conviertas un impacto potencial en un impacto confirmado si el conjunto no lo demuestra. No inventes tiempos, costos, responsables ni causas.
```

**Criterio de finalización:** existe una priorización basada en criterios explícitos y trazable al conjunto de observaciones.

### Fase 4 — Generar plan de acción y resumen ejecutivo

**Tiempo:** 5 min  
**Aplicación:** Microsoft Copilot Chat  
**Objetivo:** Convertir el análisis en un producto útil para revisión operativa.

> **PROMPT 4 — PLAN DE ACCIÓN Y RESUMEN EJECUTIVO**

```text
Usa únicamente la clasificación y priorización validadas anteriormente.

Genera:

A. Plan de acción inicial con tres niveles:
- acciones inmediatas;
- acciones de seguimiento;
- áreas que requieren investigación adicional antes de implementar cambios.

Para cada acción indica el problema que atiende, la evidencia que la justifica y qué debe validarse antes de ejecutarla.

B. Resumen ejecutivo dirigido a un responsable de CIBEST CAPITAL con:
- principales hallazgos;
- prioridades identificadas;
- riesgos observados;
- información pendiente de validar;
- recomendaciones preliminares de atención.

Restricciones:
- no inventes responsables, costos, plazos, causas raíz ni resultados esperados;
- etiqueta como hipótesis cualquier conclusión que dependa de información no incluida en las observaciones;
- máximo 300 palabras para el resumen ejecutivo.
```

Revisa que el plan no convierta una recomendación en una decisión aprobada.

**Criterio de finalización:** existe un plan con tres niveles de atención y un resumen ejecutivo que distingue hallazgos, riesgos y pendientes.

### Fase 5 — Consolidar el resultado en una Página de Copilot

**Tiempo:** 4 min  
**Aplicación:** Páginas de Copilot  
**Objetivo:** Organizar la versión final para una reunión de revisión operativa.

### Paso 1. Crea o abre una Página de Copilot

Desde la respuesta validada, utiliza la opción disponible para crear o agregar el contenido a una Página de Copilot. Si la interfaz permite crear la página directamente desde Copilot Chat, úsala; si no, crea una página y pega manualmente el contenido validado.

### Paso 2. Organiza la página con estas secciones

1. **Resumen ejecutivo**
2. **Clasificación y frecuencia**
3. **Priorización**
4. **Plan de acción**
5. **Información pendiente de validar**

### Paso 3. Valida la página

Comprueba que la página pueda leerse sin abrir la conversación original y que no contenga datos distintos del análisis aprobado.

**Criterio de finalización:** la Página de Copilot contiene las cinco secciones y conserva clasificación, priorización, plan y pendientes.

## Validación y pruebas finales

| # | Criterio | Estado |
|---|---|---|
| 1 | El conjunto contiene entre 20 y 30 observaciones | ☐ |
| 2 | Todas las observaciones fueron consideradas | ☐ |
| 3 | La suma de frecuencias de categorías primarias coincide con el total de observaciones | ☐ |
| 4 | Se comparó el prompt inicial con una versión mejorada por Prompt Coach | ☐ |
| 5 | Hallazgos e interpretaciones están diferenciados | ☐ |
| 6 | La priorización usa frecuencia, impacto potencial, urgencia y afectación al proceso | ☐ |
| 7 | El plan separa acciones inmediatas, seguimiento e investigación adicional | ☐ |
| 8 | El resumen ejecutivo indica información pendiente de validar | ☐ |
| 9 | La Página de Copilot contiene las cinco secciones requeridas | ☐ |

## Solución de problemas

| Situación | Qué hacer |
|---|---|
| El conjunto de observaciones no fue proporcionado | No inventes casos. Solicita el insumo y marca la práctica como pendiente hasta recibirlo. |
| Copilot crea categorías diferentes para casos equivalentes | Pide que normalice los nombres de categorías y recalcule frecuencias sin modificar las observaciones. |
| La suma de frecuencias no coincide con el total | Solicita una tabla con identificador de observación y categoría primaria; corrige la clasificación antes de priorizar. |
| Prompt Coach no está disponible | Verifica la sección de agentes y la cuenta de trabajo. Si no está habilitado, informa al instructor; la práctica no puede cubrir esa parte exactamente como está definida en el temario. |
| No aparece Páginas de Copilot | Comprueba la cuenta y el almacenamiento habilitado en Microsoft 365. Si la función sigue sin estar disponible, conserva el resultado validado en Copilot Chat e informa al instructor. |

## Limpieza y conservación

- Conserva la Página de Copilot final si el instructor solicita evidencia.
- No sustituyas las observaciones ficticias por datos operativos reales.
- Elimina borradores que contengan clasificaciones erróneas para evitar confusión.
- No compartas la página fuera del entorno autorizado para la sesión.

## Resumen de la práctica

Partiste de una indicación simple, utilizaste Prompt Coach para mejorarla, validaste conteos y categorías, priorizaste incidencias, propusiste un plan de acción y generaste un resumen ejecutivo. Finalmente consolidaste la versión validada en una Página de Copilot para una revisión operativa.
