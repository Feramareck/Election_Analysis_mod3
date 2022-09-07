# Election_Analysis

## Project Overwiew
Produce a Python code that serves as an electoral audit of tabulated results for a US Congressional police station in Colorado. Our main task was to report the total number of votes cast, the total number of votes for each candidate, the percentage of votes for each candidate, and the winner of the election based on popular vote.
After the votes are counted, it is necessary to generate a vote count report to certify this race to the US Congress.

## Resources
 - Data Source: election_results.csv
 - Software: Python 3.9.1, VS code 1.71

 ## Summary
 

 Election Results
 
-------------------------
Total Votes: 369,711

-------------------------
Candidades:    
Charles Casper Stockham  
Diana DeGette  
Raymon Anthony Doane  

-------------------------
Candidates Results:  
Charles Casper Stockham: 23.0% (85,213)  
Diana DeGette: 73.8% (272,892)  
Raymon Anthony Doane: 3.1% (11,606)  

-------------------------
Winner of the Election  
Winner: Diana DeGette  
Winning Vote Count: 272,892  
Winning Percentage: 73.8%  

-------------------------

## Challenge Overview
The data of the votes were made available in an Excel file, which makes them very susceptible to a problem during their manipulation and also very easy to make a mistake if the results were manipulated in the file itself. Thus, this project was coded using Python as it is a highly used language in data analysis.



## Challenge Summary
1. To create this project, it was initially necessary to add dependencies to open Excel(.csv).  
2. Initialized the variables, list and dictionary.
3. Opened the file and work within a for to increase the overall votes and that of a given candidate.
4. Created a .txt named election_analysis.txt file to store the calculated result and determine the winner of the election.  
All the commands used are in the PyPoll.py code as well as the respective comments about each coded step.
