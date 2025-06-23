# Spring_Boot_Project
Platform SmartClass
A project that facilitates the management between students and teachers, allowing different options from live streaming inside Zoom to the submission of homework assignments into Palgiat (A Tool that helps teachers to find similarities and AI contents in students' submission work).
### ZOOM Developer Application
Visit Zoom.us Marketplace and go to build a development app and create a developer app, then go to the file application properties.yml, fill in the Zoom:API:{base-url: https://api.zoom.us/v2; account-id: your_id_account; client-id: your_client_id; client-secret: your_client_secret}

### Mailing Server SMTP
In the properties file, fill in the mail host, user, and password 

## Clone the project 
In your terminal, run the following command 
```bash
git clone https://github.com/Meh06di/Spring_Boot_Project.git
cd Spring_Boot_Project
```
## Run Vite dependencies and run
```bash
cd src/main/app
npm install vite
npm run dev
```
## Visit the localhost http://localhost:5173/
## Install maven dependencies
```bash
./mvnw install
```
## Run the Spring Boot 
```bash
./mvnw spring-boot:run
```


