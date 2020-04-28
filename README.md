# EPF-RUDN-USCityChoice-test

1. **Credits:**  
Instructor's name: **Naci Dilekli**  
Instructor's github: *https://github.com/ndilekli/*  
Author's name: **Thomas Calvet** (EPF Student)  
Author's github: *https://github.com/Thomas-C-EPF*  
Contact the author: thomas.calvet@epfedu.fr  

2. **Intent:**  
This project developed for the Geospatial Programming class of Spring 2020, an international collaboration between two universities, EPF of France and RUDN of Russia”.  
*https://www.epf.fr/*  
*http://www.rudn.ru*  

3. **Purpose:**  
This work allow you to find the best city to live in while minimizing nuclear contmaination and pollution risks.  
*Screenshot0* = General risks points (nuclear tests sites, nuclear, gas and coal power plants)  
*Screenshot1* = Nuclear High risks ares  
*Screenshot2* = Combined risks areas (nuclear and humain pollution)  
*Screenshot3* = Major cities in the USA  
*Screenshot4* = Final results (best cities according to user entered parameters) after computing the function  

4. **How it works:**  
The function takes as inputs, the distances from nuclear  
![Nuclear Hazard](https://github.com/Thomas-C-EPF/EPF-RUDN-USCityChoice-test/blob/master/Screenshot0.png)   
, coal, and gas power plants ![Nuclear and Pollution high risks areas](https://github.com/Thomas-C-EPF/EPF-RUDN-USCityChoice-test/blob/master/Screenshot1.png) as well as your   choice in terms of minimum population and the vacancy rate of your dream city.  
It then creates buffers related to your distances inputs  
![Major US cities](https://github.com/Thomas-C-EPF/EPF-RUDN-USCityChoice-test/blob/master/Screenshot2.png)  
and substract all cities  
![Image description](https://github.com/Thomas-C-EPF/EPF-RUDN-USCityChoice-test/blob/master/Screenshot3.png)  
that are located inside the "high risks" area. Moreover, user entered conditions helps to get a more relevant city choice and finally sorts the remaining cities  
![Last cities remaining](https://github.com/Thomas-C-EPF/EPF-RUDN-USCityChoice-test/blob/master/Screenshot4.png)   
in the desired order (user   entered order as well).  
The *flowchart* is also available to provide other information. 
![Project Flowchart](https://github.com/Thomas-C-EPF/EPF-RUDN-USCityChoice-test/blob/master/flowchart.png)

5. **How to use:**  
*First:* Create a folder named "Thomas_Calvet_City_Choice"  
*Second:* Put all downloaded files into the folder "Thomas_Calvet_City_Choice"  
*Third:* Place the folder "Thomas_Calvet_City_Choice" in your Local Disk (C:)  
*Fourth:* Open Jupyter Notebook via the ArcGIS panel  
*Fifth:* Select "CityChoice_Thomas_Calvet.ipynb" and open it  
*Sixth:* Enter the desired values and run the function  

6. **Function:**  
CityChoice("C:/Thomas_Calvet_City_Choice/City_Choice_In_Python/City_Choice_In_Python.gdb",  
"USA_NPP", "A miles",  
(Nuclear Power Plants Layer ~ Feel free to enter the A value you want (=distance from NPP))  
"USA_NTS", "B miles",  
(Nuclear Tests Sites Layer ~ Feel free to enter the B value you want ( =distance from NTS))  
"USA_GPP", "C miles",  
(Gas Power Plants Layer ~ Feel free to enter the C value you want (=distance from GPP))  
"USA_CPP", "D miles",  
(Coal Power Plants Layer ~ Feel free to enter the D value you want (=distance from CPP))  
E, F,  
(Enter the minimum population of your dream city (E), Enter the number of empty houses you want to have in your new city (F))  
"FIELD", "METHOD"  
(Sort your cities by FIELD = "POPULATION" or "VACANT", Select your sort METHOD = "ASCENDING" or "DESCENDING")  

7. **Other:**  
If you are running into trouble or having question, feel free to contact me whatever the subject is.  

*Thomas Calvet*
