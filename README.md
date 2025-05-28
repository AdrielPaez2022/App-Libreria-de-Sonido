🎧 App - Librería de Sonido

Librería de Sonido es una aplicación de escritorio desarrollada en Python que permite a los usuarios organizar, etiquetar, buscar y reproducir muestras de audio (samples) de forma rápida y eficiente. Está diseñada especialmente para productores musicales, DJs, diseñadores de sonido y cualquier persona que trabaje con archivos de audio.



🧠 Objetivo General:

Desarrollar una aplicación de escritorio intuitiva y eficiente para organizar, etiquetar, visualizar y reproducir muestras de audio, orientada a productores, diseñadores sonoros y músicos.

____________________________________________________________________________________________________________________________________________________________________________________________

🎯 Objetivos Específicos:

* Permitir el almacenamiento estructurado de samples en una base de datos no relacional (MongoDB).
* Implementar funcionalidades CRUD (crear, leer, actualizar y eliminar samples).
* Integrar un sistema de reproducción de audio con visualización de forma de onda.
* Garantizar una interfaz gráfica amigable usando Python.
* Asegurar operaciones seguras con archivos multimedia.

_____________________________________________________________________________________________________________________________________________________________________________________________

❗ Problema: 
Los productores y diseñadores de sonido suelen tener miles de muestras de audio dispersas, mal organizadas o duplicadas, lo que dificulta su localización, clasificación y uso eficiente. Las herramientas disponibles suelen ser complejas, caras o no adaptadas a flujos de trabajo personalizados.


_____________________________________________________________________________________________________________________________________________________________________________________________

💡 Solución: 

* Una aplicación de escritorio liviana, hecha en Python, que permite:
* Importar y etiquetar archivos de audio fácilmente.
* Guardarlos y gestionarlos en MongoDB bajo una colección personalizada.
* Reproducir los audios con control de reproducción.
* Visualizar la forma de onda para una selección más precisa.
* Buscar de forma inteligente por nombre, etiquetas o metadatos.

_____________________________________________________________________________________________________________________________________________________________________________________________

🛠️ Tecnologías Utilizadas: 

* Python (Backend + GUI)
* MongoDB (Base de datos NoSQL)
* Pygame (Reproducción de audio)
* Tkinter o similar (Interfaz gráfica)
* Pillow, NumPy, Matplotlib (Procesamiento de imágenes y visualización)

_____________________________________________________________________________________________________________________________________________________________________________________________

🗂️ Arquitectura de la Aplicación
1. principal.py
  * Manejo principal de la app
  * Funciones para CRUD y conexión con MongoDB

2. archivo_operaciones.py
  * Selección, reproducción y eliminación segura de archivos

3. CRUDOperations.py
  *  Funciones centrales para crear, actualizar, buscar y eliminar samples con validación

4. forma de onda.py
  * Carga y dibujo de la forma de onda sonora
____________________________________________________________________________________________________________________________________________________________________________________________

🧪 Requisitos para Ejecutar

_ Python instalado desde: https://www.python.org/downloads/windows/
_ MongoDB Compass desde: https://www.mongodb.com/es/products/tools/compass
_ Dependencias Python: pygame, pymongo, pillow, numpy, matplotlib
