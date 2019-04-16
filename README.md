# The Dream Stream Documentation Development


## Milestone App Review
Watch the latest review of the application on Youtube [here](https://www.youtube.com/embed/3njvE3QVbVk). 

AWS website [dreamstream website](http://thedreamstream.us-east-2.elasticbeanstalk.com)  
View all the Java documentation [here](https://mmitar.github.io/capstone/)

## Table of Contents
Home Directory
  * [Embedded System Technology](#Embedded-System-Technology)
    * [Arduino Stack](#Arduino-Stack)
    * [Load Scale](#Load-Scale)
    * [Arduino Wired to the Scale](#Arduino-wired-to-the-scale)

1. [System Design](https://github.com/mmitar/capstone/tree/master/_System%20Design)
2. [Database Design](https://github.com/mmitar/capstone/tree/master/_Database%20Design)	
3. [Class Design](https://github.com/mmitar/capstone/tree/master/_Class%20Design)	
4. [API Design](https://github.com/mmitar/capstone/tree/master/_API%20Design)
5. [Application Design](https://github.com/mmitar/capstone/tree/master/_Application%20Design)
6. [Other Design Documentations](https://github.com/mmitar/capstone/tree/master/_Other)

## Embedded System Technology

<img align="left" width="300" height="200" src="https://github.com/mmitar/capstone/blob/master/App%20Images/arduino.jpeg">  

### Arduino Stack

The Arduino stack is comprised of the Arduino Uno R3, an ESP8266 Wifi Shield, a prototype shield for good affect, and the HX711 Load cell micro controller. With the proper pinning and I/O port configuration, we have the stack ready to ready to POST data to the server. 

<br/><br/>

<img align="left" width="300" height="200" src="https://github.com/mmitar/capstone/blob/master/App%20Images/load_scale.jpeg">  

### Load Scale

This 5kg load cell uses the strain gauages to monitor the weight distribution. The HX711 micro controller can track all the small changes made fast, and accurately. A 3D printed base and coaster were printed in specification to the load cell.

<br/><br/>

<img align="left" width="300" height="200" src="https://github.com/mmitar/capstone/blob/master/App%20Images/scale_ard.jpeg">  

### Arduino Wired to the Scale

Together, the technology from both the Arduino Stack and the HX711 load cell micro controller provide a powerful combination that can provide real time monitoring and `POST` data directly to the server, providing an automation to liquor inventory tracking.

<br/><br/>

## Application Services

<img align="right" height="300" src="https://github.com/mmitar/capstone/blob/master/App%20Images/inventory.JPG"> 

### Inventory Management

Input the inventory you plan to monitor. This can be purposed for identifying a units popularity, tracking its general traffic, or to be notified during low inventory levels. In the future we hope to automate this feature further.

<br/><br/><br/>

<img align="right" height="300" src="https://github.com/mmitar/capstone/blob/master/App%20Images/Activity.JPG"> 

### User Activity Log

Track user activity through this logging utility. Keep users will access to the application accountable for their actions after they've modified your business's inventory or reconfigured a scale. All the data in context is provided.

<br/><br/><br/>

<img align="right" height="300" src="https://github.com/mmitar/capstone/blob/master/App%20Images/Scale%20Config.JPG"> 
<img align="right" height="300" src="https://github.com/mmitar/capstone/blob/master/App%20Images/Scale%20config%20pg2.JPG"> 

### Scale Configuration View

Remotely configure your inventory to the scales it will be using. Only inventory that is unbinded can be applied to a scale. Add more scales based on your business requirements. Remove scales you don't plan to use. 

<br/><br/><br/>

<img align="right" height="300" src="https://github.com/mmitar/capstone/blob/master/App%20Images/Metrics%20p1.JPG"> 
<img align="right" height="300" src="https://github.com/mmitar/capstone/blob/master/App%20Images/Metrics%20p2.JPG"> 

### Business and Inventory Metrics

Monitor real time data to align your inventory stock and consumption rate expectations with your business strategy. Analytics help identify the most popular drinks and stay on top of the competition by giving you up-to-date information to help inform your next move.

<br/><br/><br/>

## DevOps

<img align="left" width="300" height="200" src="https://github.com/mmitar/capstone/blob/master/App%20Images/Junit%20Test%20Cases.JPG"> 

### JUnit Test Cases

The Arduino stack is comprised of the Arduino Uno R3, an ESP8266 Wifi Shield, a prototype shield for good affect, and the HX711 Load cell micro controller. With the proper pinning and I/O port configuration, we have the stack ready to ready to POST data to the server. 

<br/><br/>

<img align="left" width="300" height="200" src="https://github.com/mmitar/capstone/blob/master/App%20Images/Code%20Coverage.JPG">  

### Code Coverage

The Arduino stack is comprised of the Arduino Uno R3, an ESP8266 Wifi Shield, a prototype shield for good affect, and the HX711 Load cell micro controller. With the proper pinning and I/O port configuration, we have the stack ready to ready to POST data to the server. 

<br/><br/>

<img align="left" width="300" height="200" src="https://github.com/mmitar/capstone/blob/master/App%20Images/Logging.JPG">  

### Logging Strategy

The Arduino stack is comprised of the Arduino Uno R3, an ESP8266 Wifi Shield, a prototype shield for good affect, and the HX711 Load cell micro controller. With the proper pinning and I/O port configuration, we have the stack ready to ready to POST data to the server. 

<br/><br/>


## Application Requirements

### Proof of Concepts

### Hardware and Software Technologies
| | |
| --- | --- |
AWS Elastic Beanstalk | Spring MVC Framekwork 4.3 |
Dynamic Web Application Framework 3.1 | Eclipse Oxygen IDE 3.0 |
JDK Compile Environment 1.8 | Tomcat Server 8.5 |
Java 8 | MySQL DB Connector Library for Java 5.1 |
Spring JDBC 4.3 | JAX-RS JSON provider 2.4 |
Servlet REST API 2.3 | JUnit Testing 4.12 |
SLF4J 1.7 / LOG4J 1.2 | MAMP |
MySQL Workbench | AWS Cloud Platform |
HTML / CSS / JavaScript 5.0 | JQuery 3.3 |
SVG | JSTL 1.2 |
Tiles 3.0 | Arduino Uno Elegoo |
ESP8266 Wifi Module | HX711 Load Scale Module |
Google Charting API | REST APIs

