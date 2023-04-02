# Week 4 — Postgres and RDS
I was working few weeks on Week4 tasks. I stuck on creating activities with database insert - making CRUD posting. I was getting many errors - first about connection failed - I understood that I was not able to connect to my RDS db in prod mood - I checked the environmental variable for Connection URl and fins what I was missing. The next few errors were about user handle, for now I hardcoded the user_handle as username. And another error was AttributeError: 'Db' object has no attribute 'query_wrap_object'  - turns out I was missing ccorrect indentation for the last two functions and they were out of the object. After fixing that I finally was able to get CruDs posted.
#### CRUD posting is working
![CRUD_POSTING](assets/Crud%20posting%20activity%20-%20Weeek4.png)


#### Ensuring DB has activities filled
![Activities-DB](assets/activity%20DB%20data%20-%20Week4.png)

#### Creating DB
![Creating-DB](assets/Create-db-week4.png)

#### Establishing connefction to local DB
![Connection-localDB](assets/connection-to-local-db-week4.png)

#### Getting User data in db 
![user_data](assets/db-user-data-week4.png)

![user-data-db2](assets/db-user-data1-week4.png)


![db](assets/db-week4.png)


![list of DB](assets/list-of%20db-week4.png)


![seed data](assets/seed-data-week4.png)


