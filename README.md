# StudetnSpaceDatabase
# **Access to Database**


Database is running inside Digital Ocean


**Port**: 5401


**Host**: 137.184.112.153


**User**: postgres by default


**Database_name**: postgres by default


**Password**: posterdata


Make sure that the psql library is installed correctly in your machine.


Once your machine has psql library installed, run this command below inside terminal to initialize the project:


**psql -h 137.184.112.153 -p 5401 -U postgres -d postgres**


**Password**: posterdata

You will see **postgres=#**  it means that you entered our database. Then you need to do **\l** (slash lowercase L)  this will show a list of databases. In there you will see a database


called user. We choose the user database with the help of cmd : **/c** user. Then if we do **\dt** it will show all relations inside the database. 


**#ERD**




![Screen Shot 2023-05-12 at 1 47 05 AM](https://github.com/Abdugafur111/StudentSpace/assets/64993553/8c51742b-7308-4cfb-96fa-4a0b2af75b9c)

