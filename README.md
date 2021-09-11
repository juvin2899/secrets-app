# Secrets App

## Usage Requirements
* Node, npm and Mongodb should be installed on the PC.

## Installation

1. Download the zip file or clone by typing the following command in your terminal (If you have git installed)-
```
git clone https://github.com/juvin2899/secrets-app.git
```
2. Go into the root of the project in the terminal and type ```npm install``` to install the necessary modules-

## Usage Procedure
* Create a .env file in the root of the project.
* Write a mongodb uri to connect to.
* Get the Google OAuth client id and client secret from https://console.cloud.google.com/ after adding a new project and user.
* Also create a random string you would like to use as a local secret.
The .env file should look like this-

```
CLIENT_ID=your_client_id
CLIENT_SECRET=your_client_secret
LOCAL_SECRET=your_local_secret
MONGO_URI=your_mongo_db_uri
```

Type ```npm start``` in the terminal to run the app!

## License

[ISC](https://choosealicense.com/licenses/isc/)
