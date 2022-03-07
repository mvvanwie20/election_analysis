# election_analysis

## Overview of Election Audit
The purpose of this challeneg was to help an election department find the results of the main candidate winner and the county with the highest number of votes. 

## Election Audit Results
- There were a total of 369,711 congressional votes
- The counties votes and percent of total votes are as follows: Jefferson: 10.5% (38,855), Denver: 82.8% (306,055), Arapahoe: 6.7% (24,801)
- Denver had the highest number of votes with 82.8% of the total votes.
- The candidates receive the following percent of voted and total votes: Charles Casper Stockham: 23.0% (85,213), Diana DeGette: 73.8% (272,892), Raymon Anthony Doane: 3.1% (11,606)
- Diana DeGette won the elecetion with 73.8% of the vote and 272,892 votes.

## Election Audit Summary

This script can be used to analyze any election results that are in the similar format of a csv file. The codes works in two parts to analyze bothe the county turnout per county and defines the largets coutny by votes, and analyzes the votes per candidate and defines the winning candidate. Results are given in the total number of votes and percent of total votes. The final results are available both in the command line and in a separate txt file. In order to modify the code for any election two modifications must be completed. in row 45 and 48 where it states (45) candidate_name = row[2] and (48) county_name= row[1] the number must be replaced witht he fitting column.For row 45 this column number must align with the column that contains the candidate name and in row 48 the number must be replaced with the column number for counties. With these two adjustments the code can analyze any election result.
