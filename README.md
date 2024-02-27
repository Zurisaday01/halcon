# Halcon Construction Material Distributor Web Application
--------------------------------------------------------

## Overview

This web application automates internal processes for "Halcon," a construction material distributor. It facilitates order tracking for customers and streamlines operations for company personnel.

## Customer-Facing Features

*   **Order Tracking:** Customers can check the status of their orders using a main screen.
    
*   **Input Fields:** Customers provide their customer number and invoice number.
    
*   **Status Display:** Orders are displayed with their current status.
    
*   **Evidence of Delivery:** If an order is marked as "Delivered," a photo of the evidence is shown.
    

## Administrative Dashboard

*   **Access:** Company personnel can access an administrative dashboard.
    
*   **Administrative User:** Default administrative user for managing user registration and roles.
    
*   **Roles:** Users are assigned roles based on departments - Sales, Purchasing, Warehouse, and Route.
    

## Order Life Cycle

1.  **Order Placement:** Customers place orders.
    
2.  **Order Entry:** Salesperson enters order details including invoice number, customer information, and delivery details.
    
3.  **Status Tracking:** Orders start with a status of "Ordered" and progress through "In Process," "In Route," to "Delivered."
    
4.  **Material Handling:** Warehouse personnel manage materials and update order statuses accordingly.
    
5.  **Delivery Verification:** Route personnel upload photos as evidence of loaded and unloaded materials upon delivery.
    

## Order Management

*   **List View:** All orders are listed with search functionality by various criteria.
    
*   **Modification and Deletion:** Orders can be modified or logically deleted.
    
*   **Recovery:** Deleted orders can be viewed separately and restored if necessary.
    

## Security and Data Integrity

*   Access control ensures only authorized users can perform specific actions.
    
*   Data integrity is maintained throughout the order lifecycle.