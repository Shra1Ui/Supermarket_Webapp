### Python Project: Grocery Store Management System

In this project, we will develop a comprehensive grocery store management application. This will be structured as a three-tier application:

- **Front End**: Developed using HTML, CSS, JavaScript, and Bootstrap for a responsive user interface.
- **Back End**: Utilizes Python with the Flask framework for server-side logic.
- **Database**: MySQL will be used to handle data storage.

#### Installation Instructions

1. Download and install MySQL for Windows from the official [MySQL Installer page](https://dev.mysql.com/downloads/installer/).
2. Install the MySQL connector for Python using the following command:
   ```bash
   pip install mysql-connector-python
   ```

#### Enhancements and Fixes

We've received user feedback on the grocery management system we've built, and here are the tasks to address the feedback and improve the application:

1. **Products Module**: 
   - Add an "Edit" button next to the existing "Delete" button on the products page, allowing users to modify current product details.
   - Implement a new form for adding new Units of Measurement (UOM). For example, you might need to add "Cubic Meter" as a new UOM to accommodate new inventory like wood. This requires updates to both the backend (Python/Flask) and frontend (UI).

2. **Orders Module**: 
   - **Validation**: Add validation on the new order form to ensure that all required fields are correctly filled out. For instance, prevent the submission of orders with an empty customer name, invalid item names, or missing quantities. This enhancement involves making changes to the front-end UI.
   - **Total Price Calculation**: Fix the bug where manually changing the price of an item does not update the grand total. Ensure that the grand total reflects any changes made to individual item prices.
   - **Order Details**: In the orders listing grid, add a "View" button in the last column. Clicking this button should display the details of the selected order, showing individual items along with their quantities and prices.
