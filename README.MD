# PROYECTO DJANGO



# Instalación
Instalar Django en el directorio deseado con pipenv, si no lo tienes instalado a continuación te doy un ejemplo:
```bash
$ pip install pipenv
```
Posteriormente:
```bash
    pipenv install django==2.2.6
```
En la ruta principal de nuestro proyecto creamos nuestro proyecto Django de la siguiente manera (en mi caso con el nombre "webpersonal"):
```bash
    pipenv run django-admin startproject webpersonal
```
## Configurando el archivo Pipfile
Pega esto en el archivo Pipfile para configurar los comandos en la terminal y sea de una manera mas fácil manejar las migraciones, arrancar el servidor etc. 
```bash
[scripts]
server   = "python manage.py runserver"
migrate  = "python manage.py migrate"
startapp = "python manage.py startapp"
makemigrations ="python manage.py makemigrations"
```

# COMANDOS DE UTILIDAD
```bash
    pipenv run server -> arrancar servidor
    pipenv run migrate -> migraciones
    pipenv run startapp <nameAPP> ->  crear una App

```
