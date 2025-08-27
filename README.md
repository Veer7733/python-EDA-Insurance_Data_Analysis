# python-EDA-Insurance_Data_Analysis
It's a exploratory data analysis for An insurance agency.

# Insurance Data Analysis

## Project Description
An insurance agency, ABC Insurance, has a large dataset containing information about their policyholders and claims. They want to perform exploratory data analysis (EDA) on this dataset to gain insights that can help them make better business decisions and improve their operations.

## Objective
To analyze the dataset that will help to create a model that will predict the cost of medical insurance based on various input features

## Dataset
- Source: ABC Insurance
- Key Columns:
  - `age`: Age of the policyholder
  - `sex`: Gender
  - `bmi`: Body Mass Index
  - `children`: Number of dependents
  - `smoker`: Smoker or non-smoker
  - `region`: Residential area
  - `charges`: Insurance premium (target variable)
- Number of rows/columns: rows -> ~1500 , columns -> 7

## Tools & Libraries
- Python 3.12.7
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Steps Performed
1. Imported libraries and loaded the dataset.
2. Checked dataset shape, data types, and missing values.
3. Performed univariate analysis:
   - Histograms/countplot for numerical columns
   - Count plots for categorical columns
4. Conducted bivariate analysis:
   - Scatter plots and boxplots for feature vs target
5. Feature vs feature visualizations to explore relationships.
6. Trend analysis:
   - Examined how charges for smokers/non-smokers change with age.
7. Recorded observations and insights after each step.

## Observations / Insights
- Insurance charges generally increase with age.
- Smokers have higher premiums than non-smokers.
- Insurance charges above 40,000 for policyholders older than 30 are higher (possibly due to smoking or other factors). 
- The normal BMI criteria is ~22 to ~48.
-  Here, in southeast region some of people paying higher insurance compare to all other regions.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Veer7733/python-EDA-Insurance_Data_Analysis
   ``` 
2. Navigate to the project folder:
   ```bash
   cd python-EDA-Insurance_Data_Analysis
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Insurance_Data_Analysis.ipynb
   ```

