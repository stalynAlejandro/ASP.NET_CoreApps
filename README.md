# ASP.NET_CoreApps
Building modular, multi-tenant ASP.NET Core Apps with Orchard Core framework

# Modular Applications
Why you would build modular applications? 

#### 1. You work with multiple teams and each team wants to own a different section of the application. So you can split the work and each project its own by each team.
- Work in isolation
  - Multiple Teams.
  - Different sections of the application.

#### 2. You want to reuse some parts of the application. For instance let's say these modules contains *static assets(images), middleware (authentication), UI (user management)..*. These pieces of your application you want to use them across the application, you would want modules. 
- Reuse application parts
  - Static assets
  - Middleware
  - UI 

#### 3. For last you can publish and share these modules as a **NuGet Packages**. 
- Publicly share NuGet Packages
  - Create extensible application ecosystems
