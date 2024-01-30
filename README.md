# IT-SIA-Final-Task-

This cafe billing system is a flexible system that allows the client to add various category types and products seamlessly. With an intuitive user interface, this system simplifies the process of managing and generating bills for a cafe or any small businesses. Client admin can easily customize the system by adding new categories such as beverages, snacks, or desserts, and populate them with specific products.

Instruction

download and extract the file cafe_system.rar
copy the extracted file and paste it to your local Disk C:/xampp/htdocts
go to xampp and start Apache and MySQL
in your chrome type "localhost/phpmyadmin" and enter
after that, click new to create your database.
name the database "cafe" and then click create.
click import -> choose and then browse the database located in cafe_system/database/cafe.sql and then click go.
in your chrome type localhost/cafe_system
credentials admin acc. user: admin pass: admin123

user acc. user: user pass: user123

Web Service Integration
This website provides a comprehensive web service featuring a curated list of its products. This website's web service isn't just about showcasing products; it's a versatile solution that enhances overall business efficiency. The integration potential with other systems such as inventory system opens up new possibilities for businesses looking to streamline their operations and maintain accurate records.

The system offers this webservices: Product ID, Category ID, Product Name, Description, Price, and Status (1 if the product is still available).

Web Service URI: "http://localhost/cafe_system/webservice/server.php"

Method to call: getProducts()

Instruction for Integration:

1. Define the SOAP service endpoint
2. Create a SOAP client
3. Navigate to your $result by calling the getProducts() method.



Sample Integration image
![image](https://github.com/F4ye024/IT-SIA-Final-Task-/assets/158114804/d08c5c63-0fbc-4d3a-8248-83203b36c0e5)
