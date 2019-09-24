# MEAN_Project
Beginner Level MEAN Task

| ++++++ Employee Management ++++++ |
|___________________________________|
|                                   |
|- Backend : Node.js                | 
|- Database : MongoDB               |
|- Frontend : Angular7              |
|___________________________________|

-------------------------------------------------------------------------------------------
API in Node.js (API-Folder)
-------------------------------------------------------------------------------------------
/app/controllers/_.controller.js 
	-> To handle the http request 
/app/routes/_.routes.js 
	-> To route the http request to corresponding controller
/models/_.model.js 
	-> To define the models to be used as an object
/database.js 
	-> To connect and interact with the MongoDB using mongoose
/server.js 
	-> To host the application on a server using Express having configurations of routes and database connection object
	
	
	
-------------------------------------------------------------------------------------------
FrontEnd in Angualar (EmployeeManagement-Folder)
-------------------------------------------------------------------------------------------
/src
/app/__components__ 
	-> All defined components
/models/__.ts
	-> To map the objects to be used to interact with API
/service/__.service.ts
	-> Services to be used to interact with API
