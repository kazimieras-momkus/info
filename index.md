# Some useful info

## Asp.NET Core 3.1 MVC

### Update Bootstrap libraries to the latest version:
1. Right click on a project name and choose Add -> "Client-Side Library.."
2. Provider: "unpkg".
3. Library: start typing "bootstrap" and then full name appears choose it.
4. Choose specific files: select "dist" catalog from Files.
5. Install

#### While developing you can get page error codes instead of the blank pages by adding the app.UseStatusCodePages() method inside the Startup.cs Confiure() method.

### EntityFrameworkCore
#### To install:
`dotnet tool install --global dotnet-ef`
#### To scaffold:
`Scaffold-DbContext [-Connection] [-Provider] [-OutputDir] [-Context] [-Schemas>] [-Tables>] [-DataAnnotations] [-Force] [-Project] [-StartupProject] [<CommonParameters>]`

Example:

 `PM> Scaffold-DbContext "Server=.\SQLExpress;Database=SchoolDB;Trusted_Connection=True;" Microsoft.EntityFrameworkCore.SqlServer -Tables Products -OutputDir Model`

