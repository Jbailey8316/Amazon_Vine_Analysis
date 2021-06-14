# Amazon_Vine_Analysis
## Purpose
This project focuses on Big Data.  We will utilize cloud services, notably AWS, to access and store data from Amazon customer reviews.  With these reviews, we will analyze if there is any bias within the supplied dataset.

## Resources
* AWS - Amazon Web Services
* RDS Amazon Relational Database Services
* PgAdmin 4 - PostgreSQL database
* Google Colab

## Results
### Fig 1 Compiling the dataset
![dataset](https://github.com/Jbailey8316/Amazon_Vine_Analysis/blob/main/images/AWS_videogame_dataset.PNG)

The first step of our project was to compile our dataset as shown in figure 1.  For this project, we selected Vine video game reviews from AWS.

### Fig 2 Total Number of Reviews
![total_reviews](https://github.com/Jbailey8316/Amazon_Vine_Analysis/blob/main/images/total_reviews.PNG)

Once our dataset was collected, we extract the total number of reviews. (Fig. 2)  We have a total of 40,565 reviews.

### Fig 3 Total 5 Star Reviews
![total_5_star](https://github.com/Jbailey8316/Amazon_Vine_Analysis/blob/main/images/total_5_star_reviews.PNG)

This was followed by filtering the dataset to determine the total number of 5 star reviews. (Fig. 3)  The dataset contains 15,711 5 star reviews. Accounting for about 39% of the total reviews.

### Fig. 4 Total Paid Reviews
![tot_paid](https://github.com/Jbailey8316/Amazon_Vine_Analysis/blob/main/images/total_paid_reviews.PNG)

We then decided to investigate the number of paid reviews vs unpaid reviews.
We have a total of 94 paid reviews within the dataset which equates to about 0.2% (Fig. 4)

### Fig. 5 Total Unpaid Reviews
![tot_unpaid](https://github.com/Jbailey8316/Amazon_Vine_Analysis/blob/main/images/total_unpaid_reviews.PNG)

Looking at the total of unpaid reviews we have 40,471.  This indicates that about 99.8% of the total reviews were not compensated to do so. (Fig. 5)

### Fig. 6 Paid 5 Star Reviews
![paid_5_star](https://github.com/Jbailey8316/Amazon_Vine_Analysis/blob/main/images/total_paid_5_star_reviews.PNG)

Researching deeper into the paid reviews, we were able to extract that of all the 5 star reviews, there were 48 reviews that received compensation. (Fig. 6)

### Fig 7 Percentage of Paid Reviews
![percent_paid](https://github.com/Jbailey8316/Amazon_Vine_Analysis/blob/main/images/percent_paid_reviews.PNG)

Fig. 7 indicates that we have a 51% of all compensated reviews were 5 stars.

### Fig. 8 Unpaid 5 Star Reviews
![unpaid_5_star](https://github.com/Jbailey8316/Amazon_Vine_Analysis/blob/main/images/total_unpaid_5_star_reviews.PNG)

Looking at the unpaid reviews, we see there were a total of 15,663 5 star reviews. (Fig. 8) 

### Fig. 9 Percentage of Unpaid Reviews 
![percent_unpaid](https://github.com/Jbailey8316/Amazon_Vine_Analysis/blob/main/images/percent_unpaid_reviews.PNG)

As shown in fig. 9, the percentage of unpaid 5 star reviews in total of the 5 star reviews is about 39%.

### Fig. 10 Percenatge of Paid 5 Star Reviews Overall
![overall_paid](https://github.com/Jbailey8316/Amazon_Vine_Analysis/blob/main/images/percent_paid_overall.PNG)

Comparing the quantity of paid 5 star reviews to the overall 5 star review count returns a percentage of about 31% as shown in Fig. 10.

### Fig. 11 Percenatge of Unpaid 5 Star Reviews Overall
![overall_unpaid](https://github.com/Jbailey8316/Amazon_Vine_Analysis/blob/main/images/percent_unpaid_overall.PNG)

Next we compared the total unpaid 5 star reviews to the total number of 5 star reviews.  Resulting in 99.7% of the 5 star reviews not being compensated for.

## Summary
Overall there seems to be a high percentage of 5 star reviews within this given dataset, indicating a high satisfaction within this category of items.  While we see a high number of these reviews (15,663) were not compensated, the number of reviews that were compensated provided an overall 51% of their reviews as 5 stars.  We can conclude given the high percentage of paid 5 star reviews that the program encourages customers to leave a high rating.  As an additional analysis for this dataset, I would be interested to compile similar data regarding 1 star reviews to compare the paid vs. unpaid unsatisfactory reviews.  This would give an overall look at how well spread the paid reviews affect the given reviews on both ends of the dataset.
