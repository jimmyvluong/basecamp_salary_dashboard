# Resources
1. Read data from Google Sheets
- https://towardsdatascience.com/read-data-from-google-sheets-into-pandas-without-the-google-sheets-api-5c468536550
2. Drop specific columns when reading in a .csv
- https://stackoverflow.com/questions/48899051/how-to-drop-a-specific-column-of-csv-file-while-reading-it-using-pandas
3. Dealing with the SettingWithCopyWarning
- https://realpython.com/pandas-settingwithcopywarning/
4. Ensure Pandas reads in dates correctly
- https://stackoverflow.com/questions/17465045/can-pandas-automatically-read-dates-from-a-csv-file
# Data Preparation Steps
1. [Done] Read in only the columns we're interested in.
2. [Done] Extract the year from "Submitted At" column
3. Map "Years of Experience" to a simpler field with ranges (0 to 3 years, 4 to 7 years, 8 to 10 years, 10+ years)
- See: https://github.com/jimmyvluong/Python-CalTPA-Demo/blob/master/caltpa_single_file.ipynb

# Tableau
1. Creating histogram bin labels
- https://www.thedataschool.co.uk/jevon-dacosta/the-proper-way-to-label-bin-ranges-on-a-histogram-tableau/
STR(INT([Pay]/[Size of bin])*[Size of bin]) +
"-" +
STR(INT([Pay]/[Size of bin])*[Size of bin]+[Size of bin]-1)