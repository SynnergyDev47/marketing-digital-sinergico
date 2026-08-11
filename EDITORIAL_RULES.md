---
title: Reglas editoriales y de evidencia
project: marketing-digital-sinergico
version: 2.0
status: canonico-proyecto
updated: 2026-08-11
controlled_by:
  - DECISIONES_EDITORIALES.md
depends_on:
  - TONE_MATRIX.md
  - AI_USAGE_GUIDE.md
feeds:
  - WORKFLOW.md
---

# Reglas editoriales y de evidencia

## Principios

1. **Claridad sobre complejidad.** Simplificar la expresión, no la realidad.
2. **Estrategia sobre relleno.** Cada sección debe ayudar a comprender, decidir o actuar.
3. **Evidencia sobre autoridad aparente.** Una afirmación importante necesita respaldo o una etiqueta honesta.
4. **Aplicación sobre acumulación.** Los marcos se incluyen por utilidad, no por cantidad.
5. **Referencia sobre duplicación.** Resumir lo indispensable y dirigir a la profundidad correcta.
6. **Portabilidad sobre dependencia.** Markdown es la fuente maestra y debe funcionar fuera de una herramienta concreta.

## Extensión

| Producto | Rango orientativo |
|---|---:|
| Ebooks gratuitos | 10.000–15.000 palabras |
| Ebooks pagados especializados | 25.000–35.000 palabras |
| El Gran Túnel | 40.000–55.000 palabras |

Puede aplicarse un margen de ±10 % cuando eliminar o añadir contenido perjudique la promesa. La extensión no es una cuota de relleno.

## Estructura de capítulo

Modelo flexible:

`tensión → explicación → evidencia → aplicación → decisión`

No todas las piezas necesitan las cinco partes como subtítulos. La narración debe sentirse natural.

- Gratuitos: aplicación breve por capítulo y plan de acción final.
- Pagados: ejercicio, diagnóstico o herramienta útil en cada capítulo; no una hoja de trabajo ornamental.

## Clasificación interna de afirmaciones

| Clase | Regla |
|---|---|
| Hecho verificado | Fuente recuperable y uso fiel a su contexto |
| Dato volátil | Incluye fecha, geografía y revisión de vigencia |
| Inferencia | Se identifica como interpretación derivada |
| Recomendación | Declara condiciones y criterio práctico |
| Ejemplo | Se marca como real, compuesto o hipotético |
| Hipótesis | No se presenta como conclusión |

Las etiquetas viven en la matriz y en las notas editoriales; solo aparecen en el manuscrito cuando el lector pueda confundir la naturaleza de la afirmación.

## Fuentes y citas

- Notas numéricas discretas en el texto.
- Numeración reiniciada en cada capítulo.
- Notas agrupadas por capítulo.
- Bibliografía completa al final.
- Preferencia por fuente primaria, institucional, académica o documentación oficial.
- URL, DOI o referencia estable obligatoria para una afirmación verificable importante.
- Prohibidas en la versión final las referencias internas de una conversación (`turn...`) sin recuperar la fuente original.
- No atribuir a una fuente una causalidad o geografía que no estudió.

## Vigencia

- Plataformas, leyes, pagos, disponibilidad y políticas: verificación inmediatamente antes de publicar.
- Estadísticas y tendencias: preferir los últimos 24 meses; justificar excepciones.
- Principios duraderos: conservar la fuente original y revisar si cambia el consenso.
- La fecha `evidence_reviewed_at` debe acompañar los paquetes preparados para IA.

## Estilo y legibilidad

- Español panlatino y `tú` consistente.
- Frases mayormente cortas y párrafos con una idea dominante.
- Términos especializados o anglicismos explicados al aparecer.
- Analogías opcionales: se usan si aclaran y se eliminan si deforman.
- Tablas legibles en móvil y comprensibles sin diseño decorativo.
- Gráficos acompañados por explicación textual y texto alternativo.
- No depender del color para comunicar una diferencia esencial.
- PDF optimizado para baja conectividad.

## Prohibiciones

- relleno, repetición y recapitulación innecesaria;
- adjetivos de hype como sustituto de prueba;
- promesas garantizadas o resultados numéricos predictivos;
- estadísticas sin fuente y estadísticas zombi;
- testimonios o casos inventados presentados como reales;
- manipulación, dark patterns y falsa escasez;
- jerga sin explicación;
- presentar una salida de IA como evidencia;
- copiar bloques de otro ebook cuando basta una referencia.

## Preparación para IA

- Encabezados estables y descriptivos.
- Identificadores persistentes por ebook y capítulo.
- Contexto suficiente para entender una sección recuperada de forma aislada.
- Metadatos y relaciones definidos en [AI_USAGE_GUIDE.md](AI_USAGE_GUIDE.md).
- Diferenciación visible entre contenido del libro, inferencia del modelo e información externa.
- Ninguna herramienta de IA puede aprobar o actualizar el canon sin revisión humana.

## Control final

Un capítulo solo se aprueba si es claro, útil, rastreable, coherente con su alcance, accesible, reutilizable con IA y honesto sobre sus límites.
