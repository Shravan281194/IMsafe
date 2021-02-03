# IMsafe

Project name:  This repository comprises the source code we use to generate "IMsafe" website.

Authors: MP-18 - Conquerors

---
Softwares to Install
---
Visual Studio 2019 - https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver15

SQL Server Management Studio - https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver15

---
Setup
---
* Clone the repository into your system - https://github.com/Shravan281194/IMsafe

* Open the solution in Visual Studio by navigating to ProjectLocation\IMsafe\IMsafe.sln

* Use the package manager console window by typing it at the top of the visual studio window under 'Search Visual Studio'
![screenshot](IMsafe/Screenshots/searchpmc.png)

* Within the package manager console, type Enable-Migrations to enable migrations for code first database
![screenshot](IMsafe/Screenshots/pmc.PNG)

* Now in order to create the database on your system, type Update-Database -Verbose in the package manager console. 

* In order to add data into the database, the csv files under DataWrangling folder would be utilized. These files need to be imported into the database using the import flat files option in SQL Server Management Studio. Follow the steps mentioned here for each csv file : https://docs.microsoft.com/en-us/sql/integration-services/import-export-data/connect-to-a-flat-file-data-source-sql-server-import-and-export-wizard?view=sql-server-ver15

* Once the database is setup, you can simply run the application by clicking on the IIS Express button with a run icon besides it on the 2nd most top row of the visual studio window.

![screenshot](IMsafe/Screenshots/Run.PNG)

Enjoy the application! Let's make immigration transition easier!
