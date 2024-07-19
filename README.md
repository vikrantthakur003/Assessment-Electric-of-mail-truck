
ChargePoint Take Home Project
Overview
This repository contains the solution for the ChargePoint Take Home Project. The goal of this project was to develop a scheduling system for charging electric mail trucks. The system needs to efficiently allocate charging resources to trucks within a given time frame.

Project Description
The project involves creating a scheduling algorithm to assign electric mail trucks to available chargers, ensuring that as many trucks as possible are charged to full capacity within the specified time limit.

Features
Truck Class: Represents an electric truck with unique ID, battery capacity, and current charge level.
Charger Class: Represents a charging station with a unique ID and charging rate.
Scheduling Algorithm: Allocates trucks to chargers based on their charging needs and the available time.
Output: Provides a schedule indicating which trucks should be charged on each charger.
Getting Started
Prerequisites
Java Development Kit (JDK) 8 or higher
A Java IDE or command-line tools for compiling and running Java programs
Installation
1. Clone the Repository
2. Navigate to the Project Directory
3. Compile the Java Files
4. Run the Project

Usage
Input: The program prompts for the number of trucks, chargers, and total available time. You will then enter the details for each truck and charger.
Output: The program prints the schedule indicating which trucks should be charged on each charger.

Example
Input
Enter Number of Trucks: 4
Enter Number of Chargers: 2
Enter Total Time: 5
Enter Configuration of Trucks: 
Enter Id of truck: 1
Enter Capacity of Trucks: 100
Enter Current Charge of Truck: 50
Enter Id of truck: 2
Enter Capacity of Trucks: 120
Enter Current Charge of Truck: 60
Enter Id of truck: 3
Enter Capacity of Trucks: 80
Enter Current Charge of Truck: 20
Enter Id of truck: 4
Enter Capacity of Trucks: 90
Enter Current Charge of Truck: 70
Enter Configuration of Chargers: 
Enter Id of Charger: 1
Enter Rate of Charger: 10
Enter Id of Charger: 2
Enter Rate of Charger: 15

Output:
2: 4,1
1: 

This output indicates that:

Charger 2 (ID 2) will charge Truck 4 and Truck 1.
Charger 1 (ID 1) has no trucks assigned due to time constraints.

Contributing
If you have suggestions or improvements, feel free to fork the repository and submit a pull request.

Contact
For any questions or feedback, please contact Vikrant.
