Tableau Dashboard located on Tableau Public as the data source leveraged included more than 17 million records, this data was filtered down to nearly 15 million records. Chriteria were subscribers to the Citibike program with a birth year of 1960 or later, and a confirmed gender.

URL for Tableau Public Workbook:<br>
https://public.tableau.com/profile/andrew.scott3265#!/vizhome/Citi2018/CitiBikeStory

Packaged Workbook Download on Google Drive 380MB:<br>
https://drive.google.com/open?id=1Dl5WIya_d0iq9qNQAJf1QstyjWH860ys

Original Data Downloaded from:<br>
https://www.citibikenyc.com/system-data

Data Manipulation via Python to combine my twelve different workbooks into one CSV. CSV output was 3.4GB with 17.5 million records. Using Python made it much easier to combine my twelve tiles, as Excel struggled with the size of my downloaded CSV files. I had some data issues exporting to Excel as my files would only have ten million rows. It took my machine several minutes to run the python script to generate the one CSV. Due to some row limitations with Tableau Public I had to shave my data down to less than 15 million rows. I used a subsequent Python script to limit my CSV to show only Subscribers born after 1959, with a gender available.

Python Data Manipulation code here:<br>
https://github.com/ascott4680/20-tableau/blob/master/Citi%20Bike%20Share%202018%20Data%20Handling.ipynb
and here:<br>
https://github.com/ascott4680/20-tableau/blob/master/Data_handling_2.ipynb

-Andrew Scott
July 2019
