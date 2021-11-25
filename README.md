# Python Poll Counter
## Overview
A Colorado Board of Elections Committee needs help in completing an audit of their recent election. They have asked to calculate the number of votes cast, and produce lists of the number of votes counted per candidate as well as percentage of vote received. They have also requested to get similar results with breakdowns based on county.

## Audit Results
    
    Election Results
    -------------------------
    Total Votes: 369,711
    -------------------------
    County Votes:
    Jefferson: 10.5% (38,855)
    Denver: 82.8% (306,055)
    Arapahoe: 6.7% (24,801)
    -------------------------
    Largest County Turnout: Denver
    -------------------------
    Charles Casper Stockham: 23.0% (85,213)
    Diana DeGette: 73.8% (272,892)
    Raymon Anthony Doane: 3.1% (11,606)
    -------------------------
    Winner: Diana DeGette
    Winning Vote Count: 272,892
    Winning Percentage: 73.8%
    -------------------------
[Audit Results above can be found here](/analysis/election_analysis.txt)

## Audit Summary
We can see that this code works well for this use case. We can further diversify the code to allow for any sort of elections. By making the code functional, we would be able to input multiple files of code, with a larger breadth of data included (more columns) so that we could have similar analysis for a larger amount of data.

Another way to advance the code would be to create and return graphs so that the board would be able see the results in a visual format.

Adding these ideas into the code should allow the script to be scalable to different types of elections as well as produce more diverse results.