**********************************
Instructor's name: **Naci Dilekli** 
Instructor's github: *https://github.com/ndilekli/*
Author's name: **Thomas Calvet** (EPF Student)
Author's github: *https://github.com/Thomas-C-EPF*
Contact the author: thomas.calvet@epfedu.fr
**********************************
This project developed for the Geospatial Programming class of Spring 2020, an international collaboration between two universities, EPF of France and RUDN of Russia”.
*https://www.epf.fr/*
*http://www.rudn.ru*
********************************** 
Purpose:
This work allow you to find the best city to live in while minimizing nuclear contmaination and pollution risks.
*Screenshot0* = General risks points (nuclear tests sites, nuclear, gas and coal power plants)
*Screenshot1* = Nuclear High risks ares
*Screenshot2* = Combined risks areas (nuclear and humain pollution)
*Screenshot3* = Major cities in the USA
*Screenshot4* = Final results (best cities according to user entered parameters) after computing the function
********************************** 
How it works:
The function takes as inputs, the distances from nuclear (*Screenshot1*), coal, and gas power plants (*Screenshot0*) as well as your choice in terms of minimum population and the vacancy rate of your dream city. It then creates buffers related to your distances inputs (*Screenshot2*) and substract all cities (*Screenshot3*) that are located inside the "high risks" area. Moreover, user entered conditions helps to get a more relevant city choice and finally sorts the remaining cities (*Screenshot4*) in the desired order (user entered order as well).
The *flowchart* is also available to provide other information.
********************************** 
How to use:
*First:* Create a folder named "Thomas_Calvet_City_Choice"
*Second:* Put all downloaded files into the folder "Thomas_Calvet_City_Choice"
*Third:* Place the folder "Thomas_Calvet_City_Choice" in your Local Disk (C:)
*Fourth:* Open Jupyter Notebook via the ArcGIS panel
*Fifth:* Select "CityChoice_Thomas_Calvet.ipynb" and open it
*Sixth:* Enter the desired values and run the function
**********************************
Function:

CityChoice("C:/Thomas_Calvet_City_Choice/City_Choice_In_Python/City_Choice_In_Python.gdb",
           "USA_NPP", "A miles",                           (Nuclear Power Plants Layer ~ Feel free to enter the A value you want (=distance from NPP))
           "USA_NTS", "B miles",		     (Nuclear Tests Sites Layer ~ Feel free to enter the B value you want ( =distance from NTS))
           "USA_GPP", "C miles", 		     (Gas Power Plants Layer ~ Feel free to enter the C value you want (=distance from GPP))
           "USA_CPP", "D miles",		     (Coal Power Plants Layer ~ Feel free to enter the D value you want (=distance from CPP))
           E, F,		                       (Enter the minimum population of your dream city (E), Enter the number of empty houses you want to have in your new city (F))
          "FIELD", "METHOD")   	                       (Sort your cities by FIELD = "POPULATION" or "VACANT", Select your sort METHOD = "ASCENDING" or "DESCENDING")

**********************************
If you are running into trouble 
or having question, feel free to 
contact me whatever the 
subject is.

Thomas Calvet
********************************** 
