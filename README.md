# Color-Detection-
color detection is an excellent data analytics project and an interactive application that will accurately identify the color in an image

Install the required packages:

pip install pandas opencv-python

Project Setup

Ensure you have an image file (e.g., pic2.jpg) in the project directory.
Ensure you have a CSV file (e.g., colors.csv) containing color names and their RGB values in the project directory.
Running the Project

Run the script:

python <script_name>.py

How it works:

The CSV file should contain columns for color name, hex value, and RGB values.

The image is read and resized for display.

Various global variables are declared to keep track of the state of the application.

This function calculates the minimum distance from all colors and gets the most matching color name.

The function captures the x, y coordinates of a mouse double-click and gets the RGB values of the clicked point.

The image is displayed in a window, and when a double-click is detected, a rectangle is drawn and the color name along with RGB values are displayed.

Usage

Double-click on the image:
![alt text](pic2.jpg)


Double-click on any point in the image to detect the color.
The color name and its RGB values will be displayed on the image.
For very light colors, the text will be displayed in black for better visibility.

Exit:

Press the Esc key to exit the application.