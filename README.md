# Analysis-of-Police-Stops
An Exploratory Data Analysis (EDA) on police.csv Dataset

Project Overview
This project involves an exploratory data analysis (EDA) of the police.csv dataset, which contains information about police stops, including details on driver demographics (age, gender, race) and the outcomes of these stops (e.g., citations, warnings, arrests). The dataset spans various stop types and violations, aiming to uncover patterns and potential disparities in law enforcement activities.

Dataset
The dataset police.csv includes the following key columns:

stop_date: Date of the stop
stop_time: Time of the stop
county_name: Name of the county where the stop occurred (note: this column is entirely missing)
driver_gender: Gender of the driver
driver_age_raw: Raw driver age data
driver_age: Cleaned and processed driver age data
driver_race: Race of the driver
violation_raw: Raw violation data
violation: Processed violation data
search_conducted: Whether a search was conducted
search_type: Type of search conducted
stop_outcome: Outcome of the stop (e.g., Citation, Warning, Arrest)
is_arrested: Whether the driver was arrested
stop_duration: Duration of the stop
drugs_related_stop: Whether the stop was related to drugs
Installation and Setup
To run the analysis on your local machine, you will need to have the following software installed:

Python (version 3.6 or higher)
Jupyter Notebook or any Python IDE (such as PyCharm or VS Code)
Required Python libraries: numpy, pandas, seaborn, matplotlib, scipy
You can install the necessary libraries using pip:

bash
Copy code
pip install numpy pandas seaborn matplotlib scipy
Running the Analysis
Clone the repository or download the files to your local machine.
Open the Jupyter Notebook or Python script containing the analysis.
Ensure the police.csv dataset is in the same directory as your notebook/script.
Run the cells/lines of code sequentially to perform the EDA.
Analysis Steps
The analysis consists of several key steps:

Importing Libraries: Importing necessary Python libraries for data manipulation, visualization, and analysis.
Data Import and Initial Exploration: Loading the dataset and exploring its structure using .head() and .tail() methods.
Exploratory Data Analysis (EDA):
Summary Statistics: Generating summary statistics for numerical and categorical columns to understand the data distribution.
Missing Values Analysis: Identifying and visualizing missing data to assess its distribution across the dataset.
Data Distribution and Visualization: Using histograms, box plots, and count plots to visualize the distribution of numerical and categorical data.
Correlation Analysis: Examining correlations between numerical features using a heatmap.
Date Conversion: Converting date columns to numerical formats for easier analysis.
Outlier Detection: Identifying outliers using box plots and Z-scores.
Univariate and Bivariate Analysis: Conducting both univariate and bivariate analysis to explore relationships within the data.
Data Preprocessing: Handling missing values, outliers, and transforming features as needed.
Results
The EDA uncovers various insights into the police stop data, such as:

The distribution of driver demographics and violation types.
The correlation between different features.
The identification of potential outliers and missing data issues.
Contributions
This project was completed by Sama Amr as part of an assignment to practice and demonstrate proficiency in data analysis using Python.

License
This project is open for educational purposes. If you use this code, please give appropriate credit.

Contact
For any questions or further collaboration, please reach out to Sama Amr via LinkedIn or email.
