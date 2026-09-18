# ¿Qué decisiones editoriales están vigentes?

## ¿Cómo se llama el libro?

El título editorial y comercial es **¿Restaurará Dios a todos?**

`Apokatastasis` es el nombre del proyecto y del repositorio de trabajo. No debe usarse como título del libro en la portada interior, cubierta, metadatos de KDP, ISBN ni materiales comerciales.

## ¿Cuál es la forma normal del libro?

**Pregunta → respuesta → siguiente pregunta.** Una pregunta por vez y una idea principal por respuesta. La siguiente pregunta debe nacer de una dificultad real dejada por la respuesta anterior.

## ¿Cómo deben titularse las partes principales?

Los capítulos argumentales se titulan como preguntas. El prólogo y el epílogo también mantienen títulos interrogativos para conservar la identidad del libro.

## ¿Cómo se nombran los archivos de capítulos?

`NN_nombre_en_minusculas_separado_por_guiones_bajos.md`

El número indica el orden actual. Si cambia el orden, se renombran los archivos y se actualizan `README.md`, `ESTRUCTURA_REPOSITORIO.md`, `proyecto/ESTADO_ACTUAL.md` y `proyecto/HOJA_DE_RUTA.md`.

El prólogo y el epílogo usan nombres descriptivos sin numeración porque enmarcan el recorrido argumental y no forman parte de la secuencia 1–9.

## ¿Cuál es el formato Markdown canónico de los capítulos?

Todos los capítulos deben usar la misma jerarquía Markdown:

```md
# Capítulo N — ¿Pregunta principal del capítulo?

## 1. ¿Primera pregunta?

Respuesta en texto normal.

## 2. ¿Segunda pregunta?

Respuesta en texto normal.
```

Reglas:

- Debe haber un solo encabezado de nivel 1 (`#`) y corresponde al título del capítulo.
- Cada pregunta numerada debe ser un encabezado de nivel 2 (`##`).
- Las preguntas no llevan negrita adicional: el encabezado ya expresa su jerarquía.
- Debe haber una línea en blanco después del título y después de cada pregunta antes de comenzar la respuesta.
- Las respuestas se escriben como párrafos normales. Cursivas, negritas y otros énfasis se conservan dentro de las respuestas cuando cumplen una función real.
- Una normalización de formato no debe cambiar palabras, argumentos, referencias ni conclusiones del manuscrito.
- Este formato debe mantenerse en todos los capítulos nuevos y en cualquier revisión futura de los existentes.

## ¿Cuál es la fuente canónica del manuscrito?

La versión más reciente presente en `capitulos/`. Las Fuentes del Proyecto siguen siendo la biblioteca de investigación y el lugar desde el que pueden importarse revisiones, pero una vez sincronizada una versión con Git, el repositorio registra el estado vigente del manuscrito.

## ¿Se guardan los PDFs de investigación en Git?

No. Los libros y artículos completos permanecen en las Fuentes/biblioteca del Proyecto. Git conserva el manuscrito, notas propias, decisiones, skills y estado de trabajo.

## ¿En qué orden se leen las epístolas y Pablo?

Primero el capítulo sobre Hechos, Hebreos, Santiago, Pedro, Judas y las cartas de Juan; después Pablo. Esto permite que esos escritos funcionen como una prueba independiente y exigente antes de llegar a algunas de las afirmaciones más amplias sobre la victoria de Cristo.

## ¿Dónde queda Apocalipsis?

Después de Pablo, como última gran prueba bíblica antes de la comparación final. Su interpretación no debe decidirse de antemano.

## ¿Se usará la oración por los muertos como argumento?

No. El manuscrito no presentará ni recomendará la **oración por los muertos**, ni la utilizará como evidencia a favor de la restauración universal.

Esto no impide estudiar por separado los textos bíblicos que puedan plantear una acción de Dios después de la muerte. La posibilidad de salvación o arrepentimiento post mortem y la práctica de orar por los muertos son cuestiones distintas y no deben confundirse.

## ¿Cuál es el formato físico elegido para Amazon KDP?

La edición impresa se diseñará en **6 × 9 pulgadas (15,24 × 22,86 cm)**.

Este tamaño reemplaza el A5 heredado de workflows anteriores para este libro.

La especificación completa de maquetación y publicación está en `proyecto/PUBLICACION_KDP.md`. Ese archivo es la referencia canónica para:

- tipografía;
- márgenes;
- sangrado;
- paginación;
- índice;
- cubierta;
- portada Kindle;
- metadatos;
- variables que sólo pueden cerrarse después de conocer el número final de páginas.

## ¿Qué edición es esta?

La edición que se está preparando es la **Primera edición** de **¿Restaurará Dios a todos?**

En la edición impresa, la página legal o de derechos debe indicar **«Primera edición»**. No colocar esa indicación en la tapa ni en la portada interior principal salvo una decisión posterior explícita.

En Amazon KDP, el campo **Edition number** debe cargarse con el número **1**. Antes de publicar, verificar nuevamente este dato porque KDP no permite modificar el número de edición de un libro ya publicado sin crear una nueva edición.

## ¿Qué tipografía se usará?

La familia canónica es **EB Garamond**.

El cuerpo parte de 11 pt. Los tamaños heredados para títulos y preguntas se conservarán como punto de partida, pero deben validarse visualmente en una maqueta real de 6 × 9 antes de considerarlos definitivos.

## ¿El interior llevará sangrado?

Por defecto, no. El libro es esencialmente textual. Sólo se activará sangrado si se incorpora contenido que deba llegar realmente hasta el borde de la página.

## ¿Hay que pedir confirmación para cada mejora?

No. Las mejoras razonables y reversibles de estructura, claridad, consistencia, documentación o flujo de trabajo deben aplicarse y versionarse directamente cuando sean pertinentes. Si una modificación cambia de manera sustantiva una conclusión doctrinal, elimina una objeción importante o altera el argumento central, debe quedar justificada por la evidencia y ser visible en el historial.

## ¿Puede el libro seguir mejorando después de una versión publicable?

Sí. Una edición puede cerrarse para publicación, pero el repositorio permanece abierto a nuevas auditorías y mejoras. Git debe permitir corregir sin perder estados anteriores.
