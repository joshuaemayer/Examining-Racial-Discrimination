# Examining Racial Discrimination in the US Job Market
# Background

Racial discrimination continues to be pervasive in cultures throughout the world. Researchers examined the level of racial discrimination in the United States labor market by randomly assigning identical résumés to black-sounding or white-sounding names and observing the impact on requests for interviews from employers.

# Data
In the dataset provided, each row represents a resume. The 'race' column has two values, 'b' and 'w', indicating black-sounding and white-sounding. The column 'call' has two values, 1 and 0, indicating whether the resume received a call from employers or not.

Note that the 'b' and 'w' values in race are assigned randomly to the resumes when presented to the employer.

# Conclusion
Given our sample data set containing 4870 candidates (2435 white, 2435 black), we analyzed whether a the probability that a white candidate receives a call is the same as a black candidate. The formulation of our null hypothesis was that indeed this is true (calls to white candidates = calls to black candidates). We looked to accept or reject assuming a 95% CI.

My analysis shows that indeed white candidates are more likely to receive callbacks than black candidates. I leveraged a two-sample test and given the results (p-value and confidence intervals) it showed that there is a 95% chance that white candidates are more likely to get a callback than black candidates.

# Further Recommendations
In this analysis we focused on race vs callbacks, however, these are only two factors (amongst many) in the dataset. In order to determine importance I would need to perform a similar analysis for the remaining factors and compare their significance (and p-values) in order to rank importance. To amend the analysis I would like to leverage more of a logistic regression type analysis, and perform factor engineering to determine the importance and significance of each factor in the dataset. This would be a MUCH more intense and extensive analysis.