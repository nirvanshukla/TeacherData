## ReadMe Summary: Data Science Capstone Project

### Project Overview  
This capstone project explores student evaluation data to analyze trends and biases in professor ratings. By applying advanced statistical and machine learning techniques, the study provides insights into gender-based differences, tag relevance, and predictors of professor ratings and difficulty.

---

### Files

- IDSCapstoneCode will contain the code utilized for this project.
- IDS_Capstone_Projects will contain the write-up for the project. 



---

### Key Objectives and Methods  

1. **Data Preprocessing**  
   - Cleaned and standardized data using Pandas.  
   - Created a weighted average to adjust professor ratings and difficulty based on sample sizes.

2. **Gender-Based Analysis**  
   - **Problem 1**: Conducted a t-test to reveal significant differences in adjusted ratings between male and female professors.  
   - **Problem 2**: Used a Kolmogorov-Smirnov (KS) test to analyze differences in rating distributions.  
   - **Problem 6**: Applied Cohen’s d to measure the effect size of rating differences.

3. **Tag Analysis**  
   - **Problem 4**: Examined gender biases in tags using permutation tests.  
   - **Problem 8**: Built a regression model to assess tag-based predictors of adjusted ratings.

4. **Difficulty Ratings**  
   - **Problem 5**: Evaluated differences in difficulty ratings using t-tests.  
   - **Problem 9**: Predicted difficulty based on tags via regression models (Lasso and Ridge).

5. **Classification Models**  
   - **Problem 10**: Developed a logistic regression model to predict whether a professor would receive a "pepper" rating.

6. **Advanced Statistical Testing**  
   - **Problem 3**: Calculated effect sizes for gender-based rating differences.  
   - **Extra Credit**: Conducted a Mann-Whitney U-test to explore differences in the number of ratings received.

---

### Results and Insights  

- **Gender Bias**: Statistically significant differences exist in ratings, but effect sizes indicate limited practical significance.  
- **Tags**: Certain tags, like "Hilarious" and "Respected," show pronounced gender bias.  
- **Predictors**: Students’ willingness to retake a class strongly predicts professor ratings, while "Tough grader" significantly impacts difficulty perception.

---

### Limitations  
- Data assumptions and sample sizes may limit generalizability.  
- Some variability in ratings and difficulty remains unexplained by the models.

---

**Contributor**  
Nirvan Mahesh Shukla  

This repository contains all project-related code, datasets, and analyses. Feedback and collaboration are welcome!
