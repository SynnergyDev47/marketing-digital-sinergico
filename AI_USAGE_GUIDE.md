---
title: Guía de preparación y uso del ecosistema con inteligencia artificial
project: marketing-digital-sinergico
version: 1.0
status: canonico-proyecto
updated: 2026-08-11
controlled_by:
  - DECISIONES_EDITORIALES.md
depends_on:
  - SYSTEM_ARCHITECTURE.md
  - CONTENT_SCOPE.md
  - EDITORIAL_RULES.md
feeds:
  - WORKFLOW.md
  - VALUE_PROPOSITION_CANVAS.md
  - CROSS_REFERENCE_MAP.md
---

# Guía de preparación y uso con IA

## Propósito

Definir cómo convertir los siete ebooks en una base de conocimiento editorial que sirva tanto para lectura humana como para análisis, planificación y aplicación asistidos por IA.

Un ebook preparado para IA no es un archivo al que se le añadió una lista de prompts. Es conocimiento con estructura estable, fuentes rastreables, límites explícitos, relaciones comprensibles y suficiente contexto para que un modelo pueda utilizarlo sin confundir evidencia, interpretación y recomendación.

## Valor diferencial frente a una investigación improvisada con IA

Una consulta aislada a una IA puede producir una respuesta rápida, pero no garantiza:

- una pregunta de investigación bien delimitada;
- selección crítica de fuentes;
- separación entre principios duraderos y datos volátiles;
- adaptación a una pyme latinoamericana;
- tratamiento específico del contexto cubano;
- coherencia entre marketing, ventas, operaciones y experiencia;
- continuidad entre sesiones o herramientas;
- control editorial de contradicciones, duplicaciones y vacíos;
- ejercicios y decisiones alineados con un recorrido pedagógico.

El ecosistema aporta una **capa de criterio**: la investigación ya fue filtrada, contrastada, organizada y transformada en un sistema de aprendizaje. La IA funciona sobre esa base; no la sustituye.

## Dos ediciones de una misma fuente

Cada ebook se mantiene desde una fuente maestra en Markdown y genera:

1. **Edición humana**: PDF ligero para los gratuitos; PDF para Hotmart y EPUB para Kindle en los pagados.
2. **Edición de conocimiento**: capítulos Markdown con encabezados estables, metadatos, referencias y activos auxiliares para cargarlos en una herramienta de IA autorizada.

No se mantienen dos manuscritos divergentes. Ambas ediciones proceden de la misma fuente editorial aprobada.

## Paquete mínimo por ebook

Además del manuscrito, cada carpeta deberá terminar con:

- `README.md`: propósito, versión, alcance y orden recomendado de lectura.
- `SEO_PLAN.md`: posicionamiento, título y subtítulo validados.
- `PLAN_CONTENIDOS.md`: arquitectura aprobada.
- `MATRIZ_DE_AFIRMACIONES.md`: afirmaciones importantes, clase, fuente, vigencia y estado.
- `FUENTES.md`: bibliografía con enlaces estables.
- `GUIA_DE_USO_CON_IA.md`: casos de uso, instrucciones y límites específicos del volumen.
- `PAQUETE_DE_CONTEXTO.md`: resumen autocontenido del libro, conceptos, relaciones, advertencias y preguntas que puede responder.
- capítulos o bloques Markdown de la fuente maestra.

Un glosario se crea solo cuando el volumen introduzca términos que realmente necesiten normalización.

## Metadatos de los archivos de conocimiento

Cada capítulo o recurso destinado a IA incluirá frontmatter con, como mínimo:

```yaml
ebook_id: E01
ebook: Domina el Marketing Digital
chapter_id: E01-C01
version: 1.0
updated: YYYY-MM-DD
status: borrador|revisado|aprobado
audience: pyme-latam
topics: []
depends_on: []
related_to: []
evidence_reviewed_at: YYYY-MM-DD
```

Los identificadores permanecen estables aunque cambie el título visible de un capítulo.

## Reglas de estructura para recuperación

- Un encabezado debe describir una idea reconocible fuera de su capítulo.
- Cada sección debe conservar el contexto suficiente para entenderse al ser recuperada por separado.
- No se divide una definición, una condición o una advertencia entre fragmentos inconexos.
- Las tablas necesitan introducción y conclusión; no deben depender únicamente del diseño visual.
- Los pronombres ambiguos se sustituyen cuando dificulten identificar el concepto recuperado.
- Las referencias cruzadas usan el nombre del ebook y, cuando exista, un identificador estable.
- Las fuentes se enlazan desde la afirmación o desde su nota; nunca dependen solo de una bibliografía sin correspondencia.

## Casos de uso previstos

El lector podrá utilizar la base con IA para:

- diagnosticar su situación mediante preguntas basadas en el libro;
- adaptar un marco a su modelo de negocio, país, presupuesto y capacidad;
- convertir un capítulo en un plan de acción;
- revisar una oferta, mensaje, proceso o experiencia contra un checklist;
- comparar alternativas sin perder los criterios del autor;
- preparar reuniones, experimentos y métricas;
- detectar qué información adicional necesita antes de decidir;
- navegar hacia el ebook más pertinente.

La IA no debe utilizarse para atribuir al libro datos que no contiene, fabricar testimonios, reemplazar asesoría legal o financiera ni convertir recomendaciones condicionadas en garantías.

## Contrato de respuesta para asistentes de IA

Las guías específicas pedirán al modelo:

1. utilizar primero el material proporcionado;
2. diferenciar lo extraído del libro de sus inferencias;
3. citar capítulo o sección cuando sea posible;
4. declarar cuándo falta información;
5. preguntar solo por datos que cambien una decisión;
6. adaptar sin contradecir los límites del ebook;
7. no presentar información externa como parte del libro;
8. recomendar verificación actual cuando trate plataformas, leyes, precios, pagos o políticas.

## Diseño de los prompts incluidos

Los prompts se organizan por resultado, no por espectáculo técnico:

- **Comprender**: explicar y relacionar conceptos.
- **Diagnosticar**: encontrar síntomas, causas y vacíos de información.
- **Decidir**: comparar alternativas con criterios explícitos.
- **Aplicar**: producir un plan ajustado al negocio.
- **Revisar**: auditar una pieza o proceso contra el libro.
- **Medir**: definir señales, métricas y próxima revisión.

Cada prompt incluirá objetivo, datos que debe aportar el lector, formato de salida, límites y criterio de calidad.

## Actualización y trazabilidad

- Los principios duraderos se revisan cuando cambie la evidencia o la arquitectura del ecosistema.
- Plataformas, leyes, pagos y políticas se verifican antes de publicar o reutilizar una recomendación.
- Estadísticas y tendencias priorizan fuentes de los últimos 24 meses.
- El campo `evidence_reviewed_at` permite a una IA advertir sobre posible caducidad.
- Una salida generada por IA nunca actualiza el canon por sí sola; primero debe revisarse y aprobarse.

## Privacidad, propiedad y portabilidad

- No se cargan en servicios externos credenciales, datos sensibles de clientes ni información confidencial.
- La guía de cada volumen advertirá al lector que anonimice sus datos.
- El Markdown será la fuente portable y no dependerá de una herramienta o proveedor de IA concreto.
- Los prompts son auxiliares del conocimiento adquirido; no reemplazan el libro ni entregan una reconstrucción sustitutiva de toda la obra.

## Criterio de aceptación

Un ebook está preparado para IA cuando una persona puede cargar su paquete de conocimiento y obtener respuestas que:

- respeten el alcance del volumen;
- distingan evidencia e inferencia;
- señalen la sección utilizada;
- conserven contexto latinoamericano;
- reconozcan límites y datos faltantes;
- produzcan decisiones o acciones, no solo resúmenes.
