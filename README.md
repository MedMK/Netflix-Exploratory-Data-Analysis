# Netflix Exploratory Data Analysis

An analysis of Netflix data to investigate whether the average duration of movies has been declining over time.

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Analysis Steps](#analysis-steps)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

This project explores the Netflix dataset to understand trends in movie durations over the years. The goal is to determine whether there is evidence of a decline in the average duration of movies and identify contributing factors.

## Data

The dataset (`netflix_data.csv`) contains information about various Netflix shows, including columns such as show type, title, country of origin, release year, and duration.

## Analysis Steps

1. **Load the CSV file:** Load the Netflix dataset and filter out TV shows.
2. **Create netflix_movies DataFrame:** Select relevant columns for analysis.
3. **Filter short_movies:** Identify movies with a duration of less than 60 minutes.
4. **Explore contributing factors:** Inspect the short_movies dataset for possible contributing factors.
5. **Assign colors to genres:** Categorize movies into genre groups and assign colors.
6. **Create scatter plot:** Visualize movie duration trends over the years.

## Results

After analyzing the data and creating visualizations, we can draw conclusions about whether movies on Netflix are getting shorter and identify any patterns or contributing factors.

## Usage

To replicate the analysis:

1. Clone the repository.
2. Install the required dependencies.
3. Run the provided Python script.

```bash
pip install -r requirements.txt
python analyze_netflix_data.py
