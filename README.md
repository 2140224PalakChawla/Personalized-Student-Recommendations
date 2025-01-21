# Personalized-Student-Recommendations
Personalized Student Recommendations, this repository contains a Python-based solution for analyzing quiz performance and providing students with personalized recommendations to improve their preparation for exams like NEET.


## Project Overview

This project uses student quiz performance data to generate insights, highlight weak areas, and provide actionable recommendations to improve learning outcomes.


## Features

- **Data Analysis:** Explore quiz performance by topic, difficulty, and accuracy.
- **Insights Generation:** Highlight weak areas and improvement trends.
- **Recommendations:** Suggest actionable steps for targeted improvement.
- **Student Persona:** Identify specific strengths and weaknesses with creative labels.


## Prerequisites

Ensure to install these on your system:

- Python 3.7 or higher
- `pip` package manager
- Recommended IDE: Jupyter Notebook or Visual Studio Code(I have used Jupyter Notebook)
  

## Setup Instructions


1. **Create a Virtual Environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Windows: venv\Scripts\activate
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook:**
   Launch Jupyter Notebook or your preferred IDE and open the `analysis.ipynb` file.

5. **API Configuration:**
   - Ensure API endpoints for quiz data are accessible.
   - Update any required API keys or endpoint URLs in the configuration section of the code.

## Approach Description

### **1. Data Analysis:**
- Fetch and preprocess data from current and historical quiz datasets.
- Analyze trends by topic, difficulty level, and response accuracy using Python libraries like `pandas`, `numpy`, and `seaborn`.

### **2. Insights Generation:**
- Visualize key performance metrics.
- Highlight trends such as commonly missed topics or challenging question types.

### **3. Recommendations Creation:**
- Develop personalized suggestions based on identified weak areas.
- Recommend specific topics, question types, and difficulty levels for targeted improvement.

### **4. Bonus Feature:**
- Define a student persona to summarize strengths and weaknesses in a creative and actionable format.

  ## The reposity contains

1. Include the source code in this repository(Juypter File)
2. Screenshots of key visualizations and insights in the `screenshots` folder.
3. Video demonstrating the script/API is included or linked.
   

## Tech Stack

- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn
- APIs for data fetching


## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your changes.

