# Rental Property Management Application

Updated: December 2021

## Authors
* Ahmed Waly
* Kai Wang
* Jaxson Waterstreet
* Dylan Windsor
* Mohamed Yassin

# Introduction

This application allows multiple user ends such as a renter and landlord to contact each other and 
register properties. The landlord can register multiple properties based on many criteria. All property postings will
be active after the landlord has paid the fee. The renter has the ability to search for specific preferences and save those searches. 
When a suitable property is available, the renter will receive a notification. 

If the renter is interested, they can send an email and arrange a meeting with the landlord.

# Installation

Steps to Compile and Run the Application:
  1. Clone The Repository on your local device.
  2. If your local device already has a mysql table that is named "mydb", drop it.
  3. Source the sql file on the MySQL Command Line(make sure to include your full path in the command)

For example:
  ```C:\Users\---Your path---\Rental-Property-Management-Application\database\RentalSystemDB.sql```
  
  4. navigate to the src folder in your compiler
  5. To Compile Run The following command line in your compiler 
  ```
  javac -cp .;../lib/mysql-connector-java-8.0.23.jar;.GUI/*.java controller/*.java model/*.java
  ```
  6. To Run, 
  ```
  java -cp .;../lib/mysql-connector-java-8.0.23.jar;. GUI/MainMenu
  ```

## Sample Screenshots

## Main Menu:
<img width="600" alt="mainmenu" src="https://user-images.githubusercontent.com/77874716/147435179-9a2bd0b4-ab5a-425f-a59d-0e6c7497c7e3.PNG">


## Registered Renter Screen:

![image](https://user-images.githubusercontent.com/73013959/145513919-0062375b-dcca-4802-972f-a5d0be899bb8.png)

## Email System:

![image](https://user-images.githubusercontent.com/73013959/145513939-c49b4bce-4e34-42ad-874e-03ecb87dd385.png)

## Landlord Register-A-Property Screen:

<img width="600" alt="registerproperty" src="https://user-images.githubusercontent.com/77874716/147894136-892dceb4-f3e2-43dd-b236-63fc0af69b12.PNG">


