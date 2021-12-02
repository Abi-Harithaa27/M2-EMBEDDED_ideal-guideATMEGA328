# Requirements
  ## Introduction
The Water Level Indicator employs a simple mechanism to detect and indicate the water level in an overhead tank or any other water container.Hence automating this system will help us to reduce the wastage of water resources.This helps the user to monitor the level of water in the tank and save this high demand renewable resouurce with ease. 
 This will also help in Industries where water is majorly used and the wastage is also high. This project is designed to help people save water and to keep a track on the level of water in the tank and prevent over flowing.
  
  ## Features
One of the most important feature of this project is that , it displays the level of water in the LCD display. This helps in preventing the overflow of the water. This also intimates us whether the water is to be filled or not in a tank. Since the product is fully automated, its cutsoff automataically when the tank is fully filled. All these make the product user friendly and prevents overflow of water tanks.
 ## SWOT ANALYSIS
  ### Strengths
 1.Water is conserved which is a high time need. <br /> 
 2.Manual work is reduced.
   ### Weakness
High Maintance is required since water is the major element.
  ### Opportunities
The data displayed as output can be transmitted to the user through various methodolgies and the code also can be easily modified.
  ### Threats

New and different versions of this product is available. Easily modifiable.
 ## 4W's and 1H
  ### Who
This Product can be used by the customer since it is user friendly and help to monitor the water level.
  ### What

It helps to fill the waterand automatically cut off when is reaches the level. This helps to monitor the level of water and prevents wastage.
  ### When

Whenever the level of the water is Low , this helps us to fill the water automatically and cutsoff whe the level is high or full. 
  ### Where

This sysstem can be used in places where the level of the water needs to be monitored.
  ### How

The system controled by atmega328 which gives commands to the system.
 ## Detailed requirements
  ### High level requirements 

| ID | Description | Status |
| ------ | ------ | ------ |
| HLR1 | Display the present level of Water Available | Implemented |
| HLR2 | Low Level- Fill the Water | Implemented
| HLR3 | Stop filling when the level is Reached| Implemented
  
   ### Low level requirements 

| ID | Description | Status |
| ------ | ------ | ------ |
| LLR1 | If the level is low before uplevel the water won't Fill | Implemented |
| LLR2 | System working without Error|Implemented



## HIGH LEVEL DIAGRAM
![High Level](https://user-images.githubusercontent.com/94228057/144435961-c6e0b4ed-2b96-4e60-967d-38f7869fe310.png)


##LOW LEVEL DIAGRAM
![low level diagram](https://user-images.githubusercontent.com/94228057/144435758-e5ab1c1b-22b7-47f8-8cc4-497cee3e260e.png)




Circuit: watertank.simu

Bill of Materials:

Hd44780-165 : Hd44780   
Led-97 : Led   
Potentiometer-145 : Potentiometer 1 kΩ
Resistor-102 : Resistor 100 Ω
Switch-100 : Switch   
Switch-99 : Switch   
atmega328-90 : atmega328   

##HIGH LEVEL DIAGRAM

![Water-Level-Indicator-Project-Working-Flow-Chart-248x300](https://user-images.githubusercontent.com/94228057/144438717-9778ca91-94a7-4535-9e36-105e8ae2c22c.jpg)

##LOW LEVEL DIAGRAM

![LOW LEVEL drawio](https://user-images.githubusercontent.com/94228057/144438737-0a9250ba-cc79-4e4c-a0b3-803bdf9e02ea.png)


## Test Plan
# High Level Test Plan:
| ID | DESCRIPTION |Exp I/P|	Exp O/P|	Actual O/P| Status |
| ------ | ------ | ------ | ------ | ------ | ------ |
| 1 |Display Level Of Water|	Nil|	0L - 2500L|	700L	|Implemented|
|2|	LED Glows when both Switches Open|	Nil	|LED Glows	|LED Glows|	Implemented|
|3|	LED OFF when both Switches Closed|	Nil	|LED OFF|	LED OFF	|Implemented|
# Low Level Test Plan:
| ID | DESCRIPTION |Exp I/P	|Exp O/P|	Actual O/P|	 Status |
| ------ | ------ | ------ | ------ | ------ | ------ |
| 1 |LED Glows |	Nil|	LED Glows|	LED Glows|	Implemented|
|2|	Level of water varies from 0L - 2500L|	Nil|	varies from 0L - 2500L|	varies from 0L-2500L|	Implemented|
