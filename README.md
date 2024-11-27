# Project: Comprehensive .NET 8 Web API and WASM App with Authentication and CRUD Functionality  

Welcome to the GitHub repository for this project! This application demonstrates how to build a full-stack application using .NET 8 Web API and WASM, with robust authentication, token management, and CRUD operations. The project is structured to guide to how I built this enterprise-grade app step by step.  

---

## 📋 **Features Overview**  
### 1. **Backend - .NET 8 Web API**  
- Database integration with EF Core.  
- Authentication with JWT, including refresh token implementation.  
- Generic Repository and Controller patterns for streamlined CRUD operations.  

### 2. **Frontend - WASM Client**  
- Integration with the API services for seamless interaction.  
- Custom Authentication State Provider to manage user sessions.  
- Responsive UI with Login, Register, Department, Employees, and more components.  

---

## 🏗️ **Project Walkthrough**  

### - **📋 Introduction**  
- Overview of the project with architectural diagrams.  

### - **🏗️ Project Setup**  
- Creating .NET 8 Web API, WASM Client, and shared libraries.  

### - **📦 Installing Required Packages**  
- Installing EF Core, JWT, and other necessary dependencies.  

### - **📝 Models and Classes**  
- Defining models for entities like Employees, Sanctions, and Vacations.  

### - **🔌 Database Context Setup**  
- Creating the `DbContext` class, connection strings, and registering the connection in the API.  

### - **🔄 Adding Migrations**  
- Implementing migrations for database schema creation.  

### - **🔐 Authentication Setup**  
- Building repositories, interfaces, and controllers for user authentication.  

### - **🔄 Refresh Token**  
- Adding functionality for token refresh to extend user sessions.  

### - **🌐 API Consumption Service**  
- Creating services to consume API endpoints in the WASM client.  

### - **🛡️ Custom Authentication State Provider**  
- Building and registering the provider to manage authentication states on the client side.  

### - **🔗 CORS Setup**  
- Configuring CORS to enable secure communication between the client and server.  

### - **🔒 Route Component Authentication**  
- Adding authentication checks to route components.  

### - **🚪 Main Layout Updates**  
- Modifying the main layout to add logout functionality.  

### - **🔑 Account Pages**  
- Creating and integrating Login and Register components with the API.  

### - **🔐 JWT Service Registration**  
- Registering JWT authentication in the server.  

### - **🛠️ Custom HTTP Handler**  
- Adding token handling to HTTP requests and implementing token refresh.  

### - **🔍 User Authentication Management**  
- Checking user authentication state and managing page navigation accordingly.  

### - **🏢 CRUD Components**  
- Creating UI components for managing Employees, Sanctions, and Vacations.  

### - **🔧 Generic CRUD Implementation**  
- Building generic interfaces and repository patterns for scalable CRUD operations.  

### - **🧪 Testing the App**  
- Comprehensive testing to ensure all features work as expected.  


## 🛠️ **Setup Instructions**  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-repo/Employee_Management_System.git  
   cd Employee_Management_System  
   ```  

2. Install required packages:  
   ```bash  
   dotnet restore  
   ```  

3. Configure database connection:  
   - Update the connection string in `appsettings.json`.  

4. Apply migrations:  
   ```bash  
   dotnet ef database update  
   ```  

5. Run the application:  
   ```bash  
   dotnet run  
   ```  

---

## 🧪 **Testing**  
- Unit and integration tests are included in the project. Run tests using:  
   ```bash  
   dotnet test  
   ```
   
Happy coding! 🎉  
