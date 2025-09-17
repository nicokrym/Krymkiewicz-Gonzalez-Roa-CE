# Trabajo Práctico 1 - Intro al Machine Learning

## Consigna

A partir de lo trabajado en el seminario, para este trabajo deberan entregar en un Jupyter Notebook lo siguiente:

- El origen del conjunto de datos que eligieron para la clasificación binaria. Tiene que tener datos numéricos continuos y categóricos.

- Justificación del problema de clasificación.
- Descripción del dataset y su adecuada exploración de los datos. ¿Qué columnas tiene? ¿Qué representan? ¿Pueden encontrar algún tipo de correlación?

- Utilizando Scikit Learn, construir los siguientes modelos:

  - A partir de solo los atributos numericos continuos

    - Un modelo de Regresión Logistica para clasificación.
    - Un modelo de Arboles de Decisión.
  
  - A partir de tanto los atributos numericos continuos como los atributos categoricos del dataset

    - Otro modelo de Regresión Logistica para clasificación
    - Otro modelo de Arboles de Decisión

    Para este último modelo de Arbol de Decisión se debe hacer una exploración de sus posibles hiperparametros para hayar la mejor performance en Validación. Deben utilizar GridSearchCV. (Pueden utilizar RandomizedSearchCV, pero no es obligatorio).

- Para todos los modelos se debe evaluar:
  - La performance haciendo uso de las metricas Accuracy, Precision y Recall en el conjunto de test. (ambas ya implementadas en SK-Learn.)
  - Mostrar una Matriz de Confusión sobre los datos de Test.
  - Para el árbol de decisión, mostrar una curva del accuracy para train y test en función de la profundidad del árbol.

El notebook debe ejecutarse sin errores y debe incluir comentarios explicativos de cada paso. Debe haber cohesión entre las secciones y los análisis realizados.

## 🔋 Bonus

Pueden investigar otros modelos para mejorar la performance de los modelos. Por ejemplo, Random Forest o XGBoost.

## Fecha de entrega

📅 Viernes 20 de Septiembre a las 23:59hs.

Se debe entregar un notebook llamado `apellido1_apellido2_apellido3_(ABD/CEF).ipynb` en el siguiente [Google Forms](https://forms.gle/uojD9eTPsn2XyQ1A6) el Notebook con el análisis realizado.

## Links Útiles

https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html#decisiontreeclassifier
https://scikit-learn.org/stable/modules/generated/sklearn.metrics.precision_score.html

https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html
https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.RandomizedSearchCV.html

https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html
https://xgboost.readthedocs.io/en/stable/

Ademas pueden utilizar los notebooks vistos en clase que están en este Repo de GitHub.
