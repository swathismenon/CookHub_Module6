CookHub is a full-stack food blog application designed to allow users to easily explore and share recipes.
Users can browse through various food recipes, add new recipes, edit existing ones, and delete recipes. The app is built using the MERN stack (MongoDB, Express.js, React.js, Node.js) with modern web development best practices to ensure responsiveness, accessibility, and scalability.

Tech Stack
Frontend:
The user interface is built using React.js, providing a dynamic, interactive experience for users. For styling, the app utilizes CSS for custom styles, ensuring responsiveness across devices.

Backend:
The backend is powered by Node.js and Express.js, making it easy to handle requests and perform CRUD (Create, Read, Update, Delete) operations with the recipes stored in a MongoDB database.

Authentication:
The app uses JWT (JSON Web Tokens) for user authentication, ensuring secure login and session management. Passwords are securely hashed using bcrypt to protect user data.

Database:
MongoDB serves as the NoSQL database where all the recipes and user information are stored. Mongoose helps to manage data models and schema validation.

1. git clone https://github.com/swathismenon/CookHub_Module6.git
 cd foodrecipe

2.cd backend
npm install

3. create .env file
CONNECTION_STRING=mongodb://localhost:27017/foodRecipe

5. npm run dev

Tracking
Tracking with Google Analytics is set up for the frontend using react-ga4 to track page views and form submissions. 

Security
I’ve taken several steps to secure the project, including:

Password hashing: Using bcrypt for secure password storage.

Authentication: Users must log in to access and modify data.

