# Electricity Billing System
## Table of Contents
* Project Overview
* Features
* Technologies Used
* Installation
* Usage
* Contributing
* License
* Contact
## Project Overview
The Electricity Billing System is a Java-based application designed to automate the billing process for electricity usage. It provides a user-friendly interface for managing customer information, recording meter readings, calculating bills, and generating reports.

## Features
* User authentication and authorization
* Customer management (add, update, delete, view customers)
* Meter reading entry and validation
* Automatic bill calculation based on usage
* Bill generation and printing
* Payment processing and receipt generation
* Report generation for billing and payment history
## Technologies Used
* Java SE
* Swing (for GUI)
* JDBC (for database connectivity)
* MySQL (for database management)
## Database (MySQL)
Database for this Electricity Billing System contains 4 Tables

* Login Table (UserName,Password)

* Bill Table(MeterNumber,Units,Month,Amount)

* Emp Table(Name, MeterNumber, Address, State, City, Email, Phone)

* Tax Table(MeterLocation,MeterType,PhaseCode,BillType,Days,MeterRent,MCB_Rent,ServiceRent,GST)

Java communicates with MySQL tables using JDBC which stands for Java Database Connectivity.
