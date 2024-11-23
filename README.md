# Mongodb_dashboard
It contains dashboard analysis for shipwrecks data done on Mongodb<br/> 

# Attributes Description
**_id** : A unique identifier for each record in the dataset. Typically assigned automatically in a database like MongoDB.<br/>
**recrd** : Possibly a placeholder for a record name or number. It's empty here, so its intended use is unclear.<br/>
**vesslterms**: May indicate terms or classifications related to the vessel involved in the wreck.<br/> 
**feature_type**: Describes the type of feature identified in the dataset. In this case, it refers to "Wrecks - Visible," meaning the shipwreck is visible or above water.<br/>
**chart**: Refers to the nautical chart or dataset the information is derived from. It may contain identifiers for region (US), chart type (DNC), and specific chart number<br/> 
**latdec**: The latitude of the shipwreck in decimal degrees.<br/>
**londec**: The longitude of the shipwreck in decimal degrees.<br/>
**gp_quality**: Likely refers to the quality of the geospatial data or positioning. It's empty here, suggesting no quality assessment has been recorded.<br/>
**depth**: The depth of the shipwreck in water, likely in meters or feet. Empty here, so the depth may not have been measured or recorded.<br/>
**sounding_type**: Refers to the method or type of sounding used to measure depth or locate the wreck. It's empty, indicating no method was recorded.<br/>
**history**: May contain historical details or events related to the shipwreck.<br/> 
**quasou**: Likely represents the "Quality of Sounding" to indicate how reliable or accurate the depth or location data is.<br/>
**watlev**: Stands for "Water Level," describing the water condition at the wreck location. In this case, "always dry" means the location is above water and remains dry.<br/>
**coordinates**: An array containing the longitude and latitude of the shipwreck, used for geospatial mapping. Matches londec and latdec.<br/>

# Objective and questions<br/>  

# 1. Median Depth for Each Condition of Shipwrecks<br/>
**Objective:** Determine the median depths for various types of shipwreck conditions to identify patterns.<br/>
**Question:** Which condition of shipwrecks is generally found at the deepest depths?<br/>
# 2. Dangerous Shorelines with Most Shipwrecks<br/>
**Objective**: Identify geographic regions with the highest concentration of shipwrecks.<br/>
**Question:** Which shoreline has the highest density of dangerous shipwrecks?<br/>
# 3. Geographical Spread of Shipwrecks with Their Condition<br/>
**Objective:** Map the global distribution of shipwrecks by condition.<br/>
**Question:** Where are most "Submerged dangerous" shipwrecks located globally?<br/>
# 4. Distribution of Shipwrecks by Their Condition<br/>
**Objective:** Examine the percentage distribution of shipwrecks based on their visibility and condition.<br/>
**Question:** What proportion of shipwrecks are visible compared to those submerged?<br/>
# 5. Depth Analysis for Different Types of Shipwrecks<br/>
**Objective:** Analyze the depth distribution for each type of shipwreck.<br/>
**Question:** At what depth are most submerged dangerous shipwrecks found?<br/>
# 6. Sound Analysis for Coordinates<br/>
**Objective:** Evaluate the quality of sound data used for determining depths.<br/>
**Question:** What is the primary reason for depth data being unavailable for certain shipwrecks?<br/>
# 7. Top Depth Category for Feature Type and Water Level<br/>
**Objective:** Identify the dominant shipwreck type and water level characteristics.<br/>
**Question:** What is the most common combination of feature type and water level?<br/>

# Dashboard

![Shipwrecks data analysis dashboard](https://github.com/user-attachments/assets/c4a08f84-0610-4327-a26f-4574cfa6c307)

# link to the dashboard : https://charts.mongodb.com/charts-project-0-vzguajj/dashboards/66ea86e8-ed00-4156-a01f-a1beac0f1948

# Insights<br/>

# 1 **Insight:** Median Depth for Each Condition of Shipwrecks<br/>
Shipwrecks labeled as "Submerged dangerous" are found at significantly greater depths compared to other<br/> conditions.
**Managerial Implication:** Allocate advanced diving and detection resources to deeper waters to ensure effective exploration and hazard mitigation.
# 2 **Insight:** Dangerous Shorelines with Most Shipwrecks<br/>
The shoreline near Virginia Beach and Boulevard is the most dangerous, hosting a high density of submerged<br/> shipwrecks.
**Managerial Implication:** Prioritize implementing safety measures and warning systems in high-density areas like Virginia Beach to reduce maritime accidents.
# 3 **Insight:** Geographical Spread of Shipwrecks with Their Condition<br/>
The North Atlantic Ocean has the largest cluster of submerged dangerous shipwrecks.<br/>
**Managerial Implication:** Enhance monitoring and navigation support in the North Atlantic to safeguard maritime operations in this high-risk zone.
# 4 **Insight:** Distribution of Shipwrecks by Their Condition<br/>
Only 23% of shipwrecks are visible, while the majority are submerged, with a large proportion being dangerous.<br/>
**Managerial Implication:** Focus on improving underwater detection technologies to address the risks posed by submerged shipwrecks.
# 5 **Insight:** Depth Analysis for Different Types of Shipwrecks<br/>
Submerged dangerous shipwrecks are most commonly located at a depth of 139 ft.<br/>
**Managerial Implication:** Develop specialized equipment and protocols for exploration and hazard management at depths of around 139 ft.
# 6 **Insight:** Sound Analysis for Coordinates<br/>
Poor sound quality is the leading reason why depth data is unavailable for many coordinates.<br/>
**Managerial Implication:** Invest in high-fidelity sonar systems to improve the accuracy and availability of depth data for shipwreck coordinates.
# 7 **Insight:** Top Depth Category for Feature Type and Water Level<br/>
"Wrecks - Submerged, nondangerous" with the status "always under water/submerged" is the most common combination.<br/>
**Managerial Implication:** Allocate resources to monitor and document non-dangerous submerged wrecks, as they may still serve historical or ecological purposes.
