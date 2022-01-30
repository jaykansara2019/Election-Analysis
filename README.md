# **Election-Analysis**

## **Purpose**
This analysis aimed to determine the election results of Colorado counties, Arapahoe, Denver and Jefferson.



## **Election-Audit Results**

- In this particular congressional election, total of 369,711 votes were cast. The total votes were counted using simple membership and logical operators as well as repetition statements to iterate through all the rows containing vote count in the CSV file. The following code was used to count the total votes.

![Total vote count code](https://github.com/jaykansara2019/Election-Analysis/blob/2591e117c4c83aa5550040bdd309668a0bf8cd01/total_vote_count.png)

- Jefferson County received 38,855, which constitutes 10.5%. Arapahoe county received 24,801 votes, comprising only 6.7% of total votes. The winning county was Denver with 306,055 that accounts to majority of the votes casted in this election, 82,8% to be precise. The if formula was used to count the votes per county.

![Votes by counties](https://github.com/jaykansara2019/Election-Analysis/blob/2591e117c4c83aa5550040bdd309668a0bf8cd01/votes_by_counties.png)

- There were three candidates in this election. The candidate Charles Casper Stockham received 85,213 votes, accounting 23.0% of votes. Raymon Anthony Doane received only 11,606, only constituting 3.1% of the total votes. The winning candidate is Diana DeGette, with 272,892 votes that make up 73.8% of the total votes. The code in the terminal looks like the image below:

![The outcome in the terminal](https://github.com/jaykansara2019/Election-Analysis/blob/2591e117c4c83aa5550040bdd309668a0bf8cd01/terminal_outcome.png)

## **Election-Audit Summary and extrapolation of the script**

The scrip can be extrapolated for other future elections given that we do the following modifications:
- All we have to do is change the source and outcome files linked to this code. 
- We also need to make sure that the column header and data type remain the same. For example, Row 1 must have the ballot ID followed by county name in row 2 and Candidate name in row 3.
