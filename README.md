**Take My Friends - Skylab Final Project**


It is the application that I have presented as the final project of the **Skylab Coders Academy** bootcamp.

It is based on an idea similar to Facebook and LinkedIn through which we can create a social network of friends in which to find who works in a particular sector. The idea is to find in your circle of friends who works in a certain sector and to be able to contact with him to request some kind of collaboration.

Through a quick registration form we can access the main page in which we will see a series of **friendship suggestions**, see your personal profile and add to our list of contacts.

Once it is our contact we can send you messages that you will receive in your inbox section.

After adding a friend, we will automatically suggest a series of contacts in the section '**Do You Know them?**' which shows possible friendships among those who have already added our contacts.

In the section '**Categories**' will be shown a list of all the trades of our contacts and clicking on any of them we can see how many of our friends have that same profession and get in touch with them.

Finally we have a search bar in which we can enter a type of work and see how many coincidences there are among our friends.



**Links to GitHub Project**

[Front-end code link](https://github.com/AgonisticKatai/take-my-friends)

[Back-end code link](https://github.com/AgonisticKatai/take-my-friends-backend)

[Surge - Take My Friends Project](http://takemyfriends.surge.sh/login)


**Screenshots**

**Run server** 
Clone the Back-End code link repository

Create a ```.env``` file
YOU NEED AN ACCOUNT ON MONGOLAB AND SENGRID
 
```
URL_DB=mongodb://<YOUR DB USER>:<YOUR DB PASSWORD>@ds<YOUR DB URL>.mlab.com:13136/<YOUR DB NAME>

SECRET=XXXXXXXXXX

SENDGRID_API_KEY=XXXXXXXXXX

googleClientID=XXXXXXXXXX
googleClientSecret=XXXXXXXXX

twitterClientID=XXXXXXXXXX
twitterClientSecret=XXXXXXXXX

facebookClientID=XXXXXXXXX
facebookClientSecret=XXXXXXXXXX

linkedinCliendID=XXXXXXXXX
linkedinClientSecret=XXXXXXXXXX
```
- mongoimport -h ds<DB URL>.mlab.com:13136 -d <DB NAME> -c users -u <DB USER> -p <DB PASSWORD> --file <JSON FILE PATH>
(JSON file are in TAKEMYFRIENDS/README_JSON folder)
- npm i
- npm run dev


**Run REACT client**
Clone the Front-End code link repository

- npm start

