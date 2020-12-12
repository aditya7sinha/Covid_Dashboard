![covid-19](covid_thumbnail.jpg )

# WIREFRAME DESIGN OF WEB PAGE
Dashboard Page

![page1 ](page1.jpg)

- For Mobile

![mobilepage1>](mobilepage1.jpg)

Guidelines Page

![page2](page2.jpg)

- For Mobile

![mobilepage2>](mobilepage2.jpg)

News Page

![page3](page3.jpg)

- For Mobile 

![mobilepage3>](mobilepage3.jpg)

# **Software Requirements Specification**
# *COVID-19 Dashboard*
#### *Prepared By Luis Thelonious Fatas Arana*
#### *Prepared By Aditya Sinha*
---
## 1 - Introduction

### 1.1 Purpose

This document will set the foundations, guidelines and rules to build a COVID-19 monitoring website, where users will be able to filter the information by country and see detailed graphs of the pandemic.

### 1.2 Document conventions

The following is a list of the conventions used throughout this and other related documents.

Convention | Definition |
-----------|------------|
js         | Javascript programming language |
md         | Markdown markup language |

### 1.3 Intended audience and reading suggestions

The purpose of the project is educational and it is intended to solidify and improve programming and presentational skills with web technologies. Its final use will be published by the developers as part of a portfolio to reach possible employers and the general public.

### 1.4 Project scope

A monitoring system/dashboard aims to present information in a clear, tidy and direct manner to aid with information understanding, in this case, about the COVID-19 pandemic. It allows to see the development of the pandemic in the world as a whole, with several statistics shown through graphs, meters, text and other presentational means. All of this will be done with web technologies, mainly *vanilla js*, *html* and *css*, with the use of external libraries like *charts.js*. The presentation should be comfortable for use and for the acquisition of information.

### 1.5 References

- [Software Requirements Specification document with example](https://krazytech.com/projects/sample-software-requirements-specificationsrs-report-airline-database)

## 2 - Overall Description

### 2.1 Product Perspective

A dashboard of the pandemics evolution will consist of:

- **World details**: total number of cases, total number of recovered, total number of deaths. Total number of countries, total number of affected countries. A graph of the evolution of cases, recovered and deaths.

- **Country details**: same as **World Details**, but specific to a country.

### 2.2 Product Features

![](covid-app-erm.svg)

### 2.3 User Class and Characteristics

Users interacting with the app should be able to get detailed information regarding the global evolution and current state of the COVID-19 pandemic from the main dashboard, and access any specific country's details by performing a search or by choosing a country from the countries selector element.

When the user performs a search or selects a country, the main dashboard's content will change to reflect the new data specific to that country.

### 2.4 Operating Environment

The operating environment for the app will be comprised of the following elements:

- Client Browser
- API Server
- Any Operating System

### 2.5 Design and Implementation Constraints

1. Global Schema (API Endpoints)
2. Fetch queries for the needed API Endpoints
3. Response management and data formatting
3. Dashboard generation

### 2.6 Assumption Dependencies

This app assumes the COVID-19 API is working and public, so that the app can fetch all the needed data from their database and display it to the end-users.

## 3 Requirements Specifications
Covid-19 Dashboard provides a friendly interface for users to get live count of cases registered at that moment.  

### 3.1 External Interface Requirements
The only link to an external system is the link to the POSTMAN for API calls using REST API. Requests will be made using POST and GET method.

### 3.1 Functional Requirements
#### - Responsive Web Site
Application should be adaptable to devices of different aspect ratios.
#### - Select Country
User should have option to select a particular country and get live data and graphs for the same.
#### - Additional Information
The Web application should also provide additional information like possible front runner vaccines their trials and latest news.
#### - Deaths,Cases and Recoveries
Provide tiles showing total count the above clearly.
#### - Graphical Representation
Provide two graphs for better representation of the data.
Graphs | To Represent  |
-----------|------------|
Bar Graph        | - |
Line Charts    | - |
## 5 Nonfunctional Requirements

### 5.1 Performance Requirements
- The page must load within 2 seconds.
- The system must meet Web Content Accessibility Guidelines WCAG 2.1.
<!-- ### 5.2 Safety Requirements
### 5.3 Security Requirements
### 5.4 Software Quality Attributes
 -->


