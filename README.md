# Analyzing-NYC-High-School-Data

The objective of this project is to examine relationships between Scholastic Aptitude Test (SAT) scores and demographic factors in New York City public high schools. The datasets are publicly available on the New York City website: data.cityofnewyork.us.

Eight of the following datasets were merged together into one dataframe using the pandas library:
- School Surveys (survey_all.txt & survey_d75.txt)
- Demographics (demographics.csv)
- Graduation outcomes (graduation.csv)
- AP test results (ap_2010.csv)
- Class size (class_size.csv)
- School Attendance (hs_directory.csv)
- SAT scores by School (sat_results.csv)   

Data Cleaning and Exploratory Data Analysis were performed in order to discover the answers to the following questions:
- Are there any ethnic differences in SAT scores?
- Do Female students outperform Male students in SAT scores?
- Is there a strong correlation between high school students who take Advanced Placement (AP) exams and SAT scores?

Interesting observations were discovered as noted below:
- White & Asian students had a positive correlation to SAT scores and Hispanic & Black students had a negative correlation to SAT scores
- There is a weak correlation between Gender and SAT scores; however, Females had a positive relationship and Males had a negative relationship with SAT scores
- Safety and respect scores rated by student and teachers had a high correlation wtih SAT scores

Libraries used:
- pandas
- numpy
- re  
- matplotlib

How to install project?

Download the entire set of CSV and TXT files and Jupyter notebook file (schools.ipynb) and save them in the same folder

How to run project?

Click run on the Jupyter notebook and you are good to go. Enjoy :)
