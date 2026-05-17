# edge-i035-dotnet-backend

Backend for EDGE course (Batch I035) — SQL Server Reporting Services (SSRS) projects for creating and managing business intelligence reports.

## Project Overview

This repository contains SQL Server Reporting Services (SSRS) projects designed for the EDGE I035 batch. The solution includes data sources and report definitions for business reporting and analytics.

## Project Structure

```
edge-i035-dotnet-backend/
├── README.md
├── Yeaish_Jahan_Turj_Report_Project/
│   ├── Yeaish_Jahan_Turj_Report_Project.slnx     # Visual Studio solution file
│   ├── Yeaish_Jahan_Turj_Report_Project/
│   │   ├── Yeaish_Jahan_Turj_Report_Project.rptproj  # SSRS project file
│   │   ├── Report1.rdl                            # Report Definition Language file
│   │   ├── SDS1.rds                               # Shared Data Source file
│   │   └── bin/
│   │       └── Debug/                             # Compiled report output
│   │           ├── Report1.rdl
│   │           └── SDS1.rds
```

## Components

### Yeaish_Jahan_Turj_Report_Project

An SSRS (SQL Server Reporting Services) project containing:

- **Report1.rdl** - Main report definition containing the structure, layout, and data binding for the report
- **SDS1.rds** - Shared Data Source definition for database connectivity and authentication
- **Yeaish_Jahan_Turj_Report_Project.rptproj** - SSRS project configuration file

## File Types

- **`.rdl`** - Report Definition Language (XML-based format for SSRS reports)
- **`.rds`** - Report Data Source (connection information and credentials)
- **`.rptproj`** - SSRS Project file (Visual Studio project configuration)
- **`.slnx`** - Visual Studio solution file

## Requirements

- **SQL Server Reporting Services (SSRS)** 2016 or later
- **Visual Studio 2015** or later with SSRS project support, or **SQL Server Data Tools (SSDT)**
- **SQL Server** instance for data connectivity

## Building and Deploying

### Build

1. Open the `.slnx` solution file in Visual Studio
2. Build the project to compile all reports
3. Compiled files will be generated in the `bin/Debug/` directory

### Deploy

1. Configure your SSRS server connection in the project properties
2. Right-click on the project and select **Deploy**
3. Enter the target SSRS server URL and credentials
4. Reports will be published to the SSRS server

## Getting Started

1. Clone this repository
2. Install SQL Server Data Tools (SSDT) for your Visual Studio version
3. Open `Yeaish_Jahan_Turj_Report_Project.slnx` in Visual Studio
4. Configure the data source connection in `SDS1.rds` with your database credentials
5. Build and preview reports in Visual Studio
6. Deploy to your SSRS server when ready

## Related Projects

This is part of the EDGE I035 batch backend infrastructure. For frontend and additional services, see the parent `edge-react-dotnet` repository.

## Author

**Yeaish Jahan Turj** - EDGE I035 Batch Participant

This project was developed as part of the EDGE I035 batch curriculum to demonstrate proficiency in SQL Server Reporting Services and business intelligence reporting.
