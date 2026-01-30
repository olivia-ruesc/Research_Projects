# Investigation of the Relationship Between Temperature and Traffic Volume in Chicago

## Overview
This project investigates the relationship between **daily maximum temperature** and **traffic vehicle volume** in **Chicago** using statistical and graphical methods. The goal is to explore whether temperature has a measurable association with traffic volume and to assess the strength and nature of that relationship.

The analysis combines exploratory data analysis, distribution diagnostics, correlation measures, and visualization techniques implemented in **R**.

This paper was published in the Heartland Review Journal which can be viewed at https://heartlandreview.wixsite.com/heartland-review/stem
This project was also presented at Western Illinois University's Undergraduate Research Day 2025 and won first in Department.
---

## Author
**Olivia M. Rueschhoff**  
Bachelor of Science in Mathematics  
Emphasis in Data Science and Statistics  

**Faculty Advisor:**  
Dr. Feridun Tasdan  

--- 

## Data Description

The dataset consists of:
- Daily maximum temperature (°F)
- Daily traffic vehicle volume counts

Data were originally compiled and cleaned in Microsoft Excel and subsequently imported into R for statistical analysis.
The study focuses on data collected in Chicago during the year 2006.
The data came from the following public sources:
  National Centers for Environmental Information. (2024). Record of climatological observations: Chicago Northerly Island, IL US (USC00111550). U.S. Department of Commerce, National Oceanic and Atmospheric Administration.
  Chicago Department of Transportation. (n.d.). Average daily traffic counts. City of Chicago. https://www.chicago.gov/city/en/depts/cdot/dataset/average_daily_trafficcounts.html 
  

## Methods

The analysis includes:
- Descriptive statistics and exploratory plots
- Distribution diagnostics using Cullen and Frey graphs
- Normal distribution fitting
- Kolmogorov–Smirnov goodness-of-fit testing
- Pearson and Spearman correlation analysis
- Outlier and influence assessment using boxplots and convex hull analysis
- Joint visualization of temperature and vehicle volume
- All statistical analyses were performed using R

## Key Findings

The relationship between temperature and traffic volume was found to be weakly positive.
There were several outliers and missing data, particularly during summer months which likely influenced correlation strength.
Nonparametric correlation measures supported the presence of a weak association.
The results suggest temperature alone is not a strong predictor of traffic volume.
Detailed results and interpretation are provided in the accompanying paper.

### Notes

This project was completed as part of an undergraduate statistics course and is intended to demonstrate applied statistical analysis, exploratory data techniques, and clear interpretation of results. 

You can view the R-code used to make this project, the paper itself, and the poster that was presented at the WIU Undergraduate Research Day 2025 and won Best in Department. 

## Sources
Chicago Department of Transportation. (n.d.). Average daily traffic counts. City of Chicago. 
   https://www.chicago.gov/city/en/depts/cdot/dataset/average_daily_trafficcounts.html
Comparison of P-P plots and Q-Q plots. (1999, September). Retrieved from Simon Fraser University: 
   https://www.sfu.ca/sasdoc/sashtml/qc/chap8/sect9.htm
Everitt, B., & Hothorn, T. (2011). An Introduction to Applied. (R. Gentleman, K. Hornick, & G. 
   Parmigiani, Eds.) London, Munchen: Springer.
Ford, C. (2015, August 26). Understanding QQ Plots. Retrieved from University of Virgina Library:
   https://library.virginia.edu/data/articles/understanding-q-q-plots
Hogg, R. V., Tanis, E. A., & Zimmerman, D. L. (2021). In Probability and Statistical Inference 
   (10th ed.). Pearson.
How to Perform Spearman. (2024). Retrieved from OnlineSPSS: https://www.onlinespss.com/spearmen-correlation-in-r/
Kolmogorov-Smirnov Test in R Programming. (2023, March 10). Retrieved from GeeksforGeeks: 
   https://www.geeksforgeeks.org/kolmogorov-smirnov-test-in-r-programming/
National Centers for Environmental Information. (2024). Record of climatological observations: 
   Chicago Northerly Island, IL US (USC00111550). U.S. Department of Commerce, National Oceanic and Atmospheric 
   Administration.
Quaresma, D. F., Pereira, T. E., & Fireman, D. (2021). Validation of a simulation model for FaaS performance 
   benchmarking using predictive validation. Campina Grande: Federal University of Campina Grande. Retrieved from 
   https://www.researchgate.net/publication/353060353_Validation_of_a_simulation_model_for_FaaS_performance_
   benchmarking_using_predictive_validation
