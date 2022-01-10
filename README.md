# ETL-Project_15

## Extracting json data from API
* We have extracted json data from NASA NEOWS API. 
## Data Transformation
* We used a Pandas functions in Jupyter Notebook to transform API request responses into dataframes.
* We used a python transformation functions for data cleaning,filtering.
* Duplicate rows was removed, and successfully managed.
## Loading into Database
* We created database called "asteroids" using psycopg2 library. Created 4 tables and loaded the values into table.

## Close Approach Dataset
NASA's Center for Near-Earth Object Studies (CNEOS) also provides data about close approaches of NEOs to Earth. A close approach occurs when an NEO's orbit path brings it near Earth - although, "near" in astronomical terms can be quite far in human-scale units, such as kilometers. Instead of kilometers, astronomical distances within the solar system are often measured with the astronomical unit (au) - the mean distance between the Earth and the sun - although sometimes you'll see distances measured with the lunar distance (ld) - the mean distance between the Earth and the moon - or even plain old kilometers.

From this dataset, we answered few questions such as "How many came asteroids approched each month?" , "How fast does an asteroid pass by Earth, on average?"
"Is marked by NASA as potentially hazardous (or not)", "How many close approaches are in json data set?"


## Tables from PostgreSQL

#### asteroid details table
![](t1.png)
#### asteroid_size table
![](t2.png)
#### asteroid_speed table
![](t3.png)
#### hazardous_asteroid table
![](t4.png)
