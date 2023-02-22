# Plantilla de LaTeX para Tesis
Esta es una plantilla no oficial diseñada para el posgrado de **Ciencias en Bioprocesos** de la **UPIBI**. Contiene algunos comandos básicos para modificar la portada y una estructura de archivos fácil de seguir.

### Comandos de para la portada:
- `\logosup{}`,`\logoinf{}` : Permite cambiar las imágenes superior e inferior de la portada, respectivamente. Sólo se debe colocar el nombre de la imagen sin extensión (de preferencia en formato PDF, EPS, SVG o PNG). Las imágenes se toman de la carpeta configurada con el comando `\graphicspath{{<carpeta>/}}`, por ejemplo: `\graphicspath{{figures/}}`.


- `\universidad{}` : Si se deja comentado (`% \universidad{}`) se mostrará en el PDF el texto por default (**Instituto**). Si se descomenta pero se deja vacío, se mostrará en el PDF el texto de ejemplo (**Instituto Politécnico Nacional**). El texto entre llaves sobreescribirá el texto de ejemplo.

- `\unidad{}` : Si se comenta (`% \unidad{}`) no se mostrará el texto. Si se deja vacío (`\unidad{}`) se mostrará el texto por default (**Unidad Profesional Interdisciplinaria de Biotecnología**). El texto entre llaves sobreescribirá el texto de default.

- `\seccion{}` : Si se comenta (`% \seccion{}`) no se mostrará el texto. Si se deja vacío se mostrará el texto por default (**Sección de Estudios de Posgrado**). El texto entre llaves sobreescribirá el texto de default.

- `\titulotesis{}` : Si se comenta se mostrará el texto por default (**Titulo de Tesis**). Si se deja vacío se mostrará el titulo por default (**Sistema semicontinuo de ...**). El texto entre llaves sobreescribirá el titulo de default.

- `\grado{}` :
    - `% \grado{}` PDF --> Vacío
    - `\grado{}` PDF --> Maestro en Ciencias
    - `\grado{Otro Grado}` PDF --> Otro Grado

- `\alumno{}` :
    - `% \alumno{}` PDF --> Vacío
    - `\alumno{}` PDF --> Nombre del Alumno
    - `\alumno{Mi nombre}` PDF --> Mi nombre

- `\directores{}` :
    - `% \directores{}` PDF --> Vacío
    - `\directores{}` PDF --> Director(es) de Tesis
    - `\directores{Nombre de Director}` PDF --> Nombre de Director

- `\fecha{}` :
    - `% \fecha{}` PDF --> Lugar Mes y Año
    - `\fecha{}` PDF --> Ciudad de México, Agosto de 2022
    - `\fecha{\today}` PDF --> 22 de febrero de 2023 (fecha de hoy)
