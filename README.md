# MindTech

# KEY VIEW
Este proyecto implementa un asistente de voz interactivo que utiliza técnicas de visión por computadora y reconocimiento de voz para realizar acciones como detectar objetos en tiempo real y reconocer texto mediante OCR (Reconocimiento Óptico de Caracteres).


## Tabla de Contenidos
#### Descripción del Proyecto
#### Arquitectura
#### Proceso de Desarrollo
#### Funcionalidades
#### Estado del Proyecto
#### Agradecimientos
#### Arquitectura
#### El proyecto utiliza las siguientes tecnologías y componentes principales:

### Python: 
Lenguaje de programación principal.
### OpenCV: 
Biblioteca para procesamiento de imágenes y video.
### PyTesseract:
Wrapper de Python para Tesseract OCR.
### Google Text-to-Speech (gTTS): 
Para reproducir texto como voz.
### SpeechRecognition:
Para capturar y reconocer comandos de voz.
### YOLOv5:
Modelo de detección de objetos.
### Google Maps API:
Para obtener ubicación y direcciones.

Proceso de Desarrollo
Fuente del Dataset
No se utiliza un dataset en este proyecto, ya que el modelo YOLOv5 está preentrenado para detectar una amplia variedad de objetos.

Limpieza de Datos
No aplica. El procesamiento de imágenes y OCR se realiza en tiempo real sobre las imágenes capturadas por la cámara.

Manejo de Excepciones / Control de Errores
Se implementa manejo de excepciones para capturar errores de reconocimiento de voz, acceso a la cámara y errores de conexión con la API de Google Maps.

Modelo de Machine Learning Utilizado
Se utiliza YOLOv5, un modelo de detección de objetos basado en redes neuronales convolucionales.

Estadísticas
No se aplican estadísticas en este proyecto. Las métricas relevantes son la confianza de detección de objetos y la precisión de OCR.

Métricas de Evaluación del Modelo
Las métricas de evaluación incluyen la precisión de detección de objetos (IoU) y la precisión de reconocimiento de texto mediante OCR.

Funcionalidades
El asistente de voz inteligente ofrece las siguientes funcionalidades:

1. Detección de Objetos
Descripción: Utiliza YOLOv5 para detectar y clasificar objetos en tiempo real desde la cámara del dispositivo.
Implementación: OpenCV para la captura de video y procesamiento de imágenes, YOLOv5 para la inferencia de detección de objetos.
2. Reconocimiento de Texto
Descripción: Utiliza Tesseract OCR para reconocer texto en imágenes capturadas desde la cámara.
Implementación: OpenCV para el procesamiento de imágenes y PyTesseract para el reconocimiento óptico de caracteres.
3. Obtención de Ubicación Actual
Descripción: Utiliza la API de Google Maps para obtener la ubicación actual del usuario mediante geocodificación inversa.
Implementación: Google Maps API para la consulta de coordenadas y dirección basada en la ubicación geográfica.
Estado del Proyecto
El proyecto está actualmente en desarrollo activo. Las funcionalidades principales de detección de objetos y reconocimiento de texto están implementadas y funcionales. Se sigue trabajando en mejoras de interfaz de usuario y manejo de excepciones.

Agradecimientos
Agradecimientos especiales a OpenCV, PyTesseract, Ultralytics (YOLOv5) y Google Cloud Platform por proporcionar herramientas y APIs esenciales para este proyecto.

