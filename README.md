# Admissions Challenge 2 of 2 - Making Cookies

For this project you will be incorporating your JavaScript skills along with jQuery in order to build out a cookie baking app. Start by cloning this repository and reading through the pre-existing code - we've built out the HTML for you.

If you're not comfortable with jQuery just yet, check out [CodeCademy](http://www.codecademy.com/tracks/jquery) or [Code school](https://www.codeschool.com/courses/try-jquery).

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

For example you can keep track of an object called `inventory` which keeps track of how much money you have, how many cookies you have, etc:

```javascript
var inventory = {
  product: {
    money: 1000,
    cookies: 0
  },
  ingredients: {
    sugar: 10,
    flour: 10
  },
  pot: {
    sugar: 0,
    flour: 0
  }
};
```

This object will hold the "truth" about what you actually have, and anytime you update this object, you will want to also update the HTML page regarding how much you have.

---

## Algorithms Challenge

Along with this challenge. Submit a solution to the following challenge:

Given an array of integers, find the smallest difference between any two elements of the array. For example:

```javascript
var findSmallestDifference = function(arr) {
  // Your code goes here
};
var result = findSmallestDifference([100, 500, 300, 1000, -200, 990]);
console.log(result); // The answer is 10 for this particular example because the difference between 1000 and 990 is 10
```

This code should print out 10 because the different between 1000 and 990 is 10 and there are no pairs that have a smaller difference.
