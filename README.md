## Random_Number_Generator


### Description

This is a simple web-based application that generates a random number between 1 and 100 and a 4-digit OTP (One-Time Password) whenever the "Generate" button is clicked. The project consists of basic HTML, CSS, and JavaScript code. 

### Features
- Generates a random number (1-100) on button click.
- Generates a random 4-digit OTP.
- Displays both the random number and OTP on the page.
- Includes a responsive and visually appealing design.
- Footer with copyright information and GitHub link.

### Files

1. **HTML File (`index.html`)**  
   The structure of the web page. It contains a title, a button to trigger the generation of random numbers and OTPs, and sections to display the results.

2. **CSS File (`styles.css`)**  
   Provides styling for the page, including the layout, colors, and button animations.

3. **JavaScript File (`index.js`)**  
   Contains the logic to generate the random number and OTP, and to display them in the respective areas on the page.

### How It Works

1. **HTML Structure:**
   - The page has a button labeled "Generate" and two `<p>` tags for displaying the random number and OTP.
   - The button triggers the `generateNumber()` function when clicked.

2. **CSS Styling:**
   - Basic styles are applied to the body, button, and text.
   - The button includes a hover effect that changes its background and adds a shadow.
   - The page is centered with a footer that remains fixed at the bottom.

3. **JavaScript Functionality:**
   - The `generateNumber()` function generates a random number between 1 and 100.
   - It also generates a random 4-digit OTP.
   - The results are displayed in the `<p>` tags with IDs `output` and `outputOTP`.


### How to Run
1. Clone or download the project files.
2. Open `index.html` in any web browser.
3. Click the "Generate" button to generate a random number and OTP.

