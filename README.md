# DivvyBikes
Divvy Bikes- Chicago EDA

1. Overview:
This repository contains an exploratory data analysis (EDA) project conducted on Divvy bike-sharing data. The analysis aims to uncover patterns in bike usage, understand user behavior, and derive actionable insights for improving the bike-sharing service.

Divvy Bikes is a public bike-sharing system in Chicago. This project explores the data to understand bike usage trends, identify peak usage times, and assess the performance of different stations. The insights derived can help in optimizing operations, planning expansions, and improving customer satisfaction.

2. Dataset Description:
The dataset used contains the following fields:

Ride Details:
start_time: The starting time of the bike ride.
end_time: The ending time of the bike ride.
ride_duration: Calculated duration of the ride (in minutes).
Station Information:
start_station_name: Name of the station where the ride began.
end_station_name: Name of the station where the ride ended.
Categorical Data:
user_type: Subscriber or casual rider.
Optional Data:
Latitude and longitude were removed from the analysis.
Station names were retained for geographical analysis.


3. Analysis Goals:
Identify peak usage times by categorizing hours into:
Rush Hour: Morning and evening commute hours.
Night: Late night and early morning.
Other: Non-peak daytime hours.
Determine popular stations for starting and ending rides.
Analyze ride durations to understand user behavior.
Examine differences in usage patterns between casual riders and subscribers.

4. EDA Highlights:
Hour Type Categorization:
Rush Hour: 7–9 AM, 3–6 PM.
Night: 9 PM–6 AM.
Other: All other hours.
Popular Stations:
Identified the top 5 stations for starts and ends.
Ride Duration Insights:
Average and median ride durations across user types.
Temporal Trends:
Weekly and monthly usage patterns.
User Comparison:
Casual vs. subscriber behaviors.

5. Technologies Used:
Python:
Pandas: Data wrangling and manipulation.
Matplotlib & Seaborn: Data visualization.
Jupyter Notebook: Interactive analysis and visualization.
Git: Version control.

6. How to use:
Clone the repository:
git clone https://github.com/amu-jay/DivvyBikes.git
Install dependencies:
pip install -r requirements.txt
Explore the Jupyter notebooks in the notebooks folder to follow the analysis step-by-step.
Contributing

Contributions are welcome! If you'd like to suggest enhancements or add new features:

Fork this repository.
Create a new branch: git checkout -b feature-name.
Commit your changes: git commit -m 'Add a feature'.
Push to the branch: git push origin feature-name.
Open a pull request.

7. Acknowledgments:
Divvy Bikes for providing the data.
The City of Chicago for fostering innovation in public transit.
Python community for the incredible open-source tools.
