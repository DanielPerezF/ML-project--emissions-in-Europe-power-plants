# ML-project--emissions-in-Europe-power-plants

Project on predicting specific emissions (kg CO2 / kW) of power plants in Europe. This was done using JRC Open Power Plants Database (JRC-PPDB-OPEN) published on December 2019. It can be accesed at https://data.jrc.ec.europa.eu/dataset/9810feeb-f062-49cd-8e76-8d8cfd488a05.
This was done in Python using Jupyter notebooks. The main library used was scikit-learn where different regression algorithsm were tested. In the end, an $R^2$ score of $98.56$% was obtained using a decision tree regressor.

The project consisted of 4 steps that can be found in the individual notebooks:
1. Exploratory analysis of the data: analyse the type of data, the columns, the distribution of power plants and emissions. <img src="https://github.com/DanielPerezF/ML-project--emissions-in-Europe-power-plants/assets/118309576/e19b6aeb-4a7b-44d1-86c2-5b7da22ea39e" width="20%"> <img src="https://github.com/DanielPerezF/ML-project--emissions-in-Europe-power-plants/assets/118309576/7eb17819-9c1e-46f8-b5e3-d7c622d04620" width="79%">

2. Pre processing of the data for machine learning: process the data to obtain features for the models.
3. Modelling: evaluate several regression models with default parameters to compare performance.![image_2023-09-27_151828632](https://github.com/DanielPerezF/ML-project--emissions-in-Europe-power-plants/assets/118309576/bf590341-1b4e-4736-a3a2-7b1647caa461)
4. Tuning and results: choose a model and tune it to evaluate the results.

The raw data can be found in the DATA folder and the data used for modeling (features, objects) in the MODELLING DATA folder.
