# Election_Analysis

## Over view of Election Audit

### Purpose
The goal of the project is supporting Tom to collect and report the total number of votes cast, the total number of votes for each candidate, the percentage of votes for each candidate, and the winner of the election based on the popular votes. Furthermore provide the report the county votes, total vote number for each county, the percentage of votes for each county.

##Election Audit Results

Total Votes: 368,711

County Votes:
- Jefferson: 10.5% (38,855)
- Denver: 82.8%(306,055)
- Arapahoe: 6.7% (24,801)

Largest County Turnout
- Denver

Candidate Result:
- Charles Casper Stockham: 23.0% (85,213)
- Diana DeGette: 73.8% (272,892)
- Raymon Anthony Doane: 3.1% (11,606)

Winner Result:
- Winner: Diana DeGette
- Winning Vote Count: 272,892
- Winning Percentage: 73.8%

##Election Audit Summary
- The edition from the script of loading csv file could help us link and open any csv election data.\
file_to_load = os.path.join("Resources", "A_election_results.csv")
- The edition from the script of counting total votes number could help us count any elections' total votes number\
for row in reader:
   total _votes = total_votes +1
   other_election_candidate_name = row[2]
   if other_election_candidate_name not in candidate_options"
 candidate_votes[other_election_candidate_name] +=1
