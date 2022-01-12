# School_District_Analysis

## Overview 
The point of this analysis was to get rid of the Thomas High School ninth graders' math and reading scores because of suspicions of academic dishonesty. While getting rid of these values, we were supposed to keep the rest of the data intact. By doing this, we needed to determine how these changes would affect the overall analysis. We want to still be able to see how each school performed relative to one another with the Thomas High School 9th grade scores being marked as NaN.
## Results
### How is the district summary affected?
Below is the District Summary before removing Thomas High School 9th graders
![Original District Summary](https://user-images.githubusercontent.com/90940985/149186103-bc1e7454-a6ad-4a02-8b72-35b31c27d152.jpg)

This is the District Summary after removing Thomas High School 9th graders.
![Challenge District Summary](https://user-images.githubusercontent.com/90940985/149186127-a1b3b42e-c473-4c85-bc25-620dea799175.jpg)

As you can see, the number of students decreased as well as the Average Math Score.

### How is the school summary affected?
  The school summary is not affected because it is per school, so the only school affected would be Thomas High School itself. 
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  
  Below is the School Summary before removing THS 9th graders:
  ![OG School Sum](https://user-images.githubusercontent.com/90940985/149187865-4d8cf8bc-ad9d-41bc-8023-4ef2c85e4bda.jpg)
  
  And this is the school summary after removing THS 9th graders:
  ![Final Challenge School Sum](https://user-images.githubusercontent.com/90940985/149188626-f394c3ea-bf9c-4caf-8f3d-1b4e31380449.jpg)

As you can see, the average passing % for math, reading, and overall decreased but did not move their ranking.

### How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
  Without 9th grade scores, we only see 10th-12th grade scores and cannot compare to other schools
  
  - Scores by school spending
  There is a slight difference in the average scores within THS's spending bucket, but nothing too impactful and no impact to other buckets.
Before removing THS 9th Graders:

![Spending OG](https://user-images.githubusercontent.com/90940985/149190612-bcc1e00f-4147-482f-8de3-ffaee52c3b61.jpg)

After removing THS 9th Graders
![Spending Challenge](https://user-images.githubusercontent.com/90940985/149190623-cb8f3493-bac6-4829-9641-6aafc4cb0de8.jpg)

 - Scores by school size
 This is similar with the spending difference, there is a slight change in the average score for Medium Size schools but no change for other size schools.
 
 Before removing THS 9th Graders:
 
 ![Scores OG](https://user-images.githubusercontent.com/90940985/149191218-bdb9743c-5e96-44eb-85b9-78fc40259b3d.jpg)

After removing THS 9th Graders:

![Scores Challenge](https://user-images.githubusercontent.com/90940985/149191292-67129be5-5f50-44b9-a0af-015791476384.jpg)

  - Scores by school type
The District school types were unchanged but the charter school types average scores and % passing were slightly changed.

Before removing THS 9th Graders;

![Type OG](https://user-images.githubusercontent.com/90940985/149191788-45cb63a0-0538-43bc-a1af-d1890cc4de8b.jpg)

After removing THS 9th Graders:

![type Challenge](https://user-images.githubusercontent.com/90940985/149191834-32f7990d-bba9-46a3-babb-11a416e48bcf.jpg)

## Summary
Some changes made to the school district analysis after the reading and math scores were replaced were that we had to change the total number of students by subtracting THS 9th graders. Another change was that we had to use this new student count to calculate new average scores and passing percentages for district summary. We then had to calculate the average scores and passing percentage for just 10th-12th graders at THS. After we had the new percentages and average scores, we had to change our code to replace the old scores with the new scores and percentages.
