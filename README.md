# EntityFrameworkCRUDSample
Simple Scaffolding CRUD Operations in ASP.NET Core Using EF Core DB First Approach

**Install-Package Microsoft.EntityFrameworkCore.SqlServer** 

** Install-Package Microsoft.EntityFrameworkCore.Tools **

** Scaffold-DbContext "Server=localhost;Database=Crud;Trusted_Connection=True;" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models**


Select the MVC Controller with the views, using the entity framework.

services.AddDbContext<TestDBContext>(options => options.UseSqlServer("Server=localhost;Database=Crud;Trusted_Connection=True;"));  
