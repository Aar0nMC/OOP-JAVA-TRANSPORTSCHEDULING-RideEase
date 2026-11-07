

# RideEase: A Route Monitoring and Commuter Assistance System

## Overview

RideEase is a Java-based transportation application designed to help commuters check predefined routes, view estimated travel distances, and identify reported traffic conditions before traveling. The system provides route information and traffic status updates maintained by an administrator.

Administrators can manage route records and manually update their traffic conditions using predefined statuses: Clear, Moderate, Heavy, and Closed. When a route is marked as Heavy or Closed, the system displays a warning to inform commuters about the reported condition.

The application also provides guidance and external booking links for transportation services such as Grab and Angkas. Actual ride reservations and transactions are completed through the respective third-party platforms.

## Key Features

- **Route Information** – Displays predefined transportation routes, including their starting points, destinations, and estimated distances.
- **Route Selection** – Allows commuters to select their starting point and destination to view available route information.
- **Traffic Status Monitoring** – Displays the reported traffic condition of each route using Clear, Moderate, Heavy, and Closed statuses.
- **Traffic Warning** – Provides an in-app warning when a selected route is marked as Heavy or Closed.
- **Route Management** – Allows administrators to add, maintain, and update predefined route information.
- **Traffic Status Management** – Enables administrators to manually update the reported traffic condition of routes.
- **Ride Booking Assistance** – Provides instructions and external links to transportation services such as Grab and Angkas.

## Target Users

- **Administrators** – Individuals responsible for maintaining route information and updating traffic statuses.
- **Passengers and Commuters** – Individuals who want to check available routes, estimated distances, and reported traffic conditions before traveling.

## Technologies and Concepts

The system will be developed using Java and object-oriented programming principles.

- Java for application development.
- Classes and objects for organizing route and system information.
- Encapsulation and abstraction for managing data and system operations.
- Methods for implementing route monitoring and management functions.
- Arrays or collections for storing predefined routes and related information.
- Exception handling for managing invalid inputs and unexpected operations.

## Limitations

- The system does not use live traffic APIs or automatically retrieve real-time traffic information.
- Traffic conditions are manually updated by the administrator.
- It does not provide continuous GPS tracking or automatic location monitoring.
- It does not handle actual ride bookings, driver assignments, payments, or trip management.
- Traffic information may not always reflect the current road situation.
- It does not provide push notifications or turn-by-turn navigation.
- It does not directly integrate with third-party transportation platforms.

