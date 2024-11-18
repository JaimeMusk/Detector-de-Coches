# Detector de Marcas y Modelos de Coches 🚗✨

Este proyecto utiliza técnicas de Deep Learning para detectar marcas y modelos de coches a partir de imágenes o videos. La aplicación ha sido diseñada como parte de un trabajo final, siguiendo un pipeline completo de Machine Learning, desde la definición del problema hasta el despliegue de la aplicación.

---

## 📋 Descripción del Proyecto

El objetivo principal es desarrollar un modelo capaz de identificar coches en imágenes y clasificarlos según su marca y modelo. La solución incluye:

1. **Definición del problema**: Detectar y clasificar marcas y modelos de coches deportivos a partir de imágenes y videos.
2. **Selección del modelo**: Uso de YOLOv5 (o similar) para detección de objetos y clasificación.
3. **Preparación del dataset**:
   - Uso de datasets preexistentes, como el Stanford Cars Dataset o datasets de Kaggle.
   - Preprocesamiento de imágenes y etiquetas.
4. **Entrenamiento del modelo**:
   - Finetuning de un modelo preentrenado para ajustarlo a las marcas y modelos seleccionados.
5. **Despliegue de la aplicación**:
   - Desarrollo de una interfaz interactiva con **Gradio** para cargar imágenes/videos y mostrar resultados.
   - Contenedor Docker para hacer la app portable y fácil de ejecutar.

---

## 🧰 Herramientas y Tecnologías

- **Frameworks y Librerías**:
  - YOLOv5 para detección de objetos.
  - Gradio para la interfaz de usuario.
  - Docker para el despliegue.
- **Lenguajes**:
  - Python.
- **Dataset**:
  - Imágenes etiquetadas de coches deportivos con marca y modelo.



## 🛠️ Pasos del Pipeline

1. **Definición del Problema**:
   - Detectar marcas y modelos de coches en imágenes/videos.
   - Clasificar correctamente entre marcas como Ferrari, Porsche, y Lamborghini, entre otras.

2. **Selección del Modelo**:
   - Modelo base: YOLOv5 (pequeño, ligero y eficiente).
   - Finetuning: Entrenamiento adicional con un dataset específico.

3. **Dataset**:
   - Uso de Stanford Cars Dataset o datasets similares.
   - Preprocesamiento de datos: Redimensionar imágenes, etiquetado, y división en entrenamiento/validación.

4. **Entrenamiento del Modelo**:
   - Entrenamiento con imágenes etiquetadas.
   - Validación del modelo en datos nuevos.

5. **Despliegue**:
   - Interfaz creada con **Gradio** para cargar imágenes o videos.
   - Implementación en Docker para garantizar portabilidad.


