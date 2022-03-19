# GIT

## Instalaciones necesarias

## Markdown

## USO DE CONSOLA

Moverme entre directorios

### Change directory
``` sh
cd
cd..
```

### Saber en el diretporio que estoy
```sh
pwd
```

### Crear un archivo
```sh
touch <nombre-archivo>
```

### Tirar multiples comandos en una linea
```sh
touch index.js index.htmol index.css

```

### crear directorios vacios
```sh
make directory
mkdir
```

### limpiar la consola
```sh
clear
```

### uso inicial

### configuraciuon inicial

```sh
git config --global user.name "Juan Zagardia"
git config --global user.email "zagardiajuan@gmail.com" #Email con el que se registraron en github
```

### ver y editar las configuraciones de git con el editor
```sh
git config --global.core.editor "code --wait"
git config --global.core.editor "nano"
```

### crear repositorio git
```sh
git init
```

### agrego archivos al stage area o index

```sh
git add <nombre-archivo>
git add .
git add *.js
```
### puedo hacer un commit(saco foto snapshoot)
```sh
git commit # me abre el editor por defecto que tengo configurado
git commit -m "mensaje descriptivo del commit"
```
### ver la historia, listar commit
```sh
git log #Version larga detallada
git log -- oneline # version corta resumida
```

### lo que tengo en el working directori contra lo que tengo en el REPO
```sh
git diff README.md
```
