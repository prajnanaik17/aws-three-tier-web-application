AWS Three-Tier Web Application

Project Overview

This project demonstrates the deployment of a Three-Tier Web Application on AWS.

Architecture

User
↓
Web Tier (Apache Web Server)
↓
Application Tier (Python Flask)
↓
Database Tier (Amazon RDS MySQL)

Web Tier

- EC2 Instance
- Apache HTTP Server

Application Tier

- EC2 Instance
- Python
- Flask

Database Tier

- Amazon RDS MySQL

AWS Services Used

- Amazon EC2
- Amazon RDS
- Amazon VPC
- Security Groups
- Public and Private Subnets

Technologies Used

- Python
- Flask
- MySQL
- Apache HTTP Server

Database Details

Database Name: employee_db

Table Name: employees

Sample Data

1. John - HR - 50000
2. Alice - IT - 70000
3. Bob - Finance - 60000

Project Outcome

Successfully deployed a Three-Tier Web Application on AWS using EC2 instances, Python Flask, and Amazon RDS MySQL. The application retrieves employee information from the database and displays it through a web interface.