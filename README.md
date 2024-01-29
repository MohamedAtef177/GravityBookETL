# Gravity Books Sales End-to-End Project
![Logo](https://github.com/3amory99/Gravity-Books-Sales-End-to-End-Project/blob/master/Project%20Screenshots/gravity%20logo.png)
## Table of Contents
- [Introduction](#introduction)
- [Project Phases](#project-phases)
- [Data Source](#data-source)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [ETL Phase](#etl-phase)
- [Analysis Phase](#analysis-phase)


## Introduction
Welcome to the Gravity Books Sales End-to-End Project repository. This project is an exemplary demonstration of a complete data warehousing solution, encompassing the Extract, Transform, Load (ETL) phase, analysis phase with SQL Server Analysis Services (SSAS), and reporting phase using Pivot Table and Power BI.

## Project Phases
1. **ETL (Extract, Transform, Load)**: In this phase, data is extracted from a transactional database called "Gravity Book Sales," transformed to meet data warehousing requirements, and loaded into a structured data warehouse.
2. **Analysis**: The data is modeled and structured for efficient querying and analysis using SQL Server Analysis Services (SSAS).

## Data Source
The source dataset for this project is the "Gravity Book Sales" database, which can be found [here](https://github.com/MohamedAtef177/GravityBookETL/tree/main/Source%20data%20file/sample_db_gravity/gravity_sqlserver). This transactional database serves as the foundation for the end-to-end project.

## Technologies Used
- SQL Server Integration Services (SSIS)
- SQL Server Analysis Services (SSAS)

## Getting Started
To explore and replicate the project, follow these steps:
1. Clone this repository to your local machine.
2. [Download and install SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) if not already installed.
3. Follow the instructions in the respective folders for each project phase (ETL, Analysis, Reporting) to set up and execute the code.

## ETL Phase


* DDL statements of table creation and the DWH Schema
  
  * Customer Dimension
    
    ![DDL Customer Dim](https://github.com/MohamedAtef177/GravityBookETL/blob/main/ScreenShots/DimCustomerData.PNG)
    
  * Book Dimension
    
    ![DDL Book Dim](https://github.com/MohamedAtef177/GravityBookETL/blob/main/ScreenShots/DimBookData.PNG)
    
   * Shipping Dimension
     
    ![DDL Shipping Dim](https://github.com/MohamedAtef177/GravityBookETL/blob/main/ScreenShots/Dimshiping_methodData.PNG)
  
   * Date Dimension
     
    ![DDL Date Dim](https://github.com/MohamedAtef177/GravityBookETL/blob/main/ScreenShots/DimDateData.PNG)





* Detailed instructions for the ETL phase can be found in the [BookDWH](/ETL).

   * Customer Dimension
   
    ![ETL Customer Dim](https://github.com/MohamedAtef177/GravityBookETL/blob/main/ScreenShots/DimCustomer.PNG)

   * Book Dimension
   
    ![ETL Book Dim](https://github.com/MohamedAtef177/GravityBookETL/blob/main/ScreenShots/Dimbook.PNG)

   * Shipping Dimension
   
    ![ETL Shipping Dim](https://github.com/MohamedAtef177/GravityBookETL/blob/main/ScreenShots/Dimshiping_method.PNG)

   * Fact Table 
   
    ![ETL Fact Table Full Load](https://github.com/MohamedAtef177/GravityBookETL/blob/main/ScreenShots/Fact_order.PNG)
    ![ETL Fact Table Full Load](https://github.com/MohamedAtef177/GravityBookETL/blob/main/ScreenShots/Fact_order2.PNG)

   * Fact History Table
    ![ETL Fact History Table Full Load](https://github.com/MohamedAtef177/GravityBookETL/blob/main/ScreenShots/Fact%20history.PNG)

## Analysis Phase
To explore the analysis phase, refer to the [Analysis folder](/Analysis).

This project harnesses the power of SQL Server Analysis Services (SSAS) for advanced data modeling and analysis. In particular, we've employed the Tabular mode of OLAP (Online Analytical Processing) to create efficient data models that cater to our analytical needs.

- **Tabular Mode:** We've chosen to work with the Tabular mode in SSAS. This mode specializes in constructing tabular data models, which provide a streamlined, relational view of the data. It excels in scenarios where data retrieval speed and simplicity are top priorities.

    ![SSAS OLAP](https://github.com/MohamedAtef177/GravityBookETL/blob/main/ScreenShots/BookCube.PNG)


---

Feel free to adapt and expand upon this template to provide all the necessary details, instructions, and context for your "Gravity Books Sales End-to-End Project" repository. An informative README.md helps users understand and engage with your project effectively.
