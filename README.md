# userRegistrationSQL
This is a NodeJS project. I created this project in my workshop to demonstrate CRUD operation using NodeJS and MySQL

Please create db "workshop"

#Use below query to create table
CREATE TABLE `workshop`.`users` ( `id` INT(11) NOT NULL AUTO_INCREMENT , `name` VARCHAR(255) NOT NULL , `email` VARCHAR(255) NOT NULL , `password` VARCHAR(255) NOT NULL , `remark` VARCHAR(255),  PRIMARY KEY(`id`) );

I used XAMPP PHPMyAdmin panel, you may use any other,

#After clone please run
npm install
#it help, in installing dependencies


