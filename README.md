# Building a simple CRM using node.js and mongoDB. 

# NPM Packages used and Why
# -------------------------


# Express: This a node js framework, this is used to simplify designing and budiling web applications easily and quickly.
# Using Express, we simplify API development by abstracting away the boilerplate needed to set up a server, which makes development faster, more readable and simpler. You can spin up a prototype API in seconds and a couple of lines of code.
# Nodemon: This package is ued to create a live server. It is a utility that will monitor for any changes in your source and automatically restart your server. Perfect for rapid development.

# swagger-ui-express: For serving the swagger user interface in our API.

# [body-parser] (https://www.npmjs.com/package/body-parser): helps us decode the body from an HTTP request

# cross-origin resource sharing: s a mechanism that allows restricted resources on a web page to be requested from another domain outside the domain from which the first resource was served. This will add CORS to the header of the request.
# -------------------------

# Files and Code Structure
   # src
      ├── app.js			app entry point
      ├── /api			controller layer: api routes
      ├── /config			config settings, env variables
      ├── /services		service layer: business logic
      ├── /models			data access layer: database models	
      └── /test               test suites

# References

# https://oai.github.io/Documentation/introduction.html
# https://swagger.io/blog/api-strategy/difference-between-swagger-and-openapi/

# https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction
# https://www.npmjs.com/package/swagger-ui-express
