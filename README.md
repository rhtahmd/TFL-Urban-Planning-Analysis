![Dashboard](https://github.com/rhtahmd/TFL-Urban-Planning-Analysis/assets/134383166/ab358feb-5711-4549-884d-dba1c86f3ec2)
![EDA](https://github.com/rhtahmd/TFL-Urban-Planning-Analysis/assets/134383166/64aec4bd-27cb-41e8-b576-de7ad81cc9d7)


# TFL-Urban-Planning-Analysis

# Introduction

In this project, the goal is to analyze transportation data from Transport for London (TFL) to gain insights into urban planning. The dataset, sourced from (https://www.kaggle.com/datasets/astronasko/transport-for-london-journey-information), consists of: 

"a 5% sample of all Oyster card journeys performed in a week during November 2009 on bus, Tube, DLR, TfL Rail and London Overground. On journey by Tube or rail, an Oyster card user must touch in at the start, and touch out at the end for journey validation. On buses and trams, Oyster card users are only required to touch in so to validate their journey.", 

including information about start stations, end stations, journey duration, and travel card types.

# Questions

What are the busiest stations in the TFL network?

How does the journey duration vary across different subsystems?

Are there any specific travel card types that are predominantly used?

How does the number of journeys vary across different days of the week?

# Dataset Description
The dataset obtained from (https://www.kaggle.com/datasets/astronasko/transport-for-london-journey-information) contains information about TFL journeys. It includes the following attributes:

StartStn: The start station of the journey.

EndStation: The end station of the journey.

JourneyDuration: The duration of the journey in minutes.

TravelCardType: The type of travel card used for the journey.

# Tools and Packages

To conduct the analysis, the following tools and packages were utilized:

Python: The primary programming language for data manipulation and analysis.

Pandas and Numpy: For data manipulation and analysis.

SQLite: For querying the dataset using SQL.

Power BI: For advanced data visualization and analysis.

# Methodology
Data Cleaning and Preparation: The dataset was cleaned and prepared using Pandas to ensure data consistency and remove any unnecessary information.

SQL Querying: SQL queries were executed using SQLite to retrieve relevant information from the dataset. Queries were designed to analyze the busiest stations, journey durations, travel card types, and journey counts across different days of the week.

Data Visualization: Power BI was employed for advanced visualizations and interactive dashboards.

# Results and Discussion
The analysis revealed the following key findings:

Busiest Stations: The top 50 busiest stations were identified, with Oxford Circus, Victoria, and London Bridge being the most frequently used stations.

Journey Duration by Subsystem: The average journey duration was calculated for different subsystems, such as DLR/LRC, NR/DLR, LUL/NR/DLR, etc. The results indicated variations in journey duration across different subsystems.

Travel Card Types: The distribution of travel card types was analyzed, revealing the most commonly used types among commuters.

Journeys by Day of the Week: The analysis showcased the number of journeys on each day of the week, highlighting any patterns or trends.

# Conclusion

In conclusion, this TFL Urban Planning Analysis Project has provided valuable insights into the TFL transportation system. By analyzing data on the busiest stations, journey durations, travel card types, and journey counts, we have gained a deeper understanding of the dynamics and challenges within the network. These findings can be instrumental in informing urban planning strategies and optimizing transportation infrastructure to enhance the overall commuting experience.

The identification of the busiest stations, such as Oxford Circus, Victoria, and London Bridge, highlights the need for targeted measures to address congestion and improve passenger flow during peak hours. By implementing strategies to distribute the passenger load to nearby stations and promoting alternative modes of transportation for short distances, we can alleviate congestion and enhance the efficiency of the network.

The analysis of journey durations across different subsystems provides insights into the average travel times experienced by passengers. This information can guide decision-making processes regarding infrastructure improvements, schedule optimizations, and route planning to reduce travel times and enhance the overall efficiency of the transportation system.

Furthermore, the examination of travel card types and their distribution offers valuable insights into the preferences and usage patterns of passengers. Understanding the popularity of different fare products, such as PAYG, LUL Travelcard-7 Day, and LUL Travelcard-1 Month, enables policymakers to design fare structures and ticketing systems that are aligned with passenger needs and encourage the use of public transportation.

Lastly, the analysis of journey counts across different days of the week provides a comprehensive understanding of travel patterns and demand variations. This information can assist in resource allocation, service planning, and scheduling adjustments to meet the varying needs of passengers throughout the week.

Incorporating the findings from this analysis into urban planning strategies can lead to more efficient transportation systems, reduced congestion, improved passenger experiences, and sustainable urban development. By leveraging data-driven insights, policymakers and transportation authorities can make informed decisions that prioritize the needs of commuters and contribute to the creation of livable and vibrant cities
