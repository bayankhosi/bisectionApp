# Enhanced Bisection Method Calculator

## Overview

The Enhanced Bisection Method Calculator is a web-based tool that implements the bisection method for finding roots of a continuous function. This interactive calculator provides a user-friendly interface for inputting functions and parameters, visualizing the bisection process, and understanding the underlying mathematical concepts.

## Features

- **Interactive Input**: Users can input custom functions and specify the interval and number of iterations.
- **Real-time Calculation**: The calculator performs the bisection method in real-time and displays the results.
- **Step-by-Step Visualization**: Users can step through the bisection process to understand how the algorithm works.
- **Graphical Representation**: The tool plots the function and illustrates each step of the bisection method on the graph.
- **Intermediate Value Theorem Check**: The calculator checks if the Intermediate Value Theorem conditions are met before proceeding with calculations.
- **Dark Mode**: A toggle for switching between light and dark modes for comfortable viewing in different lighting conditions.
- **Responsive Design**: The interface adapts to different screen sizes, making it usable on both desktop and mobile devices.
- **Educational Content**: An "About" section provides detailed information about the bisection method, its formula, advantages, and disadvantages.

## How to Use

1. Open the `bisection_method_calculator.html` file in a web browser.
2. Enter your function in terms of `x` in the "Enter function f(x)" field (e.g., `x^3 - x - 2`).
3. Specify the lower bound `a` and upper bound `b` of the interval.
4. Enter the desired number of iterations.
5. Click "Calculate" to run the bisection method.
6. Use the "Step Through" button to visualize the process step by step.
7. Toggle dark mode using the "Toggle Dark Mode" button if desired.
8. Click "Show/Hide About Section" to view or hide educational content about the bisection method.

## Dependencies

This calculator uses the following external libraries:

- [Math.js](https://mathjs.org/): For parsing and evaluating mathematical expressions.
- [Plotly.js](https://plotly.com/javascript/): For creating interactive plots.
- [MathJax](https://www.mathjax.org/): For rendering mathematical equations.

All dependencies are loaded via CDN links in the HTML file, so no additional installation is required.

## Technical Details

- The calculator is implemented as a single HTML file containing embedded CSS and JavaScript.
- It uses modern JavaScript features and is compatible with recent versions of major web browsers.
- The bisection algorithm is implemented in JavaScript and runs entirely in the browser.

## Customization

You can customize the appearance of the calculator by modifying the CSS variables in the `<style>` section of the HTML file. The color scheme, fonts, and layout can be adjusted to fit your preferences or to match your website's design if you're embedding this calculator.

## License

This Enhanced Bisection Method Calculator is open-source software licensed under the MIT license. Feel free to use, modify, and distribute it as per the terms of the license.

## Contributions

Contributions to improve the calculator are welcome. Please feel free to submit issues or pull requests on the project's repository.

## Author

[Your Name or Organization]

---

Enjoy using the Enhanced Bisection Method Calculator for your mathematical explorations and educational purposes!