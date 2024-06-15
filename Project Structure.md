# Heart Disease Analysis Project

This project involves a comprehensive analysis of a heart disease dataset to uncover key insights that can inform clinical decision-making and future research. The analysis includes exploratory data analysis (EDA), statistical tests, and machine learning model evaluation.

## Project Structure

```
heart-disease-analysis/
├── data/
│   ├── raw/
│   │   └── heart_disease_data.csv
│   ├── processed/
│   │   └── heart_disease_cleaned.csv
├── notebooks/
│   ├── 01_data_preprocessing.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_statistical_tests.ipynb
│   ├── 04_model_training_evaluation.ipynb
├── scripts/
│   ├── data_preprocessing.py
│   ├── eda.py
│   ├── statistical_tests.py
│   ├── model_training.py
│   ├── model_evaluation.py
├── reports/
│   ├── figures/
│   │   ├── age_distribution.png
│   │   ├── cholesterol_distribution.png
│   │   ├── correlation_matrix.png
│   │   ├── feature_importance.png
│   ├── clinical_report.pdf
│   └── README.md
├── .gitignore
├── README.md
├── requirements.txt
└── setup.py
```

### Directories and Files

1. **data/**
    - **raw/**: Contains the original dataset (`heart_disease_data.csv`).
    - **processed/**: Contains the cleaned and preprocessed dataset (`heart_disease_cleaned.csv`).

2. **notebooks/**
    - **01_data_preprocessing.ipynb**: Jupyter notebook for data cleaning and preprocessing.
    - **02_exploratory_data_analysis.ipynb**: Jupyter notebook for exploratory data analysis (EDA).
    - **03_statistical_tests.ipynb**: Jupyter notebook for performing statistical tests.
    - **04_model_training_evaluation.ipynb**: Jupyter notebook for training and evaluating machine learning models.

3. **scripts/**
    - **data_preprocessing.py**: Script for data cleaning and preprocessing.
    - **eda.py**: Script for performing exploratory data analysis.
    - **statistical_tests.py**: Script for conducting statistical tests.
    - **model_training.py**: Script for training machine learning models.
    - **model_evaluation.py**: Script for evaluating machine learning models.

4. **reports/**
    - **figures/**: Contains figures and plots generated during the analysis.
        - **age_distribution.png**: Age distribution plot.
        - **cholesterol_distribution.png**: Cholesterol distribution plot.
        - **correlation_matrix.png**: Correlation matrix heatmap.
        - **feature_importance.png**: Feature importance plot.
    - **clinical_report.pdf**: Final clinical report summarizing the analysis and findings.
    - **README.md**: Report-specific README file.

5. **.gitignore**: Specifies files and directories to be ignored by Git.
6. **README.md**: Project README file with an overview and instructions.
7. **requirements.txt**: List of Python dependencies required for the project.
8. **setup.py**: Script for installing the project as a package.

### Detailed Steps

1. **Data Preprocessing**
    - Load the raw dataset.
    - Handle missing values, outliers, and erroneous data.
    - Normalize or standardize features as necessary.
    - Save the cleaned dataset to `data/processed/heart_disease_cleaned.csv`.

2. **Exploratory Data Analysis (EDA)**
    - Generate summary statistics for each feature.
    - Create visualizations (e.g., histograms, box plots, scatter plots) to understand data distributions and relationships.
    - Identify and visualize correlations between features using a correlation matrix.
    - Save figures to `reports/figures/`.

3. **Statistical Tests**
    - Perform t-tests and chi-square tests to identify significant differences and associations between variables.
    - Conduct ANOVA to assess the effect of multiple variables on the target.
    - Document the results and interpretations of the statistical tests.

4. **Machine Learning Model Training and Evaluation**
    - Split the cleaned dataset into training and testing sets.
    - Train various machine learning models (e.g., Logistic Regression, Decision Tree, Random Forest, SVM).
    - Evaluate model performance using metrics such as accuracy, precision, recall, F1 score, and ROC AUC.
    - Identify the best-performing model based on the evaluation metrics.
    - Save model performance results and feature importance plots.

5. **Report Generation**
    - Compile the findings from EDA, statistical tests, and model evaluation into a comprehensive clinical report.
    - Include key visualizations and interpretations to support the findings.
    - Save the report as `clinical_report.pdf` in the `reports/` directory.

### Installation and Usage

1. **Clone the Repository**

    ```
    git clone https://github.com/yourusername/heart-disease-analysis.git
    cd heart-disease-analysis
    ```

2. **Install Dependencies**

    ```
    pip install -r requirements.txt
    ```

3. **Run Notebooks**

    - Open and run the Jupyter notebooks in the `notebooks/` directory to execute each step of the analysis.

4. **Run Scripts**

    - Alternatively, run the scripts in the `scripts/` directory to perform the analysis steps programmatically.

5. **Generate Report**

    - Ensure all analysis steps are completed and figures are saved.
    - Compile the final clinical report using the provided templates and interpretations.

### Contributions

Contributions are welcome! Please submit a pull request or open an issue to discuss potential improvements or additions to the project.

### License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

This structured project organization ensures clarity and ease of use, facilitating seamless collaboration and reproducibility of the analysis.
