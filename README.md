# A/B testing

A chi-square test always tests the null hypothesis that there is no relationship between two variables vs. the alternative hypothesis that there is some relationship between the two variables.

Use p-value of chi2_contingency imported from scipy.stats to determine rejecting or failing to reject the null hypothesis.  

## Udacity WebText and Clickthroughs

### Introduction
Udacity tested a change where if the student clicked "start free trial", they were asked how much time they had available to devote to the course.
If the student indicated 5 or more hours per week, they would be taken through the checkout process as usual. If they indicated fewer than 5 hours per week, 
a message would appear indicating that Udacity courses usually require a greater time commitment for successful completion and suggesting that the student might 
like to access the course materials for free.
At this point, the student would have the option to continue enrolling in the free trial, or access the course materials for free instead.

### The null and alternative hypothesis
Ho: There is no relationship between the web text and clickthroughs.
Ha: There is a relationship between the web text and clickthroughs.

### p-value and Conclusion
The p-value is 0.94, we fail to reject the null hypothesis and conclude that there is no association between the screen the individual was shown and clicking 
through.

## Titanic Example

### Introduction
In the early hours of April 15, 1912, the unsinkable ship RMS Titanic sank when it struck an iceberg, killing more than half of the passengers and crew aboard.
The Titanic.csv dataset contains demographic information for 889 of those passengers as well as a record of whether or not each passenger survived.
Our goal is to determine if there is a relationship between ticket class and passenger survival on the Titanic.

### The null and alternative hypothesis
Ho: There is no relationship between passenger ticket class and survival on the Titanic.
Ha: There is a relationship between passenger ticket class and survival on the Titanic.

### p-value and Conclusion
The p-value is 3.84e-58, at the 0.05 significance level, we can reject the null hypothesis and conclude that is a statistically significant relationship between
passenger sex and survival.


