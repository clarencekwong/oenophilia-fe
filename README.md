# Oenophilia

Oenophilia is a simple React web application made for users to find their recommended food and wine pairing. Users are able to select the food type they are currently having, and the web application will recommend some wine varietals for the users. Users can then select that they chose this pairing for their food and write a review if they wish to.

![](https://media.giphy.com/media/lp1ZvMyVRO9bPAvhZl/source.gif)

## Libraries 
- [create-react-app](https://github.com/facebook/create-react-app)
- [Semantic UI React](https://github.com/Semantic-Org/Semantic-UI-React) is used for styling

## Installation

Fork and clone this repository on your local machine. `cd` into oenophilia-fe and run `npm install`. Once completed, run `npm start` to start the application. Be sure to run the back-end first before the front-end. If not you may need to update the link port reference in the code to whichever port the back-end is running on.

## Future Development

+ Implement a review page for all users to see what previous users think about the food-wine pairing.
+ Implement a Wine API to find more wine choices as well as providing a link for user to purchase the wine
+ Implement a persistent login status, and avoid storing user data in the localStorage
+ Implement Redux to clean up state management
