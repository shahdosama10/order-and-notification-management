# Orders and Notifications Management Module

## Introduction
This repository contains the implementation of the "Orders and Notifications Management" module with java and spring boot web service 

## Module Overview
The "Orders and Notifications Management" module is responsible for facilitating online purchases, order management, and notification creation based on various actions during the order process.

## Features
### 1. Product Display
- Display a list of all available products for purchase, including details such as serial number, name, vendor, category, price, and remaining quantity in each category.

### 2. Customer Account Management
- Allow customers to create accounts and set a specific balance for future purchasing operations.

### 3. Order Placement
- Enable customers to place simple orders (single or multiple products) and compound orders (including orders for friends in different locations to reduce shipping fees).

### 4. Order Details
- Provide the ability to list details for both simple and compound orders.

### 5. Order Shipment
- Implement order shipment functionality, deducting shipping fees from the customer's account for simple orders and from all participating customers for compound orders.

### 6. Notifications Management
- Create notification templates for order placement and shipment.
- Manage templates, subjects, content, available languages, channels (email, SMS), and placeholders.
- Support at least two different notification templates for order placement and shipment.

### 7. Notifications Queue
- Implement a notifications queue to track notifications that are yet to be sent.
- Allow listing the current content of the queue.

### 8. Order Cancellation
- Allow customers to cancel order placement or shipping within a pre-configured automated duration.

### 9. Automated Queue Clearance
- Automatically remove messages from the queue after a configured time to simulate successful sending.
- Provide live statistics for successful notifications, including the most notified email address/phone number and the most sent notification template.

## Usage


1. **Compile and Run**
2. **Use the collection of endpoints to try the above features**

## Contributing

We would like to thank the following contributors to this project:



[Ahmed Saad](https://github.com/ahmedsaad123456).

[Shahd Osama](https://github.com/shahdosama10).

[Salma Abdelaziz](https://github.com/Salmaabdelaziz271).

[Adham Khaled](https://github.com/Adham-K-Fahmy).

Special thanks to everyone who has helped make this project better.



