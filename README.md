# Work Experience Management Web Service
This web service is created to manage work experiences, including details about previous workplaces, job titles, locations, start and end dates, and job descriptions. It is built using Node.js, Express, and a SQLite database.
## Assignment Overview:
The assignment requirements are as follows:
* Create a web service that handles CRUD (Create, Read, Update, Delete) operations for managing work experiences.
* Use Node.js, Express, and any relational database.
* The database should have at least four fields: id, companyname, jobtitle, location, startdate, enddate, and description.
* Data from the web service should be presented in JSON format.
* Implement CRUD operations using the HTTP verbs: GET, POST, PUT, and DELETE.
* Enable cross-origin requests to allow testing from other domains.
* Ensure well-commented code and publish the project to a GitHub repository.
* Include a README file in the repository documenting the web service and providing URI links for CRUD operations.
## Testing the Web Service:
You can test the web service using tools like Postman or by making HTTP requests from your client application. Here's how to perform each operation:

** Retrieve all work experiences: Send a GET request to http://localhost:8000/workexperiences to retrieve all work experiences stored in the database.

** Add a work experience: Send a POST request to http://localhost:8000/workexperiences with a JSON body containing the details of the new work experience.

** Update a work experience: Send a PUT request to http://localhost:8000/workexperiences/:id with the ID of the work experience to update, along with the updated data in the JSON body.

** Delete a work experience: Send a DELETE request to http://localhost:8000/workexperiences/:id with the ID of the work experience to delete.
    
