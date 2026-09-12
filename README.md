# Libro Apokatastasis

Libro cristiano en desarrollo sobre la restauración universal.

El proyecto busca evaluar, paso a paso, el caso bíblico, histórico, filosófico y teológico a favor de la restauración universal, sin asumir de antemano que universalismo, infernalismo o aniquilacionismo sean verdaderos.

## ¿Cómo se escribe el libro?

El manuscrito avanza principalmente mediante **pregunta → respuesta → siguiente pregunta**. Cada conclusión importante debe considerar la evidencia principal, la mejor objeción, la mejor respuesta disponible y qué podría demostrar que estamos equivocados.

La Biblia es la fuente central del argumento. La investigación especializada sirve para aclarar los textos, no para reemplazarlos.

## ¿Qué partes del manuscrito existen hoy?

Actualmente están versionados en `capitulos/` los capítulos 1 al 8. El capítulo 8, **¿Qué muestra Apocalipsis sobre el destino final?**, completa la última gran prueba bíblica del recorrido y, como los capítulos anteriores, queda sujeto a auditorías futuras. La introducción **¿Por qué este libro?** y el epílogo todavía están previstos y no forman parte del manuscrito versionado.

## ¿Dónde está cada cosa?

- `capitulos/`: manuscrito, un capítulo por archivo.
- `proyecto/`: directivas, estado actual, hoja de ruta, decisiones y preguntas personales.
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
4. `skills/escritura-pregunta-respuesta/SKILL.md`.
5. `proyecto/PREGUNTAS_Y_REFLEXIONES_PERSONALES.md` cuando el tema pueda relacionarse con una inquietud guardada allí.

## ¿Cómo se trabaja con Git?

Se trabaja directamente sobre `main`. No se crean branches, pull requests, GitHub Actions ni procesos de `assemble` salvo que el usuario lo pida expresamente. Siempre que sea razonable, un cambio lógico debe quedar agrupado en un solo commit.
