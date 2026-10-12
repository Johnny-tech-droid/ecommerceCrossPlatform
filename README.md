# ECommerceApp
This is a simple E-Commerce Web-App built with C#, HTML, CSS, and JavaScript. 
It is a simple web application that allows users to view products. The application is built with ASP.NET Core MVC and Entity Framework Core.

## Database variant

This version uses **SQLite** (`UseSqlite`, file `localdatabase.db` in the project folder) and runs on
Windows, macOS and Linux. The original variant with **SQL Server LocalDB** lives in
[ECommerceApp](https://github.com/Johnny-tech-droid/ECommerceApp).

## Run

Requires the .NET 8 SDK.

```bash
dotnet tool install --global dotnet-ef
dotnet ef database update
dotnet run
```

## License

MIT, see [LICENSE](LICENSE).

## Contact

Johnny-tech-droid · contact@hausrund.info · https://github.com/Johnny-tech-droid
