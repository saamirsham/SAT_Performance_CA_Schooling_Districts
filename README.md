# Analysing the SAT Performance of California School Districts


The California Department of Education is attempting to identify districts with low performance, where students struggle to meet the SAT benchmark as stipulated by CollegeBoard and university standards. The focus of this project is to undertake a detailed analysis of these districts within California and compare the findings with established college SAT standards.


# Data Dictionary


|Feature|Type|Dataset|Description|
|---|---|---|---|
|School|object|sat_act_by_college|Name of College|
|Number of Applicants|int|sat_act_by_college|Number of Applicants| 
|Accept Rate|float|sat_act_by_college|Acceptance rate| 
|SAT Total 25th-75th Percentile|object|sat_act_by_college|Range of Scores Accepted by Colleges| 
|25th Percentile|float|sat_act_by_college|25th Percentile Score of Acceptances| 
|75th Percentile|float|sat_act_by_college|75th Percentile Score of Acceptances| 
|Score_Bracket|object|sat_act_by_college|Bracket within 25th Percentile Score Fits in| 
|DName|object|sat_2019_ca|District Name|
|NumTSTTakr12|float|sat_2019_ca|Number of Test Takers| 
|TotNumBothBenchmark12|float|sat_2019_ca|Number of Test Takers Scoring Above Benchmark| 
|PercOverBench|float|sat_2019_ca|Percentage of Test Takers Scoring Above Benchmark| 
|OverCAAvg|int|sat_2019_ca|1: Over CA Average, 0: Below CA Average| 
|Z_Scores|float|sat_2019_ca|Number of Standard Deviation away from Mean (Over Percentage of Test Takers Scoring Above Benchmark|




# Executive Summary

This analytical summary offers an in-depth investigation of the SAT performance within California school districts, with an aim to comprehend how these results align with the college SAT expectations. Utilizing different visualization tools, the report presents detailed insights into current trends and performances, offering possible solutions to improve the standing of SAT scores in these districts.

Figures 1 and 2 display key data points. Figure 1 demonstrates the Z-score of the percentage of students achieving scores higher than the SAT benchmark, providing a comparative measure of the districts' performances. Notably, fewer districts present a Z-score of -2, indicating that districts are not underperforming to an extreme degree compared to those outperforming. This evidence suggests a potential normal distribution of the district performances, an interpretation further corroborated by Figure 2. Presented as a box plot, Figure 2 effectively visualizes the maximum, minimum, and median percentages of students who surpass the benchmark, confirming the normally distributed SAT performance across the districts.

Further analysis provides a more nuanced understanding of the district performance. Figure 3 indicates a larger portion of students scoring below the district average than those scoring above it, a potentially concerning trend. Expanding on this, Figure 4 shows how the districts compare in terms of the percentage of students scoring over and under the average SAT benchmark percentage. A primary conclusion from these figures suggests that districts with larger test-taking populations generally underperform, with fewer students achieving scores above the SAT benchmark. This pattern requires further attention to ensure educational equity and success across the state's diverse student population.

Turning our attention to college expectations, Figures 5 and 6 offer valuable insights. A significant number of colleges, as shown in Figure 5, require SAT scores higher than the prevailing benchmark, implying heightened competition. Figure 6 further confirms this trend, visualizing the score expectations from college applicants. These figures raise the question about the adequacy of the current SAT benchmark, suggesting it may be outdated and not reflective of the rising academic competitiveness of colleges.

In conclusion, the analysis helps to identify the districts that need concentrated attention in terms of improving their students' SAT scores. Based on these findings, the California Board of Education should consider a two-pronged approach to address these issues. First, they should target improvements in SAT preparation, focusing on districts with larger student populations that presently display lower overall percentages of students achieving scores above the benchmark. This might involve developing specialized SAT prep programs and allocating additional resources to ensure these students are fully supported.

Second, the board should aim for an equitable distribution of resources for SAT preparation across all districts. This may involve funding for additional test attempts and providing online resources to facilitate at-home learning and practice. Such strategic allocation of resources could help bridge the gap between current district performance and rising college expectations, thereby ensuring that all students have the best possible opportunity to succeed in their post-secondary endeavors.
