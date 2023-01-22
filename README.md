# (Go Bike Data Set)
## by (Tae Singhanart)


## Dataset

I selected Ford GoBike System Data which includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. Originally, there were 183,412 entries with 16 features in this dataset. I retreived the dataset from [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv)


## Summary of Findings

> Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.

The main feature I'm interested in this data set is user type, customer and subscriber. I want to see some different or commonality (if any) relationship with other features such as the duration of the ride, gender, and age. 

The finding is showing that t the age profile of customer and subscriber group is quite simliar. For the gender by user type, there are more male member in both group. Noticably, the number of male subscriber is far way more than the other group around 3-25 folds. The customer group seem to have longer duration ride than subscriber. In Gender wise, both subscriber and customer group, male gender take a more ride. For both group most ride are take around 1 - 40 minutes. It's also show that the member after 60 year olds who taking the trip from 1-40 minutes are mostly customer than the subscriber. Lastly,  the exploration also showing that in each top three place, the majority group of visitor is different between subscriber and customer. For example, Market St at 10 St, the subscriber with the below 20 and mids 20 are the most group riding to this place while the customer group is the age over 30. In marketing perspective, this information help the company gain a huge advantage when it come to lauching the promotion on site or select target group for some specific promotion.


## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.

For the presentation, I will focus on just user type. I will start by introducing the the user_type variable showing the number of users by type, Next, showing its  and age profile (violin plot) and gender(bar plot).

Afterwards, I will describe the characteristic of the ride duration by user type (bivariable) and ride duration, user_type and age (multivariable). Lastly I will present the difference in number of ride of the top three destination by user type and age (multivariable).