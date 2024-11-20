# Mongodb_dashboard
It contains dashboard analysis for shipwrecks data done on Mongodb 

#Attributes Description
_id : A unique identifier for each record in the dataset. Typically assigned automatically in a database like MongoDB.
recrd : Possibly a placeholder for a record name or number. It's empty here, so its intended use is unclear.
vesslterms: May indicate terms or classifications related to the vessel involved in the wreck. 

feature_type: Describes the type of feature identified in the dataset. In this case, it refers to "Wrecks - Visible," meaning the shipwreck is visible or above water.

chart: Refers to the nautical chart or dataset the information is derived from. It may contain identifiers for region (US), chart type (DNC), and specific chart number 

latdec: The latitude of the shipwreck in decimal degrees.

londec: The longitude of the shipwreck in decimal degrees.

gp_quality: Likely refers to the quality of the geospatial data or positioning. It's empty here, suggesting no quality assessment has been recorded.

depth: The depth of the shipwreck in water, likely in meters or feet. Empty here, so the depth may not have been measured or recorded.

sounding_type: Refers to the method or type of sounding used to measure depth or locate the wreck. It's empty, indicating no method was recorded.

history: May contain historical details or events related to the shipwreck. 

quasou: Likely represents the "Quality of Sounding" to indicate how reliable or accurate the depth or location data is.

watlev: Stands for "Water Level," describing the water condition at the wreck location. In this case, "always dry" means the location is above water and remains dry.

coordinates: An array containing the longitude and latitude of the shipwreck, used for geospatial mapping. Matches londec and latdec.

![Shipwrecks data analysis dashboard](https://github.com/user-attachments/assets/c4a08f84-0610-4327-a26f-4574cfa6c307)


1. Median Depth for Each Condition of Shipwrecks
Objective: Determine the median depths for various types of shipwreck conditions to identify patterns.
Question: Which condition of shipwrecks is generally found at the deepest depths?
Insight: Shipwrecks labeled as "Submerged dangerous" are found at significantly greater depths compared to other conditions.

2. Dangerous Shorelines with Most Shipwrecks
Objective: Identify geographic regions with the highest concentration of shipwrecks.
Question: Which shoreline has the highest density of dangerous shipwrecks?
Insight: The shoreline near Virginia Beach and Boulevard is the most dangerous, hosting a high density of submerged shipwrecks.

3. Geographical Spread of Shipwrecks with Their Condition
Objective: Map the global distribution of shipwrecks by condition.
Question: Where are most "Submerged dangerous" shipwrecks located globally?
Insight: The North Atlantic Ocean has the largest cluster of submerged dangerous shipwrecks.

4. Distribution of Shipwrecks by Their Condition
Objective: Examine the percentage distribution of shipwrecks based on their visibility and condition.
Question: What proportion of shipwrecks are visible compared to those submerged?
Insight: Only 23% of shipwrecks are visible, while the majority are submerged, with a large proportion being dangerous.

5. Depth Analysis for Different Types of Shipwrecks
Objective: Analyze the depth distribution for each type of shipwreck.
Question: At what depth are most submerged dangerous shipwrecks found?
Insight: Submerged dangerous shipwrecks are most commonly located at a depth of 139 ft.

6. Sound Analysis for Coordinates
Objective: Evaluate the quality of sound data used for determining depths.
Question: What is the primary reason for depth data being unavailable for certain shipwrecks?
Insight: Poor sound quality is the leading reason why depth data is unavailable for many coordinates.

7. Top Depth Category for Feature Type and Water Level (Word Cloud)
Objective: Identify the dominant shipwreck type and water level characteristics.
Question: What is the most common combination of feature type and water level?
Insight: "Wrecks - Submerged, nondangerous" with the status "always under water/submerged" is the most common combination.

