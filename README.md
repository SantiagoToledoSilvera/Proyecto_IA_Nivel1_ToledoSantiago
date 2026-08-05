# AgendaBot

Repositorio del proyecto AgendaBot: bot conversacional en Telegram. para agendar citas, tareas, hábitos, listas y recordatorios, construido con n8n y Google Sheets.

## Opciones disponibles

- **`Agenda`** — Crea citas con opcion a editarlas y consultarlas.
- **`Tareas`** — Crea tareas y permite administrarlas.
- **`Recordatorios`** — Te permite ver los recordatorios para citas que tengas el mismo día, un mensaje te sera enviado el mismo día incluso si no eliges esta opción.
-  **`Hábitos`** — Crea y administra los habitos que quieras lograr.
-  **`Listas`** — Crea listas y agrega los objetos necesarios para estas, junto con la administración de estos.

## Modo de uso

Para correr el programa, copiar el archivo JSON en la carpeta workflow y pegarlo en la plataforma de n8n, luego publicar el flujo y finalmente escribirle al bot para comenzar.

### Extras

Pruebas de la creación, base de datosy funcionalidad del programa se encuentran en la carpeta de evidencias.
La carpeta de docs contiene el archivo docs con la información solicitada por el cliente para los requerimientos minimos del programa.
 
### Examen

Opción agregada: Reportes

 - **`Reporte completo`** — En el menú actual de la opción reportes solo funciona la opcion número 6, que muestra el total de interacciones, citas y tarea shechas por el usuario, en cuya descripción aparece el id de telegram para su reconocimineto.
 - El resto de las opciones solo mostraran un mensaje de que la opción elegida no se encuentra disponible actualmente, devolviendo al usuario al menu anterior para usar la unica opción usable.  
