# WorldOMeter-Data-Storage
WScraping - Python - GSheets - Azure SQL - PowerBI
This is a project I've been working on during the past few days. It is supposed to store data from the website WorldOMeter every 6 hours. After a year, I plan on doing some type of time series analysis on this, however, for the meantime, the data will be available daily on PowerBI, being automatically taken from the web and published for anyone to see. Some graphs will be available, allowing anyone to see how the total population, suicide rates, CO2 emissions, have been increasing daily, weekly, monthly, or every 6 hours. Besides this, it'll be possible to see during which days of the week each of these statistics tend to increase or decrease faster.
The project was made using the windows task scheduler to execute an .exe Python file created using the lybrary pyinstaller. The jupyter .ipynb file will be available here, and it'll be possible to see what I've done to be able to extract data from the website (Library Selenium) and store it on a Google Sheets spreadsheet, on 3 different worksheets (Library GSpread). After this, I will transfer it to Azure SQL, and from SQL to PowerBI, and on PowerBI I'll create all the visualizations that I consider to be important. A couple of videos explaining the steps necessary are available on this link https://drive.google.com/drive/folders/1ffCa_pQ04iYAkxR2NouzB87TfpL0UgwF?usp=sharing.
