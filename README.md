# ADA: Wedge Process

This repository builds on our Wedge Exploration exercise. This assignment will help you carry out the Wedge project
at an A level. 

1. Create an empty data frame called `wedge_summary` with the following columns: file_name, num_rows, num_cards, num_dates
1. Iterate over the zip files that hold the Wedge transaction files
2. Unzip each file one at a time (so this will be part of a `for` loop)
3. Use the CSV sniffer to determine the delimiter and whether or not there is a header row. 
4. Read, or attempt to read, the file into a Pandas dataframe, using the delimiter and handling headers correctly. 
5. For each file, store a row in `wedge_summary` that holds the values listed above. `num_cards` should be the unique card numbers in the file and `num_dates` should be the number of dates.  





