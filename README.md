# Prediccion de precios de laptops

## Descripción

El conjunto de datos contiene información sobre diversas especificaciones de hardware y los precios de las laptops. Se analizan las características que influyen en el precio para construir un modelo predictivo.

## Objectivo

Este proyecto tiene como objetivo predecir los precios de laptops en base a sus características técnicas, utilizando técnicas de **machine learning**.

## Modelos Evaluados

* **Regresión Lineal**
* **Random Forest**
* **XGBoost**
* **LightGBM**
* **CatBoost**
* 
## Las  métricas utilizadas para evaluar los modelos: R2, MSE y RMSE

|Modelo|	R2|	MSE|	RMSE|
|:-----|:-----|:-----|:-----|
|Regresión Lineal| 0.879467|	213594.644255|	462.163006|
|Random Forest Regressor| 0.977677|	39558.634240|	198.893525|
|XGBoost| 0.990709|	16464.269478|	128.313170|
|LightGBM| 0.993182|	12082.193100|	109.919030|
|CatBoost| 0.995001|	8859.146202|	94.123038|

## Conclusiones

* El R2 de **CatBoost** es es el más alto, lo que indica que tiene las mejores predicciones. Seguido de **LigtGBM** y **XGBoost** con 0.993 y 0.9903 respectivamente. 
* El MSE de **CatBoost** descatada nuevamente aunque es alto pero es menor a los otros.
* El RMSE de **CatBoost** es relativamente alto pero nuevamente es menor a los otros modelos.
* De todos los modelos evaluados, el que peores metricas es la de **Regresion Lineal** en cambio los modelos basados en arboles son las que tiene mejores metricas descatando **CatBoost** con los mejores resultados.
  
