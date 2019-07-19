Tableau Dashboard located on Tableau Public as the data source leveraged included more than 17 million records. 

URL for Tableau Public Workbook:
https://10ay.online.tableau.com/#/site/andrewscott/views/ExploringCitibike2018Data/CitiBikeStory?:iid=1

Original Data Downloaded from:
https://www.citibikenyc.com/system-data

Data Manipulation via Python to combine my twelve different workbooks into one CSV. CSV output was 3.4GB with 17.5 million records. 
Using Python made it much easier to combine my twelve tiles, as Excel struggled with the size of my downloaded CSV files. I had some data issues exporting to Excel as my files would only have ten million rows. It took my machine several minutes to run the python script to generate the one CSV. Due to some row limitations with Tableau Public I had to shave my data down to less than 15 million rows. I used a subsequent Python script to limit my CSV to only Subscribers born after 1959, with a gender available.

Python Data Manipulation code here:
https://github.com/ascott4680/20-tableau/blob/master/Citi%20Bike%20Share%202018%20Data%20Handling.ipynb


-Andrew Scott
