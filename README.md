# Filtros de Convolución en Imagen
Este proyecto permite aplicar filtros de convolución sobre la camara o sobre un archivo de imagen. Se usa la técnica de convolución para modificar la imagen en el navegador sin necesidad de enviar datos a un servidor.

## 🚀 Características

- Aplicación de filtros de convolución en imágenes en vivo desde la cámara web.

📺 **Video Explicativo:**  
<p align="center">
  <a href="https://www.youtube.com/watch?v=AwTH_0yW9_I">
    <img src="https://img.youtube.com/vi/AwTH_0yW9_I/0.jpg" width="200">
  </a>
</p>

📖 **Procesamiento digital de imágenes por núcleo, kernel, matriz de convolución o máscara:**  
- [Artículo en Wikipedia sobre Núcleos en Procesamiento Digital de Imágenes](https://es.wikipedia.org/wiki/N%C3%BAcleo_(procesamiento_digital_de_im%C3%A1genes))

## 🛠 Technologies Used

- **JavaScript** para la manipulación de imágenes y la aplicación de filtros de convolución.
- **HTML y CSS** con **Bootstrap 4.6** para una interfaz responsiva y fácil de usar.
- **Canvas API** para capturar y procesar la imagen en tiempo real.

## 🔧 Funciones Principales en `vision.js`

El archivo `vision.js` contiene las siguientes funciones para el procesamiento de imágenes:

- `convolucionar(canvasFuente, canvasDestino, kernel, divisor)`: Aplica un filtro de convolución a la imagen.
- `convolucionarSobel(canvasFuente, canvasDestino, colorizar, blurFirst, lowThreshold)`: Aplica el filtro de detección de bordes de Sobel.
- `changeHue(rgb, degree)`: Modifica el matiz de un color RGB.
- `rgbToHSL(rgb)`: Convierte un color de formato RGB a HSL.
- `hslToRGB(hsl)`: Convierte un color de formato HSL a RGB.
- `normalize_rgb_value(color, m)`: Normaliza los valores RGB.
