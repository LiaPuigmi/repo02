# GIT

## Comandos:

Inicio git local: 

  _$ git init_

Crear archivo readme.md: 

  _$ cat >readme.md_

Añadir archivo al String Area: 

  _$ git add readme.md_ 
  
Añadir todos los archivos al String Area:

  _$ git add ._

Mirar el estado actual del repo: 

  _$ git status_ 

Hacer un snapshot(commit): 

  _$ git commit -m "mensaje"_

Crear el repo en gitHub y subirlo:

  _$ git remote add origin https://github.com/LiaPuigmi/repo01.git_
  _$ git branch -M main_
  _$ git push -u origin main_

Clonar repo del gitHub:
  
  _$ git clone https://github.com/LiaPuigmi/repo02.git_

Configurar git:

1. $ git config --global user.name "Name"
    $ git config user.name
2. $ git config --global user.email "email"
   2. $ git congig user.email


Otros comandos:
- $ git --version 
  - mirar versión de git
- $ pwd
  - imprime ruta directorio actual
- $ ls
  - listar contenido
- $ cd
  - cambiar de directorio
- $ cd ..
  - retroceder
- $ mkdir repo02
  - crear directorio