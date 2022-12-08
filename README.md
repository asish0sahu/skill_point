# Making API Call with Hooks | Part 2

- Avoiding Unnecessary API Calls
  - Using Dependency Array
- Handling API Response
  - Updating Object in State using Spread operator
  The Object provided to the setter function will replace the current state object
The newly created object may not contain all the keys and values

While updating the state, use callback function and spread operator to get all the key values from the current state object
  
While making an API call, we need to display different views like Loading View, Success View, and Failure View

For displaying these views, we need to maintain the following values in the state

Status
Data
Error Message
We use a single state variable with an object as an initial value to store these values as they tend to change together


![lk](https://user-images.githubusercontent.com/111269058/206361759-e0024510-ddf4-4902-b3f7-4394352235b8.png)
