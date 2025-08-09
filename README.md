FoodFrenzy is an all-in-one platform crafted to efficiently handle customer management, inventory tracking, and order processing. Featuring secure user authentication and role-based access control, it ensures that admins and staff members can access the system according to their privileges. Powered by Spring Boot and Thymeleaf, and backed by a robust MySQL database, FoodFrenzy delivers a smooth and reliable experience for restaurant operations.


![767001_food_app_logo_reveal-nixmotion](https://github.com/user-attachments/assets/6b14de88-1114-40fb-90fd-d2a85c8559a3)



Key Features
Customer Management: Add, update, and remove customer profiles effortlessly.

Inventory Tracking: Monitor stock levels, manage pricing, and track inventory items.

Order Processing: Handle order creation, updates, and real-time status tracking.

Secure Authentication: Login system that safeguards user credentials.

Role-Based Access Control: Customize permissions for admins and staff members.

Dynamic UI: Responsive front-end powered by Thymeleaf templates.

Database Integration: Reliable MySQL storage for all data.

Technology Stack
Backend: Spring Boot, Java 8, Spring MVC, Spring Data JPA (Hibernate)

Frontend: Thymeleaf, HTML5, CSS3, JavaScript

Database: MySQL

Development Tools: Eclipse, Spring Tool Suite (STS)

Build Tool: Maven



Prerequisites
Before running the application, please ensure the following software is installed:

Java Development Kit (JDK) 8

MySQL Server

Maven build tool

IDE such as Eclipse or Spring Tool Suite (STS)

## Setup and Installation
# 🎁 Donate

<a href="https://buymeacoffee.com/1122anuragg">
  <img src="https://user-images.githubusercontent.com/25067102/154570688-9e143f2b-fee3-4b05-a9d2-a7a3013b2b51.png" />
<a/>
1. Clone the repository:
    ```bash
    git clone https://github.com/your-repository-url/FoodFrenzy.git
    ```

2. Navigate to the project directory:
    ```bash
    cd FoodFrenzy
    ```

3. Configure MySQL Database:
    - Create a new MySQL database.
    - Update `application.properties` with your MySQL credentials:
      ```properties
      spring.datasource.url=jdbc:mysql://localhost:3306/foodfrenzy
      spring.datasource.username=root
      spring.datasource.password=root
      spring.jpa.hibernate.ddl-auto=update
      ```

4. Run the project:
    ```bash
    mvn spring-boot:run
    ```

5. Access the application:
    - Navigate to `http://localhost:8080` in your browser. 
## Website Screenshot

Here is a preview of the FoodFrenzy interface:

![48cd58175418045 64b37a1b02caf](https://github.com/user-attachments/assets/228fc69e-8bf7-4b82-98fd-2ffedcab6c40)




![image](https://github.com/user-attachments/assets/3d407958-efbe-449f-b4e1-5b08b9f8a28b)


![Screenshot 2024-08-24 194958](https://github.com/user-attachments/assets/c11a4710-69f8-42fd-b9d7-2b5278b2c8a3) 


![Screenshot 2024-08-24 220831](https://github.com/user-attachments/assets/d3cd3cdd-cda5-460a-a253-24e45cf600b0)  
![Screenshot 2024-08-24 195054](https://github.com/user-attachments/assets/733afb94-a251-4a6d-86a4-3a124e8c3469)
![Screenshot 2024-08-24 195106](https://github.com/user-attachments/assets/ef09886f-7936-4ef7-b01e-4da0008fd047) 
![Screenshot 2024-08-24 195121](https://github.com/user-attachments/assets/219272b8-3938-4b7f-ba78-817e507beee9)
![Screenshot 2024-10-03 093051](https://github.com/user-attachments/assets/d4da51a4-dfe8-4cc1-ae49-745f6e1ae17a) 
![Screenshot 2024-10-03 093106](https://github.com/user-attachments/assets/09c31cf7-e960-4ea5-a858-8807317486b7)
![Screenshot 2024-10-03 093133](https://github.com/user-attachments/assets/b1da1faa-7e71-49be-972a-432029a1e7c3) 
![Screenshot 2024-10-03 093424](https://github.com/user-attachments/assets/b0a9a1e2-6018-475a-95fc-d64980677ee7) 
![Screenshot 2024-10-03 093437](https://github.com/user-attachments/assets/b860f905-2c35-4af3-9df8-38cda70b4406)

## Project Structure

```bash
src/
├── main/
│   ├── java/
│   │   └── com.example.foodfrenzy/
│   │       ├── controller/      # Contains all controllers
│   │       ├── model/           # Contains entity classes
│   │       ├── repository/      # Repository interfaces for database interaction
│   │       └── service/         # Service layer with business logic
│   ├── resources/
│   │   ├── templates/           # Thymeleaf templates for views
│   │   ├── static/              # Static assets (CSS, JavaScript)
│   │   └── application.properties  # Project configuration
│   └── webapp/
│       └── WEB-INF/
│           └── views/           # Additional view files
└── test/                        # Test cases for unit testing
