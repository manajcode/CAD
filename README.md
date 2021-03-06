# CAD
Predicting CAD is an R project in which I aplied logistic regression and cross validation techniques to predict Coronary artery disease using the "Heart Disease Data set from the UCI machine learning repository (https://archive.ics.uci.edu/ml/datasets/Heart+Disease).

The data was originally collected and used in Detran et al. (1989):

Detrano, R., Janosi, A., Steinbrunn, W., Pfisterer, M., Schmid, J., Sandhu, S., Guppy, K., Lee, S., & Froelicher, V. (1989). International application of a new probability algorithm for the diagnosis of coronary artery disease. American Journal of Cardiology, 64,304--310. 

In this project myself and Tam modified the Detrano et al. procedures by:

a) applying modern variable selection procedures (backwards stepwise procedure

b) dealt with the issues of messy data by scraping all acceptable data from all sample sets

c) used 70:30 cross validation 

d) calculated sensitivity, specificty, and a confusion matrix to estimate accuracy.


Here is a description of the following files within the R project:

1. Predicting_CAD_power_point_presentation_5.8.19.rmd: the r markdown file containing the scripts used to input, manipulate, and analyze data.

2. processed.cleveland.txt: text file containing the medical data for patients from Cleveland.

3. processed.hungarian.txt: text file containing the medical data for patients from Hungary.

4. processed.switzerland.txt: text file containing the medica data for patients from Switzerland.

5. processed.va.txt: text file containing the medical data for veteran patients from Long Beach.

6. stat632_Najarro_Tam_final_project_report.pdf: A final written report of our findings post analsyes. 


information regarding the data sets can be found at https://archive.ics.uci.edu/ml/datasets/Heart+Disease.

