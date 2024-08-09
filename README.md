# subir_git
Cómo hacer un primer commit en GitHub

1)Inicializar un repositorio de Git:
git init

2)Agregar archivos al área de preparación (staging area):
git add .

3)Hacer el primer commit:
git commit -m "Primer commit"

4)Agregar el repositorio remoto (si aún no se ha hecho):
git remote add origin https://github.com/usuario/nombre-del-repo.git

5)Enviar los cambios al repositorio remoto en GitHub:
git push -u origin master

/*-----------------------------------------------------------------------------------------------------------------------------*/

Ejemplo:

Supongamos que has creado un nuevo proyecto y tienes un archivo README.md. Aquí están los comandos completos:


mkdir mi-proyecto

cd mi-proyecto

git init

echo "# Mi Proyecto" > README.md

git add README.md

git commit -m "Primer commit"

git remote add origin https://github.com/usuario/mi-proyecto.git

git push -u origin master


Con esto, has creado un primer commit en tu nuevo repositorio en GitHub, estableciendo la base para todo el desarrollo futuro.

/*--------------------------------------------------------*/Actualizar proyecto--------------------------------------------------------*/

git status               # Verifica el estado de los archivos en tu repositorio local

git add .                # Añade todos los archivos cambiados al área de preparación

git commit -m "Tu mensaje de commit"   # Crea un commit con los cambios añadidos

git push origin main     # Envía los cambios al repositorio en GitHub


