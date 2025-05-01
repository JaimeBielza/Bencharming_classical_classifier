# Heart Attack Classification Benchmark

Este repositorio implementa un **benchmark** de modelos de clasificación supervisada aplicados a la predicción de ataques cardíacos.  
Compara:

- **Regresión Logística** (con regularización L2 y búsqueda de `C`)  
- **SVM** con:
  - Kernel lineal  
  - Kernel polinómico  
  - Kernel RBF  

Cada modelo se entrena mediante pipelines de `scikit-learn`, incorpora escalado de características, validación cruzada estratificada y `GridSearchCV` para optimizar hiperparámetros. Finalmente, se comparan sus rendimientos usando **accuracy**, **F1-score** y **ROC AUC**.
