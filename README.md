# CS465-FullStack-1
## Architecture
### Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
<p>This application was developed utilizing a MEAN stack. A MEAN stack is developed using four key components to build a JavaScript based web application. A MEAN stack utilizes MongoDB 
for its database, Express as the application framework for Node.js, Angular for creating the framework of the interface for the application and lastly Node.js is the software platform 
that will allow the creation of the web server and allows us to build the web application on top of it. The administrator side of the application or the API, was built utilizing MongoDB, 
Express and Node.js. The customer facing side is a single page application built using the Angular framework. This will essentially create a collection of structured URLs that will return 
specific data when called.

The front end was developed utilizing Express HTML that was later converted to handelbars. Handlebars is a templating language that uses a template and an input object to generate HTML.
Javascript is a frontend and backend coding language that is used to add dynamic elements to the webpage. This was used to pull trip information from the MongoDB database so that the page
can change dynamically based on user interaction. A single-page application is a website that delivers full content on the inital page load. An SPA does not require a page refresh when the user
interacts with the webpage like HTML would. This is particularlly useful in giving the website a local/native application feel when interacting with the applicaiton itself. </p>

### Why did the backend use a NoSQL MongoDB database?
<p>The backend used a NoSQL MongoDB database because of its ease of modifying schema based on scaling and functionality changes, as well as
the ability to rapidly scale horizontally because of its non-relational nature of the database.</p>

## Functionality
### How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
<p>JSON allows a standardized way to format object data using key value pairs that can be easily read by Javascript to form it into Javascript objects. This makes it easy for Javascript to take the 
data and form it into a object in the Javascript language. This ties frontend and backend development together by creating a way for objects to be stored on the backend and used in different ways
based on what the frontend is requesting.</p>

### Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.
<p>An instance that code was refactored to improve functionality and efficiency is that the trip card versus trip list components. Having two seperate components that render the same information
is inefficient, but having the each trip being rendered separately but part of the whole works better in the overall functionality of the site. Reusing UI components is benificial because it
decreases overall size of an application, makes the development process quicker, and decreases the chance of errors and vulnerabilities introduced into the system (provided the component is
secure).</p>

## Testing
### Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.
<p>There are multiple ways of testing endpoints. The first is by just going to the localhost web address for the API endpoint. Other methods include using an API platform such as postman or insomnia that tests HTTP requests. These tools are also ideal as you can pass paramaters, view headers and body and view elements such as bearer tokens. You can also use the developer tools to view the html, headrs and tokens.</p>

## Reflection
### How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
<p>This course is very much relevant to my career asperations. The methods and techniques learned in this course are very applicable in a professional environment. Using tools like git for version control and knowing how to checkout, create new branches commit and push those changes will be very valuable skills.</p>
