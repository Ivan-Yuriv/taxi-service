# Taxi-Service Web App

[![N|Solid](https://image.spreadshirtmedia.com/image-server/v1/mp/products/T1459A839PA3861PT28D1015931844W10000H8965/views/1,width=1200,height=630,appearanceId=839,backgroundColor=F2F2F2/funny-taxi-cartoon-car-sticker.jpg)](https://nodesource.com/products/nsolid)

## Project Description
This is a taxi service web application connected to a MySQL Database. It allows you to create, read, update, and delete data relating to the cars and drivers that provide taxi services.

You must either log in to your account using your login name and password or create a new account to be able to perform the above operations.
## Project Structure
The project follows a three-tier architecture and consists of the following layers:
- Presentation tier (controllers)
- Business Logic tier (services)
- Data Tier (DAO)
## The technology stack used in this project includes:
- Java 11
- MySQL
- JDBC
- HTML, CSS
- JSP, JSTL
- Maven
- Apache TomCat 9.0.50
## Getting Started
To run this application, you need to install MySQL and Apache TomCat 9.0.50 on your computer and follow these steps:

 1. Clone this project.
 2. Run the SQL scripts placed in init_db.sql (resources directory) to create a new DB schema and the respective tables.
 3. Create a connection to your database in the ConnectionUtil class (/taxi.util) by using your credentials.
 4. Configure TomCat. Use / as your application context path.
 5. You can now run this application by using a TomCat local server.

