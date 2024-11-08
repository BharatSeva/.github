# Bharat Seva+

### [Watch Demo Here](https://youtube.com/playlist?list=PLXRQ5AMta2AI_jZlGr0A5owICnGkDpElO&si=8AApluBocodaW-pr)

Welcome to Bharat Seva+, an advanced healthcare management system designed to streamline patient records, appointment scheduling, notifications, and data processing for healthcare services. Built for scalability and high performance, Bharat Seva+ integrates various backend technologies, ensuring secure, efficient, and reliable services for healthcare providers and patients. The project comprises a Healthcare Portal and a Client (or Patient) Portal, facilitating a seamless and user-friendly experience.

- **Microservices Architecture**: Bharat Seva+ follows a microservices design, separating the healthcare and user services for scalability and maintainability.
- **Asynchronous Task Processing**: Utilizes RabbitMQ to manage task queues, ensuring timely processing of messages and notifications.
- **Data Storage and Caching**:
- **PostgreSQL**: Primary storage for structured data, such as appointment logs and activity tracking.
- **MongoDB**: Storage for patient healthcare records and unstructured data.
- **Redis**: Caching and rate-limiting to enhance response times and control access.
- **Load Balancing and Scalability**: Nginx is used as a reverse proxy and load balancer, distributing traffic evenly between service replicas.
- **Real-time Monitoring**: Prometheus and Grafana are integrated for monitoring system performance, resource usage, and tracking critical health metrics.
- **CI/CD with Docker and GitHub**: Streamlined deployment process with Docker Compose for container orchestration, backed by CI/CD pipelines on GitHub.
---

## Project Overview

This project consists of **two web apps**:

1. **Healthcare Interface** [↗️](https://github.com/BharatSeva/HealthCare-Interface)    
   A portal for healthcare professionals (HIPs) to generate and manage health logs like biodata, health records, and more.

2. **Client Interface** [↗️](https://github.com/BharatSeva/Client-Interface)  
   A Client-facing portal where Client can access their records, make appointments, and avail other healthcare services (also refered as Patient portal or enduser).

Both interfaces work together to provide seamless healthcare management services.

---

## Features

### 1. Log Health Records Effortlessly  
Say goodbye to paper! **Bharat Seva+** allows healthcare providers and patients to log and store all their health data digitally. Whether it's vital signs, medications, lab results, or vaccination records, everything is securely stored in the cloud and can be accessed anytime.

### 2. Easy Appointment Scheduling  
Patients can easily schedule appointments with registered healthcare facilities through the app, eliminating the need for paper-based records.

### 3. Personalized Health Insights* (Coming Soon)  
In future updates, **Bharat Seva+** will analyze user health data and provide personalized insights, trends, and recommendations, helping users proactively manage their health.

### 4. Secure and Accessible Health Records  
Health records are stored securely in the cloud, making them easily accessible when needed and shareable with healthcare professionals.

### 5. Effortless Records Sharing
With this feature you can track your health data to predict future risk much early and avoid them

---

## Current Tech Stack

- **Frontend**: React.js, Tailwind  
- **Backend**: Express.js, Python, and Golang    
- **Database**: MongoDB, Redis, RabbitMQ, and PostgreSQL  
- **Authentication**: OAuth 2.0, JWT (for sessions)  

---

## Roadmap

Here’s what I’ve implemented so far:

- **Golang** healthcare server for optimized performance, scalability, and concurrency
- **NGINX** for Traffic Management and Load balancing
- **Docker** for containerization
- **MongoDB** as the database
- **RabbitMQ** ensures the application can process tasks asynchronously.  
- **Redis** for caching frequently accessed data
- **Python Consumer** Service for logs, appointment, medical records, and email notifications.
- **PostgreSQL** to handle advance querying, and to perform large data analytics.
- **Node.js** client server, built with Express.js.  
- **OAuth 2.0** and **JWT** for authentication and session management
- Two Front-end (Client and Healthcare) built with React.js and Tailwind  

## Target : Scale this application for Massive 50 Million Users 🚀
### Upcoming Features:
- **Prometheus and Grafana** to collect and stores metric data as time-series data, and for analytics and visualization of backend applications.
- **Elasticsearch** for search functionality of healthcare

### Future Plans:
- Implement Deep learning model to better analyze health data ( One of My Most **Ambitious** Task )  
- Transition from a monolithic architecture to microservices  
- Continuously improve code quality to ensure long-term maintainability  

---

## Challenges
One of main challenge is to implement a model to better analyze health data to predict future risk inorder to avoid them.  
There’s still a lot to learn and implement, from writing maintainable code to integrating features that can scale efficiently. I’m constantly improving and learning with the support of the open-source community. Stay tuned for more updates!  

---

## Embrace the Future of Healthcare

**Bharat Seva+** started! I’m excited to keep building and enhancing this project to provide the best healthcare management solution. Whether you're a patient or a healthcare provider, this platform is designed to make managing health records simple and effective.

---

## Project Architecture  

![image](https://github.com/user-attachments/assets/84c33f1b-fca1-4159-b2f8-c1f50a401bf2)
---

## Contributions
Please find a CONTRIBUTING.md file on repo of this organisation. If you've any doubt you can start discussions.   
Happy Contributions! 

---

### Bharat Seva+ - Your Wellbeing, Simplified.
_Project developed and managed by [**Vaibhav Yadav**](https://www.linkedin.com/in/vaibhav-yadav-4397351b9/)_ 

