# Escribir Descripción Técnica de Proyectos PICT en LaTeX

Este es un esqueleto básico LaTeX para Descripción Técnica de Proyectos PICT (Agencia I+D+i, Argentina). Pueden forkear el repo, subirlo a Overleaf, usarlo en instalaciones locales de TexLive, etc. 

## El paso a paso

1. Editar `settings/variables.tex` (**mandatorio**)
  - Nombre y Apellido del IR
  - Titulo del proyecto
  - Codigo del PICT
  - Palabras clave
  - Institución Beneficiaria
2. Agregar tu archivo de referencias bibliograficas (.bib) y editar `settings/bibliography.tex`. Ahora mismo hay un `sample.bib` minimo de ejemplo. 
3. Opcional: editar `settings/colors.tex` y elegir colores para links, texto de secciones, etc.
4. Opcional: editoar `settings/fonts.tex` y elegir tipografia para texto + encabezados.
5. Opcional: editar `settings/page.tex` y modificar espacio entre parrafos, margenes, etc.
6. Compilar con XeLaTeX!
