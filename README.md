# SQL IT Helpdesk Database Project

## Overview
This project demonstrates the creation of a basic IT helpdesk ticketing database using Microsoft SQL Server 2022 Express and SQL Server Management Studio (SSMS).

The purpose of the project was to develop foundational SQL, database management, reporting, and troubleshooting skills through a realistic IT support scenario.

---

## Technologies Used
- Microsoft SQL Server 2022 Express
- SQL Server Management Studio (SSMS)
- SQL
- Windows 11

SQL Server Management Studio (SSMS) was used to connect to the SQL Server instance, create databases and tables, execute SQL queries, and analyse query results.

---

## Database Configuration

### Database Name
- ITHelpdesk

### Table Created
- Tickets

### Table Structure
The Tickets table was designed to simulate a real-world IT support helpdesk environment.

Fields included:
- TicketID
- UserName
- Department
- IssueType
- PriorityLevel
- Status
- DateCreated
- ResolutionNotes

<img src="screenshots/create_table_query.png" width="700">

---

## Features Implemented

### Ticket Table Creation
Created a structured SQL table to store IT support ticket information.

<img src="screenshots/create_table_query.png" width="700">

### Ticket Data Insertion
Inserted realistic IT support ticket records into the database.

<img src="screenshots/insert_into_tickets_query.png" width="700">

### Open Ticket Queries
Queried the database to identify currently open support tickets.

<img src="screenshots/Open_Tickets_Query.png" width="700">

### Ticket Reporting by Status
Used SQL aggregation queries to count tickets by support status.

<img src="screenshots/total_tickets_department.png" width="700">

### Ticket Reporting by Department
Generated reports showing ticket counts across departments.

<img src="screenshots/count_tickets_department_query.png" width="700">

