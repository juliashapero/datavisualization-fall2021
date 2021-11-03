# Assignment 4: Interviewing a Dataset

## Dataset

[CPS Aug 2021 Data](https://github.com/juliashapero/datavisualization-fall2021/blob/main/CPS%20Aug%202021%20Data%20Cleaned%20FINAL.csv)

## Cleaning Dataset

* Removed rows that did not have 201 under HUFINAL (201s were completed interviews)
* Deleted last two rows that were missing data
* Deleted 334 columns that were not relevant to information we're looking for

## Questions about Dataset

1. What is the difference between single mother households and single father households? 
2. How do single mother and father households differ by race?
3. How do single mother and father households differ among Hispanic and non-Hispanic households?

## Analyzing Dataset

### Question 1

* Made a pivot table with the dataset
* Used hrhtype (household type) in the rows section
* Used HUFINAL in the values section
* Looked at 3 (UNMARRIED CIVILIAN MALE-PRIM. FAM HHLDER) and 4 (UNMARRIED CIV. FEMALE-PRIM FAM HHLDER)

### Question 2

* Made a pivot table with the dataset
* Used ptdtrace (race) and hrhtype (household type) in the rows section, with hrhtype under ptdtrace
* Used HUFINAL in the values section
* Looked at 3 (UNMARRIED CIVILIAN MALE-PRIM. FAM HHLDER) and 4 (UNMARRIED CIV. FEMALE-PRIM FAM HHLDER)
* Used Excel formulas to divide 3 and 4 by the total number in each section and multiply by 100 to give a percentage

### Question 3

* Made a pivot table with the dataset
* Used pehspnon (hispanic/non-hispanic) and hrhtype (household type) in the rows section, with hrhtype under pehspnon
* Used HUFINAL in the values section
* Looked at 3 (UNMARRIED CIVILIAN MALE-PRIM. FAM HHLDER) and 4 (UNMARRIED CIV. FEMALE-PRIM FAM HHLDER)
* Used Excel formulas to divide 3 and 4 by the total number in each section and multiply by 100 to give a percentage

## Answers to Questions

1. The number of single mother households is more than double single father households in this sample, with 14163 single mother households and 6349 single father households.
2. While the portion of single father households is similar across white, Black, Asian, American Indian/Alaskan Native and Hawaiian/Pacific Islander households and ranges from 6-9%, the portion of single mother households is vastly different. Among white and Asian households, single mother households represent 10-11% of the sample. On the other hand, about 32% of Black households, 30% of American Indian/Alaskan Native households and 20% of Hawaiian/Pacific Islander households are led by a single mother. 
3. The portions of Hispanic households that are single father households and single mother households are larger than the portions of non-Hispanic households in both categories. While almost 10% of Hispanic households are led by a single father and 21% by a single mother, about 6% of non-Hispanic households are led by a single father and 13% by a single mother. 

## Sample Headline and Nut Graf

Headline for Questions 2/3: Black, Brown households more likely to be led by single mother

Nut Graf: Black, American Indian/Alaskan Native, Hawaiian/Pacific Islander and Hispanic households are more likely to be led by a single mother than white, Asian or non-Hispanic households, according to data released by the Census Bureau for August.
