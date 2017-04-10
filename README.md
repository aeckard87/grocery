# grocery
App that compiles your grocery list based off chosen recipes from your weekly meal plan

[![Dependancy Status](https://david-dm.org/aeckard87/grocery.svg)][https://david-dm.org/aeckard87/grocery]

## Goals ##

#### Ingredients
- [ ] Add an ingredient to a master list
- [ ] Edit Ingredient
- [ ] Delete Ingredient
- [ ] Add ingredient to a food type/group
  - Eample: Ingredient Thyme is a type of Spice
- [ ] Edit Ingredient food type/group
- [ ] Allow an ingredient to have multiple types/groups
#### Recipes
- [ ] Add a Recipe
  - recipe qualifies if the following are met:
    - Name
    - Ingredients /qty (what do you do if the recipe is the ingredient, like an Apple for snack time?
  - Other fields may be added to a recipe:
    - Prep/Cook time
    - Directions
    - Who's kitchen was this from?
- [ ] Edit Recipe
- [ ] Delete Recipe
#### Meals
- [ ] Add many or one Recipe(s) to make a meal
- [ ] Edit/Delete Meals
- [ ] Assign a Meal or Recipe to a day(s) -> the meal plan
#### Grocery List
- [ ] Populate a grocery list based off the meal plan, with qty's needed
  - should the list be dynamically updated when there is a change to the meal plan?


### Things to think about
- [ ] Socializing the app. 
  - Case: You have an event to cook for but you're not sure what you should make based on known attendies preferances or allergies.
  - Solution? Setup simple profile of guests preferances and allergies. Select which people will be attending the event and cross referance it to the dishes you'd like to consider for the event. It will populate suggestions based on the two.
 - [ ] Collaborate with recipe websites to cumulate a common recipe.
   - Case: You would like the commonly accepted recipe version for spaghetti. 
   - Solution? Sweep through a recipe website to search for "spaghetti" using a phonetic algorithim, then collect ingredients and sort through the most commonly found to produce the "Common _spaghetti_ Recipe". 
