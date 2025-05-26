# PARCIAL_1

Utilizando un esquema de validacion cruzada de 5 folds,  se compara el rendimiento de los siguientes regresores de sklearn sobre el ´
conjunto de datos Ames Housing Dataset: https://www.kaggle.com/datasets/shashanknecrothapa/ames-housing-dataset:
• LinearRegresor
• Lasso
• ElasticNet
• KernelRidge
• SGDRegressor
• BayesianRidge
• Gaussian Process Regressor
• RandomForestRegressor
• Support Vector Machines Regressor


Se Utiliza GridSearch, RandomSearch y optimizacion Bayesiana con muestreo tipo Gaussian Processes para encontrar los hiper-
parametros relevantes de cada modelo. Se Justifican los hiper-parametros a buscar, la rejilla o cotas de valores escogida para cada
algoritmo segun los modelos estudiados y el score a minimizar. Finalmente,se presentan los rendimientos promedios en los datos de 
evaluacion con su respectiva desviacion estandar para las siguientes medidas de desempeño: MAE, MSE, R2 y MAPE.


 Se construye un Dashboard a partir del paquete Streamlit: https://streamlit.io/ que permita visualizar de forma intuitiva el dataset y
comparar el rendimiento de los tres mejores regresores

+ En este repositorio se encuentra la teoria (archivo .pdf) de los modelos analizados en el codigo: PARCIAL_TAM.ipynb

+ Y tambien esta el codigo de la aplicacion de streamlit en : APP.ipynb

PDT: (el dashboard tiene la logica de ejecucion de acuerdo a como se ejecuta el cuaderno, se puede arreglar, pero por temas de tiempo y robustez se deja asi como esta )
link del dashboard: https://4e1e-35-185-9-112.ngrok-free.app/
