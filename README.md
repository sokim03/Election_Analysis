# Election_Analysis

## Overview of Election Audit
The Colorado Board of Elections has requested an election audit with the following requirements:
1. Total number of votes cast
2. A complete list of candidates who received votes
3. Total number of votes each candidate received
4. Percentage of votes each candidate won
5. The winner of the election based on popular vote

## Resources
- Data Source: election_results.csv 
- Software: Python 3.7 & Visual Studio Code 1.63

## Election-Audit Results
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The candidates were:
   - Charles Casper Stockham
   - Diana DeGette
   - Raymon Anthony Doane
   
- The number of votes and percentage of total votes for each county is shown below:


   ![County](https://user-images.githubusercontent.com/96352427/149861077-8f94045f-b813-44e7-b835-f3f634a6364b.PNG)

- Denver county had the largest number of votes.

- The number of votes and percentages of total votes for each candidate is shown below:

   ![Candidates](https://user-images.githubusercontent.com/96352427/149861097-454a3cd0-a139-4aaf-937c-3228f6bcc3b1.PNG)

- The winner of the election is Diana DeGette with the number of votes and total percentage shown below:

   ![Winner](https://user-images.githubusercontent.com/96352427/149861114-e1a70c33-b562-4ec5-abe9-ab79fd171d41.PNG)
   
## Election Summary
The provided script can be used for other elections that may also need to be audited.
To be used on a more federal level, one way to modify the existing script to cover larger areas can be to replace county votes with state votes. 
Another modification to the script could include different types of votes, such as in person votes and absentee ballot votes. 
These could then be further analyzed to calculate how much of each type of vote is turned in as long as we have the necessary data to show this.


