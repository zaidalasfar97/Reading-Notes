# Array.map():
###### The map() method creates a new array populated with the results of calling a provided function on every element in the calling array.

# Array.reduce():
###### The reduce() method executes a reducer function (that you provide) on each element of the array, resulting in single output value.

# Superagent :
### Promise .then() syntax:
###### function getData(){
###### superagent.get(url)
###### .then(result =>{
######    console.log(result.body)
###### })
###### }


### async / await syntax:
###### async function newData(){
###### let result = await superagent.get(url);
######    console.log(result);
###### }


# The Promise object represents the eventual completion (or failure) of an asynchronous operation and its resulting value.

# A Promise is a proxy for a value not necessarily known when the promise is created. It allows you to associate handlers with an asynchronous action's eventual success value or failure reason. This lets asynchronous methods return values like synchronous methods: instead of immediately returning the final value, the asynchronous method returns a promise to supply the value at some point in the future.


# Are all callback functions considered to be Asynchronous? Why or Why Not? 
##### Simply taking a callback doesn't make a function asynchronous. There are many examples of functions that take a function argument but are not asynchronous. For example there's forEach in Array. It iterates over each item and calls the function once per item.
