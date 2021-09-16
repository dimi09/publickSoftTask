# publickSoftTask
* Simple crud+search spring boot application
* First of all you should have installed the following requirements:
 ◦ OpenJDK 1.8
 ◦ Maven 3.x
 ◦ Git 2.x
 ◦ MySQL 5.x
 ◦ Node.js 6.x
* Create an empty database with name: springbootcrud
* You can also import the springbootcrud_supplier.sql file for the suplier table with custom data entries
* Open the file: springbootcrud-webapp/src/main/resources/application.properties and
  modify the following properties, depending on your MySQL installation: 
 ◦ spring.datasource.username=root
 ◦ spring.datasource.password=root
* Run the Application.class 
* Be sure that you are in the springbootcrud-client folder and execute the following
  command: npm install
* When the installation will be finished you can run the Client with: npm run dev
* Then you can visit http://localhost:9000
* There is a suplier field, there you can edit, add new suplier and delete. You can also do a search
  by company name and vat-number of the existings suplier entities
