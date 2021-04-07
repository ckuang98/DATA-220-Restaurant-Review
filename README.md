# DATA-220-Restaurant-Review

Project Description

For our project, we would like to analyze cities that were ranked with the best places to eat and pull the restaurants’ data of different cities from Yelp.  We will then apply the concepts of database design and modeling to restaurants and their customers’ reviews.  We will use MySQL as our database.  Through applying the concepts of database design, we would like to showcase why some cities are ranked above others and provide the granular data analysts might want.

The Database Initial Study

Analyze the Project situation

The main purpose of the Restaurant Review Project is analysis of why some restaurants in certain areas are top rank or bottom rank in Yelp. Based on the Project  situation, the database is stored and maintained in one local machine. 

Define problems and constraints

The dataset pulled from Yelp Open-dataset has some empty columns and multiple columns are less related to restaurant analysis, Data team need to work on the data cleaning and create a suitable, usable dataset for analysis.

Define objectives

We would like to pull the data from cities, in order to showcase why they might be at the top or bottom of the list in rankings and provide the granular data an analyst might want.

Define scope and boundaries

In reality, The Restaurant Review Project  is not able to cover all the restaurants in the whole world. Thus, scope of the database environment is only focused on the restaurants in Yelp Open-dataset.The boundaries of this Project  are mainly limited at cost, so the database is running in local designer machines. The Project might think about cloud servers later. In that case, Amazon AWS is considered because AWS has most servers in the world and a built-in server to handle everything, such as EC2, S3, RDS. In addition, AWS Macie can greatly handle Personal Identifiable Information issues. Either way, our database will be able to scale upwards if needed due to our python script, which allows us to clean and import data seamlessly.

Database Design

Create the conceptual Design

Data Analysis and Requirements
1.	Information
The information that Project  collected is from Yelp Open dataset. The information includes restaurant information, restaurant reviews, restaurant users and etc.. All of this information is the input of the database and the required information. We made certain that “all of the information needed is there, and all that is there is needed.”
2.	Outputs
Information that is relevant to restaurant reviews.
3.	Interfacing with the systems design
a.	The key point is database stability, which is solved by physical design
b.	We build the dataframe based on entities, attributes, relationships, connectivities, cardinalities, and constraints.

Summary and Conclusion

A restaurant review on Yelp's website gives only star ratings (one to five stars), the text of the review and the other attributes tells a more complete story. A reviewer may have enjoyed the food but been frustrated by the service, or they may have been impressed by the décor but put off by the long wait. Our database seeks to address this limitation and provide a centralized source of information to answer analysts questions. In the beginning, we were curious about why certain cities were ranked higher as best places to eat and with this database we would be able to answer this question much more seamlessly.

Future Work

Using data from Yelp, students at Berkeley used natural language processing to detect what the most important subtopics in reviews are. They were able to discover that customers seemed to care the most about service; and ratings for food quality and service tend to be positively correlated. We hope that our database model can be used to derive actionable insights from Yelp’s data and restaurants can leverage the findings in order to provide better services to their customers.

