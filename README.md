# EPF-RUDN--Health-care-
# Access to health care
**This project developed for the Geospatial Programming class of Spring 2020, an international collaboration between two universities, [EPF](https://www.epf.fr) of France and [RUDN](http://www.rudn.ru) of Russia.**

**I am a student of the engineering school EPF (France) in 4th year (out of 5) in aeronautics and space major.  
This project was supervised by [Naci Dilekli](https://github.com/ndilekli/).**

## Objective :  
**The goal of this project is to find the areas furthest from a densely populated hospital and doctor. This for different age groups and for a region or the whole country. And that in an automatic way with the choices of the user**  

## Code operation : 

This project is realized with the python programming language using the arcpy library.   
The results obtained must be read on the Arcgis Pro software. 

The code works according to the following flowchart: 
![image](https://user-images.githubusercontent.com/64481591/81005731-b1cfcb80-8e4e-11ea-940a-b22402fcec3a.png)  
 
There are 3 criteria:
* The minimum distance from a hospital
* The minimum distance from a doctor 
* Population density 

The user can associate a coefficient to each criterion to signify the importance (or not) of this criterion in front of the others.  

**The result displayed is the following sum:**   

**Coef1**×"The minimum distance from a hospital"+**Coef2**×"The minimum distance from a doctor"+**Coef3**×"Population density"  

And this for each square of the population density (square of 1km by 1km).

The user can also choose an age range of the population being studied or the entire population and can also choose to study only one region of the country or the entire country.  

We may have different results depending on the user's choices:   
![results](https://user-images.githubusercontent.com/64481591/81006151-518d5980-8e4f-11ea-80e1-2468088855ca.png)

## How do I use this program?
* Download files   
* Run the code with an application using python   
* Make your choices when the program asks for them  
* Open Arcgis Pro and display the "Display" field of the opNHFinal.shp layer   
* You can change the symbology to make the map more meaningful   

## Contact :

For any information or problem please contact Guillaume Igersheim by email:  
Guillaume.igersheim@epfedu.fr
