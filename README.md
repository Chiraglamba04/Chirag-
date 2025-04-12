📝 Overview
This project explores and analyzes a dataset related to Indian Railways operations. The dataset includes key operational details such as train numbers, train names, start and end stations, days of operation, and classes available. The goal is to extract meaningful insights about train services across the country through data analysis and visualization techniques.

📂 Dataset Description
Filename: railway.csv
This dataset contains information about various trains operating in India. Key columns include:

train_no: Unique identifier for each train.

train_name: Name of the train.

start_station_code / start_station_name: Origin station's code and name.

end_station_code / end_station_name: Destination station's code and name.

runs_on: Days of the week the train runs (e.g., "Y N Y Y N Y N").

classes: Types of classes available (e.g., 1A, 2A, SL, etc.).

zones: Railway zone under which the train operates.

train_type: Type of train (e.g., Mail, Express, Superfast).

distance: Distance covered by the train (in km).

duration: Time duration of the journey (in HH:MM format).

avg_speed: Average speed of the train (in km/h).

🎯 Objectives
Clean and preprocess the dataset.

Explore the distribution of trains across different zones and types.

Analyze travel durations, distances, and average speeds.

Understand the frequency of train operations across weekdays.

Evaluate availability of train classes on different routes.

Perform statistical and visual analysis for actionable insights.

📊 Key Features
Distribution of trains by zone and train type.

Top fastest and longest routes in terms of distance and duration.

Days with highest and lowest train activity.

Analysis of class-wise availability across zones.

Correlation between distance, duration, and average speed.

🛠️ Technologies Used
Python 3.x

Pandas for data manipulation

Matplotlib / Seaborn for visualization

Jupyter Notebook for interactive analysis
