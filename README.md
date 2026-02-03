🍽️ CookBook — Recipe Discovery Web Application
Overview

CookBook is a modern React-based web application for discovering, exploring, and organizing recipes using real-time data from TheMealDB API.
The application delivers a smooth single-page experience with category-based browsing, detailed recipe views, and search functionality.

This project focuses on frontend architecture, API integration, routing, and scalable component design.

🚀 Key Features

Browse recipes by category (Chicken, Vegetarian, Seafood, Desserts, etc.)

Search recipes dynamically using external API data

View detailed recipe information including ingredients and instructions

Responsive UI with reusable React components

Client-side routing using React Router

Clean separation of pages, components, and styles

🧠 Tech Stack

Frontend: React (Create React App)

Routing: React Router DOM

API Integration: Axios + TheMealDB API

Styling: CSS (Modular structure)

State Management: React Hooks & Context API

Testing (Planned): Jest, React Testing Library

🏗️ Application Architecture

Component-based design for scalability

Pages handle routing logic

Reusable components for UI consistency

Centralized API calls for maintainability

Core Components

RecipeList – Displays recipes by category

RecipeDetail – Shows detailed recipe information

SearchBar – Enables recipe search

Navbar & Footer – Application layout

CategoryPage – Dynamic category-based routing

🔄 Routing Structure
/                   → Home Page
/category/:name     → Recipes by Category
/recipe/:id         → Recipe Details

🛠️ Setup & Installation
Prerequisites

Node.js (LTS)

npm

Git

Installation Steps
git clone https://github.com/<your-username>/cookbook.git
cd cookbook
npm install
npm start


The app will be available at:
👉 http://localhost:3000

🌐 Environment Variables

Create a .env file in the root directory:

REACT_APP_API_URL=https://www.themealdb.com/api/json/v1/1

📊 Project Highlights

Reduced dependency on static data by integrating live APIs

Modular architecture supports future enhancements

Designed for performance, readability, and scalability

Clear separation of concerns improves maintainability

⚠️ Known Limitations

Depends on external API availability

No caching layer implemented yet

Authentication not included in current version

🔮 Future Enhancements

User authentication & saved recipes

AI-based recipe recommendations

Meal planning and grocery list generation

API caching and performance optimization

Mobile app extension (React Native)

👥 Contributors

Supriya Amudapaku — Frontend Development & API Integration

Team contributors as documented in project documentation 

Recipe app(Documenation)
