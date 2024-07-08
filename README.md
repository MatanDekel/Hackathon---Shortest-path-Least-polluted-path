<h1>Hackathon---Shortest-path-Least-polluted-path</h1>
<h3>Description:</h3>
This project aims to predict travel time between two points and subsequently find the shortest or least polluted path. We utilized XGBRegressor for the time prediction and NetworkX for creating the graph and determining the shortest or least polluted paths.

<h3>Installation:</h3>
To get started with this project, follow these steps:

Clone the repository:


git clone https://github.com/MatanDekel/hackathon2024.git
cd hackathon2024
Create a virtual environment:


python -m venv venv
Activate the virtual environment:

On Windows:

venv\Scripts\activate

On macOS/Linux:

source venv/bin/activate

Install the required packages:


pip install -r requirements.txt
<h3>Usage</h3>
<h4>Predict Travel Time</h4>
Open the Jupyter notebook for travel time prediction:


jupyter notebook hackathon2024_TravelTime_GUI.ipynb
Follow the instructions in the notebook to load data and make predictions.

<h4>Find Shortest/Least Polluted Path</h4>
Open the Jupyter notebook for pollution path analysis:


jupyter notebook hackathon2024_Pollution_GUI.ipynb
Follow the instructions in the notebook to analyze and visualize the paths.

<h3>Data</h3>
Ensure you have the necessary data file (DATA pswd.csv) in the /mnt/data/ directory. This file contains the data points used for travel time prediction and pathfinding.
