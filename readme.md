# Clase 01 - GIT

## Archivo MarkDown (archivo.md)

https://www.markdownguide.org/cheat-sheet

## Saber si tengo git instalado
** Nota ** `= backtick => ALT 96
```sh
git --version
```
```js
console.log("Hola")
```
## Crear Repositorio

```sh
git init
```

## Listar archivos de consola
```sh
ls -la
```

## proyecto mas todo junto
```sh
git init && npm init -y && touch index.html && mkdir css && mkdir js
```
## Configurar
```sh
git config --local user.name "Gon"

git config user.email "gonzalomrivas@gmail.com"

git config --get-regexp user
```

## Agregar archivo a  Working Directory (WD) al index (Staged)

```sh
git add nombreArchivo.ext

git add .
```
#### asi agrega todo!

### Hacer commit
```sh
git commit -m "mensaje"
```

### Log del commit

```sh
git log

git log --oneline
```

### Para saber lo que pasa en el WD
```sh
git status
```





