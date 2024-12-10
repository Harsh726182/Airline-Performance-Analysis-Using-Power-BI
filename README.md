 Project Title:
 Airline Performance Analysis using Power BI
 
 Problem Statement:
 The airline industry is highly dynamic, with numerous daily operations, including flight scheduling, passenger
 management, and ticket booking. Analyzing and managing this data effectively is crucial for operational
 efficiency, customer satisfaction, and strategic decision-making. This project aims to streamline and analyze
 airline operations using Power BI to uncover insights and improve management processes.
 
 Datasets Used:
 1. Flight Information:
 Fight_Information
 Contains details about flights, including FlightID, FlightNumber, Airline, Destination, and Status.
 2. Passenger Information:
 Passenger_Information
 Contains details about passengers, including PassengerID, FlightID, and SeatNumber.
 3. Ticket Information:
 Ticket_Information
 Contains details about ticket bookings, including TicketID,
 FlightID, and BookingStatus.

 Objective:
 The primary objective of this project is to analyze and visualize the airline data to gain insights into flight
 operations, passenger management, and ticketing. The project will utilize various Power BI features to transform,
 model, and visualize data, ultimately creating a comprehensive dashboard for decision-making.
 
 Tasks which is used in project are given below:
 
 1. Data Extraction and Transformation in Power Query:- Extract data from the provided CSV files and load them into Power BI. Perform data cleaning activities such as removing duplicates, handling missing values, and formatting
 columns appropriately.
 2. Conditional and Custom Columns:- Create a conditional column to classify flights as “best” and “to be improved” based on the status column of the flight information dataset(best for on time and to be improved for the rest).
 3. Column from Examples and Replace Values:- Use the "Column from Examples" feature to extract a substring from the FlightNumber column that represents the flight number. Replace values in the Status column to standardize them (e.g., "On Time" to "On- Time").
 4. Merge Queries and Merge Columns:- Merge the Flight Information and Passenger Information datasets based on FlightID to create a unified dataset for analysis.Merge the SeatNumber and PassengerID columns to create a unique identifier for each passenger.
 5. Create Relationships:- Establish relationships between the datasets (e.g., FlightID as a key between Flight Information and Ticket
 Information) and understand cardinality.
 6. DAX:-Find the total number of passengers who booked a ticket on any specific flight. (example, FL1276) Total number of tickets booked.Create filtered table using DAX to show only best flights information.
7. Visualization:- Create a multi card chart to visualize the number of passengers, flights for each airline.Develop a bar chart to compare the number of passengers per airline.- Use a donut chart to represent the distribution of ticket booking statuses.
 8. Advanced Visualizations: Decomposition Tree and Key Influencer:- Use a decomposition tree to break down the number of flights based on airlines and destination.Implement the Q&A to visualize booking statuses by total tickets.
 9. Interactive Features: Slicers, Bookmarks, and Drill Through:- Add Destination slicer to filter data by Airline, total passengers and total flights.Status.Create bookmarks to save different views of the report for quick access.Implement a drill-through feature to navigate from a page having all airline names to a page that will drill to that specific airline and its destinations and number of flights.
 10. Final Report and Dashboard:- Create a workspace “Airline” and design a comprehensive dashboard that includes the created visuals, a Q&A section, and a summary of key insights. Create a RLS to view only Airline A data across all the sheets of the report and assign it to a colleague on power bi service.Configure the report in the Workspace and set up a schedule refresh to keep the data up to date at 5 pm
 everyday.
