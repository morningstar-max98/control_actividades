git status: muestra el estado de los archivos y qué cambios existen.

git add README.md: prepara README.md para el commit.

git commit -m "Actualiza documentación": guarda los cambios en el historial local de Git.

git push: envía los commits locales al repositorio remoto en GitHub

2. Identifica qué falta
Caso A
Modificar archivo
↓
git add .
↓
¿?
↓
git push

Falta:

git commit -m "Describe el cambio"

Función: guarda los cambios preparados en el historial de Git para después poder enviarlos a GitHub con git push.

Caso B
Repositorio GitHub
↓
¿?
↓
Repositorio local

La operación es:

git pull

Función: descarga los cambios del repositorio de GitHub y actualiza el repositorio local.

Caso C 
Repositorio remoto actualizado
↓
¿?
↓
Repositorio local actualizado

falta el git pull descarga los cambios del repositorio remoto y actualiza el repositorio local.


