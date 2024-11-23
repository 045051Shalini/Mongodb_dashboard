# Shipwreck data analysis
It contains dashboard  as well as objectives and insigts for analysis of shipwrecks data which is done using Mongodb atlas and Mongodb compass. <br/> 

## Attributes Description for shipwreck data
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

## Objectives<br/>  
1. Analyze shipwreck patterns by depth, visibility, and condition to uncover key insights.<br/>  
2. Map global shipwreck distribution and identify regions with high concentrations.<br/>  
3. Assess data quality, depth characteristics, and dominant shipwreck types to understand trends and influences.<br/>  

## Analysis <br/>

### 1. Median Depth for Each Condition of Shipwrecks<br/>

**Question:** Which condition of shipwrecks is generally found at the deepest depths?<br/>

![Median depth for each condition of shipwrecks nbsp; (1)](https://github.com/user-attachments/assets/ea570f3a-9fcd-4230-a07d-fd3ce600064d) <br/>

**Insight:** Shipwrecks labeled as "Submerged dangerous" are found at significantly greater depths compared to other conditions.<br/> 
**Managerial Implication:** Allocate advanced diving and detection resources to deeper waters to ensure effective exploration and hazard mitigation.<br/>

### 2. Dangerous Shorelines with Most Shipwrecks<br/>

**Question:** Which shoreline has the highest density of dangerous shipwrecks?<br/>

![Dangerous shorelines with most shipwrecks](https://github.com/user-attachments/assets/083797f3-0002-4871-9295-ab6e6c2ac69d) <br/>
**Insight:** The shoreline near Virginia Beach and Boulevard is the most dangerous, hosting a high density of submerged shipwrecks.<br/>
**Managerial Implication:** Prioritize implementing safety measures and warning systems in high-density areas like Virginia Beach to reduce maritime accidents.<br/>

### 3. Geographical Spread of Shipwrecks with Their Condition<br/>

**Question:** Where are most "Submerged dangerous" shipwrecks located globally?<br/>

![nbsp;Geographical Spread of Shipwrecks with their condition](https://github.com/user-attachments/assets/0f80abdd-de4c-4eeb-b802-7bc425a9f818) <br/>
**Insight:** The North Atlantic Ocean has the largest cluster of submerged dangerous shipwrecks.<br/>
**Managerial Implication:** Enhance monitoring and navigation support in the North Atlantic to safeguard maritime operations in this high-risk zone.<br/>

### 4. Distribution of Shipwrecks by Their Condition<br/>

**Question:** What proportion of shipwrecks are visible compared to those submerged?<br/>

![Distribution of Shipwrecks by their condition in which they were found](https://github.com/user-attachments/assets/271f7808-f2de-44cf-af32-316b002a6735) <br/>
**Insight:** Only 23% of shipwrecks are visible, while the majority are submerged, with a large proportion being dangerous.<br/>
**Managerial Implication:** Focus on improving underwater detection technologies to address the risks posed by submerged shipwrecks.<br/>

### 5. Depth Analysis for Different Types of Shipwrecks<br/>
**Question:** At what depth are most submerged dangerous shipwrecks found?<br/>

![Depth analysis for different types of shipwrecks](https://github.com/user-attachments/assets/c9731f20-ad63-4894-a114-6cb1eaacd552) <br/>
**Insight:** Submerged dangerous shipwrecks are most commonly located at a depth of 139 ft.<br/>
**Managerial Implication:** Develop specialized equipment and protocols for exploration and hazard management at depths of around 139 ft.<br/>

### 6. Sound Analysis for Coordinates<br/>
**Question:** What is the primary reason for depth data being unavailable for certain shipwrecks?<br/> 

![Sound analysis for coordinates](https://github.com/user-attachments/assets/e5e49261-42b4-4b52-9f9d-af4450105602) <br/>
**Insight:** Poor sound quality is the leading reason why depth data is unavailable for many coordinates.<br/>
**Managerial Implication:** Invest in high-fidelity sonar systems to improve the accuracy and availability of depth data for shipwreck coordinates.<br/>

### 7. Top Depth Category for condition of shipwreck (Feature Type) and Water Level<br/>
**Question:** What is the most common combination of feature type and water level?<br/>

<img src="https://github.com/user-attachments/assets/9623d14a-603a-487a-afab-5da6ad07ccb0" width="50%" alt="image description" />

**Insight:** "Wrecks - Submerged, nondangerous" with the status "always under water/submerged" is the most common combination.<br/>
**Managerial Implication:** Allocate resources to monitor and document non-dangerous submerged wrecks, as they may still serve historical or ecological purposes.<br/>


## Dashboard 
[View Dashboard](https://charts.mongodb.com/charts-project-0-vzguajj/public/dashboards/66ea86e8-ed00-4156-a01f-a1beac0f1948)

![Shipwrecks data analysis dashboard](https://github.com/user-attachments/assets/c4a08f84-0610-4327-a26f-4574cfa6c307) <br/>




