# 📌 Descripción del Modelo de Machine Learning

Este proyecto utiliza un modelo de **Árbol de Decisión** para realizar predicciones relacionadas con problemas de columna vertebral. El modelo fue creado, definido, entrenado y testeado en un entorno de Google Colab.

## 📍 Origen del Modelo

El modelo fue desarrollado en el siguiente notebook de Google Colab:

🔗 [Google Colab - Modelo de Árbol de Decisión](https://colab.research.google.com/drive/1K16cQzeSptOwU81W3i8ZsziQcjm35Q0F?usp=sharing)

## 🛠️ Proceso de Creación

El modelo fue entrenado con un conjunto de datos específico, utilizando la librería **Scikit-Learn**. El flujo general del proceso fue el siguiente:

1. **Importación de Librerías:** Se usaron librerías como `pandas`, `numpy`, y `sklearn`.
2. **Carga del Dataset:** Se obtuvo un dataset con información sobre medidas de la columna vertebral.
3. **Preprocesamiento:** Se limpiaron y transformaron los datos para adaptarlos al modelo.
4. **Entrenamiento del Modelo:** Se usó un clasificador de Árbol de Decisión (`DecisionTreeClassifier` de Scikit-Learn).
5. **Evaluación:** Se midió la precisión del modelo con métricas como `accuracy_score`.

## 🚀 Uso en la API

La API de esta aplicación consume el modelo previamente entrenado para realizar predicciones en tiempo real. El backend procesa los valores ingresados por el usuario y utiliza el modelo de Machine Learning para retornar un diagnóstico basado en los datos proporcionados.

## 📂 Código Relacionado

- **[Aplicación Móvil](https://github.com/JTWindshaker/predictColumn)** – Implementación del cliente móvil que consume la API y permite a los usuarios realizar predicciones desde su dispositivo.
- **[Modelo: modelo_columna.bin](https://github.com/JTWindshaker/predictColumnModel/blob/main/Arboles_Columna_Vertebral.ipynb)** – Notebook de Google Colab en GitHub con el código completo para la creación, entrenamiento y evaluación del modelo de Árbol de Decisión utilizado en la aplicación.
- **[ApiRest](https://github.com/JTWindshaker/predictColumnApi)** – Servicio backend encargado de procesar las solicitudes de la aplicación móvil. Implementa el modelo de Machine Learning para realizar predicciones en tiempo real y devolver los resultados al usuario.
