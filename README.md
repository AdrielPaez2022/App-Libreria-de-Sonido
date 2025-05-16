# App-Libreria-de-Sonido
App de escritorio para organizar, etiquetar y reproducir samples de audio con interfaz gráfica en Python y MongoDB.

1_Instalar Python
  Descargar e instalar python: https://www.python.org/downloads/windows/

2_Instalar MongoDB
  *Descargá e instalá MongoDB: https://www.mongodb.com/es/products/tools/compass
  *Luego, en el disco principal (por lo general C: en Windows), creá una carpeta llamada:"C:\data\db"

  Crear base de datos y colección en MongoDB Compass
    _Abrí MongoDB Compass
    _Crear la base de datos y colección
      * En la barra lateral izquierda, hacé clic en "Create Database"
      *  En el modal que aparece:
          Database Name: "SOUNDFRESH"
          Collection Name: "samples"
    

3_Instalacion de Dependencias 
  Abrir el CMD e ingresar los siguentes comnados:
    * pip install pygame==2.5.0
    * pip install pymongo
    * pip install pillow
    * pip install numpy
    * pip install matplotlib
