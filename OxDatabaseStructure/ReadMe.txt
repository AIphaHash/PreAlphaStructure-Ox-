this ReadMe expline the png in this file , which is about the database that will be attached to the OxformsStructure
------------------------------------------------------------------------------------------------------------------
*this database is editable it is not the last version it is pre alpha 
------------------------------------------
1-EMPLOEY LOGIN : with this table its job is just to save emploey ids and passwrods and some other info about the
emploey , it used to give privilages to the emploey to what they can do or even if they are meant to get access to
the app

2-HC INFO : if has all the info about the HCs that is saved in the database that can be used almost everywhere 
and it also have the (Acitve or NotActive) which it come handy in alot of places

3-STORAGES : it have the {PK from the HC INFO table} which means all HCs have storages that have a size that tell
if it is empty or full also the location of that storage 

4-MEDIC : it have a {FK from the STORAGES table} which tells where this certin medic is located , it also
have alot of info that can be used in alot of places for example the exDate for a certin medic can be used to 
know how much days left for this medic and also the quantity of it , and the cost price and the sell price of it
.
.
.
.
.
.
.
.
.