# Movie-Analysis
A data analysis project exploring key factors that influence a movie's box office success. The purpose of this project is to discover what attributes correspond with profitable movies. This promotes an understanding of what makes a successful movie, which could be useful for those in the entertainment industry.

## Research Questions
1. Does a movie's budget affect its success?
2. Does the majority of profit come domestically or internationally?
3. Do shorter movie titles make more money?
4. Does release season affect box office performance?
5. Which genre has the most influence on a movie's success?

## Dataset
This project uses the [Movie Dataset for Analytics and Visualization](https://www.kaggle.com/datasets/mjshubham21/movie-dataset-for-analytics-and-visualization) from Kaggle. This is a synthetic dataset containing 999,999 rows and 17 columns​. Movies span from 1950 through 2025​ and across 8 genres​.
<img width="1795" height="476" alt="dataset ds final proj" src="https://github.com/user-attachments/assets/b17568cb-73a0-4bcb-b6c7-783a69f9f828" />

## Methods
Here are the tools used to complete the project:
- Pandas (dataframe access and manipulation)
- Matplotlib​ (plotting)
- Seaborn (plotting)
- Scikit-learn​ (Regression)
- statsmodels ​(ANOVA)
- Colab​ (Python coding software)
- GitHub Repository (organization and README)

## Results
1. Does a movie's budget affect its success?​​ Budget strongly predicts both U.S. and global revenue, though hypothesis testing results differed between the two models. It is likely that a higher budget​ corresponds with higher global box office earnings. However, the relationship between budget and U.S. earnings is not statistically significant enough to imply that there is an effect.
<img width="683" height="627" alt="ds final" src="https://github.com/user-attachments/assets/ee9d1624-925c-4f33-b121-5202b184d02d" />

2. Does most profit come domestically or internationally?​​ 67 percent of American-made movies earned more profit domestically than internationally. It can be inferred that domestic profit is commonly greater than international profit.​
<img width="1547" height="322" alt="ds final2" src="https://github.com/user-attachments/assets/0b05e710-e610-4d10-a2d6-8abbdb2d1f38" />

3. Do shorter movie titles make more money?​​ A one-way ANOVA test comparing movies title lengths grouped by every 5 characters (1-5, 6-10, ..., 41-45) shows that there is no statistical evidence that says so. ​
<img width="720" height="72" alt="Screenshot 2026-04-08 134841" src="https://github.com/user-attachments/assets/6cde3e7b-70df-476f-9576-44f178547419" />

4. Does release season affect box office performance?​​ A one-way ANOVA test using movies grouped by release month says there is no statistical evidence that says so. ​
<img width="671" height="73" alt="Screenshot 2026-04-08 134914" src="https://github.com/user-attachments/assets/0564f489-5367-4aea-9920-d6efbbaad7d7" />

5. Which genre has the most influence on a movie's success?​​ The Drama/Documentary genres have the most profit on average.
<img width="1139" height="767" alt="Screenshot 2026-04-08 134451" src="https://github.com/user-attachments/assets/d7bce8e0-ef50-4541-8da1-8472cb6ab8bf" />

## Discussion
Many factors showed no statistically significant impact​. Due to the data being randomly generated, the lack of statistically significant relationships suggests that the dataset may not reflect real-world movie dynamics. 

## Summary
Assuming that the dataset is an appropriate measure of real-life movie box office earnings, one may conclude that the most successful movies consist of the following characteristics:
- Large budget
- Main source of earning is domestic
- Drama or Documentary genre

## Authors
Abia Hasan, Eoin Darlington, Meta Klatzke
