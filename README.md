# Description

Do you have ingredients to use up but not sure what else to combine them with to cook a tasty meal? Are you looking for ways to spice up and enhance a dish? food-suggest can help solve that problem! Simply input the ingredients you want to use and food-suggest will recommend other ingredients that go well with your list. The rest is up to your imagination! By design, food-suggest does not provide recipe instructions in order to allow your culinary brain room to practice being creative!

## Technical details

- food-suggest currently runs on a Recurrent Neural Network (RNN) architecture.
- Recipe database obtained from https://eightportions.com/datasets/Recipes/ (~125,000 recipes)
- Current tokenizer was scraped from all letters of https://git.macropus.org/bbc-food/www.bbc.co.uk/food/ingredients/by/letter/a.html
