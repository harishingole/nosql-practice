# nosql-practice
Training Deqode
#Day 1
Configuration of below technical is done<br />
git<br />
docker<br />
sts<br />
postman<br />
maven<br />
java (jdk 1.8)<br />
mongodb<br />

#NoSql <br />
Understands the differences of sql and nosql<br />
get the brief knowledge of caps theorem<br />
understanding of architecture of mongodb and features<br />
Understanding of MOngodb and mongodb compass<br />

Perform crud operation like create db , read , update and delete<br />
Insert into db for e.g<br />

#To insert one record<br />
db.RecordsDB.insertOne({<br />
    name: "Marsh",<br />
    age: "6 years",<br />
    species: "Dog",<br />
    ownerAddress: "380 W. Fir Ave",<br />
    chipped: true<br />
})<br />


#Day 4

 show dbs<br />
admin   0.000GB<br />
config  0.000GB<br />
local   0.000GB<br />
> use demoDatabase;<br />
switched to db demoDatabase<br />
> show dbs<br />
admin   0.000GB<br />
config  0.000GB<br />
local   0.000GB<br />
> db.createCollection("contacts");<br />
{ "ok" : 1 }<br />
> show dbs<br />
admin         0.000GB<br />
config        0.000GB<br />
demoDatabase  0.000GB<br />
local         0.000GB<br />
> db.dropDatabase();<br />
{ "ok" : 1 }<br />
> show dbs<br />
admin   0.000GB<br />
config  0.000GB<br />
local   0.000GB<br />
> <br />

