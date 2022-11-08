# Get YouTube Subscribers - Backend Capstone Project by Sri Srinivasan S and Murtuza Bharmal

BACKEND CAPSTONE PROJECT - **Team of Sri Srinivasan S and Murtuza Bharmal** - Cohort Satoshi

Member 1

Name - Sri Srinivasan S
Email - srini624618@gmail.com
Contribution - 
1.Created the http GET request to Display the written message on the homepage to the client.
2.Created the http GET request to get a list of all users stored in the database.
3.Created the http GET request to get a list of users with only name and subscribedChannel field.

Member 2 

Name - Murtuza Bharmal
Email - mbharmal.info@gmail.com
Contribution - 
1.Created the http GET request to get a particular user with its id.
2.Wrote and formatted Github README description in Markdown language.
3.Made the project demo video and published it on Youtube.

**Short summary of the Back-end Capstone Project :**

Created an application using MongoDB , NodeJS and expressjs to get the array of subscribers from the data present in MongoDB.

=> Initially, all the dependencies and node modules are installed using the “npm install” command. 

=> Then, run the “node src/createDatabase.js” to store the dummy data from data.js file to your local MongoDB server in your computer. 

=> At last, run “node src/index.js” or “npm start” to start the backend server.

We’ve used 3 different main http requests for Searching the data in the database.

1. GET http://localhost:3000/ =>  which is used to Display the written message on the homepage to the client.

2. GET http://localhost:3000/subscribers => request is used to get an array of all subscribers from the database.

3. GET http://localhost:3000/subscribers/names => request is used to get an array of all subscribers with only name and subscribedChannel fields from the database.

4. GET http://localhost:3000/subscribers/:id => request is used to get a particular user from the database,client need to replace the  :id is replaced by the user’s id in the url to get particular data from the databases.