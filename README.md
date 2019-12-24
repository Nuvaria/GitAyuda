# Git 

## Configuracion

git config --global core.autocrlf false -> para quitar el cambio de tipo de fin de linea automático LF, CR o CRLF

## Ignorar

Hay que crear un archivo oculto llamado <code>.gitignore</code> en el que se van poniendo los documentos y carpetas a ignorar. Ver ej. mas abajo

Se puede hacer de 1000 formas, por ej. en la terminal con <code>$ touch .gitignore</code>

Ejemplo del contenido de <code>.gitignore</code>
log.txt
/directorioA
/directorioB
apps.js

## General


git init: inicializa el repositorio en el directorio

git status: indica que hay 


git add index.html -> añade archivo
        *.html -> añade todos los archivos de un tipo
        .  -> añade todo lo que haya en el dir
