
##Architecture Overview
![image](https://github.com/user-attachments/assets/26796c6b-75cd-4366-be7e-a79ea4d098e7)


## Technologies Used

### Programming Languages and Frameworks
- **Java (Servlets)** – Core backend logic implemented using Java servlets for the RESTful web service.
- **Android SDK (Java/XML)** – Used for building the native mobile application with background threading, JSON parsing, and view layout design.
- **HTML, JSP, and CSS** – For the Logging & Analytics Dashboard frontend interface.
- **JavaScript** – Used for client-side interaction and frontend enhancements.

### APIs and Data Integration
- **3rd-Party Charity API** – Fetched charity information based on location and category (JSON-based REST API).
- **MongoDB Atlas** – Cloud-hosted NoSQL database used to persist logging data across user requests and API calls.
- **MongoDB Java Driver** – Used to connect and perform CRUD operations on MongoDB from Java.

### Backend and Middleware
- **Apache Tomcat (Catalina)** – Servlet container used for deploying the Java web service in cloud environments.
- **GitHub Codespaces** – Hosted deployment environment for running the web application in the cloud via Docker containers.
- **Docker** – Containerized the web application (using `ROOT.war`) for consistent deployment in Codespaces.

### Networking and Communication
- **HTTP** – RESTful request/response pattern between Android app, servlet backend, and external Charity API.
- **JSON** – Standard format for structured API response and inter-service communication.
- **Background Threads (AsyncTask / ExecutorService)** – Ensured non-blocking API calls in the Android application.

### Logging, Analytics & Visualization
- **MongoDB (NoSQL)** – Used for logging request metadata, timestamps, phone model info, and response statistics.
- **JSP Tables** – Displayed logs and analytics in a readable, formatted HTML table on the dashboard.
- **Analytics Metrics Tracked** (examples):
  - Most common charity categories searched
  - Average API response latency
  - Most active Android device models using the service

### Development Tools
- **IntelliJ IDEA** – Java development and servlet packaging.
- **Android Studio** – Native Android app development and UI testing.
- **Postman** – For testing servlet endpoints and Charity API responses.
- **GitHub & GitHub Classroom** – Version control and cloud deployment integration.

### Build and Dependency Management
- **Maven** – Managed project dependencies including:
  - `mongodb-driver-sync` for MongoDB connectivity
  - `slf4j-api` and `slf4j-simple` for MongoDB logging





