# surfs_up by Jesus Vera
![](surfs_up/Images/Surfing.png)

# Overview
This project analyzes weather data for a stakeholder interested in investing in a surfing business located in Hawaii. The data has been collected by a Weather Observing System and stored in a flat database file(.db/.sqlite). We analyzed the weather to ensure the company is sustainable with Hawaii's temperature. The stakeholder has expressed explicit interest in weather statistics for June and December throughout recent years.

# Resources
•	SQLite (smaller and faster version of SQL that lives on a computer or mobile device)
•	SQLAlchemy (query tool designed for SQLite and integration statistical analysis with dataFrame analysis)
•	Flask (web framework that enables python use to build web pages)
•	Jupyter Notebook and Pandas
•	A SQLite database containing weather information about Hawaii
•	VS Code to create the Flask application


# Results
To access the observation data and analyze it, I have utilized SQLAlchemy ORM, which allows me to query the data bypassing python objects as queries. The data is then transformed within a python environment and analyzed, resulting in the below summary statistics.
We can see that a standard deviation of 3.25 with a max of 85 and a minimum of 64 with 74. 
-June Temperature Summary Statistics 
        # June Temps
•	count 1700.000000
•	mean 74.944118
•	std	3.257417
•	min	64.000000
•	25%	73.000000
•	50%	75.000000
•	75%	77.000000
•	max	85.000000


We have analyzed December's temperature find that the mean is 71, the std is 3.74, the of 83 degrees with a min of 56 degrees. 
   -December Temperature Summary Statistics
    # December Temps
•	count 1517.000000
•	mean 71.041529
•	std	3.745920
•	min	56.000000
•	25%	69.000000
•	50%	71.000000
•	75%	74.000000
•	max	83.00000


Using the statistical overview of the data, we can see a higher max temperature for June than December. However, with only a difference of 2 degrees.
June also has a maximum average temperature of fewer than 3 degrees. We can see June also has a higher minimum temperature of 8 degrees.

# Summary Additional Analysis
We learned that by analyzing the weather data spread, it is safe to say that while December is colder, it is still possible to run a business focused on outdoor activities in Hawaii, even in colder months.
Based on our Data Analysis, Data Provided, we can state as a high-level summary of results that Standard deviation is 3.25 in June and 3.75 in December, making a 0.5 difference between both seasons.

In addition, current data provide attributes such precipitation and others, with two queries that our analysis pursue, performing weather data for June and December that helps results to decide how we would like to build the shop and what areas would make this location attractive to visitors to stop by and have a successful business.
        
 Below you can find June Temperature Observations Temp Range and count with 50,60 count of 0, 60,40 count of 171,  70,80 count of 1485, 80,90 count of 44 and 90,100 counts of 0.
    June spread	
    Temp Range Observation Count
•	0	(50, 60]	0
•	1	(60, 70]	171
•	2	(70, 80]	1485
•	3	(80, 90]	44
•	4	(90, 100] 0

Below you can find December Temperature Observations Temp Range and count with 50,60 count of 9, 60,40 count of 621,  70,80 count of 883, 80,90 count of 4, and 90,100 counts of 0.
        December spread
        Temp Range Observation Count
•	0	(50, 60]	9
•	1	(60, 70]	621
•	2	(70, 80]	883
•	3	(80, 90]	4
•	4	(90, 100]	0
