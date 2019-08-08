# BDBDEV---Power-BI-Developer-Bootcamp
Files for Power BI Bootcamp Classes at ONLC

This intense class is a four day immersion into the powerful world of Power BI.


Book: Courseware is provided and shipped by Critical Path - Power BI Developer Bootcamp
     (Critical Path )
     
     Below, please find the detailed outline.  Optionally, you can always visit www.onlc.com and search for ALL our Power BI Classes!
     
     Course Module Detailed Outline

Module 01: Power BI Desktop Primer
This module begins with a fast-paced primer on building reporting and data analysis projects using Power BI Desktop. The module reviews the phases of building Power BI Desktop projects including designing queries, building data models and designing reports. The module examines the PBIX project file format and explains how PBIX files provide the foundation to developers for deploying and updating datasets and reports for custom solutions. The module explains the best practices of importing data into a star schema and designing a data model using calculated columns, measures and dimensional hierarchies. The module teaches students how to design reports in Power BI Desktop using bookmarks and drillthrough pages to provide interactive navigation and filtering.
Topics Covered
•      Designing Queries using the Query Editor Window
•      Importing Data into a Star Schema
•      Building a Data Model using DAX
•      Designing Interactive Reports with Bookmarks
•      Designing Reports with Drillthrough Pages
•      Publishing PBIX Project Files to the Power BI Service

Module 02: Designing Advanced Queries using M
This module examines advanced query design techniques in Power BI Desktop. Students will be introduced to the M programming language and will learn to edit M expressions in the Advanced Editor window of Power BI Desktop and in Visual Studio. The module explains how to program with complex M datatypes such as records, lists, tables and user-defined types. The module explains the inner workings of query folding with the mashup query engine and teaches students how to design queries to be more efficient. The module explains the purpose of query functions and teaches students how query functions can be used to design a more flexible and dynamic process for importing data. Along the way, students will learn when and how to use query parameters and how to create Power BI project template files.
Topics Covered
•      Understanding Query Design and the ETL Process
•      Introduction to Programming with M
•      Understanding Query Folding
•      Designing with Query Functions
•      Designing with Query Parameters
•      Creating Reusable Project Template Files

Module 03: Developing Custom Data Connectors
This module provides an introduction to developing custom data connectors using the Power Query SDK. The module explains the motivation for creating custom data connectors and walks through how to get started creating custom data connector projects using Visual Studio and the Power Query SDK. Students will learn how to write shared functions in M that are accessible to queries created in Power BI Desktop. The module explains how to package a custom data connector as well as how to test it using Power BI Desktop. The module discusses how to design a custom data connector for a specific type of authentication such as connecting to a Software-as-a-Service (SaaS) applications using OAuth2. Along the way, students will learn to develop a custom data connector that authenticates against Azure Active Directory and extracts data by executing queries using the Microsoft Graph API.
Topics Covered
•      Understanding the Role of Custom Data Connectors
•      Developing with the Power Query SDK
•      Packaging, Deploying and Testing a Custom Data Connector
•      Configuring Authentication for a Custom Data Connector
•      Understanding Authentication Flows with OAuth2
•      Creating a Custom Data Connector for the Microsoft Graph API
 
Module 04: Programming with TypeScript and the D3.js Library
This module begins with quick primer on TypeScript programming for developers already experienced with JavaScript. Students will learn to design and program client-side web applications using TypeScript in Visual Studio. The module explains how to use typed definition files to enable strongly-typed programming when working with JavaScript libraries such as jQuery. The module introduces the D3.js library and explains fundamental D3 programming concepts such as generating SVG graphics, using data binding and enhancing charts with scales and axes. The module demonstrates how to use advanced D3 features to create layouts, to bind to DOM events and to create visual transitions. Along the way, students will learn how to leverage the D3 library by creating bar charts, line charts, area charts and donut charts.
Topics Covered
•      TypeScript Language Primer
•      Getting Started with D3 and SVG Graphics
•      Creating Data-driven Visuals
•      Enhancing Visuals with Scales and Axes
•      Using D3 Layouts
•      Event Handling and Transitions

Module 05: Getting Started with the Power BI Developer Tools
This module introduces students to the developer tools and utilities that are used to develop custom visuals for Power BI. The module explains how to set up a development environment for building custom visuals by installing Node.js and a cross-platform toolchain which includes Node Package Manager (npm), TypeScript, the Power BI Custom Visual Tool (PBIVIZ) and Visual Studio Code. Students will learn about the structure of a Power BI custom visual project as well as how to start a local debugging session in the Node.js environment to test and debug a custom visual in a Power BI report running inside the Power BI Service.
Topics Covered
•      Developing Custom Visuals in Power BI
•      Getting Started with Visual Studio Code
•      Working with Node.js and Node Package Manager
•      Creating Custom Visual Projects with PBIVIZ
•      Understanding the Custom Visual Build Process
•      Testing and Debugging a Custom Visual

Module 06: Developing and Distributing Custom Visuals
This module focuses on how to design and implement custom visuals for Power BI. The module examines the Power BI Visuals API that Microsoft created to assist in the development of custom visuals. Students will learn how to define the capabilities and data mappings for a custom visual and how to program D3-style data binding using categorical data from a Power BI dataset. The module demonstrates how to extend a visual with custom properties as well as how to take advantage of the powerful utility classes that are included along with the Power BI Visuals API. The module demonstrates how to package a custom visual as a PBIVIZ file for distribution and demonstrates adding custom visuals to Power BI Desktop projects and publishing custom visuals to an organization.
Topics Covered
•      Understanding the Power BI Visuals API
•      Defining Visual Capabilities and Data Mappings
•      Programming D3-style Data Binding using Categorical Data
•      Extending a Visual with Custom Properties
•      Packaging and Distributing Custom Visuals

Module 07: Programming the Power BI Service API
This module introduces students to the Power BI Service API and provides an overview of its scope and functionality. The module explains the fundamentals of authenticating with Azure Active Directory and teaches students common programming techniques for authenticating using the Azure Active Directory Authentication Library (ADAL) and working with access tokens and refresh tokens. Students will learn how to call into the Power BI Service API using direct REST calls and also by programming with the .NET client library (Microsoft.PowerBI.Api.dll). Along the way, student will learn how to perform common tasks with the Power BI Service API including uploading PBIX files, patching datasource credentials, redirecting database connection strings and triggering data refresh.
Topics Covered
•      Power BI Service API Overview
•      Registering Applications with Azure AD
•      Programming Authentication and Managing Access Tokens
•      Developing Custom Applications to Publish PBIX Project Files
•      Patching Datasource Credentials and Refreshing Datasets

Module 08: Developing with Power BI Embedded
This module teaches students how to embed Power BI reports and dashboards into custom web applications. The module explains the differences between the two primary development models (user-owns-data versus app-own-data) and discusses when to use Power BI Premium versus when to use the Power BI Embedded service in Microsoft Azure. Students will learn to program with the Power BI Service API to retrieve the data required for embedding reports and dashboard. The module explains when to embed reports using Azure AD access tokens versus when to embed reports using embed tokens generated by the Power BI Service API. Students will learn to write client-side code using the Power BI JavaScript API to embed and interact with reports and dashboards.
Topics Covered
•      Overview of the Embedding Features in Power BI
•      Understanding Premium Capacities versus Embedded Capacities
•      Retrieving Embedding Data using the Power BI Service API
•      Generating and Managing Embed Tokens
•      Using the Power BI JavaScript API to Embed Reports and Dashboards
•      Writing Client-side Code to Interact with an Embedded Report

Module 09: Securing Datasets using Row Level Security
This module builds upon the previous module to teach students how to leverage Row Level Security (RLS) when developing custom applications which use Power BI embedding. The module demonstrates how to implement RLS within a Power BI Desktop project by creating security roles and writing DAX table filter expressions. The module then explains how designing an application with RLS differs depending on whether you are using the user-owns-data model versus the app-owns-data model. Students will learn how to design an RLS security scheme for the user-owns-data model by using the USERNAME function in DAX and a custom table that associates users with the data they are allows to access. Students will also learn to use RLS when developing with the app-owns-data model where your code must generate embed tokens that are restricted by RLS roles.
Topics Covered
•      Understanding Row Level Security (RLS)
•      Implementing RLS in a Power BI Desktop Project
•      Designing for RLS with the User-Owns-Data Model
•      Implementing RLS Dynamically using the USERNAME Function
•      Designing for RLS with the App-Owns-Data Model
•      Generating Embed Tokens Restricted by RLS Roles
 
Module 10: Developing Streaming Datasets and Real-time Dashboards
This module teaches students how to build real-time dashboards in Power BI using streaming datasets, push datasets and hybrid datasets. The module examines differences between streaming datasets and push datasets and explains how to choose between them for a specific scenario. Students will learn how to use the Power BI Service API to create streaming datasets and to push in rows of data in real time from across the Internet. Students will learn how to build a real-time dashboard on top of a streaming dataset using streaming data tiles. The module demonstrates how create push datasets with multiple tables and measures containing DAX expressions. The module concludes with an examination of using the Azure Streaming Analytics service to create real-time dashboards in Power BI which monitor activity arriving at an Azure IoT hub or an Azure event hub.
Topics Covered
•      Introduction to Real-time Datasets
•      Creating a Streaming Dataset using C# Code
•      Designing Dashboards with Streaming Data Tiles
•      Creating a Push Dataset with Real-time Data
•      Integrating Azure Streaming Analytics Jobs

Module 11: Getting Started with R in Power BI
This module provides students with a fast and furious introduction to R as the world’s most popular platform for advanced data analytics and data visualization. Students will learn how to get up and running with R by installing Microsoft R Open and RStudio. The module teaches students R programming fundamentals and explains how to import and load popular R packages. Students will learn to use RStudio to write and test R scripts which import data and generate R visualizations. After learning how to write and test R scripts in RStudio, students will then learn how to integrate R code into a Power BI Desktop project. Along the way, students will learn how to import data into a Power BI Desktop project using an R script as well as how to use the R script visual to enhance a Power BI report with visualizations created using R visualization packages such as lattice and ggplot2.
Topics Covered
•      Overview of R as a Data Analytics Platform
•      R Programming Language Primer
•      Writing and Testing Scripts in RStudio
•      Using R Packages to Generate Charts and Graphs
•      Using an R Script to Import Data into Power BI Desktop
•      Creating Reports using the R Script Visual

Module 12: Developing Custom R Visuals
While it's possible to write and maintain R code inside a Power BI Desktop project, it often makes sense to encapsulate this type of R code using a custom R visual which can be packages and reused across multiple Power BI Desktop projects. This module examines the architecture of a custom R visual and explains how develop a custom R visuals to render charts and graphs in Power BI Desktop reports. Students will learn how to use the PBIVIZ tool to create new custom R visual projects and to define CRAN package dependencies to install and load the R packages that the custom R visual requires. The module explains how to define the capabilities and data mappings for a custom R visual to shape the dataset that will be passed to the R code inside. The module demonstrates how to test and debug custom R visuals as well as how to package them for distribution.
Topics Covered
•      Architecture of a Custom R Visual
•      Defining CRAN Package Dependencies
•      Mapping Data Fields to the R Script File
•      Developing and Debugging the R Script File
•      Packaging and Distributing Custom R Visuals

