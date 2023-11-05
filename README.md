# Introduccion a GIT

## Comandos generales
* ```git init``` inicializa el proyecto para seguir el control de cambios
* ```git add <file>``` añade el fichero al control de cambios
* ```git rm <file>``` borra el fichero del control de cambios
* ```git mv <file> <newfile>``` renombra el fichero
* ```git commit -m "message"``` confirma los cambios
* ```git status``` muestra los ficheros bajo control de cambios
* ```git log``` muestra el historial de cambios
* ```git checkout <commit/brach>``` vuelve al entorno de un commit anterior
* ```git restore <file>``` deshace los cambios de un fichero (antes de hacer commit)
*
* ```git branch <branch>``` crea una nueva rama
* ```git switch <branch>``` cambia a la rama indicada (similar a checkout, pero checkout descarga datos remotos de la rama si no estan en local)
* ```git branch -d <branch>``` borra la rama indicada
* ```git merge <main|branch>``` fusiona el main o la rama indicada con la actual
* ```git stash``` guarda los cambios WIP en caso de querer saltar a otra rama
* ```git stash list|pop|drop``` muestra/recupera/borra los stash guardados
*
* ```git remote add origin <url>``` añade el repositorio remoto
* ```git push -u origin master``` sube los cambios al repositorio remoto
* ```git clone <url>``` clona el repositorio remoto
* ```git pull``` sube los cambios del repositorio remoto
* ```git fetch``` descarga los cambios del repositorio remoto
* ```git diff <commit> <commit>``` muestra las diferencias entre dos commits o braches
* ```git diff <commit> <commit> <file>``` muestra las diferencias entre dos commits o ramas de un fichero
* ```git reset [<file>]``` deshace los cambios desde el ultimo commit o de un fichero
* ```git reset --hard <commit>``` vuelve/avanza al commit indicado borrando el historial a partir de ese commit
* ```git reset --hard origin/master``` vuelve al ultimo commit del repositorio remoto borrando el historial de cambios
* ```git reflog``` muestra el historial de cambios incluso lo borrado con reset hard
* ```git tag <tag>``` da un nombre a un commit

## Configuracion inicial
* ```git config --global user.name "name"``` configura el nombre de usuario
* ```git config --global user.email "email"``` configura el email del usuario
* ```git config --global core.editor "editor"``` configura el editor de texto
* ```git config --global alias.<alias> "<command>"``` crea un alias para un comando
* ```git config --global --unset alias.<alias>``` borra un alias
* ```git config --global --list``` muestra la configuracion actual
* ```git config --global --edit``` edita la configuracion
* ```git config --global --add <config> <value>``` añade un valor a una configuracion

## alias utiles
* ```git config --global alias.st status``` crea un alias para el comando status
* ```git config --global alias.tree "log --graph --decorate --all --oneline"``` visualiza el log en forma de arbol
*

## Configuracion de un repositorio
* ```echo "# README.md" >> README.md```
* ```git init``` inicializa el repositorio
* ```git add README.md```
* ```git commit -m "first commit"```
* ```git branch -M main```
* ```git remote add origin https://github.com/<gitUser>/<gitRepository>.git``` añade el repositorio remoto
* ```git push -u origin main``` sube los cambios al repositorio remoto
*
*
*



## Intragracion con IntelliJ
* Cambiar terminal por defecto a la de git: File -> Settings -> Tools -> Terminal -> Shell path -> 
```C:\Program Files\Git\bin\bash" --login -i```  
