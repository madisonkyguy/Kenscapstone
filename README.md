# Ken's Franchise Valuation Capstone project

# Overview
This respository is for the final capstone project for the Data Analysis Module
I chose this project as I am an avid Sports fan and have always been amazed at the valuations that the biggest franchises in sports seem to be given.  In this project I chose to compare the two biggest sports in the US(Pro Football and Pro Basketball) to determine which of these leagues has the franchises with the greatest values.  As as an aside, I also did some comparisons of the franchises and their Revenues.

# Data

I pulled the datasets I used from two datasets located in the following locations:

https://www.cnbc.com/2025/02/14/cnbcs-official-nba-team-valuations-2025.html

https://www.cnbc.com/2024/09/05/official-nfl-team-valuations-2024.html

Inside the datasets above contained information for the following:  The Franchises, their current Valuation and the Revenue they have made over the past year

# Project Structure

I utilize a Jupyter notebook to incorporate the datasets in Python
Once I imported the datasets, I used Python and the packages provided by Pandas to do some clean up of the data as well as some calculations with that data
I then utilized Matplotlib to develop some visualizations using Graphs to demonstrate what my calculations were showing
I then developed a data dictionary that can be used by future developers to see how the values are designated in these datasets as well as a virtual environment so it can be tested and verified that it is indeed functioning

Features I utilized in this project

# Feature:  Read Two Data Files - I used 2 CSV files from the above URLS
           
           #Clean your data and perform a pandas merge with your two data sets, then calculate some new values based on the new data set -  
           
           I cleaned my data by removing some unnecessary columns from each CSV and then I joined them using Pandas on the 'Value' column.  I then performed 3 different calculations using panda functions on the 'Value' and 'Revenue' columns

           #Make 3 matplotlib or seaborn (or another plotting library) visualizations to display your data:  
           
           I created 3 seprate graphs in my code using matplotlib functions to illustrate what my data was meant to show

           #Build a custom data dictionary and include it either in your README or as a separate document. This will only apply if your data set does not already have a data dictionary or if you’re building a custom data set. For an example, see the resources to the right 
           
           I created a Data Dictionary that could be used by future developers to determine what the data types will be in this code.  I included this dictionary in my Read Me file

           #Utilize a virtual environment and include instructions in your README on how the user should set one up

           I created a Virtual environment for other developers to use to test my code and included the instructions on how to initialize, utilize and then deactivate the virtual environment

           
# Annotate your code with markdown cells in Jupyter Notebook,
  write clear code comments, and have a well-written README.md. Tidy up your notebook, and make sure you don’t have any empty cells or incomplete cells that don’t do anything. Make sure it’s all functional before your final github commit:

 Throughout my code I included Markdown boxes to explain what each part of my code was going to do

# Getting Started

  Clone the following repository in Github:  https://github.com/madisonkyguy/Kenscapstone
  Install Pandas and matplotlib
  Go through this specific Jupyter notebook:  CapstoneCode.ipynb


 # Data Dictionary  (utilized ChatGPT to get structure correct for Readme)

| Field Name | Type   | Description                                   | Example            |
|------------|--------|-----------------------------------------------|--------------------|
| Team Name  | String | The name of the Franchise                     | New York Knicks    |
| Value      | Float  | The amount the Franchise is worth             | $5.1B              |
| Revenue    | Float  | The amount the Franchise has earned           | $546M              |


# Initialize Virtual Environment

In order to test my code, you will need to do via a virutal environment.  Please follow the instructions below:

1. Clone the repository: https://github.com/madisonkyguy/Kenscapstone to a directory for this project in your terminal.
2. Within the project folder, run this command in the terminal: python -m venv classvm
3. Activate the Virtual environment by typing source classvm/Scripts/activate
4. Next install the required dependencies: pip install -r requirements.txt
5. Run the file: https://github.com/madisonkyguy/Kenscapstone/blob/main/Capstone%20Code.ipynb
6. Exit out of the virtual environment by typing the word deactivate

Feel free to leave feedback as I love to hear what you think