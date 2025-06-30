# Adult Income Logistic Regression Project

This project is an initiative to learn and apply machine learning algorithms and concepts commonly used in data science. Using a public dataset from Kaggle containing features such as salary ranges, job types, nationality, gender, age, and other demographic factors, the project aims to predict whether an individual's income exceeds $50,000 per annum.

## Dataset Information

The dataset used in this project is the [Adult Income Dataset](https://www.kaggle.com/datasets/wenruliu/adult-income-dataset) from Kaggle. It contains demographic and employment-related information for more than 48,000 individuals. The data is arranged in a tabular format, with each row representing a person and each column representing a feature or attribute.

### Columns in the Dataset
- **age:** Age of the individual
- **workclass:** Type of employment (e.g., Private, Self-emp, Government)
- **fnlwgt:** Final weight (a statistical weight assigned to the person)
- **education:** Highest level of education achieved
- **education-num:** Number of years of education
- **marital-status:** Marital status
- **occupation:** Type of occupation
- **relationship:** Relationship status (e.g., Husband, Wife, Not-in-family)
- **race:** Race of the individual
- **sex:** Gender
- **capital-gain:** Capital gains
- **capital-loss:** Capital losses
- **hours-per-week:** Hours worked per week
- **native-country:** Country of origin
- **income:** Target variable (<=50K or >50K)

## Downloading the Dataset

To download and use the dataset in your local environment:

1. Go to the [Kaggle dataset page](https://www.kaggle.com/datasets/wenruliu/adult-income-dataset).
2. Click on the **Download** button to download the dataset as a ZIP file.
3. Extract the ZIP file to obtain the CSV files (e.g., `adult.csv`).
4. Move the CSV file into your project directory. For best practice, you can place it inside the `venv` folder or a dedicated `data` folder within your project directory.

   Example structure:
   ```
   project-root/
   ├── venv/
   ├── data/
   │   └── adult.csv
   └── ...
   ```

## Key Steps

- **Exploratory Data Analysis (EDA):**  
  The `pandas` library was used extensively for data loading, cleaning, and exploratory data analysis to understand the dataset and identify important features. This included:
  - Checking for missing values and outliers
  - Analyzing the distribution of categorical and numerical variables
  - Visualizing relationships between features and the target variable (`income`)
  - Identifying correlations and feature importance

- **Data Preprocessing:**  
  Data was cleaned and transformed, including handling missing values and applying one-hot encoding to categorical variables.

- **Predictive Analysis:**  
  The logistic regression algorithm was implemented to perform predictive analysis, estimating the probability of an individual's income being above or below $50,000 per year.

- **Visualization:**  
  Results and insights were visualized using `seaborn` and `matplotlib` libraries.

## Technologies Used

- Python
- pandas
- scikit-learn (for logistic regression)
- seaborn & matplotlib (for visualization)

## Setting Up a Virtual Environment and Running Jupyter Notebook

To ensure a clean and isolated Python environment for this project, follow these steps:

1. **Create a Virtual Environment**
   ```powershell
   python -m venv venv
   ```
   This will create a folder named `venv` in your project directory.

2. **Activate the Virtual Environment**
   ```powershell
   .\venv\Scripts\Activate
   ```
   You should see `(venv)` at the beginning of your terminal prompt, indicating the environment is active.

3. **Check if Jupyter Notebook is Already Installed**
   ```powershell
   jupyter --version
   ```
   If Jupyter is installed, this command will display the version number. If not, proceed to the next step to install it.

4. **Install Jupyter Notebook (if needed)**
   ```powershell
   pip install jupyter
   ```

5. **Open Jupyter Notebook**
   ```powershell
   jupyter notebook
   ```
   This will launch the Jupyter Notebook interface in your default web browser.
