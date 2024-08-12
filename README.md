# Predicting and locating brain tumors using Regression

## Introduction  
This project involves building a predictive model to recognize and locate brain tumors in scans. 
The dataset contains two dataframes: image_df with 2500 brain scan images, and data_df providing tumor location coordinates. 
Understanding these factors is crucial for improving a hypothetical brain scan classifier and accurately identifying tumor locations which I attempt to do.

## Project Structure  
- **README.md**: This file, providing an overview of the project.  
- **ImagePredictionCapstone.ipynb**: The Jupyter Notebook containing my full analysis and modeling process.  

## Analysis and Modeling  
### Exploratory Data Analysis (EDA):  
- Examined the dataset to understand its structure.  
- Tested image overlay and took random images to perform  
- Hyperparameter tuninh
- Functions to take image, pedict, and confirm location of tumor.

### Data Cleaning and Preparation:  
- Transformed image data to ensure suitability for modeling.  

### Model Comparison:  
- Attempted 4 models: Linear Regression, Random Forest, SVR, & KNN.  
- Selected the best-performing model with PCA and evaluated RandomForrest using cross-validation.

### Final Model Testing:  
- Tested the final model by making predictions on unseen input data.  

## Results  
The final model demonstrated overfitting performance metrics, indicating moderate effectiveness in locating patterns of tumors. 

## Conclusion  
Regression is moderately successful at finding patterns from image value data, but better approaches are necessary to get better accuracy scores.

## How to Run the Notebook  
1. Clone the repository: `git clone [repository_url]`  
2. Navigate to the project directory: `cd [project_directory_name]`  
3. Open the Jupyter Notebook: `[Your_Notebook_Name].ipynb`  
4. Follow the steps in the notebook to replicate the analysis and modeling process.  

## Dependencies  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- Jupyter Notebook  

## Acknowledgements  
This project is based on an altered data set thanks to the following:
https://www.kaggle.com/datasets/gonzalorecioc/brain-tumor-images-with-tumor-location-coordinates/data
--- 
