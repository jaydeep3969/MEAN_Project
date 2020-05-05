# MEAN-POC
Beginner Level MEAN POC
- Task Information in /Task Information.docx
- Outputs are in /Outputs

**Employee Management**
> Backend : Node.js                 
> Database : MongoDB               
> Frontend : Angular7 | Primeng           

-------------------------------------------------------------------------------------------
API in Node.js (API-Folder)
-------------------------------------------------------------------------------------------
- /app/controllers/_.controller.js 
	-> To handle the http request 
- /app/routes/_.routes.js 
	-> To route the http request to corresponding controller
- /models/_.model.js 
	-> To define the models to be used as an object
- /database.js 
	-> To connect and interact with the MongoDB using mongoose
- /server.js 
	-> To host the application on a server using Express having configurations of routes and database connection object
	
	
	
-------------------------------------------------------------------------------------------
FrontEnd in Angular (EmployeeManagement-Folder)
-------------------------------------------------------------------------------------------

- /src/app/\_\_components__ 
	-> All defined components
- /src/models/__.ts
	-> To map the objects to be used to interact with API
- /src/service/__.service.ts
	-> Services to be used to interact with API
