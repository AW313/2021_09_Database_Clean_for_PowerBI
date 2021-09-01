**
This is a data cleaning and prep example using Python and Pandas to load, clean, edit and prepare a dataframe for input into PowerBI.
The data is an openfile database of producing oil and gas wells within onshore South Australia.

Workflow used;
- pandas load excel
- delete unwanted columns, rename columns
- REGEX clean up column values - often Company and Foramtion names can have similar values but different descriptions. REGEX consolidated these to common names
- Convert Lat Long degress to deci degrees.   PowerBI only uses decidegrees
- Drop null values from lat long columns. Check dataframe for missing values.
- Export to csv
- Create GITHUB repo from terminal and push files.
