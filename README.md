# School_District_Analysis
## Overview of the school district analysis
Use Python and the Pandas library with Jupyter Notebook to analyze school district data and showcase trends in highschool performance.
### Purpose
The purpose of this analysis was to replace all of the ninth graders math and reading scores from Thomas High School as they seem to have been altered making them invalid. After replacing the scores, the purpose was to repeat the school district analysis and see how the updated scores affected the overall results. 
## Results
- How is the district summary affected?
  - The district summary was barely affected by replacing the ninth grade scores from Thomas High School! The last five columns of the updated district summary dataframe reveal that the scores and percentages mostly decreased by 0.3(0.3% as well for the percent colums) compared to the original district dataframe. The only column that did not experience any changes was the "Average Reading Score" column.

**Original District Summary** 
  ![8F6442A4-EC80-44D9-94DF-4EC762C66E82_4_5005_c](https://user-images.githubusercontent.com/92240407/145519105-a4a9770a-0bc0-4479-9d7a-bc7287b2b8be.jpeg)

**Updated District Summary**
![15FDF67E-26D5-4571-A23D-9390EF5DB932_4_5005_c](https://user-images.githubusercontent.com/92240407/145519300-3b85ddd0-b800-4e5d-ab5c-20027f285ac9.jpeg)
- How is the school summary affected?
  - The school summary was barely affected as well! All of the results were the same as before except for Thomas High School which had the same type of decrease experienced in the updated district summary dataframe!
- How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
  - Even though Thomas High School experienced a change in scores due to their ninth graders, their overall ranking compared to the other schools stayed the same with Thomas High School ranked as the second top school in regards to school performance. 

**Original Top 5 Schools**
![3937965A-D69A-419A-899E-1BC0116EA551](https://user-images.githubusercontent.com/92240407/145521198-95e6a928-cc0b-401b-abfc-01a3b6a6c4fb.jpeg)

**Updated Top 5 Schools**
![5EC38F34-54D6-4FA7-8215-D5A558DFB01E_4_5005_c](https://user-images.githubusercontent.com/92240407/145521384-663d4d56-c635-42fd-8dc6-b62535e0b26a.jpeg)
- How does replacing the ninth-grade scores affect the math and reading scores by grade?
  - The only scores that are affected when replacing the ninth-grade scores are the math and reading score in the "Thomas High School" row in the column of "9th". These scores depict a NaN value rather than an actual number. 

**Original Math Scores by Grade**
![B5187EE3-9416-407E-9F50-0D3537357894_4_5005_c](https://user-images.githubusercontent.com/92240407/145522580-0f9e276e-4436-454b-912b-fe789b9a5feb.jpeg)
**Updated Math Scores by Grade**
![C1EA4BAD-7EF3-48D2-8214-02110C43F056](https://user-images.githubusercontent.com/92240407/145522626-db11579c-ae5b-440f-8a0a-75ed5c61f877.jpeg)

**Original Reading Scores by Grade**
![2E1DAA39-B6CD-4FB9-BF1F-859642EF9A26](https://user-images.githubusercontent.com/92240407/145522784-78c5a46b-7def-4df2-92dd-24d57d3a08fc.jpeg)

**Updated Reading Sccores by Grade**
![52895331-AACF-47AA-8114-87561C1FB82D](https://user-images.githubusercontent.com/92240407/145522807-fe309150-540d-4910-b86d-b735394cfb0d.jpeg)

- How does replacing the ninth-grade scores affect scores by school spending?













