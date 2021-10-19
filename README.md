# School_District_Analysis

## Project Overview 
The school board has requested and analysis of the math and reading standaized testing scores for the district highschools. Using school and student level data an analysis was performed to show the folloing metrics:

  1. Math and reading scores by grade 
  2. Scores by schoool spending 
  3. Scores by school size
  4. schores by school type 

Additionaly, there was evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders. While infomration is still being uncovered, a second analysis was perfomred with the math and reading grades for Thomas High removed. 
  

## Results 
Below we will review the results of the analysis and review how each metric was impacted by the removal of the Thomas High School 9th graders' scores being removed. 
  - The district summary: 
      - The table on the top shows the full student summary and the bottom is the same information without the Thomas 9th graders. The data has shifted downward slightly. While we'd expect few students to be counted, all the passing percentages moved down a few tenths of a percent. 
      ### Orginal District Summary
      ![district_summary_og](https://user-images.githubusercontent.com/86968320/137984927-0e2c2db9-2e2f-4729-a92a-870f9580840a.png)
      ### Updated District Summary
      ![district_summary_updated](https://user-images.githubusercontent.com/86968320/137984948-00661d35-5546-4194-b73b-44b598b4357c.png)

  - The school summary: 
      - Again with the full data set on the top and the appended on the bottom we can see that there is no impact to any school other than Thomas High School
     ### Orginal School Summary
     ![per_school_summary_og](https://user-images.githubusercontent.com/86968320/137985887-4e470f59-4f53-4e42-affc-d43a378f5ec1.png)

     ### Updated School Summary
     ![per_school_summary_updated](https://user-images.githubusercontent.com/86968320/137985901-54e9caf1-fb0b-4481-830a-4bd11f8ab626.png)

  - How does Thomas stack up?
      - Even with the removed data points, Thomas High remains the second highest performing school in our analysis. While they saw a slight drop in the overall passing percent (90.9% to 90.6%) they still performed strongly. 
      ### Orginal Top School Review 
      ![top_schools_og](https://user-images.githubusercontent.com/86968320/137986200-a28c6e5b-75ed-4361-8abd-c0ac91905b1a.png)

      ### Updated Top School Review 
      ![top_schools_updated](https://user-images.githubusercontent.com/86968320/137986212-fcc4e008-49a4-4357-b1f6-9b9fbc4b974b.png)

  - Looking even deeper at the data cuts we can see they way the Thomas High 9th graders score removal impacted other analysis. The four summary analysis below were unimpacted by the data change. While the Math and reading scores by grade showed a Nan value for Thomas 9th graders, the rest of the summery calucations,
      - Math and reading scores by grade: Nan values for the Thomas 9th graders 
      - Scores by school spending: unimpacted by the data removal 
      - Scores by school size: unimpacted by the data removal
      - Scores by school type: unimpacted by the data removal
       

 
## Summary
Overall the the anlysis with and without the Thomas High School 9th graders is not drasticly different. After replacing the 9th grade math and reading scores of Thomas High School, there were several minor changes to our initial anlysis. At the district level the average reading dropped .01%, and the overall passing rate decreased by about 0.10%. It was not enough to change the school's rank, but it will impact how other schools compare their metrics to Thomas High School. Given that about 25% of Thomas High School's data had to be omitted, its own metrics became less reliable, since, like with smaller schools, the calculations are susceptible to larger fluctuations due to the smaller sample size.
