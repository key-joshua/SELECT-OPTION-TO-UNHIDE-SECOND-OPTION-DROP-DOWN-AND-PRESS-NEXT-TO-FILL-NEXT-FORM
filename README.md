# NB: PLEASE READ THIS DESCRIPTION BEFORE DOING ANY THING ON THIS CODES PLEASE OR PROJECT PLEASE

SELECT-OPTION-TO-UNHIDE-SECOND-OPTION-DROP-DOWN-AND-PRESS-NEXT-TO-FILL-NEXT-FORM

In this simple project I have developed form by combined different kinds of forms
where in this video at the first form you will insert data by selecting the option mentioned by programmer 
after selection you will be prompted to select another option on next input and it all about drop-down 
also you will input data according to user needs then after filling forms you will be able to insert data in database 

0. SAVE THIS FILE AS " connection.php " INSIDE " umuganda_project "
1. CREATE FOLDER INSIDE " C:\xampp\htdocs " NAME IT " umuganda_project "
2. SAVE THIS FILE AS " umuganda_form1.php " INSIDE " umuganda_project "
3. SAVE NEXT FILE AS " umuganda_form2.php " INSIDE " umuganda_project "
4. SAVE NEXT FILE AS " umuganda_form3.php " INSIDE " umuganda_project "
5. SAVE LAST FILE AS " umuganda_form4.php " INSIDE " umuganda_project "
6. CREATE ANOTHER FOLDER INSIDE " C:\xampp\htdocs\umuganda_project " NAME IT " css "
7. SAVE THIS FILE AS " style.css " INSIDE " css "
8. CREATE ANOTHER FOLDER INSIDE " C:\xampp\htdocs\umuganda_project " NAME IT " js "
9. SAVE THIS FILE AS " valid_box.js " INSIDE " js "
10.OPEN THIS URL IN WEB BROWSER " http://localhost/phpmyadmin/ "
11. CLICK NEW TO CREATE DATABASE NAME IT " umuganda_project "
12. CLICK ON CREATED DATABASE THEN CLICK ON MENU ----> SQL  TO CREATE TABLE
13. PASTE THOSE QWERY TO CREATE TABLE

CREATE TABLE `umuganda_project` (
 `PROVINCE` varchar(255) NOT NULL,
 `DISTRICT` varchar(255) NOT NULL,
 `SECTOR` varchar(255) NOT NULL,
 `CELL` varchar(255) NOT NULL,
 `VILLAGE` varchar(255) NOT NULL,
 `RECORD_DATE` date NOT NULL,
 `GENDER` varchar(255) NOT NULL,
 `ID_NUMBER` varchar(16) NOT NULL,
 `FIRST_NAME` varchar(255) NOT NULL,
 `LAST_NAME` varchar(255) NOT NULL,
 `TELEPHONE` varchar(255) NOT NULL,
 `RESULT` varchar(255) NOT NULL,
 `AVATAR` varchar(255) NOT NULL,
 PRIMARY KEY (`ID_NUMBER`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8


14. OPEN THIS URL IN WEB BROWSER TO RUN PROJECT " http://localhost/umuganda_project/ "

![|way of access](SELECTOPTIONTOUNHIDESECONDO.gif)


Thank you so, much guys in next video i will sharing you how to retrieve those data based on user id
and if there are any question let me know and help you by emailing me k.joshua800@gmail.com 
