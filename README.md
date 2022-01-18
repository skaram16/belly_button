# Plotly (Belly Button Biodiversity Dashboard)
## Overview of Project
> Roza has a partially completed dashboard that she needs to finish. She has a completed panel for demographic information and now needs to visualize the bacterial data for each volunteer. Specifically, her volunteers should be able to identify the top 10 bacterial species in their belly buttons. That way, if Improbable Beef identifies a species as a candidate to manufacture synthetic beef, Roza's volunteers will be able to identify whether that species is found in their navel.

1. ***Deliverable 1***: Create a Horizontal Bar Chart
2. ***Deliverable 2***: Create a Bubble Chart
3. ***Deliverable 3***: Create a Gauge Chart
4. ***Deliverable 4***: Customize the Dashboard
5. ***Deliverable 5***: A written report on the Belly Button Biodiversity Dashboard analysis [`README.md`](https://github.com/skaram16/belly_button/). 

## Resources and Before Start Notes:

* Data Source: `BellyButton_bar_chart_starter_code.js`, `BellyButton_bubble_chart_starter_code.js`, `BellyButton_bubble_chart_starter_code.js` and `index.html`
* Data Tools: ECMAScript, JavaScript, JSON and IO (Web Server)
* Software: ES6+, ECMAScript and Visual Studio Code 1.50.0

# Functional JavaScript

## The map() Method

The `map()` method in JavaScript applies a transformation to each element in an array. Like a for loop, it can perform an operation to every element of an array.

Here is an example in which all the numbers of an array are doubled:

````java
var numbers = [1,2,3,4,5];
var doubled = numbers.map(function(num){
    return num * 2;
});
console.log(doubled);
````

In this code, an array named `numbers` contains five integers:`var numbers = [1,2,3,4,5];`. Let's break down the rest of the code in more detail:

- The `numbers` array calls the `map()` method.
- Inside the `map()` method, there is another function. This function is anonymous, meaning that the function does not have a name. When `map()` is called, it in turn calls this anonymous function.
- The anonymous function takes a parameter, named `num`, and returns the number multiplied by 2. Its sole task is to perform this single action.
- For every element in the array, the `map()` method calls the anonymous function, which doubles the value of the element.
- The `map()` method returns an array of doubled values, which is assigned the variable `doubled`.

Here, the `map()` function becomes a method of the `numbers` array. It then takes in an anonymous function whose sole task is to double the value of num, its argument.

Behind the scenes, an iterative process similar to a `for` loop takes place. The anonymous function takes in each integer of the `numbers` array and doubles it. Finally, the variable `doubled` is an array of integers whose values are twice their original values.
