
# 🚢 Titanic - Machine Learning from Disaster

Este proyecto aplica Machine Learning supervisado para predecir la supervivencia de los pasajeros del Titanic usando regresión logística. 🧠

---

## 📂 Contenido del Proyecto

- `titanic_modelo_ml.py`: Código fuente principal que carga los datos, entrena el modelo y lo evalúa.
- `train.csv`: Conjunto de datos de entrenamiento (no incluido en el repo por tamaño).
- Documentación en Word y tabla de habilidades incluidas.

---

## 🧠 Modelo Utilizado

Se entrenó un modelo de **Regresión Logística** con `scikit-learn`, usando las siguientes técnicas:

- Limpieza de datos (valores nulos, columnas irrelevantes)
- Codificación de variables categóricas
- División de datos en entrenamiento y prueba
- Evaluación con métricas como `accuracy`, `confusion_matrix` y `classification_report`

---

## 📊 Resultados

- **Accuracy del modelo:** ~81%
- Buen rendimiento al predecir tanto sobrevivientes como no sobrevivientes
- Se visualizó la matriz de confusión con `seaborn`

---

## 🧰 Tecnologías Usadas

- Python
- pandas
- NumPy
- scikit-learn
- seaborn
- matplotlib

---

## 🎯 Cómo correr el proyecto

1. Clona el repositorio:
   ```bash
   git clone https://github.com/MayChio/titanic-ml-project.git
