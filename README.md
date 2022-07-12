# School_District_Analysis
## Overview:
  In this challange we were asked by the school board to analyze various aspects of information for 15 schools in a particular disctrict. We were able to analyze standardize testing results for each grade level in each school, and see what affects the scores with certain variables, such as budget per student or school size or school type. As we were working through this analysis we were notified that there had been some academic dishonesty in the reading and math testing results from the ninth-graders in a particular school, Thomas High School. In order to keep the data fair we were asked to remove all the math and reading scores from the ninth-graders at Thomas High School. We will now explore how this deletion of data affected the schools overall scores and how it compares to other schools.
  
## Results: 

* When it comes to the district summary for this analysis, one can say it did not affect the data at all. This can be contributed to the fact that the 9th grade class of Thomas High School was rather a small number of students; a total of 461 students which comes out to approximately 1.18% of the total number of students in the district. This did not have a visible effect for this summary analysis, which can be seen below, as the first image shows the district summary without the ninth-grade class and the one following shows all students accounted for (this particular summary was taken from the work that was done throughout the module.)

![new_district_summary](https://github.com/Mparra14/School_District_Analysis/blob/main/District_Analysis/District%20Summary%20(new).png)

![old_district_summary](https://github.com/Mparra14/School_District_Analysis/blob/main/District_Analysis/District%20Summary(old).png)

* For the school summary analysis,in the begining we were actually able to see a big difference in the scores just in the school we altered. One of the main reason why deleting the ninth-grade class from this high had such a great impact on the average of scores, it wass because of the student size of Thomas High School.The ninth-grade class accounts for approximately 28% of the total school size, and if the ninth-grade had high testing scores, this will most definetly bring the overall passing percentage down, which is why it was necessary to make some alterations to the school summary that would only include the 10th-12th graders; as soon as we replaced the scores with those from just the 10th-12th grade, and adjusted the school size to just include students from those grades. Comparing this new data frame with the old data frame that included ninth-graders, you can see that it decreased the percentage overall by approximately 0.31%. Please see below for images of the new data frame and old date frame that included the ninth grade class of the Thomas High school (this was again taken from the work done throughout the module.)

![school_summary](https://github.com/Mparra14/School_District_Analysis/blob/main/School_Summary%20(new%201).png)

![old_school_summary](https://github.com/Mparra14/School_District_Analysis/blob/main/School_Summary%20(old).png)

* Without the ninth-grade class, Thomas High School still remains in the number 2 spot as their overall passing percentage is a 90.63%. The deletion of the ninth-grade class did not impact their school ranking since their score only amounted to 0.31% of the overall passing perncentage. This was not enough to bring the ranking down since the 3rd ranking school had 90.59% of overall passing percentage. This can be seen in the image below. 

![Top_5_schools](https://github.com/Mparra14/School_District_Analysis/blob/main/top_5_schools.png)

* How does replacing the ninth-grade scores affect the following:

* Looking at the math and reading scores by grade, you can see that replacing the ninth grade scores with Nan's are still into effect in this section. Due to the ninth-graders in Thomas High School not having these score there is no data to analyze from this grade at this particular school. This did not affect the other grades since their score did not depend on the ninth graders. Please see below for both math and reading scores. As it can be seen these scores did not affect any other score in that school. 
  
![math_score_grade]()

![reading_score_grade]()
  
 
* While examining the scores by school spending, you can see that not much changes in Thomas High School data, their spendature per student falls in the ranges of $631-$645 and while is on the higher side of the range, it certainly did not mean that having this amount per student increases their test scores, because their overall passing percentage is 63%, unlike those schools with lower per student budgets, which were able to reach that 90% overall passing for both reading and math. Therefore, having the ninth grade scores deleted from one high school did not impact this data set, this can be seen below. 
 
 ![score_by_school_spending]()
  
* In this particular data frame, we can see that the the medium and smaller sized schools are able to achieve higher overall math and reading scores unlike larger schools. This data frame supports the idea that having smaller size classes aids the teacher as she can have more time for individual learning, therefore higher test scores. Again having the ninth grade scores replaced for one high school, did not alter the results since this school was already mid sized and their overall scores for their 10th-12th graders were pretty high. Please see image below for evidence. 
 
 ![scores_by_school_size]
  
 *Scores by school type
 * The school type testing scores were much higher from those students that were enrolled in charter school rather than district schools, this is evident as charter schools are smaller in size which was a factor seen int the last data frame for successfule scores. Because Thomas high school is also a charter school, we have to see if the ninth grade deletion had any impact on this data set, and it did not. 

## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

One of the changes that can be seen 
