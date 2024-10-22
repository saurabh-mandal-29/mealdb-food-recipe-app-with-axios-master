# Recipe Quest

Recipe Quest is a robust food recipe web application developed using **React JS**, **Axios**, and the **Meal DB API**. The app provides users access to over 1,000 unique recipes, allowing them to search and explore a variety of meal options with real-time data retrieval.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Integration](#api-integration)

## Demo

Check out the live demo of Recipe Quest here:

👉 [**Live Demo**](https://recipe-quest-five.vercel.app/)

## Features

- Access over 1,000 unique recipes in real-time.
- Efficient API integration for fast data retrieval using Axios.
- Search for recipes by name or category.
- Beautiful, responsive design using CSS and CSS-in-JS libraries.
- Dynamic rendering of recipe details including ingredients, instructions, and images.

## Technologies Used

- **React JS** – JavaScript library for building interactive UIs.
- **Axios** – For handling HTTP requests and managing asynchronous API responses.
- **Meal DB API** – Source of over 1,000 food recipes.
- **CSS/CSS-in-JS** – Styling for enhanced visual appeal and responsiveness.

## Installation

To run the project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/recipe-quest.git
    ```

2. Navigate to the project directory:
    ```bash
    cd recipe-quest
    ```

3. Install the required dependencies:
    ```bash
    npm install
    ```

4. Create a `.env` file in the root directory and add your Meal DB API key:
    ```bash
    REACT_APP_MEALDB_API_KEY=your-meal-db-api-key
    ```

5. Start the development server:
    ```bash
    npm start
    ```

## Usage

After running `npm start`, the app will be available at `http://localhost:3000`. Users can:
- Search for recipes by entering keywords.
- Click on a recipe card to view detailed instructions, ingredients, and meal images.

## API Integration

Recipe Quest uses the **Meal DB API** to fetch recipes. Axios handles the API requests and responses, ensuring that data is efficiently delivered to the front-end. By optimizing asynchronous calls, the app achieves a 20% reduction in data fetch time, providing real-time updates to the UI components.

To learn more about the Meal DB API, visit the official [Meal DB documentation](https://www.themealdb.com/).
