# Class 12

## Status Codes Based On REST Methods

1. **In your own words, describe what each group of status code represents:**

 - 100’s = Informational status codes.

 - 200’s = Success codes.

 - 300’s = Redirection codes. Tells the client that something they are trying to reach isn't available.

 - 400’s = Client error codes. Invalid requests and such.

 - 500’s = Server error codes.

2. **What is a status code 202?:**Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future.

3. **What is a status code 308?:** This tells the client to use another URL to access the resource and not use the current URL anymore.

4. **What code would you use if an update didn’t return data to a client?:**204 No Content

5. **What code would you use if a resource used to exist but no longer does?:**410 Gone

6. **What is the ‘Forbidden’ status code?:** 403 Forbidden 

## Build A REST API With Node.js, Express, & MongoDB - Quick

1. **Why do we need to pull our MongoDB database string out of our server and put it into our .env?:**Without a connection string, we cannot connect to the database server, we need a connection string to connect the database server.

2. **What is middleware?:**A function that will have all the access for requesting an object, responding to an object, and moving to the next middleware function in the application request-response cycle.

3. **What does app.use(express.json()) do?:**Adds a new middleware to the app.

4. **What does the /:id mean in a route?:**It's a variable used by Express.

5. **What is the difference between PUT and PATCH?:**PUT is a technique of altering resources when the client transmits data that revamps the whole resoruce. PATCH is a technique for transforming the resources when the client transmits partial data that will be updated without changing the whole data.

6. **How do you make a default value in a schema?:** Example: `{ type: String, default: '' }.`

7. **What does a 500 error status code mean?:** It means that the server encountered an unexpected condition that prevented it from fulfilling the request.

8. **What is the difference between a status 200 and a status 201?:**200: “Everything is OK.” This is the code that is delivered when a web page or resource acts exactly the way it's expected to. 201: “Created.” The server has fulfilled the browser's request, and as a result, has created a new resource.