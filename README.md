# Healthcare_management_system

Language: Python, HTML, FASTAPI
Arlington Physicians’ Center (APC) FastAPI Project


Project Overview
This project provides a simple web interface for managing and viewing hospital data using FastAPI and MySQL. Users can run queries to update or view data without needing to interact with the database directly.

The project supports:

Adding new specialities
Viewing patient coverage policy details
Updating follow-up times
Deleting hospital locations
Viewing aggregated hospital and physician data



Project Structure

- phase3.py          # Main FastAPI application
- queries.py         # Contains all database query functions
- templates/
- index.html         # HTML template for interface
- database.py        # Database connection setup


Requirements

Python 
FastAPI
Uvicorn
MySQL (XAMPP)
mysql-connector-python

Install Python dependencies:
        pip install fastapi uvicorn mysql-connector-python



Database Setup

All the tables in the database are already created in project phase2.




Running the Project

1. Start your MySQL server (XAMPP).
2. Run the FastAPI app:
         uvicorn phase3:app --reload

3. Open your browser at [http://127.0.0.1:8000].
4. Use the web interface to run queries and view hospital data.



Features

Perform insertion, retrieve, update and delete operation specified by project description
Queries and views integrated on the same page.
 Directly fetches and displays database results.



Notes

All SQL queries are stored in ‘queries.py’.
Database credentials should be configured in ‘database.py’.
Ensure the MySQL server is running.
