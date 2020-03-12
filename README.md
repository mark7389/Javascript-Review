## Javascript Essentials:

### Topics:
- Datatypes: basics
  - String
  - Number
  - Boolean
  - Array
  - Object
- variables
- Loops
- Functions
- If done with everything we can talk about DOM events at a highlevel for next class

### Datatypes / Variable Declaration warmup

- declare a variable of type string
- common string methods/properties
    - `includes()`
    - `charAt()`
    - `substring()`
    - `indexOf()`
    - `trim()`
    - `length`
    - `split()`
- declare an array
- common array methods/properties
  - `length`
  - `indexOf()`
  - `join()`
  - `forEach()`
  - `length`

source [MDN](developer.mozilla.org)

### loops

## For Loop
- syntax
```javascript
  for (var index = 0; index < value; index++) {
    // as long as index is less than value I will execute the code here
  }
```

## while loop
- syntax

```javascript
  var text = ""
  var i = 0
  while(i < 5) {
    text += i + ", "
    i++
  }

  while(condition) {
    // as long as condition is true I will execute code in here
  }
```

## do while loop

```javascript
  var text = "";
  var i = 0;
  do {
    text += "The number is " + i;
    i++;
  }
  while (i < 5);

  do {
    // as long as the condition below is true I will execute code here

  }
  while (condition)
```

### Activities:
---
```javascript
var fruits = ["banana", "pear", "apple", "cherry", "peach"]
//print apple

var favFoods = {
  vegetable: "brussel sprouts",
  meat: "tofu",
  fruit: "peach",
  legume: "peanut",
  grain: "millet"
}

//print peanut
```
---
```javascript
var groceryList = {
    produce: {
        fruits: ["bananas", "cherries", "blueberries"],
        vegetables: ["turnip", "carrot", "spinach"]
    },
    desserts: ["ice cream", "brownie"]
}

//print brownie
//print cherries
```
---

```javascript
var metals = ["copper", "silver", "tin", "gold", "steel", "aluminum", "iron"]

/* print the following:
    copper
    tin
    steel
    iron
*/
```
---
```javascript
var nums = [2,4,6,8,10]

//use a loop to increment each element by 1

//use a loop to print each element in the updated array

/* Output should be:
    3
    5
    7
    9
    11
*/

// when done use one loop to do both
```
---
```javascript
// Using the code provided and conditionals, print "High" if the provided number is over 10, "Low" if the number is under 10, and "Perfect" if the number is exactly 10.

var num = 7

//add your conditional here
```
---

Functions:

syntax:

```javascript
  //no parameters
  function function_name () {
    // function code
    return
  }

  //with parameters
  function function_name (x, y) {
    // have acces to x,y here
    return x + y
  }


  //to invoke or call a function
  function_name()

  //with arguments
  function_name(3,4)
  // 3,4 here are the parameter values (arguments) which will be the values of x,y above
```

Function Exercises: (we might not finish all of them but recommended to go over them on your own)

```javascript
  // 1- write a function that takes a string parameter and returns the string reversed HINT: need loop - temp variables
  // 2- write a function that takes two similar objects and returns true if the second key's value of object 1 is equal to second key's value of object 2
  // 3- write a function the takes an array of sorted numbers and returns the max and minmum values as an object



```
