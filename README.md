# Elevate_Task2
xploratory Data Analysis (EDA) on Titanic Dataset
This analysis focuses on understanding the distribution, relationships, and anomalies in the Titanic dataset. The goal was to derive insights from the data using visual and statistical tools.

Tasks Performed
1. Summary Statistics (Mean, Median, Std Dev, etc.)
To understand the central tendency and spread of numerical variables, we computed:

Mean: Average values give us a quick idea of central values.

Median: Useful in identifying skewed distributions (more robust to outliers).

Standard Deviation (std): Measures how spread out the data is.

These were calculated for columns such as:

Age , Fare , Pclass , SibSp , Parch

🔍 Key Findings:

Fare has a high standard deviation, indicating large variation in ticket prices.

Age distribution is slightly skewed; younger passengers are more common.

2. Histograms and Boxplots for Numeric Features
Histograms were created for all numerical features to visualize their frequency distributions. Boxplots were used to identify outliers and compare medians across features.

📌 Visual Insights:

Fare has a right-skewed distribution with many extreme values (outliers).

Age shows a concentration around young adults but includes all age ranges.

SibSp and Parch are heavily concentrated at zero, indicating most passengers traveled alone or with few family members.

3. Pairplot and Correlation Matrix
We used Seaborn’s pairplot and a heatmap of the correlation matrix to explore relationships between features.

🔗 Correlation Matrix:

Positive correlation between SibSp and Parch: passengers with siblings often had parents or children with them.

Slight negative correlation between Pclass and Fare: higher-class tickets were more expensive.

Survived had moderate correlations with Sex, Fare, and Pclass.

4. Identifying Patterns, Trends, and Anomalies
Through visual and statistical methods, the following were observed:

High-class passengers (Pclass = 1) had better survival rates.

Females had significantly higher survival rates compared to males.

Passengers who paid more (Fare) tended to survive more often.

Boxplots revealed clear outliers in Fare and Age.

5. Basic Feature-Level Inferences
From the visuals and statistics:

Survival is not random: Strong dependency on Sex, Pclass, and Fare.

Traveling with family (non-zero SibSp/Parch) had mixed outcomes—helpful in some contexts but not in others.

Embarkation point (Embarked) showed differing survival rates, with ‘C’ (Cherbourg) having higher than average.

📌 Conclusion
This exploratory analysis revealed meaningful patterns in the Titanic dataset that are vital for further predictive modeling. Visual tools like histograms, boxplots, pairplots, and heatmaps, combined with statistical summaries, provide a solid foundation for feature selection and hypothesis generation.
