# Amazon Clone  

This repository contains a project that replicates key features of **Amazon**, one of the largest e-commerce platforms. The **Amazon Clone** is designed to simulate the core functionalities of Amazon, allowing users to browse products, add items to their cart, proceed with checkout, and more. This project provides an opportunity to understand and build scalable e-commerce applications, while offering a simplified version of Amazon’s user interface (UI) and experience.

---

## 🚀 Features  

- **User Authentication**: Users can sign up, log in, and manage their profiles.  
- **Product Catalog**: Browse products across various categories such as electronics, fashion, books, and more.  
- **Shopping Cart**: Add products to the cart and view cart details with the ability to update quantities or remove items.  
- **Checkout Process**: A streamlined checkout process for adding delivery addresses, selecting payment methods, and placing orders.  
- **Order History**: View past orders with their status.  
- **Search Functionality**: Users can search for products by keywords, categories, or filters.  
- **Responsive Design**: The website is mobile-friendly and adapts to various screen sizes.  

---

## 🛠️ Installation  

Follow these steps to set up the Amazon Clone locally:

### 1. Clone the Repository  
```bash  
git clone https://github.com/anaumsharif/amazon-clone.git  
cd amazon-clone  
```  

### 2. Install Dependencies  

For **backend**:
```bash  
cd backend  
npm install  
```

For **frontend**:
```bash  
cd frontend  
npm install  
```

### 3. Set Up Environment Variables  
Create a `.env` file in the **backend** folder and set the following environment variables:
- `MONGO_URI`: MongoDB connection string.
- `JWT_SECRET`: Secret key for JSON Web Tokens.

### 4. Start the Application  
For **backend**:
```bash  
cd backend  
npm start  
```

For **frontend**:
```bash  
cd frontend  
npm start  
```

The application should now be running locally. Visit `http://localhost:3000` to view the frontend.

---

## 📊 Technologies Used  

- **Frontend**:  
  - **React**: For building the user interface.  
  - **React Router**: For navigation between different pages.  
  - **Redux**: For managing global state (like the shopping cart and user authentication).  
  - **CSS/SCSS**: For styling the components.  

- **Backend**:  
  - **Node.js**: JavaScript runtime for building the server.  
  - **Express**: Web framework for routing and building APIs.  
  - **MongoDB**: NoSQL database for storing user and product data.  
  - **JWT (JSON Web Tokens)**: For user authentication and authorization.  

- **Other Tools**:  
  - **Axios**: For making HTTP requests between frontend and backend.  
  - **Bcrypt**: For hashing passwords.  
  - **Stripe**: For handling payments (if implemented).  

---

## 🚦 Usage  

### 1. **User Registration & Login**  
Users can register with their details and log in to access personalized features such as the shopping cart and order history.

### 2. **Browse and Search Products**  
Users can browse through product categories or use the search bar to find products.  

### 3. **Add to Cart and Checkout**  
After selecting items, users can add them to the cart and proceed to checkout. The system allows users to input shipping information and choose payment methods.

### 4. **Order History**  
Users can view their past orders along with their status (processing, shipped, delivered).  

---

## 📜 Acknowledgements  

This project is built to replicate the functionality of Amazon and is intended for educational purposes. It is not affiliated with Amazon in any way.  

---

