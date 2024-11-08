# Eating Behavior Analysis of Thammasat University Students

## Overview

This project analyzes the eating behavior of Thammasat University students through the visualization of survey data. It explores dietary preferences, trends, and habits, providing insights into the eating behaviors of university students.

## Technologies Used

- **Python**: The main programming language for data analysis and visualization.
- **Google Colab**: An online platform used to run the Python scripts for processing and analysis.
- **Pandas**: A Python library for data manipulation and cleaning.
- **Matplotlib**: A plotting library used to create static visualizations.
- **Plotly**: A library used for creating interactive visualizations.
- **WordCloud**: A Python package for generating word clouds to highlight key terms.
- **PyThaiNLP**: A Thai language processing library used for tokenization and stopword filtering.

## Installation

To run this project locally, make sure you have Python installed, then install the required libraries:

```bash
pip install pandas matplotlib plotly wordcloud PyThaiNLP
```

Alternatively, you can run the notebook directly in Google Colab, where all dependencies are pre-installed.

## Dataset

The dataset used in this project consists of survey responses from Thammasat University students. The survey collects data on dietary preferences, meal frequency, food types, and other related factors. The data is pre-processed for analysis and visualization in the Python scripts.

**Note**: The path for the `.csv` file in this project has not been changed, so please ensure that the file is placed in the correct directory when running the project locally.

## Features

1. **Data Processing**: The raw survey data is cleaned and transformed using Pandas for easier analysis.
2. **Visualization**: Interactive and static visualizations are created using Plotly and Matplotlib, respectively.
3. **Word Cloud**: Key terms from the survey responses are visualized as word clouds to show popular foods, meal types, etc.
4. **Thai Language Processing**: PyThaiNLP is used to process Thai text, enabling tokenization and filtering of stopwords for more accurate analysis of student responses.

## Running the Project

1. Open the `Eating_Behavior_Analysis.ipynb` notebook in Google Colab or Jupyter Notebook.
2. Run the cells sequentially to load the data, clean it, and generate visualizations.
3. Explore the insights about the students' eating habits through the interactive and static plots.

## Example Visualizations

- **Dietary Preferences**: Pie charts showing the breakdown of food types preferred by students.
- **Meal Frequency**: A bar chart visualizing how often students eat certain meals (e.g., breakfast, lunch, dinner).
- **Word Clouds**: Visualizations of popular food items based on the survey responses.

## Contributing

Feel free to fork this repository and contribute improvements to the analysis or visualizations. Pull requests are welcome!
