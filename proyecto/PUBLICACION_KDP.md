# ¿Cómo se preparará este libro para Amazon KDP?

Este archivo reúne las decisiones canónicas de maquetación y publicación para **¿Restaurará Dios a todos?**, de Nicolás Bertoa.

`Apokatastasis` es el nombre interno del proyecto y del repositorio. No debe aparecer como título del libro en portada, cubierta, metadatos de KDP, ISBN ni materiales comerciales.

Los requisitos técnicos de Amazon KDP pueden cambiar. Las cifras de KDP recogidas aquí fueron verificadas el **12 de septiembre de 2026** en la documentación oficial de KDP y deben volver a comprobarse antes de la subida final.

## ¿Cuál es el título editorial exacto?

El título es:

**¿Restaurará Dios a todos?**

Debe conservarse exactamente, incluidos los signos de interrogación y la tilde de «Restaurará», en:

- portada interior;
- cubierta impresa;
- portada Kindle;
- ficha de Amazon KDP;
- ISBN y metadatos bibliográficos cuando corresponda.

En la cubierta puede componerse tipográficamente en mayúsculas —**¿RESTAURARÁ DIOS A TODOS?**— sin que eso cambie el título registrado.

No hay subtítulo definido.

## ¿Qué edición es esta?

La edición actualmente en preparación es la **Primera edición**.

La página legal o de derechos del interior debe indicar **«Primera edición»**.

No colocar «Primera edición» en la tapa ni en la portada interior principal salvo decisión posterior explícita.

En Amazon KDP, el campo **Edition number** debe cargarse con **1**. Antes de la publicación final, volver a verificar el comportamiento vigente de ese campo, porque modificar el número de edición después de publicar puede requerir una nueva edición.

## ¿Cuál es el tamaño físico elegido?

El formato de impresión elegido es:

- **6 × 9 pulgadas**;
- **15,24 × 22,86 cm**.

KDP identifica 6 × 9 pulgadas como el tamaño de impresión más común para libros de tapa blanda en Estados Unidos. El formato también está disponible para tapa dura dentro de los límites de páginas aplicables.

Este tamaño reemplaza para este libro el formato A5 heredado de workflows anteriores.

## ¿El interior llevará sangrado?

Por defecto, **no**.

El manuscrito es esencialmente textual y no necesita imágenes, fondos ni elementos gráficos que lleguen hasta el borde de la página. Por eso el interior debe prepararse en **6 × 9 pulgadas exactas, sin sangrado**.

Si en el futuro se agregara algún elemento que deba llegar hasta el borde, habrá que cambiar la configuración. Para un libro de 6 × 9 pulgadas con sangrado, KDP indica un tamaño de página de **6,125 × 9,25 pulgadas**. No debe activarse sangrado sin una necesidad concreta.

## ¿Qué tipo de interior se usará?

La configuración de referencia es:

- tinta negra;
- interior en blanco y negro;
- papel blanco, salvo decisión posterior distinta;
- lectura de izquierda a derecha;
- sin contenido a sangre.

El papel blanco es la preferencia heredada del workflow del autor. Si una prueba física muestra que el papel crema mejora claramente la experiencia de lectura, se puede reconsiderar antes de generar la cubierta definitiva, porque el tipo de papel afecta el ancho del lomo.

## ¿Qué tipografía usa el interior?

La familia tipográfica canónica es **EB Garamond** en todo el libro.

Valores de referencia heredados y actualmente vigentes:

- cuerpo: **EB Garamond 11 pt**;
- título de capítulo: **EB Garamond 32 pt, negrita, centrado**;
- preguntas/subtítulos: **EB Garamond 24 pt, negrita cursiva, centrado**;
- número de página: **EB Garamond 11 pt, centrado**.

Estos tamaños deben validarse visualmente en una muestra real de 6 × 9 pulgadas antes de generar el interior definitivo. En especial, los 24 pt de las preguntas pueden resultar demasiado grandes en un libro construido con muchas preguntas consecutivas. Si la prueba muestra una densidad deficiente, el tamaño podrá reducirse sin cambiar la familia tipográfica ni la jerarquía conceptual.

No mezclar EB Garamond con Calibri, Arial, Times New Roman u otras fuentes salvo una necesidad editorial explícita.

## ¿Cómo será la página de título?

La primera página debe contener, centrados y en este orden:

1. **¿Restaurará Dios a todos?**
2. **Nicolás Bertoa**
3. **jesusyyo.com**

No agregar subtítulo, epígrafe, indicación de edición, créditos de inteligencia artificial, descripción de fuentes ni otros elementos salvo decisión explícita posterior.

## ¿Cómo será la página legal o de derechos?

Debe incluir, como mínimo, la indicación **«Primera edición»**.

Los demás elementos —copyright, año, ISBN, editorial/imprint y cualquier aviso legal— se cerrarán cuando se defina la estrategia final de ISBN y publicación.

La página legal no debe inventar derechos, editoriales o identificadores todavía no asignados.

## ¿Cómo se alineará el cuerpo?

El cuerpo se compondrá **justificado**.

La referencia heredada usa:

- espaciado posterior de párrafo: `200` en unidades DOCX;
- interlineado: `340` en unidades DOCX.

Esos valores técnicos se consideran punto de partida, no una obligación visual independiente del resultado. La prueba de 6 × 9 debe confirmar que el ritmo de lectura es cómodo y que no aparecen ríos de blanco, líneas demasiado abiertas ni páginas excesivamente aireadas.

## ¿Qué márgenes se usarán?

La decisión editorial de partida es usar márgenes espejados y un aspecto más generoso que el mínimo técnico de KDP.

Objetivo inicial:

- superior: **0,75 pulgadas**;
- inferior: **0,75 pulgadas**;
- exterior: **0,75 pulgadas**;
- interior: **0,75 pulgadas como punto de partida**, sujeto al número final de páginas.

KDP exige que el margen interior aumente con el número de páginas. Para interiores sin sangrado, los mínimos vigentes son:

| Páginas | Margen interior mínimo KDP | Margen exterior mínimo KDP |
| --- | --- | --- |
| 24–150 | 0,375 in | 0,25 in |
| 151–300 | 0,5 in | 0,25 in |
| 301–500 | 0,625 in | 0,25 in |
| 501–700 | 0,75 in | 0,25 in |
| 701–828 | 0,875 in | 0,25 in |

Por tanto, **el margen interior definitivo no se fija hasta conocer el número final de páginas**. Si el libro supera 700 páginas, 0,75 pulgadas dejaría de ser suficiente según los mínimos actuales de KDP.

Usar márgenes espejados. No agregar un valor separado en el campo `Gutter/Medianil` de Word si se sigue el método recomendado por KDP con margen interior ya definido.

## ¿Habrá encabezados y pies de página?

El número de página debe ir centrado en el pie con EB Garamond 11 pt.

No se han definido encabezados corridos. Si se agregan, habrá que revisar nuevamente los márgenes superior e inferior y la relación con el comienzo de capítulos.

## ¿Cómo se tratan los títulos al paginar?

Ningún título de capítulo ni pregunta debe quedar huérfano al final de una página con su primer párrafo en la página siguiente.

Aplicar propiedades de paginación para mantener el encabezado con el párrafo siguiente. Evitar saltos manuales innecesarios.

No debe haber páginas completamente vacías producidas accidentalmente por saltos de página, saltos de sección o párrafos vacíos.

## ¿Cómo se manejará el índice?

El índice se genera o actualiza **al final**, después de cerrar la maquetación y la paginación.

Debe incluir:

- prólogo;
- capítulos 1–9 con sus títulos completos;
- epílogo;
- fuentes, si la edición final incluye esa sección.

Debe verificarse:

- numeración real de páginas;
- puntos de relleno;
- fuente y tamaño coherentes;
- ausencia de secciones faltantes.

## ¿Habrá una página de fuentes?

Si se incluye, debe contener solamente fuentes realmente usadas en el manuscrito o necesarias para documentar la edición.

No agregar créditos a ChatGPT, OpenAI u otras herramientas de inteligencia artificial ni frases de generación asistida por IA salvo una obligación legal o una decisión expresa posterior del autor.

La forma exacta de la bibliografía/fuentes todavía debe definirse para esta edición; no debe copiarse automáticamente una lista heredada de otro libro.

## ¿Cómo será la cubierta impresa?

El diseño de referencia es minimalista:

- fondo negro;
- tipografía EB Garamond blanca;
- contratapa a la izquierda;
- lomo al centro;
- tapa a la derecha;
- título **¿RESTAURARÁ DIOS A TODOS?** en el tercio superior de la tapa;
- `Nicolás Bertoa` cerca del pie de la tapa;
- reseña contemplativa de aproximadamente 80–100 palabras en la contratapa;
- `Nicolás Bertoa — jesusyyo.com` al pie de la contratapa.

El acabado de referencia es **mate**.

KDP puede colocar el código de barras. Esa es la opción predeterminada salvo necesidad específica de incorporar uno propio.

## ¿Podemos definir ahora las dimensiones de la cubierta completa?

No.

La cubierta de imprenta depende de:

- 6 × 9 pulgadas de tamaño de corte;
- número final de páginas;
- tipo de papel;
- tipo de tinta/interior;
- tipo de encuadernación.

El ancho del lomo sólo debe calcularse cuando el PDF interior definitivo haya fijado el número de páginas. Para la cubierta final se debe usar el **calculador/plantilla oficial de KDP** correspondiente a esos datos.

No reutilizar una plantilla antigua de otro libro sin recalcularla.

## ¿Cómo será la portada Kindle?

La portada digital contiene **sólo la tapa frontal**. No incluye contratapa ni lomo.

El workflow histórico usaba JPG RGB de 1600 × 2560 px. Esa dimensión se conserva sólo como referencia histórica y debe verificarse contra los requisitos vigentes antes de generar el archivo final.

No deformar el diseño de la tapa impresa para obtener otra relación de aspecto. Adaptar el lienzo preservando las proporciones y la composición.

## ¿Qué metadatos están ya definidos?

- título: **¿Restaurará Dios a todos?**;
- autor: **Nicolás Bertoa**;
- edición: **1 / Primera edición**;
- editorial/imprint opcional: **jesusyyo.com**;
- subtítulo: **ninguno definido**;
- descripción: debe basarse en el contenido real del libro;
- categorías y palabras clave: se elegirán con las opciones vigentes de KDP en el momento de publicación;
- derechos: declarar únicamente derechos que el autor realmente posea o pueda publicar.

El título debe coincidir exactamente entre portada, cubierta, ficha de KDP e identificadores bibliográficos.

No activar KDP Select automáticamente si el mismo contenido se distribuye de una manera incompatible con la exclusividad vigente.

No cambiar DRM, título u otros campos potencialmente difíciles de revertir sin confirmación explícita antes de la publicación final.

## ¿Qué decisiones todavía faltan?

Antes de generar archivos finales hay que cerrar:

1. tamaño final de H1 y H2 después de ver una muestra real de 6 × 9;
2. papel blanco o crema;
3. número final de páginas;
4. margen interior definitivo según ese número de páginas;
5. inclusión o no de encabezados corridos;
6. forma final de la página de derechos y de fuentes;
7. ISBN: propio o asignado por KDP, según la estrategia de publicación;
8. texto definitivo de contratapa;
9. metadatos comerciales: descripción, categorías y palabras clave;
10. dimensiones exactas de la cubierta completa, calculadas al final.

## ¿Cuál es el orden de trabajo para producir la edición impresa?

1. Congelar una versión editorial del manuscrito.
2. Generar una primera maqueta DOCX en 6 × 9.
3. Revisar visualmente tipografía, jerarquías, espaciado, densidad y comienzos de capítulo.
4. Ajustar sólo lo que la prueba física/visual justifique.
5. Determinar el número final de páginas.
6. Fijar el margen interior definitivo y volver a paginar si corresponde.
7. Generar el PDF interior final sin marcas de corte, comentarios ni elementos invisibles.
8. Revisar página por página: blancos accidentales, títulos huérfanos, numeración e índice.
9. Con el número de páginas definitivo, generar la plantilla de cubierta de KDP.
10. Preparar la cubierta completa sobre esa plantilla.
11. Subir interior y cubierta a KDP y revisar el Print Previewer.
12. Corregir cualquier advertencia real del previsualizador antes de aprobar.
13. Pedir una prueba física antes de considerar cerrada la edición, cuando sea posible.

## ¿Qué fuentes definen esta especificación?

Decisiones del autor y documentos de referencia aportados al proyecto:

- `FUENTE-FORMATO-DOCX.md`: EB Garamond, jerarquía tipográfica, portada interior, paginación, índice y reglas de DOCX;
- `FUENTE-CUBIERTAS.md`: diseño minimalista de cubierta y separación entre cubierta impresa y portada Kindle;
- `FUENTE-KDP.md`: workflow histórico de KDP, interior blanco y negro, papel blanco como preferencia, mate y barcode de KDP.

Verificación técnica vigente realizada sobre la documentación oficial de Amazon KDP:

- tamaño de impresión, sangrado y márgenes;
- opciones de impresión y límites de páginas;
- requisitos de cubierta y calculador de portadas.

Cuando una preferencia histórica entre en conflicto con un requisito vigente de KDP, prevalece el requisito técnico de KDP. Cuando no exista conflicto, prevalece la decisión editorial documentada para este libro.
