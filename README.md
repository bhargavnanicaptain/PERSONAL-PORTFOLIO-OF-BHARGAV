**PORTFOLIO :**
Welcome to my portfolio repository! This repository contains a collection of my projects, skills, and experiences, showcasing my expertise in Java Full=Stack Developer. Feel free to explore the projects and reach out to me for collaborations, job opportunities, or inquiries.

Table of Contents
About Me
Projects
Resume 
Contact
About Me
I am V.T.BHARGAV, a Java Full-Stack Developer with a passion for Web development .  

Projects
**HOSPITAL MANAGEMENT SYSTEM**
Description: The Hospital Management System is a Java-based application designed to streamline patient management, doctor management, and appointment booking within a hospital setting. The system leverages JDBC (Java Database Connectivity) to interact with a MySQL database, allowing seamless storage and retrieval of patient and doctor information.

FEATURES :

Patient Management: Allows the addition of new patients, viewing existing patient records, and searching for patients by ID.
Doctor Management: Facilitates the viewing of doctor profiles, including their names and specializations.
Appointment Booking: Enables the booking of appointments between patients and doctors, ensuring efficient scheduling within the hospital.

FILE STRUCTURE : 

The project consists of the following Java files : 
Patient.java: Defines the Patient class responsible for managing patient-related operations such as adding patients, viewing patient records, and searching for patients by ID.
Doctor.java: Contains the Doctor class, which handles doctor-related functionalities such as viewing doctor profiles and checking doctor availability.
HospitalManagementSystem.java: The main entry point of the application, orchestrating user interactions and integrating patient, doctor, and appointment functionalities.

IMPLEMENTATION DETAILS : 

PATIENT MANAGEMENT : 
   The “patient class” encapsulates methods for managing patient data. It includes functions for adding new patients to the database, retrieving patient records, and validating patient IDs.

DOCTOR MANAGEMENT  :
 In the “Doctor class”, functionalities related to doctor management are implemented. This includes viewing doctor profiles and checking doctor availability for appointments.
 

APPOINTMENT BOOKING : 
The “HospitalManagementSystem class” orchestrates the booking of appointments between patients and doctors. It integrates patient and doctor functionalities to facilitate appointment scheduling and ensures that appointments are booked efficiently.

DATABASE CONNECTIVITY  : 

The application connects to a MySQL database using JDBC. The database schema includes tables for storing patient information, doctor details, and appointment records. The system leverages prepared statements to execute SQL queries securely and efficiently.

DEVELOPMENT ENVIRONMENT : 

The project was developed using IntelliJ IDEA, a powerful integrated development environment for Java development. IntelliJ IDEA provides advanced features such as code completion, refactoring, and debugging, enhancing developer productivity.

EXTERNAL LIBRARIES : 
 The project was developed using IntelliJ IDEA, a powerful integrated development environment for Java development. IntelliJ IDEA provides advanced features such as code completion, refactoring, and debugging, enhancing developer productivity.

CONCLUSION : 
The Hospital Management System offers a comprehensive solution for managing hospital operations, including patient management, doctor profiles, and appointment scheduling. Its intuitive interface, robust database connectivity, and integration with external libraries make it an ideal choice for hospitals seeking to streamline their administrative processes.

Technologies Used: The project utilizes Java programming language, JDBC (Java Database
                Connectivity), and MySQL database for implementation. IntelliJ IDEA IDE is employed for project
                development and management.
Link: https://github.com/bhargavnanicaptain/HOSPITAL-MANAGEMENT-SYSTEM.git

**HOSTEL MANAGEMENT SYSTEM**
Description: INTRODUCTION : 

The Hostel Reservation System is a Java application developed to streamline the process of managing hostel reservations. It provides a comprehensive set of features to facilitate reservation creation, viewing, updating, and deletion. The system leverages JDBC (Java Database Connectivity) to interact with a MySQL database, ensuring efficient data management and retrieval.

SYSTEM ARCHITECTURE : 
The system architecture follows a client-server model, where the Java application serves as the client interacting with the MySQL database server. It utilizes JDBC to establish a connection to the database and perform CRUD (Create, Read, Update, Delete) operations on reservation data.

CLASS OVERVIEW : 
The main class of the system is HostelReservationSystem, which contains the entry point main method and various utility methods for handling reservations. Other classes include java.sql.DriverManager, java.sql.Connection, java.sql.Statement, java.sql.ResultSet, and java.util.Scanner.

METHOD DETAILS : 
reserveRoom(Connection connection , Scanner scanner)
Allows users to reserve a room by entering guest details.
Constructs an SQL INSERT statement to add reservation data to the database.
viewReservations(Connection connection)
Retrieves and displays all current reservations stored in the database.
Executes an SQL SELECT statement to fetch reservation data and formats it for display.

getRoomNumber(Connection connection, Scanner scanner)
Prompts users to enter a reservation ID and guest name to retrieve the corresponding room number.
Constructs an SQL SELECT statement with a WHERE clause to fetch the room number based on the provided reservation ID and guest name.

updateReservation(Connection connection , Scanner scanner)
Enables users to update an existing reservation by providing a reservation ID.
Prompts users to enter new guest details and constructs an SQL UPDATE statement to modify the reservation.

deleteReservation(Connection connection, Scanner scanner)
Allows users to delete a reservation from the database by specifying the reservation ID.
Constructs an SQL DELETE statement to remove the reservation based on the provided ID.

DATABASE CONNECTIVITY
The application connects to a MySQL database named "hostel" running locally on port 3306. It utilizes the JDBC API to establish a connection to the database using the provided URL, username, and password.

ERROR HANDLING
The application handles exceptions such as ClassNotFoundException, SQLException, and InterruptedException. It prints error messages to the console to inform the user about any database-related issues or unexpected errors.

USAGE : 
Users can interact with the application by selecting options from the menu displayed on the console. Each option corresponds to a specific operation related to hostel reservations, such as reserving rooms, viewing reservations, updating reservation details, and deleting reservations.

CONCLUSION : 
The Hostel Reservation System offers a convenient and efficient solution for managing hostel reservations. With its user-friendly interface and robust database connectivity, the system simplifies reservation management tasks and ensures smooth operation.

FUTURE ENHANCEMENTS 
Future enhancements to the system may include : 
Implementing user authentication and authorization features.
Adding support for multi-threading operations to improve performance.
Enhancing the user interface with graphical components for a more intuitive experience.

Technologies Used: The project utilizes Java programming language, JDBC (Java Database
                Connectivity), and MySQL database for implementation. IntelliJ IDEA IDE is employed for project
                development and management.
Link: https://github.com/bhargavnanicaptain/HOSTEL-MANAGEMENT-SYSTEM.git

**SMART RAILWAY PLATFORM WITH  PASSENGER SAFETY  GATES TO PREVENT LEVEL CROSSING USING IOT**
Description : 
In today’s scenario Railway safety becomes the most important aspect of railways all over the world. As we know the Railways is the cheapest mode of transportation, and due to manual operation, accidents are likely to happen. There are 30348 level crossings on Indian Railways across the country.18785 are manhandled and 11563 are non-man handled level crossings out of 303048 level crossings. To avoid accidents over the previous five years 4792 level crossings have been removed by the respective Zonal railways of Indian Railways. The Indian ministry of Railways made a decision focusing on eliminating all level crossings on availability of railway funds, which could be controlled automatically. The suggested system helps in achieving the safety and to prevent accidents at the level crossings that are non-man handled. The Automatic railway gate control system can be employed under non manhandled level crossing where the chances of accidents are higher and requirement of reliable operation are there. Since, the proposed model suggests an automatic system, it helps in reducing the error which is in manual operation and it will be used as a highly reliable source. The proposed model of automatic gate control at level crossings is highly economical based on the arrangement done by using Arduino and Servo motor which makes the design for use in almost every non man handled that is unmanned railway crossings. The proposed model suggests a design to control a railway level-crossing by servo motor using Arduino controller. The connection of the motor is done from Arduino with the help of a driver IC for controlling the railway gate. Two IR sensors are used to detect arrival of the train and two are used to detect departure of the train. IR sensors are checking the complete closing of the gate.
Technologies Used : We employed IoT technology, utilizing the NSP232 microcontroller and Arduino IDE, to manage the movement of servo motors and control the activity of a buzzer. This was achieved through the implementation of the C programming language.

**GARBAGE MONITORING AND AUTO ALERTING SYSTEM TO MUNICIPALITY USING IOT**
Description : Each day, our lives become more dependent on 'embedded systems', digital information technology that is embedded in our environment. More than 98% of processors applied today are in embedded systems, and are no longer visible to the customer as 'computers' in the ordinary sense. An Embedded System is a special-purpose system in which the computer is completely encapsulated by or dedicated to the device or system it controls. Unlike a general-purpose computer, such as a personal computer, an embedded system performs one or a few predefined tasks, usually with very specific requirements. Since the system is dedicated to specific tasks, design engineers can optimize it, reducing the size and cost of the product. Embedded systems are often mass- produced, benefiting from economies of scale.

The increasing use of PC hardware is one of the most important developments in high-end embedded systems in recent years. Hardware costs of high-end systems have dropped dramatically as a result of this trend, making some projects feasible which previously would not have been done because of the high cost of non-PC-based embedded hardware. But software choices for the embedded PC platform are not nearly as attractive as the hardware.

Typically, an embedded system is housed on a single microprocessor board with the programs stored in ROM. Virtually all appliances that have a digital interface -- watches, microwaves, VCRs, cars -- utilize embedded systems. Some embedded systems include an operating system, but many are so specialized that the entire logic can be implemented as a single program.  Physically, Embedded Systems range from portable devices such as digital watches and MP3 players, to large stationary installations like traffic lights, factory controllers, or the systems controlling nuclear power plants. The applications software on such processors is sometimes referred to as firmware.

Technologies Used :We implemented an Internet of Things (IoT) solution for our Garbage Monitoring and Auto-Alerting System to Municipality project.<br> Employing the Arduino IDE and utilizing the NSP232 Micro Controller, we controlled the working activity of the Ultrasonic sensor through a C language code, seamlessly integrated into the Arduino IDE.

Skills
**JAVA**: *****
**MYSQL**: *****
**JDBC**: *****
**HTML**: *****
**CSS**:*****
**JAVA SCRIPT**: *****
**LINUX**: ****
**C# PROGRAMMING LANGUAGE**: ****
**C PROGRAMMING LANGUAGE**: ****

...
Contact
Feel free to reach out to me at vallamkondabhbargav@gmail.com or connect with me with 8074588232. I'm open to collaboration, networking, and new opportunities!

