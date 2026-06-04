# Typstuc Templates

Plantillas en Typst para informes y tareas con el formato de ICS1113. Proyecto original creado por Vicente Zúñiga colaborado por Sebastián Pennerhag, esta versión simplificada del proyecto de TypstUC para uso exclusivo dentro del ramo, para más plantillas revisar el proyecto original.

## Uso

1. Edita [config/variables.typ](config/variables.typ) con los datos de tu documento. 
2. En la variable archivo escoga el tipo de documento que se va a utilizar, archivo=0 para tareas y archivo=1 para informes.
3. Edita la configuración general de acuerdo a tus necesidades en [config/template.typ](config/template.typ).
4. Edita tu documento dentro de [main.typ](main.typ).
5. Compila el documento con Typst.

## Estructura

- `assets/`: recursos gráicos
- `bibliography.bib`
- `config/`
  - `template.typ`: configuración general.
  - `variables.typ`: nombre, fecha, autores, archivo, etc.
- `content/`
  - `tarea_opti.typ`
  - `informe_opti.typ`
- `main.typ`: main file
- `main.pdf`: compiled file

## Requisitos

- Typst instalado localmente o acceso a [Typst web](https://typst.app/play/).
- Un editor compatible con Typst, como VS Code.
