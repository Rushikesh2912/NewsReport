# API-Based News Application
Welcome to our API-based news application! This project provides a platform for users to access the latest news articles from various sources through a RESTful API.
## Features
   * **Browse News:** View the latest news articles from multiple sources.
   * **Search:** Search for news articles by keyword or topic.
   * **Filter:** Filter news articles by category, date, or source.
   * **Save Favorites:** Save favorite articles for later reading.
   * **User Authentication:** Secure user authentication system to manage saved favorites.
## Technologies Used
   * ### Frontend:
     * HTML, CSS, JavaScript
     * React.js
     * Axios for API requests
  * ### Backend:
    * Node.js
    * Express.js
  * ### Database:
      * MongoDB (for storing user favorites)
  * ### Authentication:
      * JSON Web Tokens (JWT) for authentication
  * ### API:
      * Integrated with News API for fetching news articles
   
  ## Setup Instructions
  1. Clone the repository:
     * git clone https://github.com/Rushikesh2912/NewsReport.git
  2. Navigate to the project directory:
      * cd NewsReport
  3. Install dependencies for both the frontend and backend:
      * cd client && npm install
      * cd ../server && npm install
  4. Configure environment variables:
      * Create a .env file in the server directory.
      * Define environment variables for MongoDB connection URI, JWT secret, and News API key.
  5. Start the backend as well as frontend server:
      * npm run both
  6. Open your browser and visit http://localhost:3000 to access the application.
