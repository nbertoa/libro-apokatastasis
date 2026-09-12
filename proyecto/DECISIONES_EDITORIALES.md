# ¿Qué decisiones editoriales están vigentes?

## ¿Cuál es la forma normal del libro?

Pregunta → respuesta → siguiente pregunta. Una pregunta por vez y una idea principal por respuesta.

## ¿Cómo deben titularse las partes principales?

Siempre como preguntas. Esto incluye introducción, capítulos y, cuando se defina, el epílogo.

## ¿Cómo se nombran los archivos del manuscrito?

`NN_nombre_en_minusculas_separado_por_guiones_bajos.md`

El número indica el orden actual del manuscrito. Si cambia el orden, se renombran los archivos y se actualizan `README.md`, `ESTRUCTURA_REPOSITORIO.md`, `proyecto/ESTADO_ACTUAL.md` y `proyecto/HOJA_DE_RUTA.md`.

## ¿Cuál es la fuente canónica de cada capítulo?

La versión más reciente presente en `manuscrito/`. Cuando se importe una revisión desde las Fuentes del Proyecto, debe sustituir explícitamente la versión del repositorio mediante un commit identificable.

## ¿Se guardan los PDFs de investigación en Git?

No. Los libros y artículos completos permanecen en las Fuentes/biblioteca del Proyecto. Git conserva manuscrito, notas propias, decisiones, skills y estado de trabajo.

## ¿Hay que pedir confirmación para cada mejora?

No. Las mejoras razonables de estructura, claridad, consistencia, documentación o flujo de trabajo pueden aplicarse directamente y quedar registradas en Git. Si una modificación cambia de manera sustantiva una conclusión doctrinal o elimina una objeción importante, debe quedar justificada por la evidencia y explicada con claridad en el commit o en el estado del proyecto.

## ¿El libro queda terminado alguna vez?

Puede publicarse una versión, pero el repositorio permanece abierto a auditorías y mejoras. El historial de Git permite corregir sin perder versiones anteriores.
