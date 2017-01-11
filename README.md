# Command-Line-API
A simple command Line API
// This is a command line driven Google API application that enables the aunthenticated user have access to remote/secret files//
// Steps on running this in command prompt//
step 1 make sure that the libraries npm install googleapis --save
npm install google-auth-library --save have been installed on the system.
step2  Run the script node quickstart.js from your node js command line
a. a prompt will require you to authorise access.
step 3: browse to the provided URL on your web broswer
step 4: you will be required to log in with your google account for authorization
step 5: you should click the accept button
step 6: A code will be generated, which you should paste in your command line and press enter
step 7:the resultant files willbe displayed.

NB: There are cases were an error is generated after pressing enter, this means that  the google API has not authenticated the request
  you are excepted to run the command again above and wait for a few minutes.
  Authorization information is stored on the file system, so subsequent executions will not prompt for authorization.
