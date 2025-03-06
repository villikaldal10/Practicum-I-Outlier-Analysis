# Practicum-I-Outlier-Analysis
Outlier analysis in Dr. Sorauf's Greenhouse Gas Emissions Research

For my Practicum 1 project I decided to join Dr. Sorauf's Greenhouse Gas Emissions project. My focus for these past 8 weeks was on detecting outliers and removing them from our massive "Mega_merged_all_real_values.csv" dataset. It contains over 180,000 rows of emission data, and when conducting our outlier research, we decided to focus on each primary activity, each reporting year (2013-2023), and the emission numbers for each company within that activity and year. As we had 214 distinct primary activities, this was a lot of data to go through, and it was a learning experience for me to get to do this over the past weeks! 

#### If you are interested in hearing more about my project, and the process, feel free to check out my presentation here: https://youtu.be/3fcNP4wNPKk

# Files found in repository:

### Outliers_VK_MESSY_PLAYGROUND.ipynb: 
OPEN AT YOUR OWN RISK. Joke, but it is the notebook I was using each week to try out different methods of removing outliers, many without success, and I just wanted it uploaded if people are interested in seeing the different things I tried through these 8 weeks and how they worked out.

### VK_Outliers_Clean.ipynb: 
This is the finalized notebook where we create the z-score = 2 or higher outliers files.

### VK_Final_Normalized.ipynb: 
This is where we normalize our emission data by the company's revenue before removing the outliers with a z-score of 2 or higher!

### Outliers_Comparison.ipynb: 
This is where we use the two different combined outliers file to remove matching account_id from our original dataset, and you can find the comparison of the two different files, and the numbers behind those removals!

### All_outliers_combined_normalized.csv: 
All outliers from the normalized method in a combined CSV file.

### All_outliers_combined_z2.csv: 
All outliers found using only the z-score of 2 in a combined CSV file.

### Mega_merged_all_real_values.csv (zip): 
Original dataset that we worked on through these past weeks.
