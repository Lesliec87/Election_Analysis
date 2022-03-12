# Election_Analysis


## Overview of Election Audit:

In this analysis we are assisting Tom, a Colorado Board of Elections employee, in an elections audit of the tabulated results for U.S. Congressional Precinct in Colorado. 

First, we are tasked to report the total amount of the votes cast, the votes for each candidate, the percentage of votes for each candidate and the winner based on popular vote. Second, the election commision requested to gather additional data such as the voter turnout for each county, the percentage of votes from each county out of the total count and the county with the highest turnout.

Tom's manager Seth has also requested a way to automate the audit using Python, if it is successful they will use the code we write to audit also Senatorial Districs and Local Elections. We are taking the election results from votes cast with one of three voting methods: mail-in-ballots, punch cards and direct recording electronic (DRE) counting machines. After the votes our counted our job is to generate a vote count report to certify the U.S congressional race. 


## Election-Audit Results:

### Election Results: 

![Election_Results](https://github.com/Lesliec87/Election_Analysis/blob/main/Resources_3/Election_Results.png)

## Election-Audit Highlights:

 - The total votes were 369,711.
  
 - In Jefferson there were 38,855 county votes which was 10.5% of the total county votes.
 - In Denver there were 306,055 county votes which was 82.8% of the total county votes.
 - In Arapahoe there were 24,801 county votes which was 6.7% of the total county votes.
   
 - The county with the largest number of votes was Denver.
   
 - For Charles Casper Stockham he had 85,213 number of votes which was 23.0% of the total candidate votes.
 - For Diana DeGette she had 272,892 number of votes which was 73.8% of the total candidate votes.
 - For Raymon Anthony Doane he had 11,606 number of votes which was 3.1% of the total candidate votes.
   
 - The winning candidate was Diana DeGette with a vote count of 272,892 and with a percentage of 73.8% for total votes.

 *Please review information above in [Election Results](#Election-Results)

## Election-Audit Summary: 

In this election audit we were able to provide the results broken down by total votes, number of votes per candidate, per county, the largets county turnout, the winning candidate, winning vote count and by the percentages.

There is significant use for this script in future elections since we are able to provide a detailed election audit only needing to make modifications to the script depending on the type of election, section of the script for the candidates with just minor modifications and update the files that will be used for the audit. 

**Here are examples of some of the modifications that can be done to the script:** 

1. We would need to modify what files we would be loading our information from and also the path where we would save our results since the information will be pulled from different files. In the script we will need to update in line "9" and "11' for the variables the "file_to_load" and "file_to_save". 

*Please review the image below where the modifications can be made. 

![Initial Modifications](https://github.com/Lesliec87/Election_Analysis/blob/main/Resources_3/python_code_1.png)

2. Another modification we will need to make is depending on what type of elections (Congressional Districts, Senatorial Districs or Local Elections) we will need to simply update the name "county" for the county list, dictionary that holds the county as the key and the votes cast for each county as the values, this will be in lines "21" and "22". 

3. Another modification that needs to be made are depending on the reading the "for loop" to go through each row we will need to update the script that gets the county name from each row in line "53".

*Please review image below where the modification can be made. 

![Initial Modifications](https://github.com/Lesliec87/Election_Analysis/blob/main/Resources_3/python_code_2.png)

