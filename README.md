# Allstate-1A


---

### 👥 **Team Members**

**Example:**

| Name             | GitHub Handle | Contribution                                                             |
|------------------|---------------|--------------------------------------------------------------------------|
| Kanz Giwa        | @kanzgiwa     | Data exploration, visualization, overall project coordination, dataset documentation, feature engineering, model evaluation, model training and optimization, hyperparameter tuning|
|Samah Keshiro |@samahkeshiro |Model development, hyperparameter tuning, model training and optimization, overall project coordination||                  |               |                                                                          |
|                  |               |                                                                          |
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

**Describe:**

- How this project is connected to the Break Through Tech AI Program
- Your AI Studio host company and the project objective and scope
- The real-world significance of the problem and the potential impact of your work

---

## 📊 **Data Exploration**

**You might consider describing the following (as applicable):**

* The dataset(s) used: origin, format, size, type of data
* Data exploration and preprocessing approaches
* Insights from your Exploratory Data Analysis (EDA)
* Challenges and assumptions when working with the dataset(s)

**Potential visualizations to include:**

* Plots, charts, heatmaps, feature visualizations, sample dataset images

---

## 🧠 **Model Development**

* LightGBM, Random Forest, XGBoost, and Lasso Regression models
* Target variable column identified, Feature Engineering (categorical feature encoding, interaction feature engineering, numerical feature scaling)
* Hyperparameter tuning with Randomized Grid Search with cross validation to find best parameters and early stopping
* Data split into 70% training set, 15% validation set, 15% test set. Mean absolute error and root mean absolute error used to evaluate performance and compare against baseline (1978 MAE, 2916 RMSE)


---

## 📈 **Results & Key Findings**

**You might consider describing the following (as applicable):**

* Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) as evaluation metrics for easy interpreability
* XGBoost model resulted in 1182 MAE and 1979 RMSE, over 40% improvement compared to the baseline model
* Implementing hyperparamter tuning improved XGBoost MAE by 6.52% (MAE of 1262 before tuning)

**Visualization of Actual Loss vs Loss Predicted by our Model**

<img width="868" height="547" alt="download" src="https://github.com/user-attachments/assets/582b530c-cadb-4235-b22b-f5ffff022721" />


## 🚀 **Next Steps**

**You might consider addressing the following (as applicable):**

* What are some of the limitations of your model?
* What would you do differently with more time/resources?
* What additional datasets or techniques would you explore?
* Apply some fairness evaluation techniques to categorical features (equalized odds, disparate impact analysis, etc.) to ensure loss predictons aren't unfairly distributed across different segments of the data


---

## 🙏 **Acknowledgements** (Optional but encouraged)

Thank you to our Challenge Advisors Nancy Zhang and Krystal Smuda, our Coach Eric Bayless, and the Break Through Tech Team!
