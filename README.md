# CSS Color Markers

A simple web project that visually represents colored markers using HTML and CSS. This project demonstrates the use of CSS gradients, box shadows, and layout techniques to create realistic marker visuals.

## 🚀 Features

      Three colored markers: Red, Green, and Blue

      Smooth gradient effects for a realistic look

      Box shadows for depth and better visibility

      Responsive and clean layout

## 📂 Project Structure

/ Colored_Markers
  ├── index.html   # Main HTML file
  ├── styles.css   # CSS file for styling
  ├── README.md    # Project documentation

## HTML Structure

The `index.html` file provides the basic structure for the markers, including:

* A container (`<div class="container">`) to hold the markers.
* Individual marker elements (`<div class="marker">`) with color-specific classes (red, green, blue).
* Cap (`<div class="cap">`) and sleeve (`<div class="sleeve">`) elements within each marker for visual detail.

## CSS Styling

The `styles.css` file defines the styling for the markers, using the following techniques:

* **Layout:**
    * The container has a white background and padding.
    * Markers are centered horizontally using `margin: 10px auto;`.
    * `display: inline-block;` is used on the cap and sleeve to place them side by side.
* **Coloring:**
    * Each marker uses a `linear-gradient` background to create a smooth color transition.
    * Red, green, and blue markers use varying gradient color stops to create distinct color effects.
    * The sleeve div has a semi transparent white background and a double border.
* **Visual Effects:**
    * `box-shadow` is used to create a glowing effect around each marker.
* **Color Models:**
    * The red and green markers use `rgb()` color values.
    * The blue marker uses `hsl()` and `hsla()` color values, demonstrating different color models.

## Technologies Used

* HTML5
* CSS3 (linear gradients, box shadows, color models)

## 🛠️ How to Run

Simply open the `index.html` file in a web browser to view the colored markers.

## Learning Points

This project is created as a practice exercise - providing practice in:

* Using CSS linear gradients for smooth color transitions.
* Applying box shadows to create visual depth.
* using different css color models.
* Using inline block to help layout elements.

## 📌 Purpose

My purpose for working on this project is to **practice and revise my CSS skills** and to **apply Git skills**. 
This project is part of **freeCodeCamp's curriculum**.








