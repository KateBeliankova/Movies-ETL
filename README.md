## Movies-ETL
Created function uses three file names as a String for wikipedia, kaggle, and ratings data files as input arguments. The following assumptions have been made in the function that can be caught by using try-except blocks.

Block IOError:
1. provided file name/ path for wikipedia json data file in input argument is correct
2. provided file name/ path for kaggle csv data file in input argument is correct
3. provided file name/ path for ratings csv data file in input argument is correct

Block ValueError:

4. pgAdmin4 database table with the provided name does not already exist 

Other assumptions not covered in the function:

5. pgAdmin4 database connection exists 

6. provided IP address of the pgAdmin4 server is correct 
