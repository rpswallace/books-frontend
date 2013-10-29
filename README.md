Book's App 
=========

Book es una aplicación HTML5 que nos permetiria:

  - obtener bases solidas de Javascript
  - pasar psds a html y css
  - trabajar con flujos reales
  - usar la metodologia agile para el proceso de desarrollo
  - optimización del proceso de desarrollo, calidad y producion (gruntjs)

Book va hacer una pequeña aplicacion que listara todos los libros de tecnologia que esten en papel. Una vez un usuario este logeado podra saber quien esta leyendo algun libro de interes o podra reservar un libro para leerlo.  

Version
----

1.0

Tech
-----------

Estas son las tecnologias a usar:

* [Gruntjs] - organizador de tareas 
* [Bower]   -manejador de dependencias en el frontend 
* [Sass] - pre compilador de css
* [jQuery] - duh 

[Tech doc link](https://drive.google.com/file/d/0B08r1h3RbqoEUjhZUzk5QWVscW8/edit?usp=sharing) 

Instalación del frontend
--------------

```sh
# clone repo
git clone [git-repo-url] 
# instalar dependencias del frontend
bower install  
# instalar dependencias de nodejs
npm install

# Correr app
grunt server
```

## Frontend - Sprint 1 ( viernes 01 de octubre ) 
- crear repositorio para el frontend en su cuenta de github
- instalar nodejs
- usar estructura de archivos igual a la de boilerplate
- crear archivo de configuracion de gruntjs que permita:
 - correr sass
 - livereload
 - preview server
- *instalar bower (si van a utilizar jquery)
 - incluir la ultima version de jquery
 - cambiar el nombre del directorio donde bower baja las depencias por "vendor"
- Instalar mongodb

## Frontend - Sprint 2 ( viernes 08 de Noviembre ) 
Antes de empezar con los demas objetivos deberan crear un tag en el repositorio llamado "sprint-1" ej:
```sh
git tag sprint-1 -m 'comment'
git push --tags #sube los cambios al branch remoto (github)	
```
Esto con el fin de poder devolverse al codigo con facilidad para hacer code reviews

En este segundo sprint vamos a investigar como crear browser tests contra el backend (restful). El framework a usar es libre. EJ: mocha, jasmine, qunit, etc.

Lo que se espera para este sprint es que investiguen acerca de los frameworks para testear javascript y una vez hayan elegido uno hagan un minimo de 5 ejemplos. Estos pueden ser contra el backend o cualquier codigo que ustedes quieran testear. Si el framework que escogen esta como componente de bower, deberan incluirlo como parte de las dependencias de desarrollo del projecto.

#### Tareas 
- crear tag.
- crear una tarea de grunt para correr los test.
- crear minimo 5 ejemplos con el framework escogido.







