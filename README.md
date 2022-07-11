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

*How does replacing the ninth-grade scores affect the following:
  *Math and reading scores by grade
  *Scores by school spending
  *Scores by school size
  *Scores by school type

Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
