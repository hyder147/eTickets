
# eTickets - Complete E-commerce Application

A full-stack e-commerce platform built with **ASP.NET Core**. Users can browse products, add items to cart, place orders, and admins can manage products and orders through a dedicated dashboard.

## ✨ Features
- User Registration & Login using ASP.NET Identity
- Product Listing, Search and Details
- Shopping Cart System (Add, Remove, Update quantity)
- Order Placement and Order History
- Admin Dashboard with full CRUD for Products and Orders
- Role-based Authorization (Admin vs User)
- Responsive UI

## 🛠 Tech Stack
- **Backend**: ASP.NET Core (C#)
- **Database**: SQL Server + Entity Framework Core (Code-First)
- **Authentication**: ASP.NET Identity
- **Frontend**: Razor Pages / MVC + Bootstrap

## 🚀 How to Run Locally

1. Clone the repository
   ```bash
   git clone https://github.com/hyder147/eTickets.git
   ```

2. Navigate to the project folder
   ```bash
   cd eTickets/eTickets
   ```

3. Update the connection string in `appsettings.json` to point to your local SQL Server

4. Create and apply database migrations
   ```bash
   dotnet ef migrations add InitialCreate
   dotnet ef database update
   ```

5. Run the application
   ```bash
   dotnet run
   ```

Open browser: `https://localhost:5001` (or the port shown in terminal)

## 📸 Screenshots

*(Add 4–5 clear screenshots here after running the project locally)*  
Examples: Homepage, Product List, Shopping Cart, Admin Dashboard, Login Page

## 📚 What I Learned / Challenges Solved
- Built a complete backend using ASP.NET Core MVC architecture
- Implemented Entity Framework Core for database operations and relationships (One-to-Many, Many-to-Many)
- Used ASP.NET Identity for secure user authentication and role-based authorization
- Managed database migrations and seeding with EF Core
- Handled shopping cart logic using sessions or database
- Understood how to structure a real-world e-commerce backend flow (Product → Cart → Order)

## 🔮 Future Improvements
- Convert backend to RESTful Web API with Swagger documentation
- Add payment gateway integration (Stripe or PayPal)
- Implement Redis caching for better performance
- Add Unit & Integration tests
- Deploy the application to Azure or IIS

---




