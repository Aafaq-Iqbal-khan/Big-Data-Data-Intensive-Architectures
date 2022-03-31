# Big Data: Data Intensive Architectures

## An Analysis of TripAdvisor And Twitter Trend Using Open Source Big Data Technologies

(The repository for the Data Intensive Architectures project.)

## Abstract

Hospitality industry always remains an important contributor in the economy of many countries across the world. In general, there are huge number of people who go for travel or visits restaurants and share their experience and reviews about the hotels and restaurants on the websites and twitter. TripAdvisor is a leading user-generated content website to explore the reviews by previous travelers and their experiences with restaurants, hotels and tourist destinations and millions of people visit this website annually. This study is about to explore the customer’s dining experience in restaurants and hotels by their rating and reviews provided on the TripAdvisor website. As TripAdvisor generating huge amount of data so the objective of the project is to use the big data frameworks and distributed environment to analysis the data on a large scale. Big data paradigm Hadoop and Spark are used in order to fetch useful information and do visualization through different graphs to gain some valuable insights. This study finds the frequent words which were used by satisfied and unsatisfied users in their reviews while sharing their experiences. A logistic regression classifier is used to predict the rating of the review based on their review text. The implementation is done in spark distributed environment. Another aim of the project is to explore the trend related to the topic like travel, tourism, TripAdvisor within twitter community. This gives us a better insight into the collective viewpoint as a whole.
# Datasets:
 
 ![image](https://user-images.githubusercontent.com/102433874/161112401-d3799d16-71db-4256-96f5-24f07958e564.png)

![image](https://user-images.githubusercontent.com/102433874/161112418-7e2c1042-9898-46b0-88b4-dc5a13f5a8da.png)

![image](https://user-images.githubusercontent.com/102433874/161112433-2f4753ad-85ec-4f8f-8f48-27cc2a1fe51d.png)
 
# Results
 
![image](https://user-images.githubusercontent.com/102433874/161112468-f266e8e7-0f6a-4b4e-bc74-a1a81d8c2a1c.png)

![image](https://user-images.githubusercontent.com/102433874/161112487-40c356cd-4019-465f-b681-0a7dc5eb2430.png)

![image](https://user-images.githubusercontent.com/102433874/161112501-2c7ed329-2b39-4088-b739-8b55a45fa2e3.png)


# Conclusion
As with the digitalization of everything, the amount of data is increasing exponentially. It has become necessary to store and manage this huge data on distributed architecture rather on traditional relational databases. This approach is adopted by many organizations worldwide. This project studies the use of well-known Big Data open source technologies in restaurant and hotel industry. Hadoop provides an efficient framework for huge data analysis and it can be integrated with Apache Hive and Flume, which we used in this project for tweets analysis.
This project mainly focus on twitter and TripAdvisor website where each year millions of users give their reviews and rating about the hotels and restaurants. The three TripAdvisor datasets downloaded from internet and they transferred into virtual machine and loaded into a directory in HDFS. These files then further pulled in spark and perform different analysis.
Major observations from the analysis are: California city has the most satisfied customers with their restaurants. While the restaurant’s customer satisfaction is least in Washington. As per the textual analysis of the reviews, location of the restaurants and their staff behavior increase the customer satisfaction. Moreover, the issues of quality of the food and order services are the major reasons for customer’s dissatisfaction.
