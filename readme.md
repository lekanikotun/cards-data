# Interview Questions

## Data Filter Exercise
* Clone this repo
* In index.js, using the fs module, create a function called `readCardsData` that asynchronously reads the `cardsdata.json` file.
* Create a function called `cardsFilter` that:
  1. calls the `readCardsData` function
  2. reduces the number of attributes per item to only what's in the  `requiredFields` array
* Create a node server and expose a route that returns the result of the `cardsFilter` method
