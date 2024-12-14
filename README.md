# Odin Recipes Project
As I'm learning about web development, I discovered how to create a simple recipe website using HTML. I'll walk you through the process of building this project, which I'm excited to share with you.

## Introduction
I recently started exploring HTML and CSS, and I wanted to apply my newfound skills to create a recipe website. This project allowed me to practice referencing other pages in HTML, creating separate directories for different types of content, and structuring a website with proper headings and lists.

## Getting Started
To begin this project, I created an odin-recipes directory and started with an index.html file. I learned how to add basic HTML boilerplate and create an h1 heading with the title "Odin Recipes" in the body.

## Adding Recipe Pages
Next, I created a new directory called recipes within the odin-recipes folder. Inside this directory, I made individual HTML files for each recipe, naming them after the dishes they contained. For example, I created a lasagna.html file.

I discovered that I should include the standard HTML boilerplate in every file I create. This boilerplate code is crucial for proper webpage structure. I also learned how to add an h1 heading with the recipe's name as its content.

## Linking Recipes
Back in the index.html file, I practiced linking to the recipe pages I created. I added a link under the main heading like this:

```html
<a href="recipes/recipename.html">Recipe Title</a>
```
I found that the text of the link should match the recipe name for better readability.

## Filling Out Recipe Pages
On each recipe page, I learned how to add the following content:

* An image of the finished dish under the h1 heading
* A "Description" heading followed by a paragraph or two describing the recipe
* An "Ingredients" heading with an unordered list of ingredients needed
* A "Steps" heading with an ordered list of the steps to make the dish

I discovered that organizing the content this way helps users quickly find the information they need.

## Expanding the Recipe Collection
I continued to expand my recipe collection by adding two more recipes with the same structure. I also learned how to organize the links on the index page using an unordered list:

```html
<ul>
  <li><a href="recipes/yourrecipe.html">Recipe Title 1</a></li>
  <li><a href="recipes/yourrecipe.html">Recipe Title 2</a></li>
  <li><a href="recipes/yourrecipe.html">Recipe Title 3</a></li>
</ul>
```
This approach keeps the links tidy and easy to read.

## Conclusion
As I worked on this project, I gained hands-on experience with HTML structure, linking between pages, and organizing content. These skills are fundamental to web development, and I'm excited to continue learning and applying them in future projects.

