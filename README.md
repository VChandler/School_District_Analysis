# School District Analysis
## Overview
An analysis was completed earlier of the school district's state-testing standards showing grades by grade level, schools, school spending, school size, and school types.  After additional review, the source data of children's scores indicated signs of academic dishonesty within 9th grade at Thomas High School.  As a result, the goal of this project is to remove the suspect scores and re-run the analysis to identify potential impact.

## Results
* How is the district summary affected?  
Overall, the district saw a slight decrease in average math scores (.1 pct point), % passing math (.2 pct point), % passing reading (.1 pct point), and % overall passing (.3 pct point).  Before removing the suspect grades:  
![district-before](https://user-images.githubusercontent.com/88070999/132957251-433dbe59-4606-4e8e-b0cb-83aa7d357ed7.png)  
After:  ![district-after](https://user-images.githubusercontent.com/88070999/132957255-0c34984c-e945-4760-a044-4a221ef6c901.png)  

* How is the school summary affected?  
The school summary showed a decrease in numbers for Thomas High School only:  
Before:  
![thomas-before](https://user-images.githubusercontent.com/88070999/132957396-061bc3aa-fafc-4dab-881d-77426d39a727.png)  
After:  
![thomas-after](https://user-images.githubusercontent.com/88070999/132957487-341cca8d-4997-4b8e-b323-f28de981a0f1.png)  
Overall, Thomas dropped by .1 for avg reading score, .1 for % passing math, .3 for % passing reading, and .3 for % overall passing.

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?  
Relative to the other schools, Thomas High School was still able to rank 2nd in terms of % overall passing:  
![top school-after](https://user-images.githubusercontent.com/88070999/132957765-fd9c5cf5-9d69-4902-b48c-e451537f1933.png)  
This is the same ranking as the first version, before the ninth grader scores were removed.

* How does replacing the ninth-grade scores affect the following:
  * Math and reading scores by grade  
  Though Thomas High School no longer has data points for ninth grade scores, it is clear that scores for 10th - 12th graders for the school are still in the upper levels compared to other schools.  Updated math scores:  
  ![math by grade after](https://user-images.githubusercontent.com/88070999/132957860-8e92e4d6-e475-4831-9004-a257aff0bbca.png)  
  Updated reading scores:  
  ![reading by grade after](https://user-images.githubusercontent.com/88070999/132957868-903a760a-e1c9-4703-bdae-ace9d4505f4c.png)

  * Scores by school spending  
  When adding spending ranges per student as a category to the schools, the removal of the scores did not have a significant impact on the overall averages for the $630-$644 (the category in which Thomas High School belongs):  
  ![spending-after](https://user-images.githubusercontent.com/88070999/132957954-0ed27dc8-a072-4158-8b1a-d15de44db9af.png)  
  In fact, when rounding to one decimal, there was no change whatsoever in the scores.
 
  * Scores by school size  
  Similarly, when account for the grade removals, we did not see a change in averages when grouping by school sizes (of which, Thomas is considered "Medium"):  
  ![school size after](https://user-images.githubusercontent.com/88070999/132958081-883b869b-3182-42af-bd8d-96fdd7fe5355.png)

  * Scores by school type  
  Thomas High School is categorized as a "charter" school.  After removing the scores, there was no change to the averages for "charter" schools:  
  ![school type after](https://user-images.githubusercontent.com/88070999/132958102-4915d6ef-72f7-4603-97ad-f8d66b9c7e52.png)

## Summary
In summary, the removal of the ninth grade scores for math and reading at Thomas High School had little impact when aggregating by school spending, school size, and school type.  One would need to go out to multiple decimal points to find the changes.  However, at a school district level, the district saw four changes to averages:
* Slight decrease in average math scores (.1 pct point)
* Decrease of .2 pct points in % passing math
* Decrease of .1 pct point in % passing reading
* Decrease of .3 pct point in % overall passing  

At a school level, Thomas High School dropped by .1 for avg reading score, .1 for % passing math, .3 for % passing reading, and .3 for % overall passing.
