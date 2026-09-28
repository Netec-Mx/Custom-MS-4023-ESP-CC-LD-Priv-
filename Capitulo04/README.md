# Gestión de comunicaciones ante una interrupción temporal de un servicio digital

Esta práctica simula una interrupción temporal de una funcionalidad digital utilizada por clientes de CIBEST CAPITAL. El trabajo comienza con un análisis prudente del impacto, continúa con comunicaciones diferenciadas por audiencia y termina con una infografía y un correo para usuarios externos.

## Metadatos

| Campo | Detalle |
|---|---|
| Duración | 23 min |
| Complejidad | Intermedia |
| Nivel de Bloom | Analizar / Crear |
| Tipo de actividad | Análisis de incidente y comunicaciones multiaudiencia |
| Aplicaciones | Microsoft Copilot Chat (Básico), agente basado en Corporate Communications Crafter, Crear en Microsoft Copilot |
| Modalidad | Individual |
| Insumos previos | Ficha ficticia del incidente completada antes de iniciar la práctica |
| Resultado | Análisis preliminar de impacto y urgencia, comunicación para TI, comunicación interna/comercial, infografía para clientes y correo externo |

## Distribución de tiempo

| Fase | Actividad | Tiempo |
|---|---|---:|
| 1 | Analizar datos, cálculos posibles y vacíos de información | 5 min |
| 2 | Definir prioridad temporal y preparar contexto transferible | 3 min |
| 3 | Crear comunicaciones para TI y equipos internos/comerciales | 6 min |
| 4 | Crear y revisar la infografía para clientes | 5 min |
| 5 | Redactar el correo externo y validar el paquete | 4 min |
|  | **TOTAL** | **23 min** |

## Descripción general

Trabajarás con una ficha ficticia de incidente. Copilot deberá diferenciar datos proporcionados, cálculos derivados y supuestos. No deberá inventar una causa técnica. Después transferirás únicamente la información validada a un agente de comunicaciones y a la capacidad **Crear** de Microsoft Copilot.

## Objetivos de aprendizaje

- Analizar el impacto de una interrupción sin convertir supuestos en hechos.
- Identificar información pendiente antes de comunicar una causa o alcance definitivo.
- Adaptar el mensaje a TI/desarrollo, equipos internos/comerciales y usuarios externos.
- Crear una infografía a partir de una descripción textual.
- Mantener continuidad de contexto entre Copilot Chat, el agente de comunicaciones y Crear.

## Escenario de la práctica

Una funcionalidad de la aplicación o sitio web utilizada por clientes presenta una interrupción temporal que afecta determinadas operaciones o consultas. No se utilizarán nombres de plataformas ni información real de CIBEST CAPITAL.

### Ficha ficticia del incidente

El temario no proporciona valores concretos para la ficha. Deben completarse **antes de iniciar el tiempo de práctica** con los datos ficticios definidos para la sesión.

| Campo | Valor para la sesión |
|---|---|
| Momento en que se detectó el incidente | Pendiente de confirmar |
| Funcionalidad afectada | Pendiente de confirmar |
| Número total de usuarios potenciales del servicio | Pendiente de confirmar |
| Periodo observado | Pendiente de confirmar |
| Volumen promedio de operaciones o consultas en el periodo | Pendiente de confirmar |
| Porcentaje o cantidad de operaciones afectadas | Pendiente de confirmar |
| Comportamiento detectado | Pendiente de confirmar |
| Canales alternativos disponibles | Pendiente de confirmar |
| Datos técnicos preliminares autorizados para el ejercicio | Pendiente de confirmar |
| Canal oficial donde se publicarán actualizaciones | Pendiente de confirmar |
| Próximo punto de actualización | Pendiente de confirmar |

> No reemplaces datos pendientes con valores inventados por Copilot. Si un campo necesario sigue pendiente, indícalo como tal en las comunicaciones.

## Prerrequisitos

- Acceso a Microsoft Copilot Chat.
- Acceso a la capacidad **Crear** de Microsoft Copilot y a la opción de infografías.
- Disponibilidad en el entorno de formación de un agente basado en **Corporate Communications Crafter**.
- Ficha del incidente completada con datos ficticios autorizados para la sesión.

## Preparación del entorno

1. Completa o recibe la ficha ficticia del incidente.
2. Abre Microsoft Copilot Chat.
3. Comprueba que el agente de comunicaciones basado en **Corporate Communications Crafter** esté visible y utilizable.
4. Abre **Crear** en Microsoft Copilot y confirma que la opción para diseñar una infografía esté disponible.
5. No uses datos reales de clientes, plataformas o incidentes de CIBEST CAPITAL.

> Corporate Communications Crafter puede estar disponible como agente ya preparado en el entorno de formación o requerir aprovisionamiento previo. No dediques el tiempo de la práctica a construir el agente.

## Desarrollo de la práctica

### Fase 1 — Analizar datos, cálculos posibles y vacíos de información

**Tiempo:** 5 min  
**Aplicación:** Microsoft Copilot Chat  
**Objetivo:** Crear un análisis inicial que separe hechos, cálculos y supuestos.

### Paso 1. Copia la ficha completada

Sustituye el marcador del prompt por la ficha con los valores de la sesión.

> **PROMPT 1 — ANÁLISIS PRELIMINAR DEL INCIDENTE**

```text
Analiza la siguiente ficha ficticia de una interrupción temporal de un servicio digital utilizado por clientes de CIBEST CAPITAL.

FICHA DEL INCIDENTE:
[PEGA AQUÍ LA FICHA COMPLETADA]

Objetivos:
1. separar datos proporcionados, cálculos derivados y supuestos;
2. indicar qué cálculos de impacto pueden realizarse directamente con los datos disponibles;
3. identificar qué información falta para estimar clientes únicos afectados;
4. proponer dos o más supuestos de cálculo que podrían probarse solo si se etiquetan explícitamente como hipótesis;
5. identificar información pendiente de confirmar;
6. proponer una priorización temporal de acciones sin inventar una solución técnica.

Restricciones:
- no determines la causa raíz si no está confirmada en la ficha;
- no conviertas operaciones o consultas en clientes únicos sin un supuesto explícito;
- no inventes tiempos de recuperación, responsables, pérdidas financieras, datos de seguridad ni compromisos;
- conserva cualquier campo no disponible como "Pendiente de confirmar".

Formato:
A. Datos proporcionados.
B. Cálculos que sí pueden realizarse y fórmula utilizada.
C. Supuestos de cálculo posibles, claramente etiquetados.
D. Información pendiente de confirmar.
E. Acciones priorizadas por horizonte: ahora, siguiente actualización y seguimiento.
```

### Paso 2. Revisa los cálculos

Confirma manualmente cualquier operación aritmética básica. Si Copilot estima clientes únicos sin una base suficiente, elimina esa cifra y conserva la limitación.

**Criterio de finalización:** el análisis separa datos, cálculos, supuestos y pendientes, y no afirma una causa técnica no confirmada.

### Fase 2 — Definir prioridad temporal y preparar contexto transferible

**Tiempo:** 3 min  
**Aplicación:** Microsoft Copilot Chat  
**Objetivo:** Crear un bloque breve que pueda transferirse a otras aplicaciones sin depender del historial del chat.

> **PROMPT 2 — RESUMEN TRANSFERIBLE**

```text
Convierte el análisis validado en un bloque de contexto para reutilizar en comunicaciones.

Incluye únicamente:
- qué funcionalidad está afectada;
- momento de detección;
- comportamiento observado;
- impacto que puede afirmarse con los datos disponibles;
- cálculos derivados claramente identificados;
- información pendiente de confirmar;
- canales alternativos disponibles;
- canal de actualizaciones;
- próximo punto de actualización;
- prioridad temporal de las acciones.

No incluyas hipótesis de causa técnica como hechos y no añadas información nueva.
```

Copia este bloque. Lo utilizarás en el agente de comunicaciones y en Crear.

**Criterio de finalización:** existe un resumen que puede entenderse fuera de la conversación original y conserva los límites de certeza.

### Fase 3 — Crear comunicaciones para TI y equipos internos/comerciales

**Tiempo:** 6 min  
**Aplicación:** agente basado en Corporate Communications Crafter  
**Objetivo:** Redactar mensajes distintos para dos audiencias.

### Paso 1. Comunicación para TI/desarrollo

Abre el agente de comunicaciones y pega el resumen validado dentro del prompt.

> **PROMPT 3 — COMUNICACIÓN PARA TI/DESARROLLO**

```text
Redacta una comunicación interna breve para el equipo de TI/desarrollo a partir de este contexto validado:

[PEGA AQUÍ EL RESUMEN TRANSFERIBLE DEL PROMPT 2]

Debe incluir:
- comportamiento detectado;
- impacto observado o estimado, diferenciándolo claramente;
- prioridad de atención;
- información disponible;
- información pendiente de confirmar;
- resultado esperado de la intervención: restablecer o estabilizar la funcionalidad y confirmar el estado mediante validaciones técnicas.

No inventes la causa raíz, la solución técnica, responsables individuales ni un tiempo de recuperación si no fueron proporcionados.

Formato: asunto y mensaje de máximo 180 palabras.
```

### Paso 2. Comunicación interna/comercial

> **PROMPT 4 — COMUNICACIÓN PARA EQUIPOS INTERNOS Y COMERCIALES**

```text
Redacta una comunicación para equipos internos y comerciales usando exclusivamente este contexto validado:

[PEGA AQUÍ EL RESUMEN TRANSFERIBLE DEL PROMPT 2]

Explica:
- qué está ocurriendo;
- qué puede comunicarse a clientes;
- qué información todavía no debe afirmarse;
- qué canales alternativos están disponibles;
- dónde consultar actualizaciones;
- cuál es el próximo punto de actualización, si fue proporcionado.

No atribuyas una causa técnica ni prometas un tiempo de resolución que no esté confirmado.

Formato: asunto y mensaje de máximo 160 palabras, con una sección final "No comunicar como hecho".
```

**Criterio de finalización:** existen dos mensajes diferenciados por audiencia y ninguno introduce una causa o compromiso no proporcionado.

### Fase 4 — Crear y revisar la infografía para clientes

**Tiempo:** 5 min  
**Aplicación:** Crear en Microsoft Copilot  
**Objetivo:** Generar una pieza visual externa basada solo en información validada.

### Paso 1. Abre Crear

En Microsoft Copilot, selecciona **Crear** y la opción equivalente a **Diseñar una infografía**. Los nombres pueden variar según la interfaz.

### Paso 2. Usa la siguiente descripción

> **PROMPT 5 — INFOGRAFÍA PARA CLIENTES**

```text
Crea una infografía informativa para clientes basada únicamente en el siguiente contexto validado:

[PEGA AQUÍ EL RESUMEN TRANSFERIBLE DEL PROMPT 2]

La infografía debe comunicar de forma sencilla:
1. que se está atendiendo una interrupción temporal;
2. qué funcionalidad presenta inconvenientes;
3. qué alternativas pueden utilizarse temporalmente;
4. dónde encontrar actualizaciones;
5. el próximo punto de actualización, si está confirmado.

No incluyas una causa técnica, una fecha u hora de recuperación, una garantía de disponibilidad ni información que siga pendiente de confirmar.

Usa texto breve, legible y neutral. Evita lenguaje alarmista.
```

### Paso 3. Revisa el contenido de la infografía

Comprueba que el texto no haya añadido información no presente en el resumen. Si aparece algún dato nuevo, edítalo o regenera la pieza.

**Criterio de finalización:** existe una infografía que contiene solo información confirmada o claramente marcada y explica alternativas y actualizaciones.

### Fase 5 — Redactar el correo externo y validar el paquete

**Tiempo:** 4 min  
**Aplicación:** Microsoft Copilot Chat  
**Objetivo:** Preparar el mensaje que acompañará la infografía.

### Paso 1. Regresa a Copilot Chat

No asumas que Copilot Chat puede ver automáticamente la infografía. Utiliza el resumen validado y describe únicamente que la pieza visual será adjuntada o insertada.

> **PROMPT 6 — CORREO EXTERNO**

```text
Redacta el correo que acompañará una infografía informativa sobre la interrupción temporal descrita en este contexto validado:

[PEGA AQUÍ EL RESUMEN TRANSFERIBLE DEL PROMPT 2]

El correo debe:
- explicar brevemente la situación sin lenguaje alarmista;
- indicar las alternativas disponibles;
- señalar dónde se publicarán actualizaciones;
- incluir el próximo punto de actualización solo si está confirmado;
- indicar que la infografía adjunta resume la información disponible.

No afirmes una causa técnica, una pérdida de datos, un tiempo de recuperación ni cualquier otro elemento que no esté confirmado.

Formato: asunto y cuerpo de máximo 140 palabras. No envíes el correo; entrégalo solo como borrador.
```

### Paso 2. Valida el paquete completo

Revisa que los cuatro productos de comunicación sean coherentes entre sí y que no aparezcan datos diferentes entre versiones.

**Criterio de finalización:** dispones del análisis preliminar, dos comunicaciones internas, una infografía y un borrador de correo externo consistentes con la misma ficha de incidente.

## Validación y pruebas finales

| # | Criterio | Estado |
|---|---|---|
| 1 | La ficha del incidente estaba completada antes de iniciar | ☐ |
| 2 | Datos, cálculos, supuestos y pendientes están diferenciados | ☐ |
| 3 | No se inventó una causa técnica | ☐ |
| 4 | La comunicación de TI no prescribe una solución técnica no confirmada | ☐ |
| 5 | La comunicación interna/comercial incluye qué puede y qué no puede comunicarse | ☐ |
| 6 | La infografía incluye funcionalidad afectada, alternativas y actualizaciones | ☐ |
| 7 | El correo externo permanece como borrador | ☐ |
| 8 | Ningún producto introduce datos que no estén en la ficha o en cálculos explícitos | ☐ |

## Solución de problemas

| Situación | Qué hacer |
|---|---|
| Quedan campos de la ficha sin completar | Mantén "Pendiente de confirmar" y evita cálculos o promesas que dependan de ese dato. |
| Copilot estima clientes únicos sin base suficiente | Elimina la cifra y conserva solo el cálculo de operaciones/consultas afectadas o exige que el supuesto quede explícito. |
| El agente de comunicaciones no está disponible | Verifica el agente aprovisionado para la formación. Si no está habilitado, informa al instructor. Solo si autoriza una contingencia, ejecuta los Prompts 3 y 4 en Copilot Chat y registra que no se practicó el agente. |
| Crear no muestra la opción de infografía | Verifica la cuenta y la suscripción habilitada para la sesión. No sustituyas la infografía por otro artefacto sin autorización. |
| La infografía inventa un tiempo de resolución | Edita o regenera la pieza indicando que el tiempo de recuperación sigue pendiente de confirmar. |

## Limpieza y conservación

- Conserva la infografía y los borradores solo si el instructor solicita evidencia.
- No envíes el correo ni publiques las comunicaciones.
- No utilices nombres reales de plataformas, clientes o incidentes.
- Elimina borradores duplicados que puedan confundirse con la versión validada.

## Resumen de la práctica

Analizaste un incidente ficticio sin inventar la causa técnica, separaste hechos y supuestos, transferiste el contexto validado entre aplicaciones y creaste comunicaciones para TI, equipos internos/comerciales y usuarios externos. El paquete final conserva el mismo conjunto de datos y deja explícita la información pendiente de confirmar.
