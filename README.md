# Gift of the Givers WebApp

This is a **.NET Core MVC web application** developed as part of a project to manage and track activities for the Gift of the Givers Foundation.  
It provides features for admins, volunteers, and donors to interact with the system.

---

##  Features

- **User Management**
  - Register, login, and manage users
- **Donations**
  - Make donations and view donation history
- **Volunteers**
  - Manage volunteers and assign tasks
- **Incidents**
  - Track and manage reported incidents
- **Admin Dashboard**
  - Quick stats for Users, Incidents, Donations, and Volunteers
  - View latest donations
  - Manage users, donations, incidents, volunteers, and tasks

---

##  Tech Stack

- **Backend:** ASP.NET Core MVC
- **Frontend:** Razor Pages with Bootstrap
- **Database:** Entity Framework Core with SQL Server
- **Authentication:** ASP.NET Identity

---

## Project Structure

- `Controllers/` → MVC controllers for handling logic
- `Models/` → Database models (Users, Donations, Volunteers, etc.)
- `Views/` → Razor views for UI
- `wwwroot/` → Static files (CSS, JS, images)
- `Data/` → EF Core DbContext for database interaction
