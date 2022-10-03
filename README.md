# School_District_Analysis

## Overview of Project
The school board wanted to get analysis done on the file that Maria had and this file had student records for all the schools in the district. Maria expected the data analysis to include specific detailed information about specific subsets of the data. Maria further got a new version of the student data file and the new dataset had some changes with one major addition being a new column of data called "school budget". For the new dataset the expectation was to analyze the data for specifics.

## Methodology/Tools
Anaconda and Jupyter Notebook( with pythonData) were used for this analysis. 
Step by step analysis was performed building on from inspecting the dataset file, prepare the data ( by removing duplicates, NaN, clean the columns for dataType, use header function to preview dataFrame), describe the data using summary statistics on the data as a whole and on individual columns, drill down on data with loc/iloc functions, and making data comparison using aggregate functions. 

## Results
Specific analysis was performed to supplement the findings that were already provided before the deep dive analysis performed for Maria for the school data analysis.
Upon cleaning the data and removing the null value rows, as well as duplicates the total number of rows that were part of this analysis were 14831! 

Summary of student count across the schools 

![image](https://user-images.githubusercontent.com/42523379/193507907-86df806a-634a-4087-b0f0-62aba204e749.png)

School Budget: It is noteworthy that the public school budget is little greater than the charter school budget. 

![image](https://user-images.githubusercontent.com/42523379/193507369-e02e9d09-1947-480d-ad7e-56cfde312acb.png)

Average Reading and Math Scores for the School Types

!![image](https://user-images.githubusercontent.com/42523379/193507509-81fd6edc-be2f-413c-aa7e-7922f0a7524f.png)

Math scores across grades for school types

![image](https://user-images.githubusercontent.com/42523379/193507962-4bbc348d-0457-4f7f-9d37-936517f23394.png)

## Future Consideration for Indepth Analysis 
Schools can use this template as a baseline and further modify the tool to meet the individual school needs. 
- One aspect that could be looked at further is analysis of how the students fared with both reading and math score in terms of percentage of respective school population. 
- Another area is identifying highest and lowest performers across school types and rank students accordingly to school_type and grade.

Individual student performance against the school benchmarks can indicate any trends of performance/scores across a particular grade and school. This information will be very powerful for causal analysis. Strategies can be incorporated to improve on the student performance around such analysis and will be useful to use at a largest scale such as across counties for comparision amongst counties across states. 

