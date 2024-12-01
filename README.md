Here's a README file for your project:

---

# Golang CRUD Projects  

This repository contains two branches demonstrating CRUD (Create, Read, Update, Delete) operations using **Golang**.  

## Branches  

### 1. `dev`  
A basic CRUD project using **Golang** without a database. It utilizes a **struct-based JSON** to manage data.  
#### Features:  
- Movie Management System.  
- Operations include:  
  - Add a Movie  
  - Get all Movies  
  - Update a Movie  
  - Delete a Movie  

#### Use Case:  
Ideal for beginners to understand the basics of CRUD operations in Golang without the complexity of database integration.  

---

### 2. `CRUD-MYSQL`  
An advanced CRUD project using **Golang** with **MySQL** for data storage and management.  
#### Features:  
- Book Management System.  
- Operations include:  
  - Add a Book  
  - Get all Books  
  - Update a Book  
  - Delete a Book  

#### Use Case:  
Perfect for developers looking to integrate Golang with a relational database like MySQL and learn about database connections, query execution, and data persistence.  

---

## Getting Started  

### Clone the Repository  
```bash  
git clone https://github.com/jithu2001/CRUD-API.git  
cd CRUD-API  
```  

### Switch Branches  
To explore the `dev` branch:  
```bash  
git checkout dev  
```  

To explore the `CRUD-MYSQL` branch:  
```bash  
git checkout CRUD-MYSQL  
```  

### Running the Project  
1. Ensure Golang is installed on your system.  
2. For `CRUD-MYSQL`, set up a MySQL database and configure the connection in the project.  
3. Run the application:  
   ```bash  
   go run main.go  
   ```  

---

## Contributing  
Contributions are welcome! Feel free to open issues or create pull requests for improvements or bug fixes.  

---

## License  
This project is open-source.  

--- 

Enjoy coding! 😊  
