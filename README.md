## Django in virtual enviroment
### Cómo instalar Django con el entorno virtual de conda y no morir en el intento

#### Instalar Anaconda en linux
1. [Anaconda download.](https://www.anaconda.com/download/)
2. $ chmod 755 "filename" *// sin comillas poner nombre de archivo.*
3. $ ./"filename" *// sin comillas poner nombre de archivo.*

#### Crear entorno virtual con conda
1. ir a la carpeta de proyecto
2. $ conda create -n myDjangoEnv django

#### Activar entorno
- $ source activate myDjangoEnv

#### Desactivar entorno
- $ source deactivate

#### Iniciar un proyecto en Django
Cuando tengas tu entorno virtual iniciado, ejecuta el comando:
- $ django-admin startproject primer_proyecto
- $ python manage.py runserver

#### Añadir github al nuevo proyecto
- $ git init
- $ $ git remote add origin https://github.com/my_usuario/mi_proyecto.git

#### Enlades a documentación
- [Python](https://docs.python.org/3/index.html)
- [Conda](https://conda.io/docs/)
- [Django](https://docs.djangoproject.com/en/2.0/)
