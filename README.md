# IBM-DataScience-SpaceX_Capstone
![Capstone](https://github.com/user-attachments/assets/83fa40af-f158-40ea-9c6a-bd1d8e3b1e62)


</p>

## 📄 Summary
This project aims to **predict the likelihood of a successful landing for the first stage of the Falcon 9 rocket.**

The complete report can be found [here](https://github.com/nevassy/IBM-DataScience-SpaceX_Capstone/blob/main/Capstone%20Project.pdf).

### Context and Business Understanding
- SpaceX advertises Falcon 9 launches at a cost of 62 million dollars, significantly lower than the 165 million dollars charged by competing providers. A major contributor to this cost difference is SpaceX's ability to reuse the first stage.  

- By accurately forecasting whether the first stage will land successfully, we can estimate the overall launch cost. This predictive capability could provide valuable insights for alternative companies seeking to compete with SpaceX in rocket launch contracts.

## 📑 Main Topics 
This project follows these steps:
1. [Data Collection](https://github.com/nevassy/IBM-DataScience-SpaceX_Capstone/blob/main/1.SpaceX%20Data%20Collection%20API.ipynb)
    - Request to the SpaceX API
    - [Web Scraping from Wikipedia](https://github.com/nevassy/IBM-DataScience-SpaceX_Capstone/blob/main/2.SpaceX%20Web%20scraping%20Falcon%209%20and%20Falcon%20Heavy%20Launches%20Records%20from%20Wikipedia.ipynb) 
2. [Data Wrangling ](https://github.com/nevassy/IBM-DataScience-SpaceX_Capstone/blob/main/3.SpaceX%20Data%20wrangling.ipynb)
    - Determine the number of launches on each site, number and occurrence of each orbit, number and occurrence of mission outcome per orbit type using .value_counts()
    - Create a landing outcome label:
      0 (not land successfully) and
      1 (land successfully)
3. [Exploratory Data Analysis](https://github.com/nevassy/IBM-DataScience-SpaceX_Capstone/blob/main/4.%20SpaceX%20EDA%20Using%20SQL.ipynb)
    - Manipulate and evaluate the SpaceX dataset using SQL queries
    - Visualize relationships between variables, and determine patterns using Pandas, and Matplotlib

4. [Interactive Visual Analytics](https://github.com/nevassy/IBM-DataScience-SpaceX_Capstone/blob/main/6.SpaceX%20Location%20Analysis%20with%20Folium.ipynb)
    - Geospatial analytics using Folium
    - Interactive dashboard using Plotly Dash
5. [Predictive Analysis (Classification)](https://github.com/nevassy/IBM-DataScience-SpaceX_Capstone/blob/main/8.SpaceX_Machine%20Learning%20Prediction_Part_5.ipynb)
    - Using Scikit-Learn to:
        - Pre-process (standardize) the data
        - Split the data into training and testing data using train_test_split
        - Train different classification models
        - Find hyperparameters using GridSearchCV
    - Plotting confusion matrices for each classification model
    - Assessing the accuracy of each classification model
    - Machine Learning prediction using Logistic Regression, Support Vector Machine (SVM), Decision Tree, K-Nearest Neighbors(KNN)
