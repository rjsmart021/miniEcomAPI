Project Requirements


Customer and CustomerAccount Management: Create the CRUD (Create, Read, Update, Delete) endpoints for managing Customers and their associated CustomerAccounts:
Create Customer: Implement an endpoint to add a new customer to the database. Ensure that you capture essential customer information, including name, email, and phone number.
Read Customer: Develop an endpoint to retrieve customer details based on their unique identifier (ID). Provide functionality to query and display customer information.
Update Customer: Create an endpoint for updating customer details, allowing modifications to the customer's name, email, and phone number.
Delete Customer: Implement an endpoint to delete a customer from the system based on their ID.
Create CustomerAccount: Develop an endpoint to create a new customer account. This should include fields for a unique username and a secure password.
Read CustomerAccount: Implement an endpoint to retrieve customer account details, including the associated customer's information.
Update CustomerAccount: Create an endpoint for updating customer account information, including the username and password.
Delete CustomerAccount: Develop an endpoint to delete a customer account.
Product Catalog: Create the CRUD (Create, Read, Update, Delete) endpoints for managing Products:
Create Product: Implement an endpoint to add a new product to the e-commerce database. Capture essential product details, such as the product name and price.
Read Product: Develop an endpoint to retrieve product details based on the product's unique identifier (ID). Provide functionality to query and display product information.
Update Product: Create an endpoint for updating product details, allowing modifications to the product name and price.
Delete Product: Implement an endpoint to delete a product from the system based on its unique ID.
List Products: Develop an endpoint to list all available products in the e-commerce platform. Ensure that the list provides essential product information.
Order Processing: Develop comprehensive Orders Management functionality to efficiently handle customer orders, ensuring that customers can place, track, and manage their orders seamlessly.
Place Order: Create an endpoint for customers to place new orders, specifying the products they wish to purchase and providing essential order details. Each order should capture the order date and the associated customer.
Retrieve Order: Implement an endpoint that allows customers to retrieve details of a specific order based on its unique identifier (ID). Provide a clear overview of the order, including the order date and associated products.
Track Order: Develop functionality that enables customers to track the status and progress of their orders. Customers should be able to access information such as order dates and expected delivery dates.


Database Integration:
Utilize Flask-SQLAlchemy to integrate a MySQL database into the application.
Design and create the necessary Model to represent customers, orders, products, customer accounts, and any additional features.
Establish relationships between tables to model the application's core functionality.
Ensure proper database connections and interactions for data storage and retrieval.
Data Validation and Error Handling:
Implement data validation mechanisms to ensure that user inputs meet specified criteria (e.g., valid email addresses, proper formatting).
Use try, except, else, and finally blocks to handle errors gracefully and provide informative error messages to guide users.
User Interface (Postman):
Develop Postman collections that categorize and group API requests according to their functionality. Separate collections for Customer Management, Product Management, Order Management, and Bonus Features should be created for clarity.
GitHub Repository:
Create a GitHub repository for the project and commit code regularly.
Maintain a clean and interactive README.md file in the GitHub repository, providing clear instructions on how to run the application and explanations of its features.
Include a link to the GitHub repository in the project documentation.
