# Overview
This project provides a detailed analysis of movie ratings and reviews using various spreadsheet functions and dynamic reporting techniques. It categorizes movies, generates actionable insights, and presents interactive reports to analyze audience preferences effectively.

## Features
### 1. Data Transformation

   Extracted genres and movie names from a single column using the SPLIT function.
Converted audience ratings from text to numeric format using the VALUE function for accurate analysis.

### 2. Movie Categorization
   
###### Categorized movies based on their rating scores:
Excellent Movie: Ratings ≥ 90.

Good Movie: Ratings ≥ 75 and < 90.

Below Average Movie: Ratings < 75.

### 3. Dynamic Reporting
   
#### a. Genre-wise Ratings and Reviews
Added a dropdown list for selecting genres to display ratings and reviews of movies dynamically.
#### b. Audience Review Analysis

Created a dropdown list for reviews (Excellent, Good, Below Average).
###### Calculated:
Total number of movies in the selected category.
Average audience rating.
Maximum and minimum ratings.
#### c. Genre-wise Top Three Movies
Implemented a dropdown list to filter top 3 movies in the selected genre based on audience ratings.
## How It Works
### Step 1: Data Preparation
The dataset includes a column combining genres and movie names. Using the SPLIT function, these were separated into individual columns for easy access.
### Step 2: Rating Conversion
Transformed text-based ratings into numeric format using the VALUE function.
### Step 3: Categorization and Insights
##### Each movie was categorized based on predefined rating conditions.
Reports were designed to filter, display, and analyze the data dynamically.
## Functions Used
#### SPLIT: 
To separate genres and movie names from a combined column.
#### VALUE: 
To convert text-based ratings into numbers.
#### Dropdown Menus: 
For interactivity and dynamic filtering of data.
#### Filter and Sort: 
To display specific subsets of data, such as the top 3 movies in a genre.
