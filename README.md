# Used Vehicle Price Prediction
This is my personal project about predicting used vehicle's price. The datasets of this project is came from kaggle's datasets, you can find it [here](https://www.kaggle.com/datasets/farhanhossein/used-vehicles-for-sale).

The motivation of this project is to gain some knowledge on data cleaning, domain knowledge about car, data preprocessing, modeling, etc. Hence the notebook divided into some main section:
1. Preparation

    This section consists of import the necessary library to analyze the data and import the raw data itself.
2. Exploratory Data Analysis and Data Cleaning

    This section consists of analyzing the data and cleaning it at the same time based on our domain knowledge.
3. Data Preprocessing

    In this section, we will transform the data so it can be fed into machine learning model, this section contains 2 main parts, which are data preprocessing for categorical data and numerical data.
4. Modeling

    This section, we will train the model by using autoML, then we will pick the best possible model based on evaluation metrics.
5. Hyperparameter Tuning

    After we picked the model in previous section, we will do some hyperparameter tuning to the model. We will using cloud platform in order to do it, since it's quite exhausting for my local machine to do it. We will import the hyperparameter tuning data from the cloud and train the model by using the best hyperparameter on my local machine.

The notebook contains table of contents, so if you want to jump to the specific section, you can open the notebook in nbviewer, [here](https://nbviewer.org/github/alfiannajih/used-vehicle-price-prediction/blob/main/used_vehicle.ipynb), since github doesn't support linking inside local notebook.