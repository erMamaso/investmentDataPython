## README

Welcome to the Investment Assets Value Data-Extractor.

**#Assets Value Folder**
First you can find a folder "AssetsValue/" that will contain all .csv files that were extracted from the CIPS of the IMF database year by year.
There you will find a .csv file named as Assets2010Error.csv. This fill is not read by the project and will cause no problems with it.
It is just there in order to know where were our problems at the beginning.

**#Project in zip**
There is a zip file that will content the whole .ipynb project that will let you take any Asset value in any year between any two countries of your preference.
This file alse contains the previous folder mentioned with all the files required.

**#.ipynb file**
The ipynb file is the python notebook itself.

**#How to use it**

1. Create a new project on any Python Notebook (CoCalc for example).
2. Extract all the files in the zip file and add them to the Python Notebook project.
3. Run the whole project (or cell by cell) to set all the functions up
4. Use the last cell (or use another one with the takeAsset Function).
5. Read the following USAGE for the documentation of the takeAsset function.


**#takeAsset USAGE**

The function holds three parameters: "Country 1", "Country 2", "Year"

Remember the following scene: "Country 1" <--assets-- "Country 2"  in year "Year"

The result is the value of Assets that Country 1 holds on Country 2 in the specified Year as the previous scene showed.

If there was no such transaction (it can be that "Country 1" does not hold assets on "Country 2" but there could be that "Country 2" holds assets on "Country 1" that year) it will print the following message:

"Theres no Asset value between "Country 1" and "Country 2" in year "Year""
