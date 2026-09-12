# ¿Cómo está organizado el repositorio?

Este archivo es el mapa canónico del repositorio. Debe actualizarse cuando cambie un nombre, un número, una carpeta o la función de un archivo.

```text
libro-apokatastasis/
├── README.md
├── AGENTS.md
├── ESTRUCTURA_REPOSITORIO.md
├── .gitignore
├── manuscrito/
│   ├── 00_por_que_este_libro.md
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

- **`manuscrito/`** contiene sólo texto destinado al libro o placeholders explícitos de capítulos aún no redactados. Cada capítulo vive en un archivo independiente para poder auditarlo y versionarlo sin tocar los demás.
- **`proyecto/`** conserva el contexto que debe sobrevivir aunque se borren todos los chats.
- **`skills/`** conserva métodos de trabajo reutilizables.
- **`investigacion/`** conserva notas propias, no la biblioteca completa.

## ¿Cómo se nombran los capítulos?

Con número de dos dígitos, guion bajo y nombre descriptivo en minúsculas: `NN_nombre_del_capitulo.md`. El número refleja el orden actual. Si el orden cambia, los archivos se renombran.

## ¿Dónde se registra un cambio de estructura?

En el mismo commit que realiza el cambio deben actualizarse, cuando corresponda:

- este archivo;
- `README.md`;
- `proyecto/ESTADO_ACTUAL.md`;
- `proyecto/HOJA_DE_RUTA.md`.

## ¿Dónde se guardará el epílogo?

Todavía no existe archivo porque su pregunta principal no está definida. Cuando se decida, se agregará como `09_<pregunta>.md` y se actualizará este mapa.
