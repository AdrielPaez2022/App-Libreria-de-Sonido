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

4_Estructura de Archivos y Funcionalidades

main.py

init: Conexión con MongoDB y configuración de rutas para archivos
create_sample: Valida y guarda nuevos samples con archivos asociados
update_sample: Actualiza samples existentes con manejo seguro de archivos
delete_sample: Elimina samples con confirmación y limpieza de archivos
search_samples: Búsqueda insensible a mayúsculas en múltiples campos
get_sample: Obtiene sample por ID con validación de existencia
get_all_samples: Recupera todos los samples (con filtro opcional) ordenados

file_operations.py

initialize_audio: Configura sistema de audio Pygame con parámetros óptimos
select_audio_file: Diálogo para selección de archivos (WAV/MP3/OGG) con validación
select_image_file: Diálogo para selección de imágenes (PNG/JPG/GIF)
play_audio: Reproducción con manejo de errores y detención de reproducciones previas
stop_audio: Detiene reproducción y libera recursos
force_delete_file: Eliminación de archivos bloqueados con reintentos
safe_file_operations: Operaciones seguras de copiado/movimiento

CRUDOperations.py

create_sample: Valida datos obligatorios y guarda con nombres únicos de archivos
update_sample: Manejo seguro de reemplazo de archivos y actualización de metadatos
delete_sample: Eliminación con confirmación y manejo de errores
search_samples: Búsqueda con regex insensible a mayúsculas/minúsculas

waveform.py

load_audio: Carga archivos y extrae datos de onda con cálculo de duración
draw_waveform: Visualización de onda sonora con amplitudes normalizadas en canvas
