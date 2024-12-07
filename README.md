# Impact of Workplace Factors on Mental Health  

This project investigates the factors contributing to mental health challenges in the tech industry, focusing on the impact of workplace conditions on employees' decisions to seek treatment. Developed for a Data Science Principles class, this study uses Python for data preprocessing, visualization, and predictive modeling.  

## 📂 Contents  

- **`Google Colab.pdf`**: Full export of the Google Colab notebook used for this project.  
- **`The impact of workplace factors on mental health.py`**: Python script containing all the analysis and modeling code.  
- **`Full report.pdf`**: Comprehensive report detailing the findings and their implications.  

## 🛠️ Tools Used  

- **Python**  
  - Libraries: `pandas`, `seaborn`, `matplotlib`, `scikit-learn`, `numpy`  
- **Google Colab**  

## 📊 Analysis Steps  

### 1. Data Cleaning  
- Dataset: [OSMI Mental Health in Tech Survey](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey).  
- Removed irrelevant columns (e.g., country, state, comments).  
- Filtered and standardized age and gender entries.  
- Handled missing values for categorical variables (`self_employed`, `work_interfere`).  

### 2. Visualization  
- Bar and stacked bar charts highlight trends like family history, work interference, and employer-provided mental health resources.  
- A correlation matrix heatmap identifies key predictors for treatment-seeking behavior.  

### 3. Predictive Modeling  
- **Goal**: Predict whether an individual seeks mental health treatment.  
- **Models Evaluated**: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, and SVM.  
- **Key Insights**:  
  - Work interference and employer-provided mental health benefits significantly impact treatment decisions.  
  - The Decision Tree model (82.5% accuracy) provided the most interpretable results.  

## 🔍 Findings  

- **Work Interference**: Strongest predictor of treatment-seeking behavior.  
- **Employer Support**: Awareness of benefits and care options positively influences decisions.  
- **Practical Implications**: Encourages tech companies to enhance mental health resources and workplace policies to improve employee well-being and productivity.  

## 🎯 Purpose  

This project demonstrates my ability to clean and analyze complex datasets, visualize insights, and build predictive models. It also reflects the importance of fostering mental health awareness in the workplace.  

## 💡 How to Use  

- Explore `Google Colab.pdf` to see the complete notebook export.  
- Check out `The impact of workplace factors on mental health.py` for the Python code used in this project.  
- Refer to the `Full report.pdf` for an in-depth explanation of findings and their implications.  

Feel free to fork this repository, explore the files, or share feedback to improve the project!  

---  
