

## Minneapolis Temperature Analysis

This Python script analyzes historical temperature data in Minneapolis, Minnesota, to see if global warming has had an effect on the average temperature over the last century.
Installation

To run this script, you must have the following installed:

    Python 3.x
    pandas
    matplotlib
    seaborn

## Usage

    Download or clone the repository to your computer.
    Navigate to the repository's directory.
    Open a command prompt or terminal in that directory.
    Type python minneapolis_temp_analysis.py and press Enter.

## Methodology

The script loads the historical temperature data from a CSV file and performs the following steps:

    Removes the first column of the dataset.
    Removes rows where temperature data is missing.
    Replaces "T" values in the data with 0.01.
    Replaces "M" values in the data with NaN.
    Calculates the average temperature and the difference between high and low temperature for each day.
    Segments the data into seasons and creates a violin plot to visualize the distribution of average temperatures for each season.
    Segments the data into Januarys and creates a box plot to compare the distribution of average temperatures between two time periods (1890-1920 vs. 1990-1920).

## Results

The analysis showed that the average temperature in Minneapolis during January has increased by approximately 3.5 degrees Fahrenheit since 1890. The box plot also showed that the distribution of temperatures shifted towards higher temperatures in the later time period. These results suggest that global warming has had an effect on the average temperature in Minneapolis over the last century.


