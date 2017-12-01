[![HTML5,CSS3 and JS](https://github.com/FransLopez/logo-images/blob/master/logos/html5-css3-js.png)](http://www.w3.org/)
[![ES6](https://github.com/MarioTerron/logo-images/blob/master/logos/es6.png)](http://www.ecma-international.org/ecma-262/6.0/) 
[![Bootstrap](https://github.com/FransLopez/logo-images/blob/master/logos/bootstrap.png)](http://getbootstrap.com/)  
[![npm](https://github.com/MarioTerron/logo-images/blob/master/logos/npm.png)](https://www.npmjs.com/)
[![React](https://github.com/FransLopez/logo-images/blob/master/logos/react.png)](https://facebook.github.io/react/)
[![NodeJS](https://github.com/FransLopez/logo-images/blob/master/logos/nodejs.png)](https://nodejs.org/)
[![ExpressJS](https://github.com/MarioTerron/logo-images/blob/master/logos/expressjs.png)](http://expressjs.com///)
[![MongoDB](https://github.com/FransLopez/logo-images/blob/master/logos/mongodb.png)](https://www.mongodb.com/)
[![Monogoose](https://github.com/MarioTerron/logo-images/blob/master/logos/mongoose.png)](http://mongoosejs.com/)
---
[![Skylab](https://github.com/FransLopez/logo-images/blob/master/logos/skylab-56.png)](http://www.skylabcoders.com/)


## Take My Friends
#### Skylab Final Project

## Login and register
## ![Login and register](https://i.imgur.com/L7U0PT4.png)

## Home page
## ![Home](https://i.imgur.com/AFdmYCT.png)
## ![Home down](https://i.imgur.com/l8JLR9N.png)

## Profile page
## ![Profile](https://i.imgur.com/VtJ5aWW.png)

It is the application that I have presented as the final project of the **Skylab Coders Academy** bootcamp.

It is based on an idea similar to Facebook and LinkedIn through which we can create a social network of friends in which to find who works in a particular sector. The idea is to find in your circle of friends who works in a certain sector and to be able to contact with him to request some kind of collaboration.

Through a quick registration form we can access the main page in which we will see a series of **friendship suggestions**, see your personal profile and add to our list of contacts.

Once it is our contact we can send you messages that you will receive in your inbox section.

After adding a friend, we will automatically suggest a series of contacts in the section '**Do You Know them?**' which shows possible friendships among those who have already added our contacts.

In the section '**Categories**' will be shown a list of all the trades of our contacts and clicking on any of them we can see how many of our friends have that same profession and get in touch with them.

Finally we have a search bar in which we can enter a type of work and see how many coincidences there are among our friends.

## Project links

- You can view project online
    http://takemyfriends.surge.sh/login

- or install client and server on your computer

#### - Install server and database
###### (YOU NEED AN ACCOUNT ON MONGOLAB AND SENGRID)

##### 1) Clone the back-end code link repository ([Take My Friends back-end code link](https://github.com/AgonisticKatai/take-my-friends-backend))

##### 2) Create a ```.env``` file on the root folder

##### 3) Enter the following information in the ```.env``` file

```
URL_DB=mongodb://<YOUR DB USER>:<YOUR DB PASSWORD>@ds<YOUR DB URL>.mlab.com:<YOUR DB PORT>/<YOUR DB NAME>

SECRET=XXXXXXXXXX

SENDGRID_API_KEY=XXXXXXXXXX
```

##### 4) Import the database
```
mongoimport -h ds<DB URL>.mlab.com:<DB PORT> -d <DB NAME> -c users -u <DB USER> -p <DB PASSWORD> --file <JSON FILE PATH>
```
###### (JSON file are in JSON_user_database folder)

##### 5) Run server
```
npm run dev
```

#### - Install REACT client

##### 1) Clone the front-end code link repository ([Take My Friends front-end code link](https://github.com/AgonisticKatai/take-my-friends))

##### 2) Run client
```
npm start
```
