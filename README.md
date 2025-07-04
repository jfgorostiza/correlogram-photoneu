Repositorio para TFM en masterIA 2024/2025.
Implementación de un algoritmo de color-correlograma para la identificación unívoca de ratones de laboratorio.
El repositorio incluyde:
- dataset, directorio con imágenes cenitales de 3 ratones de laboratorio. dataset Trimouse-161. Las imágenes están etiquetadas con 12 puntos de pose en cada individuo ratón.
- videos_ratones,
- src:
    |- mouseDetection.old.py, programa para la detección de ratones como formas oscuras en un fondo claro. Operaciones morfológicas de toma de imágenes, blur, threshold, y localización de contornos.
    |- test_inRange.py, programa para calibrar el espacio de color HSB de una imagen
    |- testCameraOpenCV.py, programa de test para visualizar datos de la camara mediante la API de OPEN-CV
    |- camHandler.py, se implementan clases para Tracker, filtro de Kahlman, manejo de la cámara, y diversas funcionalidades de imaagen artificial.
    |- testCamHandler.py, programa de test de la clase CamHandler.
     
