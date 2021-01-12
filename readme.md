# HelloWorld
ASP.NET can be used to create a multitude of different web applications.

## How was this project created?
This project was created by running the following at the command line:
```
dotnet new webApp -o myWebApp --no-https
```

The `dotnet new` command indicates something is to be created.
- The `webApp` parameter is selecting the template to use
- The `-o` parameter created a directory named `myWebApp` where the app is stored
- The `--no-https` flag specifies not to enable HTTPS

## What files were created?
- Startup.cs contains all the settings and configurations.
- The myWebApp/Pages directory contains some example web pages for the application.
- myWebApp.csproj defines what libraries are referenced etc.

## How to run a .NET project?
```
dotnet run
```