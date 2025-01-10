
## README for the eMall Project Documentation
# eMall - e-Mobility for All
## Overview
This repository contains the Requirement Analysis and Specification Document (RASD) and the Design Document (DD) for the eMall application. The project was developed as part of the Software Engineering 2 course for the M.Sc. in Computer Science and Engineering.

The eMall application is conceptualized to connect electric vehicle owners with Charging Point Operators (CPOs), enabling seamless booking, pricing management, and notifications. While the implementation of the application is not within the scope of this work, this documentation provides a comprehensive analysis of the system requirements and design.

## Objective
The goal of this project was to:

- Define the functional and non-functional requirements for the eMall application.
- Design a robust system architecture that supports scalability, maintainability, and ease of use.
- Provide a foundation for the implementation of the application by future development teams.
  
## Documents
### Requirement Analysis and Specification Document (RASD):
- Defines the goals, actors, functional and non-functional requirements of the system.
- Provides detailed use case diagrams and descriptions to illustrate system interactions.
- Includes domain assumptions and environmental constraints.

### Design Document (DD):
- Details the system architecture and design decisions.
- Outlines the three-tier architecture, including presentation, application, and data layers.
- Includes class diagrams, sequence diagrams, and component descriptions to guide implementation.

## System Overview
The eMall application is designed with the following objectives in mind:
- Facilitate bookings for charging stations and provide dynamic suggestions based on user schedules and vehicle status.
- Enable CPOs to manage pricing, promotions, and charging station availability.
- Integrate external APIs for features such as map visualization, calendar integration, and vehicle battery monitoring.

### Key Components:
- Actors:
- Customers: Book charging stations, monitor battery levels, and receive notifications.
- CPO Employees: Manage station pricing and promotions.
- External APIs: Provide data on maps, vehicle information, and calendar events.

### Architecture:
Three-tier architecture:
- Presentation Layer: Web and mobile interfaces for different user roles.
- Application Layer: Business logic for bookings, notifications, and station management.
- Data Layer: Persistent storage of users, bookings, and station details.

### APIs:
- Google Maps API for station location visualization.
- Google Calendar API for scheduling recommendations.
- SmartCar API for vehicle and battery status.
- DSO API for dynamic energy pricing updates.
