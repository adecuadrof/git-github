# GIT & GITHUB

## Configuracion

```
git config --global user.name "Nombre Apellido"

git config --global user.email "correo@correo.com"
```

## Comandos Basicos


```
git init

git status

git add archivo.tipo / git add . (sube todos los archivos)

git reset archivo.tipo

git commit -m "texto relevante de los cambios realizados"

git checkout -- . (Reconstruye el proyecto a la ultima version guardada)

git branch (Permite ver las ramas)

git log

git commit --amend -m "Nuevo texto del commit" (Permite modificar el texto del ultimo commit)

git reset --soft HEAD^n (te devuelve al commit anterior o n cantidad)

git reset --hard xxx (En las xxx podriamos poner el codigo del commit, tener presente que el hard realiza una eliminacion de archivos o cambios)


git reflog (Nos da un historico de todos los cambios)

```