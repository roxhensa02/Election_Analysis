# Election_Analysis

## Overview of Election Audit: 

*Explain the purpose of this election audit analysis.*

In this analysis we will analyze the results of the election audit to the election commission. We will determine of the votes breakdown by county and candidate. We will see the vote count for each candidate and county as well their vote percantage comapred to the total votes. In this analysis we will show the county with the highest turnout. At the end we will determine the winning candidate by showing the total votes tis candidate received and its percantage overall the total votes.


## Election-Audit Results: 

*Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.*

- How many votes were cast in this congressional election?

In this congressional election were casted 369,711 votes

![Chart](https://github.com/roxhensa02/Election_Analysis/blob/main/analysis/Total%20votes.PNG)



- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

The breakdown of votes for Jefferson, Denver and Arapahoe are as below where it is presented as percentages respectively to the total votes. And the number in paranthesis is the total of votes that each country had.

![Chart](https://github.com/roxhensa02/Election_Analysis/blob/main/analysis/breakdown.PNG)



- Which county had the largest number of votes?

The country with the largest number of votes is Denver with 306,055 votes.

- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

  * The candidate Charles Casper Stockham had a total of 85,213 which is 23.0% of total votes.
  * The candidate Diana DeGette had a total of 272,892 votes which is 73.8% of total votes.
  * The candidate Raymon Anthony Doann had a total of 11,606 votes which is 3.1% of total votes, and this candidate had the lower number of votes.

![Chart](https://github.com/roxhensa02/Election_Analysis/blob/main/analysis/candidate%20breakdown.PNG)



- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

Dianna DeGette is the winner of the election with 272,892 votes, which is 73.8% of total votes. She won strongly compared with to the other candidates as she had a high number of votes.

![Chart](https://github.com/roxhensa02/Election_Analysis/blob/main/analysis/winning%20candidate.PNG)




## Election-Audit Summary: 

*In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.*

As we can re-use the script for further election analysis, one of the modification that we can use is for the winner candidate. A county may have have more than a candidate, so we can determine their votes and percantage compared to the county votes and not the total votes. Therefore the modification will be to replace the total_votes with the county_votes. 

If we have more tha 3 counties or more than 3 candidates, if we want to show the top 5 counties, candidates, we can add a for loop for the if-statement to present the top 5 candidates, or just additional if-statements.

Also this script can be used to analyse the results withhin the states, therefore we can change the county_votes with the votes from each state (state_votes).
