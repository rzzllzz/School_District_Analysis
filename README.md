# School District Analysis

## Overview
The purpose of this analysis was to use code created for analysis of the entire school district's data and modify it to accomodate for an instance of academic dishonesty from one of the high schools in the district, Thomas High School. 

## Results
- How is the district summary affected?

  - Below is the district summary from the original PyCitySchools analysis:
![pycityschools_district_summary](https://user-images.githubusercontent.com/101225282/169937536-98899139-e357-44b3-b3cd-878c2156b48d.png)
  - Below is the district summary from the modified analysis: 
![pycityschoolschallenge_district_summary](https://user-images.githubusercontent.com/101225282/169937560-76069bd8-8b8d-4158-afaf-de4ea1b1eb79.png)

We can see that there are marginal changes made to the district summary after replacing Thomas High School's ninth graders' math and reading scores with null values. The biggest change is the Overall Passing percentage value **decreased** from 65.17% to 64.9%.

- How is the school summary affected?

  - Below is the summary per school from the original PyCitySchools code: 
![pycityschools_per_school_summary](https://user-images.githubusercontent.com/101225282/169937817-07f5c043-22e7-419e-8886-c71a3305c056.png)
  - Below is the summary per school from the modified analysis: 
![pycityschoolschallenge_per_school_summary](https://user-images.githubusercontent.com/101225282/171313704-6ad020b3-e2a7-40f7-9f59-f4387bc24cbc.png)

Most of Thomas High School's data in the school summary table changed marginally after replacing the ninth graders' math and reading scores with null values. The Average Math Score changed from 83.41 to 83.35. The Average Reading Score changed from 83.72 to 83.89. The Percentage of students passing math changed from 93.27% to 93.18%. The Percentage of students passing reading changed from 97.30% to 97.01%. The Overall Passing Percentage changed from 90.94% to 90.63%.

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - Below are the top schools from the original PyCitySchools code:
![pycityschools_topschools](https://user-images.githubusercontent.com/101225282/171316965-f48e4b78-0627-4398-818f-d01ec63db124.png)
  - Below are the top schools from the modified analysis:
![pycityschoolschallenge_topschools](https://user-images.githubusercontent.com/101225282/171316970-b9f87111-6dca-45ec-8b15-525892586324.png)

We can see that changing the ninth graders' math and reading scores to null values does not affect Thomas High School's performance relative to other schools. 

- How does replacing the ninth-grade scores affect the following:

- Math and reading scores by grade
  - Below are the math scores by grade for math and reading from the original PyCitySchools code:
![pycityschools_math_scores_by_grade](https://user-images.githubusercontent.com/101225282/169938667-1327f429-896a-4d63-a16e-668caebb8a1a.png)
![pycityschools_reading_scores_by_grade](https://user-images.githubusercontent.com/101225282/169938693-0caff730-fe96-43c3-84e6-fdaff2ea2be2.png)

  - Below are the math scores by grade for math and reading from the modified analysis: 

![pycityschoolschallenge_math_scores_by_grade](https://user-images.githubusercontent.com/101225282/169938697-7413b4e4-63f6-4b6e-86e9-c933268378af.png)
![pycityschoolschallenge_reading_scores_by_grade](https://user-images.githubusercontent.com/101225282/169938702-b4e0b761-c389-484b-a9a8-c25ab0e5e59f.png)

We can see from the math and reading scores across the different grades that the scores for other grades were not affected by replacing Thomas High School's ninth grade class with null values. 

- Scores by school spending
  - Below is the table that displays the spending per school from the original PyCitySchools code:
![pycityschools_spending_summary](https://user-images.githubusercontent.com/101225282/171317569-f84df9e2-bee8-4d3f-8e4c-756552322274.png)
  - Below is the table that displays the spending per school from the modified analysis: 
![pycityschoolschallenge_spending_summary](https://user-images.githubusercontent.com/101225282/171317619-25f3212b-b86b-4f0a-a1ee-4d1ed07d1020.png)

The only change that occurred in the school spending category were the spending ranges. The original analysis had ranges of <$586, $586-$630, $631-$645, $646-$675, which were then changed to <$584, $585-$629, $630-$644, $645-675. This changed Thomas High School's spending range from $631-645 to $630-$644. 

- Scores by school size
  - Below is the table that displays the size summary of the schools from the original PyCitySchools code:
![pycityschools_size_summary](https://user-images.githubusercontent.com/101225282/171318325-a7e3c009-1a3b-4533-ba86-8a167f2b68f0.png)
  - Below is the table that displays the size summary of the schools from the modified analysis:
![pycityschoolschallenge_size_summary](https://user-images.githubusercontent.com/101225282/171318376-09af1863-2710-4c04-b6ab-64327a52b6c6.png)

- Scores by school type 
  - Below is the table that displays the summary of the type of schools from the original PyCitySchools code:
![pycityschools_type_summary](https://user-images.githubusercontent.com/101225282/169939198-e558db54-8966-4c99-b518-b763d3270e17.png)
  - Below is the table that displays the summary of the type of schools from the modified analysis:
![pycityschoolschallenge_type_summary](https://user-images.githubusercontent.com/101225282/169939170-f4db4a2e-257c-40ff-bd86-04b42be255e2.png)

We can see from the tables for school size and school type, the data was largely unchanged after replacing Thomas High School's ninth grade class' math and reading scores with null values.

## Summary
After identifying academic dishonesty from the ninth grade class of Thomas High School, it is important to go through and identify the effect of replacing the affected data with null values. One of the places in the analysis we can check to see the effects of this are in the district summary. As mentioned before, the Overall Passing percentage value decreased from 65.17% to 64.9%. 
