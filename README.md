# DineTime

DineTime is a restaurant table reservation web application where restaurants and customers can register, log in, and manage their accounts through personalized dashboards.

## Features

- User registration and login (separate roles for customers and restaurants)
- Table reservation system with queue-based management
- Reservation sorting using merge sort (by time)
- File-based data storage (no external database)
- Custom data structures (Queue, etc.)
- Role-based dashboards for customers and restaurant owners
- Responsive design using Bootstrap

## Tech Stack

| Layer         | Technology              |
|---------------|--------------------------|
| Frontend      | HTML, CSS, JavaScript, Bootstrap |
| Backend       | Java Servlets and JSP    |
| Build Tool    | Maven                    |
| Server        | Apache Tomcat 11         |
| IDE           | IntelliJ IDEA            |

## Project Structure

```

DINETIME-MASTER/
├── .idea/                       # IntelliJ IDEA settings
├── .mvn/                        # Maven Wrapper
├── mvnw, mvnw\.cmd               # Maven scripts
├── pom.xml                      # Maven config
├── src/
│   └── main/
│       ├── java/
│       │   └── com/dinetime/dinetime/
│       │       ├── Classes/                # Core models
│       │       ├── DataStructures/         # Custom structures (Queue, etc.)
│       │       ├── Handlers/               # Utilities
│       │       ├── ReservationServlets/    # Reservation logic
│       │       ├── RestaurantServlets/     # Restaurant operations
│       │       └── UserServlets/           # User login/registration
│       └── webapp/
│           ├── css/
│           ├── js/
│           ├── jsp/
│           └── WEB-INF/
├── WebAppData/                 # Data stored in files
└── target/                     # Compiled output

````

## Setup and Running the Project

### Prerequisites

- Java JDK 8 or above
- Apache Tomcat 11
- IntelliJ IDEA (or any IDE with Maven support)

### Installation and Deployment

1. **Clone the repository**

```bash
git clone https://github.com/vishwa-aloka-16/dinetime.git
cd dinetime
````

2. **Open in IntelliJ IDEA**

   * Import as a Maven project

3. **Build the project**

```bash
./mvnw clean install
```

4. **Deploy the `.war` file**

   * Locate the `.war` file in the `target/` directory
   * Copy it to your Tomcat `webapps/` folder
   * Or configure Tomcat directly in your IDE

5. **Start the Tomcat server**

```bash
cd /path/to/tomcat/bin
startup.bat    # Windows
./startup.sh   # Linux/Mac
```

6. **Access the application**

Open your browser and visit:

```
http://localhost:8080/dinetime
```

## Test Login Credentials

Here are some sample users for testing:

### Admin

| Email                                                 | Name         | Password |
| ----------------------------------------------------- | ------------ | -------- |
| [vishwaaloka@gmail.com](mailto:vishwaaloka@gmail.com) | Vishwa Aloka | 1234567  |

### Restaurant Owners

| Email                                               | Name        | Password |
| --------------------------------------------------- | ----------- | -------- |
| [owner1@gmail.com](mailto:owner1@gmail.com)         | Owner 1     | 1234567  |
| [owner2@gmail.com](mailto:owner2@gmail.com)         | Owner 2     | 1234567  |
| [owner3@gmail.com](mailto:owner3@gmail.com)         | Owner 3     | 1234567  |
| [owner4@gmail.com](mailto:owner4@gmail.com)         | Owner 4     | 1234567  |
| [owner5@gmail.com](mailto:owner5@gmail.com)         | Owner 5     | 1234567  |
| [vitospizza@gmail.com](mailto:vitospizza@gmail.com) | Vitos Pizza | 1234567  |

### Customers

| Email                                     | Name   | Password |
| ----------------------------------------- | ------ | -------- |
| [user1@gmail.com](mailto:user1@gmail.com) | User 1 | 12345    |
| [user2@gmail.com](mailto:user2@gmail.com) | User 2 | 12345    |
| [user3@gmail.com](mailto:user3@gmail.com) | User 3 | 12345    |
| [user4@gmail.com](mailto:user4@gmail.com) | User 4 | 12345    |
| [user5@gmail.com](mailto:user5@gmail.com) | User 5 | 12345    |

## Contributing

Feel free to fork the repository and submit pull requests. Issues and suggestions are welcome to improve the project.

## License

This project is open-source and available under the MIT License.

## Author

**Vishwa Aloka**

* GitHub: [https://github.com/vishwa-aloka-16](https://github.com/vishwa-aloka-16)
* LinkedIn: [https://www.linkedin.com/in/vishwaaloka](https://www.linkedin.com/in/vishwaaloka)
* Email: [vishwaaloka16@gmail.com](mailto:vishwaaloka16@gmail.com)

```

