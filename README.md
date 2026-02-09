# Image Contour Analysis with OpenCV

Proyecto académico de **Procesamiento de Imágenes** centrado en la detección y análisis de contornos utilizando OpenCV.

El trabajo explora distintas técnicas para identificar contornos en imágenes y analizar sus propiedades geométricas con fines descriptivos y comparativos.

---

## Objetivo
Detectar contornos en imágenes binarias y analizar sus características principales, tales como:
- Área
- Perímetro
- Jerarquía de contornos
- Propiedades geométricas básicas

---

## Tecnologías utilizadas
- Python
- OpenCV
- NumPy
- Matplotlib

---

## Contenido del repositorio
- Notebook con el desarrollo completo del análisis de contornos
- Detección de contornos mediante `cv2.findContours`
- Filtrado y clasificación de contornos por área
- Cálculo de propiedades geométricas
- Análisis de jerarquía de contornos

---

## Cómo ejecutar
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/image-contour-analysis-opencv.git
2. Instalar dependencias:
pip install opencv-python numpy matplotlib
3. Abrir y ejecutar el notebook:
jupyter notebook

 Descripción del análisis

A partir de imágenes binarias se detectan los contornos presentes y se analizan sus propiedades, permitiendo:

Discriminar objetos según su tamaño

Analizar la estructura de la imagen

Comprender la relación entre contornos externos e internos mediante jerarquía

Este tipo de análisis resulta fundamental en tareas de Visión por Computadora, especialmente en reconocimiento de formas y segmentación.

 Aplicaciones

Análisis y clasificación de formas geométricas

Segmentación de objetos

Preprocesamiento para sistemas de visión artificial

Reconocimiento de patrones en imágenes
