# Introducción a la visión por computador

## Índice
* [Resumen del curso](#resumen)
* [Presentaciones](#presentaciones)
* [Preguntas frecuentes](#preguntas-frecuentes)
  * [Instalar el entorno](#instalar-el-entorno)
    * [Instalación en Windows](#instalación-en-windows)
    * [Instalación en Linux](#instalación-en-linux)
  * [Hacer preguntas](#hacer-preguntas)
* [Enlaces de interés](#enlaces-de-interés)
* [Otros cursos](#otros-cursos)


# Resumen

Este es el repositorio principal del curso “Introducción a la visión por computador” que impartiré en Mayo de 2018. Todo el material necesario para el curso estará disponible aquí. El contenido del curso será el siguiente:

Sesión 1 - Fundamentos de la visión por computador.

- Introducción a la visión por computador

- Introducción al procesado de imagen

- Introducción a los descriptores

- Parte practica

Sesión 2 - Detección de caras. 

- Detección de caras. Algoritmos básicos

- Detección con descriptores

- Detección con redes neuronales

- Parte práctica

Sesión 3 - Reconocimiento de rostros.

- Face landmarks

- Algoritmos para reconocer rostros con Faces landmarks

- Parte práctica

Sesión 4 - Transformaciones y recap de todo lo que hemos hecho.

- Similarity Transformations

- Ideas para proyectos

- Parte práctica


## Presentaciones

| Sesión | Diapositivas | Parte práctica |
| ------ | ------ | ------ |
| Sesión 1 - Fundamentos de la visión por computador | [Diapositivas](https://docs.google.com/presentation/d/16Bms6BbmLxBtoIK5sWMdhKDQAWKViHsxcuLvfVVktIw/edit?usp=sharing) | [Notebook](https://github.com/carlescarmonacalpe/computer_vision_course/blob/master/Sesi%C3%B3n%201%20-%20Fundamentos%2C%20filtrado%20de%20imagen%20y%20descriptores.ipynb) |
| Sesión 2 - Detector de caras| [Diapositivas](https://docs.google.com/presentation/d/1bDeTgP6bBBwJbyNWjy5YMPIEwokpTxDvL3FRWRm8KjA/edit?usp=sharing) | [Notebook](https://github.com/carlescarmonacalpe/computer_vision_course/blob/master/Sesi%C3%B3n%202%20-%20Detecci%C3%B3n%20de%20caras.ipynb) |


## Preguntas frecuentes

### Instalar el entorno

#### Instalación en Windows
* Paso 1 - Descargar el repositorio y descomprimirlo en un directorio.

Simplemente hacer click en [este enlace](https://github.com/carlescarmonacalpe/computer_vision_course/archive/master.zip) para descargarlo y descomprimirlo.

* Paso 2 - Instalar Miniconda

Descargar el instalador en [este enlace](https://conda.io/miniconda.html). Estos instaladores contienen el __conda package manager__ y una versiona actual de __Python__ que seran necesarias para la parte practica.

* Paso 3 - Instalar las librerías de Python que requeriremos para el proyecto.

Una vez instalado el Miniconda ejecutaremos anaconda prompt, para ello la forma más sencilla es desde el menú inicio buscar __Anaconda Prompt__. Una vez abierta la consola tendremos que situarnos en el directorio donde hemos descomprimido los recursos para ello ejecutamos la instrucción __cd <path>__.
  
Por último para instalar las librerías de Python necesarias deberemos realizar dos acciones, la primera usar la instrucción

    pip install -r resources/requeriments.txt

Esta instrucción instala todas la librerías necesarias excepto una que debemos instalarla manualmente con la instrucción

    pip install resources/dlib-19.8.1-cp36-cp36m-win_amd64.whl

!Eso es todo, ya tenemos el entorno instalado!

#### Instalación en Linux.

* Paso 1 - Descargar el repositorio y descomprimirlo en un directorio.

Simplemente hacer click en [este enlace](https://github.com/carlescarmonacalpe/computer_vision_course/archive/master.zip) para descargarlo y descomprimirlo.

* Paso 2 - Instalar python y pip

Simplemente ejecutar la instrucción 

    sudo apt-get install python pip

* Paso 3 - Instalar las librerías de Python que requeriremos para el proyecto.

Para instalar las librerías de Python necesarias deberemos realizar dos acciones, la primera usar la instrucción

    pip install -r resources/requeriments.txt

Esta instrucción instala todas la librerías necesarias excepto una que debemos instalarla manualmente con la instrucción

    pip install resources/dlib-19.8.1-cp36-cp36m-win_amd64.whl

### Hacer preguntas

Para hacer preguntas o comentarios o proponer mejoras o informar de erratas para básicamente ayudar a futuros alumnos usaremos la sección issues de este repositorio. Para ello debemos:

* Hacer click en la pestaña __Issues__ o hacer click en [este enlace](https://github.com/carlescarmonacalpe/computer_vision_course/issues)
* Pulsar en __New issue__ o hacer click en este [este enlace](https://github.com/carlescarmonacalpe/computer_vision_course/issues/new)
* Introducir un título sencillo y realizar la pregunta, por último hacer click en __Submit new issue__

## Enlaces de interés

## Otros cursos

### En Altran

* __Introduction to Machine learning__ - Prassana Ravishankar & Carles Carmona - [Enlace](https://github.com/altran-machine-learning-course/course_11_2017)

### Por internet

* __Computer vision A-Z__ - Udemy - [Enlace](https://www.udemy.com/computer-vision-a-z/)
