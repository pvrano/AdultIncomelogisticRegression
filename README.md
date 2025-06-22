# Adult Income Logistic Regression Project

This project is an initiative to learn and apply machine learning algorithms and concepts commonly used in data science. Using a public dataset from Kaggle containing features such as salary ranges, job types, nationality, gender, age, and other demographic factors, the project aims to predict whether an individual's income exceeds $50,000 per annum.

## Key Steps

- **Exploratory Data Analysis (EDA):**  
  The `pandas` library was used extensively for data loading, cleaning, and exploratory data analysis to understand the dataset and identify important features.

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
