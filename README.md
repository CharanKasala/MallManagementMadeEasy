# Mall Management Made Easy (MEME)

This repository houses the Mall Management System project, designed to optimize the management of various mall operations, including parking space reservations, food stall administration, gaming features, and job application handling. The application is developed using Java, Spring Boot, and MySQL, and is fully deployed on an AWS EC2 instance.

**Features of the Application:** 

**Admin  Features:**

•	**Manage Food Stalls:** Add, update, delete, and view food stall managers.

•	**Manage Parking:** Add and manage parking spaces within the mall.

•	**Manage Games:** Add, update, and delete available games in the gaming area.

•	**Job Opportunities:** Post, update, and remove job openings, and review job applications.

**Food Stall Manager Features:**

•	**Menu Management:** Add, update, delete, and view menu items for the assigned food stall.

•	**Process Orders:** Handle and process customer food orders efficiently.


**Customer Features:**

•	**Book Parking Space:** Reserve parking spots for specific time slots.

•	**Book Movie Tickets:** Purchase tickets for movies in available time slots.

•	**View Job Openings**: Browse available job opportunities and track application status.

•	**Order Food:** Browse food stalls, place orders, and monitor order status.

•	**View Events:** Stay informed about ongoing events, promotions, and activities at the mall


**PROJECT SETUP:**

**Pre-requisites:**

**Java 11:** Install Java Development Kit (JDK) version 11.

**Maven:** Install Apache Maven for project management and build automation.

**Eclipse IDE** : Install Eclipse IDE for Java EE development

**MySQL Workbench:** Install MySQL Workbenchfor managing MySQL databases

**Frontend Setup**

1. Import zip file into Eclipse IDE

2. Add [lombok](https://projectlombok.org/setup/) plugin to eclipse 

3.	Edit the following properties in ~/mallmgt/src/main/resources/application.properties file.
   
•	spring.datasource.url=jdbc:mysql://localhost:3306/mallmgt?createDatabaseIfNotExist=true

•	spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver

•	spring.datasource.username=root

•	spring.datasource.password=root

•	spring.jpa.database-platform = org.hibernate.dialect.MySQL8Dialect

•	spring.jpa.generate-ddl=true

•	spring.jpa.hibernate.ddl-auto = update

•	server.port = 8080

**Backend Setup**

1.  Create MYSQL server on port 8080.
  
2.	Dump the Database.sql file into MySQL Workbench.

**Credentials for Testing**

**Admin:**

Main Admin: 

	Username: Admin@gmail.com
 
	Password: Demo@123
 
Food Admin:

	Food stall Name: Taco Bell
 
		Username: Tacobelladmin@gmail.com
  
		Password: Demo@123
  
	Food stall Name: Popeyes
 
		Username: Popeyesadmin@gmail.com
  
		Password: Demo@123
  
	Food stall Name: Mc Donalds
 
		Username: Mcdadmin@gmail.com
  
		Password: Demo@123

**Customer:**

	Username: Keerthi@gmail.com

	Password: Demo@123

**Contribute:**

Follow the below steps to contribute/make changes to the project

1. For the repository

2. Clone the Repository Locally

		git clone https://github.com/CharanKasala/mall-management-system.git
 
3. Create a New Branch for Your Changes
   
		git checkout -b my-feature-branch

4. Make Changes Locally

5. Stage and Commit Your Changes

   		git add .

		git commit -m "Description of the changes made"

6. Push Your Changes to GitHub

   		git push origin my-feature-branch

7. Create a Pull Request for review
