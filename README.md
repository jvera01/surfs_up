# surfs_up by Jesus Vera


# Overview
This project aims to analyze weather data for a stakeholder interested in investing in a surfing business located in Hawaii. The data has been collected by a Weather Observing System and stored in a flat database file(.db/.sqlite).To ensure the business is sustainable, year-round weather trends need to be analyzed.To understand Hawaii's weather, the stakeholder has expressed explicit interest in weather statistics for June and December throughout recent years.

# Results
To access the observation data and analyze it, I have utilized SQLAlchemy ORM, which allows me to query the data bypassing python objects as queries. The data is then transformed within a python environment and analyzed, resulting in the below summary statistics.

  -June Temperature Summary Statistics 
        # June Temps
        count	1700.000000
        mean	74.944118
        std	3.257417
        min	64.000000
        25%	73.000000
        50%	75.000000
        75%	77.000000
        max	85.000000

   -June Temps
        0	78.0
        1	76.0
        2	78.0
        3	76.0
        4	77.0


   -December Temperature Summary Statistics
        # December Temps
        count	1517.000000
        mean	71.041529
        std	3.745920
        min	56.000000
        25%	69.000000
        50%	71.000000
        75%	74.000000
        max	83.00000

   -December Temps
        0	76.0
        1	74.0
        2	74.0
        3	64.0
        4	64.0


Using the statistical overview of the data, we can see that:There is a higher max temperature for June than December. However, with only a difference of 2 degrees.
June also has a maximum average temperature of fewer than 3 degrees. We can see June also has a higher minimum temperature of 8 degrees.

# Summary Additonal Analysis
We learned that by analyzing the weather data spread, it is safe to say that while December is colder, it is still possible to run a business focused on outdoor activities in Hawaii, even in colder months
        
   -June Temperature Observations by group
    June spread	
    Temp Range Observation Count
        0	(50, 60]	0
        1	(60, 70]	171
        2	(70, 80]	1485
        3	(80, 90]	44
        4	(90, 100]	0

   -December Temperature Observations by group
        december spread
        Temp Range	Observation Count
        0	(50, 60]	9
        1	(60, 70]	621
        2	(70, 80]	883
        3	(80, 90]	4
        4	(90, 100]	0
