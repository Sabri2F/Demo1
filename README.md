# A CRUD Webpage using C#, ASP.NET, Microsoft SQL Server Management Studio

This project is a simple CRUD (Create, Read, Update, Delete) web application built using C#, ASP.NET MVC, Microsoft SQL Server Management Studio (MSMS), Bootstrap, and Toastr. The application allows users to perform basic CRUD operations on a list of items, with the data being stored in a database.

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Database Setup](#database-setup)
- [Screenshots](#screenshots)

## Features

- **Create**: Users can add new items to the list.
- **Read**: Users can view the list of items.
- **Update**: Users can edit and update existing items.
- **Delete**: Users can delete items from the list.
- **Data Storage**: Item data is stored in a Microsoft SQL Server database.
- **User-Friendly Interface**: The application uses Bootstrap for a responsive and visually appealing UI.
- **Notifications**: Toastr is used to display notifications for CRUD operations.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Visual Studio with ASP.NET MVC support.
- Microsoft SQL Server Management Studio (MSMS) installed.
- .NET Framework (version X.X or higher).

## Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/Sabri2F/Demo1.git
```

2. Open the project in Visual Studio.

3. Build the solution to restore the NuGet packages.

## Usage

1. Run the application in Visual Studio.

2. Open your web browser and navigate to `http://localhost:4431`, where `4431` is the port on which the application is running.

3. You will see the list of items. You can perform the following actions:
   - Click on "Create New" to add a new item.
   - Click on "Edit" to modify an existing item.
   - Click on "Delete" to remove an item.

## Database Setup

To set up the database for this project, follow these steps:

1. Open Microsoft SQL Server Management Studio (MSMS).

2. Connect to your local SQL Server instance.

3. Run the SQL script provided in the `database.sql` file to create the necessary database and table.

4. Update the connection string in the `Web.config` file with your SQL Server connection details:

```xml
<connectionStrings>
    <add name="DefaultConnection" connectionString="Server=YourServer;Database=YourDatabase;User Id=YourUsername;Password=YourPassword;" providerName="System.Data.SqlClient" />
</connectionStrings>
```

## Screenshots


