#  C Programming on Multiple platforms - PBL Approach
## features
- To view the balance
- To withdraw balance
- To deposit balance

## State of art/ Research
Now a days the people are not intrested in wasting time and due to covid they are not intrested to go to bank for money in thise case we use atm these atm Automated teller machines (ATMs) have altered the relationship between banks and their depositors, as well as the competitive relationships among banks. Which help the people to get money instant in there locality.If an error occurs, the ATM will automatically shutdown and return the card to the user.A main menu will be output to the display after validation of the PIN. The User selects Withdraw from the menu and withdraws cash from the ATM. The User selects Deposit option from the menu and deposits cash or cheques into the ATM. 
1. Account balance checking
2. ATM Cash withdrawal
3. Deposition of cash
## 4 W's and 1H
### Who
People to who need monwy
### When
when the people required money and save time.
### What
Verifying the the account details and add/subtract money.
### Where
Around many places in town.
### How
Geting money after inserting atm card and entering pin.
## SWOT
![swot](https://user-images.githubusercontent.com/68550769/153435609-9a1ecdd5-6e61-4c4c-bf72-8b1c5915a0e4.jpg)


## High Level Requirements
1. A customer must be able to make a cash withdrawal from any suitable account linked to the card, in multiples of 100.
2.  A customer must be able to make a deposit to any account linked to the card, consisting of cash and/or checks in an envelope. The customer will enter the amount of the deposit into the ATM, subject to manual verification when the envelope is removed from the machine by an operator. 
3.   A customer must be able to make a balance inquiry of any account linked to the card.

## Low Level Requirements
1. An ATM machine accepts a card from a user.
2. The user inputs a PIN to authenticate the user’s identity.
3. The system validates the card and the PIN then either continues processing or rejects the card.
4. The ATM prompts the validated user for the type of transaction.

## Best method followed
- Used functions to decrease dependency on main function
- Used loops to exicute the commands one bye one and follow the flow.
- Printf statements have been placed only wherever necessary to avoid confusions
- Created header file so that the fuctions can be used else where ever required without any difficulty
# Behavioural Diagram
## HIGH LEVEL FLOWCHART
![high flow](https://user-images.githubusercontent.com/68550769/153441829-f80553a4-c228-4c68-b872-a4b210686dc9.png)

## LOW LEVEL FLOWCHART
![low flow](https://user-images.githubusercontent.com/68550769/153440528-be9e4dbc-20be-4b79-9132-bcde5536e924.jpg)

# Structural Diagram
## HIGH LEVEL UML
![umlhigh](https://user-images.githubusercontent.com/68550769/153440276-f2c6a1cb-bcc4-4a94-b64c-d87bb9ae4ac9.png)

## LOW LEVEL UML
![uml low level](https://user-images.githubusercontent.com/68550769/153440484-d1b58fc4-0cdb-4c55-a168-a2d60accafbb.png)

# Object Oriented Programming in Java

# Abstract:

Brick Breaker game consists of bricks aligned at the top of the screen. The player is represented as a tiny ball that is placed on a small platform at the bottom of the screen. The platform can be moved around from left to right on the screen with the help of arrow keys on the keyboard. The player uses the platform to keep the ball running. The goal is to break the bricks without missing the ball with your platform. The project makes use of Java swing, OOPS concepts and much more.

# State of art/ Research

This game is one of the classic platformer games, the game consists of a moving platform at the bottom of the screen that the player controls. The goal for the users is to try and destroy all the bricks on the top by bouncing a small ball of the plateform. Every brick the comes in contact with the ball gets destroyed.

I will be developing this application using Unreal 4 engine. The aim is create the game to run both on computers and mobile platforms. This will be a fun little game that can be played and enjoyed by all age groups.

# Primary and Secondary Features

## Primary Features
1. Single player
2. Player controlled moving platform
3. Bricks that can be destroyed
4. Moving Ball to destroy bricks
5. Be able to shot ball up on initial game start

## Secondary Features
1. Score counter
2. Number of balls remaining
3. Power ups add
4. Play sfx when ball hits/launches

# 4 W's and 1H
## Who
People to who need enjoy and have fun.

## When
when the people required to entertain there life .

## What
For makeing the people entertained.

## Where
Around any where the digital screan is present.

## How
Using keys present in the keyboard can play.

# High Level Requirements

| ID | Description | Exp I/p | Exp O/P | Status |
| -- | ----------- | ------- | ------- | ------ |
| HR01 | 	Check if brickBreaker game gui executes properly | Key Press in accordance to menu option | GUI should open | Pass |
| HR02 | Check if slide moves in accordance to arrow key |	keys pressed for the movement of slide | Slide should turn in desired direction | Pass |
| HR03 |	Check if game gets over if ball move out of slide |	key pressed | display Game Over restart | Pass |
| HR04 |	Check if player hit all the brickes  |	key Pressed | display you won press enter to restart | pass |
| HR05 |	Check if ball hit brick every time each brick should be removed | key pressed | bricks should decreases by 1 |	pass |

# Low Level Requirements

| ID | HLT Id | Description | Exp I/p | Exp O/P | Status |
| -- | ------ | ----------- | ------- | ------- | ------ |
| L01 | H 1 | application should start with out any error	| Application Execute |  Application Executed | Success |
| L02 | H 2 | Grid of 700px X 600px Y should be devlpoed |	keys pressed | Grid of 700x600 px should be created | Success |
| L03 | H 3 |	Check if game gets over if ball move out of slide |	key pressed | display Game Over restart | Success |
| L04 | H 4 |	Slide corrdinate should move left and right |	key Pressed left and right | slide moves left and right | Success |

# High Level Flow Chart

![ME_ME_PROJECT_BREAKOUT_JAVA_MODULE_ME_PROJECT_BREAKOUT_JAVA_MODULE_BREAKOUT_JAVA_arch](https://user-images.githubusercontent.com/68550769/157929709-01881cb3-d1f7-4215-b914-3f78b97c0c58.jpg)


# Lowlevel Flow chart

![BrickBreakerFlowChart](https://user-images.githubusercontent.com/68550769/157928352-d6736b87-38f9-4207-841d-19ea048ac171.jpg)

# Behavioural

![NlAzl](https://user-images.githubusercontent.com/68550769/158005305-e001b9a7-936c-4474-bebb-f1154c2dfbd5.png)

# High Level TestPlan

| ID | Description | Exp I/p | Exp O/P | Status |
| -- | ----------- | ------- | ------- | ------ |
| HR01 | 	Check if brickBreaker game gui executes properly | Key Press in accordance to menu option | GUI should open | Pass |
| HR02 | Check if slide moves in accordance to arrow key |	keys pressed for the movement of slide | Slide should turn in desired direction | Pass |
| HR03 |	Check if game gets over if ball move out of slide |	key pressed | display Game Over restart | Pass |
| HR04 |	Check if player hit all the brickes  |	key Pressed | display you won press enter to restart | pass |
| HR05 |	Check if ball hit brick every time each brick should be removed | key pressed | bricks should decreases by 1 |	pass |

# Low Level TestPlan

| ID | HLT Id | Description | Exp I/p | Exp O/P | Status |
| -- | ------ | ----------- | ------- | ------- | ------ |
| L01 | H 1 | application should start with out any error	| Application Execute |  Application Executed | Success |
| L02 | H 2 | Grid of 700px X 600px Y should be devlpoed |	keys pressed | Grid of 700x600 px should be created | Success |
| L03 | H 3 |	Check if game gets over if ball move out of slide |	key pressed | display Game Over restart | Success |
| L04 | H 4 |	Slide corrdinate should move left and right |	key Pressed left and right | slide moves left and right | Success |

# Essential of Python Programming + Object Oriented Programming using Python(SW)


# Essentials of Object Oriented Concepts using C++

# INTRODUCTION

Smart switches are designed as direct replacements for traditional built-in switches. Yes, you can still turn your lights on and off, just as you always did, but these smart switches provide you with much greater control over your home's lighting, as well as fans and hardwired appliances. A smart light switch replaces an existing light switch. When you link it to your home's wireless network you can flip that switch off and on remotely or via voice assistants. Your light bulbs don't need to be smart lights, they just need to be the lights connected to that switch.Smart Switch can transfer all your data, including your device settings, so that you can pick up your new device and carry on right where you left off. You can even create a backup for your old phone's files on your PC or Mac, then transfer or sync your data onto your new Galaxy phone.When you press buttons on smart light switches, they send wireless signals to control your smart lights (typically via WiFi, Bluetooth, Zigbee or Z-Wave) .


# FEATURES
- Smart switch enables us to control light,fan and fridge.
- MOOD LIGHTNING - Switch on lights (yellow,white,blue,red)based on your mood.
- Can controll your fan speed and turn it on or off.
- Can controll your fridge by adjusting temperature,turn on or off.
- encryption is available.
- Unique ID.


# 5 W's  and 1H 
![4'W and 1H](https://user-images.githubusercontent.com/79264869/161008889-c4c7a698-4ab8-4242-959b-81f2811dd6f7.jpeg)


# SWOT
![](https://github.com/GENESIS-2022/ILSWTTI101-Mar-Team35/blob/82d992a7a69ae034aa3da039db23d5b832ffb603/1_Requirements/smart%20switch.jpg)


# High Level Requirements

| ID | Description |
| -- | ----------- |
| HR01 | 	System shall control Fan,Light and Fridge |
| HR02 | The light is connected with switch to on/off and to change the colour |
| HR03 |	The fan is connected with switch to on/off and to increase the speed |
| HR04 |	The fridge is connected with switch to on/off and to increase/decrease the tempature |


# Low Level Requirements
|ID|Description|
|------|---------|
|LR01 |With the help of Switch the fridge will be on/off|
|LR02 |The switch will helps to increase/decrease the temperature in the fridge|
|LR03 |With the help of switch we can on/off the light|
|LR04 |With the help of switch we can on/off the fan|
|LR05 |And it helps to increase/decrease the speed of the fan|
|LR06 |To check the code whether it is able to on/off the switch to access the fan,light and fridge||

# Behavioural Diagram

## HIGH LEVEL FLOWCHART

![High Level Flow Chart](https://user-images.githubusercontent.com/68550769/160358330-e7e74f2d-d2db-4ffd-a065-33be00d5cea2.jpeg)


## LOW LEVEL FLOWCHART

![flowchart](https://user-images.githubusercontent.com/85921878/160228205-1a73a1cd-c070-4b2b-93cc-9c9b4f52b311.jpg)


# Structural Diagram

## HIGH LEVEL UML 
![High level UML](https://user-images.githubusercontent.com/59719836/161041170-36d9c4ba-3fa1-44c9-b93c-dfaeac61ff8d.jpeg)


## LOW LEVEL UML Diagram
![LLL](https://user-images.githubusercontent.com/79264869/161004389-460ecf76-a2eb-4945-8d17-c865dce4a39b.jpeg)


# Test Plan

# Bulb

  |    ID	 |  Description	            | Expected I/P	  |   Expected O/P                  |	 Actual O/P	   |  Type of test cae | Category |
  |--------|--------------------------|-----------------|----------------------------------- |----------------|---------------|------------|
  | 01     | Input Bulb               |   1             | To Turn on light with 25% brightness   | Turn on light with 25% brightness | Code based testing | Positive|
  | 02     | Input Bulb               |   2             | To Turn on light with 50% brightness   | Turn on with 50% brightness  | Code based testing | Positive |
  | 03     | Input Bulb               |   3             | To Turn on light with 75% brightness   |  Turn on light with 75% brightness | Code based testing | Positive |
  | 04    | Input Bulb               |   4             | To Turn on light with 100% brightness  |  Turn on light with 100% brightness | Code based testing | Positive |
  | 05     | Input Bulb              |   5            |  To turn off light                  |     Turn off light                  | code based testing     | positive |
  
# Fan

  |    ID	   |  Description	            | Expected I/P	  |   Expected O/P                  |	 Actual O/P	   |   Type of test cae | Category |
  |----------|--------------------------|-----------------|----------------------------------- |----------------|-----------------|---------|
  | 01       | Input Fan                |   1             | To turn on with speed of 1             |  Turn on with 1 speed | Code based testing | Positive |
  | 02       | INput Fan                |   2             | To turn on with speed of 2              | Turn on with 2 speed | Code based testing | Positive |
  | 03       |Input Fan                 | 3               | To turn on with speed of 3              | Turn on with 3 speed | Code based testing | Positive |
  | 04      |Input Fan                  |  4              | To turn on with speed of 4              | Turn on with 4 speed | Code based testing | Positive |
  | 05     | Input Fan                  |   5             |  To turn off fan                        |   turn off fan     | code based testing  | positive |
  
  # Fridge
  
  |    ID	   |  Description	            | Expected I/P	  |   Expected O/P                  |	 Actual O/P	   |  Type of test cae | Category | 
  |----------|--------------------------|-----------------|----------------------------------- |----------------|-----------------|----------|
  |   01     | Input Fridge             | ON              | Set Temperature at high           | High Temperature | Code based testing | Positive |
  | 02       | Input Fridge             | ON              | Set Tempetrature at Low             | Low Temperature | Code based testing | positive |
  | 03       | INput Fridge             | Off             | To turn off                        |  OFF            |  code based testing  | positive|



# Insights of OS Concepts and Linux System Programming

# Object Oriented Programming with Python

# Introduction

L&T Management System aids in the automation of manual processes, saving both time and money. This system safeguards the professional and personal information of employees and the interns. HR and business managers are relieved of their burdens and pressures thanks to the personnel management system.

# Abstract

An employee management system is a software, that helps your employees to give their best efforts every day to achieve the goals of your organization.

# 5W's 1H

## Who

Employees and Interns of L&T company members can acces

## When

In the office time.

## What

veryifying the details every day.

## Where

In L&T officeer

## Why

To save time and efforts

## How

we use software to store in database

# SWOT

![swot](https://user-images.githubusercontent.com/68550769/162017373-1b0f93b5-ae8b-4dcb-9151-0554dd700c34.jpg)


# High Level Requirements

| ID  | High level requirements |
| ------------- | ------------- |
| HL1 | admin shall be able to add Employee record |
| HL2 | admin  shall be able to display Employee record |
| HL3 | admin shall be able to update a Employee record |
| HL4 | admin shall be able to delete a Employee record |
| HL5 | admin shall be able to save records in a file |
| HL6 | admin shall be able to read data from a file |
| HL7 | Data should be stored when closing the system |


# Low Level Requirements

| ID  | Low level requirements |
| ------------- | ------------- |
| L1 | New record is added and Employee id should be unique |
| L2 | Finding the Employee details can be either by searching by name or the best way of searching is by psnumber |
| L3 | If user searches for an invalid ID ""ERROR RECORD NOT FOUND" message should be displayed |
| L4 | If opening the login page fails system shloud prompt the message "Invalid login" |


# Behavioural Diagram
## HIGH LEVEL FLOWCHART
![highlevel](https://user-images.githubusercontent.com/68550769/161942860-5e370437-51d9-4e72-909a-f198cc6ae2ef.jpg)

## LOW LEVEL FLOWCHART
![lowlevel](https://user-images.githubusercontent.com/68550769/161942888-fa56e6e3-7522-4848-b877-a52848b4ec43.jpg)

# Structural Diagram
![lowlevel uml](https://user-images.githubusercontent.com/68550769/161942879-d80ff6fe-a50a-4a56-a0e5-96e8de91d0d4.jpg)

## Best method followed
- Used functions to decrease dependency on main function
- Used loops to exicute the commands one bye one and follow the flow.
- Printf statements have been placed only wherever necessary to avoid confusions
- Used fiel handling to store data. 

# PYLINT
![image](https://user-images.githubusercontent.com/68550769/163315189-08ec0a9f-0a24-44fa-a18c-52bd21562ab0.png)

# TEST PLAN
## High Level Test Plan
| Test ID | Description | Expected Input | Expected Output | Actual Output | Type Of Test |
| ------- | ----------- | -------------- | --------------- | ------------- | ------------ |
| H_01 | Check if the User selects an option from the available choices, and if want to add record of the Emplyee give the details like id,Name,salary,permanent address,present Address,phone number,e-mail | User's choice, an integer and character | Success | Success | Requirement based |
| H_02 | Check if the User selects an option from the available choices, and if want to delete record of the Emplyee give the details like id | User's choice, an integer | success | success | Requirement based |
| H_03 | If record is only present in File, then delete from File | 	user choice as an integer | PASS | Success | Technical |
| H_04 | Check if the user want to see the Complete list of the Employee, then select the option as display | Display in a file | SUCCESS | SUCCESS | S	Required based |
| H_05 | Check if the user want to display basic information then give employee id if present in the list will give details else it will display the message as "ERROR RECORD NOT FOUND" | Users choice as an integer | SUCCESS | SUCCESS | 	Required based |
| H_06 | Check if the system asks the user for repeating the process and exits the system when choosed | User's choice | SUCCESS | SUCCESS | Scenario based |

## Low Level Test plan
| Test ID | Description | Expected Input | Expected Output | Actual Output | Type Of Test |
| ------- | ----------- | -------------- | --------------- | ------------- | ------------ |
| L_01 | When choosing from the options, check if the input is valid or invalid | User's Choice | Invalid Message/ Invoke the process | SUCCESS | Scenario based |
| L_02 | Check that the details of the record | user choice | SUCCESS | SUCCESS | Scenario based |
| L_03 | Check user's choice when selects dispaly list of the Employee | SUCCESS | SUCCESS | SUCCESS | Scenario based |
| L_04 | If the Record is already exist | user gives integer as emp id | Already Exists | Already Exists | Scenario based |

## Best Practices
- [x] Checked all the possibilities of output
- [x] Mentioned all the inputs for better understanding
- [x] Presented in tabular form for easy understanding
- [x] Both High level and low level Test plans are shown

# Professional Skills

# Applied TDLC

# Advanced python programming concepts

# NETWORKING PYTHON

# Overview of Docker, Cloud & Micro Services

# Acceptance Testing using Robot Framework


