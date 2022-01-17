# Election_analysis

## Election Audit Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast. 
2. Calculate the total number of votes from each county.
3. Calculate the percentage of votes from each county.
4. Get a complete list of candidates who received votes.
5. Calculate the total number of votes each candidate received.
6. Calculate the percentage of votes each candidate won.
7. Determine the winner of the election based on popular vote.

## Resources
  - Data Source: election_results.csv
  - Software: Python 3.7.6, Visual Studio Code 1.63.2

## Election Audit Results
### The analysis of the election show that:
There were 369711 votes cast in the election.

### The county results were:
  - Jefferson County had 10.5% of the vote with 38,855 voters.
  - Denver County had 82.8% of the vote with 306,055 voters.
  - Arapahoe County had 6.7% of the vote with 24,801 voters.

Denver County had the largest turnout of voters.

### The candidates were:
   - Charles Casper Stockham
   - Diana DeGette
   - Raymon Anthony Doane
    
### The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
  - Diana DeGette received 73.8% of the vote and 272,892 votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes.
  
### The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 votes.

## Election Audit Summary

This Election_analysis code can be used in any election to determine the candidate votes and the location of the of the votes. For example, in a national election, the votes from all 50 states could be calculated by state using similar code to: 

county_list = [ ]

county_votes = { }

and changing the variable and output names to:

state_list = [ ]

state_votes = { }





