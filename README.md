#LIVE CHAT APPLICATION


The Live-Chat Application is a Node.js-based project incorporating Express.js, Socket.IO, and MySQL to facilitate seamless, text-based communication among users. With features like user registration, authentication, and session management, it provides a dynamic platform for real-time interaction without the need for page refreshes.

To set up the application, ensure Node.js is installed, clone the repository, and install dependencies using npm. Start the server with `node app.js` and access the application through a web browser at `http://localhost:3000`.

API routes handle user interactions:
- `/index` renders the login page.
- `/register` displays the registration page.
- `/logindata` manages user login, redirecting authenticated users to the search page.
- `/register` handles user registration, storing data in the MySQL database.

Environment configurations involve installing Express.js, Body-parser, Multer, MySQL, Express-session, and Socket.IO dependencies.

Server-side logic resides in `app.js`, managing routes and integrating Socket.IO for real-time communication. HTML templates (`index.html`, `register.ejs`, `search.ejs`) provide user interfaces, while CSS styles are embedded within for simplicity. However, external CSS files are recommended for better maintainability.

Ensure MySQL database setup includes necessary tables for user authentication and registration.

In essence, the Live-Chat Application offers a robust platform for users to engage in instant messaging, facilitated by Node.js technologies and real-time communication capabilities.
