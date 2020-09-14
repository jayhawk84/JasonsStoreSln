# JasonsStoreSln
Class Project to create a outdoor sports store that utilizes C# and a database within Visual Studio.
This is a student exercise, but the source code comes from author Adam Freeman, https://www.apress.com/gp/book/9781484254394.

### Console Commands to Build Project
```
    dotnet new globaljson --sdk-version 3.1.401 --output JasonsStoreSln/OutdoorProducts
    dotnet new web --no-https --output JasonsStoreSln/OutdoorProducts --framework netcoreapp3.1
    dotnet new sln -o JasonsStoreSln
    dotnet sln JasonsStoreSln add JasonsStoreSln/OutdoorProducts 
    dotnet new xunit -o JasonsStoreSln/OutdoorProducts.Tests --framework netcoreapp3.1
    dotnet sln JasonsStoreSln add JasonsStoreSln/OutdoorProducts.Tests 
    dotnet add JasonsStoreSln/OutdoorProducts.Tests reference JasonsStoreSln/OutdoorProducts 
```

### Figure 7-3 
![Figure 7-3](https://raw.githubusercontent.com/jayhawk84/JasonsStoreSln/master/JasonStoreMedia/JasonSportsFig7.3.PNG)

### Figure 7-4 
![Figure 7-4](https://raw.githubusercontent.com/jayhawk84/JasonsStoreSln/master/JasonStoreMedia/JasonSportsFig7.4.PNG)

### Last Screenshot 
![Last Screenshot](https://raw.githubusercontent.com/jayhawk84/JasonsStoreSln/master/JasonStoreMedia/JasonSportsFigLast.PNG)
