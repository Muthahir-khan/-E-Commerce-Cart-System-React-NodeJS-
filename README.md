# -E-Commerce-Cart-System-React-NodeJS-
E-Commerce Cart System (React.js & Node.js)

This is a Mini E-Commerce Cart System built using React.js for the frontend and Node.js + Express for the backend.
It allows users to view products, add them to the cart, update quantities, proceed to checkout, and receive an order confirmation.

🚀 Features

View products fetched from an API

Add products to the cart and manage quantities

Remove items and view a dynamic total price

Checkout with a validated form (Formik & Yup)

Order confirmation page

Navigation between Home, Cart, and Checkout pages (React Router)

API integration with a backend server

Project Structure
ShopEase/
│── backend/                # Node.js & Express backend
│   ├── server.js           # API routes for products & checkout
│   ├── package.json        # Backend dependencies
│── frontend/               # React.js frontend
│   ├── src/
│   │   ├── components/
│   │   │   ├── ProductList.js
│   │   │   ├── Cart.js
│   │   │   ├── Checkout.js
│   │   │   ├── OrderConfirmation.js
│   │   ├── App.js
│   │   ├── index.js
│   ├── package.json        # Frontend dependencies
│── README.md               # Documentation

 Setup & Installation

1️⃣ Clone the Repository
git clone https://github.com/Muthahir-khan/ShopEase.git
cd ShopEase
Backend Setup (Node.js + Express)

Navigate to the backend folder:
cd backendStart the React app:

Install dependencies:
npm install

Start the backend server:
node server.js
Or, if you want the server to restart on changes:
npx nodemon server.js

Verify the API:Open your browser or use Postman and visit:
http://localhost:5000/api/products

Frontend Setup (React.js)

Open a new terminal and navigate to the frontend folder:
cd frontend
Install dependencies:
npm install
Start the React app:
npm start
Open your browser and go to:
http://localhost:3000


Usage

Browse products on the Home page.

Click "Add to Cart" to add products.

Click the Cart link to view your items.

Increase/decrease quantity or remove items.

Go to Checkout, enter details, and submit.

View the Order Confirmation page.

Tech Stack

Frontend: React.js, React Router, Formik, Yup

Backend: Node.js, Express.js

State Management: React Hooks (useState)

Styling: Basic CSS

API Handling: Axios, Fetch API

API Endpoints

Method

Endpoint

Description

GET

/api/products

Fetch product list

POST

/api/checkout

Submit order details


