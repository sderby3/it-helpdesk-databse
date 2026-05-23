# SQL IT Helpdesk Database Project

## Overview
This project was created to improve my SQL, database management, reporting, and troubleshooting skills by building a simple IT helpdesk database using Microsoft SQL Server.

The database simulates a basic IT support environment where tickets can be created, tracked, and reported on. I also connected the database to Power BI to create an interactive reporting dashboard.

---

## Technologies Used
- Microsoft SQL Server 2022 Express
- SQL Server Management Studio (SSMS)
- Power BI
- SQL
- Windows 11

---

## Database Setup

### Database Name
- ITHelpdesk

### Table Created
- Tickets

The Tickets table stores information about IT support issues, including:
- TicketID
- UserName
- Department
- IssueType
- PriorityLevel
- Status
- DateCreated
- ResolutionNotes

<img src="/create_table_query.png" width="700">

---

## Features Implemented

### Ticket Table Creation
Created a SQL table to store helpdesk ticket information.

<img src="/create_table_query.png" width="700">

---

### Ticket Data Insertion
Added sample IT support tickets to simulate a real helpdesk environment.

<img src="/insert_into_tickets_query.png" width="700">

---

### Open Ticket Queries
Used SQL queries to identify open support tickets.

<img src="/Open_Tickets_Query.png" width="700">

---

### Ticket Reporting by Status
Used aggregation queries to count tickets by status.

<img src="/total_tickets_department.png" width="700">

---

### Ticket Reporting by Department
Generated reports showing ticket counts across different departments.

<img src="/count_tickets_department_query.png" width="700">

---

## Power BI Dashboard

The SQL database was connected to Power BI to create a simple IT helpdesk dashboard.

The dashboard includes:
- Tickets by department
- Tickets by status
- Tickets by priority
- Open ticket count
- High priority ticket count

<img src="/powerbi_dashboard.png" width="900">

---

## Troubleshooting & Issues Encountered

### SQL Server Connection Issues

#### Issue
Initial attempts to connect to SQL Server failed because the SQL Server service was not running correctly.

#### Resolution
Checked the SQL Server installation, started the required services, and connected using the correct SQL Server instance name.

---

### Duplicate Ticket Entries

#### Issue
Ticket records were accidentally inserted twice during testing.

#### Resolution
Used SQL DELETE queries to remove the duplicate records.

---

## Skills Developed
- SQL querying
- Database creation and management
- Data filtering and aggregation
- IT support reporting
- SQL troubleshooting
- Power BI dashboard creation
- Data visualisation
- Problem solving
