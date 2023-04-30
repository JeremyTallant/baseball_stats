# A New Era of Data Analysis in Baseball
## Description 
There's a new era of data analysis in baseball. Using a new technology called Statcast, Major League Baseball is now collecting the precise location and movements of its baseballs and players. In this project, we will use Statcast data to compare the home runs of two of baseball's brightest (and largest) stars, Aaron Judge (6'7") and Giancarlo Stanton (6'6"), both of whom now play for the New York Yankees.

The dataset used in this project is from [Baseball Savant.](https://baseballsavant.mlb.com/about)
## Usage
Clone this repository and open the Jupyter notebook file (`*.ipynb`) in a Jupyter environment with Python kernel support. Make sure to install the required packages such as `pandas`, `numpy`, `seaboarn`, and `matplotlib`. You can do this by running the following commands in a code cell within the notebook:
```python
!pip install pandas numpy matplotlib seaboarn
```
Once the packages are installed, run the code cells in the notebook to generate the plots and analyses.

If you don't have a Jupyter environment set up, you can install Jupyter Notebook and the Python kernel using the following steps:

1. Install Jupyter Notebook by following the instructions on the [official Jupyter website](https://jupyter.org/install).

2. Ensure you have Python installed. If not, you can download and install Python from the [official Python website](https://www.python.org/downloads/).
## Contents
1. **The Statcast revolution:** Load the CSV files, which hold the Statcast data for each player, into pandas DataFrames.
2. **What can Statcast measure?:** Display the last five rows of the judge DataFrame.
3. **Aaron Judge and Giancarlo Stanton, prolific sluggers:** Isolate each player's batted ball events for the 2017 season.
4. **Analyzing home runs with Statcast data:** Isolate each player's home runs then plot exit velocity vs. launch angle.
5. **Home runs by pitch velocity:** Plot the pitch velocities of each player's home runs on box plots
6. **Home runs by pitch location (I):** Create a function that returns the x-coordinate of a pitch zone.
7. **Home runs by pitch location (II):** Create a function that returns the y-coordinate of a pitch zone.
8. **Aaron Judge's home run zone:** Assign Cartesian coordinates to the strike zone and plot pitches that resulted in Judge home runs as a 2D histogram.
9. **Giancarlo Stanton's home run zone:** Assign Cartesian coordinates to the strike zone and plot pitches that resulted in Stanton home runs as a 2D histogram.
10. **Should opposing pitchers be scared?:** Answer the following question: "Should opposing pitchers be wary of Aaron Judge and Giancarlo Stanton?"