# Flight Price Prediction Model  

## [Live Application](https://flight-price-prediction-tool.streamlit.app/)  

## Overview  
This project involves building a machine learning model to predict flight ticket prices based on various features. Using **AWS SageMaker**, the model was trained with the **XGBoost** algorithm, utilizing advanced techniques like **hyperparameter tuning** and **feature engineering**. An **interactive Streamlit application** was created and deployed to enable users to predict flight prices seamlessly.  

## Project Highlights  
1. **Data Analysis and Cleaning**:  
   - Performed **data quality checks** to identify inconsistencies or errors in the dataset.  
   - Detected **missing values**, **outliers**, and **duplicated samples** in the dataset.  

2. **Exploratory Data Analysis (EDA)**:  
   - Performed **univariate**, **bivariate**, and **multivariate** analysis to understand data distributions and relationships between features.  
   - Conducted hypothesis testing and normality testing using a **custom EDA class**.  
   - Performed **correlation analysis** to identify relationships between features.  

3. **Feature Engineering**:  
   - Handled **missing values** and **outliers**.  
   - Extracted 43 features from the raw data.  
   - Selected 26 critical features using custom transformers and data pipelines for better model performance.  

4. **Model Training**:  
   - Used **AWS SageMaker** to train the model with the **XGBoost** algorithm.  
   - Optimized performance through hyperparameter tuning on an **EC2 instance**.  

5. **Deployment and Storage**:  
   - Stored datasets and the best model in an **S3 bucket** using **Boto3**.  
   - Deployed an interactive **Streamlit application** for user interaction on **Streamlit Community Cloud**.  

## Technologies Used  
- **Cloud Tools**: AWS SageMaker, EC2, S3, Boto3  
- **Libraries**: XGBoost, scikit-learn, Pandas, NumPy, Streamlit, Feature-engine, Matplotlib, Seaborn, SciPy  

