# Day5
## Explorartory Data Analysis on titanic dataset 

## Project Overview:
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to understand passenger demographics, ticket classes, fares, and survival patterns. The analysis uses visualizations to explore relationships between categorical and numerical variables.

## Libraries used :
- Pandas – Data manipulation
- Matplotlib & Seaborn – Data visualization

## Steps performed :
1. Data loading and cleaning
- First i import the datset using pandas.
- Deal with null and missing values.
- Converted null values in appropriate for better analysis.
 
2. Univariate Analysis
- Count Plots for variables like Survived, Sex, and Pclass to see distribution.
- Histograms for Age and Fare to check data spread.

3. Bivariate Analysis
- Age vs Pclass (Barplot) – Found that average age was highest in 1st class and lowest in 3rd class.
- Pclass vs Fare split by Gender (Barplot) –
   - 1st class passengers paid the highest fares.
   - Women in 1st class paid slightly more on average than men.
   - In 2nd and 3rd class, fares for men and women were almost equal.
   
   
4. Multivariate Analysis
- Combined categorical and numerical variables to find patterns, such as differences in fares and ages across gender and passenger class.

## Key Insights 
- Class & Age: 1st class had older passengers on average, 3rd class had younger passengers.
- Class & Fare: Higher class meant higher ticket prices, especially in 1st class.
- Gender & Fare: In 1st class, women paid slightly more than men; no major difference in other classes.
- Socio-economic Effect: Richer passengers (1st class) had a different demographic compared to lower classes.
- Higher fares are mostly paid by 1st class passengers, and many of them survived.Lower fares are linked to the 3rd class passengers , and survival rate seems much lower . 2nd class fares are in between and have a mixed survival rate. Overall, passengers who paid higher fare had a better chance of survival.

