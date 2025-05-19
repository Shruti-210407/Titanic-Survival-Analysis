• Task 5: Exploratory Data Analysis (EDA) 
• Objective: Extract insights using visual and statistical exploration.

ABOUT THE DATA: 
The Titanic Passenger dataset provides information about passengers who were aboard the RMS Titanic during its ill-fated maiden voyage. This dataset is often used for exploring patterns and factors associated with survival on the Titanic.
PassengerId: Unique identifier for each passenger.
Survived: Survival status of the passenger (0 = Not Survived, 1 = Survived).
Pclass: Passenger class (1 = First class, 2 = Second class, 3 = Third class).
Sex: Gender of the passenger.
Age: Age of the passenger.
SibSp: Number of siblings/spouses aboard the Titanic.
Parch: Number of parents/children aboard the Titanic.
Fare: Fare paid by the passenger.
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

APPROACH TO EXPLORATORY DATA ANALYSIS: 
1. Download the dataset from Kaggle. 
2. Create a new file named Titanic_Data Jupyter into the Notebook.
3. Import pandas, matplotlib, seaborn, NumPy into the Notebook
4. Import the xlsx data file using pandas.
5. Perform Basic data exploration. 
• What kind of data do we have? 
• How many rows/columns are there? 
• Are there any missing values? 
• What are the numerical distributions? 
6. Fill the null values using mode, mean etc.
7. Perform Basic data cleaning on the dataset. 
8. Plot charts using imported libraries. 
9. Understand Insights of the visualization output. 
10. Create a Report of the EDA.

CONCLUSION
There was a significantly higher survival rate among females compared to males, highlighting the impact of the "women and children first" evacuation policy. Passenger class also played a crucial role in survival, with those in first class having much higher chances of survival than those in second or third class. The fare and age distributions further suggest that wealthier and likely older passengers tended to be in higher classes, which correlated with better survival odds. The boxplot and violin plots show that survivors generally paid higher fares, indicating that they belonged to upper classes. Embarkation port analysis showed that most passengers boarded at Southampton, but the survival rate varied across ports. The scatter plot of Age vs Fare showed clustering of survivors in certain fare ranges, especially among younger individuals. The correlation heatmap revealed modest correlations between survival and features like class, fare, and number of siblings/spouses.
Overall, the data and visualizations collectively suggest that gender, socio-economic status, and class were the strongest indicators of survival on the Titanic.

