# Práctica 01 — Red Neuronal con Fine Tuning (dataR2)

## Descripción del problema
El problema abordado en esta práctica consiste en desarrollar un modelo de
Inteligencia Artificial capaz de realizar **clasificación binaria** a partir de un
conjunto de variables biomédicas presentes en el dataset *dataR2*.

El objetivo principal es predecir correctamente la variable **Classification**,
analizando el comportamiento de una red neuronal artificial y evaluando el impacto
del ajuste de hiperparámetros (fine tuning) en el desempeño del modelo.

---

## Stack tecnológico
Para el desarrollo de esta práctica se utilizó el siguiente stack tecnológico:

- Lenguaje de programación: **Python**
- Entorno de desarrollo: **Jupyter Notebook**
- Librerías utilizadas:
  - **Pandas** y **NumPy** para manejo de datos
  - **Scikit-learn** para preprocesamiento, métricas y validación cruzada
  - **TensorFlow / Keras** para la implementación de la red neuronal
  - **Matplotlib** para visualización de resultados

---

## Arquitectura = fases
La solución se estructuró en las siguientes fases:

1. **Carga del dataset**  
   Importación del dataset dataR2 y análisis inicial de sus variables.

2. **Preprocesamiento de datos**  
   Limpieza de datos, separación de variables independientes y variable objetivo,
   y normalización mediante técnicas de escalado.

3. **Modelo base**  
   Implementación de una red neuronal inicial como línea base para comparación.

4. **Fine Tuning del modelo**  
   Optimización de hiperparámetros mediante Grid Search y validación cruzada
   (K-Fold), ajustando arquitectura, número de neuronas y regularización.

5. **Evaluación del modelo**  
   Análisis del desempeño del modelo optimizado utilizando métricas de clasificación.

---

## Capturas
Las evidencias gráficas del proceso de desarrollo se encuentran almacenadas en la
carpeta `capturas/`, incluyendo:
- Visualización del dataset
  <img width="1407" height="503" alt="image" src="https://github.com/user-attachments/assets/d8c67e8e-dcf1-4191-905b-73543348164a" />
- Arquitectura de la red neuronal
  <img width="1156" height="347" alt="image" src="https://github.com/user-attachments/assets/7f4c306f-26b9-466d-98d1-b019f5eb120b" />
  <img width="1699" height="612" alt="image" src="https://github.com/user-attachments/assets/da0749af-9bb6-4e1c-b0dd-99473a883c81" />
- Proceso de entrenamiento
  <img width="953" height="785" alt="image" src="https://github.com/user-attachments/assets/b33bfa01-4f95-477b-aa6c-1ed2ceb6c865" />
- Resultados obtenidos
  <img width="653" height="251" alt="image" src="https://github.com/user-attachments/assets/93487188-99c5-4591-89eb-8eeb7d7c7429" />
  <img width="762" height="507" alt="image" src="https://github.com/user-attachments/assets/5cac25e4-17f0-434f-b4bf-027c2187570c" />
  <img width="1016" height="201" alt="image" src="https://github.com/user-attachments/assets/363b2591-be52-4e05-9f76-489c2daa922e" />
  <img width="1124" height="876" alt="image" src="https://github.com/user-attachments/assets/715707a1-cb65-4570-a795-83125223aade" />
  <img width="731" height="231" alt="image" src="https://github.com/user-attachments/assets/e8241b8f-78ab-4dc3-9858-cbe4e6af48dd" />
  <img width="731" height="187" alt="image" src="https://github.com/user-attachments/assets/b23c682f-da2a-4dcd-a4b9-66184d8fad60" />
  <img width="904" height="114" alt="image" src="https://github.com/user-attachments/assets/23a4dc7f-9b2d-48c4-bd41-d080a9a165e8" />
---

## Qué se logro
Se logró implementar y optimizar una red neuronal artificial, evidenciando una
mejora en el desempeño del modelo al aplicar técnicas de fine tuning y validación
cruzada, reduciendo el sobreajuste y mejorando la capacidad de generalización.

---

## Código
El código fuente desarrollado para esta práctica se encuentra disponible en la
carpeta llamado como`Examen redes neuronales`, debidamente organizado y documentado para su reproducción.

---

## Resultados cuantificables
El desempeño del modelo se evaluó mediante métricas cuantificables, tales como:

- Accuracy:
- Precision:
- Recall:
- F1-Score:


