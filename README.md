# Secrets Node.js App
This project aims to have crud with MongoDB + Authentication with Passport (email, Google OAuth2.0, and Facebook).

inorder to setup this project to run locally:

1- change directory to project's folder `cd <DIRECTORY_OF_THE_PROJECT>` 

2- run the `npm i` command to install required modules.

3- Setup/Create an environment file `.env`.

4- define required settings inside the `.env` file:
```
SECRET=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
FACEBOOK_APP_ID=
FACEBOOK_APP_SECRET=
FACEBOOK_CALLBACK_URL=http://localhost:3000/auth/facebook/secrets
MONGO_URL=
```
You have to get Goodle Client ID and Secret from google developer console, and Facebook App ID and Secret from Facebook developer dashboard.

5- run `node app.js` to run the server and respectively, the app. 

*NOTE: if you have Nodemon you can run it by typing `nodemon app.js` for live reloading.

Enjoy!
