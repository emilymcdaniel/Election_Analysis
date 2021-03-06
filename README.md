# Analyzing an Election Using Python
A review of the election results by County & Candidate
---
---
## Overview
This analysis provides a snapshot of the total turnout for this election, voter turnout by county, the votes received by each candidate, along with the election winner. 

In this election, 3 candidates ran in an election, and 3 counties particpated. 

---

## Election: Audit Results
A total of 369,711 votes were cast from Araphoe, Denver, and Jefferson couties. 

### Candidate Results
- The winner of the election is Diana DeGette, who receieved 73.8% of the vote (272,892 total votes!)
- Charles Casper Stockham received 85,213 votes (23.0%).
- Raymon Anthony Doane received 11,606 (3.1%).

### County Results
Denver had the largest turnout of the 3 participating counties, with 82.8% of votes cast. Jefferson county's participation accounts for 10.5% of the election, and Araphoe county accounts for the remaining 6.7%.
- Jefferson County: 10.5% (38,855)
- Denver County: 82.8% (306,055)
- Arapahoe County: 6.7% (24,801)

---
## Election: Audit Summary 
This analysis is effective because it identifies each county and each candidate, regardless of the turnout, number of candidates, or the number of participating counties. If the csv file is updated with a different election's data, provided that the columns remain in the same order this script can be run again without modification.

For example, an election with 25 candidates and voters from one county would have a similar print-out, though the list of candidates in our summary would be lengthy and the largest county turnout would be unsurprising.

With minor adjustments to labels, we could apply the same script to a national election - where we may count states instead of counties.

### Further application of this script
To improve this script, I recommend:
- Adding a voter fraud checkpoint. With the data provided, we can easily build a checkpoint to ensure the same Ballot ID was not used multiple times.
- Outlining candidate support by county.
- Including a separate section to the data that outlines all potential candidates and counties. It is possible that other counties were eligible and there was no turnout or a candidate who received no votes. Neither will show in this print-out.

---
## References
Please find source code and raw results here:

![View of Summarized Results](https://github.com/emilymcdaniel/Election_Analysis/blob/main/Resources/Election%20Summary%20Screenshot.PNG?raw=true)

Python Script Location (.py): (https://github.com/emilymcdaniel/Election_Analysis/blob/main/PyPoll_Challenge.py)

Election Summary Results (.txt): (https://github.com/emilymcdaniel/Election_Analysis/blob/main/Analysis/election_analysis.txt)

Original Data File (.csv): 
(https://github.com/emilymcdaniel/Election_Analysis/blob/main/Resources/election_results.csv)
