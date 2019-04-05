# email_data

Here I clean and plot some anonymized data from an email system that malfunctioned on a particular day, to prepare these data for analysis. I take a large flat text file of data and used a regex (see tablemaker_better) to capture the desired information in a csv file with three columns. The column"created" represents the time that a task was created-- e.g., when an email was supposed to be sent off. "first_attempt" is the time that the system first attempted to process the task, and "final_attempt" is the time that the system successfully processed the task.

This repo also contains a script for importing a csv file into R and generating histograms, scatter plots, and further datasets from it (see r_import_and_analysis). (Script to be run from an R console; needs to be rewritten if run from command line.)
