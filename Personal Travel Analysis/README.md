# Personal Travel Analysis

This projects uses my own dataset to identify recurring patterns in my behavior and favorite destinations. I have collected data from 2016 until today about all my travels. by gaining more insights, I'll be able to better schedule and plan my next travel. I also wanted to work on my story telling skills. 

For this project, the dataset is stored in my personal Google Sheet therefore it's not included. If you want to build something similar, find below the dataset original structure so that you can directly build the dataset and see the results. 

#### Columns with data types

 - Start Date <DATE> NOT NULL
 - End Date <DATE> NOT NULL
 - Continent <TEXT> NOT NULL
 - Country <TEXT> NOT NULL
 - Region <TEXT> NOT NULL
 - City <TEXT> NOT NULL
 - Type <TEXT in [Alone, Family, Friends]> NOT NULL
 - Transportation <TEXT> NOT NULL
 - Nb Travellers <INT> NOT NULL
 - Home Town <TEXT> NOT NULL 
 - Coordinates <DECIMAL, DECIMAL> NULL

  

#### Example

| Start Date | End Date | Continent | Country | Region | City | Type | Transportation | Nb Travellers | Home Town | Coordinates |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| 2022-12-20 | 2022-12-28 | Oceania | New-Zealand | North Island | Wellington | Alone | Plane | 1 | Tokyo | -41.276825, 174.777969 |
  
  
*NOTE: In Power BI, if you are using the map visual you might need to adjust the Country name in order to match Power BI. For example you need to replace Scotland or England by United-Kingdom.*

