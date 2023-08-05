# Matplotlib Analysis of Anti-Cancer Medications
What good is data without a good plot to tell the story? In this assignment, we will get to see intuitive applications of Matplotlib to any real-world situation and will include datasets bridging it all together as a cohesive unit.
# Background
After seeking and getting employment at Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications; I have been assigned as a Senior Data Analyst at the company! Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. I have been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured by myself and other notable specialists of varying skilled backgrounds within the company. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked me with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked for my top-level summary of the study results.
# Datasets for Analysis Purposes
Mouse Metadata: https://github.com/faceadversity/matplotlib-challenge/files/12266516/Mouse_metadata.csv
Study Results: https://github.com/faceadversity/matplotlib-challenge/files/12266518/Study_results.csv
# Instructions
I will be tasked to do the following:
* Run the provided package dependency and data imports, and then merge the mouse_metadata and study_results DataFrames into a single DataFrame. Display      the number of unique mice IDs in the data, and then check for any mouse ID with duplicate time points. Display the data associated with that mouse ID,     and then create a new DataFrame where this data is removed. Use this cleaned DataFrame for the remaining steps. Display the updated number of unique       mice IDs.
* Create a DataFrame of summary statistics that include two of the following: 1) A row for each drug regimen. These regimen names should be contained in     the index column. 2) A column for each of the following statistics: mean, median, variance, standard deviation, and SEM of the tumor volume.
* Generate two bar charts: Both charts should be identical and show the total total number of rows (Mouse ID/Timepoints) for each drug regimen through 
  out the study. The first bar chart will be created with the Pandas DataFrame.plot() method while the second bar chart will be created with the 
  Matplotlib's pyplot method. Two pie charts will also be included for analysis. One using the Pandas method described already including Matplotlib's        pyplot method also.
* Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. 
  Then calculate the quartiles and IQR and determine if there are any potential outliers across all four treatment regimens. Use Matplotlib to generate a 
  box plot that shows the distribution of the final tumor volume for all the mice in each treatment group.
  Highlight any potential outliers in the plot by changing their color and style.
