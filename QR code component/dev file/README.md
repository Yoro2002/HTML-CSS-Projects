# QR-Code Component Design

## Overview
This project features a QR-code component design that encourages users to improve their front-end skills by scanning the QR code. It is built with HTML and SCSS and uses Bootstrap for styling.

## Features
- **QR Code Display:** A central mini-container displays the QR code image.
- **Call-to-Action Text:** Encourages users to scan the QR code with a motivational message.
- **Responsive Design:** Utilizes Bootstrap for responsive features.

## Structure
- `<!DOCTYPE html>`: Defines the document type and version of HTML.
- `<html lang="en">`: Sets the language of the document to English.
- `<head>`: Contains meta tags, title, and link to the stylesheet.
- `<body>`: Encapsulates the main content of the webpage.
  - `<div class="container">`: Represents the main container for the QR-code component.

## Styles
- `main.scss`: Defines the visual appearance using SCSS rules which compile to CSS.
  - Bootstrap is imported for responsive grid system and utilities.
  - Custom properties are declared under `:root` for a consistent color scheme.

## External Assets
- **Bootstrap:** The Bootstrap framework can be included via npm or CDN from [Bootstrap](https://getbootstrap.com/).
- **Fonts:** 'Poppins' font can be imported from [Google Fonts](https://fonts.google.com/specimen/Poppins).
- **QR Code Image:** The QR code image used can be sourced from free resources like [QR Code Generator](https://www.qr-code-generator.com/).

