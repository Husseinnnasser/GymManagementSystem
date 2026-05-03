# Gym Management System 🏋️‍♂️

A comprehensive, full-stack web application designed to streamline gym operations, including member management, trainer assignments, and session bookings. 

This project is built using **ASP.NET Core MVC** and enforces a strict **3-Layer (N-Tier) Architecture** to ensure clean separation of concerns, scalability, and maintainable code.

## 🏗️ Architecture

The solution is divided into three distinct layers, reflecting enterprise-level design practices:

* **Presentation Layer (`GymManagementPL`):** Built with ASP.NET Core MVC and Bootstrap, handling user interactions, dynamic reporting dashboards, and view rendering.
* **Business Logic Layer (`GymManagementBLL`):** Contains the core business rules, services, and logic that dictate how data is processed between the UI and the database.
* **Data Access Layer (`GymManagementDAL`):** Manages secure database operations using **Entity Framework Core** and **SQL Server**, implementing the **Repository Pattern** to abstract data persistence.

## ✨ Key Features

* **Member & Trainer Management:** Full CRUD operations to register and manage gym members and staff.
* **Session Bookings:** Efficient scheduling system for assigning members to specific training sessions and trainers.
* **Dynamic Dashboards:** Real-time reporting dashboards for administrative oversight.
* **Secure Data Operations:** Enforced business rules and secure data access through repository abstractions.

## 💻 Tech Stack

* **Language:** C#
* **Framework:** .NET Core, ASP.NET Core MVC
* **Database:** Microsoft SQL Server, Entity Framework Core (ORM)
* **Frontend:** HTML5, CSS3, Bootstrap
* **Design Patterns:** N-Tier Architecture, Repository Pattern, Dependency Injection

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps:

### Prerequisites
* [.NET SDK](https://dotnet.microsoft.com/download) (Version matching the project)
* SQL Server (LocalDB or standard instance)
* Visual Studio or any preferred C# IDE

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Husseinnnasser/GymManagementSystem.git](https://github.com/Husseinnnasser/GymManagementSystem.git)
