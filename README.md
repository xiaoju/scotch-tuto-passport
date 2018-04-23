# 'passport.js authentication' tutorial by scotch.io

Use Passport to authenticate users locally, with Facebook, Twitter, and Google.

Source:
https://scotch.io/tutorials/easy-node-authentication-setup-and-local#conclusion

## Local install instructions

0. Prerequisites
   1. create a database by `mlab.com`
1. Clone the repo: `git clone git@github.com:scotch-io/node-authentication-guide`
2. Install packages: `npm install`
3. Change out the database configuration in config/database.js
4. Launch: `node server.js` or `nodemon server.js`
5. Visit in your browser at: `http://localhost:8080`

## Files structure

```
- app
------ models
---------- user.js  <!-- our user model -->
------ routes.js    <!-- all the routes for our application -->
- config
------ auth.js      <!-- will hold all our client secret keys (facebook, twitter, google) -->
------ database.js  <!-- will hold our database connection settings -->
------ passport.js  <!-- configuring the strategies for passport -->
- views
------ index.ejs    <!-- show our home page with login links -->
------ login.ejs    <!-- show our login form -->
------ signup.ejs   <!-- show our signup form -->
------ profile.ejs  <!-- after a user logs in, they will see their profile -->
- package.json      <!-- handle our npm packages -->
- server.js         <!-- setup our application -->
- README.md
- gitignore
```
