CRUD Application Using ASP.NET MVC Core 2.0 and Mongo DB
	In this article, we understand the ASP.NET MVC Core 2.0 application with Mongo DB for database operation. Here I have been used “Product” entity for an example purpose.
Below are the Prerequisites for understanding and executing the ASP.NET VC Core 2.0 application.
1.	Microsoft Visual Studio 2017.
2.	Mongo DB. (https://docs.mongodb.com/getting-started/shell/tutorial/install-mongodb-on-windows/)
Below steps guide you to creating a new project.
1.	Start Visual Studio 2017.
2.	Click on File -> New -> Project.
 
3.	Click on “OK”.
 
Select “Empty” template and Click on “OK”.
4.	The new empty solution will be open in your window.
5.	In this article, we will talk about “DotNetCoreWithMongoApplication”. The Solution Explorer window for that project is defined as bellows
 
6.	For running the application, you first need to change the database connection string. Open “appsettings.json” file.
 
You need to be change the mongo connection as per your system.
7.	Mongo Database snapshot is as below.
 
8.	Right click on solution, and clean the solution.
9.	Right click on solution, and rebuild the solution.
10.	Run the application.

We have move forward to understand creation of Entity, its’ snapshot, Listing page, Creation page, Editing page and Deleting a record in below section.
“Product” Entity Section:
1.	Product.cs class
 
2.	Defining Product Context class



 
3.	Product Repository Interface And Class



 

 
Startup and configuration file Section:
 
 
Listing Screen Section
1.	Cshtml page
 
2.	Controller Action Method
 
3.	Repository Method
 
4.	Output screen
 

Creation/Modifying Section
1.	Cshtml page
 
2.	Create/Edit Controller Action Methods
 
3.	Repository Methods
 
 
4.	Output screen
 
 

Delete Section
1.	Cshtml Page
 
2.	Delete Controller Action Methods
 
3.	Repository Methods
 
 
4.	Output screen
 


