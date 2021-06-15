## Descripción del proyecto

En este proyecto, aplicará las habilidades que ha adquirido en este curso para poner en funcionamiento una API de microservicio de aprendizaje automático.

Se le proporciona un modelo `sklearn` previamente capacitado que ha sido capacitado para predecir los precios de la vivienda en Boston de acuerdo con varias características, como el promedio de habitaciones en una casa y datos sobre el acceso a la carretera, la proporción de maestro por alumno, etc. . Puede leer más sobre los datos, que inicialmente se tomaron de Kaggle, en [el sitio de origen de datos](https://www.kaggle.com/c/boston-housing). Este proyecto prueba su capacidad para poner en funcionamiento una aplicación de matraz de Python, en un archivo proporcionado, `app.py`, que ofrece predicciones (inferencias) sobre los precios de la vivienda a través de llamadas a API. Este proyecto podría extenderse a cualquier modelo de aprendizaje automático previamente entrenado, como los de reconocimiento de imágenes y etiquetado de datos.

### Tareas del proyecto

El objetivo de su proyecto es poner en funcionamiento este microservicio de aprendizaje automático en funcionamiento mediante [kubernetes] (https://kubernetes.io/), que es un sistema de código abierto para automatizar la gestión de aplicaciones en contenedores. En este proyecto podrás:
* Pruebe el código de su proyecto usando linting
* Complete un Dockerfile para contener esta aplicación
* Implemente su aplicación en contenedores usando Docker y haga una predicción
* Mejorar las declaraciones de registro en el código fuente de esta aplicación
* Configurar Kubernetes y crear un clúster de Kubernetes
* Implementar un contenedor usando Kubernetes y hacer una predicción.
* Cargue un repositorio completo de Github con CircleCI para indicar que su código ha sido probado

Puede encontrar una [rúbrica del proyecto, aquí](https://review.udacity.com/#!/rubrics/2576/view).

** La implementación final del proyecto mostrará sus habilidades para poner en funcionamiento microservicios de producción. **

---

## Configurar el entorno

* Crea un virtualenv y actívalo
* Ejecute `make install` para instalar las dependencias necesarias

### Ejecutando `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

### Pasos de Kubernetes

* Instalar y configurar Docker localmente
* Instalar y configurar Kubernetes localmente
* Crear aplicación Flask en contenedor
* Ejecutar a través de kubectl