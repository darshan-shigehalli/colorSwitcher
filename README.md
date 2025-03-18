# Color Switcher

This is a simple web page that allows users to change the background color of the page by clicking on colored boxes.

## Features

* **Color Selection:** Users can choose from aqua, black, green, orange, and yellow.
* **Dynamic Background Change:** Clicking a color box instantly changes the background color of the entire page.
* **Text Color Adjustment:** When the background color is set to black, the color of the heading and paragraph text is automatically changed to white to ensure readability.

## How to Use

1.  Open the `index.html` file in a web browser.
2.  Click on any of the colored boxes (aqua, black, green, orange, yellow).
3.  The background color of the page will change to the color of the box you clicked.

## Code Structure

* `index.html`: Contains the HTML structure of the page, including the color boxes and the heading and paragraph elements.
* CSS (embedded in `<style>` tags in `index.html`): Provides the styling for the color boxes, the layout, and the text elements.
* JavaScript (embedded in `<script>` tags in `index.html`): Handles the event listeners for the color box clicks and the logic for changing the background color.

## Improvements

The following improvements have been made to the code:

* **DRY (Don't Repeat Yourself):** Reusable function and CSS classes have been implemented to reduce code duplication.
* **Accessibility:** ARIA attributes or `<button>` elements could be considered for further accessibility improvements.
* **Code Organization:** The JavaScript code is organized for better readability.

## Credits

This project was created to demonstrate basic HTML, CSS, and JavaScript concepts.
