# SCADA Process Simulation – AVEVA InTouch

## Project Overview

This repository presents an industrial SCADA application developed in AVEVA InTouch HMI for monitoring and controlling a simulated production process.

The application simulates liquid storage, mixing, conveyor transport and warehouse management. It also includes user authentication, alarm handling and real-time process monitoring.

The project was developed as part of the Industrial Visualization and Process Monitoring Systems course.

## Project Objectives

The main objective of this project was to design and implement a functional SCADA application capable of monitoring and controlling a simulated industrial process.

The system was designed to provide an intuitive operator interface, process visualization, alarm handling and user management while following the principles of industrial HMI design.

## Main Features

- Three process tanks
- Inlet and outlet valve control
- Real-time liquid level monitoring
- Liquid mixing and concentration calculation
- Conveyor belt simulation
- Automatic product filling
- Warehouse management
- Product classification
- User authentication with role-based access
- Alarm system
- Multi-window HMI interface

## System Components

The application consists of the following modules:

- Tank A
- Tank B
- Mixing Tank C
- Conveyor Belt
- Product Filling Station
- Warehouse
- Alarm System
- User Authentication
  
## Technologies

- AVEVA InTouch HMI
- AVEVA System Platform
- SCADA
- HMI
- Industrial Automation
  
## System Architecture

The simulated production process follows the workflow presented below.

```
Tank A ──┐
         ├──► Mixing Tank C ───► Filling Station ───► Conveyor Belt ───► Warehouse
Tank B ──┘
```

The application continuously monitors the process, calculates the concentration of the mixture, controls the filling process and classifies finished products.

## Process Workflow

1. Raw materials are stored in Tank A and Tank B.
2. Liquids are transferred to Mixing Tank C.
3. The system calculates the mixture concentration.
4. The finished product is transferred to the filling station.
5. Filled products are transported by the conveyor belt.
6. Products are classified and stored in the warehouse.
   
## Screenshots

### Main Dashboard

![Main Dashboard](images/dashboard.png)

---

### Process Window

![Process Window](images/process.png)

---

### Warehouse

![Warehouse](images/warehouse.png)

---

### Tank A

![Tank A](images/tankA.png)

---

### Tank B

![Tank B](images/tankB.png)

---

### Tank C

![Tank C](images/tankC.png)

---

### Login Window

![Login](images/login.png)


## Demonstration

A demonstration video will be added soon.

## Repository Structure

```
docs/
images/
video/
README.md
```

## Future Improvements

Possible future extensions of the project include:

- PLC integration
- OPC UA communication
- SQL database integration
- Historical data logging
- Production reports
- Energy consumption monitoring
  
## Documentation

The project documentation contains a detailed description of the application, implemented process logic, alarm handling, user management and the overall system functionality.

The complete project report is available in the `docs` directory.

## Skills Demonstrated

This project demonstrates practical knowledge of:

- SCADA application development
- HMI design
- Industrial process visualization
- Process control logic
- Alarm configuration
- User authentication
- Industrial automation
- Human-Machine Interface (HMI)
  
## Author

Yevhenii Barannik

Automation and Robotics

Faculty of Electrical Engineering
