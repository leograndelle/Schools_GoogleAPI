# Schools_GoogleAPI

Using Google's Places API to search for schools in a certain area. It generates a .xlsx file and a interactive map showing the selected area.

Since the maximum number of elements retrieved by query is 60, the code works by searching multiple smaller radiuses within the bigger one specified by the user to ensure it doesn´t miss any school due to the given limit. 
