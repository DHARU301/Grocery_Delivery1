# Grocery_Delivery1
🐰 Rabbit Mart
Rabbit Mart is a new  startup that guarantees delivery within 20 minutes of specified locations. While Rabbit Mart is only available on mobile platforms, our job is to make the shopping experience available to web users as well.



Tech Stack
Frontend	Backend
React	Node.js
React Router	Express.js
Redux	MongoDB
Axios	Stripe
SendGrid
Usage



Client Side
$ cd client   # go to the client folder
$ npm i       # install packages
$ npm start   # run the client side statically with react-scripts
Server Side
Create a .env file in the server directory and insert the following code. Replace the values with your credentials.

# DATABASE CONNECTIVITY
CONNECTION_URL=

# JWT SECTION
JWT_SECRET_KEY =
JWT_AUTH_TTL = 
JWT_CHECKOUT_TTL = 

# EMAIL SECRETS
SENDGRID_KEY = 

# PAYMENT SECRETS
STRIPE_PRIVATE_KEY = 
Start the server

$ cd server   # go to the server folder
$ npm i       # install packages
$ npm start   # start the server
