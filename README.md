# Election_Analysis

## Overview

An employee of the Colorado Board of Elections has requested an election audit of a recent congressional election. This request specifically addresses Jefferson, Denver, and Arapahoe counties. Results are aggregated by couty as well as by candidate. The analysis was completed utilizing Python 3.9.12 to verify results that were previously obtained in Excel. A summary of results and implications for future applications of the code used for analysis are discussed.

## Election-Audit Results 

Ballots were counted to tally the total number of votes across the three counties and determine the winner via popular vote. In addition, the number of votes were tabulated by counties and by candidate. The results along with images of the code relevant to each task is presented below.

  -	A total of 369,711 votes were cast in this congressional precinct.
  
    <img width="469" alt="Total_votes" src="https://user-images.githubusercontent.com/108107856/178786805-642d591d-fe57-4eaf-a2ee-624f10c1be0c.png" width="50%" height="50%">

  
  -	Results by County
  
| County    | Total Number of Votes | Percentage of Total Votes | 
|-----------|:---------------------:|:-------------------------:|
| Arapahoe  |         24,801        |            6.7%           |
| Denver    |        306,055        |           82.8%           |
| Jefferson |         38,855        |           10.5%           |


     
![County_Results](https://user-images.githubusercontent.com/108107856/178803016-70b17bb5-f490-4e94-958a-31942281dabc.png)
      
  
  - Denver County had the largest number of votes.
  
  
 ![Largest_County](https://user-images.githubusercontent.com/108107856/178804018-9a576270-235e-4837-a6a2-074b0aaf447d.png)


  
  
  - Results by Candidate

  | Candidate           | Total Number of Votes | Percentage of Total Votes |
  |---------------------|:---------------------:|:-------------------------:|
  | Charles C. Stockham |         85,213        |           23.0%           |
  | Diana DeGette       |        272,892        |           73.8%           |
  | Raymon A. Doane     |         11,606        |            3.1%           |


  ![Candidate_Results](/Resources/Candidate_Results.png)
       
    
  - The winner of the election was Diana DeGette.
  
   ![Winner](https://user-images.githubusercontent.com/108107856/178805004-8496ac85-2b58-4aec-a3aa-f1f1a3e6e5dc.png)


## Election-Audit Summary

Publishing ballot data results  varies extensively across a state and even more at the national level. As is evident in this analysis, auditing ballots is a process that can be automated with the use of Python code. Data can be analyzed, and reports published in an easy-to-understand standard format. In this report, the data were aggregated by county and by candidate, but other examples of aggregation include, but are not limited to, reporting by ballot type, by various precincts, or even by city. 

Python code is easily modified to apply to any election variables that might warrant scrutiny and is scalable to larger projects. For example, suppose the Colorado Board of Election is interested in examining results of larger cities within a certain county. The code used for tracking votes by county shown above could easily be modified to examine cities with larger populations. The same "for" loop design is applied to a **city_name** in **county_votes** for various cities tallied in the Elections Results data file. Also, by simply changing the link to the data file and a quick adjustment to variable names, this code can examine any sort of election results such as general or primary elections. In regard to scalability, the county design could be scaled up to examine votes by state in a federal election. 

This analysis offers only a small glimpse into what Python can do. With Python's easy to learn syntax and powerful data analysis tools, its implementation into the voting environment would prove invaluable. 



