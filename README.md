---

# Inventory Management System for Retailers

## Overview

This project is an **Inventory Management System (IMS)** developed as part of the **IBM-Nalaiya Thiran Project**. The system automates inventory management for retailers by tracking purchases, sales, and stock levels. It is designed to help retailers manage their inventory effectively, reduce overstocking, and ensure that products are available when needed.

The IMS enables retailers to streamline inventory processes, track stock in real time, and generate reports for better decision-making.

## Features

- **User Authentication**: Registration, login, and user authentication through email and password.
- **Inventory Management**: Real-time tracking of product quantities, sales, and stock levels.
- **Product Movements**: Manage product movements between different locations.
- **Stock Alerts**: Automatic notifications when product stock levels fall below predefined thresholds.
- **Reporting**: Generate reports for stock levels, sales, and product movements.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (Flask framework)
- **Database**: IBM DB2, MySQL
- **Cloud**: IBM Cloud, Kubernetes for container orchestration
- **Security**: SHA-256 for password hashing

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/IBM-EPBL/IBMProject-39093-1660394652.git
   cd IBMProject-39093-1660394652
   ```

2. **Install Dependencies**

   Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**

   Start the application with:

   ```bash
   python app.py
   ```

4. **Access the Application**

   Open your browser and navigate to `http://localhost:5000` (or the port specified in your application configuration).

## Features Breakdown

1. **User Authentication**:
   - Users can register and log in with email and password.
   - Secure password storage using SHA-256 encryption.

2. **Inventory Management**:
   - Track quantities of products across different locations.
   - Add, update, and delete products in the inventory.

3. **Product Movements**:
   - Manage movements of products between different locations within the organization.
   - Ensure accurate tracking of stock levels across various locations.

4. **Threshold Alerts**:
   - Automatic notifications when a product's stock level goes below the set threshold.
   - Helps avoid overstocking or stockouts.

5. **Reporting**:
   - Generate reports on stock levels, sales data, and product movements.

## Database Schema

- **Products Table**: Stores product information such as ID, cost, and available quantity.
- **Locations Table**: Stores location details for each product.
- **Product Movements Table**: Tracks movements of products between different locations.

## Testing

- **Test Case 1**: Check the functionality of the "Add Product" interface.
- **Test Case 2**: Ensure the system alerts users when product quantities fall below the threshold.
- **Test Case 3**: Verify that product updates reflect correctly in the database.

## Advantages

- **Efficient Inventory Management**: Streamlines inventory operations and reduces manual errors.
- **Cost Savings**: Prevents overstocking and reduces waste by ensuring accurate stock levels.
- **Improved Productivity**: Automates inventory processes, saving time and labor.

## Disadvantages

- **Overhead Costs**: The initial setup and infrastructure can be costly, especially for small businesses.
- **Impersonal Service**: The automation of processes may reduce personal interaction with customers.

## Future Scope

- Integrating advanced analytics to predict stock requirements based on historical data.
- Expanding the system to manage multi-warehouse inventories.
- Implementing IoT for real-time stock tracking using RFID tags.

---
