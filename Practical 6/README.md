# Practical 6: Statistical Analysis of Teaching Ratings Dataset

## Objective

To perform statistical analysis on the Teaching Ratings dataset using Python and SciPy to examine differences, associations, and relationships among selected variables.

## Dataset Description

The Teaching Ratings dataset contains information about instructors, including teaching evaluation scores, beauty scores, gender, age, and tenure status. The dataset is used to perform statistical tests and analyze relationships between these variables.

## Tools and Libraries

* Python
* Pandas
* NumPy
* SciPy
* Jupyter Notebook

## Statistical Analysis Performed

### Independent Two-Sample Welch's t-Test

To determine whether the mean teaching evaluation scores differ significantly between male and female instructors.

### One-Way ANOVA

To examine whether beauty scores differ significantly across different age groups.

### Chi-Square Test of Independence

To investigate whether tenure status is associated with gender.

### Pearson Correlation

To examine the strength and direction of the linear relationship between teaching evaluation scores and beauty scores.

## Project Files

* `practical 6.ipynb` – Contains the Python code and statistical analysis.
* `teachingratings.csv` – Dataset used for the analysis.
* `README.md` – Provides an overview of the practical, its objectives, and the statistical methods used.

## Conclusion

This practical demonstrates the application of statistical hypothesis testing and correlation analysis to the Teaching Ratings dataset. The results can be interpreted using test statistics and p-values to determine whether the observed differences and relationships are statistically significant.

## How to Run

1. Clone or download the repository.

2. Install Python and Jupyter Notebook.

3. Install the required libraries:

   ```bash
   pip install pandas numpy scipy jupyter
   ```

4. Open `practical 6.ipynb` in Jupyter Notebook.

5. Ensure that `teachingratings.csv` is available in the appropriate directory.

6. Run the notebook cells sequentially to perform the statistical analysis.
