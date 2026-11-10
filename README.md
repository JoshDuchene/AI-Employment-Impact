# AI-Employment-Impact
Examining the relationship between exposure to AI and changes in employment, by industry, in the US. This analysis is being conducted using BLS data. 

The general question I'll be testing is this: Have industries that are highly exposed to AI seen greater changes in total employment over the past few years compared to industries that are less exposed?


These are the data sources I plan to use:

https://www.bls.gov/emp/publications/ai-exposure-categories.htm:

gives the AI-exposure levels of the ~830 job categories included.

The exposure ratings are Low, Moderate, High, and Very High. They cite 5 articles that informed this ranking. It seems like they did a pretty thorough job trying to come up with these ratings, but, it's obviously a bit speculative and subjective. My hope is that, since my plan is to just look at historical job numbers, who is more likely than the BLS to have gathered decent data/knowledge on how/where AI is currently being deployed.

This data set also includes projected employment numbers in 2035, but I don't plan on using these. 


https://www.bls.gov/oes/tables.htm:

  This page has links to a file for each year, giving employment numbers, median wages, etc by job title... it has 830 job titles, and each of those has an industry code, (e.g 12-3456), where each digit provides a more detailed breakdown, meaning I will be able to group/aggregate the data to a more useful level, while still having access to the lower level data.

https://www.bls.gov/oes/2025/may/oes_stru.htm

Gives the breakdown of the occupation codes, at the high level, and all subsequent lower levels. Here's the first few rows to give an idea:
	
11-0000 Management Occupations

11-1000 Top Executives

11-1010 Chief Executives

11-1011 Chief Executives

11-1020 General and Operations Managers

11-1021 General and Operations Managers

11-1030 Legislators

11-1031 Legislators

11-2000 Advertising, Marketing, Promotions, Public Relations, and Sales Managers

<br>
https://www.bls.gov/soc/

this page just gives a more thorough explanation of the classification system.
