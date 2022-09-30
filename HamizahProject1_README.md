# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Test Analysis

### Overview

The SAT and ACT are standardized tests that many colleges and universities in the United States require for their admissions process. This score is used along with other materials such as grade point average (GPA) and essay responses to determine whether or not a potential student will be accepted to the university.

### Problem Statement

Mr Zac is an educator that has since retired, he is planning to open a SAT/ACT prep course centre and he's undecided in which state he should consider to start his tuition centre. He's hopeful that this analysis will allow him to have peace of mind to make a decision.

We could analyse which states he should consider! Based on the number of participations and/or scores?


### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|index|ACT/SAT|State names of 50 states in the US, with District of Columbia| 
|participation_sat_17|float|SAT|State participation rate of SAT in 2017 (%)| 
|ebrw_sat_17|float|SAT|State mean score for Evidence-Based Reading and Writing (EBRW) in 2017| 
|math_sat_17|float|SAT|State mean score for Math in 2017| 
|total_sat_17|float|SAT|State mean total (combined score for ERW and Math) in 2017| 
|participation_act_17|float|ACT|State participation rate of ACT in 2017 (%)| 
|english_act_17|float|ACT|State mean score for English in 2017| 
|math_act_17|float|ACT|State mean score for Math in 2017| 
|reading_act_17|float|ACT|State mean score for Reading in 2017| 
|science_act_17|float|ACT|State mean score for Science in 2017| 
|composite_act_17|float|ACT|State mean score for Composite (Average score for English, Math, Reading and Science) in 2017| 
|participations_sat18|float|SAT|Participation rate in 2018 (%)| 
|ebrw_sat18|float|SAT|State mean score for Evidence-Based Reading and Writing (EBRW) in 2018| 
|math_sat18|float|SAT|State mean score for Math in 2018| 
|total_sat18|float|SAT|State mean total (combined score for ERW and Math) in 2018| 
|participation_act18|float|ACT|State participation rate of ACT in 2018 (%)|
|composite_act18|float|ACT|State mean score for Composite (Average score for English, Math, Reading and Science) in 2018| 


### Summary of Analysis

1. Comparing the scores
2. Looking into participation rates
3. Further insight into particpation rates and the correlation between the SAT and ACT for both years
4. Visualizing the participation rates on a choropleth


### Conclusion

- High participation rates for one test is usually lower for the other test
The participation for mandatory states correlates to the information gathered with the outside research.
- Due to more states accepting ACT instead of SAT. The dataset confirms that ACT is more widely taken-up.
- The median scores for ACT and SAT in 2017/2018 is not much of a range difference.
- Comparatively outside of the SAT, nearly 20-30% participants took the ACT as well.


### Recommendations

Based on research and analysis, considering that Mr Zac could widen his clientele pool by going to states that have both options to take SAT or ACT. We narrow down to 3 states Ohio, Idaho and Tennesee. To choose which state we looked further into the participation rates and the test scores. For the test scores, Tennessee did below avg compared to Idaho and Ohio in the ACTs. In the SATs, Idaho did below avg compared to the other 2 states. Finally we are going to look at the participation rates for Tennesee and Idaho. Idaho is more SAT dominant while Tennesee is ACT dominate however eventhough Idaho is SAT dominant there 30% of them that takes the ACT as well for both years. Tennesee only have 5% participation rate for the SAT.

Looking at the stats and the plots, Mr Zac should open his tuition prep course centre in Idaho. He will see both SAT and ACT students taking his courses.


