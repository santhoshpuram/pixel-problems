# PixelProblems
This is a website for a sample coding website that tracks user progress and also has authentication requests for user logins and verifications.

# Step for successfull firebase connection

Open Google Cloud Console -> Firebase -> Create/Open Project -> Configure settings -> Download Json

Put the json as serviceAccountKey.json in the folder with you node.js file.

Our index.js is the server code. 

>> npm install -g firebase-tools
# install all other packages like express and more
>> npm install -g <packages> 

login to firebase account with the key.

>> firebase login

This will take you to authorization link. Login to your account.

>> firebase init

Asks options to select i selected hosting.

>> firebase deploy

Deployed successfully