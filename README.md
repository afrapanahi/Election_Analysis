# Election_Analysis
## Overview of Election Audit: 
In this project we are using python to analyze the results of an election audit. The script lists the number of votes and percentage for each candidate, each county along with their number of votes, the winner of the election and the county with the largest turnout.  
##Election-Audit Results: 
See the figure below
![Outcome of election](/analysis/terminal.png?raw=true "Outcome of election")
Based on the analysis, here are the results for the following questions:
-How many votes were cast in this congressional election?

Total of 369,711 votes were cast in this election.

- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

Jefferson: 10.5% (38,855)
Denver: 82.8% (306,055)
Arapahoe: 6.7% (24,801)

-Which county had the largest number of votes?

Denver has the largest turnout with 306,055 (82.8% of total votes)

-Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)

-Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

The winner of this election is Diana DeGette with 272,892 votes out of total 369,711 (73.8%)

##Election-Audit Summary: 
This script assumes that the second column of the input csv file contains the county name, and the third column is used to list the candidate’s name. These number are hard coded and to generalize this script, one needs to ensure that the input file meets these criteria. Therefore, it can be used to audit election results from any state as long as the input file is formatted according to these conditions. 

This script goes through each row and counts number of unique appearances of the inputs in columns 2 and 3. By simply changing the input file format or the column number(s) we need to count in the code and the output to the desired property and format, this script can be generalized for many uses such as counting different products of a company.
