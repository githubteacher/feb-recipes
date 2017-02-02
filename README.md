# Recipes

A place to render family recipes: https://githubteacher.github.io/feb-recipes/

## Contributing Instructions

### Fork and Pull
1. Fork the repository
1. Clone the repository to your local machine using `git clone`
1. Checkout the `development` branch using `git checkout development`
1. Create a new branch called `HANDLE-recipe` using `git checkout -b HANDLE-recipe`
1. Navigate to the `_/posts` folder
1. Create a new file with the following naming convention: `dd-mm-yyyy-name.md`, where name is the recipe
1. Copy the template content (found below) to create your content.
1. Create your recipe.
1. Create a commit with your new recipe using the following commands: (`add`, `commit -m "message"`, and `push`)
   - You will need to set your upstream since this is a local branch with no tracking branch on your remote so use `git push -u origin HANDLE-recipe`
1. Create a Pull Request using the base fork: `githubteacher/feb-recipes` and the `development` branch.

### Collaborator
1. Clone the repository to your local machine using `git clone`
1. Checkout the `development` branch using `git checkout development`
1. Create a new branch called `HANDLE-recipe` using `git checkout -b HANDLE-recipe`
1. Navigate to the `_/posts` folder
1. Create a new file with the following naming convention: `dd-mm-yyyy-name.md`, where name is the recipe
1. Copy the template content (found below) to create your content.
1. Create your recipe.
1. Create a commit with your new recipe using the following commands: (`add`, `commit -m "message"`, and `push`)
   - You will need to set your upstream since this is a local branch with no tracking branch on your remote so use `git push -u origin HANDLE-recipe`
1. Create a Pull Request using the base: `development` branch and the compare: `HANDLE-recipe`.

## Template
```
---
layout: post
title:  "RECIPE TITLE"
date:   yyyy-mm-dd 
categories: main
---

![food](IMAGE LINK)

## Ingredients
- Ingredient
- Ingredient


## Directions

1. step 1
1. step 2
1. step 3
```
