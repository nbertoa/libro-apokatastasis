# ¿Qué debe hacer cualquier agente antes de trabajar en este repositorio?

1. Leer `proyecto/DIRECTIVAS_PROYECTO.md`.
2. Leer `proyecto/ESTADO_ACTUAL.md`.
3. Leer `skills/escritura-pregunta-respuesta/SKILL.md`.
4. Si el trabajo cambia orden, nombres o estructura, leer `ESTRUCTURA_REPOSITORIO.md` y `proyecto/HOJA_DE_RUTA.md`.
5. Para editar un capítulo, leer primero el capítulo completo y sus transiciones con el anterior y el siguiente.
6. Consultar `proyecto/PREGUNTAS_Y_REFLEXIONES_PERSONALES.md` por si existe una inquietud del usuario relevante para el tema.

# ¿Cuál es la prioridad?

Precisión antes que defensa de una conclusión. El proyecto construye el caso más fuerte posible a favor de la restauración universal, pero ninguna respuesta puede asumirse de antemano. Toda objeción fuerte debe conservarse hasta que pueda responderse.

# ¿Cómo se trabaja con Git?

- Trabajar siempre directamente sobre `main`.
- No crear branches ni pull requests salvo pedido explícito del usuario.
- No usar GitHub Actions, workflows ni procesos de `assemble` salvo pedido explícito del usuario.
- Siempre que sea razonable, agrupar una tarea lógica en un solo commit.
- Git es el mecanismo de reversión: una mejora razonable y reversible puede aplicarse y pushearse sin pedir una confirmación adicional.

# ¿Qué debe actualizarse después de un cambio importante?

- Cambios de estructura o nombres: `ESTRUCTURA_REPOSITORIO.md`.
- Cambios de orden, progreso o próxima tarea: `proyecto/ESTADO_ACTUAL.md` y, si corresponde, `proyecto/HOJA_DE_RUTA.md`.
- Decisiones permanentes de método o edición: `proyecto/DECISIONES_EDITORIALES.md`.
- Preguntas personales nuevas: `proyecto/PREGUNTAS_Y_REFLEXIONES_PERSONALES.md`.

# ¿Qué carpeta contiene el manuscrito?

`capitulos/`. La versión más reciente de cada capítulo allí es la versión canónica del manuscrito en Git.

# ¿Dónde están las fuentes de investigación?

Los libros, artículos y PDFs completos permanecen en las Fuentes/biblioteca del Proyecto. No deben copiarse al repositorio. Git conserva el manuscrito, las decisiones, el estado, las notas propias y las skills.
