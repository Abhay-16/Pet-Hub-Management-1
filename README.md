# Pet Hub Management System

## Overview
The Pet Management System is a web application designed to manage pet-related services, including product listings, appointments, orders, and reviews. It enables users to explore pet products, book appointments, and manage their purchases efficiently.

## Features
- **User Authentication**: Registration, login, and session management.
- **Pet Products Management**: Add, update, delete, and view pet products.
- **Cart & Wishlist**: Add products to the cart and wishlist.
- **Appointment Booking**: Schedule veterinary consultations.
- **Reviews & Ratings**: Users can provide feedback.
- **Admin Panel**: Manage users, products, and orders.

## Technologies Used
- **Backend**: Java (Servlets, JSP)
- **Database**: MySQL
- **Frontend**: HTML, CSS, JavaScript
- **Frameworks/Libraries**: Bootstrap

## Project Structure
```
PetManagementSystem/
│── src/main/java/com/MVC
│   ├── Controller/  # Contains Servlets for handling requests
│   ├── Model/       # Data models (e.g., User, Product, Order)
│── webapp/
│   ├── Assets/      # Images and static files
│   ├── img/         # UI images
│   ├── imghome/     # Home page templates
│   ├── JSP Files    # UI pages (JSP files)
│── WEB-INF/
│   ├── web.xml      # Deployment descriptor
│── lib/
│   ├── mysql-connector-j-8.0.33.jar  # Database connector
│   ├── servlet-api.jar  # Servlet dependencies
│── .gitignore
│── pom.xml
│── README.md
```

## Setup & Installation
1. **Clone the Repository**:
   ```sh
   git clone <repository-url>
   ```
2. **Import the Project**:
   - Open the project in Eclipse/IntelliJ.
   - Configure Tomcat server.
3. **Setup Database**:
   - Import `pet_management.sql` into MySQL.
   - Update database credentials in `web.xml`.
4. **Run the Project**:
   - Deploy on Tomcat and access via `http://localhost:8080/PetManagementSystem`

## Contributors
- **Developer**: Abhay Itagi

