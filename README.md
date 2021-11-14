# Movies ETL

## Project Overview
Amazing Prime video wants to predict which movie releases will be popular, before they become popular. Without any fortune-telling abilities, we will rely on analyses of past movie releases to help predict what types of movies will become popular. 

In order to stay up-to-date with the newest releases, we can create an automated pipeline that takes in new data on a daily basis, and loads the data into existing tables. That way, we don't need to wait for someone to manually import new releases, and we can be sure to see the data of a new movie as early as possible. 

This project involves pulling data from three separate files, performing the Extract, Transform, and Load process on each, and then adding that data to a PostgreSQL database (in this case, pgAdmin). 