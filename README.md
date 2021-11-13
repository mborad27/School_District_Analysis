# School District Analysis with Pandas and Jupyter Notebook
## Overview
Maria, the chief data scientist for City School, is responsible for collecting data on City Schools testing proficiency. She provided us `.csv` files with the students' test scores, school-related information and funding. Using Pandas, we will be analyzing this data and presenting it to the school board. This will help them with making decisions regarding school budgets and priorities.

Maria was notified by the school board that the `students_complete.csv` file contains academic dishonesty for math and reading grades for some students. She would appreciate if we replace the math and reading scores for Thomas High School with NaNs. With that, she would also like for us to re-do the school district analysis and write a report explaining how these changes affected our analysis.

## Results
### Original District Summary:
![orignal distruct sum](https://user-images.githubusercontent.com/92230478/141050740-3eaf9732-0112-4b7c-9418-a21596b3d883.PNG)
### After Data Cleanup District Summary:
![district summary](https://user-images.githubusercontent.com/92230478/141050792-0e1b2946-5715-4496-b359-77e7f7d11eb5.PNG)
* After the data cleanup, the District Summary shows that the Average Math Score dropped from 79.0 to 78.9. The percent of students passing math decreased from 75 to 74.8. The Average Reading Score remained the same, but the percent of students passing reading decreased from 86 to 85.7. The percent of students overall passing also lowered from 65 to 64.9
### Original School Summary:
![original](https://user-images.githubusercontent.com/92230478/141050936-f7998412-3abb-48c2-9237-d8c81d6a0cbf.PNG)
### After Data Cleanup School Summary:
![rendered](https://user-images.githubusercontent.com/92230478/141402699-bb475f3d-3eb1-400a-9a4b-1a18de31aace.PNG)
* After the school summary was updated, only the row for Thomas High School displayed changes: the average math score dropped from 83.418349 to 83.350937 and the percentage of students passing math lowered from 93.272171 to 93.185690. The average reading score increased from 83.848930 to 83.896082, the percentage of students passing reading dropped from 97.308869 to 97.01879, and the percent of students overall passing declined from 90.948012 to 90.630324.
### Top 5 Ranking:
![t5](https://user-images.githubusercontent.com/92230478/141404997-042c4508-c4a2-4184-a268-0d97af374fa5.PNG)
### Bottom 5 Ranking:
![bottom 55](https://user-images.githubusercontent.com/92230478/141404920-019ac469-bce7-4955-90ef-293f5e0b5954.PNG)
* After the 9th grade math scores and reading scores for Thomas High School were cleaned up, Thomas High School is still ranked at #2 in the top 5 achieving schools. The bottom 5 have not been affected. 
### Math Scores by Grade:
![math scores](https://user-images.githubusercontent.com/92230478/141403701-c54ccd31-becb-4fbc-9541-2a58838cb999.PNG)
### Reading Scores by Grade:
![Reading Scorees](https://user-images.githubusercontent.com/92230478/141403718-3a527936-d777-468a-9de5-0d9889d8ea80.PNG)
* Because Thomas High School's 9th grade math and reading scores were replaced by NaN, it does not affect the scores of the other grade-levels and schools. They are exluded from having a numerical value.
### Scores by School Spending and School Size:
![p1](https://user-images.githubusercontent.com/92230478/141407140-a27b549a-7058-4d95-949a-535ea75e3ece.PNG)
![p2](https://user-images.githubusercontent.com/92230478/141407148-55b40620-78ed-43c6-bf01-10c439dd3c52.PNG)
### Average Scores by Spending:
![spending per stude](https://user-images.githubusercontent.com/92230478/141411668-a729a97b-00e5-414e-98a6-d669bbf07a52.PNG)
 * Thomas High School is in the $630-$644 per student range. With an overall passing of 90.630324%, Thomas High School is performing better than its other two counterparts in the same spending range: Rodriguez High School has an overall passing of 52.988247%, Figueroa High School with 53.204476%, and Ford High School at 54.289887% overall passing students. With removing the 9th grade reading and math scores, the average scores and the percent passing categories must have been reduced (other than the average reading score which increased) based on the changes for Thomas High School. These changes were very slight at less than 0.1%
### Average Scores by School Size:
![by school size](https://user-images.githubusercontent.com/92230478/141407552-520691ae-e359-4fd1-acf0-ab53699a406f.PNG)
* Thomas High School is a medium size school with a student body of 1000-2000 students. Without the Math and Reading Scores of the 9th Graders, the percent of students passing math, percent of students passing reading, overall percent passing, and average math score has all been lowered. The average reading score has been slightly raised. These changes are based on the changes for Thomas High School and are also small at less than 0.1%
### Average Scores by School Type:
![by school type](https://user-images.githubusercontent.com/92230478/141408602-ae0beb6b-c4c2-48d1-8bf1-be6fad174a41.PNG)
* Thomas High School is a Charter School and their new scores (without 9th grade Math and Reading) have lowered the charter school's percentage of students passing math, the percentage of students passing reading, the percentage of students overall passing, as well as the average math score. The average reading score has increased. These are based on the changes for Thomas High School, however, these changes are super tiny at less than 0.1%.
  
# Summary 
After replacing the 9th Grade Reading and Math Scores for Thomas High School we were able to witness some changes happening in this data set. All of these changes were in the Thomas High School bracket or another bracket that Thomas High School was included in such as District Summary, School Spending per student at $630-$644, Medium School Size, and Charter School. In each bracket we are able to see slight changes to the Average Reading Score, Average Math Score, Percent Passing Math, Percent Passing Reading, and Percent Passing Overall. In the District Summary, the Average Math Score dropped from 79.0 to 78.9. The percent of students passing math decreased from 75 to 74.8. The Average Reading Score remained the same, but the percent of students passing reading decreased from 86 to 85.7. The percent of students overall passing also lowered from 65 to 64.9. Because these scores and percentage changes were minimal,  the removal of Math and Reading scores of 9th graders at Thomas High School were not as significant as Maria would imagine it to be. However, it is critical for the School Board to have the correct values to ensure they are able to make decisions regarding budgets and priortites accordingly.

