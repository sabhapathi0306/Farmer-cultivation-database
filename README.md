# Farmer-cultivation-database
cultivation database district wise 
cultivation database is a simple database to track the type of crops and their production are cultivating annualy ,district wise and it also contain types of Soil which are using for cultivation, some of commercial and cereals crops cultivation is particular districts.
This database contain cultivation information of all districts of KARNATAKA and database which is used for this project is SQLite.

It  contain Three table Area,district,Production.

Area table for district list which are present in karnataka
district table contain soiltypes,local crops and total production.
production table contain district name crop by crop production annualy 

steps to create database

step 1)
create Area table which will contain State name,district name and district ID
District_name is primary key and district_ID act as foreign key

step 2)
creat district table which will contain district_ID,soil_type,local_crops and total production
district_ID act as primary key

step 3)
create Production table which will contain district_ID,district_name,Rice_production,maize_production.wheat_production,Ragi_production,Bajra_production,jowar_production,sugarcane_production,cotton_production,tobbaco_production
district_ID and district_name act as foreign key.
.........

Next step Insert data and all data information.
