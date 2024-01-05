![Logo of the recipe project](cake%20(logo).png)

# Recipe API project

The goal of this API is to help users to create, store and select recipe of their wish.

User can:
- Create a recipe;
- Tag their own tags to the recipe;
- Create ingredients and link existing ingredients to the recipe;
- Add image representation to the recipe;
- Filter recipes by Ingredients or/and Tags;
- GET, PUT, PATCH and DELETE Recipe, Tag and Ingredient.
([Click this link to get documentation of API](http://ec2-16-171-6-193.eu-north-1.compute.amazonaws.com/api/docs))   

I covered all code with tests to eliminate 99.9% of bugs, using the TDD approach (tests first, then the code that will pass these tests)

## Technologies used:

- Python 3.9
- Django 4.1
- DjangoRestFramework 3.14
- Docker
- PostgreSQL 13
- Flake8
- Swagger 
- Github Actions

## Deploy

- Uwsgi 2.0.23
- AWS Server
[The project DOCS link](http://ec2-16-171-6-193.eu-north-1.compute.amazonaws.com/api/docs)
