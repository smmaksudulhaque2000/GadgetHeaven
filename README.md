<div align="center">
  <img src="https://i.ibb.co.com/WWpBCCtC/Screenshot-1.png" height="400" alt="GadgetHeaven"/>
</div>

# GadgetHeaven ✨

Your ultimate destination for the latest and most innovative gadgets! GadgetHeaven is a fully responsive e-commerce platform designed for users to explore, purchase, and manage a wishlist of various gadgets. The project is meticulously crafted following a detailed Figma design, incorporating an intuitive navigation system, categorized product listings, individual product detail pages, and seamless shopping functionalities.

---

## 🌐 Live Demo

Experience the live site here: [GadgetHeaven on Surge](https://maksudulhaque2000.surge.sh/)

---

## 🎯 Features

### 1. **Gadget Categories & Product Filtering**
   - Sidebar navigation with categories such as Computers, Phones, Smartwatches, Chargers, and Power Banks.
   - A structured layout dynamically displays products based on the selected category, each featuring distinct attributes and prices (starting at $50).

### 2. **Product Details & Interactive Wishlist/Cart**
   - Detailed product pages showcasing comprehensive information.
   - Interactive buttons for adding items to the cart or wishlist.
   - Data persistence using Context API and LocalStorage for an uninterrupted user experience.

### 3. **Shopping Cart & Wishlist Management**
   - Dedicated tabs for managing the Cart and Wishlist from the Dashboard.
   - Sorting functionality for Cart items (descending price order) and real-time total price calculation.

### 4. **Error Handling & Custom 404 Page**
   - A dedicated 404 page ensures users are informed when visiting an incorrect route.
   - Robust error handling prevents unexpected disruptions.

### 5. **User Engagement with Toast Notifications**
   - Instant feedback through toast notifications when adding items to the cart or wishlist.

---

## 📱 Technologies Used

- **React** – Component-based architecture for a scalable UI.
- **Context API** – Efficient state management.
- **React Router** – Smooth navigation and route handling.
- **React-Toastify** – User notifications for enhanced engagement.
- **LocalStorage** – Persistent data handling for cart and wishlist.

---

## 🛠 Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/programming-hero-web-course-4/b10a8-gadget-heaven-smmaksudulhaque2000.git
   cd gadgetheaven
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the application:
   ```bash
   npm start
   ```
4. Open [GadgetHeaven Live](https://smmaksudulhaque2000.surge.sh/) in your browser.

---

## 🎨 Application Overview

### Navbar
   - Displays logo, brand name, and navigation links to Home, Dashboard, and Statistics.
   - Highlights the active route for better navigation clarity.

### Home Page
   - **Banner Section:** Styled according to Figma with a call-to-action button leading to the Dashboard.
   - **Categories Sidebar:** Organized gadget categories for seamless browsing.
   - **Product Cards:** Displays product image, name, price, and a "Details" button linking to the respective product page.

### Product Details Page
   - Comprehensive product information.
   - Options to add items to the Cart or Wishlist.

### Dashboard
   - Displays Cart and Wishlist items with total price calculation.
   - Sort function for Cart items by price.

### Footer
   - Consistent footer across all pages with essential links and details.

---

## 🚀 How to Use

1. **Explore Products by Category:** Use the sidebar to filter gadgets by category.
2. **View Product Details:** Click "Details" on any product card for more information.
3. **Add to Cart/Wishlist:** Utilize buttons on product pages to save desired items.
4. **Manage Cart and Wishlist:** Navigate to the Dashboard to review, sort, or remove items.

---

## 📂 Project Structure
```
gadgetheaven/
├── public/
├── src/
│   ├── components/    # Reusable React components
│   ├── context/       # Context API setup
│   ├── data/          # JSON data for products
│   ├── pages/         # Application pages (Home, Dashboard, Details, 404)
│   ├── App.js         # Main application entry
│   ├── index.js       # Root file
│   └── styles/        # Styling and CSS
├── README.md
├── package.json
└── vite.config.js
```

---

## 🧩 React Fundamentals Implemented

- **JSX** for component structuring.
- **State & Props** for dynamic data handling.
- **Context API** for managing cart and wishlist states.
- **React Router** for seamless navigation.

---

## 📝 Additional Features

- **Dynamic Page Titles & Favicon:** Unique titles and favicons for different pages.
- **Edge Case Handling:** Limits cart value to $1000 with proper user notifications.
- **Fully Responsive Design:** Optimized for desktops, tablets, and mobile devices.

---

## 💡 Challenges & Enhancements

- **Custom Background by Route:** Dynamic background colors based on the active route.
- **Purchase Confirmation Modal:** A congratulatory message with a redirect option upon purchase.
- **Statistics Page (Optional):** Displays product price and rating charts for user insights.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🏆 Acknowledgments

- **Figma** for UI design inspiration.
- **React-Toastify** for smooth notifications.
- **Vite** for optimized development workflow.

