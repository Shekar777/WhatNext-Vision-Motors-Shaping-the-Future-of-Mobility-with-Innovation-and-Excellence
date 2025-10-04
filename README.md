WhatsNext Vision Motors - Salesforce CRM Implementation 🚗

This repository contains the Salesforce implementation for WhatsNext Vision Motors, a project designed to enhance the customer experience and streamline automotive sales and service operations. The solution leverages Salesforce CRM capabilities to create an efficient, transparent, and customer-friendly ordering process.

📝 Project Overview:

WhatsNext Vision Motors aims to revolutionize its mobility sector operations. This Salesforce project is at the core of that transformation, focusing on three key areas:
Enhanced Customer Convenience: Automatically suggesting the nearest dealer to a customer.
Operational Efficiency: Preventing orders for out-of-stock vehicles and automating order status updates.
Process Automation: Reducing manual administrative tasks for staff, allowing them to focus on high-value activities.
This implementation serves as a comprehensive example of using Salesforce to solve real-world business challenges in the automotive industry.

✨ Core Features:

📍 Smart Dealer Assignment: Automatically assigns new customer orders to the nearest dealer location based on the customer's shipping address to ensure faster fulfillment.
✅ Real-Time Stock Validation: Prevents customers from placing an order for a vehicle that is currently out of stock, avoiding confusion and improving order accuracy.
🔄 Automated Order Status Updates: A scheduled batch process runs periodically to update bulk order statuses to 'Pending' or 'Confirmed' based on real-time vehicle stock availability.
🗓️ Test Drive and Service Management: Efficiently tracks customer test drives and service requests, complete with automated email reminders for upcoming appointments.

🛠️ Technical Implementation:

This project is built using a combination of declarative tools and custom Apex code to enforce complex business logic and ensure scalability.

Data Model:

A robust data model forms the foundation of the application, featuring custom objects to store key information:
Vehicle__c: Stores details about each vehicle model, including name, specifications, and Stock_Availability__c.
Dealer__c: Holds information about dealership locations, including addresses for geo-location-based assignment.
Order__c: A central object to track customer orders, linked to Accounts/Contacts, Vehicles, and Dealers.
Test_Drive__c & Service_Request__c: Objects to manage customer appointments and service history.

🧠 What You'll Learn:

 This project provides hands-on experience and a practical demonstration of the following Salesforce concepts:
  Data Modelling: Designing custom objects and relationships (Lookup, Master-Detail).
  Fields and Relationships: Creating custom fields to store business-critical data.
  Lightning App Builder: Building a user-friendly interface for sales and service teams.
  Record-Triggered Flows: Implementing powerful declarative automation for processes like dealer assignment.
  Apex & Apex Triggers: Writing custom server-side logic to enforce complex business rules.
  Batch Apex: Processing large data volumes efficiently without hitting governor limits.
  Scheduled Apex: Automating business processes to run at specific intervals.
