# censusdata_white_black

## Table of contents

* [General Info](#general-info)
* [Dataset](#dataset)
* [Technologies](#technologies)

## General Info

Introduction
In this analysis, we will be looking at the "Current Population Survey, 2020 Annual Social and Economic (ASEC) Supplement" conducted by the Bureau of the Census for the Bureau of Labor Statistics.

Importance of the Census Data
The Census data helps determine how much funding the federal governments allocate to state governments and local communities, including programs that benefit lower-income families such as Medicaid, special education grants, and more.

Objective
This analysis takes a closer look at differences between the White and Black communities concerning factors such as education, income, health care, and more. These insights could help federal governments decide where to allocate funds to address existing issues in black communities.

## Dataset

Dataset Description
This analysis uses the "Person (SAS/CSV)" record type which originally has 157,959 rows and 840 columns of which 12 columns are chosen for the statistical analyses.

Except for one column, all columns are integers. Two columns contain continuous variables, while the others contain categorical variables.

In addition, the analyses only look at data for race White and Black in the race column. Using this modified dataset, eight statistical tests are conducted to assess whether race (White and Black) affects:

<ul><li>Receiving financial assistance</li></ul><br>
Poverty level<br>
Having health insurance coverage<br>
Health status<br>
Receiving medicaid<br>
Educational attainment<br>
Employment status<br>
Income

and two statistical tests to assess whether:<br>
Education affects poverty level<br>
Poverty level affects health status

Statistical tests run in this analysis:<br>
Chi-Square test<br>
Cramér's V<br>
Welch's t-test<br>
which will be further explained in their respective sections.

## Technologies

Project is created with:<br>
Python

