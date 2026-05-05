## MIST4610-Group-Project-2

## Team Name:
21482 Group 6

## Team Members:
1. Andrew Mckenna [@andrew-mckenna] (https://github.com/andrew-mckenna)
2. Benjamin Perez-Acosta [@bp59023] (https://github.com/bp59023)
3. Mason Herndon [@Mason-port] (https://github.com/Mason-port) 
4. Maria Jacob [@mej65217] (https://github.com/mej65217)
5. Parker Gallagher [@Parker1094] (https://github.com/Parker1094)

## Project Overview

This project analyzes motor vehicle collision data to identify patterns in accidents and better understand the key factors that contribute to them. By using data visualization and analysis techniques, the goal is to uncover trends that can help improve road safety and highlight areas of concern.

## Dataset Description

The dataset used for this project was obtained from Data.gov. It contains real-world crash data reported by law enforcement agencies, including detailed information about when and where accidents occur, as well as the outcomes of those incidents.

The dataset includes thousands of records and multiple columns with different types of data, making it well-suited for meaningful analysis. Each record represents an individual collision and includes variables such as crash date and time, location (borough or zip code), number of injuries and fatalities, contributing factors, and vehicle types involved.

This dataset is valuable because it provides insight into real-world accident patterns. It can be used to identify common causes of crashes, evaluate trends over time or location, and support improvements in road safety. Additionally, the data is useful for policymakers and city planners looking to reduce injuries and fatalities and make more informed decisions.

## Question 1:

Which contributing factors are associated with the highest number of injuries?

Importance:

Finding out what contributing facotrs lead to the largest number of injuries is crucial to improving road safety for all commuters in NYC. With over 2 million vehichles registered in the State, finding the root causes of the most dangerous collisions allow state officials, law enforcement, and policy makers to zero in on what is most detrimental to road safety.


<img width="1131" height="678" alt="Screenshot 2026-05-02 at 3 12 01 PM" src="https://github.com/user-attachments/assets/be66ed5a-6b8c-44ed-9288-9919506da9a8" />



Consulting the graph, we can see that the main contributing factors to collisions involving injuries are Driver Inattention, Failure to Yield Right of Way, and Following to closely. What's most notable is that more injuries are caused by Driver inattention than failure to yield and following to closely combined. The top three contributing factors to injuries suggest that behavioral and human attention based causes far outweigh mechanical/environmental causes. 

## Question 2:

How do injury-causing collisions vary by time of day and location for the top contributing factors identified in Question 1?



Importance:

Understanding how injury-causing collisions vary by time of day and location for the most dangerous contributing factors is essential to improving road safety across NYC. While identifying the leading causes of injuries highlights what behaviors are most harmful, examining when and where these incidents occur allows state officials, law enforcement, and city planners to take more targeted action. With millions of vehicles on the road each day, recognizing patterns in high-risk times and locations can help allocate resources more effectively, implement preventative measures, and ultimately reduce the number of injuries caused by motor vehicle collisions.

<img width="1137" height="588" alt="Screenshot 2026-05-04 at 10 52 34 PM" src="https://github.com/user-attachments/assets/af546621-563e-486c-baae-e05bef975a38" />
<img width="1137" height="588" alt="Screenshot 2026-05-04 at 10 53 04 PM" src="https://github.com/user-attachments/assets/cffdc5a6-f4c8-462a-a7ff-d26e4c741aaa" />
<img width="1137" height="588" alt="Screenshot 2026-05-04 at 10 53 28 PM" src="https://github.com/user-attachments/assets/029a276f-56ad-4525-98e5-d08577c61ad7" />


Through examining the graphs based upon the top three contributing factors of crashes sorted by time and location, we found that all three factors shared a consistent pattern of higher crash rates in hours of rush hours traffic which is pretty typical. However on the location side of things we found that Statin Island was the most consistent in injury rates, followed by manhatten and the Bronx. Knowing the locations impact on injury trends, it is clear that the most effective bouroughs to target for legislation changes on controbuting factors would be that of Brooklyn and Queens as they are the most prone to injuries overall.



## Modifications to base data

In the process of creating the first visualization, we found that a large portion of contributing factors were labeled as "uncategorized." This data was unecessary and it's large amount of values skewed the scaling of the causes that had a labed contributing factor. We decided to remove rows that were uncategorized aswell as any null values.

As for the creation of the second visualization, the only main filtering we completed was removing null values such as car crashes that didn't have a borough assigned to them. This removed any potential excess data that didn't contribute to answering our second question.








