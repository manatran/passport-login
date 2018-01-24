## Login and Registration with Passport.js

This project contains complete login and registration capabilities using Passport.js, a Node.js module. The data is stored in a MongoDB database.

## Purpose

This repository is an exercise to learn development with Passport.js and some other Node.js modules. Among these modules are Express and Mongoose. It is also an excellent opportunity to get to know MongoDB and authentication and validation with Node.js. The contents of this repository are loosely based on a tutorial by [Traversy Media]() on YouTube.

## Installation and setup

Clone the repository

```
git clone https://github.com/manatran/passport-login.git
```

Navigate into the directory

```
cd passport-login
```

Install the node modules

```
npm install
```

Run the Node.js server using the globally installed nodemon module

```
npm install -g nodemon
nodemon
```

Next, navigate to your installation of MongoDB and initialize the service

```
cd mongodb/bin
net start MongoDB
mongo
```

When you're done with the database, stop the service
```
^C
net stop MongoDB
```

## Contributors

* **Manaus Transez**

## License

Licensed under the MIT license.