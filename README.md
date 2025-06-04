🎧 Librería de Sonido
Aplicación para organización y reproducción de samples

Descripción general:
Librería de Sonido es una aplicación de escritorio desarrollada en Python con una base de datos MongoDB local, pensada para facilitar el trabajo de productores musicales, DJs, diseñadores de sonido y cualquier profesional que trabaje con muestras de audio (samples).

🧠 Su objetivo principal es ofrecer una gestión rápida, visual y eficiente de archivos de sonido, permitiendo su organización, búsqueda, reproducción y visualización de forma intuitiva.

🛠️ Tecnologías utilizadas:  

-Python (interfaz de escritorio + backend)  

-MongoDB (almacenamiento local de datos)  

-Pygame (Reproducción de audio)  

-Tkinter o similar (Interfaz gráfica)  

-Pillow, NumPy, Matplotlib (Procesamiento de imágenes y visualización)  



  🎯 Funcionalidades principales:  
      🎵 Organizar y etiquetar samples   
       🖼️ Asociar imágenes a sonidos   
       🔊 Reproducir audio desde la app   
       📊 Visualizar formas de onda   
       📂 Guardar todo en una base MongoDB local   ____________________________________________________________________________________________________________________________________________________________________________________________  
     
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
____________________________________________________________________________________________________________________________________________________________________________________________

🧪 Requisitos previos para Ejecutar:  

🐍 1. Instalación de Python  

-Descargá Python desde 👉 python.org/downloads/windows  

-Activá la opción ✅ “Add Python to PATH” al instalar.  
_____________________________________________________________________________________________________________________________________________________________________________________________


🍃.2 Instalación de MongoDB Compass  

-Instalá MongoDB Compass desde 👉 mongodb.com/tools/compass  

-En el disco principal (C:), creá la carpeta:  

 📁 C:\data\db  
 
-Luego, en MongoDB Compass:  

  ➕ Clic en "Create Database"  
  
  📌 Database Name: SOUNDFRESH  
  
  📌 Collection Name: samples  
_____________________________________________________________________________________________________________________________________________________________________________________________
  

📦 3. Instalación de Dependencias  

 -Abrí CMD y ejecutá uno por uno:       
      📥 pip install pygame==2.5.0   
      📥 pip install pymongo   
      📥 pip install pillow   
      📥 pip install numpy   
      📥 pip install matplotlib   
      💡 Recomendación: crear un entorno virtual con python -m venv venv   
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
_____________________________________________________________________________________________________________________________________________________________________________________________
🧠 Funcionalidades del Sistema:   
    ✔️ Carga de samples con imágenes y metadatos   
    🔎 Búsqueda avanzada (por nombre, tags, categoría)   
    🎶 Reproducción directa del audio   
    📈 Visualización gráfica de la onda sonora   
    🗃️ Gestión CRUD (crear, consultar, modificar, eliminar)   
_____________________________________________________________________________________________________________________________________________________________________________________________
🔁 Flujo de Uso Básico:   
     1. 🚀 Ejecutar main.py   
     2. 📂 Seleccionar audio e imagen   
     3. 📝 Ingresar metadatos   
     4. 💾 Guardar   
     5. 🔍 Buscar samples   
     6. ▶️ Reproducir   
     7. 📉 Visualizar forma de onda   
     8. 🛠️ Editar o eliminar si se desea   
    
