# Admissions Challenge - Making cookies

For this project you will be incorporating your JavaScript skills along with jQuery in order to build out a cookie baking app. Start by cloning this repository and reading through the pre-existing code - we've built out the HTML for you.

---

## Step 1

All of your code will go inside of the document ready function. Here's the functionality you need to build out:

1. When someone clicks on Use 1 Sugar, decrement 1 from the sugar in ingredients, and increment 1 from the sugar count in the pot
2. Replicate the same for flour
3. When someone clicks Cook a Cookie, deplete 6 units of flour and 3 units of sugar. Add 1 cookie as well.
4. When you click on buy Sugar, add 1 unit of sugar for $10.
5. 1 unit of flour costs $20
6. Make sure you spend time cleaning up your code. Keeping your code flexible and DRY is very important. This is your chance to showcase your ability to write excellent code.

---

## Step 2

Right now, anyone can just jump into the developer console for the HTML page and change how many cookies are available. This is unacceptable! We cannot have people counterfeiting cookies! Instead of keeping track of cookies inside of the HTML, we want to keep track of cookies inside of our JavaScript code - the HTML code will simply reflect what the JavaScript says.

For example, you will keep track of an object called `ingredients` which will have properties for how many ingredients we have:

```javascript
var ingredients = {
  sugar: 10,
  flour: 5
};

var pot = {
  sugar: 2,
  flour: 1
};
```

This object will hold the "truth" about how much sugar you have, and anytime you update this object, you will want to also update the HTML page regarding how much you have.

---

## Algorithms Challenge

Along with this challenge. Submit a solution to the following challenge:

Given an array of integers, find the smallest difference between any two elements of the array. For example:

```
var findSmallestDifference = function(arr) {
  // Your code goes here
};
var result = findSmallestDifference([100, 500, 300, 1000, -200, 990]);
console.log(result); // The answer is 10 for this particular example
```

This code should print out 10 because the different between 1000 and 990 is 10 and there are no pairs that have a smaller difference.
