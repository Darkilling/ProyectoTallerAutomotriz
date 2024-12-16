# ProyectoTallerAutomotriz
Es una aplicacion web creada con django y nodejs para implementar un sistema de gestion automotriz


# ProyectoTallerAutomotriz
Es una aplicacion web creada con django y nodejs para implementar un sistema de gestion automotriz


para hacer funcionar esto se debe iinstalar varias cosas en cada carpeta

en la carpeta node debes instalar 
npm install nodejs
npm install express firebase-admin
npm install punycode



y en la carpeta django instalar un entorno virtual
si aun no tienes la virtualizacion pon esto

pip install virtualenv

si ya lo tenias no es necesario instalarlo y prosigue con esto 

Python -m venv entorno    entorno es como yo la llame puedes ponerle el nombre que quieras

luego ingresamos al entorno creado 
cd entorno 
cd scripts
.\Activate.ps1

y al estar dentro del entorno instalalmos django
 pip install django

 luego fuera del entorno creamos el proyecto

 django-admin startproject MiProyectoDjango .

miproyectodjango lo puedes cambiar por el nobre que desees 

luego se crea la app 
python manage.py startapp nombre_app
 
 y estariamos listos parausarlo