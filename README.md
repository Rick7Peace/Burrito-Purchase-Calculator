# Burrito-Purchase-Calculator
This project is a simple web-based app that allows users to select the number of burritos they want to purchase and calculates the total cost including tax and shipping.

# Files

1. index.html
The main HTML page for the app.

Contains a header prompting users to select the number of burritos.

Includes a dropdown <select> with options from 1 to 8 burritos.

A "Calculate" button triggers the cost calculation.

Displays the calculated total cost dynamically.

Links to the external CSS and JS files located in the assets folder.

2. assets/style.css

Contains the styling for the page.

Applies a global reset for margins and paddings.

Styles the page with a clean and modern look:

Centered content with a gradient background.

Styled dropdown menu and button with hover effects.

Header and output text formatting.

Adds subtle animations such as a hover lift effect on container (though not used explicitly in HTML here).

3. assets/index.js

Defines constants for burrito price, tax rate, and shipping cost.

Reads the number of burritos selected by the user.

Calculates total cost as:
(burrito price × quantity) + (tax per burrito × quantity) + shipping cost

Updates the page with the total cost when the button is clicked.

# How to Use

Open index.html in a web browser.

Select the number of burritos to purchase from the dropdown.

Click the "Calculate" button.

The total cost (including taxes and shipping) will display below the button.

# Screenshots
<img width="1512" height="982" alt="Image" src="https://github.com/user-attachments/assets/281358ce-dfae-4a9a-8086-919b03577213" />

<img width="1512" height="982" alt="Image" src="https://github.com/user-attachments/assets/1997a7ef-e6ce-4042-b1cf-661b6e4a6c8f" />

<img width="1512" height="982" alt="Image" src="https://github.com/user-attachments/assets/31fed5de-f9be-4cce-924d-b87d3e4c55b4" />

# Notes
Prices and rates are hardcoded but can be easily updated in index.js.

Shipping cost is fixed regardless of quantity.

The app uses vanilla JavaScript for simplicity.

The UI uses simple CSS styles with a focus on usability and aesthetics.