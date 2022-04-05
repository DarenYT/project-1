#### Introduction
In recent years, more and more states have been introducing mandatory testing for their K-12 students, with the aim of making them better prepared for college or working life, occasionally even when there is already another testing system in place. In this project, I will examine if the change of testing is truly beneficial, and whether it is worth the cost.
<br>
<br>

#### Data Dictionary
<br>
<br>
|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|string|all_tests_years<br>all_tests_years_part<br>all_tests_years_scores|State that produced the results| 
|participation|float|all_tests_years<br>all_tests_years_part<br>all_tests_years_scores|Percentage of test-takers out of all<br>the enrolled students in the state|
|act_participation_(year)|float|all_tests_years<br>all_tests_years_part<br>all_tests_years_scores|Percentage of test-takers of the ACT out of all<br>the enrolled students in the state|
|sat_participation_(year)|float|all_tests_years<br>all_tests_years_part<br>all_tests_years_scores|Percentage of test-takers of the SAT out of all<br>the enrolled students in the state|
|act_score_(year)|float|all_tests_years<br>all_tests_years_part<br>all_tests_years_scores|Average total score (out of 36) for the ACT for that state for that year|
|sat_score_(year)|float|all_tests_years<br>all_tests_years_part<br>all_tests_years_scores|Average total score (out of 1600) for SAT for that state for that year|
|total_participation_(year)|float|total_part| The sum of participation rates of both ACT and SAT|
<br>
<br>

#### Analysis
My data analysis revealed that two states, Colorado and Illinois, had recently changed from ACT mandated testing to SAT mandated testing and were producing worse results across the board. one reason given for doing so, was to allow for more standardised [data gathering](https://mindfish.com/which-states-require-the-sat/) in order to better assess the students capabilities. However, my data analysis also indicated that enforcing mandatory tests increases the variance of the test results, causing any data gathered to be less meaningful
<br>
<br>

#### Conclusion
My final conclusion is that there does not seem to be any observable benefits for the student population for the money to be spent in this manner.
