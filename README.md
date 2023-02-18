# vue-app
-------------------------------------------------------------------------------
this app is a demo ecommerce application using MEVN technology
--------------------------------------------------------------------------
>> to run the demo application 
>> clone the repo on your local
>> 2 folders will be there one is shop-frontend and other is shop-backend
>> shop-frontend contains a code of frontend using VUe
>> shop-backend contains a code of backend using nodejs, Mongodb local instanc
>>  need to install vue latest version
>>  install vue-cli latest version
>>  Install Mongodb mongoshell, nodejs latest version
>> Not used Mongo Atlas as need to share the password and username in this


>> to get the data, first create a db in mongodb in your local machine
>> using mongoshell use the commands like :
>> use vue-db to create a database in your local
>> then create collections :
>> db.products.insertMany([data has to be put in one by one from the file fakedata.js products array individual object as we can have some console error while putting all the data together])
>> db.users.insertOne({userId: 12345, cartItems: ["123", "345", "567"]})
>> after creating these collections you will get all the data which is required for the application in your local and then you can run the app using local instance of Mongodb and mongoshell 
>> Run the command "npm run serve by going into the backend folder shop-backend
>>Application will be running on the port 8085

Ensure all the required packages are installed using npm install in both frontend and backend

