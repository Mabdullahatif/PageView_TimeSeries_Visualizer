
# PageView TimeSeries Visualizer

## Introduction

This repository contains a Python script that performs data visualization and analysis on freeCodeCamp forum page views data using the Matplotlib and Seaborn libraries. The script draws line, bar, and box plots to visualize various aspects of the dataset.

## Table of Contents

- [Introduction](#introduction)
- [Table of Contents](#table-of-contents)
- [Code Description](#code-description)
- [Key Points / Learning](#key-points--learning)
- [Applicability](#applicability)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [Initial Contributor](#initial-contributor)

## Code Description

The Python script performs the following tasks:

1. Imports necessary libraries: `matplotlib.pyplot`, `pandas`, `seaborn`, and `numpy`.

2. Reads forum page views data from a CSV file using Pandas, parsing dates and setting the index column to 'date'.

3. Cleans the data by filtering out data points outside the 2.5th and 97.5th percentiles.

4. Defines three functions: `draw_line_plot`, `draw_bar_plot`, and `draw_box_plot`.

5. The `draw_line_plot` function draws a line plot using Matplotlib, showing the daily page views from May 2016 to December 2019.

6. The `draw_bar_plot` function draws a bar plot using Matplotlib, showing the average monthly page views for each year.

7. The `draw_box_plot` function draws two box plots using Seaborn: one for the year-wise trend and another for month-wise seasonality.

8. Calls the three functions to generate and save the respective plots.

9. Displays the plots.

## Key Points / Learning

- **Matplotlib and Seaborn Usage:** The script showcases the use of Matplotlib and Seaborn libraries for data visualization and plot creation.

- **Data Cleaning:** The script demonstrates how to clean and preprocess data for visualization.

- **Different Plot Types:** The script illustrates the creation of line, bar, and box plots to visualize different aspects of the dataset.

## Applicability

This code is applicable in scenarios where you need to visualize and analyze forum page views data over time. Potential areas of application include:

- **Web Analytics:** Analyzing and presenting user engagement and page views for online platforms.

- **Performance Monitoring:** Visualizing website or forum performance over specific time periods.

- **Trend Analysis:** Identifying trends and patterns in user interactions and engagement.

## How to Use

To visualize and analyze PageView TimeSeries Visualizer using this script, follow these steps:

1. Clone the repository to your local machine using `git clone https://github.com/Mabdullahatif/PageView_TimeSeries_Visualizer.git`.

2. Download the dataset file `PageView_TimeSeries_Visualizer.csv` and place it in the repository directory.

3. Open the Jupyter Notebook or Google Colab environment.

4. Navigate to the repository directory.

5. Open the `main.py` file.

6. Run the code cells to perform data visualization and analysis and view the generated plots.

## Contributing

Contributions are welcome! To contribute to the FreeCodeCamp Forum Data Visualization, follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix.

3. Make your changes and commit them with descriptive commit messages.

4. Push your changes to your forked repository.

5. Create a pull request detailing your changes and explaining their purpose.

Please make sure to follow the repository's code of conduct and guidelines.

## Initial Contributor

So far, all the work in this repository is purely done by me.


## LinkedIn &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Facebook &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Instagram &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Twitter
<a href="https://www.linkedin.com/in/muhammad-abdullah-atif/">
    <img height="50" src="https://cdn2.iconfinder.com/data/icons/social-icon-3/512/social_style_3_in-306.png"/>
</a> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp;&nbsp;&nbsp;

<a href="https://www.facebook.com/abdullahatif362/">
    <img height="50" src="https://cdn0.iconfinder.com/data/icons/social-flat-rounded-rects/512/facebook-64.png"/>
</a> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

<a href="https://www.instagram.com/abdullah._.atif/">
    <img height="50" src="https://cdn2.iconfinder.com/data/icons/social-media-applications/64/social_media_applications_3-instagram-64.png"/>
</a> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;

<a href="https://www.twitter.com/abd_allah_atif/">
    <img height="50" src="https://cdn3.iconfinder.com/data/icons/2018-social-media-logotypes/1000/2018_social_media_popular_app_logo_twitter-64.png"/>
</a>