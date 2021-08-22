# CS-465-Full-Stack-Development-with-MEAN Q&A Readme

Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
    
    When we created this application, we used may different applications to create the full stack project.  Thef first development was Express.  This is designed to be very rich and capture the eyes of the user that is looking at the website.  The basic website was created with this.  Then we included JavaScript for the different trips in the application.  Each trip was formatted using JSON to read the different key characteristics of each individual trip.  The JSON was parsed and transfered into JavaScript objects that would be placed on the web application.  On the backend, we created a single-page application using angular.  The design of this page wasn't to be as eye-catching, but to make administrative moves that would be seen by the user on the front facing website.  The SPA could add and update different travel packages.
  
Why did the backend use a NoSQL MongoDB database?
    
    We used a NoSQL database so that each trip could be added with niminal information.  Then, when a trip was added, we could edit the information to create a fuller trip experience.  If we used a MySQL database, then all fields would have to be populated to be placed into the database.  
    
How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
    
    JavaScript is a scripting language that supports objects and functional programming styles.  JSON is the way that we write the objects in MongoDB and how it is stored in the database.  Each field has a matching entry.  When we place the JavaScript item into MongoDB, we strinify the object into JSON.  When we pull the JSON object from the database, we parse it and turn it back into the JavaScript item to be used on our web application.  
    
Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.
    
    One of the instances where we refactored the code was with the /travel page from the website.  The original setup was for the project to redirect the user to static HTML pages.  We changed the code so that the user was sent to a dynamic page that could be changed by the site owner.  A second instance was creating the header and footer for the /travel page.  It was code that was repaeted for each static page, which was the menu at the top and bottom.  Rather than keeping copied code for 6 different pages, we refactored the code so that each page calls the headers and footers rather than explicit code in each page.
    
Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.
    
    The application that we tested the endpoints and security for the API was postman.  We can use different calls to the API like GET and POST to see the information retrieved from the API.  Postman displays the results accurately and in a format that can be read easily.  This was also used to secure the endpoints.  Where we would have to pass a valid user name and password to retrieve a token to be used to access the API functionality.
    
How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
    
    This course has helped me understand the building of a web application.  I had never created a full experience for a user, all previous classes were individual functions, but this course put them all together.  I am sure that I will need more practice with this, but this was a great start.  I had an enjoyable time learning about the different aspects of the web application building.
