# ¿Cómo está organizado el repositorio?

Este archivo es el mapa canónico del repositorio. Debe actualizarse cuando cambie un nombre, un número, una carpeta o la función de un archivo.

## ¿Qué existe hoy?

```text
libro-apokatastasis/
├── README.md
├── AGENTS.md
├── ESTRUCTURA_REPOSITORIO.md
├── .gitignore
├── capitulos/
│   ├── prologo_por_que_hice_estas_preguntas.md
│   ├── 01_que_podria_impedir_que_dios_restaure_a_todos.md
│   ├── 02_que_hace_dios_con_un_mundo_que_se_aparta_de_el.md
│   ├── 03_hasta_donde_llega_la_esperanza_del_antiguo_testamento.md
│   ├── 04_que_muestran_los_evangelios_sobre_la_mision_de_jesus_y_el_juicio.md
│   ├── 05_es_el_juicio_la_ultima_palabra_sobre_los_perdidos.md
│   ├── 06_que_dicen_los_demas_escritos_del_nuevo_testamento_sobre_el_destino_final.md
│   ├── 07_hasta_donde_llega_la_victoria_de_cristo_segun_pablo.md
│   ├── 08_que_muestra_apocalipsis_sobre_el_destino_final.md
│   ├── 09_que_explicacion_del_final_hace_justicia_a_todo_lo_que_hemos_visto.md
│   └── epilogo_como_se_veria_una_victoria_completa.md
├── proyecto/
│   ├── DIRECTIVAS_PROYECTO.md
│   ├── ESTADO_ACTUAL.md
│   ├── HOJA_DE_RUTA.md
│   ├── DECISIONES_EDITORIALES.md
│   ├── PUBLICACION_KDP.md
│   ├── REFERENCIA_VISUAL.md
│   └── PREGUNTAS_Y_REFLEXIONES_PERSONALES.md
├── skills/
│   └── escritura-pregunta-respuesta/
│       └── SKILL.md
└── investigacion/
    └── README.md
```

## ¿Qué significa cada carpeta?

- **`capitulos/`** contiene el manuscrito canónico. Prólogo, capítulos 1–9 y epílogo viven en archivos independientes para poder auditarlos y versionarlos sin tocar los demás.
- **`proyecto/`** conserva el contexto que debe sobrevivir aunque se borren todos los chats: directivas, estado, hoja de ruta, decisiones y especificaciones de publicación.
- **`skills/`** conserva métodos de trabajo reutilizables.
- **`investigacion/`** conserva notas propias y análisis que convenga versionar, no la biblioteca completa.

## ¿Cómo se nombran los capítulos?

Los capítulos argumentales usan número de dos dígitos, guion bajo y nombre descriptivo en minúsculas: `NN_nombre_del_capitulo.md`.

El prólogo y el epílogo no llevan número porque enmarcan el recorrido argumental y no forman parte de la secuencia 1–9.

## ¿Dónde se documenta la publicación?

`proyecto/PUBLICACION_KDP.md` es la referencia canónica para la edición impresa y digital destinada a Amazon KDP.

Incluye:

- título editorial y número de edición;
- tamaño 6 × 9 pulgadas;
- tipografía;
- márgenes y sangrado;
- paginación;
- índice;
- cubierta impresa;
- portada Kindle;
- metadatos;
- pasos de producción;
- decisiones pendientes que dependen del número final de páginas.

`proyecto/REFERENCIA_VISUAL.md` documenta la referencia visual aprobada por el autor —**El arte perdido de preguntar**— y distingue qué rasgos de esa familia editorial deben conservarse y cuáles necesitan adaptación para **¿Restaurará Dios a todos?**.

## ¿Qué documentos deben actualizarse cuando cambia la estructura?

Según corresponda, en el mismo cambio deben revisarse:

- `ESTRUCTURA_REPOSITORIO.md`;
- `README.md`;
- `proyecto/ESTADO_ACTUAL.md`;
- `proyecto/HOJA_DE_RUTA.md`;
- `proyecto/DECISIONES_EDITORIALES.md` si el cambio establece una regla nueva;
- `proyecto/PUBLICACION_KDP.md` si cambia una decisión de maquetación o publicación;
- `proyecto/REFERENCIA_VISUAL.md` si cambia la referencia visual o la forma de trasladarla al nuevo libro.

## ¿Dónde se guardan las fuentes de investigación?

Los PDFs, libros y artículos completos permanecen en las Fuentes/biblioteca del Proyecto de ChatGPT. No se duplican en Git. Las conclusiones, auditorías y notas propias que deban sobrevivir entre sesiones sí pueden guardarse en `investigacion/`.
