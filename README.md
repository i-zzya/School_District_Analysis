# School_District_Analysis

## Overview
After helping Maria analyize "City School" records, it was determined that there was academic dishonesty. The school in question, Thomas High School. 
The Reading and Math grades for all ninth graders at THS show evidence of being altered. We replaced ninth grade math and reading scores with null values to find the impact this has had on our overall analysis.  

## Results

* ### How the district summary affected?

   The district summary didn't change much. Less than .25 of a difference.
  
  before:
   
   ![ds 1](https://user-images.githubusercontent.com/99618784/160259587-9f852e26-328d-488f-adfc-58b50496199c.PNG)
  
  after:
   
   ![ds 2](https://user-images.githubusercontent.com/99618784/160259593-28d98c8b-6302-40f2-8cc7-da00463ce122.PNG)


* ### How the school summary was affected:
   
   -Positively. Prior to replacing the scores for 9th grade, Thomas High School had an overall passing of just 65%. Afterwards the overall passing percentage was 90%. 
 
 before:
  
  ![ss 1](https://user-images.githubusercontent.com/99618784/160257566-e6a34bf2-aca5-41a7-91ea-09c4ddc2ce13.png)
 
 after:
 
 ![ss 2](https://user-images.githubusercontent.com/99618784/160257917-2ad0a102-5159-4421-82d0-6f69eb675aaf.png)


* ### How replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

   -Positively. After replacing the ninth grade values, Thomas High School was ranked in the Top 5 schools overall. 

  ![top5schools](https://user-images.githubusercontent.com/99618784/160258344-8152ee1e-5a0e-4af5-9a3d-fd9abc542111.PNG)


### How replacing the ninth-grade scores affect the following:

* Math and reading scores by grade

   -Since we only replaced the 9th grade reading scores with null values and left grades 10th through 12th intact, you will see NaN as the value for 9th. This also means we can't compare how 9th graders at THS did next to other schools. 
      
![math](https://user-images.githubusercontent.com/99618784/160259982-93084233-0b97-4a69-b99a-d5b1e86bb0bd.PNG)

![reading](https://user-images.githubusercontent.com/99618784/160259985-cf9cf81f-93a6-4d14-a415-3ccb28a11f44.PNG)


* Scores by school spending

   -It decreased by a few dollars. 
   
   before:
   
   ![old](https://user-images.githubusercontent.com/99618784/160260296-d7ed19e0-a2bd-4df1-83f3-fceec6cbb938.PNG)

   after:
   
   ![new](https://user-images.githubusercontent.com/99618784/160260301-f0c407c0-d52d-40a2-9d28-970efdfd55a4.PNG)


* Scores by school size

   -Again, minimal changes
   
   before:
   
   ![old ss](https://user-images.githubusercontent.com/99618784/160260411-293a71e9-bf8a-4b57-93eb-a19b76bed796.PNG)

   after:
   
   ![new ss](https://user-images.githubusercontent.com/99618784/160260417-2e317dbd-bc32-4693-8ed0-ad8b990496d8.PNG)


* Scores by school type

   -you guessed it, minimal changes 
   
   before:
   
   ![old scores](https://user-images.githubusercontent.com/99618784/160260477-4b3fb11d-4f07-4903-9577-49cd76270833.PNG)

   after:
   
   ![scores new](https://user-images.githubusercontent.com/99618784/160260485-71cf1d58-0bf6-414c-83ce-b49e9c7d3532.PNG)


## Summary: 
The biggest change that we notcied was the jump Thomas High School made into the Top performing schools. THS had a 25% increase once we replaced the 9th grade values. 





