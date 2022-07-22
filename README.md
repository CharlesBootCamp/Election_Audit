# Election Audit
Challenge 3 is to use Python to help Sam and Ethan properly submit the election audit results
# Printing CSV Data and Saving to Text File

## Overview of Project
Using the CSV file, I was able to determine the voting ID, county, and voted candidate for almost 400k people. My first task was to make it so the program could first find the CSV file and be able to look into its contents for use in the future code. I had to create a load path variable, and then use that variable to complete the loading variable, which used the data from the given location. Then, the total number of votes is set to 0, new lists/directories are made, and all this data is then used to create the number of votes as well as their percentages. The data gets printed out both into the terminal of the python program, and it gets writtne to the analysis folder as a .txt file.
### Purpose
The purpose of this project is to take the total number of election votes and break them down by county and who the people voted for, it is being done to make sure that a quick and accurate means of collecting and using all this data can be done. This method is good becuase it allows for large datasets to be able to be broken down quickly and efficiently, while also storing the data in multiple locations.
### Challenges and Difficulties Encountered
One challenge that I experienced was trying to get the code to accept the CSV file as the input file path, I fixed this by creating a second variable that relied on using the data that was also included in the Election Audit folder. Another issue I had was calculating the percentage of votes per county, then I realized that I had misnamed a variable and needed to remove specifiers for the directory.
## Results
As shown with the following image, as well as the text file equivalent of it:
![image](https://github.com/CharlesBootCamp/Election_Audit/blob/main/Terminal.png)
(https://github.com/CharlesBootCamp/Election_Audit/blob/main/Election%20Audit/analysis/election_analysis.txt)

- There were 369,711 total votes in the election
- The represented counties were Jefferson, Denver, and Arapahoe
- The county results follow: Jefferson contained 10.5% (38,855) of the votes, Denver contained 82.8% (306,055) of the votes, and Arapahoe contained 6.7% (24,801) of the votes.
- The county with the largest turnout was Denver
- The candidates were Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane
- The candidate results follow: Charles received 23.0% (85,213) of the votes, Diana received 73.8% (272,892) of the votes, and Raymon received 3.1% (11,606) of the votes.
- Diana DeGette was the winner of the election with 73.8% of the votes, totaling at 272,892 votes.
## Summary
The script can also be used for other election data managing as well, whether by changing the/ adding new variables with how to group the votes together and who they represent, as well as the votes having multiple people that a vote can choose, making it so that there are many ways to use this type of script to calculate any election.
