README – INSY7213 POE PART 3: BikesRUs Database System
Module Information

Module: Information Systems 2C
Module Code: INSY7213
Assessment Type: Summative Project (Paper Only)
Student Name: Nonjabulo Mathenjwa
Student Number: ST10077892

1. Project Overview

This project implements a fully functional relational database for BikesRUs, a non-profit bicycle outlet based in Gugulethu, Cape Town. The outlet relies on volunteers and donors to collect and resell bicycles affordably to the community.
The goal of this assessment was to design, implement, and test a complete database in Oracle SQL Developer that meets the outlet’s operational and reporting needs.

The project demonstrates practical database design, querying, and procedural programming using SQL and PL/SQL, along with secure and well-structured data manipulation.

2. Objectives

The database solution was designed to:

Create and populate the core entity tables for Volunteers, Donors, Bikes, and Donations.

Establish primary keys, foreign keys, and constraints to maintain referential integrity.

Implement queries, procedures, functions, views, and triggers to automate key business processes.

Enforce data validation and prevent invalid transactions.

Generate accurate, readable reports for management and operational staff.

Apply data confidentiality, integrity, and availability (CIA) principles to protect organisational information.

3. Files and Structure

All project components are organised in one main folder:

ST10077892_INSY7213_POE_PART3/
│
├── README.txt / README.md        ← (this file)
├── INSY7213_POE_PART3.sql        ← main SQL script containing all answers (Q1–Q10)
├── Screenshots/                  ← screenshots of outputs, views, and results
│
└── Documentation/                ← supporting written report for Question 10


Note:
Each question (Q1–Q10) in the SQL script is clearly labelled with comments for easy navigation and marking.

4. Summary of Tasks
Question	Description	Main Focus Area
Q1	Database and table creation, data insertion, constraints	Database design
Q2	Query for bikes with a value above R1500	SQL SELECT with conditions
Q3	VAT calculation for Road Bikes	Use of constants and computed fields
Q4	Creation of a database view for specific volunteer	View creation and justification
Q5	Stored procedure to display donor and volunteer details	PL/SQL procedure with exception handling
Q6	Function to calculate total donation value per donor	PL/SQL function with return value
Q7	Report using IF…ELSIF to assign bike status	PL/SQL conditional logic
Q8	Same report using CASE structure	SQL CASE statement
Q9	Triggers to prevent deletion and enforce valid updates	Data integrity enforcement
Q10	Technical report on confidentiality, integrity, and availability	Database security concepts
5. Testing and Validation

All SQL and PL/SQL scripts were tested using Oracle SQL Developer.

The DBMS Output panel was enabled for displaying results.

Procedures, functions, and triggers were verified using sample data provided in the assessment.

Errors such as ORA-20001 and ORA-20002 confirm successful enforcement of business rules.

Screenshots of the test outputs are saved in the Screenshots folder for marking reference.

6. Security and Data Protection

To ensure confidentiality, only authorised roles can modify data.
To maintain integrity, triggers and constraints validate updates and prevent deletions.
To support availability, backup strategies and role-based access principles are discussed in the technical report.

7. Tools and Environment

Database System: Oracle Database Express Edition (Oracle XE)

Interface Tool: Oracle SQL Developer

Operating System: Windows 10/11

Programming Language: SQL / PL/SQL

Output Display: DBMS Output console

8. References

Oracle Documentation (https://docs.oracle.com
)

The Independent Institute of Education (IIE) assessment brief (INSY7213 POE Part 3, 2025)

SQL and PL/SQL best practices as covered in module lectures and tutorials
