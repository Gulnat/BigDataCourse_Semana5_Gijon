# CursoBigDataSemana5

## File M5_01 Python :

- Theory on lists, operators, types of data, functions, dictionaries, strings.
- Functions Maps, Filter and Reduce.
  
## File M5_02 Conditions :

- Practicing applying the IF structure.
- Examples with Tree diagram (Super heroes), Loop year and Palindrom.
 
## File M5_03 Bucles/Loops :

- Theory and practice on the usage of loops FOR and WHILE.
- Iterations.
- Ex on counting the number of vocals in the string. Generate number sequencies, nested loops, use of Range. 

## File SpaceX :

- Import libraries
- Function for creating empty lists: LaunchSite, PayLoads and CoreData
- Append()
- Head()
- Filter dataframe, condition

In this practice you will obtain the data to predict if a Falcon 9 will land successfully or not.

## File Introduction a Machine Learning / SciKit Learn :

- !pip install scikit-learn - import SciKit 
- Ej1 of Supervised Learning: X-Train. X-Test, Y-Train, Y-Test - 20/80 notion
- Assigning instances for testing
- Fit() - for training the model
- Predict() - after training its ready to make prediction
- Lineplot(), Scatterplot() - build a graph for prediction 
- Ej2 - using LinearRegression model
- StandardScaler - normalization of values, build 2 graphs to compare original and normalised values
- Ej3 - problem of overfitting, as using 100% of testing data instead of 80%
- Ej4 - GridSearch CV - Cross Validation. Repite many times and choose the best in terms of best parametres of m and n.

## Predecir el valor de Bitcoin :

- Prophet - library for predicting timeseries
- !python -m pip - install prophet
- Download BTC (Bitcoin) timeseries from Yahoo Finance
- btc_df.isnull().sum() - valifate nulls
- Use only 2 columns "Date" and "Open" and rename them into "Ds" and "Y"
- Build a graph on all data
- Assign instance, train model with fit()
- Make_future_dataframe(x) - method of Prophet for making a prediction

## Folium  : NB!!! TO Do

- Import libraries
- Function for creating empty lists: LaunchSite, PayLoads and CoreData
- Append()
- Head()
- Filter dataframe, condition

## File M5-Spacex2-6 ML Prediction : 

- 1.Import libraries
- 2.Def function de visualization of matrix de confusion
- 3.Download first df (variable type is text + Class)
- 4.Download second df (normalisation of (3)). Transformacion one-hot(X)
- 5.TAREA 1. Crear un array NumPy de Class con metodo to_numpy(). Y=data['class'].to_numpy()
- 6.TAREA 2. Normalise los datos en X con function fit_transform. X=scaler.fit_transform(X)
- 7.TAREA 3. Dividimos values en 4 partes (entrenamiento y prueba) by using train_test_split()
X_train, X_test,Y_train,Y_test= train_test_split
(X,Y,tarin_size=0.8,random_state=2)
- 8.TAREA 4. To train objeto GridSearchCV para encontrar mejores parametres del diccionario parametres
GridSearchCV(modelo, parametres, scoring,CV)
- 8.1.parametres ={'c':[0.01,0.1.1], 'penalty': ['12'], 'solver': ['lbfgs']
- 8.2.Crear un objeto de RegrLogistica. modelo=LogisticRegression()
- 8.3.Crear un objeto GridSearchCV con (8.2)+mas
logreg_cv=GridSearchCV(modelo,parametro,scoring='accuracy', CV=10)
- 8.4.Train ridSearchCV to define the best parameters of dictionary parameters
logreg_cv.fit(X_train,Y_train)
- 8.5.Print mejores parametros - presicion de trained data.  best_params_, best_score_ 
- 9. TAREA 5. 
- 9.1 Precision de prueba X_test, Y_Test - metodo score(), precision=logreg_cv.score(X_Test, Y_Test)
- 9.2 Prediction Y_Pred with input X_Test, Y_Pred= logreg_cv.predict(X_Test)
- 9.3 Compare Y_Pred (de 9.2) and Y_test. Usar function de Luis de matrix de confusion. Plot_confusion_matrix(Y_Test, Y_Pred)
- 10. Tarea 6. From imports take first model SVC(). Next, the same as Tarea4 (de 8) repeat from 8.1 until 8.5
- 11. Tarea 7. Calculate precision como en tarea 5 (de 9), repeat from 9.1. until 9.3
- 12. Tarea 8. Arbol de decision. The same as Tarea 4, repeat 8.1.- 8.5
- 13. Tarea 9. The same as Tarea 5, repeat 9.1 - 9.3
- 14. Tarea 10. 
  
## File SpaceX-4 EDA with Visualization :

- Import matplotlib and seaborn for creating graphs
- Using Categorical plot catplot() create different graphs based on different categories (Ej1)
- In Ej2 in Orbits calculate probabilities of success using groupby(),and sort it using sort_values(). Based on it, build a bar chart.
- In Ej3 repeat all steps of Ej2 using LaunchSite as a measure.
- In Ej4 use finction DatetimeIndex() in order to see the change of the PayLoadMass over the time (years). Build a lineplot.
- In Ej6 repeat all steps as in Ej4 but for Probability of Successes, the month timeseries.
- In Ej7 repeat all steps as in Ej6 but for Probability of Successes, the year timeseries.
    
## File Repaso - Teoria :

- Cover all topics of Semana 5 de ML, AI, Python syntax, NumPy, ML Regression and Prediction

