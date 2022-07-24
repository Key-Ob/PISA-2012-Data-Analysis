# PISA 2012 Data Analysis.
## by Keith Obade


## Dataset

This is the PISA 2012 Dataset. PISA is the Program for International Student Assessments that allows countries to compare outcomes of the learning as students get close to finishing compulsory schooling. It is a survey of the skills and knowledge of students as they approach the end of compulsory education which looks at majorly how prepared the students are for life beyond school.It gives an assessment of reading, mathematics and science representing about 28 million 15-year-olds globally. Of those economies, 44 took part in an assessment of creative problem solving and 18 in an assessment of financial literacy.

This was a large dataset therefore it required a lot of wrangling and I took these steps:

    - Changed the country names that were wrongly put    
    - Renamed the columns of the data frame
    - Computed the average of plausible scores determines the PISA score of a student in a particular subjects
    - Filled in the means and replace in the NaN variables
    - Changing the Likert Scales into categories
    - Replace the values of Birth Month = 99 to null
    - Removed unnecessary columns


## Summary of Findings

- A lot of the students are born in 1996 with 93% and 7% born in 1997.

- The vast majority of students are between 15 and 16 years old with the most popular age is around 15.5.

- Most countries performed slightly in the same region in all tests between 400 - 500 points with China being the best performing country in all tests while Peru was the least.

- Most students chose the Agree choice then Strongly Agree, Disagree and lastly Strongly disagree. This shows that most students agree that the is motivation to studying.

- The strongest positive correlations can be observed between the scores of the different test areas math, reading, or science.If a student does well in one subject, it is likely that they will do well in another as well.

- Those who strongly disagreed on all 4 modes of motivation got the lowest scores which might the reason of low scores.

- Mexico has the highest student count who participated with around 34000 students and Lischtestein with less than 1000 students.

- The distributions of the subject scores show that the Maths Scores have a slightly lower mean than the rest which shows there is a bit of a struggle on Maths.


## Key Insights for Presentation


- Mexico has the highest student count who participated with around 34000 students and Lischtestein with less than 1000 students. No changes.

- Most students chose the Agree choice then Strongly Agree, Disagree and lastly Strongly disagree. This shows that most students agree that the is motivation to studying. Combined the plots together to be viewed easily.

- Most countries performed slightly in the same region in all tests between 400 - 500 points with China being the best performing country in all tests while Peru was the least. No changes.

- The strongest positive correlations can be observed between the scores of the different test areas math, reading, or science.If a student does well in one subject, it is likely that they will do well in another as well. Added the title.

- Those who strongly disagreed on all 4 modes of motivation got the lowest scores which might the reason of low scores. No Changes.
