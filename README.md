# Allstate-1A


---

### 👥 **Team Members**

| Name             | GitHub Handle | Contribution                                                             |
|------------------|---------------|--------------------------------------------------------------------------|
| Kanz Giwa        | @kanzgiwa     | Data exploration, visualization, overall project coordination, dataset documentation, feature engineering, model evaluation, model training and optimization, hyperparameter tuning|
|Samah Keshiro |@samahkeshiro |Model development, hyperparameter tuning, model training and optimization, model evaluation, overall project coordination||                  |               |                                                                          |
| Samip Lamichhane                |@samipLC               | Dataset documentation, feature engineering, model evaluation, model training and optimization, hyperparameter tuning|                                                                          |
|                  |               |                                                                          |

---

## 🎯 **Project Highlights**


- Developed a machine learning model using `XGBoost` to address `better risk assesment, enhance pricing strategies, and streamline claims processing`.
- Reduced `Mean Absolute Error by 40% `, demonstrating `less prediction errors` for `Allstate`.
- Enabled faster, fairer, and data-driven claims assessment for `Allstate`.
- Implemented `feature engineering and scaling` to improve accuracy.

---

## 👩🏽‍💻 **Setup and Installation**

**Provide step-by-step instructions so someone else can run your code and reproduce your results. Depending on your setup, include:**

* [Access the Google Drive with the dataset and Google Colab file](https://drive.google.com/drive/folders/1zt21JxIOPzPp8aMHYheBfVRQCZf8LwZb?usp=sharing)
* Download the dataset
* Open up Google Colab file
* Make sure the path in read_csv() matches the file location of your claims.csv file in your Drive (**should be df.read_csv("/content/drive/MyDrive/Allstate 1A/claims_data.csv")**)
* Run the notebook

---

## 🏗️ **Project Overview**
 
- Our AI Studio team partnered with Allstate, one of the world’s leading insurance companies, to build a machine learning model that predicts the severity of auto insurance claims.
- Goal: Develop a ML model that accurately estimates potential claim costs using historical claims records
- Outcome: Improve risk assessment, enhance pricing strategies, and streamline claims processing


---

## 📊 **Data Exploration**


* The dataset used: categorical and continuous variables
* We used a seaborn correlation matrix for continous features and loss, applied one-hot encoding, and feature engineering
* A large number of categorical features have a small number of unique values and one-hot encoding resulted in a significant increase in the number of columns in the dataset
* Challenges we faced were figuring out which columns to keep and drop

**Visualizations:**

<img width="915" height="836" alt="download" src="https://github.com/user-attachments/assets/5ce88edc-30f7-4be1-be12-64e03c81d1f7" />
<img width="597" height="455" alt="download" src="https://github.com/user-attachments/assets/70b5ced5-c1b3-4c5f-a9b7-cfeed1e5c273" />

---

## 🧠 **Model Development**

* LightGBM, Random Forest, XGBoost, and Lasso Regression models
* Target variable column identified, Feature Engineering (categorical feature encoding, interaction feature engineering, numerical feature scaling)
* Hyperparameter tuning with Randomized Grid Search with cross validation to find best parameters and early stopping
* Data split into 70% training set, 15% validation set, 15% test set. Mean absolute error and root mean absolute error used to evaluate performance and compare against baseline (1978 MAE, 2916 RMSE)


---

## 📈 **Results & Key Findings**

* Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) as evaluation metrics for easy interpreability
* XGBoost model resulted in 1182 MAE and 1979 RMSE, over 40% improvement compared to the baseline model
* Implementing hyperparamter tuning improved XGBoost MAE by 6.52% (MAE of 1262 before tuning)

**Visualization of Actual Loss vs Loss Predicted by our Model**

<img width="868" height="547" alt="download" src="https://github.com/user-attachments/assets/582b530c-cadb-4235-b22b-f5ffff022721" />


## 🚀 **Next Steps**

* Further Feature Engineering
* Optimizing our best performing model (MAE in the hundreds, RMSE in low thousands)
* Making changes to optimize current models 
* Apply some fairness evaluation techniques to categorical features (equalized odds, disparate impact analysis, etc.) to ensure loss predictons aren't unfairly distributed across different segments of the data


---

## 🙏 **Acknowledgements**

Thank you to our Challenge Advisors Nancy Zhang and Krystal Smuda, our Coach Eric Bayless, and the Break Through Tech Team!
