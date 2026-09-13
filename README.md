# Libro Apokatastasis

Libro cristiano sobre la restauración universal.

El proyecto evalúa, paso a paso, el caso bíblico, filosófico y teológico a favor de la restauración universal, sin asumir de antemano que restauración universal, tormento consciente sin fin o aniquilacionismo sean verdaderos.

## ¿Cómo está construido el libro?

El manuscrito avanza principalmente mediante **pregunta → respuesta → siguiente pregunta**. Cada conclusión importante debe considerar la evidencia principal, la mejor objeción, la mejor respuesta disponible y qué podría demostrar que estamos equivocados.

La Biblia es la fuente central del argumento. La investigación especializada sirve para aclarar los textos, no para reemplazarlos.

## ¿Qué partes del manuscrito existen hoy?

El manuscrito está completo en `capitulos/` y contiene:

- prólogo;
- capítulos argumentales 1–9;
- epílogo.

El contenido pasó por varias rondas integrales de auditoría de coherencia, estructura, imparcialidad, cobertura bíblica, claridad y continuidad. Para esta edición, la fase principal de auditoría de contenido se considera cerrada salvo que aparezca un error concreto o nueva evidencia importante.

## ¿En qué fase está el proyecto?

En **preparación editorial y publicación**.

La edición impresa se prepara para Amazon KDP en **6 × 9 pulgadas (15,24 × 22,86 cm)**. La especificación canónica de tipografía, márgenes, interior, cubierta y workflow está en `proyecto/PUBLICACION_KDP.md`.

## ¿Dónde está cada cosa?

- `capitulos/`: manuscrito canónico, un archivo por parte o capítulo.
- `proyecto/`: directivas, estado actual, hoja de ruta, decisiones editoriales, especificación KDP y preguntas personales.
- `skills/`: métodos de trabajo reutilizables para escribir y auditar.
- `investigacion/`: notas propias que convenga conservar en Git.
- `ESTRUCTURA_REPOSITORIO.md`: mapa canónico de carpetas y archivos.
- `AGENTS.md`: instrucciones para continuar el proyecto desde una sesión nueva.

Los PDFs, libros y artículos completos de investigación permanecen en las Fuentes/biblioteca del Proyecto y no se duplican en Git.

## ¿Cómo se continúa el proyecto desde una sesión nueva?

Leer, en este orden:

1. `AGENTS.md`.
2. `proyecto/DIRECTIVAS_PROYECTO.md`.
3. `proyecto/ESTADO_ACTUAL.md`.
4. `proyecto/HOJA_DE_RUTA.md`.
5. `proyecto/DECISIONES_EDITORIALES.md`.
6. `proyecto/PUBLICACION_KDP.md` si la tarea afecta maquetación, impresión, cubierta o publicación.
7. `skills/escritura-pregunta-respuesta/SKILL.md` si la tarea afecta el texto del manuscrito.

## ¿Cómo se trabaja con Git?

Se trabaja directamente sobre `main`. No se crean branches, pull requests, GitHub Actions ni procesos de `assemble` salvo que el usuario lo pida expresamente. Siempre que sea razonable, un cambio lógico debe quedar agrupado en un solo commit.
