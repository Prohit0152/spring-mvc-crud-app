# Java Spring MVC CRUD App with Hibernate JPA

This is a simple CRUD (Create, Read, Update, Delete) application built using Java Spring MVC framework and Hibernate JPA for data persistence.

## Prerequisites

Before running this application, ensure that you have the following installed:

- Java Development Kit (JDK) version 8 or higher
- Apache Maven
- MySQL or any other relational database management system

## Setup

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Prohit0152/spring-mvc-crud-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd spring-mvc-crud-app
   ```

3. Configure the database settings in `src/main/resources/application.properties`. Replace the placeholders with your database credentials:

   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/your_database_name
   spring.datasource.username=your_username
   spring.datasource.password=your_password
   ```

4. Build the project using Maven:

   ```bash
   mvn clean install
   ```

5. Run the application:

   ```bash
   mvn spring-boot:run
   ```

The application will start running on `http://localhost:8080`.

## Usage

- Open a web browser and navigate to `http://localhost:8080`.
- You will see the home page with options to perform CRUD operations on your data.
- Click on the respective links to add, view, update, or delete records.

## Contributing

Contributions are welcome! Feel free to submit pull requests or open issues for any improvements or bug fixes.

## License

This project is licensed under the [MIT License](LICENSE).

---
