# Autolib-Hypothesis-and-Stastical-overview
Autolib electric car-sharing service company to investigate a claim about the blue cars from the provided Autolib dataset.

# Hypotheisis Document
   * Google docs : https://docs.google.com/document/d/1ssRgh9V_bBQFkCasioZWQf64c_i8NiDd0GJq0wAv3Uw/edit?usp=sharing

# Overview 

* Just like before, we have been tasked to understand electric car usage by solving for another research question. We will work as a Data Scientist for the Autolib electric car-sharing service company to investigate a claim about the blue cars from the provided Autolib dataset.

* In an effort to do this, we need to identify some areas and periods of interest via sampling stating the reason to the choice of method, then perform hypothesis testing with regards to the claim that we will have made. An example of claim to test would be "Is the number of Bluecars taken in area X different than in area Y? Is it greater in area X than in area Z? Etc”. The selected periods of interest be either weekdays or weekends but not a mix of both. You can also consider postal codes 75015 vs 75017 to some of the areas of interest. 

* To work on this project, we will perform the following analysis with Python; 

* Find and deal with outliers, anomalies, and missing data within the dataset.
* Plot appropriate univariate and bivariate summaries recording our observations.
* Implement the solution by performing hypothesis testing.
* This will need to be documented when writing the report. 

* Below are the guidelines for creating your report:

   * Problem Statement
     * Introduce the data you will be describing and the random variable that you are investigating. 
     * State very precisely the null and alternate hypothesis that you will be testing. 
     * Provide some explanation for why this hypothesis is important and/or interesting. 
     
    * Data Description
      * Provide information about the data necessary to understand the rest of the report including a precise statement of the random variable.
      * Provide a description of the source of your data and the data collection procedures, the descriptive statistics, and some assertions about the model that is consistent    with the data. 
     
    * Hypothesis Testing Procedure
      * Present the details concerning how you will test your hypothesis. 
      * Describe the logic behind your null and alternate hypotheses -- where did they come from, why are they interesting. 
      * Describe the test statistic will you use (i.e., z, t, f) and why?  For example, if you are testing a hypothesis about a mean, you have what appears to be normal data, and you have a small n, then you would use a T-test.  When explaining your choice of the test statistic, you need to discuss whether you have satisfied the assumptions necessary for using the specific statistic (e.g., does the statistic require your population to be normal and is it?). 
      * Determine the alpha level you will use (i.e., 0.01, 0.05).
      
    * Hypothesis Testing Results
      * Start with the results of your test. 
      * State the value of the test statistics and the result of the accept/reject decision. 
      * Identify the p-value of the test.
      * State what the point estimate is for the parameter
      * Construct a confidence interval around the parameter.
      
    * Discussion of Test Sensitivity  
      * If you conducted a test on a parameter (e.g., m, p, s), then you might comment on the following:  the practical significance of the finding in the event that your null hypothesis is rejected and the power of the test (1-ß) for the given alpha level and sample size, and the effect of changing the sample size.
      * If you conducted the goodness of fit test, comment on the effect of different bin sizes, different numbers of bins, and different estimates of the parameters of the hypothesized model.
    
    * Summary and Conclusions
      * Summarize the process of the project
      * Provide the concluding statement concerning the hypothesis, the results, and the sensitivity of the testing.

#### -- Project Status: [Completed]

## Project Intro/Objective
* In an effort to do this, we need to identify some areas and periods of interest via sampling stating the reason to the choice of method, then perform hypothesis testing with regards to the claim that we will have made. An example of claim to test would be "Is the number of Bluecars taken in area X different than in area Y? Is it greater in area X than in area Z? Etc”. The selected periods of interest be either weekdays or weekends but not a mix of both. You can also consider postal codes 75015 vs 75017 to some of the areas of interest.

### Partner
* [Moringa School]
* https://moringaschool.com/

### Methods Used
* Descriptive Statistics
     * Standard Deviation
     * Mean
     * Kutosis
     * Skewness
     * Coeeficeint of Variation 
     
* Data Visualistaion Techniques
     * Profiling report
     * Histograms
     * Frequency bar charts
     * Scatter Plot
     * Heat Map
     
* Data Analysis
   * EDA Univariate Analysis
   * Bi-variate Analysis
  
 * Normaility Tests
    * QQ-plot
      ```python
         from statsmodels.graphics.gofplots import qqplot #  libraries to plot our Q-Q plot
      ```
      
    * Shapiro-Wilks Test 
    
 * Sampling techniques
   * Finding the z-score
   * Finding P-value
   * Methods used to find evdence if the null hypothesis will be rejected or accepted
         * Setting a significance level
  

### Technologies
* Python
* Pandas,Numpy,Gooogle Colab
* Google Docs

```python
import pandas as pd # python library that import datasets into a working env and does so much more such as helping in cleaning datasets etc
import numpy as np # offers comprehensive mathematical functions etc
from pandas_profiling import ProfileReport
!pip install pandas==1.2.4
!pip install pandas-profiling==2.7.1
```

## Data Used
 * Data Soruces used
    * Variable Definitions: http://bit.ly/DSCoreAutolibDatasetGlossary
    * Dataset: http://bit.ly/DSCoreAutolibDataset
  * Data Analysis used
      * Univariate Analysis 
          * [EDA.HTML]
          * Frequency Distibutions
          * Bar graphs
          * Descriptive Statistics
              * Standard deviation
              * Mean
              * Variance
              * Skewness
              * Kurtosis
          * Histograms
       * Bivariate Analysis
           * Scatter Plot
           * Heat Map
  
## Needs of this project
- data exploration/descriptive statistics
- data processing/cleaning - involves taking care of missing data, outliers and duplicates before after merging the datasets
- Data Visualisation
- Stratified Smapling techniques
- EDA 

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate
