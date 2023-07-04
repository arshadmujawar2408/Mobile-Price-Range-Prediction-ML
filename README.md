# ML for Mobile Price Range Prediction  
  In the competitive mobile phone market companies want to understand sales to of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, internal Memory etc)and its selling price. In this problem, we do not have to predict the actual price but price range indicating how high the price is.

**Programming Language** : Python

**Libraries used** : Pandas, Numpy, Matplotlib, Seaborn, Sklearn

**NoteBook** : Google Colab

**Dataset Source** : Provided by Almabetter themself.
 
## Dataset 
We are given an Mobile Price Range dataset. It contains the following features.
```
- battery_power :Total energy a battery can store in one time measured in mAh
- blue :Has bluetooth or not
- clock_speed :speed at which microprocessor executes instructions
- dual_sim :Has dual sim support or not
- fc :Front Camera mega pixels
- four_g :Has 4G or not
- int_memory :Internal Memory in Gigabytes
- m_dep :Mobile Depth in cm
- mobile_wt :Weight of mobile phone
- n_cores :Number of cores of processor
- pc :Primary Camera mega pixels
- px_height :Pixel Resolution Height
- px_width :Pixel Resolution Width
- ram :Random Access Memory in Mega Bytes
- sc_h :Screen Height of mobile in cm
- sc_w :Screen Width of mobile in cm
- talk_time :longest time that a single battery charge will last when you are
- three_g :Has 3G or not
- touch_screen :Has touch screen or not
- wifi :Has wifi or not
- price_range :This is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost).
```

- Total number of rows in data:  2000 
- Total number of columns:   21
  
## Exploratory Data Analysis
 Mainly performed using Matplotlib and Seaborn library and the following graph and plots had been used:
   - KDE Plot.
   - Scatter Plot.
   - Pie Chart.
   - Heatmap.
   - Bar plot
   - DisPlot
   - ImpPlot
   - Correction heatmap
             
## ML Model Used:

Several machine learning algorithms were utilized in this project to predict the range price. These models include:
```
1. Logistic Regression
2. Random Forest Classifier
3. DecisionTree Classifier
4. XGboost Classifier
 ```

## Conclusion  
As a single person, I followed a standard workflow for data analysis and model building. Here's a summary of the steps I took:

- Dataset Understanding and EDA: I began by gaining a basic understanding of the dataset, exploring its contents, and performing Exploratory Data Analysis (EDA). This step helped me uncover valuable insights and characteristics of the dataset.

- Feature Engineering: To enhance the predictive power of the models, I applied feature engineering techniques. This involved creating new features, selecting relevant features, or transforming existing features to improve their representation.

- Model Building: The core of my work was focused on building predictive models. I constructed three different models: Logestic regression, Decision tree, Random Forest, and XGBoost. Initially, I used the default parameters for each model.

- Hyperparameter Optimization: To improve the performance of the models, I employed various techniques to find optimal hyperparameters for each model individually. This could include techniques like grid search, random search, or Bayesian optimization.

- Model Selection: Based on the evaluation results, I selected Logistic regression as the preferred model due to its good performance on the dataset.
  
By following these steps, I was able to perform data analysis, build models and select the best model.
