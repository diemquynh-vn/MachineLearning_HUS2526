# MachineLearning_HUS2526

**PROJECT: ANALYSIS AND PREDICTION OF STOCK PRICES IN THE BEER – ALCOHOL INDUSTRY**
---

## 1. Team Members and Task Assignment
**Team Members:**
* **Lưu Thị Thủy Tiên** (Team Leader)
* **Dương Diễm Quỳnh**
* **Lê Xuân Lộc**

**Task Assignment:**
**Lê Xuân Lộc**
* Data preprocessing and statistical analysis.
* Dimensionality reduction using PCA and data visualization.
* Perform clustering using the Gaussian Mixture Model (GMM) algorithm.
* Analyze and interpret clustering results.

**Dương Diễm Quỳnh**
* Build and train the Linear Regression model.
* Perform clustering using the DBSCAN algorithm.
* Perform classification using Gaussian Naive Bayes.
* Evaluate models and analyze experimental results.

**Lưu Thị Thủy Tiên**
* Build and train the KNN model for regression.
* Perform clustering using the K-Means algorithm.
* Perform classification using Decision Tree.
* Evaluate models and analyze experimental results.
---

## 2. Problem Description
The project focuses on analyzing and predicting stock prices of five companies in the beer – alcohol – beverage industry in Vietnam, including the stock codes: HBH, SMB, BHN, SAB, and HAV.
The objectives of the project are:
* To build machine learning models to predict the closing price (Close) of stocks based on historical trading features.
* To perform data analysis and visualization to better understand market trends and structural patterns.
* To evaluate the performance of regression models (Linear Regression, KNN), classification models (Gaussian Naive Bayes, Decision Tree), and clustering algorithms (K-Means, GMM, DBSCAN).
* To identify important factors affecting stock price fluctuations and support investment decision-making.
---

## 3. Data Description
### Data Source
The data was manually collected from the financial website Simplize by downloading `.xlsx` files for each stock code during the period 2021–2025.
Each file contains historical trading data of a company operating in the beer – alcohol – beverage industry.

### Data Structure
The dataset contains approximately 5000 samples with 16 features, including:
* Date: Trading date
* Open, High, Low, Close: Opening, highest, lowest, and closing prices
* Change, %Change: Price change and percentage change compared to the previous trading session
* Volume: Trading volume
* Company: Company ticker symbol
* Average Price: Average price during the trading day
* Market Cap: Market capitalization
* Turnover Rate: Stock turnover ratio
* FB, Trading Value: Trading coefficient and trading value
* MA5: 5-day moving average
* Volatility: Price volatility

### Data Processing
After collecting the data, the team performed the following steps:
* Merged the data of the five companies into a single `.csv` file.
* Cleaned the data, handled missing values, and normalized numerical features.
* Prepared datasets for regression, classification, and clustering tasks.
---

## 5. Experimental Scenario
The experimental workflow of the project is conducted through the following steps:
1. Collect historical trading data of five stock codes from the Simplize website.
2. Perform data preprocessing: merge datasets, clean data, normalize features, and conduct descriptive statistics.
3. Analyze and visualize key features of the dataset.
4. Apply PCA (Principal Component Analysis) for dimensionality reduction and compare original data with reduced data.
5. Apply clustering algorithms: K-Means, GMM, and DBSCAN to explore the data structure.
6. Implement regression models (Linear Regression, KNN) to predict closing prices.
7. Implement classification models: Gaussian Naive Bayes and Decision Tree.
8. Evaluate the models using appropriate metrics and visualize the results.
9. Compare results, analyze findings, and draw conclusions.
