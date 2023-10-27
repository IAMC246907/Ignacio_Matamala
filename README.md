### Reconecedor de caras (Visión Artificial)

 Se hace uso del modelo haarcascade_frontalface_default.xml, el cual está disponible en el repositorio GitHub de OpenCV y ya está entrenado, y reconoce caras con cierta exactitud.
Clasificador disponible en el repositorio de github de opencv: https://github.com/kipr/opencv/tree/master/data/haarcascades

En el paso #2 además se enmarcan todas las caras que se logra reconocer con el modelo, y se recorta cada una de ellas.

En el paso #3 se separan los canales B, G y R para cada una de las imágenes recortadas, cada canal se almacena en un archivo independiente.

En el paso #4 se ecualizan los canales de cada una de las imágenes recortadas.

Los pasos #5 y #6 se aplican para cada una de las imágenes recortadas.

Link de cuaderno alojado en Google Colab:
https://colab.research.google.com/drive/1YOcYCZc23pBhgmXZLv1XL8KTk80dBENl?usp=sharing
