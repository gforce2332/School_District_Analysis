# School District Analysis

## Project Overview
Performed an analysis on student funding data and student's standardized test scores to provide insights at the school and district level.
After discovering ninth grade reading and math scores for Thomas High School (THS) appear to have been altered, an updated analysis was provided.

## Results
- District Summary was not affected after replacing math and reading scores with null values for THS while keeping the rest of the data intact.            
- ![School_District_Summary](https://user-images.githubusercontent.com/98711219/164155066-c5351762-4557-4099-9d02-b939eade4159.png)
- School Summary for THS dropped in the categories of passing math, reading and overall passing percentages between 25-30% after replacing ninth grade scores. 
 ![School_Summary](https://user-images.githubusercontent.com/98711219/164167033-6579dd58-1516-4f4d-b33e-88931adb436f.png)

  Below shows totals for THS prior to replacing ninth grade scores.
  ![THS_Before_Null_Values_Added](https://user-images.githubusercontent.com/98711219/164157753-e2974bcc-87a8-4019-935b-9d62798799b1.png)

- Prior to replacing the scores, THS performed in the top 5 schools. After replacing scores, THS sits 8th out of 15 schools.
![Top_Five_Performing_Schools](https://user-images.githubusercontent.com/98711219/164168023-8a2ec2d7-04e0-4568-b76e-309e7e8ca4e0.png)
![Bottom_Five_Performing_Schools](https://user-images.githubusercontent.com/98711219/164168030-cccac335-e3ac-4c57-a8f9-e4f516bfc80e.png)

- Replacing ninth-grade scores affect the following:

     * Only ninth-grade math and reading scores were affected. All other scores by grade remained unaffected;
     ![Average_Math_Scores_by_Grade_ _School](https://user-images.githubusercontent.com/98711219/164169206-e2705326-297f-4e0a-8dc7-0f3570882188.png)
     ![Average_Reading_Scores_by_Grade_ _School](https://user-images.githubusercontent.com/98711219/164169217-203d1bd8-e0b3-4208-b4d7-f9133b64a98f.png)

     * Scores by school spending were reduced by less than 1% for THS;
     ![School_Spending_Summary](https://user-images.githubusercontent.com/98711219/164169320-c09f5716-e6ac-4bf5-9b53-52ef3069f383.png)

     * Scores by school size was unaffected; and
     ![School_Size_Summary](https://user-images.githubusercontent.com/98711219/164169356-e96dc8b8-621a-450c-9ac3-8c6d96d5ced0.png)

     * Scores by school type also remained unaffected. 
     ![School_Type_Summary](https://user-images.githubusercontent.com/98711219/164169382-ee9b7e61-3101-4539-a3d3-2bb46f182b55.png)


## Summary
- The four major changes that occurred is the number of total students, the number of students counted at THS, the average math and reading scores, and the overall percentages for math and reading at Thomas High School. The removal of data implies a decrease in the count of total students overall, and total students at THS, specifically for this analysis. And since the population amount was decreased, this leads to a change in average scores and score percentages. Due to the fact that these score and percentage changes were minimal, we can assume that the removal of math and reading scores of 9th graders at Thomas High School not as significant as we would imagine it to be.
