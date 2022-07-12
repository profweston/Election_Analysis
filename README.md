# Election_Analysis

## Overview

An employee of the Colorado Board of Elections has requested an election audit of a recent congressional election. This request specifically addresses Jefferson, Denver, and Arapahoe counties. The analysis was completed utilizing Python 3.9.12 to verify results that were previously obtained in Excel. A summary of results and implications for future applications are discussed.

## Election-Audit Results 

Ballots were counted to tally the total number of votes across the three counties and determine the winner via popular vote. In addition, the number of votes were tabulated by counties and by candidate. The results along with images of the code relevant to each task is presented below.

  -	A total of 369,711 votes were cast in this congressional precinct.
  
  
      ![Total votes](/Resources/Total_Votes.png)

  
  -	Results by County
  
| County    | Total Number of Votes | Percentage of Total Votes | 
|-----------|:---------------------:|:-------------------------:|
| Arapahoe  |         24,801        |            6.7%           |
| Denver    |        306,055        |           82.8%           |
| Jefferson |         38,855        |           10.5%           |


     
   ![County Results](/Resources/County_Results.png)
      
  
  - Denver County had the largest number of votes.
  
     ![Largest_County](https://user-images.githubusercontent.com/108107856/178604725-0f6417f1-5c74-4e0a-b93f-7d5ee00d01d3.png)
  
  
  - Results by Candidate

| Candidate           | Total Number of Votes | Percentage of Total Votes |
|---------------------|:---------------------:|:-------------------------:|
| Charles C. Stockham |         85,213        |           23.0%           |
| Diana DeGette       |        272,892        |           73.8%           |
| Raymon A. Doane     |         11,606        |            3.1%           |

  ![Candidate Results](/Resources/Candidate_Results.png)

  - The winner of the election was Diana DeGette.

## Election-Audit Summary

Publishing ballot data results  varies extensively across a state and even more at the national level. As is evident in this analysis, auditing ballots is a process that can be automated with the use of Python code. Data can be analyzed, and reports published in an easy-to-understand standard format. In this report, the data were aggregated by county and by candidate, but other examples of aggregation include, but are not limited to, reporting by ballot type, by various precincts, or even by city. Python code is scalable to larger projects and is easily modified to apply to any election variables that might be warrant scrutiny.



