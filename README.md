# TelecomXAluraParte2

Este proyecto forma parte del desafío de análisis de cancelación de clientes (churn) para la empresa ficticia **Telecom X**, siguiendo las directrices del curso de formación en Ciencia de Datos de Alura Latam.

El objetivo principal es predecir qué clientes tienen mayor probabilidad de cancelar el servicio, identificar los factores más influyentes y proponer estrategias para mejorar la retención de usuarios.

## Estructura del proyecto

- `TelecomXAlura_Parte2.ipynb`: Notebook principal con el análisis exploratorio, preparación de datos, entrenamiento de modelos de clasificación y evaluación de resultados.
- `telecomX_limpioP1.csv`: Archivo de datos preprocesado, resultado de la limpieza y transformación de la base original.

## Objetivos

1. Cargar y explorar los datos.
2. Tratar valores nulos y transformar variables categóricas.
3. Visualizar las relaciones entre variables y la cancelación.
4. Entrenar múltiples modelos de clasificación:
   - Regresión Logística (con normalización)
   - KNN (con normalización)
   - Árbol de Decisión (sin normalización)
   - Random Forest (sin normalización)
   - SVM (con normalización)
5. Evaluar los modelos mediante:
   - Exactitud (Accuracy)
   - Precisión
   - Recall
   - F1-score
   - Matriz de confusión
6. Comparar los modelos y seleccionar el mejor.
7. Analizar la importancia de las variables según cada modelo.
8. Proponer recomendaciones para reducir la cancelación de clientes.

## Resultados principales

- Los factores más relevantes en la cancelación fueron: tipo de contrato, monto de facturación mensual, método de pago y tipo de servicio de internet.
- El modelo con mejor balance entre precisión y recall fue **SVM**, con una exactitud cercana al 80%.
- Se evidenció que clientes con contrato mensual, facturación electrónica y servicio de fibra óptica presentan mayor propensión a cancelar.

## Requisitos

- Python 3.10+
- Bibliotecas:
  - pandas
  - numpy
  - seaborn
  - matplotlib
  - scikit-learn

Puedes instalar los requerimientos ejecutando:

```bash
pip install -r requirements.txt
