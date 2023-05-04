# Capstone VERMILLION

# IOD - SOFTWARE ENGINEERING COURSE FEBRURARY 2023

Visual Studio Code: https://code.visualstudio.com
Node.js/npm: https://nodejs.org/en
MongoDB Compass: https://www.mongodb.com/products/compass

Deployment must be done by cloning the git repository and running the files locally on the host's PC. 

Files can be found on my GitHub: https://github.com/Dissilence/capstone
Front end: https://github.com/Dissilence/capstone/tree/master/frontend
Back end: https://github.com/Dissilence/capstone/tree/master/backend

Clone the repo and pull them from git

Open a terminal and run the command: cd frontend, followed by: npm install
Open a new terminal and run the command: cd backend, followed by: npm install
Create 2 .env files, the first one must be at the highest level of code and must have the following: 

JWT_SECRET=
PAYPAL_CLIENT_ID=
MONGODB_URI=

The 2nd .env file must be in the back end folder at the highest level, and must include the following code: 

JWT_SECRET=
PAYPAL_CLIENT_ID=
MONGODB_URI=
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_URL=
CLOUDINARY_API_SECRET=

to be filled in with your own data, you can get the paypal ID by going to development.paypal.com and creating a sandbox account and getting access to the link
for payment. the JWT secret should be something of your choosing, mongo URI should be the uri to connect to ur mongo db back end. cloudiary api key and url
can be used by signing up for cloudinary and going to your account and copy past the key and url. connect to the mongo db (reccomend that you use mongodb compass to connect). 
there should be no issue running the files and deploying the code locally.

The page will reload when you make changes. if there are errors, it will appear in the console.


