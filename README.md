# Introduccion a GIT

## Comandos
* ```git init``` inicializa el proyecto para seguir el control de cambios
* ```git status``` muestra los ficheros bajo control de cambios
* ```git restore <file>``` deshace los cambios de un fichero
* ```git add <file>``` añade el fichero al control de cambios
* ```git commit -m "message"``` confirma los cambios
* ```git log``` muestra el historial de cambios
* ```git checkout <commit>``` vuelve a un commit anterior
* ```git checkout master``` vuelve al ultimo commit
* ```git branch <branch>``` crea una nueva rama
* ```git checkout <branch>``` cambia a la rama indicada
* ```git merge <branch>``` fusiona la rama indicada con la actual
* ```git branch -d <branch>``` borra la rama indicada
* ```git remote add origin <url>``` añade el repositorio remoto
* ```git push -u origin master``` sube los cambios al repositorio remoto
* ```git clone <url>``` clona el repositorio remoto
* ```git pull``` descarga los cambios del repositorio remoto
* ```git fetch``` descarga los cambios del repositorio remoto
* ```git diff <commit> <commit>``` muestra las diferencias entre dos commits
* ```git diff <branch> <branch>``` muestra las diferencias entre dos ramas
* ```git diff <commit> <commit> <file>``` muestra las diferencias entre dos commits de un fichero
* ```git diff <branch> <branch> <file>``` muestra las diferencias entre dos ramas de un fichero
* ```git reset --hard <commit>``` vuelve al commit indicado borrando los cambios
* ```git reset --hard origin/master``` vuelve al ultimo commit del repositorio remoto borrando los cambios

## Configuracion inicial
* ```git config --global user.name "name"``` configura el nombre de usuario
* ```git config --global user.email "email"``` configura el email del usuario
* ```git config --global core.editor "editor"``` configura el editor de texto
* ```git config --global alias.<alias> "<command>"``` crea un alias para un comando
* ```git config --global --unset alias.<alias>``` borra un alias
* ```git config --global --list``` muestra la configuracion actual
* ```git config --global --edit``` edita la configuracion
* ```git config --global --add <config> <value>``` añade un valor a una configuracion


## Configuracion de un repositorio
* ```git init``` inicializa el repositorio
* ```git remote add origin <url>``` añade el repositorio remoto
* ```git push -u origin master``` sube los cambios al repositorio remoto
*
*
*
*



## Intragracion con IntelliJ
* Cambiar terminal por defecto a la de git: File -> Settings -> Tools -> Terminal -> Shell path -> 
```C:\Program Files\Git\bin\bash" --login -i```  
