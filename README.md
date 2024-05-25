# Recipe App

Welcome to the **Recipe App** repository! This project provides a user-friendly application for discovering, creating, and managing recipes. Whether you're a seasoned chef or a home cook, this app helps you keep track of your culinary creations and explore new ones.

## Features

- **Recipe Discovery**: Browse and search for recipes by ingredients, cuisine, or dietary restrictions.
- **Recipe Creation**: Add your own recipes with detailed ingredients, steps, and photos.
- **Favorites**: Save your favorite recipes for quick access.
- **Categories**: Organize recipes by categories such as breakfast, lunch, dinner, and desserts.
- **Shopping List**: Generate a shopping list based on the ingredients needed for your selected recipes.
- **User Authentication**: Secure login and registration for personalized recipe management.
- **Responsive Design**: Optimized for both desktop and mobile devices for cooking on the go.

## Technologies

- **Frontend**: HTML5, CSS3, JavaScript, React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **Deployment**: Netlify, Vercel, Heroku

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/recipe-app.git
   cd recipe-app
   ```

2. **Install frontend dependencies**:
   ```bash
   cd client
   npm install
   ```

3. **Install backend dependencies**:
   ```bash
   cd ../server
   npm install
   ```

4. **Configure the environment variables**:
   - Create a `.env` file in the `server` directory and add your MongoDB URI and JWT secret.
   ```
   MONGO_URI=your_mongo_db_uri
   JWT_SECRET=your_jwt_secret
   ```

5. **Run the backend server**:
   ```bash
   npm start
   ```

6. **Run the frontend application**:
   ```bash
   cd ../client
   npm start
   ```

7. **Access the application**:
   - Navigate to `http://localhost:3000` in your web browser.

## Usage

1. Sign up for a new account or log in if you already have one.
2. Browse recipes by category, ingredients, or search keywords.
3. Create and add your own recipes with step-by-step instructions and photos.
4. Save recipes to your favorites for quick access.
5. Generate a shopping list from the ingredients of selected recipes.
6. Use the responsive design to access and cook recipes from any device.

## Project Structure

- `client/`: React.js frontend source code
- `server/`: Node.js backend source code
- `public/`: Public assets and static files
- `models/`: MongoDB models for storing user data and recipes
- `routes/`: API routes for the backend

## License

This project is licensed under the MIT License – see the [LICENSE.md](LICENSE.md) file for details.
