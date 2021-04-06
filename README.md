# MelsStoreSln

SportsStore: A Real Application
The store in the demo is called "Mel's Store Solution." The product inventory will contain items typically found in outdoor, activity and gaming stores. This is a student exercise on building web applications from Adam Freeman's, 8th Edition Pro ASP.NET Core 3 available at the URL:
https://www.apress.com/gp/book/9781484254394.

## Chapter 7

### :trident: Creating the Projects and Solution


    dotnet new globaljson --sdk-version 5.0.201 --output MelsStoreSln/OutdoorProducts
    dotnet new web --no-https --output MelsStoreSln/OutdoorProducts --framework net5.0
    dotnet new sln -o MelsStoreSln
    dotnet sln MelsStoreSln add MelsStoreSln/OutdoorProducts 
    dotnet new xunit -o MelsStoreSln/OutdoorProducts.Tests --framework net5.0
    dotnet sln MelsStoreSln add MelsStoreSln/OutdoorProducts.Tests 
    dotnet add MelsStoreSln/OutdoorProducts.Tests reference MelsStoreSln/OutdoorProducts


### :trident: Startup

![Startup Screenshot](https://github.com/montiqum/MelsStoreSln/blob/master/Images/Part1.JPG)

### :trident: Display a List of Products

![List Screenshot](https://github.com/montiqum/MelsStoreSln/blob/master/Images/Part2.JPG)

### :trident: Page Links

![Page Links Screenshot](https://github.com/montiqum/MelsStoreSln/blob/master/Images/Part3.JPG)

### :trident: Displaying Page Links

![Displaying Page Links Screenshot](https://github.com/montiqum/MelsStoreSln/blob/master/Images/Part4.JPG)

### :trident: Improving URLs

![Improving URLs Screenshot](https://github.com/montiqum/MelsStoreSln/blob/master/Images/Part5.JPG)


### :trident: Using Bootstrap and Pagination

![Bootstrap Screenshot](https://github.com/montiqum/MelsStoreSln/blob/master/Images/Part6.JPG)

****What is Entity Framework?****

Entity Framework is an open-source ORM framework for .NET applications supported by Microsoft. It enables developers to work with data using objects of domain specific classes without focusing on the underlying database tables and columns where this data is stored. With the Entity Framework, developers can work at a higher level of abstraction when they deal with data, and can create and maintain data-oriented applications with less code compared with traditional applications.

****What is a Connection String?****

The connection string contains the information that the provider need to know to be able to establish a connection to the database or the data file. There are some basic rules on how to format the information needed for the connection to take place. The way we represent the configuration values inside of the connection string. As it is a string, there are no data types, it's all string values but they have to be correctly coded so the drivers can read it properly.

****What is a Database Context?****

A DbContext instance represents a combination of the Unit Of Work and Repository patterns such that it can be used to query from a database and group together changes that will then be written back to the store as a unit. DbContext is an important class in Entity Framework API. It is a bridge between your domain or entity classes and the database. DbContext is the primary class that is responsible for interacting with the database.

****What is a Model Repository?****

The Model repository is a relational database that stores the metadata for projects and folders. Connect to the Model repository to create and edit physical data objects, mapping, profiles, and other objects. Include objects in an application, and then deploy the application to make the objects available for access by end users and third-party tools.

****Migration vs Scaffolding?****

Migration is a way to keep the database schema in sync with the EF Core model by preserving data. EF Core migrations are a set of commands which you can execute in NuGet Package Manager Console or in dotnet Command Line Interface (CLI).

Scaffolding is a technique used by many MVC frameworks like ASP.NET MVC, to generate code for basic CRUD (create, read, update, and delete) operations against your database effectively. Further you can edit or customize this auto generated code according to your need. Scaffolding consists of page templates, entity page templates, field page templates, and filter templates. These templates are called Scaffold templates and allow you to quickly build a functional data-driven Website.

****Seeding the database****

Database seeding is the initial seeding of a database with data. Seeding a database is a process in which an initial set of data is provided to a database when it is being installed. It is especially useful when we want to populate the database with data we want to develop in future.


## Chapter 8

### :trident: Filter
![Filter Screenshot](https://github.com/montiqum/MelsStoreSln/blob/master/Images/Chap%208%20Part%202.JPG)

### :trident: Highlight

![Layout Screenshot](https://github.com/montiqum/MelsStoreSln/blob/master/Images/Chap%208%20Part%206.JPG)

### :trident: Add To Cart

![Add To Cart Screenshot](https://github.com/montiqum/MelsStoreSln/blob/master/Images/Chap%208%20Part%208.JPG)


### :trident: Cart

![Cart Screenshot](https://github.com/montiqum/MelsStoreSln/blob/master/Images/Chap%208%20Shopping%20Cart.JPG)


### :trident: Tests

![Tests Screenshot](https://github.com/montiqum/MelsStoreSln/blob/master/Images/Tests.JPG)

[Back To Top](https://github.com/montiqum/MelsStoreSln#melsstoresln)
