This repo explores regression techniques to predict:House prices using linear and multiple linear regression based on property characteristics.
Car prices based on multiple vehicle-related features.
Folder StructureCar_priceCar price prediction uses a multivariate linear regression model trained on features such as:
1.Brand
2.Body type
3.Mileage
4.Engine Volume (engineV)
5.Engine Size
6.Registration
7.Year
8.Model
Data preprocessing includes cleaning missing values, handling categorical variables (creation of dummies), and feature selection. 
The notebook/code walks through data cleaning, encoding, training a regression model, and evaluating predictions.

Simple Linear reg: This section covers basic house price prediction using simple linear regression:
Independent variable: Size (e.g., square footage)Target variable: Price
The code demonstrates:Loading and inspecting the dataTraining a linear regression model with one featureVisualizing results and assessing accuracy

multiple_linear_reg: Expands house price prediction using multiple independent variables:Size Beach view (Yes/No)
This section walks through:Data preparation for multiple regression 
Encoding categorical variables (beach view)
Training and assessing a multiple linear regression model.
