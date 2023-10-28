# Reconocedor de Caras (Visión Artificial)

## Descripción
El proyecto se centra en el reconocimiento facial haciendo uso del modelo pre-entrenado 'haarcascade_frontalface_default.xml' disponible en el repositorio GitHub de OpenCV. El modelo es capaz de identificar caras con precisión.

## Pasos del Proyecto

1. **Modelo y Repositorio**
    - El clasificador 'haarcascade_frontalface_default.xml' está disponible en el repositorio de OpenCV [aquí](https://github.com/kipr/opencv/tree/master/data/haarcascades).

2. **Detección y Recorte de Caras**
    - Se utiliza el modelo para detectar y recortar las caras identificadas.

3. **Manipulación de Imágenes**
    - Los canales B, G y R de cada imagen recortada se separan y se almacenan en archivos independientes.
    - Ecualización de los canales de las imágenes recortadas.

4. **Procesamiento Individual de Imágenes**
    - Se aplican procesos adicionales (Pasos 5 y 6) a cada imagen recortada.

## Cuaderno en Google Colab
Puedes acceder al cuaderno del proyecto en Google Colab [aquí](https://colab.research.google.com/drive/1YOcYCZc23pBhgmXZLv1XL8KTk80dBENl?usp=sharing). Las bibliotecas utilizadas son: cv2, matplotlib y numpy.

## Imagen
La imagen utilizada se llama "reconocedor de caras" y está alojada en Google Colab y en este proyecto.

## Librerías y Herramientas
- cv2
- matplotlib
- numpy
