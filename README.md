# pandas_challenge #

## PyCitySchools ##

This project looks at how different factors affect the the fictional standardized test scores of students within the PyCity school district. The program runs sequentially, first summarizes the district as a whole and the schools within the district respectively, then pulls from those tables to examine specific factors affect on scores. These factors include: year in school, schools spending per student, school size, and the type of school.
    
The application works with *pandas* to take the data provided in two csv files and manipulates the data to create a merged table to give us an overview the district and the schools in a grouped format. The information from the latter table is then sorted to present the top performing schools followed by the bottom performing schools. It is from here that the possible factors influencing scores are examined beginning with year in school and ending with school type. Multiple methods are utilized throughout this program to gather the information requested to examine the different factors such as groupby and binning.
