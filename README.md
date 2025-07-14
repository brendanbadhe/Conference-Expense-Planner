# Conference Expense Planner

## Overview

The Conference Expense Planner is a front-end application designed to help users estimate and plan expenses for hosting a conference at a convention center. The app provides an interactive interface for selecting rooms, add-ons, and meals, and calculates pricing based on user selections.

## Live Demo

You can try the app online at: [https://brendanbadhe.github.io/Conference-Expense-Planner/](https://brendanbadhe.github.io/Conference-Expense-Planner/)

## Features

- **Landing Page**: Engages users with a company introduction, background image, company name, and a "Get Started" button to enter the main application.
- **Product Selection Page**: Allows users to select rooms, add-ons (AV equipment), and meals. Each section has its own header and navigation bar.
  - **Room Selection**: Choose from 5 room types with increment/decrement buttons for quantity.
  - **Add-ons Selection**: Select AV equipment (speakers, microphones, whiteboards, projectors, signage) with quantity controls.
  - **Meals Selection**: Enter the number of people for each meal type (breakfast, lunch, high tea, dinner).
- **Show Details Pop-up**: Displays a summary table of all selections, including item type, unit cost, quantity, subtotal, and total cost.
- **Dynamic Pricing**: Real-time calculation and display of subtotals and total expenses based on selections.
- **Redux Toolkit**: State management using Redux slices for rooms, add-ons, and meals.
- **Modern UI**: Built with React and Vite for fast, responsive user experience.

## Technologies Used

- React
- Redux Toolkit
- Vite
- CSS

## Getting Started

1. Clone the repository:

   ```sh
   git clone https://github.com/brendanbadhe/Conference-Expense-Planner.git
   ```

2. Install dependencies:

   ```sh
   npm install
   ```

3. Start the development server:

   ```sh
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173` (or the port shown in your terminal).

## Project Structure

- `src/` - Source code for components, slices, and styles
- `public/` - Static assets and images
- `index.html` - Main HTML file
- `vite.config.js` - Vite configuration
