# 301-practice-2
In a Handlebars template, what does {{city}} refer to?
{{}}  Handlebars expression  to include the value of variable (city) to add it to DOM


Explain how the following code in a Node-express server is triggered to run, and what it's output is

server.get('/list', (request, response) => {
   let animals = ['Cat','Dog','Sheep'];
   response.send(200).json(animals);
});
solution:
 server.get('/list', (request, response) => {
   let animals = ['Cat','Dog','Sheep'];
   response.status(200).json(animals);
});




Write a Constructor function that can create an instance of a person, with a name and an age, given 2 arguments
function Person(name,age)   {
    this.name=name;
    this.age=age;
}