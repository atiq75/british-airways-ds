# British Airways Data Science Project

## TASK1 - WEB SCRAPING TO GAIN COMPANY INSIGHTS

### BACKGROUND INFORMATION
British Airways (BA) is the flag carrier airline of the United Kingdom (UK). Every day, thousands of BA flights arrive to and depart from the UK, carrying customers across the world. Whether it’s for holidays, work or any other reason, the end-to-end process of scheduling, planning, boarding, fuelling, transporting, landing, and continuously running flights on time, efficiently and with top-class customer service is a huge task with many highly important responsibilities.

Customers who book a flight with BA will experience many interaction points with the BA brand. Understanding a customer's feelings, needs, and feedback is crucial for any business, including BA. This first task is focused on scraping and collecting customer feedback reviewing data from a third-party source and analysing this data to present any insights that may be uncovered.

#### Scrape data from the web
The data was collected from [https://www.airlinequality.com/airline-reviews/british-airways]. Python and BeautifulSoup were used to collect the reviews.

#### Analyzing the data
The data was quite messy as it contained pure text. Once the data was clean, topic modelling, sentiment analysis, and creating word clouds were implemented to gain a deeper understanding of the reviews.

## TASK2 - PREDICT CUSTOMER BUYING BEHAVIOUR

### BACKGROUND INFORMATION
Customers are more empowered than ever because they have access to a wealth of information at their fingertips. This is one of the reasons the buying cycle is very different to what it used to be. Being reactive in this situation is not ideal; airlines must be proactive in order to acquire customers before they embark on their holiday. This is possible with the use of data and predictive models. 

#### Explore and prepare the dataset (customer_booking.csv)
The data was explored and feature engineering was performed before implementing a machine learning model.

#### Train a machine learning model
Random Forest Classifier was used for this task. 

#### Evaluate the model and present findings
The model had an 85% accuracy score. Other model evaluations were performed including visualizations. 
The most important features that dictate the customer bookings were visualized as well. 

