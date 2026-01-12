
# Lotto Number Generator

## Overview

A simple web application to generate random lottery numbers.

## Features

*   Generate 6 unique random numbers between 1 and 45.
*   Display the generated numbers in a clean, modern interface.
*   A button to trigger the generation of a new set of numbers.

## Application Blueprint

### `index.html`
*   Sets up the basic structure of the page.
*   Includes a title, a heading (`<h1>`), a button (`<button id="generate-btn">`), and a container (`<div id="numbers-container">`) for the results.
*   Links to the `style.css` stylesheet and the `main.js` script.

### `style.css`
*   Provides a visually appealing layout.
*   Centers the content on the page.
*   Styles the "Generate Numbers" button with a green background, hover effects, and a subtle shadow to make it feel interactive.
*   Styles the generated numbers within circular elements (`<div class="number-circle">`) for a classic lottery look.

### `main.js`
*   Contains the core logic for the application.
*   An event listener on the "Generate Numbers" button triggers the number generation process.
*   It generates 6 unique random integers from 1 to 45 using a `Set` to prevent duplicates.
*   It dynamically creates and inserts the number display elements into the DOM.

## Current Plan: Relaunch and Verify

The previous attempt to launch the web server failed. The code for the generator is likely correct, but you were unable to see it. The plan is to restart the web server and ensure it's accessible.

1.  **Restart Web Server:** Attempt to launch the `http-server` again to serve the project files.
2.  **Verify Access:** Confirm that the application is running and accessible in the browser preview.
