Instagram Backend
This repository contains the backend application for an Instagram-like platform. It provides essential functionalities such as user authentication (login and registration), following/followers features, adding posts, and viewing other users' profiles and posts.

Getting Started
To run the application locally, follow these steps:

Clone this repository to your local machine:

bash
Copy code
git clone <repository_url>
Navigate to the project directory:

bash
Copy code
cd instagram-backend
Install dependencies:

bash
Copy code
npm install
Start the server:

bash
Copy code
npm start
The server should now be running at http://localhost:3000.

Endpoints
User Authentication
POST /register: Register a new user.
POST /login: Log in an existing user.
Following/Followers
POST /follow: Follow another user.
Posts
POST /posts: Add a new post.
GET /posts/:userId: Get all posts by a specific user.
Viewer
GET /viewer/:userId: Get information about another user.
MongoDB URI
Make sure to update the MongoDB URI in config/db.js with your local MongoDB URI.

Technologies Used
Node.js
Express.js
MongoDB
Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Feel free to modify and expand this README to include any additional information or instructions relevant to your project!
