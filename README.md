# Prediction and Inference of Concrete Compressive Strength(CCS) using Regression Analysis

Concrete is a composite material composed of fine and coarse aggregate, bonded together with a fluid cement and hardens over the time. It is the most commonly used man-made material for construction and used extensively in buildings, bridges, roads and dams. Concrete strength is affected by many factors such as quality of raw materials, water : ce- ment ratio, coarse : fine aggregate ratio, age of concrete, compaction of concrete, temperature, relative humidity and curing of concrete. Concrete mixtures can be designed to provide a wide range of mechanical and durability properties to meet the design requirements of a structure. The compressive strength of concrete is the most common attribute used by the engineer when designing structures. It is calculated by the failure load divided by the cross sectional area resisting the load and reported in units of pound-force per square inch (psi) or megapascals (MPa). CCS can vary from 2500 psi (17 MPa) for residential concrete to 4000 psi (28 MPa) and higher in commercial structures.

#### The objective of this study is to make prediction and inference on concrete compressive strength using 8 predictor variables, which are factors that affect the variation of compressive strength of concrete.

### Following are the questions answered in this project.
1. Is there a relationship between dependent variable and predictor variables?
2. Does transformation of dependent variables improve the accuracy of regression model?
3. Does transformation of predictor variable improve the accuracy of regression model?

### The outline of the project is as follows:
1. Use of regression analysis to create a prediction and inference model on Concrete Compressive Strength
2. Use transformation methods such as box-cox and log transformation for dependent and predictor variables
3. Use weighted least square method for model improvement
4. Use variable selection methods such as forward and backward selection
5. Use k-fold cross validation for model validation

#### Dataset

This dataset consists of 1030 observations with 8 quantitative predictor variables and one quantitative response variable. In this dataset, the actual concrete compressive strength for a given mixture under a specific age was determined and recorded. This data set was obtained from UCI machine learning repository. The aim of the project would be “to predict and make inference on concrete compressive strength using the 8 predictor variables. All the variables are described below.

Predictor Variables: (Amount of kg in a m^3 mixture)

1. Cement (cmt) 
2. Blast Furnace Slag (bfs) 
3. Fly Ash (flya) 
4. Water (wtr) 
5. Superplasticizer (spl)
6. Coarse Aggregate (ca)
7. Fine Aggregate (fa)
8. Age - Age of the mixture (number of days)

Dependent Variable: Concrete Compressive Strength(CCS) - measured in MPa (megapascal)
