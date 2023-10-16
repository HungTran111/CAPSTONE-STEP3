<!-- 
API: ('https://api.edamam.com/search?q=${searchValue}&app_id=8be19060&app_key=229ab3365ee8d660b03ce476d4920033&from=0&to=10') 
app_id=8be19060
app_key=229ab3365ee8d660b03ce476d4920033&from=0&to=10
 
 SCHEMA TABLE: https://app.quickdatabasediagrams.com/#/d/cE5YBB

<!-- Table: User
| user_id      | int     | primary key |
| username     | varchar | not null    |
| password     | varchar | not null    |

Table: Recipe
| recipe_id    | int     | primary key |
| title        | varchar | not null    |
| instructions | text    | not null    |

Table: Ingredient
| ingredient_id | int     | primary key |
| name          | varchar | not null    |

Table: UserList
| list_id      | int     | primary key |
| user_id      | int     | foreign key (User.user_id) |
| list_name    | varchar | not null    |

Table: ListIngredient
| list_id      | int     | foreign key (UserList.list_id) |
| ingredient_id | int   | foreign key (Ingredient.ingredient_id) | -->
