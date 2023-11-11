#MERN Stack Multi-Vendor-Website
This is a fully functional multi-vendor-website built using the MERN stack (MongoDB, Express, React, Node.js) and Socket.io for real-time communication. The website allows users to browse products, add them to their cart, and checkout securely using Stripe payment gateway.

##Features
User authentication and authorization using JWT tokens
Real-time communication using Socket.io
Product search and filtering
Product reviews and ratings
Shopping cart and checkout functionality
Admin dashboard for managing products, orders, and users , analytics , chat, products.
Technologies Used
MongoDB Express.js React.js Node.js Socket.io.

##Installation
Clone the repository
Install dependencies using npm install on both
Create a .env file in the root directory and add the following environment variables:
  NODE_ENV=development
PORT=8000
MONGO_URI=<your_mongodb_uri>
JWT_SECRET=<your_jwt_secret>
NODE_ENV=development
Run the full app from the backend using npm run dev
Run the client using npm run client
Open http://localhost:3000 in your browser
