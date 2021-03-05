# Election_Analysis


## Overview of Election Audit:

### Tom's Manager, Seth, in Colorado Board of Elections requested a help in completing an election audit of a recent local congressional election.
The following tasks are to be included in the completed election audit.


1. Calculate the total number of votes cast. 
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received. 
4. Calculate the percentage of votes each candidate won. 
5. Determine the winner of the election based on popular vote. 


### Also there are a few more Seth would like to review. And he asked if could confirm the voter turnout for each county that voted in this congressional district.



1. Calculate the voter turnout for each county.
2. Calculate the percentage of votes each county contributed to the election.
3. Determine which county had the largest turnout.




## Election-Audit Results:

### [Total Votes: 369,711](https://github.com/Ahmed-nidhal/Election_Analysis/blob/main/Resources/Total%20Votes.PNG)


### [County Results:](https://github.com/Ahmed-nidhal/Election_Analysis/blob/main/Resources/county%20Results.PNG)

Jefferson: 10.5% (38,855)

Denver: 82.8% (306,055)

Arapahoe: 6.7% (24,801)

### [Largest County Turnout: Denver](https://github.com/Ahmed-nidhal/Election_Analysis/blob/main/Resources/county%20with%20largest%20number%20of%20votes.PNG)

### [Candidate Results:](https://github.com/Ahmed-nidhal/Election_Analysis/blob/main/Resources/candidate%20results.PNG)

Charles Casper Stockham: 23.0% (85,213)

Diana DeGette: 73.8% (272,892)

Raymon Anthony Doane: 3.1% (11,606)


### [Election Winner:](https://github.com/Ahmed-nidhal/Election_Analysis/blob/main/Resources/candidate%20won%20the%20election.PNG)

Diana DeGette

Vote Count: 272,892

Percentage: 73.8%



## Election-Audit Summary:

In this project the script we run will be so helpfull to use in any Election audit, 
the script basically can be modified by changing the data base resource file as we in this step bellow:

(file_to_load = os.path.join("Resources","election_results.csv")

In addition this script could be refactore to do more tasks like getting the percentage of votes each county and determine which county had the largest turnout.
