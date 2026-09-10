# fundamentos-web-taller1
Nombre: Yhojan David Collo Ortega, William Diaz Moreano, Alex Santiago Bocanegra Mejia
Este repositorio contiene el primer taller de HTML de la asignatura
Fundamentos de Programacion Web.
## Verificación y Corrección de Errores

### Caso A
 Problema identificado: La imagen del campus de la universidad no se mostraba en la página web.
 Corrección realizada: Se corrigió la ruta del atributo `src` en la etiqueta `<img>` para apuntar correctamente a la carpeta `multimedia/imagen1.jpg`.
 Fuente consultada: MDN Web Docs - Atributos de ruta y elemento img.

### Caso B
Problema identificado: El reproductor de audio nativo no cargaba el archivo de sonido local.
Corrección realizada: Se verificó el nombre del archivo en el atributo `src` dentro de `<source>` y se aseguró que el archivo estuviera ubicado en el directorio `multimedia/`.
Fuente consultada: MDN Web Docs - Elemento de audio HTML5 `<audio>`.

### Caso C
Problema identificado: El video incrustado desde YouTube mediante `<iframe>` arrojaba error de conexión ("www.youtube.com rechazó la conexión").
Corrección realizada: Se cambió la URL convencional del video (`/watch?v=`) por la URL de incrustación autorizada (`/embed/`).
Fuente consultada: Documentación de soporte de YouTube - Incrustar videos en sitios web.

### Caso D
Problema identificado: La tabla del horario no tenía una estructura semántica clara ni encabezados definidos.
Corrección realizada: Se estructuró la tabla utilizando los elementos semánticos `<caption>`, `<thead>`, `<tbody>`, `<tr>` y `<th>`.
Fuente consultada: W3Schools - HTML Table Basics.

### Caso E
Problema identificado: Los campos del formulario no estaban asociados correctamente con sus etiquetas de texto.
Corrección realizada: Se vincularon las etiquetas `<label>` con sus respectivos controles mediante el atributo `for` coincidiendo con el `id` de cada `<input>`.
Fuente consultada: MDN Web Docs - HTML Forms and Labels.
