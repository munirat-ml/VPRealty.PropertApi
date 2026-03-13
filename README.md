# VPRealty.PropertyApi

A clean ASP.NET Core Web API project for managing real estate properties using C#, SQL Server, and Entity Framework Core.

## Features
- Create, read, update, and delete property records
- RESTful API endpoints
- SQL Server database integration
- Entity Framework Core
- Swagger UI for API testing

## Tech Stack
- ASP.NET Core Web API
- C#
- SQL Server
- Entity Framework Core
- Swagger / OpenAPI

## Endpoints
- GET /api/properties
- GET /api/properties/{id}
- POST /api/properties
- PUT /api/properties/{id}
- DELETE /api/properties/{id}

## Sample JSON
```json
{
  "title": "Modern 2 Bedroom Condo",
  "address": "25 Sheppard Avenue East",
  "city": "North York",
  "province": "Ontario",
  "price": 759900,
  "bedrooms": 2,
  "bathrooms": 2,
  "isAvailable": true
}
