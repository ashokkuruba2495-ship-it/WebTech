# WebTech Springboot Practice 

## Spring Boot Learning Progress

| Day    | Topic             | Description                                                                                                                        |
| ------ | ----------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| Day 1  | Spring Boot Setup | Installed JDK, Maven, and IDE. Created the first Spring Boot project using Spring Initializr and successfully ran the application. |
| Day 2  |   Spring Basics   | Learned Spring Core, IoC (Inversion of Control), and Spring MVC architecture. Understood Controller, Service, and Model layers and created a simple REST API endpoint. |
| Day 3  | CRUD Operations   |Implemented CRUD operations in the Product Management System using Spring Boot. Used Postman to test APIs and stored product data in the MySQL database. |
| Day 4  |  Saturday    |      Practiced on crud Operations                                                                                                                              |
| Day 5  |  Sunday     |     Building the frontend Application of the given task (MedTrack)                                                                                                                               |
| Day 6  |React Frontend Development  |Started working on the frontend using React. Set up the React project environment and learned the basic structure of a React application including components, folders, and dependencies. Began developing the user interface for the project such as Login and Registration pages and connected the frontend with backend APIs using Axios.|
| Day 7  |Frontend Improvement |      Improved the frontend by 80% of it.   |
| Day 8  |Project Structure, Flowchart & Data Flow  |  Organized the Spring Boot project by creating proper packages (Controller, Service, Repository, Model), configured database settings in application.properties, and connected the project to MySQL. Designed a flowchart explaining the system workflow and documented the data flow of the project including project details, errors encountered during development, and their solutions. Prepared the complete workflow explanation to share as a single report/message. |
| Day 9  |                   |                                                                                                                                    |
| Day 10 |                   |                                                                                                                                    |

---

## Technologies Used

* Java
* Spring Boot
* REST API
* Git & GitHub
* MySQL 
* Postman 

<img width="306" height="356" alt="image" src="https://github.com/user-attachments/assets/7bc4b8c1-4061-4862-ae34-15865bd0d571" />


# Spring Boot Learning – Issues Log

| Day | Issue | Reason | Fix |
|-----|------|--------|-----|
| Day 1 | Hibernate MySQL Dialect Error | MySQL8Dialect removed in Hibernate 7 | Changed to `org.hibernate.dialect.MySQLDialect` in `application.properties` |
| Day 2 | Postman API 404 Not Found | Used online Postman which didn't send requests correctly | Installed and used Postman Desktop |
| Day 3 | Application not starting (Port in use) | Port 8080 already running | Changed `server.port` to `8081` |
| Day 3 | JSON format error in Postman | Incorrect JSON syntax | Corrected JSON request body |
| Day 3 | 405 Method Not Allowed | Wrong HTTP method used | Selected correct method (`POST` / `PUT`) |
| Day 4 | GitHub authentication error from STS | Password authentication removed by GitHub | Generated and used Personal Access Token |
| Day 5 | React project creation confusion | Mixed Create React App and Vite | Recreated project using Vite |
| Day 6 | React folder structure mismatch | Incorrect component structure and missing dependencies | Reorganized folders and installed dependencies |
| Day 7 | Project workflow not clear | No clear architecture between frontend, backend, database | Created flowchart and project documentation |
| Day 8 | Spring Boot dependency installation issue | Dependency/version mismatch | Added correct dependencies and reloaded Maven project |
| Day 9 |  |  |  |
| Day 10 |  |  |  |

