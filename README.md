# Analysis of Engineer-related Employment Trend in United States

### `Project Status: [Completed]`

## Project Intro/Objective
Many engineer graduates, young engineers and experienced engineers feel confused and frustrated with their career directions and paths. They lack the skills, ability, information, and confidence to seek a better job, gain promotion at existing place of work, or establish themselves as exceptional managers and executives. 

There are various career coaching services online, and one of them, the Engineer’s Coach, is offering a one-on-one career counseling service to engineers, which charges more than $75 per hour. U.S. Bureau of Labor Statistics also provide some basic career outlook for engineers, but not useful for individual career choice. 

Considering that current one-on-one career counseling is rather expensive and engineer employment outlook on Bureau of Labor Statistics websites is not detailed enough, our start-up, YouAreHired Company, is dedicated to providing engineers with practical career guidance based on engineering occupation data analysis, thus helping engineers map out their personalized career paths and achieve future success at work. YouAreHired Company is bridging the gap by providing engineers with in-depth analysis of occupation data and advice on personalized career trends. 

### Methods Used
- Exploratory Data Analysis
- Data Visualization
- Web Scraping

### Technologies
- Jupyter Noteboook
- Libraries: 
    - Numpy
    - Pandas
    - BeautifulSoup
    - Matplotlib
    - Plotly
    - Seaborn
    - Statsmodel

## Needs of this project
- Data Exploration/Descriptive Statistics
- Data Processing/Cleaning
- Writeup/Reporting
- etc.

## How to Use Our Code
Before run the whole ipynb file, please make sure all the datasets are in the same document as ipynb file. 

Then open the ‘AIPI510 project_Team8_Combined code.ipynb’ file, where we combined all the codes and divided into different parts in one file.

### The structure of our code:
+ Step 0: Introduce the libraries and datasets
    + Load the data
+ Step 1: Data Preparation
    + Check for missing data
    + Fill the missing data using different methods
    + Merge datasets to get useful information
+ Step 2: Visualization of df1---Wage and employment number
    + 2.1 Plot employment numbers for each state
        + Slice the dataset into data we want to visualize
        + Define the function to plot top 20 occupations with the highest employment numbers
        + Define the function to plot employment numbers for each state
    + 2.2 Plot wage(mean/median/25%/75%/standard deviation) of different occupations in U.S.
+ Step 3: Visualization of df2---Age
    + 3.1 Plot the employment by occupation and age group (engineer)
    + 3.2 Plot pie chart of employment by age group (all occupation & engineers)
    + 3.3 Plot the top 20 occupations with highest or lowest median age
+ Step 4: Visualization of df3---Gender
    + 4.1 Visualize the median wage for male and female in selected occupations
    + 4.2 Visualize the employment number by gender for all occupations/engineer-related jobs
    + 4.3 Visualize the top 20 occupations with highest earnings by gender
+ Step 5: Visualization of df4---Race
    + 5.1 Visualize the employment by race for all occupations/engineer-related jobs
    + 5.2 Visualize the top 20 occupations with the highest wage by race
+ Step 6: Webscraping and visualization of df6---Job openings
    + 6.1 Web Scraping for Indeed.com (commented out)
    + 6.2 Data Visualization
+ Step 7: Visualization of df7---Time series of race and gender
    + 7.1 Prepare for the dataset
    + 7.2 Data visualization

## Contributing Members
Team Members:
- Lanyu Dong
- Chuting Li
- Tong Zhou
- Hung-wei Chung

## Contact
Feel free to contact team members with any questions!
+ Lanyu Dong (lanyu.dong@duke.edu)
+ Tong Zhou (tong.zhou045@duke.edu)
+ Chuting Li (Chunting.li@duke.edu)
+ Hung-wei Chang (hungwei.chang@duke.edu)
