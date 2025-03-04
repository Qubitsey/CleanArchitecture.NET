# CleanArchitecture

A simple application built with Clean Architecture using .NET 8 Web API. This project demonstrates a scalable and maintainable project structure, using an in-memory database with seed data and unit tests for core functionalities.

## Overview

This repository is a practical implementation of Clean Architecture principles in .NET 8. The project includes:
- **Clean Architecture** for structured, decoupled, and maintainable code
- **In-Memory Database** for quick setup and easy testing
- **Data Seeding** to populate initial data for testing
- **Unit Tests** to ensure code reliability and robustness

## Project Structure

The solution is organized to reflect Clean Architecture principles:

- **Domain**: Core entities and business rules
- **Application**: Interfaces, services, and application-specific logic
- **Infrastructure**: Repositories, data access, and configurations
- **WebAPI**: API controllers and endpoints

## Key Features

- **RESTful API** endpoints to manage ToDo items and lists
- **Dependency Injection** for services and repositories
- **In-Memory Database** for local testing and development
- **Seed Data** to quickly populate data without manual entry
- **Unit Tests** for services and repositories to validate core logic

## Getting Started

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)

### Database
The application uses an in-memory database by default, with seed data defined in Program.cs. You can easily switch to a SQL Server or another database by updating the connection string and configuration.

### Setup

1. Clone the repository:
   ```
   git clone 
   cd 

   dotnet restore
   dotnet run --project TodoApp.WebAPI

