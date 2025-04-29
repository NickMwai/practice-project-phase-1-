Finding safe aircrafts for consideration to invest in a new aviation business venture 
Business Problem
As part of its strategy to diversify operations, the company is expanding into the aviation industry with plans to purchase and operate aircraft for both commercial and private purposes. However, the organization currently lacks domain knowledge about the risks associated with different aircraft types. To support the new aviation division, this project analyzes National Transportation Safety Board (NTSB) Aviation Accident data to identify aircraft models with the lowest risk profiles in terms of operational safety and performance.
Data Understanding
Data Source
The dataset was sourced from the National Transportation Safety Board via Kaggle and contains historical aviation safety records of incidents and accidents involving various aircraft types, starting from 1962.
Data Preparation
The dataset was  cleaned to remove:
•	Inconsistencies
•	Incomplete entries ;Dropped columns that had missing and unkown values. 
 This cleaning process enhanced the overall quality and relevance of the dataset for assessing aircraft risk.
Objectives
This project aims to:
•	Determine aircraft makes and models with the lowest operational risk 
•	Deliver clear, data-driven recommendations to support the aviation division in selecting aircraft for initial investment
•	Reduce potential liabilities and support a safer, more informed entry into the aviation sector
Key Variables Used in the Analysis
	Examine the relation between the number of engines in an aircraft and occurence of accidents or incidents.
	Make and Model: Specifies the manufacturer and model of the aircraft.
	Total Fatal Injuries: The number of fatalities per accident.
   Aircraft category and count of accident
   Aircraft damage per count of accident
   Top 10 accident prone makes and models 

Relevance to Analysis
The selected variables provides valuable insights into accident trends, fatality rates, and aircraft damage levels. These insights are relevant to assessing the likelihood and fatality of aviation incidents, as well as factors that influence aircraft safety.
For a detailed breakdown of the analysis, please refer to the full notebook: student.ipynb

Key Findings & Results
I created an interactive Tableau dashboard to present the results of the analysis in a clear and accessible way https://public.tableau.com/views/aviationdatatableau/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link.

•	Aircraft with one or two engines accounted for the highest number of accidents, while aircraft equipped with eight engines showed significantly fewer accidents, suggesting that a higher number of engines may contribute to greater safety.
•	The majority of aircraft makes and models experienced substantial or complete damage during incidents, indicating a higher level of risk associated with acquiring them. Only a few aircraft types recorded minor or no damage, suggesting a lower risk profile.
• Cessna 172 aircraft recorded the highest number of accidents (476), the Cirrus Design Corp SR22 had fewer total accidents (78) .
•	Aircrafts with minimal accidents such as the Rans S6S, Hawk Arrow II, and Kitfox Super Sport suggest that factors like design, usage, or operational procedures may contribute to their safety.
. Prioritize Aircraft with Higher Engine Counts and Electric Engines for Improved Safety and Reliability
•	Focusing on aircraft with more engines has shown to significantly reduce the risk of accidents, indicating a clear correlation between the number of engines and improved safety. It is recommended that the company prioritize acquiring aircraft with higher engine counts.
•	Transitioning to electric engines for new fleet acquisitions will improve safety while reducing long-term operational costs. This shift would not only boost reliability but also position the company as a forward-thinking player in the evolving aviation industry.
Make & Model Combinations
•	It is advised that the company avoid acquiring aircraft like the Quicksilver, which has been associated with a higher number of incidents, or any aircraft linked to fatal accidents. Instead, the company should prioritize aircraft models with fewer or no accidents. Aircraft such as the Cessna T210L and Beech B23 exhibit greater durability and therefore should be considered safer options.

Below are some of graphs and charts derived
![alt text](image.png)
![alt text](image-1.png)
![alt text](image-2.png)
![alt text](image-3.png)
![alt text](image-4.png)