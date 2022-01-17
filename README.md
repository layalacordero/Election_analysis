# Election Analysis with Python

## Overview of Election Audit
&nbsp; A Colorado Board of Elections employee has asked you to create a python script that will help
analyize the results of a local election. You need to figure who won the election as well as 
which county has the greatest turnout. <br>
<br>
In order to do this we need to accomplish the following with the python script.
* Calculate Total number of votes cast
* Create a complete list of candidates who received votes
* Get the total number of votes each candidate received
* Calculate percentage of votes each candidate won
* Find the winner of the election based on popular vote
* Get the voter turnout for each county
* Calculate the percentage of votes from each county out of the total count
* Calculate the county with the highest turnout
## Resources
* Data Source: election_results.csv
* Software: Python 3.7.6, Visual Studio Code 1.63.2
## Election-Audit Results 
* The amount of votes casted in this congressional election was 369,711
* In the three counties that voted, there was 38,855 (10.5%) votes in Jefferson county, 306,055 (82.8%)
votes in Denver county, and 24,801 (6.7%) votes in Arapahoe county
* After reviewing the results, Denver county recieved the most votes among the three counties
* In the election the candidate Charles Casper Stockham recieved 85,213 (23.0%) votes, Diana DeGette recieved
272,892 (73.8%) votes, and Raymon Anthony Doane recieved 11,606 (3.1%) votes
* The candidate Diana DeGette won the election with 272,892 votes which made up 73.8% of the total votes

The image below shows the results of the election in a formatt the board suggested<br>
![results_summary](https://github.com/layalacordero/Election_analysis/blob/main/Resources/election_results_summary.jpg)

## Election-Audit Summary
&nbsp;In this dataset we analysed the election based on ballot ID, county, and the candidate with a script that
calculated the total votes, the votes by county, the votes by candidate, and the winning candidate. If the
election commission wanted to, there is room for modification.<br>
&nbsp; In order to detect if a vote was inputted twice or more the commission can add  lines of code that checks if
a ballot ID appears more than once in the dataset. You can also substitute code variables to count election at the 
state level instead of the county level.
