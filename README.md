# ManagementSystem [Assignment]

## Project Overview
ManagementSystem is a comprehensive solution designed to streamline and manage. This system is built using modern technologies and offers a user-friendly interface, robust features, and scalable architecture.

## Features
1. **User Authentication and Authorization**: Utilizes ASP.NET Core Identity for secure user authentication and authorization.
2. **Role-Based Access Control**: Implements role-based access control with policies like "AdminOnly" and "CashierOnly".
3. **Product Management**: Allows for the management of products, including adding, editing, and deleting products.
4. **Category Management**: Facilitates the management of product categories.
5. **Transaction Processing**: Supports recording and viewing transactions, including daily transactions.
6. **Database Integration**: Integrated with SQL Server using Entity Framework Core for robust data management.
7. **Clean Architecture**: Follows the principles of Clean Architecture for maintainable and scalable software design.
8. **Blazor Server-Side Framework**: Built with Blazor for interactive and dynamic web UIs.
9. **Responsive Web Design**: Features a responsive design, ensuring compatibility across various devices and screen sizes.

## Technologies Used
- .NET 5
- ASP.NET Core
- Entity Framework Core
- Blazor (Server-Side)
- SQL Server
- HTML/CSS
- JavaScript (for Blazor interop)


## Installation and Setup
To set up the ManagementSystem project on your local machine, follow these steps:
1. Clone the repository: `git clone https://github.com/TIberiu99p/ManagementSystem.git`
2. Navigate to the project directory: `cd ManagementSystem`
3.1. Open the `appsettings.json` file in the project.
3.2 Locate the connection string for the university server.
3.3. Replace the connection string with the one provided.
3.4. Save the `appsettings.json` file.
4. Run the application:
   - Restore the necessary packages: `dotnet restore`
   - Build the project: `dotnet build`
   - Start the application: `dotnet run`

## Usage
To use the ManagementSystem, follow these steps:
1. Start the application.
2. Log in using your credentials. If you don't have an account, register a new one.
3. Navigate through the dashboard to manage products, categories, and transactions.
4. Use the role-based access control to manage user roles and permissions.



