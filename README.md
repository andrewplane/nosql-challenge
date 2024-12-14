# Module 12 Challenge: noSQL Eat Safe, Love

This project is an introduction to noSQL databases, specifically mongoDB. The data looks at food establishments in the UK. 

## Acknowledgements

 - This project was created as part of the EdX Data Analytics Bootcamp.
 - File structure and data is provided by EdX.
 - The language model AI Xpert was used for troubleshooting during the project.

## Authors

Andrew Lane, 2024
- [@andrewplane](https://github.com/andrewplane)

## Highlights - Setup

-Add the restaurant Penang Flavours to the database:
-The BusinessTypeID for Restaurant/Cafe/Canteen is: 1
-The BusinessTypeID for Penang Flavours has been updated to '1'
-All establishments in Dover have been removed from the database
-All latitude and longitudinal coordinates have been changed from strings to decimals
-All RatingValue entries have been changed to an integer unless they contain a text note.

## Highlights - Analysis

-Number of establishments with a hygiene score of 20 (0 is best, higher numbers are worse): 41
-Number of establishments with London as the Local Authority and a RatingValue >= 4: 33
-The top 5 establishments close to Penang Flavours with a Hygiene score of 0:
![alt text](Resources/image.png)
