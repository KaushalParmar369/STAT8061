# STAT8061
Data Visualization Tools and Techniques 



## Overview

This assignment applies statistical methods and data visualization techniques to analyze weight data of students from two samples. Using formulas and visualizations, the project identifies patterns, compares distributions, and presents insights effectively.


### Key Tasks

1. **Sampling and Data Preparation**:
   - **Samples**:
     - Sample 1: 55 students (68% males, 32% females).
     - Sample 2: 49 students (65% males, 35% females).
   - **Sampling Method**: Simple random sampling.
   - 
   - **Gender Ratio Calculation**:
     \[
     \text{Gender Ratio (Male or Female)} = \frac{\text{Count of Gender in Sample}}{\text{Total Count in Sample}} \times 100
     \]

   - **Example (Sample 1, Males)**:
     \[
     \text{Male Ratio} = \frac{37}{55} \times 100 = 67.27\%
     \]


2. **Statistical Analysis**:

   - **Mean Weight Calculation**:
     \[
     \text{Mean Weight} = \frac{\text{Total Weight of Students}}{\text{Number of Students}}
     \]
     - Sample 1 (Males): \( \text{Mean} = \frac{5274.77}{37} = 142.56 \, \text{lbs} \)
     - Sample 2 (Males): \( \text{Mean} = \frac{4431.42}{32} = 138.48 \, \text{lbs} \)

   - **Standard Deviation**:
     \[
     s = \sqrt{\frac{\sum(x_i - \bar{x})^2}{n - 1}}
     \]
     - Where:
       - \( x_i \): Each data point
       - \( \bar{x} \): Mean
       - \( n \): Number of data points
     - Standard Deviation:
       - Sample 1: \( 20.75 \)
       - Sample 2: \( 18.06 \)

   - **Weight Range (Percentage of Students)**:
     \[
     \text{Percentage} = \frac{\text{Count of Students in Range}}{\text{Total Students}} \times 100
     \]
     - \( \text{Percentage} = \frac{57}{104} \times 100 = 54.8\% \)


3. **Visualizations**:

   - **Pie Chart**:
     - Showcased the gender distribution:
       - Male#1: 37 (36%), Male#2: 32 (31%)
       - Female#1: 18 (17%), Female#2: 17 (16%).
       - 
   - **Bar Graph**:
     - Compared counts of males and females in both samples.
     - 
   - **Boxplots**:
     - **Comparison 1**: Male weights in Sample 1 vs. Sample 2.
     - **Comparison 2**: Male vs. Female weights in both samples.


 Key Insights

1. **Variability**:
   - Sample 1 had higher standard deviations for both genders, indicating more weight variability.
2. **Overlap**:
   - Male and female weight ranges showed some overlap in both samples.
3. **Weight Range**:
   - 54.8% of all students had weights between 121–157 lbs, a common range across samples.


 # Tools and Formulas Used

- **Microsoft Excel**:
  - Calculated mean, standard deviation, and ratios.
  - Formulas:
    - Mean: `=AVERAGE(range)`
    - Standard Deviation: `=STDEV.S(range)`
    - Percentage: `=COUNTIF(range, "criteria")/COUNT(range)`

- **Visualization Tools**:
  - Created pie charts, bar graphs, and boxplots to represent data trends.



## Conclusion

This assignment provided detailed insights into student weight distribution by applying statistical formulas and visualizations. It demonstrated proficiency in using statistical tools and techniques to compare and interpret datasets.


