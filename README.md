# datasci_9_data_prep


## Dataset #1
    This dataset contains information about electric vehicle registrations, including VIN, location, model details, and eligibility for Clean Alternative Fuel     Vehicle (CAFV).

### Intended Machine Learning Task:
    Predicting Clean Alternative Fuel Vehicle (CAFV) eligibility

### Data Cleaning and Transformation Steps:
  1. Handling Missing Values:
  2. Identify and handle missing values in relevant columns (e.g., Deaths, Age-adjusted Death Rate).
  3. Identify and handle outliers in numerical features, considering their impact on the target variable
  4. Convert categorical variables (e.g., 113 Cause Name, State) into numerical format using one-hot encoding or label encoding.
  5. Identify Variables:
      Dependent (Target) Variable: "Clean Alternative Fuel Vehicle (CAFV) Eligibility."
      Independent (Predictor) Variables: Features like "Model Year," "Make," "Model," "Electric Range," "Base MSRP,"
     
## Dataset #2
    The dataset contains mortality data with information such as the year, cause of death, state, number of deaths, and age-adjusted death rate.

### Intended Machine Learning Task:
    Regression - Predict the age-adjusted death rate based on various features.

### Data Cleaning and Transformation Steps:
  1. Handling Missing Values:
  2. Identify and handle missing values in relevant columns (e.g., Deaths, Age-adjusted Death Rate).
  3. Identify and handle outliers in numerical features, considering their impact on the target variable
  4. Convert categorical variables (e.g., 113 Cause Name, State) into numerical format using one-hot encoding or label encoding.
  5. Identify Variables:
      Dependent (Target) Variable: Age-adjusted Death Rate.
      Independent (Predictor) Variables: Year, Cause Name, State, Deaths.
