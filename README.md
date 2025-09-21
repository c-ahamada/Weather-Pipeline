# Weather-Pipeline

## Project Overview
The project demonstrates a simple **data engineering pipeline** using the Open-Meteo API.
The goal is to automatically collect, process, store and visualize weather data for a specific city (e.g., Lyon).

## Project Plan

### 1. Extrqct
- Call the Open-Meteo API to retrieve zeather data (temperature, precipitation, wind, etc.).
- Collect daily or periodic data automatically.

### 2. Transform
- Clean and structure the data.
- Convert dates to standard formats, rename columns, and handle missimg values.

### 3. Load
- Store the cleaned data in a CSV file or SQLite database.
- Organize files into a 'data/' folder for clarity.

### 4. Analyze / Visualize
- Create basic visualization to show trends in temperatre, precipitation , etc.
- identify patterns or anomalies in the data.

### 5. Automation (Optional / Bonus)
- Prepare scripts to rerun the pipeline daily oor weekly.
- Demonstrates a simple end-to-end ETL workflow.

## Technologies Used
- Python (pandas, reauests, matplotlib)
- Google Colab
- git / GitHun

## How to run

1. Clone the repository
2. Open the notebook in Google Colab.
3. Run the first cell to set up GitHub integration and fetch the latest version.
4. Execute the cells sequentially to extract, trqnsform, load, and visualize the data.