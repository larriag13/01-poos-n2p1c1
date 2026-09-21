# 01-poos-n2p1c1
## Luis Arriagada
## markdown

### `git clone url_repo .`
Clona (descarga) un repositorio remoto completo y lo ubica directamente en el directorio actual (representado por el punto `.`), en lugar de crear una carpeta nueva.

### `git config --global user.name usuario_github`
Configura tu nombre de usuario de manera global en tu equipo. Este nombre será el que quede registrado como autor en el historial de todos los *commits* que realices.

### `git config --global user.email email_github`
Configura la dirección de correo electrónico a nivel global. Es fundamental que coincida con el correo que utilizas en plataformas como GitHub o GitLab para que se enlacen correctamente tus aportes.

### `git config --global --list`
Muestra en pantalla una lista con todas las configuraciones globales que tiene Git actualmente, permitiéndote verificar que tu nombre y correo se hayan guardado correctamente.

### `git add .`
Añade todos los archivos nuevos, modificados o eliminados del directorio actual al "área de preparación" (*staging area*). Esto indica qué archivos serán incluidos en la próxima confirmación.

### `git commit -m "comentario"`
Guarda permanentemente los cambios preparados en el historial del repositorio local. El parámetro `-m` permite escribir un mensaje descriptivo ("comentario") directamente desde la terminal para explicar de qué trata el cambio.