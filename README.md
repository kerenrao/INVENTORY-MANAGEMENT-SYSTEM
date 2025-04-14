# INVENTORY-MANAGEMENT-SYSTEM

# Inventory Management System

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)
![SQL Server](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white)
![Windows Forms](https://img.shields.io/badge/Windows%20Forms-00A4EF?style=for-the-badge&logo=windows&logoColor=white)

A modern Windows desktop application for managing product inventory with SQL database backend.

<img width="431" alt="image" src="https://github.com/user-attachments/assets/ad160d2b-f7fd-4b75-aa6d-ade314656f9b" />


## Features

- **CRUD Operations**: Create, Read, Update, and Delete products
- **Dark Mode UI**: Sleek dark theme interface
- **Database Integration**: MSSQL LocalDB backend
- **Search Functionality**: Quick product search by name or category
- **Data Grid View**: Interactive product listing with click-to-edit
- **Category Management**: Predefined product categories

## Technologies Used

- C# (.NET Framework)
- Windows Forms
- Microsoft SQL Server (LocalDB)
- ADO.NET for database operations
- Dark UI styling

## Installation

1. **Prerequisites**:
   - .NET Framework 4.7.2 or later
   - SQL Server Express LocalDB

2. **Database Setup**:
   ```sql
   CREATE DATABASE InventoryDB;
   USE InventoryDB;
   
   CREATE TABLE Products (
       ID INT PRIMARY KEY IDENTITY(1,1),
       Name NVARCHAR(100) NOT NULL,
       Category NVARCHAR(50) NOT NULL,
       Quantity INT NOT NULL,
       Price DECIMAL(10,2) NOT NULL
   );



3. CODE STRUCTURE

InventoryManager/
├── Form1.cs             # Main application form
├── Form1.Designer.cs    # UI designer file
├── App.config           # Configuration file
└── Properties/          # Assembly info



Developed by KEREN RAO NAVAKOTI
