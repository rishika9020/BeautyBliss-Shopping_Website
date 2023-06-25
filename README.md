# BeautyBliss-Online Cosmetic Shopping Website
BeautyBliss is an online cosmetic shopping website developed as a project for the DBMS course. The purpose of this repository is to provide an overview of the project, its functionalities, and instructions on how to set it up locally.

## Project Overview
BeautyBliss is an e-commerce website designed to provide a seamless shopping experience for cosmetic enthusiasts. It allows users to browse a wide range of cosmetic products, choose variants, and easily place orders. The project also includes an administrative panel for managing inventory, brands, sales reports, and order statuses.

## Key Features
<ol> 
<li> **User Registration and Authentication:** </li>
  <ul>
  <li>Users can create new accounts or log in with existing ones.</li>
  <li>Passwords are securely stored using encryption techniques.</li>
  <li>User authentication ensures secure access to user-specific data.</li>
  
  </ul>
  
  <li>**Product Catalog:**</li>
  <ul>
  <li>Extensive collection of cosmetic products with various categories.</li>
  <li>Users can conveniently browse, filter, and search for products.</li>
  <li>Detailed product pages provide comprehensive information, including descriptions, images, and customer reviews.</li>
  </ul>
  
  <li>**Shopping Cart and Checkout:**</li>
  <ul>
  <li>Users can add products to their shopping cart and manage quantities.</li>
  <li>The shopping cart is persisted across sessions for a seamless shopping experience.</li>
  <li>Secure checkout process with multiple payment options.</li></ul>
  
  <li>**Admin Panel:**</li>
  <ul>
  <li>Administrative access for managing inventory, brands, and order statuses.</li>
  <li>Sales reports provide insights into revenue and popular products.</li>
  <li>Efficient order management system to track delivery statuses.</li>
  </ul>
</ol>

## Local Setup
To run the BeautyBliss project locally, follow these steps:
<ol>
  <li>**Install XAMPP:**</li>
  
  -Download and install XAMPP, a web development environment that includes Apache, MySQL, and PHP.
  -Visit the official XAMPP website (https://www.apachefriends.org) and follow the installation instructions for your operating system.
  Clone the Repository:
  
  Clone this repository to your local machine using Git or download the ZIP file and extract it.
  
  Start XAMPP:
  
  Launch XAMPP and start the Apache and MySQL services.
  Import the Database:
  
  Open phpMyAdmin in your web browser by visiting http://localhost/phpmyadmin.
  Create a new database named "Cbpos db".
  Import the database dump file provided in the repository (database_dump.sql) into the newly created database.
  Configure Database Connection:
  
  Locate the config.php file in the repository and open it in a text editor.
  Update the database connection details (host, username, password) to match your local setup.
  Run the Application:
  
  Place the repository files in the appropriate directory of your local web server (e.g., XAMPP's htdocs folder).
  Open your web browser and visit http://localhost/beautybliss to access the application.
  Admin Access:
  
  To access the admin panel, use the following credentials:
  Username: admin
  Password: admin123

</ol>
