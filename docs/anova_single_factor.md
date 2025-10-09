A single factor or one-way ANOVA is used to test the null hypothesis that the means of several populations are all equal. In this example, you find the salaries of people who have a degree in economics, medicine, or history. You can see that the groups are not related because they have different numbers of observations in the groups. 
Null hypothesis: H0: μ1 = μ2 = μ3 (meaning that the means/averages of all three groups are the same)
Alternative hypothesis: H1: at least one of the means is different.
If we find that at least one mean is different, you can do  pairwise comparisons with t tests to see where there is a difference and where not. In this example, there is at least one different group. The type of t test depends on whether the two samples have equal variances or not, and whether the observations are paired. In this example, they are not paired but we don't know about the variances yet. 

First we  check if the means are equal.
- On the Data tab, in the Analysis group, click Data Analysis. If it is not available, you may need to install the Analysis Toolpak.
![original values](pics\anova1a.png)
- Select Anova: Single Factor
- Enter the data as in the picture below. You can click the up arrow for Input Range and Output Range to use the mouse to select.In this case, we  include the labels (row 1) so select the labels box.
![input values](pics/anova1b.png)
- The ANOVA results show that there is at least  one difference between groups, since the p value is 0.0000716 which is less than 0.05 (5%).
![anova output](pics/anova1c.png)
