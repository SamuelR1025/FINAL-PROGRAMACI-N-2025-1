# FINAL-PROGRAMACIÓN-2025-1
Predicción de Diabetes Tipo 2

Este proyecto corresponde al trabajo final de la materia **Programación 2025-1**. Se enfoca en aplicar técnicas de ciencia de datos y aprendizaje automático para predecir la presencia de diabetes tipo 2 en personas adultas, a partir de indicadores de salud.

Objetivo

Desarrollar modelos de clasificación que permitan predecir la diabetes utilizando datos clínicos y de comportamiento recogidos a gran escala.

Dataset

Se utiliza un dataset sintético basado en el **Diabetes Health Indicators Dataset** del BRFSS (Behavioral Risk Factor Surveillance System), con las siguientes características:

* 5000 instancias
* 15 atributos predictivos
* 1 variable objetivo (`Diabetes_binary`)
* Se introdujo un 5% de datos faltantes de forma aleatoria

Estructura del repositorio

├── README.md
├── 01 - exploración.ipynb
├── 02 - preprocesado.ipynb
├── 03 - modelo 1.ipynb
├── 04 - modelo 2.ipynb
├── 05 - comparación.ipynb
├── 06 - dataset.csv
└── 07 - informe.pdf

Modelos utilizados

- **Random Forest**: para clasificación robusta y manejo de variables no lineales
- **Support Vector Machine (SVM)**: para clasificación basada en márgenes óptimos

Ambos modelos fueron evaluados con métricas como precisión, recall, F1-score y matriz de confusión. También se aplicaron técnicas de búsqueda de hiperparámetros para mejorar su desempeño.

Resultados esperados
Comparar el desempeño de los modelos y determinar cuál ofrece una mejor predicción de diabetes, además de analizar el comportamiento frente a problemas de overfitting o bias.

Autor

Samuel Redondo
