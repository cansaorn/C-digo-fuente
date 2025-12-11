# C-digo-fuente
Ángel David
Eduardo Collado
Roberto Román

Análisis, Visualización y Comparación de Modelos de Machine Learning

Dataset: Breast Cancer Wisconsin (scikit-learn)

Descripción General
Este proyecto entrena, compara y evalúa varios modelos de machine learning para la detección temprana de cáncer de mama utilizando el clásico dataset de Breast Cancer Wisconsin. Además, incluye análisis visual, métricas detalladas, validación cruzada, curvas ROC, matriz de confusión y predicción con un caso nuevo.

El código también incorpora un modelo adicional llamado Voting Ensemble, que combina varios algoritmos para obtener un rendimiento más estable y robusto.

Características Principales

- Carga y exploración del dataset
- Normalización de datos con StandardScaler
- Entrenamiento de múltiples modelos:

KNN
Random Forest
SVM
Logistic Regression
Gradient Boosting

Voting Ensemble (nuevo modelo agregado)
- Validación cruzada (5-fold)
- Reportes de clasificación por modelo
- Gráficos avanzados:

Comparación de precisión
Curvas ROC
Matriz de confusión
Importancia de características (si el modelo lo permite)
Distribución de variables importantes
- Predicción detallada con un caso nuevo
- Exportación de gráficos en alta calidad
- Ranking final de modelos

Estructura del Proyecto

analisis_cancer_completo.png
Gráfico general de desempeño de modelos, curvas ROC, matriz de confusión e importancia de características.
distribucion_caracteristicas.png
Histogramas comparativos de las variables más relevantes del dataset.
Código principal.
Maneja todo el análisis automático de principio a fin.

Conclusión

Este proyecto brinda una evaluación completa de diferentes algoritmos de clasificación aplicados al diagnóstico temprano de cáncer de mama. La inclusión del Voting Ensemble mejora la robustez del sistema y demuestra cómo los métodos de combinación pueden incrementar el rendimiento general.
