# Steps to work on this course project

1. Download the data source and put into a local folder. Extract the compressed file into the UCI HAR Dataset folder.
2. Using setwd() function in RStudio, set the folder as the working directory .
3. Put run_analysis.R in the parent folder of UCI HAR Dataset.
4. Run source(`run_analysis.R`), then it will generate a new file `tidy_data.txt` in the working directory.

# Dependencies

The run_analysis.R file depends on data.table 