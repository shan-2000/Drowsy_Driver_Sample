## Introduction

Driver drowsiness detection is a car safety technology which helps prevent accidents caused by the driver getting drowsy. Various studies have suggested that around 20% of all road accidents are fatigue-related, up to 50% on certain roads. Drivers must keep a close eye on the road, so they can react to sudden events immediately. Driver fatigue often becomes a direct cause of many traffic accidents. Therefore, there is a need to develop the systems that will detect and notify a driver of her/him bad psychophysical condition, which could significantly reduce the number of fatigue-related car accidents. However, the development of such systems encounters many difficulties related to fast and proper recognition of a driver’s fatigue symptoms. One of the technical possibilities to implement driver drowsiness detection systems is to use the vision-based approach. This article presents the currently used driver drowsiness detection systems. The technical aspects of using the vision system to detect a driver drowsiness are also discussed. Nowadays, more and more professions require long-term concentration. Drivers must keep a close eye on the road, so they can react to sudden events immediately. Driver fatigue often becomes a direct cause of many traffic accidents. Therefore, there is a need to develop the systems that will detect and notify a driver of her/him bad psychophysical condition, which could significantly reduce the number of fatigue-related car accidents. However, the development of such systems encounters many difficulties related to fast and proper recognition of a driver’s fatigue symptoms.In recent years, driver drowsiness has been one of the major causes of road accidents and can lead to severe physical injuries, deaths and significant economic losses. Statistics indicate the need of a reliable driver drowsiness detection system which could alert the driver before a mishap happens. A number of road accidents might then be avoided if an alert is sent to a driver that is deemed drowsy.Drowsy driving is a major problem . The risk, danger, and often tragic results of drowsy driving are alarming. Drowsy driving is the dangerous combination of driving and sleepiness or fatigue. This usually happens when a driver has not slept enough, but it can also happen because of untreated sleep disorders, medications, drinking alcohol, or shift work.No one knows the exact moment when sleep comes over their body. Falling asleep at the wheel is clearly dangerous but being sleepy affects your ability to drive safely even if you don’t fall asleep. 
Drowsiness:

Makes you less able to pay attention to the road.

Slows reaction time if you must brake or steer suddenly.

Affects your ability to make good decisions.

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
 8. The detected abnormal behavior is
corrected through alarms in real time.
 9. Life of the driver can be saved by alerting
him using the alarm system.
 10. Speed of the vehicle can be controlled.
 11. Traffic management can be maintained by
reducing accidents.

 ## Disadvantages

 1. Damage of sensor cannot be detected.
 2. Vehicle based measures mostly affected by the
 geometry of road which sometimes unnecessarily
 activates the alarming system.
 3. The driving style of the current driver needs
 to be learned and modeled for the system to
 be efficient.
 4. The condition like micro sleeping which mostly happens
 in straight highways cannot be detected. 

## 4W and 1H

__WHO:__
its for the drivers and their own safety.

__WHAT:__
It means , if this detections happens earlier that to when driver's starts to drive it will save his life as well as it helps to avoid accidents.

__WHEN:__
Its depends upon the drivers attitute like sleepy face, drowsiness and drunken mode of detection and so.

__WHERE:__
It mostly happens when the driver feels asleep and drowsy inside the car when he is driving.

__HOW:__
The driver drowsiness detection is based on an algorithm, which begins recording the driver's steering behavior the moment when the driver starts to drive. It then recognizes changes over the course of long journeys, and thus also the driver's level of fatigue.

## SWOT Analysis

![SWOT](https://user-images.githubusercontent.com/94435852/145719082-985766e0-9cd3-4d96-aa0f-e1bb785ec345.PNG)

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

