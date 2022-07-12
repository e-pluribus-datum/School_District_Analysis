# School District Analysis

## Overview
The math and reading scores for ninth graders at a particular school were removed due to suspicion of academic dishonesty. The effects of removing these scores from the data set was explored, especially pertaining to summary statistics for the district.

## Results

Replacing the ninth-grade scores of students at Thomas High School had the following effects:

### District Summary

#### Before:
![district_summ_before](./Resources/before_tables/before_district_summ.png)

#### After:
![district_summ_after](./Resources/after_tables/after_district_summ.png)

There was little (0.1 points) to no change for average scores in each subject, and a 0.3 p.p. decrease in overall passing rate.

---
### School Summary

### Before:
![school_summ_before](./Resources/before_tables/before_school_summ.png)

### After:
![school_summ_after](./Resources/after_tables/after_school_crop.png)

The average math score for Thomas High School decreased by about 0.06 points, with the average reading score increasing by about the same amount. There was a decrease in overall passing by about 0.31 p.p., to 90.63%.

---
### Relative Ranking

![top_five](./Resources/after_tables/after_top_5.png)

Score replacement did not affect Thomas High School's second-place rank in overall passing rate.

---
### Math and Reading Scores by Grade

As intended, only the scores for 9th graders at Thomas High School were altered, being replaced by NaN for both subjects.

---
### Scores by School Spending

![by_spending](./Resources/after_tables/after_spending.png)

There was no change in the reported values for scores grouped by per-student spending in Thomas High School's cohort ($631-645).

---
### Scores by School Size

![by_size](./Resources/after_tables/scores_by_size.png)

There was no change in the reported values for scores grouped by school size in Thomas High School's cohort (1000-1999).

---
### Scores by School Type

![by_type](./Resources/after_tables/scores_by_type.png)

There was no change in the reported values for scores grouped by school type in Thomas High School's cohort (Charter).

## Summary

Replacing the scores for ninth graders at Thomas High School had a miniscule effect on the high school's scores. There appeared to be no change in values when the school was considered in the aggregate, such as being grouped by spending, size, or school type. An exception to this is the district summary, which shows a small (0.3 p.p.) decrease in overall passing rate. When taken to two significant digits of value, there were no changes in scores at all. 