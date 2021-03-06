# MeanBoilerplate

## Steps to run

### 1) Start the MongoDB daemon process
Run `mongod` to start the MongoDB daemon process. Test a connection by opening another terminal and running `mongo`. 

### 2) Build the project
Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

### 3) Start the node server
Run `node server` to start the nodejs server. Navigate to `http://localhost:3000/` to view the index.html.

If you want to check out the API endpoint, visit `http://localhost:3000/api/users`

## Information
The MongoDB database and collection used is set within `/server/routes/api.js`. Currently, a `users` collection within a `mean` database is searched for. This is also where the API methods are defined to fetch records from the MongoDB connection. 

The `Data Service` is what accesses the API endpoint and maps the response to a JSON object to be accessed within the `App Component`. 

## Credits
This boilerplate was based from https://www.youtube.com/watch?v=Tw-rskOmcMM
