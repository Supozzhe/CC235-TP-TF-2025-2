# CC235-TP-TF-2025-2  
Curso de Procesamiento de Imágenes  

## Trabajo Parcial 2025-02  

### Objetivo del trabajo  
Aplicar técnicas de **procesamiento de imágenes** aprendidas en el curso para analizar un conjunto de datos visuales y proponer un modelo que permita **responder preguntas de clasificación o predicción**.  
El objetivo es comparar el rendimiento entre un enfoque **clásico** (técnicas tradicionales de visión por computadora) y un enfoque basado en **redes profundas**, evaluando su desempeño mediante métricas e interpretando los resultados obtenidos.

---

### Integrantes del grupo  
- **Sebastián Rojas Vélez de Villa** – U202110299  
- **Braulio Alonso Bartra Sandoval** – U202214969  
- **Luis Marcelo Mercado De la Rosa** – U20211B656  
---

### Descripción del dataset  
El dataset seleccionado para este proyecto es **Fruits 360**, disponible públicamente en [Kaggle](https://www.kaggle.com/datasets/moltean/fruits).  
Contiene alrededor de **70,000 imágenes** de frutas y verduras pertenecientes a más de **120 clases diferentes**, capturadas en distintas condiciones de iluminación y con variabilidad visual significativa entre categorías.

En su estado actual, el dataset **requiere un proceso de limpieza y preparación** antes del análisis. Entre las tareas previstas se encuentran:  
- **Normalización de tamaños y formatos de imagen.**  
- **Revisión de clases desbalanceadas** (algunas categorías tienen más muestras que otras).  
- **Eliminación de imágenes con ruido o fondos inconsistentes.**  
- **Ajuste del conjunto de entrenamiento y prueba** para evitar sobreajuste.  

Estas etapas de preprocesamiento permitirán aplicar de manera más efectiva las fases del proyecto, como la segmentación, la extracción de características y la clasificación final.  

El conjunto de datos será utilizado para responder preguntas como:  
- ¿Qué técnicas de preprocesamiento mejoran la precisión en la clasificación de frutas?  
- ¿Cómo se comporta un modelo clásico frente a una red neuronal profunda en un dataset con ruido y variabilidad?  
- ¿Qué métricas permiten evaluar mejor la robustez del modelo ante datos no balanceados?  


###  Conclusiones  
En este trabajo se busca comprobar cómo las técnicas clásicas de procesamiento de imágenes (como ecualización, filtrado, detección de bordes, entre otras) se comparan frente a las redes neuronales profundas (CNN, Transfer Learning, etc.).  
Los procedimientos y resultados estarán enfocados en:  
- Analizar el **rendimiento y precisión** alcanzados por cada método.  
- Identificar las **limitaciones del dataset**, especialmente aquellas relacionadas con el balance de clases, la limpieza de imágenes y la calidad del etiquetado.  
- Proponer **mejoras futuras**, como el uso de técnicas de aumento de datos (*data augmentation*), mayor control de iluminación o reentrenamiento con nuevas muestras.  


📎 *Nota:* Este README corresponde al **Trabajo Parcial (TP)** del curso CC235 – Procesamiento de Imágenes. Será actualizado con los resultados, métricas y modelo final para el **Trabajo Final (TF)**.
