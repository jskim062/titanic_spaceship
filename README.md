# Spaceship Titanic - Top 6% Solution (2024 Edition)  
  
This project is an updated version of the [Spaceship Titanic - Top 6% for Beginners](https://www.kaggle.com/code/lazer999/spaceship-titanic-top-6-for-beginners) Kaggle notebook, refactored for the latest Python and machine learning library versions.  
  
---  
  
## Project Overview  
  
- **Spaceship Titanic** is a Kaggle competition to predict whether passengers were transported to another dimension, based on various onboard features.  
- This notebook guides beginners through data cleaning, exploratory data analysis (EDA), feature engineering, modeling, and prediction.  
  
---  
  
## Updates & Improvements  
  
- Compatible with Python 3.10+ and the latest versions of `pandas`, `scikit-learn`, and other key libraries.  
- Uses modern APIs such as `SimpleImputer`, `OneHotEncoder`, and `Pipeline`.  
- Improved visualizations and code clarity.  
- Works seamlessly on Jupyter Notebook and Google Colab.  
  
---  
  
## Requirements  
  
- Python 3.10+  
- pandas >= 2.0  
- numpy >= 1.24  
- matplotlib >= 3.7  
- seaborn >= 0.12  
- scikit-learn >= 1.3  
- xgboost >= 1.7 (optional)  
  
All requirements are listed in `requirements.txt`.  
  
---  
  
## Repository Structure  
  
```plaintext  
SpaceshipTitanic/  
├── README.md                # Project description  
├── spaceship_titanic.ipynb  # Main notebook  
├── train.csv                # Kaggle train data  
├── test.csv                 # Kaggle test data  
├── submission.csv           # Prediction output for submission  
└── requirements.txt         # Library dependencies  

  
---  
---  
  
## Usage  
  
1. **Install dependencies**  
    ```bash  
    pip install -r requirements.txt  
    ```  
  
2. **Download data**  
    - Get `train.csv` and `test.csv` from [Kaggle Spaceship Titanic](https://www.kaggle.com/competitions/spaceship-titanic/data)  
    - Place them in the project folder  
  
3. **Run the notebook**  
    - Open `spaceship_titanic.ipynb` in Jupyter Notebook or Google Colab  
    - Execute the cells step by step  
  
4. **Generate submission**  
    - The notebook will create `submission.csv` for Kaggle submission  
  
---  
  
## Main Steps  
  
- **EDA**    
  Analyze feature distributions, handle missing values, visualize relationships  
  
- **Feature Engineering**    
  Impute missing data, encode categorical variables, create new features  
  
- **Modeling**    
  Train models such as RandomForest and XGBoost  
  
- **Evaluation**    
  Use cross-validation and hyperparameter tuning for performance improvement  
  
- **Prediction**    
  Export results for Kaggle submission  
  
---  
  
## References  
  
- Original Kaggle notebook: [Spaceship Titanic - Top 6% for Beginners](https://www.kaggle.com/code/lazer999/spaceship-titanic-top-6-for-beginners)  
- Kaggle competition: [Spaceship Titanic](https://www.kaggle.com/competitions/spaceship-titanic/overview)  
- Library documentation:  
    - [scikit-learn](https://scikit-learn.org/stable/whats_new/v1.3.html)  
    - [pandas](https://pandas.pydata.org/docs/)  
  
---  
  
## License  
  
This project is open source and free to use for educational and research purposes.  
  
---  
  
For questions or suggestions, please open an issue!  
  
