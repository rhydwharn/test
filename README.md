# Trivago Portal Solution

The portal solution helps the organization to at all times know all on-going projects, due-date, number of personnel assigned to projects, amongst other functions.

The portal solution is built with ASP.NET using Microsoft SQL database as the database engine.

# Pre-requisites for accessing the application
1.  Visual Studio 2017
2.  Micsrosoft SQL Server 2014

# How to Import Database Content to Local MS-SQL Server.
Download the application, extract the zip content. There are two (2) MSSQL files, which are;
(1) 01_Create.sql
(2) 02_Seed.sql

* Launch Microsoft SQL Management Studio
* Create Database - OSPortal
* Select create new script, setting destination database as OSPortal
* Copy the content of the 01_Create.sql script to the blank script page
* Execute the script to create tables
* Re-itrate step 4 for 02_Seed.sql to import content to the created table.

# How to Launch the application on Visual Studio
In the extracted file, double click on Trv.OS.Portal.sln
In the solution explorer, right-click on Trv.OS.Portal.Web then click on "Set as Starup project"
Right click on References on Trv.OS.Portal.Web
Click on Add Reference
In the dilaog box, click on Browse
Go to directory of the extracted files, Packages, Kendo.Mvc
Clikc on Kendo.Mvc.dll to add the Kendo library to the project
Build and Compile the program

# Automated Test

I was unable to attend to the Automated test suite for the regressional testing due to un-forseen circumstanece as at the deadline of the submission time-out.
