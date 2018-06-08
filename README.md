# HW16---Data-Journalism-and-D3

## Background

The editor wants to run a series of feature stories about the health risks facing particular demographics. The goal is to sniff out the first story idea by sifting through the latest information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System.

## Task
#### 1. Find the Data

You need to find a correlation between various data variables, each measured state by state and taken from different data sources: 

For demographic information, we are using the 2014 one-year estimates from the U.S. Census Bureau's American Community Survey - [American FactFinder](http://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml) tool. Below are the dataset criteria:

* Topics -> Dataset -> 2014 ACS 1-year estimates
* Geographies -> Select a geographic type -> State - 040 -> All States within United States and Puerto Rico

Selected data will be downloaded as .csv file.

For health risks data, we are using 2014 survey data from the [Behavioral Risk Factor Surveillance System](https://chronicdata.cdc.gov/Behavioral-Risk-Factors/BRFSS-2014-Overall/5ra3-ixqq). 

All raw data were saved in the data/raw_data folder. 

#### 2. Format and Test the Data

We combined the data and put the clean data into data/clean_data folder. To test on the correlation, we test the data using Excel's `=CORREL()` function. The goal is to aim for a value either less than -0.5 or more than 0.5—these values (moderate correlated).

#### 3. Visualize the Data

Use D3 to visualize the data `app.js` `d3.html` were the files to prepare the coding. 

#### 4. Embed into an iframe

When `d3.html` displays the graphic just as you'd like it to, we embed it in `index.html` with an iframe. A quick written analysis of the data were provided below the graphic.

#### 5. Result 

To view the result, please download the files, open cmd in the file, and type `python -m http.server` in the cmd, and use your local path (something like this http://###.#.#.#:8000) to view the website. 

Alternatively, the solution has been deployed through [Gibhub](https://zl14e161110.github.io/HW16---Data-Journalism-and-D3/.). 

Below are some snapshots of the website:
![1](Images/web1.png)

![2](Images/web2.png)

![3](Images/web3.png)

![4 with tooltip](Images/web4.png)
  

