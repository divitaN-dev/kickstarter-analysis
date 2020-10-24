
## Overview of Project

The goal of project is to comb through an Excel database of thousands of crowdfunding projects to draw insights for a persona 'Louise' who needs help with starting her own crowdfunding project for a theater play.


### Purpose

The purpose of the project is to identify insights and trends from an Excel dataset using advanced Excel formulas and translate those into informative visualisations.


## Analysis and Challenges

The focus of the analysis was to generate two key insights most relevant for Lousie to kick off her crowdfunding project for her theater play -

  ### Analysis of Outcomes Based on Launch Date
  
    * Assess the success, failure, and cancelation numbers of all theater projects based on month of the crowdfunding campaign launch.

  ### Analysis of Outcomes Based on Goals
  
    * Assess in detail, the subcategory - plays in theater to calculate the success, failure, and cancelation percentage based on the fundraising goal in dollar amount ranges upto $50000 with intervals of $5000.

  ### Challenges and Difficulties Encountered
  
    * Assuring proper data formatting of a large dataset required great attention to detail and several revisions. For instance, conversion of linux timestamps to readable date formats and checking all columns to ensure correct data format so excel formulas are evaluated correctly.
      
    * Pivot table analysis took sevral tries in order to produce actionable insights, for example, plotting the number of outcomes based on months vs years or other data ranges. Plotting against month produced the most valuable insights.
      

## Results

  ### Conclusions on the analysis of Outcomes based on Launch Date:

    May is the best time to launch the campaign.
    
      * The most number of successful campaigns were launched in May, and closely followed by June and then July.

    December is not a good time to launch the campaign.
    
      * About half of the theater related campaigns launched in December failed to meet their fundraising goal. The failure rate was notably in high in October as well.
      
      
![Outcomes based on Launch Date](https://github.com/divitaN-dev/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png)

      

  ### Conclusions on the analysis of Outcomes based on Goals:

    A fundraising goal of under $5000 has the highest sucess rate for theater plays.
    
      * Campaigns with a goal of less than $1000 and within the range $1000 - $4999 met their goals over 70% of the times.
      
      * Although campaigns with fundraising goals in the range of $35000 - $44999 had a 2/3rd chance of meeting their goals, the number of campaigns in that range were only 9.

    A fundraising goal of $5000 - $24999 has the second highest rate of success.
    
      * Campaigns with goals in the range of $5000 - $14999 succeeded more than 50% of the times, and also accounted for the hightest number of total projects.
      
      * Campaigns with goals in the range of $15000 - $24999 succeeded close to 50% of the time, however, they acoounted for significantly fewer projects.
      
      
![Outcomes based on Goals](https://github.com/divitaN-dev/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)

      

 ### Limitations of this dataset:
    * Although the dataset contains information about thousands of project, the categorgy most relevant to Louise - theater plays within US accounted for a fraction of the total number of projects.

## Recommendation for additional tables or graphs:
  
  Some more useful insights could be genreated by evaluating:
  
    * A table of successful and failed Kickstarter campaign within U.S.
    
    * A stacked column of graph of outcomes of tehater plays for all regions in the dataset.


