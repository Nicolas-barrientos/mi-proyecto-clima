1.¿Qué mala práctica identificaste?
*El archivo index.ccs no estaba vinculado al index.hmtl*
*Algunos comentarios que no estaban bien claros.*

2.¿Por qué es considerada una mala práctica, no vincular el archivo index.css al index.html?
**No vincular el archivo index.css al index.html es una mala práctica porque el diseño no se aplica, entonces el código CSS se vuelve inútil, ya que puede generar confusión en otros desarrolladores y demuestra desorganización en el proyecto.**

¿Por qué es considerada una mala práctica no poner comentarios claros en las partes de los codigos?
**No poner comentarios claros en el código es una mala práctica porque dificulta su comprensión, mantenimiento y colaboración.Los comentarios ayudan a que otros desarrolladores (o uno mismo en el futuro) entiendan rápidamente qué hace una parte del código, especialmente en secciones complejas o clave. Sin comentarios, el código puede volverse confuso y propenso a errores.**

3.¿Cómo la solucionaste?
**Para corregir, agregue la línea <link rel="stylesheet" href="index.css"> dentro del <head> del HTML.**

**Lo solucione colcando un comentario claro ANTES de lo que hacia cada codigo, para poder comprender mejor cada parte o seccion del codigo**

4.¿Qué beneficios aporta tu solución?
**Solución 1 – Vincular correctamente el CSS al HTML:**
Asegurarse de que el archivo `index.html` tenga bien referenciado el archivo `index.css` mediante la etiqueta `<link>`. Esto permite que los estilos se apliquen correctamente, mejorando la apariencia y experiencia del usuario.

**Solución 2 – Agregar comentarios claros en el código:**
Incorporar comentarios explicativos en secciones clave del código (HTML, CSS o JavaScript) para facilitar su lectura, mantenimiento y comprensión por parte de otros desarrolladores o del propio autor en el futuro.
