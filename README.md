# ecommerce-shop

This repository contains a C# ecommerce store built using the .NET Framework 4.8.

Prerequisites
To run the ecommerce store locally, ensure that you have the following prerequisites installed:

.NET Framework 4.8
Visual Studio 2019 (or any compatible version)

Getting Started
To get started with the ecommerce store, follow these steps:

Clone the repository: git clone this repository
Open the solution in Visual Studio.
Build the solution to restore dependencies.
Make sure you have connection string set up correctly both in .DataAccess.SQL and .WebUi projects to connect to your local enviroment.
In project .DataAccess.SQL you will need to update nu-get EntityFramework package.
In package manager console run command Update-Database to restore migrations to your local database.
Set the .WebUI project as the startup project.
Run the application using the debugger or by pressing F5.

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and commit them.
Push your changes to your fork.
Submit a pull request to the main repository.
Please ensure that your code follows the existing coding style and conventions, and include appropriate tests for your changes.

License
The ecommerce store is released under the MIT License. You are free to use, modify, and distribute the codebase as per the terms of the license.
