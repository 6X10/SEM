# SEM (09.2022 ~ 02.2023)
* Ewha Math Study Club at Ewha Womans University in South Korea
* As the Statistical Team Leader, I led entire data analysis process

### 1. Project Introduction
   Teammates and I conducted empirical analysis by using all linear models in scikit-learn package which we studied for a semester.

### 2. Purpose of Analysis
   My team aimed to find the best prediction model and optimal hyperparameter set for the demand of Seoul Bike with the weather data. 

### 3. Process of Analysis
   * Analysis Tools
     <br/> Python(libraries such as NumPy, Pandas, seaborn, matplotlib, SciPy and Scikit-learn)
   * Data
     Seoul Bike (http://data.seoul.go.kr/dataList/OA-14994/F/1/datasetView.do)
     Weather (https://data.kma.go.kr/data/grnd/selectAwsRltmList.do)
   * Analysis
     - Processed data such as handling missing values with KNN Imputer and one hot encoding for categorical variable
     - Select a model and hyperparameter set with the most popular '대여소' among lr, ridge, lasso, elastic, LassoLars, SGDRegressor, lm.SGDRegressor, and Perceptron based on MAE
     - Checked average error for every '대여소' with best prediction model
     - 
### 4. Result of Analysis
 Best model is elastic with alpha=01 and average on prediction is one bicycle.

### 5. What I learned
   * I handled raw data and conducted complex data preprocessing, such as missing value imputation.
   * I used ML models in the Scikit-learn package and selected the best prediction model with hyperparameter tuning.
   * I refined, analyzed, and visualized data using Python with various packages. 
     
