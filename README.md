# School District Analysis
During regular analysis of local high schools on behalf of the school board, officials discovered Thomas High School 9th grade scores show evidence of academic dishonesty. This report analyzes the impact of removing this class completely on the overall analysis of the school district's performance.

## Impact of Academic Dishonesty
### The impact at Thomas HS and Beyond
How much did Thomas HS's scores change due to the faulty data for the 9th grade class? In a review of math and reading scores by grade, the change is drastic. The 9th grade class' results have been removed and now shows as NaN, or "not a number".

|           | Previous Scores | New Scores |
|-----------|-----------------|------------|
|Math Scores|![Math_Before.png](https://github.com/kaileymd/School_District_Analysis/blob/main/DataFrames/Math_Before.png)|![Math_After.png](https://github.com/kaileymd/School_District_Analysis/blob/main/DataFrames/Math_After.png)|
|Reading Scores|![Reading_Before.png](https://github.com/kaileymd/School_District_Analysis/blob/main/DataFrames/Reading_Before.png)|![Reading_After.png](https://github.com/kaileymd/School_District_Analysis/blob/main/DataFrames/Reading_After.png)|

In a comparison at the high school level, however, the removal of Thomas HS's 9th grade class was the difference of a few tenths of a percent across the board. As a result, this did not greatly impact the summary statistics of Thomas HS and did not change its standing as a top-ranking high school.

#### Previous Top High School Rankings:
![Top_HS_Before.png](https://github.com/kaileymd/School_District_Analysis/blob/main/DataFrames/Top_HS_Before.png)

#### New Top High School Rankings:
![Top_HS_After.png](https://github.com/kaileymd/School_District_Analysis/blob/main/DataFrames/Top_HS_After.png)

These small changes to Thomas HS's data does carry over into the district summary, creating a slight decrease in academic acheivement for the district.

#### Previous District Summary:
![District_Before.png](https://github.com/kaileymd/School_District_Analysis/blob/main/DataFrames/District_Before.png)
#### New District Summary:
![District_After.png](https://github.com/kaileymd/School_District_Analysis/blob/main/DataFrames/District_After.png)

### Data Impact, Categorically
Thomas HS is a member of its school district, but it also represents schools of its size and type. While it slightly impacted the academic acheivement of the district, did it change the outcome of schools in its category?

Thomas HS is a medium size school and did not change the score outcomes of schools in its category:
![Size_After.png](https://github.com/kaileymd/School_District_Analysis/blob/main/DataFrames/Size_After.png)

Similarly, it did not impact the score outcomes of schools with a similar size budget:
![Spending_After.png](https://github.com/kaileymd/School_District_Analysis/blob/main/DataFrames/Spending_After.png)

Thomas HS is a charter school, like roughly half of the schools in this district, and also did not change the score outcomes here:
![Type_After.png](https://github.com/kaileymd/School_District_Analysis/blob/main/DataFrames/Type_After.png)

## Conclusion
Although the academic dishonesty found in Thomas HS's 9th grade class was not distinguishable at a categorical level and did not impact Thomas HS's school ranking, the removal of the 9th grader's scores did result in a decrease in the academic achievement of the district. The four areas impacted were:
- Average Math Scores
- % Passing Math
- % Passing Reading
- % Overall Passing
