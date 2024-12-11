# Predicting March Madness Success


**Requirements to Run**
We used **R Studio** version 4.4.1 in the construction of our project, as well as the packages **dplyr** version 1.3.1 and **tidyverse** version 2.0.0. 
Both of the data sets we used were downloaded from **kaggle**, with the first being titled March Madness Data, by author Nishaan Amin, and the second being titled College Basketball Dataset, by author Andrew Sundberg. 

**How to Run** : 


 import kagglehub

  Download latest version
 path = kagglehub.dataset_download("nishaanamin/march-madness-data")

 print("Path to dataset files:", path)

and

import kagglehub

 Download latest version
path = kagglehub.dataset_download("andrewsundberg/college-basketball-dataset")

print("Path to dataset files:", path)

to get the data into r studio. 

**Known Limitations**: 


It is important to note how hard it is to predict success in March Madness, and although we have found trends that point to success, our methods are not foolproof, and should not be trusted for sports betting predictions. 

**References**: 



[HarvardSportsAnalysis](https://harvardsportsanalysis.org/2019/03/a-method-to-the-madness-predicting-ncaa-tournament-success/)
