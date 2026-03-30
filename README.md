*eTickets - Complete E-commerce Application*

A full-stack e-commerce platform built with ASP.NET Core. Users can browse products, add to cart, place orders, and admins can manage products and orders.

 Features
- User Registration & Login (ASP.NET Identity)
- Product Listing, Search & Details
- Shopping Cart System
- Order Placement & History
- Admin Dashboard for CRUD operations
- Responsive UI

 Tech Stack
- **Backend**: ASP.NET Core (C#)
- **Database**: SQL Server + Entity Framework Core
- **Authentication**: ASP.NET Identity
- **Frontend**: Razor Pages / MVC + Bootstrap
- **Other**: AutoMapper, Validation (if used)

 How to Run Locally

1. Clone the repo
   ```bash
   git clone https://github.com/hyder147/eTickets.git
   cd eTickets

What I Learned / Challenges Solved

Built a complete backend using ASP.NET Core MVC architecture
Implemented Entity Framework Core for database operations and relationships (One-to-Many, Many-to-Many)
Used ASP.NET Identity for secure user authentication and role-based authorization
Managed database migrations and seeding with EF Core
Handled shopping cart logic using sessions or database
Understood how to structure a real-world e-commerce backend flow (Product → Cart → Order)

🔮 Future Improvements

Convert to RESTful Web API with Swagger documentation
Add payment gateway integration (Stripe or PayPal)
Implement Redis caching for better performance
Add Unit & Integration tests
Deploy the application to Azure or IIS
