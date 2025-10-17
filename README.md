# CSV Reader

## Overview
This project is a simple, lightweight web application that reads a CSV file containing products and their prices, calculates the total price of all the products, and displays it on the webpage. The application is built with vanilla JavaScript and Bootstrap 5, demonstrating the power of these technologies in rapidly building functional, responsive web applications. This application can be useful in a variety of settings where quick calculations of total price from a CSV file are needed, such as in a small retailer's inventory management system.

## Features
- Fetch and read data from a CSV file
- Calculate the total price of all products
- Display the total price in a user-friendly format
- Responsive design that works on all devices
- Proper error handling

## Setup Instructions
1. Download the project files from the repository
2. Place your CSV file named 'products.csv' in the same directory as the 'index.html' file
3. Open 'index.html' in your web browser to run the app

## Usage Guide
After setting up the application as described above, simply open 'index.html' in your web browser. The application will automatically fetch the data from the 'products.csv' file, calculate the total price, and display it on the webpage.

## Technical Details
The application is built with HTML, CSS, JavaScript, and Bootstrap 5. It uses the Fetch API to read the CSV file and vanilla JavaScript to parse the CSV data and calculate the total price.

## Code Explanation
The JavaScript code fetches the CSV file, parses the data into a 2D array, calculates the total price by summing up the price column, and displays the total price in a div. In case of an error (such as the CSV file not being found), it displays an error message.

## License
This project is licensed under the MIT License.