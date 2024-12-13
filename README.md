# Online Shopping Management System

This project simulates the working of an online shopping portal where customers can buy products. The application is a purely console-based system implemented using the Java programming language.

## Features

### Admin Panel
- Manage products (add, update, delete)
- Manage customers (add, update, delete)

### Customer Panel
- Browse and buy products
- Add products to the cart
- Make payments

## Class Structure

The project contains a total of 8 class files:

1. **DatabaseConnection.java**: Manages the database connection using JDBC.
2. **Shop.java**: The main starting point of the application.
3. **Admin.java**: Handles admin functionalities like managing products and customers.
4. **Customer.java**: Manages customer-related functionalities like browsing and purchasing products.
5. **Products.java**: Represents the product catalog and its operations.
6. **Cart.java**: Implements the shopping cart functionality.
7. **Payment.java**: Handles payment processing.
8. **Bills.java**: Generates and manages bills for completed transactions.

## Java Concepts Used
- **String Manipulations**: For handling and processing text data.
- **Collections Framework**: Utilized in the form of `ArrayList` for storing dynamic data.
- **JDBC**: For database operations.
- **Exception Handling**: To handle runtime errors gracefully.
- **Inheritance**: For creating relationships between classes.
- **Classes and Objects**: Implements object-oriented principles.
- **BufferedReader**: For taking user inputs efficiently.

## Getting Started

### Prerequisites
- **Java Development Kit (JDK)**: Ensure JDK 8 or higher is installed.
- **Database**: Set up a database for the application and update the connection details in `DatabaseConnection.java`.

### Running the Application
1. Clone the repository:
   ```bash
   git clone https://github.com/Moureeswaran2705/online-shopping-management-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd online-shopping-management-system
   ```
3. Compile the Java files:
   ```bash
   javac *.java
   ```
4. Run the application:
   ```bash
   java Shop
   ```

## Contribution

Contributions are welcome! Feel free to fork this repository and submit pull requests.


## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgements
Special thanks to everyone who contributed to this project!
