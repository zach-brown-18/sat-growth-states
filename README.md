# State Mandatory ACT Testing

## Problem Statement:
The ACT overtook the SAT in overall test takers in 2012 ([source](https://www.washingtonpost.com/local/education/sat-to-drop-essay-requirement-and-return-to-top-score-of-1600-in-redesign-of-admission-test/2014/03/05/2aa9eee4-a46a-11e3-8466-d34c451760b9_story.html?tid=a_inl_manual)). The SAT reclaimed its spot as the top test taken in 2018 ([SAT source](https://reports.collegeboard.org/pdf/2018-total-group-sat-suite-assessments-annual-report.pdf)/[ACT source](https://blog.prepscholar.com/average-act-score-by-year)). Are the majority of test takers for either or both of these tests coming from state contracts and mandatory test taking across all high schools in a state? Identify potential states for the College Board to broker partnerships with.

---

### Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*object*|ACT 2017-19|All 50 states and the District of Columbia.| 
|**participation**|*float*|ACT 2017-19|The percent of the state's high school graduates that took the ACT for the year listed. A decimal value from 0.00 to 1.00| 
|**composite**|*float*|ACT 2017-19|Total ACT composite score. Excludes the optional writing section.| 
|**year**|*int*|ACT 2017-19|A year from 2017, 2018, or 2019| 
|**state**|*object*|SAT 2017-19|All 50 states and the District of Columbia| 
|**participation**|*float*|SAT 2017-19|The percent of the state's high school graduates that took the SAT for the year listed. A decimal value from 0.00 to 1.00| 
|**total**|*float*|SAT 2017-19|Total SAT composite score. Excludes the optional writing section.| 
|**year**|*int*|SAT 2017-19|A year from 2017, 2018, or 2019| 


---

### File structure

- [Code](./code) folder with Jupyter notebooks for data cleaning, visualisations and analysis.
- [Data](./data) folder with all data used in this project.
- [Plots](./plots) folder with images.
- [Presentation slides](./ppt.pdf)
- README.md

---

## Analysis

Percent of States with Perfect Participation Rate 2017-2019
|ACT|SAT|
|---|---|
|**32.0%**|**11.1%**|

The ACT leverages state contracts to elicit 100% participation in nearly one third of all 50 states and Washington DC.  
The SAT falls behind with 11.1%.

Which states can the College Board target for contracts to implement mandatory state-wide SAT testing?
![Texas and California](./Plots/texas-california.png)

Texas and California are the two most populous states in the country. Additionally, participation rates in both states are trending towards the SAT and away from the ACT. These two states make the perfect candidates to pursue for state contracts.

## Conclusions

The ACT owes much of its success to its state partnership program. 32% of states exhibited 100% participation rate between 2017-2019. Only 11.1% of states exhibited a 100% participation rate on the SAT during the same time period.

The data demonstrates a clear trend as states shift in participation from the ACT to the SAT. As states end their contracts with ACT, Inc. in favor of the SAT, the College Board must recognize an opportunity to gain a massive boost in test attendance through state partnerships.

Texas and California should be targeted most aggresively for these state contracts, primarily due to their large population size, and also due to their trend towards the SAT from 2017-2019. These two states are available for state contracts and provide the largest potential dividend.