# CSV_Randomizer

This tool is able to import a csv file into a simple GUI with Tkinter and to display a random choosen row of the list. 

How to use: 
1.)Click on "Browse Files" and choose the .csv file 
2.)Click on "Choose Random" to choose one row of the csv file at random 

The program will ignore the first row of the CSV, as it expects it to be a header of the data 


How to convert to .exe with pyinstaller: (with "Python 3.10 _bootlocale Error)

1.) first install pyinstaller 
pip install pyinstaller 

2.) Go to file respository (Ordner), leftclick on filepath and enter "cmd" - enter

3.) pyinstaller -onefile -w --exclude -module _bootlocale CSV_Randomizer.py  

