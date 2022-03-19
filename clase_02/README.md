# Vinculacion con nuestra cuebnta de Github

# Cuando quiero guardar una carpéta vacia
Necesito crear un arachivo de tipo ** .gitkeep **

# .gitignore sirve para descartar archivos no deseados


# log

## me lista una cantidad elegida de commit

```sh
git log --oneline -4
```

## lista commit por fecha

```sh
git log --since="2020-02-01"
git log --after="2020-02-01"
git log --before="2020-02-01"
git log --after="2020-02-01" --before="2020-05-21" --oneline
```

# Git BRANCH


## creo la rama
```sh
git branch dev
```

## listo la rama
```sh
git branch dev
```

## para cambiar la rama hago un switch
```sh
git switch <nombre de la rama>
```

## Eliminar una rama 
```sh
git branch -d <nombre de la rama>
```

## para forzar Eliminar una rama 
```sh
git branch -D <nombre de la rama>


# Git STASH
```sh
es una pila que almacena el working directory
permite almacenar el WD para seguir trabajando.
solo los stash que creo estan en la copia local del repo
```

## creo un stash

```sh
git stash
```

## ver los stash
```sh
git stash list
```

## Recuperar un stash
```sh
git stash pop

```