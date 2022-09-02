# Primer dia con Git/Github

Comando para configurar el usuario y correo

Para crear version en Git
```bash
git --version
```
Para crear user mail
```bash
girt config --global user.email "elvia.madrid97@gmail.com"
```
Para crear user name
```bash
git config --global user.name "EluMadrid"
```

```bash
git config --list
```
Sirve para poder empezar a usar el control de version (git) en una carpeta.

Esto solo se hace una vez por carpeta
```bash
git init
```
Para ver el estado de nuestros cambios
```bash
git status
```
Para agregar los cambios a la memoria de la PC
```bash
git add .
```
Para agregar commit (Agrega registro de los cambios)
```bash
$ git commit -m "Mi primer commit"
```
Para ver el historial de versiones
Retorna in `id` para ver el detalle de los cambios ue se hicieron en ese commit 
```bash
$ git log
```
Para ver el detalle del id
```bash
$ git show  9c6cf93919b00d9a0afe15de3a4f6ac6f8e99ffa
```