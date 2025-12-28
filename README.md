# Dormitory Management System

## Introduction
The Dormitory Management System is a Windows Forms application developed using C# and SQL Server. It is designed to automate and efficiently manage dormitory operations, providing comprehensive tools for management, staff, and students.

## Key Features

### 1. Student Management
- Add, edit, and delete student information.
- Manage personal details (full name, date of birth, gender, email, address).
- Track room assignments.
- Manage priority policies.

### 2. Room & Area Management
- Manage dormitory areas (Add, edit, view information).
- Manage room types and detailed room information.
- Track room status (available/occupied).
- Manage room pricing.

### 3. Contract Management
- Create and manage dormitory residency contracts.
- Monitor contract expiration dates.
- Manage contract extensions.

### 4. Invoice & Billing Management
- Create and manage invoices for residency fees.
- Track additional costs (electricity, water, etc.).
- Maintain payment history.

### 5. Staff Management
- Manage staff information and profiles.
- Role-based access control.
- Monitor staff tasks and assignments.

### 6. Authentication & Authorization
- Secure user login system.
- Permission levels for different roles (Student, Staff, Manager).
- Account security management.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/duy-debug/dormitory_management_system.git
   ```

2. **Database Setup:**
   - Create a new database named `QLKTX` in SQL Server.
   - Execute the SQL script located at `QuanLyKyTucXa/Db/65.CNTT-1_Nhom2_QLKTX.sql` to generate tables and sample data.

3. **Configure Connection String:**
   - Open the `DatabaseHelper.cs` file.
   - Update the connection string to match your local SQL Server configuration.

4. **Build and Run:**
   - Open the `QuanLyKyTucXa.sln` solution in Visual Studio.
   - Build the solution.
   - Run the application.

## Project Structure

```
QuanLyKyTucXa/
├── UI/                    # User interface (Windows Forms)
├── Models/               # Data models
├── Db/                   # Database logic and SQL scripts
├── Resources/            # Assets (images, icons)
├── Properties/           # Project configuration
└── bin/ obj/             # Build output
```

## Tech Stack

- **Language:** C#
- **Framework:** .NET Framework (Windows Forms)
- **Database:** SQL Server
- **Data Access:** ADO.NET

## Development Team

- **Trần Mai Ngọc Duy** (Leader)
- **Trần Minh Hoàng**
- **Nguyễn Lê Thùy Linh**
- **Ngô Văn Lực**

## Contribution

Contributions are welcome! Please feel free to create an issue or submit a pull request.

## Acknowledgments

Special thanks to all team members for their hard work and dedication to this project.
