Architecture

    Compare and contrast the types of frontend development you used in your full stack project, including Express HTML,
    JavaScript, and the single-page application (SPA).

For the frontend customer side we developed using Express a node based framework for this project. We 
also implmented the use of handlebars to create templates and render in HTML. We used Angular to create the 
SPA. A SPA works by first taking the HTTP request sent by the user to the site and responds with everything 
needed to render the webpage and its functions. This was used to allow the client to fully render the page without
the need to stay connected to the network and also was more efficent on server usage. 
    
    Why did the backend use a NoSQL MongoDB database?

The NoSQL mongodatabase was used because it provided better functionality, speed and structure. It also
works well with Mean apllications and can be used with both JSON and JavaScript. 

Functionality

    How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?

Json is a data transmission format while Javascript is a programming language. A HTTP request will contain JSON data
that allows for the API request to be recieved and to be understood by the compiler. JSON is also used for the back 
end when the request is received, and a response is sent and front-end when a user makes a HTTP request and .
    
    Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, 
    and name the benefits that come from reusable user interface (UI) components.

One way that I lowered the chance that errors could occur was through the implementation of a reusable UI. This
helped by keeping the design flow simple and allowed for effective development. 

Testing

    Methods for request and retrieval necessitate various types of API testing of endpoints, 
    in addition to the difficulties of testing with added layers of security. 
    Explain your understanding of methods, endpoints, and security in a full stack application.

My understanding of how our testing was suppose to be performed was through error codes in the console log
and the log messages. The codes were there to tell us what failed while the log told us why it failed. We used
API methods to check and verify the user was logged in correctly. All of these methods and endpoints provide
calls to the database. The PUT issues an edit call, the POST issues a create call, the GET issues a read call, 
and the DELETE issues a delete call.

Reflection

    How has this course helped you in reaching your professional goals? What skills have you learned, developed, 
    or mastered in this course to help you become a more marketable candidate in your career field?

One way theis course has helped in reaching a professional goal is that I am one step closer to getting my degree
that will help me advance from my current postion. It also gave me more tools to assist in my daily duties at my
company. I think the most helpful skill that will help with marketability is the work I did with the integration
and administration of the NoSQL database.
