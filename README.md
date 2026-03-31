# inet4031_lab9_crudecrud
Updated Crude CRUD made by Stardust Crusaders scrum team for UMN INET 4031 lab 9

# INET 4031 Lab 9 – Updated Crude  

## Program Description  
This lab focuses on setting up a complete virtualized infrastructure and deploying a web-based application in a controlled environment. The objective is to simulate a real-world IT workflow where systems are configured, connected, and tested before being used in production.

Instead of manually setting up each component separately, the lab walks through a structured process that includes creating virtual machines, configuring network settings, and deploying a web application. This approach improves consistency, reduces configuration errors, and allows teams to efficiently test systems before deployment.

The lab also introduces key concepts such as virtual networking, server configuration, and database integration, which are essential in modern IT environments.

---

## Program User Operation  
The lab is completed in a team setting where each member has a specific role, such as system administrator or developer. The team works together to configure the environment and ensure everything functions properly.

Users interact with the system by:
- Creating and running virtual machines  
- Configuring network adapters  
- Deploying a web application  
- Testing connectivity using commands like ping  
- Verifying that required services are running  

The system administrator focuses on infrastructure and server setup, while developers work on the application and database functionality.

---

## Infrastructure Configuration  

### Virtual Network Bridging  
Bridging a virtual network adapter means connecting a virtual machine directly to the physical network so it behaves like its own device with a unique IP address. This allows the VM to communicate with other devices on the network.

### Network Verification  
The system was tested by running the virtual machine and confirming connectivity using network tools.

**Example:**  
Test Environment VM IP Address → `192.168.56.102`  

Successful ping results confirmed that the VM was properly connected and reachable.

---

## Development Environment  
The team created and modified a web-based application for their company environment. The homepage was updated, and a search feature was implemented to retrieve employee records from a database.

**Key update:**
- The employee search page is prepopulated with `Smith` instead of `Weedman`  

The application uses PHP to interact with a MySQL/MariaDB database and display results dynamically.

---

## Server Configuration and Deployment  
The system includes a full web server stack:
- Apache (web server)  
- MySQL/MariaDB (database)  
- PHP (server-side scripting)  

The team verified that all services were running and successfully deployed application files to the `/var/www/html` directory, allowing access through a web browser.

---

## Test Environment Deployment  
The application was deployed to a test environment to ensure everything worked correctly before production use.

**Testing included:**
- Verifying database connectivity  
- Running queries to retrieve employee data  
- Confirming that the application displayed results correctly  

Command-line checks showed that user records were successfully stored and accessible.

---

## Database Credentials  

- **Username:** `phpuser`  
- **Password:** `password`  

### Security Considerations  
Using personal credentials is not recommended. Instead:
- Create generic users for shared systems  
- Assign permissions based on roles  
- Limit access to only what is necessary 
