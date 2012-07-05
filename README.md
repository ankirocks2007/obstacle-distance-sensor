obstacle-distance-sensor
====================

In this project we have chosen arduino as our platform and atmega 328 as a microcontroller. We have used infrared sensors to detect existence of obstacle in front of robot and also to detect at what distance (in centimeters) the obstacle is detected .We have used interrupt timer in this project ,as the obstacle is detected ,the interrupt routine is executed. Once the interrupt routine gets executed, then first of all the distance is calculated out through another subroutine which defined inside it. After the distance is calculated the direction is determined out in which robot has to be moved and then accordingly the actuators are given control. 
On the part of actuators we have used the theory of differential drive i.e. for example to turn sharp right left wheel will be rotated in forward direction and the right side motor is rotated in backward direction.
As a part of monitoring the distance of obstacle we have used serial communication between out robot and PC via IC RS 232.It can also be done by on board monitoring using LCD and send in the data to LCD. 
In this entire project power supply used is of 5V in all the places except for motor IC, in which 12Vpower supply is used.
There  is one limitation of this project i.e. ,this robot will not be able to detect black coloured obstacle because it is the property of black colour that its absorbtivity is very high ,it will absorb all the infrared radiations and will not radiate it to the sensor.
