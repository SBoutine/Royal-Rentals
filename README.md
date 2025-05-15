# Royal Rentals - Vehicle Leasing System

## Overview

Royal Rentals is a Java-based vehicle leasing system that simulates the operations of a vehicle rental service. It allows users to manage vehicles, clients, and leasing operations through a console-based interface. The system supports various vehicle types, including gasoline cars, electric cars, diesel trucks, and electric trucks.

## Features

- **Vehicle Management**
  - Add, delete, update, and list vehicles by category
  - Supports multiple vehicle types with unique attributes
  - Automatic plate number generation for each vehicle

- **Client Management**
  - Add, edit, and delete clients
  - Track client information (name and phone number)

- **Leasing Operations**
  - Lease vehicles to clients
  - Return leased vehicles
  - View vehicles leased by a specific client
  - View all leased vehicles

- **Additional Operations**
  - Find the truck with the largest capacity
  - Create copies of electric truck arrays

## Class Structure

The system is organized into several packages and classes:

### Packages
- `clientPackage`: Contains the `Client` class
- `driverPackage`: Contains the main `DriverRoyalRentals` class
- `vehiclePackage`: Contains all vehicle-related classes

### Key Classes
- **Vehicle Hierarchy**
  - `Vehicle` (abstract base class)
  - `Car`(extends Vehicle)
    - `GasolineCar`
    - `ElectricCar`
  - `Truck`(extends Vehicle)
    - `DieselTruck`
    - `ElectricTruck`
- **Support Classes**
  - `Lease`: Manages leasing information
  - `Client`: Represents rental clients

## How to Run

1. Compile all Java files:
   ```bash
      javac driverPackage/DriverRoyalRentals.java
2. Run the main class:
   ```bash
      java driverPackage.DriverRoyalRentals

3. Follow the on-screen menu prompts to interact with the system.

## Usage

The system provides two modes:
1. **Interactive Menu-Driven Interface**: Allows manual operation of all features
2. **Predefined Scenario**: Demonstrates the system with preloaded test data

## Design Patterns

- **Inheritance**: Used extensively in the vehicle class hierarchy
- **Encapsulation**: All classes properly encapsulate their data
- **Polymorphism**: Used in vehicle operations through method overriding

## Testing

The system includes:
- A predefined scenario that tests all major functionalities
- Comprehensive `equals()` methods for object comparison
- Input validation throughout the interface

## Author

**Sara Boutine**  


