# shopyfy

# Online Ecommerce Application

## This is an online ecommerce shop build with Node, Express and MongoDB. It has following features.

# Feature

- Login and signup
- Reset Password
- Session and Cookies
- Adding and deleting products
- Validation on input fields
- Sending automatic email on signup
- Stripe payment gateway
- Automatic invoice generation after order
- Pagination on products list page
- File uploads and downloads
- And many more ....

# Main technology and framework used
- Node.js
- Express
- MongoDB
- Mongoose
- Requirements
if you want to run this app in your project then the following things must be installed in your system

Node.js
MongoDB
Installation

- Open the project in VS code or any other code editor.
- Run npm intall in terminal to download all the dependencies
- Get Mongodb atlas url or use your local database
- Create a .env file in the root directory
- Run command npm start to run the code.

- .env file should contain the following data

-- SENDGRID_API_KEY=(Add your sendgrid api key for email sending)
-- SESSION_SECRET_KEY=(Put any session secret string you want)
-- STRIPE_API_KEY=(Add Your Stripe API Key)
-- If you are using Mongodb atlas then also put

- MONGO_USERID=(Atlas user id)
- MONGO_PASSWORD=(atlas password) If you are using local database then replace MONGODB_URI in app.js file with mongodb://localhost:27017/shop
