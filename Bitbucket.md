# Como usar Bitbucket
---
A continuación como usar Bitbucket con los repositorios.
Como recomendación, la carpeta en donde se va a recibir el proyecto, recomiendo que tenga el mismo nombre que **nombre_proyecto**.

```bash
:~$ mkdir nombre_proyecto
:~$ cd nombre_proyecto
:~/nombre_proyecto$ git init
:~/nombre_proyecto$ git config --global user.name "UserName"
:~/nombre_proyecto$ git config --global user.email "email@email.com"
```

Como recomendación, la carpeta en donde se va a recibir el proyecto, recomiendo que tenga el mismo nombre que `nombre_proyecto`.

```bash
:~/nombre_proyecto$ git remote add origin https://Usuario@bitbucket.org/Usuario/nombre_proyecto.git
```

Con la siguiente linea se consigue traer el proyecto en Bitbucket al local.

```bash
:~/nombre_proyecto$ git pull https://Usuario@bitbucket.org/Usuario/nombre_proyecto.git
```

La siguiente linea agrega para ser subidos los archivos que estan modificados en el local, pero que no estan actualizados en el remoto.

```bash
:~/nombre_proyecto$ git add -A
:~/nombre_proyecto$ git commit -m "comentario de lo que se hizo"
```

El siguiente comando se usa **sólo la primera vez**.

```bash
:~/nombre_proyecto$ git push --set-upstream origin master
```

Con eso estamos Ok en la inicialización de git.
