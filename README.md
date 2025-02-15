# E-commerce-
an example of an e-commerce store focused on selling ski products.
# .NET Core 8 + Angular eCommerce App

## Overview
This project is a full-featured **eCommerce application** built using **.NET Core 8** for the backend and **Angular** for the frontend. It provides a seamless shopping experience with features such as product listings, user authentication, shopping cart, order management, and payment integration.

## Features
- **User Authentication** (JWT-based authentication & authorization)
- **Admin Dashboard** for managing products, categories, and orders
- **Product Management** (CRUD operations for products and categories)
- **Shopping Cart** with real-time updates
- **Order Processing** (checkout and payment integration)
- **Multi-Tenant Support** for handling multiple stores
- **RESTful API** for frontend and third-party integrations
- **Secure Payment Gateway** integration (Stripe, PayPal, etc.)
- **SEO Optimization** and performance improvements
- **Mobile Responsive** UI with Angular Material & Bootstrap
- **Localization & Multi-language Support**
- **Caching & Performance Optimization** (Redis, Entity Framework Core optimization)
- **Docker Support** for easy deployment
- **Unit & Integration Testing** with xUnit and Jasmine/Karma

## Tech Stack
### Backend (.NET Core 8)
- **ASP.NET Core 8 Web API**
- **Entity Framework Core 8** (EF Core) for database access
- **Dapper** for high-performance queries
- **Identity Server / JWT** for authentication
- **MediatR** for clean architecture & CQRS pattern
- **Fluent Validation** for request validation
- **AutoMapper** for object mapping
- **Redis** for caching
- **SignalR** for real-time notifications
- **Hangfire** for background jobs

### Frontend (Angular)
- **Angular 17**
- **Angular Material / Bootstrap** for UI components
- **NgRx** for state management
- **RxJS** for handling asynchronous data streams
- **Lazy Loading** for improved performance
- **SCSS** for styling
- **PWA Support** for offline capabilities

## Installation
### Prerequisites
- **.NET SDK 8**
- **Node.js (Latest LTS)**
- **Angular CLI** (`npm install -g @angular/cli`)
- **SQL Server / PostgreSQL**
- **Redis** (Optional, for caching)
- **Docker** (Optional, for containerization)

### Backend Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/ecommerce-app.git
   cd ecommerce-app/backend
   ```
2. Install dependencies:
   ```sh
   dotnet restore
   ```
3. Update **appsettings.json** with database connection details.
4. Apply database migrations:
   ```sh
   dotnet ef database update
   ```
5. Run the API:
   ```sh
   dotnet run
   ```

### Frontend Setup
1. Navigate to the frontend folder:
   ```sh
   cd ../frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Run the Angular app:
   ```sh
   ng serve
   ```
4. Open the browser and visit `http://localhost:4200`

## Deployment
### Docker
To run the application in a **Docker container**:
1. Build and run the Docker containers:
   ```sh
   docker-compose up --build -d
   ```
2. The backend will be available at `http://localhost:5000`, and the frontend at `http://localhost:4200`.

## API Documentation
- Swagger UI: `http://localhost:5000/swagger`
- Postman Collection: Available in the `docs` folder.

## Contributing
Feel free to submit **pull requests** and **issues** for bug fixes, new features, and improvements.

## License
This project is licensed under the **MIT License**.

---
**Author:** Reem Halabia

🚀 Happy Coding!

