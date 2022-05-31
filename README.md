<img src='src/img/Titular.png'>

# Tutorial Entornos Virtuales Python

## Rquisitios:
* Un editor de texto
* Conocimiento básico de Consola/Terminal

## Introducción:

A la hora de trabajar paquetes para python, se pueden crear entornos donde requeriras tener versiones especificas para evitar temas de conflictos. Ya sea que siempre trabajes con 1 librería, no esta de más tener su ambiente virtual.

<img src='src/img/Proyectos.png'>

Como puedes ver en la imagen, llegaremos a tener diferentes proyectos donde en algunos, estaremos utilizando librerías diferentes o hasta versions diferentes de Python. Tal vez puedas instalar todas en tu computadora e importarlas cuando se requieran pero ademas de las buenas practicas, a la hora de exportar tu proyecto, necesitaras enlistar las librerias utilizadas en un archivo llamado Requeriments que le ayuda a los demas a instalar las librerias utilizadas justamente en otro ambiente virtual.



## Paso 1. Verificar la version de python

Dependiendo la version de python que tienes, es el ambiente virtual que podras trabajar. Podras encontrar tuturiales que utilizan la libreria virtualvenv y que se debe de instalar pero aquí estaremos utilizando el módulo venv que ya viene en las ultimas versiones de python.

Si nunca hemos trabajado con archivos .py y solo notebooks, ahí nos dice que version esta trabajando nuestro kernel.

1. Crearemos un archivo .ipybn en nuestro editor de texto que es el formato para los notebooks.
2. Dentro de una celda de código, ejecutaremos un `print("Hola Mundo")` y nos preguntara con que kernel deseamos trabajar. 

<img src='src/img/version.png'>

Si no llegara a preguntarnos, este se encuentra en la esquina superior derecha.

3. Verificamos que esta version sea la que tenemos en nuestra consola

Entraremos a nuestra consola y dependiendo el sistemas operativo, utilizaremos el comando

**Windows**: `python --version` o `py --version` 

**Mac/Linux** `python3 --version`