# 🚢 Titanic Data Cleaning & Exploratory Data Analysis (EDA)
---

# 📌 Project Overview
This project performs Data Cleaning and Exploratory Data Analysis (EDA) on the Titanic dataset from Kaggle.
The goal is to:

- Clean and preprocess raw data
- Explore relationships between variables
- Identify patterns affecting passenger survival
- Visualize trends using modern data visualization techniques

# 📂 Dataset Information
- Dataset: Titanic – Machine Learning from Disaster
- Source: Kaggle Competition
- The dataset contains information about passengers such as:

    - PassengerId
    - Survived (Target Variable)
    - Pclass (Passenger Class)
    - Name
    - Sex
    - Age
    - SibSp (Siblings/Spouses aboard)
    - Parch (Parents/Children aboard)
    - Ticket
    - Fare
    - Cabin
    - Embarked
      
# 🧹 Data Cleaning Steps

The following preprocessing steps were performed:
1. Handling Missing Values
Age → Filled with median value
Embarked → Filled with mode
Cabin → Dropped due to excessive missing values
2. Removing Duplicates
   
Checked and removed duplicate rows
3. Encoding Categorical Variables
Sex converted to numeric (0 = Male, 1 = Female)
Embarked encoded using One-Hot Encoding

4. Dropping Irrelevant Columns
- Name
- Ticket
- Cabin

# 📊 Exploratory Data Analysis (EDA)
🔹 1. Survival Distribution
Majority of passengers did not survive.
🔹 2. Survival by Gender
Females had a significantly higher survival rate than males.
🔹 3. Survival by Passenger Class
1st Class → Highest survival rate
3rd Class → Lowest survival rate
🔹 4. Age Distribution
Most passengers were between 20–40 years old.
🔹 5. Fare vs Survival
Passengers who paid higher fares had better survival chances.

# 🔥 Correlation Analysis
Quantitative Variables
A correlation heatmap was generated using numeric variables.
---

# Key findings:
- Strong correlation between Sex and Survival
- Moderate correlation between Pclass and Survival
- Fare positively correlated with Survival
- Qualitative Variables
- Chi-Square test was used to evaluate:
- Sex vs Survival
- Embarked vs Survival
- Results showed statistically significant relationships.

# 📈 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scipy

# 📌 Conclusion
This project demonstrates how data cleaning and exploratory analysis can reveal meaningful patterns in real-world datasets. Proper preprocessing and visualization are critical before applying machine learning models.

--- 

# 👩‍💻 Author
- Name: PRUONH KIMLIYA
- Email: kimliyapruonh@gmail.com
---


