Predicción de Supervivientes del Titanic
Este repositorio contiene un proyecto de Machine Learning que utiliza datos del famoso desastre del Titanic para predecir la supervivencia de los pasajeros. Se utiliza un conjunto de técnicas de aprendizaje supervisado para construir y evaluar modelos predictivos.

Conjunto de Datos
El conjunto de datos utilizado en este proyecto se obtiene de Kaggle https://www.kaggle.com/competitions/titanic y contiene información sobre pasajeros del Titanic, incluyendo características como edad, sexo, clase de boleto, etc., así como la variable objetivo "Survived" que indica si el pasajero sobrevivió o no.

Preprocesamiento de Datos
El preprocesamiento de datos es una parte crucial del proyecto y se lleva a cabo antes de construir y entrenar los modelos de Machine Learning. Esto incluye la limpieza de datos, manejo de valores faltantes, ingeniería de características y codificación de variables categóricas.

Modelado
Se exploran y comparan varios algoritmos de clasificación, como Regresión Logística, Bosques Aleatorios y Redes Neuronales, para determinar cuál ofrece el mejor rendimiento en términos de precisión de predicción. Se ajustan y evalúan múltiples modelos utilizando técnicas como la validación cruzada y la búsqueda de hiperparámetros.

Evaluación del Modelo
La evaluación del modelo se realiza utilizando métricas como la precisión, el recall, la curva ROC y el área bajo la curva (AUC). Se utiliza un conjunto de datos de prueba separado para evaluar el rendimiento del modelo finalmente seleccionado.

Uso del Repositorio
data/: Carpeta que contiene los datos del Titanic en formato CSV.
notebooks/: Jupyter Notebooks que contienen el código utilizado para el preprocesamiento de datos, construcción y evaluación de modelos..

README.md: Este archivo, proporcionando una descripción general del proyecto y cómo utilizarlo.
Requisitos
Python 3.x
Bibliotecas de Python: pandas, scikit-learn, matplotlib, seaborn, etc.
Cómo usar
Clona este repositorio en tu máquina local.
Instala las dependencias necesarias utilizando pip install -r requirements.txt.
Explora los cuadernos Jupyter en la carpeta notebooks/ para comprender el flujo de trabajo y la implementación del proyecto.
Utiliza el código fuente en la carpeta src/ para reutilizar funciones y clases en tus propios proyectos.
Contribuciones
Las contribuciones son bienvenidas. Si deseas contribuir al proyecto, por favor abre un issue para discutir los cambios propuestos o envía una pull request.

Licencia
Este proyecto está bajo la licencia MIT.
