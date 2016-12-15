# How start a Python Django repository

Creamos nuestro archivos:

* AUTHORS.md
* LICENSE.md
* README.md
* .gitignore

Dentro del archivo `.gitignore` escribimos:

```
    # Directory patterns
    __pycache__

    # File patterns
    db.sqlite3
```

Creamos la carpeta `www`:

```
    $ mkdir www
```

Crear un entorno virtual: 

```
    $ conda create -n :virtual_env_name:
```

Donde `:virtual_env_name:` es el nombre del entoro virtual que vamos a crear.

Activamos el entorno virtual

```
    $ source activate 'Nombre del entorno virtual'
```

Creamos un archivo de requerimientos del entorno virtual, una lista de los archivos que se han instalado

```
    $ conda list -e > requeremenets.conda
```

Installamos django

```
    $ pip install django
```

Creamos un archivo requerimientos de pip

```
    $ pip freeze > requerements.pip
```

Entramos a la carpeta `www`:

```
    cd www
```

Creamos un projecto de Django:

```
    django-admin startproject :project_name:
```

Donde `:project_name:` es el nombre de nuestor proyecto.
