﻿# Web API with .NET 8 and Clean Architecture

## Overview

This project is a Web API developed using **.NET 8** and adheres to the **Clean Architecture** principles. It ensures separation of concerns, testability, and scalability while following best practices for modern software development.

## Features

- **Clean Architecture** implementation:
  - Separation of layers: Domain, Application, Infrastructure, and Presentation.
- RESTful endpoints for efficient API communication.
- Dependency Injection for better modularity and flexibility.
- Integration with **Entity Framework Core** for data persistence.
- Logging and error handling for robust and maintainable code.
- Asynchronous programming with `async`/`await`.

## Technologies Used

- **.NET 8**
- **Entity Framework Core**
- **ASP.NET Core Web API**
- **FluentValidation** for model validation
- **AutoMapper** for object mapping
- **MediatR** for CQRS pattern
- **Swagger/OpenAPI** for API documentation

## Project Structure

The project follows the Clean Architecture pattern, which divides the application into distinct layers:

1. **Domain**:  
   - Core entities and business rules.
   - No external dependencies.
   
2. **Application**:  
   - Application-specific logic.
   - Contains use cases, CQRS handlers, and interfaces.

3. **Infrastructure**:  
   - Handles database access, external APIs, and third-party integrations.
   - Implements the interfaces defined in the Application layer.

4. **Presentation**:  
   - API controllers and endpoint definitions.
   - Manages HTTP requests and responses.

## Prerequisites

Before running the project, ensure you have:

- **.NET 8 SDK** installed
- **SQL Server** or another compatible database
- **Visual Studio**, **JetBrains Rider**, or any code editor of your choice

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/Amirhossein-Olyanasabnarab/Online_Shop_API.git
cd your-repository