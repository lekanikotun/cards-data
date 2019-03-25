# Interview Questions

## Data Filter Exercise
* Clone repo
* Create a simple node server in a file called server.js. 
* In the index.js, file create a function called readJSONData that asynchronously reads the cardsData.json file using the fs module.
* In the index.js file, create a function called cardsFilter that:
** reads the response of the readJSONData function
** returns the same number of elements in the array 
** each element in the array only returns fields in the requiredFields array.
* Export the cardsFilter function
* Import the cardsFilter function in the server.js file
* Create a route called cardsFilter that returns the result of the cardsFilter method.
* BONUS:  Modify the route to read a query parameter from the route to limit the number of objects returned by the function.
* Write unit tests using any framework to cover the cardsData function.
