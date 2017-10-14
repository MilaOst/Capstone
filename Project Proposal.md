# Problem

What is influencing product ratings of unlocked mobile phones sold on Amazon.com?
	
## Client

Amazon would like to understand the performance of its core brands, models that bring 90% of revenue as measured by product ratings and reviews.
It needs to identify what are the most problematic brands, products and what is influencing poor product ratings. 
It is interested to find out whether the problems are product/service-related or both as described by product reviews and what areas could be improved.
Based on this information it can decide what actions should be taken to fix the issues and to serve customers better with an aim of increasing sales of the highest revenue products.

	
## Business questions

* What are the core brands, models that bring 90% of revenue to Amazon?
* What is the distribution of prices among most popular brands, models?
* What is the distribution of ratings among most popular brands, models?
* What are the core products with the best/worst reviews?
* What are customers talking about in their reviews - product features, service, experience, etc.?
* How are the categories customers talking about in their reviews, related to the ratings?
* What role do price, brand, product features, and service play in explaining product rating?
* What are the main dissatisfiers of customer experience?
* What are the main delighters of customer experience? 
	
## Approach 

### Data wrangling 

* Clean "Brand Name", "Product Name" columns to derive brand, product, and features
* Transform and summarize data
 

### Exploratory data analysis

* Discover correlations existant in the data
* Test hypotheses related to business questions
* Visualizations

### Text analytics

* Discover what key themes exist in customer reviews 

### Multiple regression

* Identify the relationships between themes and product ratings 
* Measure relative importance of themes, brand names, product features, and price to predict product ratings
	
## Data

n=400K customer reviews of unlocked [mobile phones sold on Amazon.com](https://www.kaggle.com/PromptCloudHQ/amazon-reviews-unlocked-mobile-phones/data)

## Deliverables

* Code
* Slide deck
* Blog