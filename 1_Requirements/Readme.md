## Introduction

Driver drowsiness detection is a car safety technology which helps prevent accidents caused by the driver getting drowsy. Various studies have suggested that around 20% of all road accidents are fatigue-related, up to 50% on certain roads. Drivers must keep a close eye on the road, so they can react to sudden events immediately. Driver fatigue often becomes a direct cause of many traffic accidents. Therefore, there is a need to develop the systems that will detect and notify a driver of her/him bad psychophysical condition, which could significantly reduce the number of fatigue-related car accidents. However, the development of such systems encounters many difficulties related to fast and proper recognition of a driver’s fatigue symptoms. One of the technical possibilities to implement driver drowsiness detection systems is to use the vision-based approach. This article presents the currently used driver drowsiness detection systems. The technical aspects of using the vision system to detect a driver drowsiness are also discussed.

## Application

• This system can be used in factories to alert
the workers.

• If found drowsy, the alarm system gets
activated and the driver is alerted.

• If there is any obstacles it is alerted to the driver.

• This system can also be used for railway
drivers.

## Objective

 The main objective of the proposed system is to provide security to a drivers when he is drunken and he feels drowsy. 

 ## Advantages

 1. Security of vehicle. 
 2. Record driving data, collision data and position data. 
 3. Analyze the accidents detail. 
 4. Send location of car and its maintenance to base station through GPS & GSM technique. 
 5. Sense gas & fuel leakage and display its status on car monitoring system. 
 6. Detect if the driver is drunk or not. 
 7. Detect if the driver is feeling sleepy.

 ## Disadvantages

 1. Damage of sensor cannot be detected.
 2. Not feasible in real time.

 ## High level requirements
|HLR ID|Description|Implemented/Furure|
|------|-----------|------------------|
|HLR_1|When ever driver is drowsy, an alarm needs to be triggered|Future|
|HLR_2|When Vehicle catches fire, windows need to be opened automatically|Future|
|HLR_3|If driver consumes alcohol,vehicle has to be automatically stop|Future|
|HLR_4|A message has to be send to the driver relatives when any kind of accident happens|Waiting list|


## Low level requirements
|LLR ID|Description|Implemented/Furure|
|------|-----------|------------------|
|LLR1_HLR_1|An eye blink sensor has to continuously monitor eye blinking|Future|
|LLR2_HLR_1|When eye blinking rate is high then alarm need to be triggered|Future|
|LLR2_HLR_1|An warning message has to be displayed on the LCD display|Future|
|LLR1_HLR_2|A fire sensor that connected to the microcontroller continiously moniter the temparature|Future|
|LLR2_HLR_2|The temparature sensor has to be connected to the window control.|Future|
|LLR3_HLR_2|When temparature is too high, it has to consider that fire present in vehicle and give input to the window control|Future|
|LLR4_HLR_2|After taking the input from fire sensor, windows control has to open the windows|Future|
|LLR5_HLR_2|A message has to send to relatives using gsm module|Waiting list|
|LLR1_HLR_3|A alcohol sensor conneted to the microcontroller continuosly moniter the alcohol presence in vehicle|Future|
|LLR2_HLR_3|If the alcohol is consumed by driver than it gives input to the ignition relay|Future|
|LLR3_HLR_3|Than ignition is off so the vehicle will be stoped automatically|Future|
|LLR1_HLR_4|Using GSM module a mesagge is send to relatives whem ant thing happens|Waiting list|

## SWOT Analysis

![SWOT](https://user-images.githubusercontent.com/94435852/145719082-985766e0-9cd3-4d96-aa0f-e1bb785ec345.PNG)
