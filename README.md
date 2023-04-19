



# Google SpreadSheet
  
This module allows you to read, write and update Google spreadsheets. You can add, delete, duplicate or even hide sheets; filter data; add or delete rows and columns; modify cells format, copy/cut and paste them; and more.  

  
*Read this in other languages: [English](Manual_Google SpreadSheet.md), [Português](Manual_Google SpreadSheet.pr.md), [Español](Manual_Google SpreadSheet.es.md)*  


## How to install this module
  
To install the module in Rocketbot Studio, it can be done in two ways:
1. Manual: __Download__ the .zip file and unzip it in the modules folder. The folder name must be the same as the module and inside it must have the following files and folders: \__init__.py, package.json, docs, example and libs. If you have the application open, refresh your browser to be able to use the new module.
2. Automatic: When entering Rocketbot Studio on the right margin you will find the **Addons** section, select **Install Mods**, search for the desired module and press install.  


## How to use this module

Before using this module, you must register your app into Google Cloud Portal.

1. Sign in with a google account and get into the following link: https://console.cloud.google.com/projectcreate?previousPage=%2Fhome%2Fdashboard
2. Complete the form to create a new proyect and then press "Create".
3. Within the Navigation Menu (Left), get into API and Services.
4. Go to the upper section and press "+ ENABLE API AND SERVICES".
5. Search for "Google Sheets API", select it 
and then press "ENABLE".
6. Go back to the Navigation Menu, go to API and Services and then get into Credentials.
7. Press Create Credentials and select OAuth Client ID. Then select Application Type: Desktop App, give it a name and press Create.
8. Download the credentials JSON file.
9. Finally, go back to the Navigation Menu, go to Consent Screen and add your user in the "Test Users" section (even if it is the same that is creating the app).

Note: When the first connection is made, a .pickle 
file will be created in the Rocketbot root folder, to connect to the same service with another account you must give each session a name. If credentials expire you must delete the .pickle file and create and download a nwe credentials (JSON) file.


## Overview


1. Setup G-Suite credentials  
Get permissions to handle Google SpreadSheet with Rocketbot

2. Create SpreadSheet  
Create a new spreadsheet in Google SpreadSheet

3. Create Sheet  
Create a new sheet in selected SpreadSheet

4. Update Sheet properties  
Update a sheet properties from selected SpreadSheet

5. Delete Sheet  
Delete a sheet from selected SpreadSheet

6. Write cells  
Write to a cell or range of cells in the selected Spreadsheet

7. Format cells  
Change format of a cell or range of cells in the selected Spreadsheet

8. Read cells  
Read a cell or range of cells from the selected Spreadsheet, example A1 or A1:B5

9. Copy/Cut and paste  
Copy or cut and paste a cell or range of cells in the selected Spreadsheet

10. Get sheets  
Get list of sheets with their ID of the selected Spreadsheet

11. Count rows and/or columns  
Count the used rows and/or columns of the selected sheet

12. Add column  
Add Columns to Selected Spreadsheet

13. Add row  
Add rows to the selected Spreadsheet

14. Delete column  
Delete a column from a selected Spreadsheet

15. Delete row  
Delete a row from a selected Spreadsheet

16. Filter data  
Filter data in the selected Spreadsheet

17. Unfilter data  
Unfilter data in the selected Spreadsheet

18. Get filtered cells  
Get the filtered cells

19. Duplicate sheet  
Duplicates the selected sheet to the same or another workbook

20. Text to columns  
Splits a column of text into multiple columns, based on a delimiter in each cell.  




----
### OS

- windows
- mac
- linux
- docker

### Dependencies
- [**google-api-python-client**](https://pypi.org/project/google-api-python-client/)- [**google-auth-httplib2**](https://pypi.org/project/google-auth-httplib2/)- [**google-auth-oauthlib**](https://pypi.org/project/google-auth-oauthlib/)- [**gspread**](https://pypi.org/project/gspread/)
### License
  
![MIT](https://camo.githubusercontent.com/107590fac8cbd65071396bb4d04040f76cde5bde/687474703a2f2f696d672e736869656c64732e696f2f3a6c6963656e73652d6d69742d626c75652e7376673f7374796c653d666c61742d737175617265)  
[MIT](http://opensource.org/licenses/mit-license.ph)