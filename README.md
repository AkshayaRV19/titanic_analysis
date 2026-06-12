# Titanic Dataset Analysis

## Data Science with Python Internship – Task 2

### Project Overview

This project analyzes the Titanic dataset to identify survival patterns among passengers. The analysis focuses on factors such as gender, passenger class, and age group, along with data visualization using Python libraries.

### Objectives

* Load and explore the Titanic dataset.
* Handle missing values in the dataset.
* Analyze survival rates based on:

  * Gender
  * Passenger Class
  * Age Group
* Create visualizations to understand survival patterns.
* Draw meaningful insights from the data.

### Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

### Dataset

The dataset used in this project is the Titanic Dataset from Kaggle.

Dataset Features:

* PassengerId
* Survived
* Pclass
* Name
* Sex
* Age
* SibSp
* Parch
* Ticket
* Fare
* Cabin
* Embarked

### Data Cleaning

The following preprocessing steps were performed:

* Checked for missing values.
* Replaced missing values in the Age column using the mean age.
* Verified data quality after cleaning.

### Analysis Performed

#### 1. Survival Rate by Gender

* Female survival rate: 74.20%
* Male survival rate: 18.89%

**Observation:** Female passengers had a significantly higher survival rate than male passengers.

#### 2. Survival Rate by Passenger Class

| Passenger Class | Survival Rate |
| --------------- | ------------- |
| First Class     | 62.96%        |
| Second Class    | 47.28%        |
| Third Class     | 24.24%        |

**Observation:** First-class passengers had the highest survival rate.

#### 3. Passenger Age Distribution

A histogram was created to visualize the distribution of passenger ages.

**Observation:** Most passengers were between 20 and 40 years old.

#### 4. Survival Rate by Age Group

| Age Group   | Survival Rate |
| ----------- | ------------- |
| Child       | 57.97%        |
| Teen        | 41.05%        |
| Young Adult | 35.29%        |
| Adult       | 40.00%        |
| Senior      | 22.73%        |

**Observation:** Children had the highest survival rate, while senior passengers had the lowest.

### Visualizations

The project includes:

1. Bar Chart – Survival Rate by Gender
2. Bar Chart – Survival Rate by Passenger Class
3. Histogram – Passenger Age Distribution
4. Bar Chart – Survival Rate by Age Group

### Key Findings

* Female passengers were more likely to survive than male passengers.
* Passenger class significantly affected survival chances.
* First-class passengers had the highest survival rate.
* Most passengers were young adults.
* Children had better survival chances than older passengers.

### Conclusion

The analysis demonstrates that gender, passenger class, and age were important factors influencing survival during the Titanic disaster. Data visualization helped uncover clear patterns and insights from the dataset.

---

**Author:** Akshaya R
**Internship:** Data Science with Python Internship
**Task:** Titanic Dataset Analysis (Task 2)
