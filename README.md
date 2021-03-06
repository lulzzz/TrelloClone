# TrelloClone

> A Kanban board using ASP.Net Core and Materialize CSS

## Scope

This project was created for the sole purpose of creating an MVVM version of a Kanban board similar to Trello using ASP.Net Core and pairing it with Materialize CSS framework.

### Function

This web application allows the creation of new categories as main boards, which are displayed as a collection. Within each board are category columns that separate a list of processes represented as cards.

Create your own boards however many you may like. Then add a few cards, which will then add three default columns named: "Todo, Doing, and Done".

Move cards into their appropriate columns. This is achieved using jQuery and the Drag & Drop JavaScript library.

## Software Stack and Tools

The application was built using the following:

- ASP.Net Core 3.1
- jQuery
- SQL with Entity Framework Core as the ORM
- Materialize CSS v1.0

## Installation

- `git clone` the repository or download a .zip file using the download button.
- In the project folder, run `dotnet restore` to install necessary NuGet packages and build runtime.
- Then either use `dotnet run` in the terminal/command line or in Visual Studio with `Ctrl + F5` to build and run the project.
- Navigate to: `https://localhost:5000` or if executed by VS to `https://localhost:4438` to see the project running.
