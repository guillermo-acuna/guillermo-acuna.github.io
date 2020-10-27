# Guillermo Acuña
Mi nombre es Guillermo Acuña, economista especialista en econometría, data science y machine learning. 

Este es mi portafolio, el lugar donde comparto algunos de mis trabajos, especialmente en las áreas de data science y machine learning.

Si deseas contactarme me puedes encontrar en mis redes sociales:
- [Twitter](https://twitter.com/guillermoacuna)
- [LinkedIn](https://www.linkedin.com/in/guillermoacuna/)

Además tengo un [sitio web](https://sites.google.com/view/guillermoacuna/home) donde puedes encontrar información adicional.

## Análisis del sentimiento de las noticias económicas en Chile (NLP)
Este es un proyecto en desarrollo, que inicié en abril del año 2020. Por ahora tengo algunos análisis preliminares, que listo a continuación:

### [Clústering de textos económicos](https://github.com/guillermoacuna-lab/portfolio/blob/main/Text%20Clustering.ipynb)
En este análisis se clasifican las noticias económicas en base a un algoritmo de clústering, para encontrar patrones entre los diferentes tipos de noticias. Esta técnica es interesante, ya que se puede utilizar para clasificar las respuestas de preguntas abiertas en una encuesta, en que hacerlo de forma manual podría ser muy intensivo en tiempo. 

![](https://github.com/guillermoacuna-lab/Portafolio/blob/main/Images/wordcloudnoticias.jpg)

### [Clasificación del sentimiento de las noticias económicas](https://github.com/guillermoacuna-lab/Portafolio/blob/main/SentimentNews.ipynb)
En este análisis verifico por primera vez si es posible predecir el sentimiento de las noticias económicas con precisión. Con este objetivo comparé el desempeño de una regresión logística, red neuronal artificial, red neuronal con embeddings y LSTM. Sin embargo, por el momento la base de datos es pequeña,contiene menos de 1000 observaciones, por lo que no se obtienen los mejores resultados especialmente en el caso de las redes neuronales, que tienden a sobreajustarse a los datos. Este análisis se irá actualizando a medida que obtenga más datos.

## Algoritmos de Clasificación

### [Churn prediction](https://github.com/guillermoacuna-lab/Portafolio/blob/main/Churn.ipynb)
En este análisis se muestra cómo predecir la tasa de fuga de clientes (Churn rate) usando una base de datos de Kaggle y tres algoritmos de clasificación: la regresión logística, random forest y XGBoost.

![](https://github.com/guillermoacuna-lab/Portafolio/blob/main/Images/Churn%20feature%20importances.png)

## Algoritmos de Regresión

### [Predicción de los precios de los derechos de agua en Chile](https://github.com/guillermoacuna-lab/Portafolio/blob/main/VAC.ipynb)
En ste ejercicio se comparan varios algoritmos de predicción de variables continuas, lo que comúnmente denominamos análisis de regresión. La variable a predecir son precios registrados en transacciones de derechos de agua en Chile, que se caracterizan por ser muy variables y contener una gran cantidad de valores outliers. Se comparan algunos modelos que provienen de la econometría con algoritmos típico de machine learning.

![](https://github.com/guillermoacuna-lab/Portafolio/blob/main/Images/Precios.jpg)

## Modelos de series de tiempo: ARIMA

### [Predicción del Imacec](https://github.com/guillermoacuna-lab/Portafolio/blob/main/ForecastingImacec.ipynb)
En este ejercicio se hace una predicción del Imacec, el índice mensual de actividad económica, publicando por el Banco Central de Chile. El objetivo es ilustrar cómo utilizar modelos ARIMA estacionales (SARIMA) para hacer predicciones de series temporales.

![](https://github.com/guillermoacuna-lab/Portafolio/blob/main/Images/Imacec.jpg)
