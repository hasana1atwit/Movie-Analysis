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

## Results
1. Does a movie's budget affect its success?​​ Budget strongly predicts both U.S. and global revenue, though hypothesis testing results differed between the two models. It is likely that a higher budget​ corresponds with higher global box office earnings. However, the relationship between budget and U.S. earnings is not statistically significant enough to imply that there is an effect.

2. Does most profit come domestically or internationally?​​ 67 percent of American-made movies earned more profit domestically than internationally. It can be inferred that domestic profit is commonly greater than international profit.​

3. Do shorter movie titles make more money?​​ A one-way ANOVA test comparing movies title lengths grouped by every 5 characters (1-5, 6-10, ..., 41-45) shows that there is no statistical evidence that says so. ​

4. Does release season affect box office performance?​​ A one-way ANOVA test using movies grouped by release month says there is no statistical evidence that says so. ​

5. Which genre has the most influence on a movie's success?​​ The Drama/Documentary genres have the most profit on average.

## Discussion
Many factors showed no statistically significant impact​. Due to the data being randomly generated, the lack of statistically significant relationships suggests that the dataset may not reflect real-world movie dynamics. 

## Summary
Assuming that the dataset is an appropriate measure of real-life movie box office earnings, one may conclude that the most successful movies consist of the following characteristics:
- Large budget
- Main source of earning is domestic
- Drama or Documentary genre

## Authors
Abia Hasan, Eoin Darlington, Meta Klatzke
