#### The goal of this assignment was to perform basic inferential statistics using google colab. To find what certain relationships and differences in health metrics and demographics which and the five questions below are the results of the relationships and differences.



1. "Is there an association between marital status (married or not married) and education level (bachelor’s degree or higher vs. less than a bachelor’s degree)?"


- The first thing that was done was check the chi-squared statistic which measures difference between observed and expected frequencies. Large value expects to have a strong association and the result was 199.6.
- The next thing that was reviewed was the p-value which indicates the probability of observing an association by chance. Anything less than 0.05 suggests a significant association the result was 0.00.
- We also needed the degrees of freedom (dof) since that is used to calculate chi-squared statistic the dof was 20.
- And last was the expected frequency table which shows the frequencies we would expect in each cell if there was no association.


2. "Is there a difference in the mean sedentary behavior time between those who are married and those who are not married?"


- The first thing we did was find out how many individuals were married and how many were non married. There were 4135 individuals that were married and 4003 were not.
- 15 missing values were identified from PAD680 and removed from the dataset to ensure data quality for analysis.
- A t-test was then conducted comparing behavior between married and non married groups it resulted in t-statistic of -2.70 and p-value 0.007. Which showed a significant difference in mean sendentary behavior time between married and non married.
- A boxplot showed the visual disaparities.


3. "How do age and marital status affect systolic blood pressure?"


- The first thing that was done was check the r-squared where model explained that approximately 27.8% of the variance in the systolic blood pressure suggest age and maritial status together are significant but isn't the sole predictor.
- Next thing that was found is that age was 0.4305 with the p-value of 0.00 which is significant. For every one year increase in age, the mean in systolic blood pressure is predicted to increase 0.4305 mmHg which holds the maritial status constant. It shows that age is a strong predictor of systolic blood pressure.
- The other finding was the maritial status where the coefficient for not married was 1.0450 with a p-value of 0.007 which is significant. This then shows that those who are not married have a mean systolic blood pressure about 1.0450 mmHg higher than those who are married when controlling age.
- Visually the scatter plot showed mean systolic blood pressure by age and maritial status.
- The box plot compared mean systolic blood pressure by maritial status.


4. "Is there a correlation between self-reported weight and minutes of sedentary behavior?"


- The first thing is to get rid of any missing value and there were about 15 missing values for PAD680 and WHD020. 
- The correlation coefficient between the two was 0.07.
- Visually the scatter plot shows the correlation and relationship between self-reported wight and sendentary behavior. There is a very weak positive linear relationship.


5. "Is there a correlation between weak/failing kidneys and age in years?"


- The first thing to do was split it up into two different groups of where there is failing kidneys and there isn't failing kidneys. with them being 321 are failing and 7486 not failing.
- The correlation coefficient between the two was 0.14.
- Visually a box plot was used to visualize the age distribution by kidney issue status. There was a weak positive linear relationship.