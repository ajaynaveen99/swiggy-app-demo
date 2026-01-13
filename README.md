🍔 Swiggy Clone – React Application

A React-based food ordering application inspired by Swiggy.
This project demonstrates core React concepts such as components, props, state management, routing, conditional rendering, and reusable UI components.

📌 Project Overview

This application allows users to:

Browse restaurants

View restaurant menus

Add items to a cart

Navigate between pages like Home, About, Contact, and Cart

Experience a clean and reusable component-based UI

The project is built mainly for learning and practicing React fundamentals.

🧩 Components Used
🔹 Header.jsx

Displays the application header

Contains navigation links (Home, About, Contact, Cart)

Acts as a common layout component visible on all pages

🔹 Body.jsx

Main container for rendering core content

Responsible for displaying restaurant listings

Uses reusable restaurant card components

🔹 Home.jsx

Acts as the landing page

Integrates Body and other UI sections

Displays the list of available restaurants

🔹 ResturantCard.jsx

Reusable card component for each restaurant

Displays:

Restaurant name

Cuisine type

Rating

Delivery details

Used multiple times to render restaurant lists

🔹 RestuarentMenu.jsx

Displays the selected restaurant’s menu

Shows food items available in a restaurant

Designed to work with dynamic route parameters

🔹 Cart.jsx

Displays items added to the cart

Central place to view selected food items

Prepared for future enhancements like quantity and total price

🔹 Theme.jsx

Handles UI theme-related logic

Helps in maintaining consistent styling

Can be extended for dark/light mode

🔹 About.jsx

Provides information about the application

Explains the purpose of the project

🔹 Contact.jsx

Contact information or support-related content

Simple static page component

🔹 NotFound.jsx

Displays a 404-style page

Shown when a user navigates to an invalid route

🛠️ Technologies Used

React.js

JavaScript (ES6+)

JSX

CSS / Tailwind CSS

React Router DOM