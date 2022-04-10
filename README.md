# Amazon_Vine_Analysis

### Overview of the analysis: 
**I picked one of the 50 datasets offered to mee and used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next I used PySpark to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, I wrote a summary of the analysis to submit to the SellBy stakeholders.**

### Results:

  - There was 94 vine reviews and 40,471 non vine reviews.





    ![Screenshot](/total_vine.PNG)
    
    
    
    
    
    ![Screenshot](/total_notVine.PNG)
    
    
    
    
    

  - There were 48 five star vine reviews and 15,663 non vine five star reviews.



    ![Screenshot](/fiveStar_vine.PNG)
    
    
    
      ![Screenshot](/fiveStar_notVine.PNG)
   
    
  - The percentage of vines that were 5 stars is 51.03 %.The percentage of 5 star non vine reviews are 38.70%
  
  
  
    ![Screenshot](/fiveStar_vine_percent.PNG)
    
  


    
    ![Screenshot](/fiveStar_notVine_percent.PNG)
    
  
### Summary: I do not find that there is a positiver bias in this database since the percentages of non vine review that are 5 stars is only 39%.This does not show any positive correlation with the vine reviews that are five stars as well since that is only 50% of five star reviews. The analysis I would add would be to do a check comparing the 5 star reviews from both with the total of reviews. I would also graph to see if there is a scatter plot trend negatively. 
