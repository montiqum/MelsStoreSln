# MelsStoreSln


dotnet new globaljson --sdk-version 5.0.201 --output MelsStoreSln/OutdoorProducts
dotnet new web --no-https --output MelsStoreSln/OutdoorProducts --framework net5.0
dotnet new sln -o MelsStoreSln
dotnet sln MelsStoreSln add MelsStoreSln/OutdoorProducts 
dotnet new xunit -o MelsStoreSln/OutdoorProducts.Tests --framework net5.0
dotnet sln MelsStoreSln add MelsStoreSln/OutdoorProducts.Tests 
dotnet add MelsStoreSln/OutdoorProducts.Tests reference MelsStoreSln/OutdoorProducts
