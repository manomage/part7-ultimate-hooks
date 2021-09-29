# part7-ultimate-hooks
We are refactoring this app using custom hooks. This app displays notes and phone numbers fetched from a backend server.

However, we noticed that the same code responsible for fetching notes from the backend could be reused in the blog post application. Indeed, only the baseUrl differs. As a result, we extracted the code for communicating with a backend server into its own useResource hook.

# Start the application
To start an application, do the following :

# Install dependencies
$ npm install
# Start the JSON Server
$ npm run server
# On another terminal, start the application
$ npm start
You can then access the app on : http://localhost:3000/

You can also see the content of the JSON Server by heading to:

http://localhost:3005/notes

http://localhost:3005/persons
 
