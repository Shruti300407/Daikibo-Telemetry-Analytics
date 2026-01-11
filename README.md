Daikibo Telemetry Data Analysis | Deloitte Job Simulation
📌 Project Overview
This project is part of a Deloitte Australia Data Analytics simulation focused on processing industrial telemetry data. The goal was to unify and analyze data from 4 global factories to identify equipment downtime and operational bottlenecks.

🏭 Business Context
Our client, Daikibo, collected telemetry data for the month of May 2021 across four locations:
Daikibo Factory Meiyo (Tokyo, Japan)
Daikibo Factory Seiko (Osaka, Japan)
Daikibo Berlin (Berlin, Germany)
Daikibo Shenzhen (Shenzhen, China)
Each location operates 9 types of machines, each sending status messages every 10 minutes.

🛠️ The Technical Task
The objective was to answer two critical business questions:
In which location did machines break the most?
Which specific machine types failed most often in that location?

Data Processing Steps:
Data Ingestion: Imported a complex JSON dataset containing one month of global telemetry logs.
Calculated Measures: Created a calculated field Unhealthy. Since each message represents a 10-minute interval, a value of 10 was assigned to every "unhealthy" status to represent potential downtime in minutes.
Interactive Dashboarding: Developed a Tableau dashboard with a filter action—selecting a factory in the "Down Time per Factory" chart dynamically updates the "Down Time per Device Type" chart.

📊 Key Insights
Highest Downtime: The analysis revealed which factory had the highest aggregate downtime.
Critical Failure Points: Identified the specific machine types (e.g., LaserWelder) that require immediate maintenance attention to improve overall production uptime.

💻 Tools Used
Tableau Desktop (Data Visualization & Dashboarding)
JSON Data Handling (Data Unification)
<img width="643" height="549" alt="image" src="https://github.com/user-attachments/assets/00c7b7d0-5769-4371-aa81-3127a16406da" />
