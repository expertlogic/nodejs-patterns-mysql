# nodejs-patterns-mysql
node js pattern learning 

1- need to run npm install 
2- node src/app.js to run 
3- check for port , 8080 should be free from binding then open 
4- install mysql db and create database calendar with table user 
CREATE TABLE `user` (
  `id` int NOT NULL AUTO_INCREMENT,
  `firstName` varchar(255) NOT NULL,
  `lastName` varchar(255) NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=3 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;

5-http://localhost:8080/users
