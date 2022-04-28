RESUMEN ÓRDENES DE GIT

Hacer clonaciones:
git clone <direccion>

Crear una branca nueva:
git branch <nombre de rama>

Cambiar de rama:
git checkout <nombre de rama>

Informacion de la rama actual:
git status

Incluir los cambios del o de los archivos en el siguiente commit:
git add

Hacer commits:
git commit

Envia commits al repositorio remoto:
git push <nombre-remoto> <nombre-de-tu-rama>

Para recibir actualizaciones del repositorio remoto(es una combinación del git fetch y del git merge lo cual significa que cundo usemos el git pull recogeremos actualizaciones del repositorio remoto (git fetch) e inmediatamente aplicamos estos últimos cambios en local (git merge))
git pull <nombre-remoto>

Para fusionar la rama con su rama padre:
git merge

Para renombrar un repositorio remoto:
git remote rename <NOMBRE_REMOTO> <NUEVO_NOMBRE>

