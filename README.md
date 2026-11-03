# PrintablePlate Planner food and recipe data

This repository contains a starter set of ingredient and recipe CSV data for PrintablePlate Planner.

## Files

- `ingredients.csv`: 500 ingredient records. Nutrient values are per 100 g and sourced from USDA FoodData Central SR Legacy. `source_reference` contains the USDA FDC food record ID. Blank nutrient cells mean the source record did not provide a value.
- `recipes.csv`: 500 original recipe drafts distributed across Europe, the United States, Latin America and the Caribbean, Asia, and Africa. Recipe nutrition totals are intentionally omitted; they should be calculated from linked ingredient records by the application. Recipes are marked `pending_review` for culinary and dietitian review.
- `recipe_ingredients.csv`: ingredient quantities and links for the recipes.
- `recipe_categories.csv`: recipe category definitions.
- `recipe_category_relationships.csv`: recipe-to-category links.

Dietary and condition tags describe ingredient-based compatibility for planning. They are not medical advice or treatment claims. Review ingredient choices, preparation states, nutrient values, and regional details before using the records for individualized clinical nutrition.
