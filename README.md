# NLP-Spam-PySpark-Project
An NLP spam Pyspark model to predict if a message is Spam or not

## Spanish

En este proyecto de NLP en Pyspark, se tiene un large dataset que contienen mensajes de tipo Spam y No spam. El trabajo requerido aquí es crear un modelo para poder predecir que mensajes son Spam y cuáles no, mediante el uso de herramientas de PySpark.

El modelo comienza con una simple linea base para luego intentar mejorar le modelo. Le sigue una exploración de datos, que ayude a visualizar las diferencias entre mensajes con SPAM y mensaje ssin SPAM (como la cantidad de palabras y cantidad de stopwords usadas, etc).

Con lo anterior se eliminan caracteres inútiles, stopwords, mensjaes con pocas palabras y se manda todo a minusculas. Luego se predice el modelo y se crea una matriz de confusión para saber si el modelo predice bien o mal. Cabe destacar que se crean dos modelos, uno con Naivebayes y otro con Regresión Logistica. El modelo con mejor capacidad predictiva fue el modelo de Regresión logística.

Finalmente al modelo se le agrega Lematización que es una herramienta para que palabras similares se reduzcan a una sola. Se entrena el modelo y se crea una matriz de confusión con los KPI's que permiten hacernos saber si el modelo predice bien o mal.
El accuraccy, f1, precision y recall del modelo son más del 93%.


## English

In this PySpark project, we have a large dataset that contains messages labeled as spam and not spam. The objective is to create  a model that predicts if a message is spam or not.

The model strats with a base line. Next is to explore the data, to visualize differences between spam and not spam items.
The next step is to eliminate useless characters, stopwords, messages with few words and lowwercase the texts. Then we use the model to predcit and create a confusion matrix to see if the model is correctly predicting. Two models were created, one with NaiveBayes and another one with Logistic Regression. The model with best predictive power was the model with Log Reg.

Finally to the model we add Lematization a well known tool to reduce words. Then the model is trained and a matrix is created. The accuracy, f1 score, precision and recall of the model are better than 93%
