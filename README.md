# Proyecto de Detección y Clasificación Facial con Django 
## Descripcion del Proyecto
En este proyecto, desarrollé un sistema integral para la detección y clasificación de rostros, utilizando una combinación de modelos preentrenados y modelos personalizados. El objetivo principal fue implementar un sistema que no solo detectara la presencia de un rostro en una imagen, sino que también pudiera identificar a la persona y analizar sus emociones.

Para la detección de rostros, utilicé modelos preentrenados como openface.nn4.small2.v1.t7 y res10_300x300_ssd_iter_140000.caffemodel, lo que permitió una detección precisa de los rostros en las imágenes. Posteriormente, entrené modelos personalizados para reconocer a las personas específicas en las imágenes y para identificar las emociones presentes en sus expresiones faciales.

La aplicación fue desarrollada con Django, un framework web de Python, creando una interfaz donde los usuarios pueden subir imágenes de celebridades. La aplicación procesa estas imágenes, identifica a la persona y determina su estado emocional, mostrando los resultados en tiempo real en la página web.

Este proyecto integra tanto modelos preentrenados como modelos entrenados por mí, demostrando la capacidad de combinar diferentes técnicas de machine learning y computer vision en un entorno de desarrollo web para crear aplicaciones avanzadas de reconocimiento facial y análisis emocional.
## Herramientas y Tecnologias
- Python
- Numpy : Manipulacion de Matriz 
- OpenCV : Manipulacion de imagenes
- Django : Desarrollo de Pagiana Web
- Scikit-Learn: Entrenamiento de modelos para reconocimiento facila y emocion
- dlib : Reconocimiento facila
- pickle : Guardar y Cargar modelos entrenados
- Modelos : uso de modelos para el la detecion de rostros
## Funcionalidades
- Detección precisa de rostros en imágenes utilizando modelos preentrenados.
- Identificación de personas específicas en las imágenes mediante modelos entrenados.
- Análisis y detección de emociones en las expresiones faciales.
- Interfaz web intuitiva para cargar imágenes y visualizar los resultados.
### Jupyter
Archivos en jupyter notebook en los cuales realice pruebas para el funcionamiento de esta herramientas y en los cuales entre los modelos para el reconocimiento de rostro y emociones 
