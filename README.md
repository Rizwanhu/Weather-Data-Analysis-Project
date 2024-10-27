# **Weather Real-Time Pakistan Cities Data Analysis**

This project provides real-time data analysis of weather conditions in various cities across Pakistan using the OpenWeather API. The analysis includes data collection, cleaning, exploration, and visualization to gain insights into weather patterns across different cities.

## **Project Overview**

1. **Data Scraping**: Collects real-time weather data for cities in Pakistan using the OpenWeather API.
2. **Data Exploration**: Explores and analyzes the dataset structure and summary statistics.
3. **Data Cleaning**: Cleans the data by handling missing values, normalizing columns, and ensuring data consistency.
4. **Exploratory Data Analysis (EDA)**: Investigates relationships, distributions, and patterns in weather data.
5. **Data Visualization**: Visualizes weather conditions, trends, and relationships between key weather features.

---

## **Table of Contents**
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Project Steps](#project-steps)
- [Dependencies](#dependencies)
- [Commands](#commands)
- [License](#license)

---

## **Installation**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Rizwanhu/weather-pakistan-data-analysis.git
   cd weather-pakistan-data-analysis
   ```

2. **Set up a virtual environment (recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install required libraries:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Add API Key**: Create a `.env` file in the root directory and add your OpenWeather API key:
   ```
   OPENWEATHER_API_KEY=your_api_key_here
   ```


---

## **Project Steps**

### **Part 1: Data Scraping**
- Collect real-time weather data for cities in Pakistan (temperature, humidity, wind speed, cloudiness, etc.).
- Save the data in CSV format for further analysis.

### **Part 2: Data Exploration**
- Load the dataset, inspect its structure, and review summary statistics for numerical and categorical features.

### **Part 3: Data Cleaning**
- Handle missing values, duplicates, and data inconsistencies.
- Convert columns to appropriate data types (e.g., `Sunrise` and `Sunset` to time).
- Normalize column names for easier handling.

### **Part 4: Exploratory Data Analysis (EDA)**
- Analyze distributions, investigate correlations, and explore patterns and outliers.
- Group and compare cities based on weather conditions.

### **Part 5: Data Visualization**
- Use Seaborn and Matplotlib to create visualizations (histograms, scatterplots, boxplots, heatmaps).
- Visualize trends and relationships across weather conditions and cities.

---

## **Dependencies**

This project requires the following Python packages:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `requests`
- `python-dotenv`

Install all dependencies using:
```bash
pip install -r requirements.txt
```

---

## **Commands**

### Essential Commands for Setup and Execution

1. **Activate Virtual Environment**:
   - On MacOS/Linux:
     ```bash
     source venv/bin/activate
     ```
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```

2. **Run Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

3. **Run Python Scripts**:
   ```bash
   python scripts/data_scraping.py
   ```

4. **Deactivate Virtual Environment**:
   ```bash
   deactivate
   ```

---

## **License**

This project is open-source and available under the MIT License. See the `LICENSE` file for more information.

---
