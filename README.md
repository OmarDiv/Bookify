# Bookify (.NET 7 MVC Web App)

Bookify is a feature-rich booking and rental management platform, built using ASP.NET Core 7 MVC. The project is designed for multi-language support, user authentication, advanced scheduling, and notification systems.

---

## What Bookify Covers

Bookify implements enterprise-grade modules and features:
- MVC Architecture (Controllers, Views, Models)
- Multi-language Localization (English & Arabic)
- RESTful Endpoints & CRUD Operations
- Model Binding, Mapping, and Validation (FluentValidation, AutoMapper)
- Database (EF Core, SQL Server)
- Authentication & Authorization (Identity, JWT)
- Role Management & Permissions
- Application Configuration & Options
- Audit Logging (Serilog, logs to file & SQL Server)
- CORS Support & Secure Headers
- Error & Exception Handling
- Problem Details Standardization
- Logging & Caching
- Background Jobs (Hangfire)
- User & Account Management
- Pagination, Filtering, Sorting
- Health Checks & Rate Limiting
- Swagger & API Documentation
- Code Review Processes
- Deployment Best Practices
- Integrated Email and WhatsApp notifications

Includes integration with Email and WhatsApp notifications, Cloudinary for image storage, and supports custom scheduling with Hangfire.

---

## Tech Stack

- ASP.NET Core 7 MVC
- Entity Framework Core + SQL Server
- AutoMapper, FluentValidation
- Hangfire, Serilog
- Cloudinary, MailKit, WhatsAppCloudApi

---

## Getting Started

1. **Clone the repository:**
    ```bash
    git clone https://github.com/OmarDiv/Bookify.git
    cd Bookify
    ```
2. **Configure Database:** Edit `Bookify.Web/appsettings.json` for your connection details.
3. **Restore dependencies:**  
    `dotnet restore`
4. **Run migrations:**  
    `dotnet ef database update --project Bookify.Web`
5. **Run the web application:**  
    `dotnet run --project Bookify.Web`
6. **Access the app:**  
    [https://localhost:5001](https://localhost:5001)

---

## Project Structure (Example)

```
Bookify/
├── Bookify.Web/           # Main MVC project
├── Bookify.Domain/        # Domain models
├── Bookify.Application/   # Business logic
├── Bookify.Infrastructure/# Data access & integrations
├── Middlewares/
├── Seeds/
├── Tasks/
├── Views/
├── wwwroot/
...
```

---

## Contributing

- Fork, branch, and submit descriptive PRs.
- Follow .NET MVC standards and write tests.

---

## License

MIT

---

## Contact

- **WhatsApp:** 01013762770
- **Email:** omaar88mohamed@gmail.com
- **LinkedIn:** [Omar Mohamed](https://www.linkedin.com/in/omar-mohamed-713b53265)
