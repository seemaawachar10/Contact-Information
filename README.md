# Contact-Information
 An application for maintaining contact information.
 
 IDE : Visual studio 2015
 S/w and tools and framework used : 
 1. web api 2.0
 2. Entity framework 6.0.2
 3. Node js
 4. Angular 6
 
 Project Structure:
 Solution(ContactInformation) includes following projects:
 1. ContactInformationAPI
 2. ContactInformationAPI.Tests
 2. ContactInformationClient
 
 How to run project:
 1. Open project in visual studio.
 2. Go to web.config file of change the server name to your local db server name.
 3. Since code first approach of entity framework is used open Nuget Package manager console, chose default project and run command update-database. Databse will get created to your local db server
 4. Now set ContactInformationAPI as start up project and run it. Port used for it is 8181.
 5. Next run node.js command prompt as and admintrator. Open directory ....\ContactInformation\ContactInformationClient
 6. Next run command ng serve --o in node.js command prompt. Port used in 4200.
 7. Open http://localhost:4200/


Note: While hosting angular application on IIS we will only use dist folder files not src folder files. dist folder get generated when we execute ng build --prod on Node.js command prompt.
