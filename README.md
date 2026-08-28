# Pizza Builder

A Blazor Server web app for customizing and ordering pizzas.

## Features

- Choose a pizza size: small, medium, or large
- Choose a thin or thick crust
- Add toppings such as extra cheese, mushrooms, tomatoes, onion, olives, and green peppers
- View the selected size and total price
- Responsive pizza-ordering interface

## Built With

- C#
- ASP.NET Core Blazor Server
- .NET 10
- Razor components
- HTML and CSS

## Requirements

- .NET 10 SDK
- A modern web browser

Check that the SDK is installed:

```bash
dotnet --version
```

## Getting Started

Clone the repository and open the project folder:

```bash
git clone https://github.com/YanalHaj/A-Blazor-web-app-for-customizing-and-ordering-pizzas.-.git
cd A-Blazor-web-app-for-customizing-and-ordering-pizzas.-
```

Restore dependencies and run the application:

```bash
dotnet restore
dotnet run
```

Open the HTTPS URL shown in the terminal, usually:

```text
https://localhost:5001
```

## Project Structure

```text
Pages/       Blazor pages, including the pizza builder
Shared/      Shared layout and navigation components
Data/        Application data services
wwwroot/     CSS, images, and other static assets
Program.cs   Application startup and configuration
```

## Future Improvements

- Fix spelling and naming consistency in the order options
- Add a complete reset-order action
- Improve price calculation when changing crust or toppings
- Add order submission and validation
- Persist orders in a database

## License

This project is for learning and demonstration purposes.
