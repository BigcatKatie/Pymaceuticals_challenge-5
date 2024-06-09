Module 5 Challenge

1)Prepare the data.
# Dependancies and setup
# Find the file path and read the mouse data and the study results
# Merge the data into a single DataFrame
# Display the data table of the new DataFrame for preview
# Checking the number of mice
# Our data should be uniquely identified by Mouse ID and Timepoint, get the duplicate mice by ID number that shows up for Mouse ID and Timepoint
# Identify the duplicate mouse
# Show data associated with duplicate time points
# Create a clean DataFrame by dropping the duplicate mouse by its ID (tutor explained why my previous code didn't work, and showed the correct way to drop the duplicate mouse ID)
# Display the first 5 rows of the cleaned dataframe

2)Generate summary statistics.
# Group the cleaned data by Drug Regimen
# Calculate summary statistics
# Assemble the resulting series into a single summary DataFrame

3)Create bar charts and pie charts
# Calculate the total number of rows for each drug regimen
# Create a bar chart showing the total numbers of rows (Mouse ID/Timepoints) for each drug regimen using Pandas
# Create a bar plot showing the total number of rows (Mouse ID/Timepoints) for each drug regimen using pyplot
# Calculate the distribution of female versus male mice
# Create a pie chart show the distribution of female versus male mice using Pandas
# Generate a pie plot showing the distribution of female versus male mice using pyplot

4)Calculate quartiles, find outliers, and create a box plot.
# Calculate the final tumor volume of each mouse across four of the treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin
# Start by getting the last (greatest) timepoint for each mouse,create a Grouped DataFrame for the Last time point
# Merge this group df with the original DataFrame to get the tumor volume at the last timepoint
# Put treatments into a list for for loop (and later for plot labels), create lists for Treatments and Tumor volumn data
# Loop through treatments to extract final tumor volumes
# Calculate the IQR and quantitatively determine if there are any potential outliers, and print the results
# Generate a box plot that shows the distrubution of the tumor volume for each treatment group.

5)Create a line plot and a scatter plot.
# Generate a box plot that shows the distrubution of the tumor volume for each treatment group (select the first mouse)
# Extract data for the selected mouse
# Generate a line plot using Matplotlib
# Generate a scatter plot of mouse weight vs. the average observed tumor volume for the entire Capomulin regimen
# Filter data for Capomulin regimen
# Calculate average tumor volume for each mouse
# Merge average tumor volume with mouse metadata to get the weight
# Generate a scatter plot using Matplotlib

6)Calculate correlation and regression.
# Calculate the correlation coefficient and a linear regression model 
# for mouse weight and average observed tumor volume for the entire Capomulin regimen
# Calculate the correlation coefficient
# Perform linear regression
# Create a regression line
# Display the regression line equation
# Generate a scatter plot with linear regression model using Matplotlib
