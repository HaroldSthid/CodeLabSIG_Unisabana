# CodeLab: Programación para "Not Devs" 🚀

¡Bienvenidos a CodeLab! 🎉  
Este es un espacio creado para descubrir el mundo de la programación de una manera divertida y sin tecnicismos abrumadores. Aquí aprenderás a ver el código detrás de lo cotidiano, romper esquemas y entender que cada píxel es parte de un lenguaje que nos conecta con el mundo digital.

---

## ¿Qué encontrarás en este laboratorio? 💻

En este proyecto exploraremos **matrices RGB** y su procesamiento, conectando el código con resultados visuales y prácticos. Usaremos **Google Colab** como entorno de desarrollo en la nube (¡no necesitas cuenta en GitHub!) y **Excel** para visualizar y analizar nuestros datos de forma sencilla.

---

## Objetivos del Laboratorio 🎯

- **Experimentar:** Crear y manipular matrices RGB en Python.
- **Visualizar:** Conectar el código con resultados en Excel, haciendo tangible lo abstracto.
- **Analizar:** Interpretar y modificar los valores RGB para transformar imágenes.
- **Procesar:** Aplicar algoritmos básicos de procesamiento de imágenes (por ejemplo, detección de bordes).
- **Conceptualizar:** Reflexionar sobre cómo estos procesos se relacionan con el manejo de datos en sistemas más complejos.

---

## Estructura del Cuaderno (Jupyter/Google Colab) 📓

### Primera Sección: Introducción a las Matrices RGB

- **Concepto:** ¿Qué es una matriz RGB y cómo se relaciona con una imagen? 🖼️  
- **Actividad:** Generar una matriz RGB de forma aleatoria.  
- **Exportación:** Guardar la matriz en Excel usando `pandas` y `openpyxl`.

### Segunda Sección: Análisis y Modificación de la Matriz

- **Interpretación:** Analizar los valores RGB para entender qué representan.  
- **Modificación:** Cambiar algunos valores para alterar la paleta de colores.  
- **Visualización:** Reexportar la matriz modificada a Excel y comparar los cambios.

### Tercera Sección: Procesamiento de Imágenes

- **Introducción a Algoritmos:** Conocer conceptos básicos como la detección de bordes.  
- **Implementación:** Ejecutar un algoritmo simple sobre la matriz RGB.  
- **Discusión:** Analizar los resultados y debatir cómo podrían integrarse en una base de datos o en aplicaciones reales.

---

## Código de Python: Pixel_Programing 🖼️➡️📊

Este código te permite transformar una imagen en un archivo de Excel, donde cada celda se colorea según el valor RGB del píxel correspondiente. Se realiza en 3 pasos:

### Step 1: Mapeo del origen de datos 🚀
```python
from google.colab import drive
drive.mount('/content/drive')
