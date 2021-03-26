# MelsStoreSln

SportsStore: A Real Application
The store in the demo is called "Mel's Store Solution." The product inventory will contain items typically found in outdoor, activity and gaming stores. This is a student exercise on building web applications from Adam Freeman's, 8th Edition Pro ASP.NET Core 3 available at the URL:
https://www.apress.com/gp/book/9781484254394.

### :trident: Creating the Projects and Solution


    dotnet new globaljson --sdk-version 5.0.201 --output MelsStoreSln/OutdoorProducts
    dotnet new web --no-https --output MelsStoreSln/OutdoorProducts --framework net5.0
    dotnet new sln -o MelsStoreSln
    dotnet sln MelsStoreSln add MelsStoreSln/OutdoorProducts 
    dotnet new xunit -o MelsStoreSln/OutdoorProducts.Tests --framework net5.0
    dotnet sln MelsStoreSln add MelsStoreSln/OutdoorProducts.Tests 
    dotnet add MelsStoreSln/OutdoorProducts.Tests reference MelsStoreSln/OutdoorProducts


### :trident: Startup

![Startup Screenshot](https://github.com/montiqum/MelsStoreSln/blob/master/Part1.JPG)

### :trident: Display a List of Products

![List Screenshot](https://github.com/montiqum/MelsStoreSln/blob/master/Part2.JPG)

### :trident: Page Links

![Page Links Screenshot](https://github.com/montiqum/MelsStoreSln/blob/master/Part3.JPG)

### :trident: Displaying Page Links

![Displaying Page Links Screenshot](https://github.com/montiqum/MelsStoreSln/blob/master/Part4.JPG)

### :trident: Improving URLs

![Improving URLs Screenshot](https://github.com/montiqum/MelsStoreSln/blob/master/Part5.JPG)


### :trident: Using Bootstrap and Pagination

![Bootstrap Screenshot](https://github.com/montiqum/MelsStoreSln/blob/master/Part6.JPG)
