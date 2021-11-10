# Project task 1 - Python and R LAB 

#### Master of Science in Data Science and Management 

### Art Institute of Chicago API

----

>For first the task, we decided to work with the API provided by the Art Institute of Chicago. 
The documentation for the API can be accessed at the following link: [Documentation | Art Institute of Chicago API](https://api.artic.edu/docs/). The API provides JSON-formatted data as a REST-style and it is a collector of all the possible information regarding the physical and virtual collection and information of the Art Institute.For the project we decided to work with the artworks' collection data. The collection is composed by 115506 objects and each artworks has 93 variables associated. We decided to retrieve 1100 artworks. 
A detailed documentation of the script can be found in the file "Task_1.pdf".
----
### The API
For the project we decided to work with the artworks' collection data. The collection is composed by 115506 objects and each artworks has 93 variables associated. We decided to retrieve 1100 artworks. In order to do so, we used the main endpoint /artworks, resulting in the following API: https://api.artic.edu/api/v1/artworks.  


----
### The dataset
The resulting dataset is provided in a .csv format. You can find the dataset under the name 'art1000.csv'.The resulting csv file is a dataset of 1100 x 93 where the rows represent the single artworks (1100) and the columns represent the variables (93) as retrieved from the API. The meaning of the variables and their type can be found at the following link: https://api.artic.edu/docs/#collections-2.
We would suggest to carefully inspect the dataset and the documentation before carrying out any analyses, considering the elevated number of Not Available data, which we tried to pre-clean by filling it with a 0 value.
