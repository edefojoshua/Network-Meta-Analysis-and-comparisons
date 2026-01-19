# Network-Meta-Analysis-and-comparisons
This script demonstrated how a network meta-analysis was performed using the netmeta package in R. The required libraries were loaded, and a simulated dataset containing three studies comparing three treatments (Drug A, Drug B, and Drug C) was prepared. Each study included log-transformed risk ratios and their corresponding standard errors.

The netmeta() function was used to combine both direct and indirect evidence across studies, with risk ratio (RR) specified as the summary measure. The results were printed to display the estimated treatment effects, and a network plot was generated to visualize the treatment comparisons.

An indirect comparison between Drug B and Drug C yielded an estimated risk ratio of approximately 1.02. Since the confidence interval included 1, the analysis indicated no statistically significant difference between the two treatments. Further clinical interpretation and additional analyses were suggested.

