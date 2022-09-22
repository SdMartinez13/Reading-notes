# Express REST API

## Readings

[Review ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

 1. Classes are a template for creating ____.

    * ***Objects***

 2. Can a class declaration be hoisted?

    * No they can't

 3. How would you describe a constructor and contextual “this” to a non-technical friend?

    * 

[Using Express Routing](https://expressjs.com/en/guide/routing.html)

  1. Within Express, what does routing refer to?

      * how an application's endpoints respond to client requests.

  2. What is the difference between a route path and a route method?

      * the route path defines the endpoint that the request can be made to. The route method is derived from one of the HTTP methods and is attached to the instance of the express class.

  3. When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

      * With multiple callback functions, it is important to provide next as an argument to the callback function and then call next() within the body of the function to hand off control to the next callback.

[Express Routing](https://scotch.io/tutorials/learn-to-use-the-new-router-in-expressjs-4)

  1. What is an Express Router?

      * its an express application that provides APIs like, `.use`, `.get`, `.param`, and `route`.

  2. By what mean do we initialize express.Router() in an express server?

      * call an instance of the `express.Router()`, apply routes to it, and then tell our app to use thoose routes

  3. What do we use route middleware for?

      * to do something before a request is processed