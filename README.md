# Wheel Spin Game

This is a simple web-based game where users can spin a wheel and win prizes based on where the wheel stops. The game is implemented using HTML, CSS, and JavaScript, with the help of the Chart.js library for rendering the wheel as a pie chart.

## How to Play

1. Open the `index.html` file in a web browser.
2. Click the "Spin" button to start spinning the wheel.
3. On the first spin, the message "Try again!" will be displayed when the wheel stops.
4. On the second spin, the user will win a gift card or prize based on where the wheel stops.

## Code Explanation

The main code for the game can be found in the `script.js` file. Here's an overview of the key components:

- `rotationValues`: An array that defines the minimum and maximum angles for each value on the wheel.
- `data`: An array that represents the size of each section on the pie chart.
- `pieColors`: An array that defines the background color for each section of the pie chart.
- `myChart`: An instance of the Chart.js library used to render the pie chart.
- `valueGenerator`: A function that determines the prize based on the angle the wheel stops at.
- `spinBtn`: Event listener for the spin button click, which triggers the wheel spinning animation.

## Customization

- To add or modify the prizes and their corresponding angles, update the `rotationValues` array.
- To change the number of sections on the wheel and their sizes, update the `data` array.
- To change the background colors of the sections, modify the `pieColors` array.
- You can also customize the appearance of the pie chart by modifying the options in the `myChart` configuration object.

Feel free to modify the code to add more features or customize the game according to your needs!
