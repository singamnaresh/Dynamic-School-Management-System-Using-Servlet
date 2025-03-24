# Dynamic-School-Management-System-Using-Servlet
A web-based system using Java Servlets, JSP, and MySQL to manage students, teachers, attendance, exams, and results efficiently. It follows MVC architecture for scalability and security. Tech Stack: Java, JSP, MySQL, HTML, CSS, Bootstrap, Tomcat.  Setup: Clone, configure MySQL, deploy on Tomcat &amp; start managing! 


Project Overview
The **Dynamic School Management System** is a web-based application developed using "Java Servlets", "JSP", and "MySQL" to efficiently manage various school operations. This project helps in automating tasks like "student enrollment, teacher management, attendance tracking, exam results processing, and class scheduling". The system is deployed using "Apache Tomcat" and uses "XAMPP" for managing the MySQL database.


#Technologies Used
- Backend:Java (Servlets, JSP, JDBC)  
- Database: MySQL (Managed via XAMPP)  
- Frontend:HTML, CSS, Bootstrap, JavaScript  
- Server:Apache Tomcat  
- IDE:Eclipse / IntelliJ IDEA  

Setup & Installation Guide
Follow these steps to set up and run the **Dynamic School Management System**:

1. Install Required Software
- Java Development Kit (JDK) – Install JDK 8 or later.
- Apache Tomcat – Download and configure Tomcat Server.
- XAMPP– Install XAMPP to manage MySQL database.
- Eclipse / IntelliJ IDEA– Recommended IDE for Java development.

2. Clone the Repository
```bash
   git clone https://github.com/yourusername/dynamic-school-management.git
```

3. Configure MySQL Database
1. Start XAMPP and enable Apache & MySQL.
2. Open phpMyAdmin and create a database named `school_db`.
3. Import the SQL file provided in the `database/` folder.

 4. Configure Project in IDE
1. Open the project in Eclipse / IntelliJ.
2. Configure Apache Tomcat as the server.
3. Update the database connection in `DBConnection.java`:
   ```java
   String url = "jdbc:mysql://localhost:3306/school_db";
   String user = "root";
   String password = ""; // Set password if configured
   ```

5. Deploy & Run
1. Right-click the project and select **Run on Server**.
2. Choose **Apache Tomcat** and start the server.
3. Open a web browser and go to:  
   ```
   http://localhost:8080/dynamic-school-management
   ```
usage
- Admin Login:Manage students, teachers, classes, and reports.
- Teacher Login:Manage class schedules, attendance, and grades.
- Student Login:View attendance, exam results, and announcements.

Future Enhancements
- Implement RESTful APIs for mobile integration.
- Add SMS & Email notifications for attendance and results.
- Improve UI/UX with modern frameworks like React or Angular.

Contributing
Feel free to **fork this repository**, submit issues, or suggest improvements!

License
This project is open-source and available under the **MIT License**.

Start managing your school efficiently today!


