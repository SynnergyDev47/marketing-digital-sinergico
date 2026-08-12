---
title: Flujo de creación, revisión y publicación de ebooks
project: marketing-digital-sinergico
version: 2.1
status: canonico-proyecto
updated: 2026-08-12
controlled_by:
  - DECISIONES_EDITORIALES.md
depends_on:
  - SYSTEM_ARCHITECTURE.md
  - CONTENT_SCOPE.md
  - CROSS_REFERENCE_MAP.md
  - BUYER_PERSONA.md
  - VALUE_PROPOSITION_CANVAS.md
  - TONE_MATRIX.md
  - EDITORIAL_RULES.md
  - BELIEF_DISRUPTION_MAP.md
  - AI_USAGE_GUIDE.md
feeds:
  - REVISION_LOG.md
---

# Flujo de creación, revisión y publicación

Este es el punto de entrada para cualquier persona o IA que trabaje en el proyecto. Ningún manuscrito comienza antes de completar las puertas de decisión indicadas.

## Autoridades de trabajo

1. Decisiones aprobadas en [DECISIONES_EDITORIALES.md](DECISIONES_EDITORIALES.md).
2. Rectores del proyecto.
3. Cánones aplicables de Synnergy Lab: Brand Voice y Flujo de Trabajo.
4. Investigación específica y fuentes verificadas.
5. Planes, borradores y salidas generadas.

Una salida de IA, un texto heredado o una fuente aislada no modifica por sí solo una decisión aprobada.

## Fase 0. Selección y estado

1. Identificar el ebook y su `ebook_id`.
2. Confirmar si su alcance está cerrado o provisional en [CONTENT_SCOPE.md](CONTENT_SCOPE.md).
3. Revisar su función conceptual, CTA y relaciones.
4. Comprobar el estado Git antes de escribir y no mezclar cambios ajenos.
5. Registrar fuentes o conversaciones pendientes. La armonización puede continuar, pero no se cierra una afirmación factual sin una referencia recuperable.

## Fase 1. Investigación validada

1. Leer el protocolo y el prompt investigativo correspondientes.
2. Inspeccionar el documento maestro de investigación completo.
3. Construir `MATRIZ_DE_AFIRMACIONES.md` con:
   - afirmación;
   - clase: hecho, dato volátil, inferencia, recomendación, ejemplo o hipótesis;
   - fuente estable;
   - geografía y fecha cuando proceda;
   - fuerza de evidencia;
   - vigencia;
   - uso editorial previsto.
4. Sustituir citas dependientes de conversaciones (`turn...`) por URL, DOI o referencia bibliográfica estable.
5. Marcar como `[FUENTE PENDIENTE]` toda afirmación importante todavía no recuperada. No pasa al texto final.
6. Revisar contradicciones, vacíos, duplicaciones y transferibilidad a Latinoamérica.

### Puerta 1

La investigación se considera utilizable cuando existe suficiente evidencia, se conocen sus límites y las afirmaciones centrales pueden rastrearse.

## Fase 2. Planificación editorial y descubrimiento

1. Crear `SEO_PLAN.md` con intención de búsqueda, alternativas de título, subtítulo, palabras clave y promesa sin exageración.
2. Confirmar el título corto oficial y aprobar el subtítulo.
3. Crear `PLAN_CONTENIDOS.md` con:
   - transformación del lector;
   - creencia maestra y creencias candidatas;
   - capítulos y función de cada uno;
   - evidencia principal;
   - herramientas o ejercicios;
   - relaciones con otros ebooks;
   - riesgos de duplicación;
   - activos preparados para IA.
4. Comprobar que el plan respeta el rango de palabras y el alcance.

### Puerta 2

`SEO_PLAN.md` y `PLAN_CONTENIDOS.md` requieren aprobación antes de redactar.

## Fase 3. Redacción calibrada

1. Redactar primero el capítulo inicial de `Domina el Marketing Digital` como calibración general de voz.
2. Tras su aprobación, trabajar normalmente en bloques de dos o tres capítulos.
3. Aplicar la estructura flexible:

   `tensión → explicación → evidencia → aplicación → decisión`

4. Utilizar el `tú` de forma consistente.
5. Señalar la diferencia entre evidencia, inferencia y recomendación cuando el lector pudiera confundirlas.
6. Añadir durante la redacción solo las llamadas numéricas necesarias; no sobrecitar ni reconstruir las referencias de memoria al final.
7. Cerrar cada capítulo con `Fuentes y notas del capítulo`, enlazando URL o DOI estable y sin parámetros UTM.
8. Mantener encabezados e identificadores estables para la edición de conocimiento.

### Puerta 3

Cada bloque se revisa antes de continuar. Un bloque no aprobado permanece como borrador.

## Fase 4. Control de calidad

Realizar las siguientes revisiones por separado:

### Editorial

- claridad, ritmo, tratamiento y tono;
- ausencia de relleno, hipérbole y repeticiones;
- disrupción respaldada y respetuosa;
- coherencia del argumento y utilidad práctica.

### Factual

- correspondencia entre afirmaciones y fuentes;
- citas recuperables;
- límites y condiciones visibles;
- diferenciación entre dato, interpretación y ejemplo;
- actualidad de plataformas, leyes, pagos, políticas y estadísticas.

### Sistémica

- alcance y no duplicación;
- CTA principal correcto;
- referencias cruzadas pertinentes;
- lenguaje coherente con los otros volúmenes.

### Preparación para IA

- frontmatter e identificadores;
- secciones comprensibles al recuperarse por separado;
- `PAQUETE_DE_CONTEXTO.md` y `GUIA_DE_USO_CON_IA.md`;
- advertencias de vigencia y datos faltantes;
- pruebas de preguntas de comprensión, diagnóstico, decisión y aplicación.

## Fase 5. Actualización factual

- Plataformas, leyes, pagos y políticas: comprobar inmediatamente antes de publicar.
- Estadísticas y tendencias: priorizar fuentes de los últimos 24 meses.
- Principios duraderos: conservar la fuente original y revisar cuando cambie el consenso o el alcance.
- Registrar `evidence_reviewed_at` en los activos preparados para IA.

## Fase 6. Producción y exportación

### Gratuitos

- fuente Markdown aprobada;
- PDF ligero, accesible y legible en móvil;
- paquete de conocimiento para IA.

### Pagados

- fuente Markdown aprobada;
- PDF para Hotmart;
- EPUB validado para Kindle;
- paquete de conocimiento para IA.

Antes de exportar se verifican en vivo las políticas vigentes de las plataformas. No se registran como permanentes reglas comerciales que puedan cambiar.

## Fase 7. Cierre

1. Actualizar [REVISION_LOG.md](REVISION_LOG.md).
2. Verificar enlaces, frontmatter, nombres, estado de fuentes y artefactos.
3. Revisar `git diff` y ejecutar comprobaciones de formato.
4. Crear un commit que indique qué se modificó y con qué objetivo.
5. No publicar, subir ni crear una versión comercial sin autorización específica.
