# salesforce-CRM
The Rice Mill CRM Application streamlines daily operations in a wholesale rice mill using Salesforce. Features include detailed reports, rollup summary fields, cross-object formulas, validation rules, and permission sets. This project enhances efficiency and customer satisfaction.
# A CRM Application for Wholesale Rice Mill
A CRM Application for Wholesale Rice Mill Utilizing Salesforce to Enhance Efficiency in Rice Mill Operations.
Prepared by: Neha Kumari
Date: 01-07-2024
# Abstract
This project report presents a comprehensive CRM application designed to streamline daily operations in a wholesale rice mill. Leveraging Salesforce, the application provides detailed reports, rollup summary fields, cross-object formula fields, validation rules, and permission sets to improve efficiency and resource allocation.
# Introduction
The wholesale rice milling industry faces numerous challenges in managing daily operations, customer relationships, and reporting. This project aims to develop a comprehensive CRM application using Salesforce to streamline and simplify the management of daily rice production, sales, and reporting. By leveraging the power of Salesforce, the application enhances customer experiences, optimizes store operations, and improves overall efficiency in the rice mill factory.
# Project Objectives
- Develop a user-friendly CRM application.
- Streamline daily operations and reporting.
- Enhance customer experience and optimize resource allocation.
# Description
The application is built on the Salesforce platform, utilizing custom objects, fields, and relationships to manage data efficiently. The architecture includes:
Custom Objects: Supplier, Rice Mill, Consumer, Rice Details
Fields: Number fields, rollup summary fields, cross-object formula fields
Relationships: Master-Detail relationships
User Interface: Custom Tabs, Page Layouts, Lightning App
Security: Validation Rules, Permission Sets
# Prerequisites
- Salesforce Developer account
- Knowledge of Salesforce admin concepts
- Two web browsers installed on the machine
- Good internet connectivity
# Features and Functionality
### Reporting and Dashboards
The application generates detailed reports and analytics on daily rice sales, total income, revenue generated, popular amenities, and customer buying patterns. These insights help the owner understand data, improve resource allocation, and plan future developments.
### Rollup Summary Fields
These fields summarize data from child objects to parent objects in a master-detail relationship. Functions include COUNT, SUM, MIN, and MAX. For example, displaying the total value of rice supplied from rice details on a related supplier.
### Cross-Object Formula Fields
These fields reference fields from another object in Salesforce. For instance, calculating the total amount payable using the formula Number of rice taken * price/kg.
### Validation Rules
Validation rules ensure data integrity by including error messages when invalid values are entered. For example, using the IsBlank formula to verify whether a field is blank and display an error message if so.
### Permission Sets
Organization-Wide Defaults (OWD) are used to restrict access. Roles are created such that the owner can see employer and worker records, and the employer can see worker records.
# Project Report
You can download the detailed project report from the following link:
[Project Report PDF](./SI-1567-1719246208.pdf)

# Milestones and Activities
#### 1. Creating Developer Account
Sign up for a Salesforce Developer account.
![1719775291602](https://github.com/Neha0916/salesforce-CRM/assets/98107526/5cab1451-f38c-4e9f-9bc0-45f28075d262)

#### 2. Creating Objects
- Supplier Object: Manage supplier details.
![1719775593325](https://github.com/Neha0916/salesforce-CRM/assets/98107526/cd308339-36ea-44e4-8642-9ef1a42c64d8)

- Rice Mill Object: Manage rice mill details.
- Consumer Object: Manage consumer details.
- Rice Details Object: Track rice production and sales.
#### 3. Creating Tabs
Create custom tabs for each object to easily access data.
![1719775810971](https://github.com/Neha0916/salesforce-CRM/assets/98107526/27b2b1d0-0af4-4384-898d-6f6a02969644)

#### 4. Creating Lightning App
Steps to create a Lightning app for the CRM application.
#### 5. Creating Fields
Number fields: Track quantities and prices.
Rollup Summary Fields: Summarize data from child to parent objects.
Cross-Object Formula Fields: Calculate total amounts.
Validation Rules: Ensure data integrity.
#### 6. Creating Page Layouts
Customize page layouts for each object to enhance user experience.
![1719776463558](https://github.com/Neha0916/salesforce-CRM/assets/98107526/271daa62-6021-44b3-ba1d-6c1091196c2c)

#### 7. Creating Profiles, Roles, and Role Hierarchy
Define profiles to control user permissions.
Create roles and set up a role hierarchy to establish data access levels.
#### 8. Creating Users
Add users to the Salesforce organization and assign appropriate profiles and roles.
#### 9. Creating Permission Sets
Define permission sets to grant additional permissions to users beyond their profiles.
#### 10. Creating Reports
Create detailed reports to track rice production, sales, and other key metrics.
#### 11. Creating Dashboards
Design dashboards to provide visual summaries of key metrics and reports.
![1719776665471](https://github.com/Neha0916/salesforce-CRM/assets/98107526/8dbe2731-917d-48db-94a8-6e8f27887d72)

# Conclusion
The CRM application successfully streamlines daily operations in the rice mill, enhancing efficiency and customer satisfaction. Future enhancements could include integrating the application with external systems for broader functionality.
# References
- Salesforce Documentation
- Community Forums
