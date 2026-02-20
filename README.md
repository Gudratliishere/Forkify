# 🍽️ Forkify - Recipe Search Application

A modern, responsive recipe search application built with vanilla JavaScript, featuring real-time recipe lookup with advanced filtering and bookmarking capabilities.

**Live Demo:** [https://forkify-gudratli.netlify.app/](https://forkify-gudratli.netlify.app/)

---

## Features

- **Recipe Search** - Search over 1,000,000 recipes in real-time using the Forkify API
- **Recipe Details** - View comprehensive recipe information including:
  - Ingredients with measurements
  - Step-by-step cooking instructions
  - Servings and cooking time
  - Nutritional information
- **Servings Adjuster** - Dynamically adjust ingredient quantities based on desired servings
- **Bookmark System** - Save your favorite recipes locally for quick access
- **Pagination** - Browse through search results with intuitive pagination controls
- **Add Custom Recipes** - Upload your own recipes to the database
- **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI** - Beautiful, user-friendly interface built with SASS

---

## Technology Stack

### Frontend
- **HTML5** - Semantic markup
- **CSS3/SASS** - Styling and preprocessor for maintainable stylesheets
- **Vanilla JavaScript (ES6+)** - Core application logic
- **Parcel** - Module bundler and build tool

### APIs & Libraries
- **Forkify API** - Recipe data source
- **Core-js** - JavaScript polyfills for browser compatibility
- **Fraction.js** - Fraction calculations for ingredient measurements
- **Regenerator Runtime** - Async/await support

---

## Project Structure

```
forkify/
├── src/
│   ├── js/
│   │   ├── controller.js       # Main application controller
│   │   ├── model.js            # Data management and API calls
│   │   ├── config.js           # Configuration and constants
│   │   ├── helpers.js          # Utility functions
│   │   └── views/              # View components
│   │       ├── view.js         # Base view class
│   │       ├── recipeView.js   # Recipe display view
│   │       ├── searchView.js   # Search input view
│   │       ├── resultsView.js  # Search results view
│   │       ├── paginationView.js # Pagination controls
│   │       ├── bookmarksView.js  # Bookmarks sidebar
│   │       ├── previewView.js    # Recipe preview component
│   │       └── addRecipeView.js  # Recipe upload modal
│   ├── sass/                   # Style files
│   │   ├── _base.scss
│   │   ├── _components.scss
│   │   ├── _header.scss
│   │   ├── _preview.scss
│   │   ├── _recipe.scss
│   │   ├── _searchResults.scss
│   │   ├── _upload.scss
│   │   └── main.scss
│   └── img/                    # Images and icons
├── index.html
├── package.json
└── README.md
```

---

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/forkify.git
   cd forkify
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```
   The application will open at `http://localhost:1234`

### Building for Production

```bash
npm run build
```
This creates an optimized production build in the `dist/` directory.

---

## How to Use

1. **Search for Recipes**
   - Enter a recipe name or ingredient in the search bar
   - Click "Search" or press Enter
   - Browse through the results with pagination

2. **View Recipe Details**
   - Click on any recipe from the search results
   - See the full ingredients list, cooking instructions, and serving info

3. **Adjust Servings**
   - Use the + and - buttons to adjust the number of servings
   - Ingredient quantities update automatically

4. **Bookmark Recipes**
   - Click the heart icon to bookmark a recipe
   - Access all bookmarks from the bookmarks menu on the left sidebar

5. **Add Your Own Recipe**
   - Click the "Add Recipe" button in the header
   - Fill in the recipe form with your custom recipe details
   - Submit to add it to your collection

---

## Architecture

The application follows the **MVC (Model-View-Controller)** architectural pattern:

- **Model** (`model.js`) - Handles data state, API calls, and business logic
- **Views** (`views/`) - Responsible for rendering UI and user interactions
- **Controller** (`controller.js`) - Orchestrates communication between model and views

This separation of concerns ensures clean, maintainable, and scalable code.

---

## About This Project

This is a **learning project** created as part of mastering JavaScript fundamentals and modern web development practices. It was built following the excellent guidance and curriculum from **Jonas Schmedtmann**.

## Acknowledgments

- **Mentor:** [Jonas Schmedtmann](https://twitter.com/jonasschmedtman) - For the comprehensive JavaScript course and best practices
- Recipe data powered by [Forkify API](https://forkify-api.jonas.io/)
- Built as part of learning JavaScript best practices, modern web development, and the MVC architecture pattern

---

**Happy Cooking! 👨‍🍳👩‍🍳**


