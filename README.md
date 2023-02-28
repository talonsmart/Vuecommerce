# Vuecommerce
A Vue, Node, Express, Bootstrap and MongoDB eCommerse frontend. 
This also contains a full node server as a demo of the application. I made this in my free time for the fun of it, but do keep it consistently updated. 

## Features
- 0auth secure authentication using passportjs
- Add to cart
- Administrative functionality where the admin can see the product list, edit and delete the product
- Logins
- Management of user sessions
- Remove from cart
- Signups
- clean, minimal design

## Installation
Clone the repository and run `npm install` if you use **npm** as package manager or `yarn install` if you use **yarn** as package manager.
Then, configure MongoDB `server/mongo/config.js`
```javascript
    mongoose.connect('<YOUR_MONGODB_URL>', {
        useNewUrlParser: true
    }); // connect to your database

```
6. Run the server `npm run serve`

## Setup
```javascript
npm install // install packages
npm run serve // serve on a local server

// for production and unit testing
npm run build
npm run test
npm run lint
```
