# School_District_Analysis

## Overview of the school district analysis
A school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonestly; specifically, reading and math grades for Thomas High School ninth grade appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help.

Our objective is to replace the math and reading scores for Thomas High school with NaNs while keeping the rest of the data intact. Once the math and reading scores have been replaced, our next objective will be to reapt the school district analysis completed in this module and write up a report to describe how these changes impacted the overall analysis.

## Results

- How is the district summary affected?

The district summary statistics are slightly lower than when we initially calculated the values for the Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, and % Overall Passing.

Module Statistics:
![image](https://user-images.githubusercontent.com/89496798/140695146-b48fc7a0-c328-48d7-8b3d-72d303e076c2.png)

Challenge Statistics:
![image](https://user-images.githubusercontent.com/89496798/140694986-d595df82-7297-4970-828e-ebde3447f304.png)

- How is the school summary affected?

The school summary was significantly affected especially in regards to Thomas High School's % Overall Passing. The % Overall Pricing for Thomas High School decreased from 90.58 percent to 65.08 percent:

Module Statistics:
![image](https://user-images.githubusercontent.com/89496798/140695672-22123753-6dc5-4cff-a614-2932d2cdeb9f.png)

Challenge Statistics:
![image](https://user-images.githubusercontent.com/89496798/140695739-10e986db-639e-4359-9d11-f04e6634ac3f.png)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Looking at the snippets above, it's apparent that Thomas High School's performance decreased for those who passed math, reading, and overall. The % Passing Math decreased from 93.27 to 66.91 and the % Passing Reading decreased from 97.31 to 69.66.

Module - Thomas High School
![image](https://user-images.githubusercontent.com/89496798/140697253-22ae6219-2433-468d-901e-38877cbabf7e.png)
![image](https://user-images.githubusercontent.com/89496798/140697575-c81179a5-97ee-4e12-a5c6-b11cdcad6f1d.png)

Challenge - Thomas High School
![image](https://user-images.githubusercontent.com/89496798/140697263-a67563a5-1d7d-42bd-9273-a8e670f2ca02.png)
![image](https://user-images.githubusercontent.com/89496798/140696843-24b06774-0ed4-4ded-8510-e56eddae2a92.png)


- How does replacing the ninth-grade scores affect the following:

    - Math and reading scores by grade
    The math and reading score averages by grade were only affected slightly. The Average Math Score decreased from 83.42 to 83.35. The Average Reading Score increased from        83.85 to 83.90. The slight variance is due to the values that may not have been correct were nulled out as NaN:
 
 Module - Thomas High School - Average Score
 
 ![image](https://user-images.githubusercontent.com/89496798/140698744-e9db9cdd-d5e7-433c-b619-0924e623afb9.png)

Challenge - Thomas High School - Average Score

![image](https://user-images.githubusercontent.com/89496798/140698796-16de732f-2a0b-42ef-96bd-9b0315587391.png)


    - Scores by school spending
    
 The scores by school spending saw no change after replacing Thomas High School's 9th grade scores:
 ![image](https://user-images.githubusercontent.com/89496798/140700770-a07780c3-3dcb-44bd-9f12-dbde20f9d3ee.png)

    - Scores by school size
    
  The scores by school size also did not see a change after Thomas High School's 9th grade scores were replaced:
  ![image](https://user-images.githubusercontent.com/89496798/140701338-5d48fbce-0590-479d-944d-fd5c9d14f15d.png)

    - Scores by school type

The scores by school type also did not see a change:
![image](https://user-images.githubusercontent.com/89496798/140701569-c4ae86b6-b99a-41a5-80cb-e3df770058dd.png)
