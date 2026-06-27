# Titanic_Survival-
Titanic Survival data this project gives report for different trend on different data via charts and graphs.
# Titanic Data Visualization 🚢

An Exploratory Data Analysis (EDA) and visualization project using the **Kaggle Titanic dataset** in **Jupyter Notebook**. This project focuses on identifying core demographic and survival trends using **Pandas** for data manipulation and **Matplotlib's Object-Oriented API** for visualization, completely avoiding Seaborn.

## 📊 Core Features

* **Data Profiling & Cleaning:** Explores dataset structures using `.head()`, `.info()`, and `.describe()`. Handles missing data via median/mode imputation and isolates critical features.
* **Unified Dashboard Layout:** Generates a 3-figure analytical dashboard in a single visual space using the object-oriented `plt.subplots()` pipeline:
  * **Bubble Chart:** Evaluates Age vs. Fare Paid, using variable bubble sizes to represent different Passenger Classes.
  * **Line Chart:** Tracks the average fare distribution trend relative to passenger age.
  * **Stacked Bar Chart:** Summarizes survival counts broken down by 1st, 2nd, and 3rd-class tickets.

## 🛠️ Built With

* **Python 3**
* **Jupyter Notebook**
* **Pandas** (Data wrangling)
* **Matplotlib** (Object-oriented custom plotting)
