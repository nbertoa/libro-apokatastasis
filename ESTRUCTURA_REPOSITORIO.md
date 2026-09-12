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
│   ├── 01_que_podria_impedir_que_dios_restaure_a_todos.md
│   ├── 02_que_hace_dios_con_un_mundo_que_se_aparta_de_el.md
│   ├── 03_hasta_donde_llega_la_esperanza_del_antiguo_testamento.md
│   ├── 04_que_muestran_los_evangelios_sobre_la_mision_de_jesus_y_el_juicio.md
│   ├── 05_es_el_juicio_la_ultima_palabra_sobre_los_perdidos.md
│   ├── 06_que_dicen_los_demas_escritos_del_nuevo_testamento_sobre_el_destino_final.md
│   ├── 07_hasta_donde_llega_la_victoria_de_cristo_segun_pablo.md
│   └── 08_que_muestra_apocalipsis_sobre_el_destino_final.md
├── proyecto/
│   ├── DIRECTIVAS_PROYECTO.md
│   ├── ESTADO_ACTUAL.md
│   ├── HOJA_DE_RUTA.md
│   ├── DECISIONES_EDITORIALES.md
│   └── PREGUNTAS_Y_REFLEXIONES_PERSONALES.md
├── skills/
│   └── escritura-pregunta-respuesta/
│       └── SKILL.md
└── investigacion/
    └── README.md
```

## ¿Qué significa cada carpeta?

- **`capitulos/`** contiene el manuscrito. Cada capítulo vive en un archivo independiente para poder auditarlo y versionarlo sin tocar los demás.
- **`proyecto/`** conserva el contexto que debe sobrevivir aunque se borren todos los chats.
- **`skills/`** conserva métodos de trabajo reutilizables.
- **`investigacion/`** conserva notas propias y análisis que convenga versionar, no la biblioteca completa.

## ¿Cómo se nombran los capítulos?

Con número de dos dígitos, guion bajo y nombre descriptivo en minúsculas: `NN_nombre_del_capitulo.md`. El número refleja el orden actual. Si el orden cambia, los archivos se renombran y este mapa se actualiza en el mismo cambio.

## ¿Qué está previsto pero todavía no existe como archivo de manuscrito?

- Introducción: **¿Por qué este libro?**. Cuando se redacte, se guardará como `capitulos/00_por_que_este_libro.md`.
- Epílogo/cierre: la pregunta todavía no está definida. Cuando se decida, se guardará como `capitulos/09_<pregunta>.md`.

## ¿Qué documentos deben actualizarse cuando cambia la estructura?

Según corresponda, en el mismo cambio deben revisarse:

- `ESTRUCTURA_REPOSITORIO.md`;
- `README.md`;
- `proyecto/ESTADO_ACTUAL.md`;
- `proyecto/HOJA_DE_RUTA.md`;
- `proyecto/DECISIONES_EDITORIALES.md` si el cambio establece una regla nueva.

## ¿Dónde se guardan las fuentes de investigación?

Los PDFs, libros y artículos completos permanecen en las Fuentes/biblioteca del Proyecto de ChatGPT. No se duplican en Git. Las conclusiones, auditorías y notas propias que deban sobrevivir entre sesiones sí pueden guardarse en `investigacion/`.
