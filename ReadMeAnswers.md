## Self-Study/Essay Questions

Demonstrate your understanding of this Sprint's concepts by answering the following free-form questions. Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager.

- [ ] Mention two parts of Express that you learned about this week.

    I learned about Express' built in Body Parser Middleware, which is invoked by express.json(). 
    Serving to use Middleware, call the express server or app .use() and pass in the Middleware.

    I learned about how to set up an Express server by importing the Express npm package and setting a variable = express(). 
    Then setting the server.listen() to a specific port.

    Additionally I learned about setting up routers which deal with particular routes specified by the server. 
    In a way, routers are also types of middleware functions.

- [ ] Describe Middleware?

    Middleware is a function that gets executed in the order they are called.

    It acts as middle-men and they are used for things like data sanitation of incoming request data.

    Additionally they can be used for authentication.

- [ ] Describe a Resource?

    A resource is what is provided to the end user after hitting an endpoint.

    It could be a rendered snippet of html. or it could be a simple array of json objects. 

    Resources could be thought of as some type of data.

- [ ] What can the API return to help clients know if a request was successful?

    API's can return status codes such as 200-204 if there was a successful request.

- [ ] How can we partition our application into sub-applications?

    We can split up a backend API into an index.js file that handles server listening alone.

    Then we create a middleware.js file for all our middleware functions.

    We also can create router.js files for each router we create.

    The database files can also be separated out. Then the front end react app can be kept in a separate directory.
