# ¿Qué debe hacer cualquier agente antes de trabajar en este repositorio?

1. Leer `proyecto/DIRECTIVAS_PROYECTO.md`.
2. Leer `proyecto/ESTADO_ACTUAL.md`.
3. Leer `proyecto/HOJA_DE_RUTA.md`.
4. Si la tarea modifica el manuscrito, leer `skills/escritura-pregunta-respuesta/SKILL.md`.
5. Si el trabajo cambia orden, nombres o estructura, leer `ESTRUCTURA_REPOSITORIO.md` y `proyecto/DECISIONES_EDITORIALES.md`.
6. Si la tarea afecta maquetación, DOCX, PDF de imprenta, cubierta, Kindle o Amazon KDP, leer **antes de hacer cambios** `proyecto/PUBLICACION_KDP.md`.
7. Para editar un capítulo, leer primero el capítulo completo y sus transiciones con el anterior y el siguiente.
8. Consultar `proyecto/PREGUNTAS_Y_REFLEXIONES_PERSONALES.md` por si existe una inquietud del usuario relevante para el tema.

# ¿Cuál es la prioridad?

Precisión antes que defensa de una conclusión. El proyecto construye el caso más fuerte posible a favor de la restauración universal, pero ninguna respuesta puede asumirse de antemano. Toda objeción fuerte debe conservarse hasta que pueda responderse.

La fase principal de auditoría del manuscrito está cerrada para la edición actualmente en preparación. No iniciar nuevas auditorías integrales por rutina. Reabrir contenido sólo ante un error concreto, una contradicción real o nueva evidencia suficientemente importante.

# ¿Cuál es el formato de publicación vigente?

La edición impresa se prepara para Amazon KDP en **6 × 9 pulgadas (15,24 × 22,86 cm)**.

`proyecto/PUBLICACION_KDP.md` es la referencia canónica para tipografía, márgenes, sangrado, cubierta, portada Kindle, metadatos y secuencia de producción. No reutilizar automáticamente el A5 ni plantillas de cubierta de libros anteriores.

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
- Cambios de maquetación o publicación: `proyecto/PUBLICACION_KDP.md`.
- Preguntas personales nuevas: `proyecto/PREGUNTAS_Y_REFLEXIONES_PERSONALES.md`.

# ¿Qué carpeta contiene el manuscrito?

`capitulos/`. La versión más reciente de cada archivo allí es la versión canónica del manuscrito en Git.

# ¿Dónde están las fuentes de investigación?

Los libros, artículos y PDFs completos permanecen en las Fuentes/biblioteca del Proyecto. No deben copiarse al repositorio. Git conserva el manuscrito, las decisiones, el estado, las notas propias y las skills.
