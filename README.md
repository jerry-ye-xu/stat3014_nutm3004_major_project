<h2 align="center" style="margin-top:10px"> STAT3014 | NUTM3004 </h2> 
<h3 align="center" style="margin-top:10px"> Joint Research Project </h3>

This is an interdisciplinary project between statistics and nutrition undergradates, where we formulate a research question based on obesity and utilise the 2011-2 Australian Health Survey (AHS) to answer our question.

<br> __Data:__ </br>
<br> The data used is the Australian Healh Survey (AHS), a study conducte d by the Australian Bureau of Statistics and consists of 3 major parts. </br>

1. National Health Survey (2011-12)
2. National Nutrition and Physical Activity Survey (NNPAS) 2011-12
3. National Health Measures Survey (NHMS) 2011-12

<br> Participants in the NHS total approximately 20,000 whilst the NNPAS has 13,000 participants. Whilst both surveys had common questions including household information, demogrpahics, body mass, food consumption and other physical measures, the NNPAS had additional components regarding physical activity whilst NHS surveyed for medications, alcohol consumption, financial stressors etc. </br>
<br> These participants were invited to volunteer for the NHMS, which consisted of taking blood tests (12yrs+), urine tests (5yrs+) and other chronic disease markers.</br>

<br>__Highlights:__</br> 

Our project focuses on the analysis of diabetes and dyslipidemia with respect to the various feature variables in the AHS. We narrowed our scope down to various types of fats and carbohydrates consumed by the sample population as well as other potential confounding variables such as age and BMI.

Unsurprisingly, age and BMI are consistently the biggest influencer in both health risks whilst the fats and carbohydrates 
varied in their use in predictive modelling. Much of this can be attributed to the overwhelming overlap of densities between classes for the various response variables, which makes it difficult for the algorithms to learn the distinguish between the two classes.

We used SMOTE upsampling for the extremely imbalanced classes in analysing diabetes, and a range of classification algorithms ranging from the simple KNN to penalised-SVM was used to optimise the balance of Type I and Type II errors. For the ordinal HDL and LDL variables, we used proportional odds models and partial proportional odds models when the parallel regression assumption does not hold. 

Although the data was not segregated well enough for some of the response variables for successful predictions, we were able to apply our knowledge of statistic learning appropriately for various response variable distributions whilst using our knowledge of nutrition to interpret the results.  

For a more detailed summary, please refer to the final report.

<br>__Final Report:__</br>

The conclusive analysis is generated by the `Final_Report.rmd` in the `rmd` directory. The detailed analysis of all the response variables are found in the corresponding rmd files in the same directory. The Final_Report.pdf was placed in the root directory for conveience, but if knitted will be generated in the `rmd` directory. 

__IMPORTANT:__ To ensure reproducibility, ensure that the appropriate libraries are installed, and the both R, RStudio and Rmarkdown are updated to the latest version. Furthermore, the files should not be moved, as they required other files from their current relative paths.  

<br>__Directories:__</br>

`Data:` Contains raw data for AHS 2011-2012 Survey.

`Output:` Output files, processed dataset

`rmd:` Rmarkdown files for analysis. Also contains reusable functions in the `functions` directory.

<br>__Functions:__</br>

All functions for use are stored as \<function_name\>.R

__GitHub:__

[GitHub Repo](https://github.com/jerry-ye-xu/stat3014_nutm3004_major_project)

__Final Words:__

Although the data was insufficient in producing revolutionary results, it was a great interdisciplinary project where as a statistics student I was able to learn more about another discipline and apply my knowledge critically to a project. 
