# Bike Share Data Analysis

## Overview
This project explores bike share data from three major U.S. cities—Chicago, New York City, and Washington, DC. Using R, we analyze bike share usage patterns by computing descriptive statistics and creating visualizations to answer intriguing questions about usage trends across the cities.

The dataset includes information on start and end times, trip durations, station names, and user types, and allows us to examine differences in bike share usage across different times, locations, and user demographics.

## Table of Contents
- [Overview](#overview)
- [Datasets](#datasets)
- [Features](#features)
- [Requirements](#requirements)
- [Getting Started](#getting-started)
- [Analysis Questions](#analysis-questions)
- [Files](#files)

## Datasets
The project utilizes bike share data from the first six months of 2017. Data files for each city contain six primary columns:

- **Start Time** (e.g., `2017-01-01 00:07:57`)
- **End Time** (e.g., `2017-01-01 00:20:53`)
- **Trip Duration** (in seconds, e.g., `776`)
- **Start Station** (e.g., `Broadway & Barry Ave`)
- **End Station** (e.g., `Sedgwick St & North Ave`)
- **User Type** (Subscriber or Customer)

The Chicago and New York City datasets also include:
- **Gender**
- **Birth Year**

This cleaned data format provides a consistent structure for analysis across cities.

## Features
Key areas explored in the dataset include:
- **Popular Times of Travel**: Identifying the most common month, day, and hour for trips.
- **Popular Stations and Trips**: Analyzing the most frequently used start and end stations, as well as the most common routes.
- **Trip Duration**: Calculating total and average trip durations.
- **User Information**: Summarizing counts of user types and, for NYC and Chicago, analyzing gender distribution and birth years.

## Getting Started
1. **Clone the repository** or download the project files to your local machine.
2. **Set up R** if you are working locally.
3. **Open the project notebook** to access helper code and guidance for analyzing the data.

## Analysis Questions
The following questions guide the exploration of the dataset:
1. **Popular Times of Travel**  
   - What is the most common month, day of the week, and hour of day?
2. **Popular Stations and Trips**  
   - What are the most common start station, end station, and trip (combination of start and end stations)?
3. **Trip Duration**  
   - What are the total and average travel times?
4. **User Information**  
   - What are the counts of each user type and gender?  
   - What are the earliest, most recent, and most common birth years (only available for NYC and Chicago)?

## Files
The following files are necessary for the project:
- **chicago.csv**  
- **new_york_city.csv**  
- **washington.csv**

These files contain the data necessary to answer the analysis questions. Additional code templates and guidance are provided within the notebook file.

---


