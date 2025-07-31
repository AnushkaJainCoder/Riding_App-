# Riding App

This is a simple .NET console application for a riding app demo. It manages customer, vehicle, and driver profiles and validates vehicle information.

## Features
- Customer profile creation
- Vehicle profile and validation
- Driver profile creation

## How to Run
1. Make sure you have the .NET SDK installed.
2. Build the project:
   ```
   dotnet build riding_app.sln
   ```
3. Run the project:
   ```
   dotnet run --project riding_app
   ```

## Project Structure
- `riding_app/` - Main application code
- `riding_app/Models/` - Contains model classes: Customer, Vehicle, Driver

## Notes
- The `.vs/`, `bin/`, and `obj/` folders are excluded from git using `.gitignore`.
- This project is for demonstration purposes.
