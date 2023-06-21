# MERN Ecommerce

## Description

An ecommerce store built with MERN stack, and utilizes third party API's. This ecommerce store enable three main different flows or implementations:

1. Buyers browse the store categories, products and brands
2. Sellers or Merchants manage their own brand component
3. Admins manage and control the entire store components 


* features:
  * Node provides the backend environment for this application
  * Express middleware is used to handle requests, routes
  * Mongoose schemas to model the application data
  * React for displaying UI components
  * Redux to manage application's state
  * Redux Thunk middleware to handle asynchronous redux actions
## Live Demo
https://thesusoutdoors.com/

## Demo photos
  Shop<br/>
  <img src='demo photos/Product List.png' />
  
  <details>
  Product Detail<br/>
  <img src='demo photos/Product Detail.png' />
 
  Register<br/>
  <img src='demo photos/Register.png' />
 
  Login<br/>
  <img src='demo photos/Login.png' />
 
  Admin dashboard<br/>
  <img src='demo photos/Admin dashboard.png' />
 
  Admin Prodct List<br/>
  <img src='demo photos/Admin Prodct List.png' />
 
  Admin Product Edit<br/>
 <img src='demo photos/Admin Product Edit.png' />
 
 Admin Category List<br/>
 <img src='demo photos/Admin Category List.png' />
 
 Admin Category Edit<br/>
 <img src='demo photos/Admin Category Edit.png' />
 
 Admin Brand List<br/>
 <img src='demo photos/Admin Brand List.png' />
 
 Admin Brand Edit<br/>
 <img src='demo photos/Admin Brand Edit.png' />
 
 Admin Merchant List<br/>
 <img src='demo photos/Admin Merchant List.png' />
 
 Admin Merchant Edit<br/>
 <img src='demo photos/Admin Merchant Edit.png' />
  </details>

## Database Seed

* The seed command will create an admin user in the database
* The email and password are passed with the command as arguments
* Like below command, replace brackets with email and password. 
* For more information, see code [here](server/utils/seed.js)

```
npm run seed:db [email-***@****.com] [password-******] // This is just an example.
```

## Install

Some basic Git commands are:

```
$ git clone https://github.com/bluesky-dragon/ECommer-MERN.git
$ cd project
$ npm install
```

## Setup

```
 Create .env file that include:

  * MONGO_URI & JWT_SECRET
  * PORT & BASE_SERVER_URL & BASE_API_URL & BASE_CLIENT_URL
  * MAILCHIMP_KEY & MAILCHIMP_LIST_KEY => Mailchimp configuration
  * MAILGUN_KEY & MAILGUN_DOMAIN & MAILGUN_EMAIL_SENDER => Mailgun configuration
  * GOOGLE_CLIENT_ID & GOOGLE_CLIENT_SECRET & GOOGLE_CALLBACK_URL => Google Auth configuration
  * FACEBOOK_CLIENT_ID & FACEBOOK_CLIENT_SECRET & FACEBOOK_CALLBACK_URL => Facebook Auth configuration
  * AWS_ACCESS_KEY_ID & AWS_SECRET_ACCESS_KEY & AWS_REGION & AWS_BUCKET_NAME => AWS configuration
```

## Start development

```
$ npm run dev
```

## Simple build for production

```
$ npm run build
```

## Run build for production

```
$ npm start
```


## Languages & tools

- [Node](https://nodejs.org/en/)

- [Express](https://expressjs.com/)

- [Mongoose](https://mongoosejs.com/)

- [React](https://reactjs.org/)

- [Webpack](https://webpack.js.org/)


### Code Formatter

- Add a `.vscode` directory
- Create a file `settings.json` inside `.vscode`
- Install Prettier - Code formatter in VSCode
- Add the following snippet:  

```json

    {
      "editor.formatOnSave": true,
      "prettier.singleQuote": true,
      "prettier.arrowParens": "avoid",
      "prettier.jsxSingleQuote": true,
      "prettier.trailingComma": "none",
      "javascript.preferences.quoteStyle": "single",
    }

```

