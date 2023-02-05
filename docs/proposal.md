AdoptAPetFamily
===============

AdoptAPetFamily is about having a dynamic database where a user can  
find and adopt a pet of their choosing. It will have seperate pages  
for each database category of pets, and a contact page where you can  
get the adoption process started.  
  
Web Service  
-----------  
AdoptAPet  
[AdoptAPet](https://www.adoptapet.com/public/apis/pet_list.html)  
Authentification Key is apiKey  
  
The endpoint URL is AdoptAPetFamily and I will use GET and POST methods.  
  
Database Use
------------
I will need these names of the pets, the type of animal they are, breeds if they  
have them, age, and a description of them and their personality. The tables will  
be Names, Animals, Breeds, Age, Description.  

I will need a table for animals, people who have adopted an animal, maybe a table for  toys and food. Animals will be the name of the animals table, Customers will be for  people who have adopted, and Objects maybe will be the name of things that go with an  animal, I will think of a different name. The Customers will have CustomerID primary key that will be used as a foreign key for animals previously adopted. Each animal will have an object/objects they can be connected with by a ObjectID key.  
  
Initial Designs
---------------
![Site Map](../SiteMap.png)  
![Site Sketch](../SiteSketch.png)  
