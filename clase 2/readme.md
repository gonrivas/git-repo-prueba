# Clase 02 - GIT

## GIT LOG

```sh
git log --oneline
```

```sh
git log --since="2021-12-27"
```
```sh
git log --after="2021-12-27"
```
```sh
git log -2
```

## GIT IGNORE
** Sirve para ignorar los archivos que no quiero seguir, /carpeta, archivo.extension

## GIT KEEP
** tiene en cuenta la carpeta vacia para que la vea git se crea un archivo .gitkeep

## FORMA CORTA DE GIT ADD + GIT COMMIT juntos, 
** tengo que tener todos los archivos seguidos, si hay algun untracked no se hace commit de esos archivos y van a seguir untracked.
```sh
git commit -am "mensaje del commit"
```
## GIT REMOTE
lista origin
```sh
git remote -v 
```

agregar remoto
```sh
git remote add {alias} <url> 
```
agregar remoto
```sh
git remote rm origin  
```






