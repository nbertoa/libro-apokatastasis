# ¿Qué decisiones editoriales están vigentes?

## ¿Cuál es la forma normal del libro?

**Pregunta → respuesta → siguiente pregunta.** Una pregunta por vez y una idea principal por respuesta. La siguiente pregunta debe nacer de una dificultad real dejada por la respuesta anterior.

## ¿Cómo deben titularse las partes principales?

Siempre como preguntas. Esto incluye la introducción, los capítulos y, cuando se defina, el epílogo.

## ¿Cómo se nombran los archivos de capítulos?

`NN_nombre_en_minusculas_separado_por_guiones_bajos.md`

El número indica el orden actual. Si cambia el orden, se renombran los archivos y se actualizan `README.md`, `ESTRUCTURA_REPOSITORIO.md`, `proyecto/ESTADO_ACTUAL.md` y `proyecto/HOJA_DE_RUTA.md`.

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

Primero el capítulo sobre Hebreos, Santiago, Pedro, Judas y las cartas de Juan; después Pablo. Esto permite que esos escritos funcionen como prueba adversarial independiente antes de llegar a algunas de las afirmaciones más fuertes sobre la victoria universal de Cristo.

## ¿Dónde queda Apocalipsis?

Después de Pablo, como última gran prueba bíblica antes del cierre. Su interpretación no debe decidirse de antemano.

## ¿Hay que pedir confirmación para cada mejora?

No. Las mejoras razonables y reversibles de estructura, claridad, consistencia, documentación o flujo de trabajo deben aplicarse y versionarse directamente cuando sean pertinentes. Si una modificación cambia de manera sustantiva una conclusión doctrinal, elimina una objeción importante o altera el argumento central, debe quedar justificada por la evidencia y ser visible en el historial.

## ¿Puede el libro seguir mejorando después de una versión publicable?

Sí. Una edición puede cerrarse para publicación, pero el repositorio permanece abierto a nuevas auditorías y mejoras. Git debe permitir corregir sin perder estados anteriores.
