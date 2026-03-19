----------------
| TOWN TROLLEY |
----------------

TOWN TROLLEY is a project designed with farmers in mind, focusing on maximizing their profits by reducing transportation costs associated with multiple agents. It connects farmers directly with customers, ensuring better earnings for both.

--------------
| CREATED BY |
--------------
  -> Jeyaprakash R
  -> Dharanish A M

---------------------
| PROJECT STRUCTURE |
---------------------

The project is built using the MERN stack and consists of two main directories:

   ->server
   ->client

----------
| SERVER |
----------

  -> Developed with Node.js, Express, and Mongoose.
  -> Runs on port 7000 with secure transactions handled via JSON Web Token (JWT).
  -> Mongoose is used for document storage in MongoDB.

----------
| CLIENT |
----------
  -> Built using the React framework.
  -> Includes key pages:
  -> Customer Page
  -> Product Page
  -> Transport Partner Page
  -> The Transport Partner Page integrates OpenStreetMap for route planning.
  -> Development Status: Several pages are still under development and currently contain placeholder code.

----------------------
| INSTALLATION & SETUP |
----------------------

1. Clone the repository:
   git clone https://github.com/JeyaprakashRajesh/TownTrolley.git
   cd TownTrolley

2. Install dependencies for both client and server:
   cd client && npm install
   cd ../server && npm install

3. Configure environment variables:
   - Create a .env file in server/ with your MongoDB URI and JWT secret:
     MONGO_URI=your_mongodb_uri
     JWT_SECRET=your_jwt_secret

4. Start the development servers:
   - Server: cd server && npm start
   - Client: cd client && npm start

-------------------
| USAGE & BUILDING |
-------------------

- Access the client at http://localhost:3000
- Server runs at http://localhost:7000
- For production builds:
  - Client: cd client && npm run build
  - Deploy the build folder to your preferred hosting service.

-------------------
| DEPLOYMENT NOTES |
-------------------

- Ensure environment variables are set securely in production.
- Use process managers (e.g., PM2) for server reliability.
- MongoDB Atlas or local MongoDB can be used.

-------------------
| API & ARCHITECTURE |
-------------------

- RESTful API endpoints for authentication, products, orders, and partners.
- JWT-based authentication for secure transactions.
- OpenStreetMap integration for transport partner route planning.

-------------------
| CONTRIBUTING |
-------------------

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Submit a pull request

-------------------
| LICENSE |
-------------------

This project is licensed under the MIT License.

-------------------
| CONTACT |
-------------------

For questions or support, contact:
- Jeyaprakash R
- Dharanish A M
