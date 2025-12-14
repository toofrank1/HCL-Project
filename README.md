# HCL-Project
# UX Feedback Aggregator

## Overview

The *UX Feedback Aggregator* is a simple Spring Boot application used to collect and manage user experience feedback for web applications. Users can submit feedback such as bug reports, feature requests, usability issues, complaints, or praise. The system stores feedback securely in MongoDB and provides REST APIs to view, update, and delete feedback.

---
## Features
* Submit user feedback
* Multiple feedback types
* File upload support
* View, update, and delete feedback
* Feedback status and priority tracking
* MongoDB database integration
---
## Technologies Used
* Java (JDK 17)
* Spring Boot
* MongoDB
* Maven
---
## System Requirements

### Software
* Windows 10 or above
* Java JDK 11+
* MongoDB
* IntelliJ / Eclipse / VS Code
### Hardware
* Intel i3 processor or higher
* Minimum 4 GB RAM
---
## Project Structure
ux-feedback-aggregator/
├── src/main/java/com/uxfeedback/
│   ├── controller/
│   ├── service/
│   ├── repository/
│   ├── model/
│   ├── dto/
│   └── config/
├── src/main/resources/
│   └── application.properties
├── uploads/
├── pom.xml
└── README.md

---
## API Endpoints
* *POST* /api/feedbacks – Create feedback
* *GET* /api/feedbacks – View all feedback
* *GET* /api/feedbacks/{id} – View feedback by ID
* *PUT* /api/feedbacks/{id} – Update feedback
* *DELETE* /api/feedbacks/{id} – Delete feedback
---
## How to Run

1. Start MongoDB
2. Open the project in an IDE
3. Configure application.properties
4. Run the Spring Boot application
5. Access APIs at:
   http://localhost:8081/api/feedbacks

   ---
## Conclusion
The UX Feedback Aggregator is a basic and efficient application for collecting and managing user feedback. It helps organizations understand user needs and improve application quality.

---
## Output
![50 op1](https://github.com/user-attachments/assets/8bbccece-cecf-43ff-aee2-5262fc8f0e19)
![50 op2](https://github.com/user-attachments/assets/b939daec-c145-4017-bb2d-b4db41b6a3a2)

