# Interview Questions

## Data Filter Exercise
* Clone repo
* In index.js, using the fs module, create a function called readCardsData that asynchronously reads the cardsdata.json file.
* Next, create a function called cardsFilter that:
1. calls the readCardsData function
2. reduces the number of attributes per item to only what's in the requiredFields array
* Create a node server and expose a route that returns the result of the cardsFilter method
* BONUS:  Modify the route to read a query parameter from the route to limit the number of objects returned by the function.
* Write unit tests using a framework of your choice to cover the cardsData function.
