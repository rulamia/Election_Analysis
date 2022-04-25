# Election_Analysis
## Overview of Election Audit
The purpose of the election audit analysis it to find the outcome of this election for an election commission.
---
## Election-Audit Results
> How many votes were cast in this congressional election?
- The total votes for this election was 369,711.
> Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
- Jefferson County recieved 38,855 votes with 10.5% of the votes. 
- Denver County recieved 306,055 votes with 82.8% of the votes. 
- Arapahoe County recieved 24,801 votes with 6.7% of the votes. 
> Which county had the largest number of votes?
Denver county had that largest number of votes at 82.8%.
> Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
- Charles Casper Stockham recieved 85,213 votes with 23.0% of the votes.
- Diana DeGette recieved 272,892 votes with 73.8% of the votes.
- Raymon Anthony Doane recieved 11,606 votes with 3.1% of the votes.
> Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
- Diana DeGette won with 272,892 votes with 73.8% of the votes.
![Image of vote analysis results](https://github.com/rulamia/Election_Analysis/blob/main/Resources/election_analysis_image.PNG)
---
## Election-Audit Summary
This script can be used for any election just by changing the csv flie in the resource folder. One way the code could be modified to help the user with this process is change the way the csv file is read in. The way we would do this is make the name of the csv file a user input variable instead of a static variable, that way mutiple election results can be stored in the resource folder at one time. We could also change the text file output to match the name of the csv file and add "_analysis" to the end to denote that it is the analysis file for that csv file. **Below is pictured what that code might look like:**
![image of example code](https://github.com/rulamia/Election_Analysis/blob/main/Resources/file_name_example.PNG)