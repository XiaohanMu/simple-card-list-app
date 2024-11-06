# Simple Card List App
This project is a Simple Card List application that displays a list of products. Users can view and delete products from the list. The project consists of a backend server to manage product data and a frontend interface to display the products.

## Features
- Display a list of products with images, names, descriptions, and prices.
- Delete a product from the list.
- Backend API to manage product data.

## Installation
git clone https://github.com/XiaohanMu/simple-card-list-app.git

## Running the Backend
1. Navigate to the backend directory：
**Command:**
cd simple-card-list-app/backend

2. Install the required dependencies：
**Command:**
npm install express dotenv cors

3. Start the server:
**Command:**
node index.js

The server should now be running on http://localhost:5000/.

4. View the Content of the Backend Data：
**Command:**
curl http://localhost:5000/api/products

5. To see full entries of content data
**Command:**
(curl http://localhost:5000/api/products).Content | ConvertFrom-Json | Format-Table -Wrap


## Running the Frontend
1. Navigate to the frontend directory：
**Command:**
cd simple-card-list-app/frontend

2. Install the required dependencies:
**Command:**
npm install

Note: You may see warnings about vulnerabilities during installation. These should not prevent the app from running.

3. Start the frontend server:
**Command:**
npm start 

The frontend client should now be running on http://localhost:3000/.
