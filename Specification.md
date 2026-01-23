### 01 Introduction

#### 1.1 Purpose/Aims
This document will outline the requirement for the system as a whole, the main body (case) of the "bomb" and the modules that will go in the case.

Risks? Might not finish due to:
- Lack of time. Mitigate by understanding current time constraints and setting realistic goals accordingly.
- Lack of motivation. Mitigate through mutual encouragement + regular (weekly?) meetings & status updates ...?
- Lack of resource (i.e. parts not physically available to make modules). Aim to make modules work with common components and only essential functionality i.e. don't overcomplicate things.

This will be a live document that will be updated regularly throughout the making of the "bomb". Given that the project has multiple subsystems, the details for each part will have their own spec. but this doc will serve as a central store of information, linking to the other files.

1.2 Scope 
This document should clarify all the requirements for the:
- Case: have similar dimensions to the game; similar appearance to game; Contain the main processor. For futureproofing, include features for OTA updates. Must fit 12 modules.
- Side panel features: low-profile, "easy" to integrate into the case;
- Modules: Have a "status" indicator in top-right corner; 
- Module tester: A device that acts as a "one module bomb" and allows the user to
  set specific parameters (e.g. parallel port, serial number, indicators, remaining time etc). This would allow streamlined systematic testing for modules, as it wouldn't need to be loaded into the full device which has random parameters.

At what point do we know we're going off-topic?

[Design Brief](Design_Brief.md)

1.3 Useful Acronyms - Key abbreviations and acronyms that will be referenced in the doc



### 02 High Level System Overview

2.1 High Level Hardware Overview - Description and diagram of physical connections in the system. Which things get powered by which other things? Which things communicate and in which direction(s)? Are there any wireless comms?

2.2 High Level Software Overview - Description and diagram of software connections. Different kinds of protocols/controls/drivers and where they'll be used (if known).



### 03 Use Case

#### 3.1 End User #1

Who are the end users? Describe a typical use case - how do they interact with the device; do they need to do any setup; how involved is it? Age range? Do they need a certain background/skillset?

3.1.1 Installation/Assembly - Will they need to put anything together? What? How? Where..? How long will it take...?

3.1.2 Setup process - Once everything's put together, how will they know it works? What firmware/UI interactions will there be?



#### 3.2 End User #2

Who are the end users? Describe a typical use case - how do they interact with the device; do they need to do any setup; how involved is it? Age range? Do they need a certain background/skillset?

3.2.1 Installation/Assembly - Will they need to put anything together? What? How? Where..? How long will it take...?

3.2.2 Setup process - Once everything's put together, how will they know it works? What firmware/UI interactions will there be?





### 04 User Interface

#### 4.1 Hardware Interface

4.1.1 Power Switch

4.1.2 Power LED

4.1.3 Display

4.1.4 Motion detection?

#### 

#### 4.2 Software Interface

4.2.1 Display (SPI... I2C?)

4.2.2 Wi-Fi and Bluetooth



### 05 Power Requirements

5.1 Power - Power source? Power conversion? Power distribution? Expected power requirements?



### 06 Environmental Requirements

6.1 General Environmental Requirements



### 07 Mechanical Requirements

7.1 General Mechanical Requirements - Constraints on dimensions of overall device. 



### 08 Key Components

#### 8.1 Case

8.1.1 Body

8.1.2 Processor

8.1.3 Battery



#### 8.2 Modules

8.1.1 Body

8.1.2 Processor

8.1.3 Wires





### 09 Electrical Inputs and Outputs

9.1 Case-to-module Power and Data Connector - pinout with all relevant expected connections between the case and the 



### 10 Safety Requirements



### 11 System Specification

11.1 Hardware System Specification

11.1.1 Power

11.1.2 Displays

11.1.3 PCBs

11.1.4 Communication

I2C communication
    - only 2 wires needed, regardless of how many modules are used.
    - Allows a module (i.e. the timer module) to act as the main controller and be placed anywhere.
      With other communication protocols, either the master module would need to be in a specific place, or there would need to be a separate master within the case.
      


11.1.5 Interfaces

11.2 Software System Specification

11.2.1 Operating System

11.2.2 External Interfaces

11.2.3 Libraries Needed

11.2.4 Application Provision

11.2.5 Phone App Provision

11.3 User Interface

11.3.1 Hardware User Interface

11.3.2 Software User Interface

11.4 Mechanical

11.4.1 Size

11.4.2 Fixing

11.4.3 Component locations

11.5 Environmental

11.5.1 Temperature

11.5.2 Humidity

11.5.3 Air Pressure

11.5.4 Location

11.6 Safety and Regulations

11.6.1 Compliance

11.6.2 Directives and Regulations

11.6.3 Standards

11.7 Product Testing

11.7.1 Electrical Test

11.7.2 BIT (Built In Test)



### 12 Risks and Limitations

12.1 Risks

12.1.1 Component Costs



### 13 References



### 14 Revision History


