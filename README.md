# 🧠 visioncomputer

Desarrollo de los talleres del curso de Visión por Computadora  
**Autores:** Manuel Andrade, Gabriel Santiago  

Este repositorio contiene los cuadernos Jupyter desarrollados para cada uno de los talleres del curso, con enfoque en tareas fundamentales de visión por computadora, incluyendo clasificación, recuperación de imágenes y detección de objetos.

## 📁 Contenido del repositorio

| Archivo | Descripción |
|--------|-------------|
| `Taller_1_Prediccion_hojas_mango_15epocs_final.ipynb` | Clasificación de hojas de mango con entrenamiento supervisado de una CNN. |
| `Taller_2_clasificacion_Autogluon_10clases_80%.ipynb` | Clasificación multiclase con AutoGluon usando representaciones extraídas con ResNet50. Incluye comparación por porcentaje de datos (10%, 30%, 80%). |
| `Taller_3_Image_Retrieval.ipynb` | Recuperación de imágenes similares mediante embeddings visuales. |
| `Taller_4_final_Modelos_fundacionalesCNNSencillas.ipynb` | Auto-supervisión con rotaciones usando CNN vs modelos fundacionales (ViT / MAE). |
| `Taller_5_deteccion_aviones_final.ipynb` | Detección de objetos (aviones) en imágenes usando modelos preentrenados. |

## 🔍 Consideraciones

- Para algunos talleres se encuentran múltiples ejecuciones o subconjuntos de datos debido a restricciones de tiempo de cómputo.
- Cada notebook incluye una sección de resultados con gráficos, métricas de evaluación y observaciones.
- En `Taller 2`, se realiza un análisis progresivo de calidad de predicción en función del volumen de datos, útil para comprender el impacto del dataset en modelos AutoML.

## 🛠️ Requisitos

Todos los notebooks fueron desarrollados en Google Colab. Se utilizan librerías como:

- `TensorFlow / Keras`
- `AutoGluon`
- `scikit-learn`
- `matplotlib`, `pandas`, `numpy`
- `timm` (para modelos fundacionales)

## 📌 Cómo usar

1. Clona el repositorio o abre el notebook en Colab.
2. Sigue las instrucciones dentro de cada notebook.
3. Verifica las métricas de evaluación y visualizaciones para cada experimento.

## 📣 Comentarios

Este repositorio fue preparado con fines académicos como parte del curso de Visión por Computadora.  
Si tienes preguntas o sugerencias, no dudes en contactarnos.

