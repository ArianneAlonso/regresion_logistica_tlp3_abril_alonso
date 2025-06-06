regresion logistica

1. Investiga un caso en la vida real donde podremos aplicar un modelo de Regresión Logística. Fundamenta.

2. Crea o selecciona un datasets que te permita entrenar tu modelo para abordar la problemática.

3. Crea un modelo de regresión logística utilizando la librería Scikit Learn y entrenalo con los datos del datasets.

4. Realiza un gráfico con la librería matplotlib de los datos de entrenamiento y las predicciones realizadas por el modelo.

para esta actividad se uso un dataset de predicion de la diabetes, hipertensión y accidentes cerebrovasculares

se instalaron las dependencias con pip install pandas matplotlib scikit-learn joblib

se uso un entorno virtual en el cual se crea de la siguiente manera: 
abres la terminal y ejecutas:
python -m venv venv
venv/Scripts/Activate
pip install pandas matplotlib scikit-learn joblib

y seleccionar el entorno en el archivo .ipynb

se ejecuto 
df.info y df.describe, para saber si el dataset contaba con valores nulos, de qe tipos son cada columna y cuantas filas son

se definio las variables, "X" "Y"

se entrenó y creó el modelo

se guardó el modelo y se hizo graficos de la prediccion