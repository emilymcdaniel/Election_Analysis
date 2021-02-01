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

### Further application of this script
To improve this script, I recommend:
- Adding a voter fraud checkpoint. With the data provided, we can easily build a checkpoint to ensure the same Ballot ID was not used multiple times.
- Adding a separate section to the data that outlines all potential candidates and counties. It is possible that other counties were eligible and there was no turnout, so they went unnoticed; that county should be listed with other counties as 0% turnout. Similarly, there may be a candidate out there who wonders why their results weren't shown as a result of their name and vote count (of 0) being absent from our list.
- Identifying candidate support by county.

---
## References
Please find source code and raw results here:

![Terminal view of Up to 7 in Notepad](https://raw.githubusercontent.com/emilymcdaniel/Election_Analysis/main/Terminal%20view%20of%20Up%20to%207%20in%20Notepad.PNG)

Please find the file containing the script here: [Deliverable 1](https://github.com/emilymcdaniel/Election_Analysis/blob/main/PyPoll_Challenge.py)

Please find .txt file containing the Election Summary Results here: (https://github.com/emilymcdaniel/Election_Analysis/blob/main/Analysis/election_analysis.txt)

