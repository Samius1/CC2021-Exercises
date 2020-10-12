# Exercise 1. Search for an example application, preferable of your own, and figure out what patterns it uses. What would it take to evolve into a microservices pattern?
This application, [Área Binaria web page](https://www.areabinaria.com/), is using the multitier pattern. When I was working in this company, I helped them to update this page from time to time.  
It would need to change the core to adapt it to a microservices pattern, since it is just connecting to database to retrieve information and resolving URLs. 
Basically, it will need to refractor the code into different microservices.  
The first step could be to create a REST API to manage the calls to the different microservices. From that point on, we would need to create the REST API to every microservice and the microservices themselves.

# Exercise 2. In the previously selected application, could it be develop with different languages? Wich data stores would be the most convenient?
Yes, it could be develop using Java or C#, for example. We would just need to swap and adapt the actual php code for the language that we want to use.  
Right now, it uses old SQL database engine. I think that they could use NoSQL databases, since it will need to store data from different types in a non structured way. 
I would use a data mart for most of the microservices since it is only showing information, for example.


