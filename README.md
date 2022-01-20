# Election Audit Analysis

## 1. Overview of Election Audit

Using election data to conclude election results. In details, includes:

* Total vote counts
* finding out the number of candidates ran for the election
* total vote counts for each candidate and their respective vote percentages
* counties that ran for election
* total vote counts for each county and their respective vote percentages
* Winning candidate, vote count and percentage
* Largest County Turnout


## 2. Election-Audit Results
* 369,711 votes were cast in this congressional election
* Jefferson has 38,855 votes, 10.5% of total vote counts. Denver has 306,055 votes and it counts 82.8% of the total votes. Arapahoe has 24,801 votes and it is 6.7% of the total votes. 
* Denvor had the largest number of votes.
* Candidate Charles Casper Stockham had won 85,213 votes, which is 23% of total vote counts. Diana DeGette had won 272,892 counts which is 73.8% of total vote counts. Raymon Anthony Doane had won 11,606 vote counts which are 3.1% of total votes counts. 
* Diana Degette won the election, with 73.8% of votes which is 272,892 vote counts.



## 3. Election-Audit Summary
This python script is compatible to do any election analysis, as long as there is data available in CSV file. There is no limit on the size of database. All the analysis reports will provide outcomes that are covered above in "Overview of Election Audit".

However, there are a couple of things that need to be tailored before running this script for other election data:
1. File path, make sure to enter the right file path for both output text report and to load the dataset. 
2. Check if "candidate name" is in the third column in the CSV file. If not, move it to the third column. (or adjust the index in script line 49)
3. Check if "county_name" is the second column in the CSV file. If not, move it to the second column. (or adjust the index in script line 52)
