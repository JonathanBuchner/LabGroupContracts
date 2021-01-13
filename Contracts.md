# Project Get Excited People
---------------------------------
## We are deployed on heroku

https://get-excited-people.herokuapp.com/

---------------------------------
## Web Application

The app we built is a textbot called Get Excited People and it will allow users to create their own library of inspiring quotes, songs, videoes or pictures. And then the textbot will automatically picked a random content from their library and send it to the user once a day.

Users have access to read, create, update, and delete the contents from their own library by sending commands at the inspirations channel in Slack me. The app checks the user id to make sure they only have access to their own database.

---------------------------------

## Tools Used
Visual Studio Code
WebStorm

- NodeJS
- Express 


---------------------------------

## Getting Started

Clone this repository to your local machine.
```
$ git clone https://github.com/ginapult-401-advanced-javascript/getexcitedpeople.git
```
Once downloaded, you can either use the dotnet CLI utilities or Visual Studio 2017 (or greater) to build the web application.
```
cd YourRepo/YourProject
`npm i`
```
Install all dependencies needed for the project.
```
Database
```
Create a .env file and within the file, add a variable called MONGODB_URI and store your mongodb URI in there.
```
cd YourRepo/YourProject
npm start
```

---------------------------------

## Usage

### Create an inspiring content and save it to the database
![Create command](/assets/create-command.PNG)

### Update a content in the library with its id and new content
![Update command](/assets/update-command.PNG)

### Delete a content in the library with its id
![Delete command](/assets/delete-command.PNG)

### Viewing a random content that is picked from the library
![Read command](/assets/read-command.PNG)

### Viewing the instructions for using the app
![Instructions](/assets/instructions.PNG)

---------------------------
## Data Model

### Overall Project Schema

There are two data schema within the app, one is for user and another one is for the content that is saved in the database.
![User Schema](/assets/user-schema.PNG)
![Content Schema](/assets/content-schema.PNG)

---------------------------


## Authors
Austin Hedeen
Gina Pultorak
Leyla Li
Lyndsey Thomas

------------------------------

