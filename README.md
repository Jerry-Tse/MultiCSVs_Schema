> ### [Click here for nbviewer](https://nbviewer.jupyter.org/github/Jerry-Tse/Internship_codebook/blob/master/MultiCSVs_Schema_Getter/Schema_MultiCSVs.ipynb)
<br/>

# Get Schema information from Multiple CSVs
Reach the columns and datatypes information when dealing with huge amount of CSVs.
    
----

<br/><br/>
![test image size](https://github.com/Jerry-Tse/Internship_codebook/blob/master/MultiCSVs_Schema_Getter/example.png)
  
## Set up 
Set environment in first cell:  
  *   Put all the target csv you wish get information into a file and record the directory as PATH_RAW  
  *   Record the path you wish to have output as PATH_OUT 
  *   Make sure the right encoding for reading the csv  

## Output
Two csv output are generated:
- header_all.csv: contains columns with csv_name and col_name within that csv.
- header_all_dtypes.csv: contains columns with csv_name, col_name within that csv and dtypes of that columns.
