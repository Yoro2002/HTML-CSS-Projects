# Product Preview Card Component

## Overview
This project consists of a single-page HTML and CSS design for a product preview card component. It features a responsive layout that adapts to different screen sizes using media queries.

## Features
- **Responsive Design:** The layout adjusts for both mobile and desktop views.
- **Product Image:** Displays an image of the product using the `<picture>` element.
- **Product Details:** Includes the product category, title, description, pricing, and an 'Add to Cart' button.
- **Styling:** Utilizes CSS custom properties for easy theme management and maintains a clean design with Google Fonts integration.

## Structure
- `<!DOCTYPE html>`: Defines the document type and version of HTML.
- `<html lang="en">`: Sets the language of the document to English.
- `<head>`: Contains meta tags, title, and links to external stylesheets including Font Awesome icons and Google Fonts.
- `<body>`: Encapsulates the main content of the webpage.
  - `<main>`: Serves as the primary container.
    - `<article class="product">`: Represents the product card.
      - `<picture>`: Contains an image representing the product.
      - `<div class="product-content">`: Holds details about the product.

## Styles
- `style.css`: Defines the visual appearance using CSS rules.
  - Custom properties are declared under `:root` for a consistent color scheme and font stack.
  - Flexbox is used for layout alignment and spacing within `.flex-group`.
  - Media query at `1280px` breakpoint alters layout for larger screens.

## Usage
To view the component, open the `index.html` file in a web browser. Ensure that the `style.css` file is located in the same directory as your HTML file.


