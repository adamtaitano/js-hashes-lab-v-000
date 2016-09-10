# Recipe Maker

## Objectives

+ Create an object
+ Add key-value pairs to an object
+ Replace values in an object
+ Delete key-value pairs in an object


## Instructions

+ Create a function `addIngredient` that accepts three arguments: a recipe object, an ingredient name (a key in the object) and the amounts (the value of the ingredient key). The body of the function should add the key-value pair to the recipe object, and then return the updated object.

You'll want to be able to use the function like this:
```js
var tacoIngredients = {tortillas: "1 dozen, small"}
addIngredient(tacoIngredients, "cheese", "a lot")
tacoIngredients //=> {tortillas: "1 dozen, small", cheese: "a lot"}
```

+ Create a function `removeIngredient` which accepts two parameters, the recipe you would like to remove an ingredient from, and the ingredient you would like to remove. The function should return the updated recipe.

+ Create a function `updateIngredient` which accepts three parameters: the recipe, the ingredient you'd like to update, and the amount of that ingredient. The function should update the hash and return the updated hash.

+ Create a function `readRecipe` which accepts a recipe object as a parameter. The function should `console.log` a string of each ingredient and the amount `"this recipe calls for <amount> of <ingredient>"`

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/js-hashes-lab' title='Recipe Maker'>Recipe Maker</a> on Learn.co and start learning to code for free.</p>

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/js-hashes-lab'>Hashes in JS Lab</a> on Learn.co and start learning to code for free.</p>
