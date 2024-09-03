# Odin Recipes

This is a basic recipe website created as part of the [Odin Project](https://www.theodinproject.com/) web development course. The goal of this project is to practice and demonstrate fundamental HTML skills by building a simple, structured website.

## Project Overview

The website consists of a main index page that links to a few individual recipe pages. Each recipe page contains the name of the dish, an image, a description, a list of ingredients, and the steps to prepare the dish.

This project is focused on building the HTML structure. In future iterations, we will revisit the website to style it using CSS.

## Iterations

### Iteration 1: Initial Structure

-   Create the main `index.html` file within the `odin-recipes` directory.
-   Add the standard HTML boilerplate.
-   Include an `<h1>` heading with the text "Odin Recipes" in the body.

### Iteration 2: Recipe Page

-   Inside the `odin-recipes` directory, create a new directory named `recipes`.
-   Create a new HTML file in the `recipes` directory named after the dish (e.g., `lasagna.html`).
-   Add an `<h1>` heading with the name of the recipe.
-   In the `index.html` file, add a link to the new recipe page under the `<h1>Odin Recipes</h1>` heading.

### Iteration 3: Recipe Page Content

-   In each recipe page:
    -   Add an image of the finished dish below the `<h1>` heading.
    -   Include a "Description" section with a paragraph or two describing the dish.
    -   Add an "Ingredients" section with an unordered list of ingredients.
    -   Add a "Steps" section with an ordered list detailing the steps to prepare the dish.

### Iteration 4: Add More Recipes

-   Create two additional recipe pages with the same structure.
-   Link these new recipe pages on the `index.html` page.
-   Consider listing all the recipe links in an unordered list for better organization.

## How to View the Website

1.  **Clone the Repository**:
    
    bash
    
    Copy code

    `git clone https://github.com/at-tawlib/odin-recipes.git
    cd odin-recipes` 
    
2.  **Open `index.html`**:
    
    -   Open the `index.html` file in your web browser to view the main page with links to all the recipes.

## Future Enhancements

This project will be revisited to add styling using CSS, improving the visual design and layout of the website.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
