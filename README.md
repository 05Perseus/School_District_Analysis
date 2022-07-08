# School_District_Analysis

## *The Goal and Methodology*
### In this analysis our goal was to take grades that were likely a result of academic dishonesty. We needed to replace the grades for 9th graders at Thomas High School with null (NaN) values while leaving the rest of the grades intact. Once we did that we needed to recreate our earlier analysis and note differences.

The things we wanted to know in particular are:
1. How is the district summary affected?
2. How is the school summary affected?
3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
4. How does replacing the ninth-grade scores affect the following:
    * Math and reading scores by grade
    * Scores by school spending
    * Scores by school size
    * Scores by school type
---
## *How is the District Summary Affected?*
#### When comparing the results of the District Summary we did not notice any change. There weren't a large enough number of 9th grade students at THS relative to the total to move the needle far. Below are the screenshots of our 2 District Summaries:

1. First summary with the THS 9th grades ***INCLUDED***

![Original District Summary](https://github.com/05Perseus/School_District_Analysis/blob/main/Resources/Original_District_Summary.png)

2. Second summary with the THS 9th grades ***EXCLUDED***

![Original District Summary](https://github.com/05Perseus/School_District_Analysis/blob/main/Resources/Updated_District_Summary.png)


---
## *How is the School Summary Affected?*
#### To further analyze the election results we broke the results up by the county and evaluated based on the same questions as before:

1. What percent of the votes came from each county?
2. How many votes came from each county?
3. What county had the best voter turnout?

#### Our answers are best presented for each county individually:

1. Jefferson County
    * Percentage of the vote - ***10.5%***
    * Number of votes - ***38,855***

2. Arapahoe
    * Percentage of the vote - ***6.7%***
    * Number of votes - ***24,801***

**<ins>And our winner was:</ins>**

3. **Denver**
    * Percentage of the vote - ***82.8%***
    * Number of votes - ***306,055***

*The <ins>Terminal</ins> Results of our Analysis*

![Original code for 2017](https://github.com/05Perseus/Election_Analysis/blob/main/Recources/Terminal%20Screenshot.png)

*The <ins>**Text File**</ins> Results of our Analysis*

![Text file screenshot](https://github.com/05Perseus/Election_Analysis/blob/main/Recources/TXT%20File%20Screenshot.png)



---
## *Conclusion*
In conclusion this election had a total of 369,711 votes. Diana DeGette won the popular vote and Denver County had the best turnout by far!

This script attached in the analysis is a great tool for election analysis and can be used for years. To replicate this analysis in the future there are 2 options:

1. Simply replace the data in the CSV file and run the code! This method requires no changes to the code and will give you the exact same results.
2. The second option is to change the path in the code to point to your new files! This method allows you to keep election result files in the folder to look back on.
 
