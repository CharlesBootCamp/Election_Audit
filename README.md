# Election Audit
Challenge 3 is to use Python to help Sam and Ethan properly submit the election audit results
# Printing CSV Data and Saving to Text File

## Overview of Project
Using the CSV file, I was able to determine the voting ID, county, and voted candidate for almost 400k people. My first task was to make it so the program could first find the CSV file and be able to look into its contents for use in the future code. I had to create a load path variable, and then use that variable to complete the loading variable, which used the data from the given location. Then, the total number of votes is set to 0, new lists/directories are made, and the data gets printed out both into the terminal of the python program, and it gets writtne to the analysis folder as a .txt file.
### Purpose
The purpose of this project is to take the yearly data of multiple stocks to evaluate which ones are worth investing money into. In order to properly find and display which ones are good to invest in, the return has to be positive. This project was done to make sure that I am able to look over the available data and am able use other data sets appopriately, finding and displyaing important data, and display how the data can be interpreted to make it easier for those I'm coding for.
## Analysis and Challenges

### Analysis of Printing to Command Line
 I started in the VBA by creating a tickerIndex variable and initializing it to 0, so that it always resets itself whenever the code gets rerun. I then created three arrays, a long called tickerVolumes, and two called tickerStartingPrices and tickerEndingPrices that are Singles, which can have decimals. I then used tickerVolumes(tickerIndex) = tickerVolumes(tickerIndex) + Cells(i, 8).Value to add any new volume to the total amount of volume. It then uses code to make sure that the data coming through is in a valid format and to see what row is currently being examined. The tickerIndex is then incremented and through the following functions: Cells(4 + i, 1).Value = tickers(i)
Cells(4 + i, 2).Value = tickerVolumes(i)
Cells(4 + i, 3).Value = tickerEndingPrices(i) / tickerStartingPrices(i) - 1
we are able to put the acquired values in the given cells on the All Stocks Analysis sheet.
![image](https://github.com/CharlesBootCamp/VBA_Challenge/blob/main/Resources/VBA_Challenge_2017.png)
Ultimately, I took all 12 stocks and used their pieces of data over the fiscal year of 2017 and found that all but one of the stocks, TERP, had gone up in value over the fiscal year.
### Analysis of Saving to Text File
 I started in the VBA by creating a tickerIndex variable and initializing it to 0, so that it always resets itself whenever the code gets rerun. I then created three arrays, a long called tickerVolumes, and two called tickerStartingPrices and tickerEndingPrices that are Singles, which can have decimals. I then used tickerVolumes(tickerIndex) = tickerVolumes(tickerIndex) + Cells(i, 8).Value to add any new volume to the total amount of volume. It then uses code to make sure that the data coming through is in a valid format and to see what row is currently being examined. The tickerIndex is then incremented and through the following functions: Cells(4 + i, 1).Value = tickers(i)
Cells(4 + i, 2).Value = tickerVolumes(i)
Cells(4 + i, 3).Value = tickerEndingPrices(i) / tickerStartingPrices(i) - 1
we are able to put the acquired values in the given cells on the All Stocks Analysis sheet.
![image](https://github.com/CharlesBootCamp/VBA_Challenge/blob/main/Resources/VBA_Challenge_2018.png)
Ultimately, I took all 12 stocks and used their pieces of data over the fiscal year of 2018 and found that all but two of the stocks, ENPH and RUN, have gone down in value over the fiscal year.


### Challenges and Difficulties Encountered
One challenge that I experienced was being able to properly the capture the message box that displayed the time that each calculation took and the year being examined, I worked around this by zooming into the message box before taking a screenshot. Another issue I had was I needed to add in an End if statement for the part that said I had to check if the current row is the last row with the selected ticker. A loop then goes through and initilaizes all values in the arrays to 0, to make sure that there is no messes in the data. 
## Results
- What are the advantages and disadvantages of refactoring code?
  Some advantages I learned from refactoring code is that it gives me multiple ways of being able to come across solving the same kind of problem. Another advantage is that the refactoring gives more detail into the nature of the returns and whether or not they are positive or negative. A disadvantage that also comes with this is that it can get confusing and tricky trying to figure out what method is best to complete.
- What are the advantages and disadvantages of the original and refactored code?
The advantage of the original code is that it is simple enough for everyone to understand and do no matter how fresh in language someone is, but an advantage the refactored version can get stuff done incredibly fast. One disadvantage of the original method is that it is ultimately slower than the refactored version, and the disadvantage of the refactored is that it takes more specialization and making sure all the little parts work together.
