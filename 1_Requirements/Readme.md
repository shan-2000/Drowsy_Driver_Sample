# Drowsy driver

Car accident

HHL:
4 Requirements

LLR:
4 Requirements


# High leval requirements
|HLR ID|Description|Implemented/Furure|
|------|-----------|------------------|
|HLR_1|When ever driver is drousy, an alarm needs to be triggered|-|
|HLR_2|When Vehicle catches fire, windows need to be opened automatically|-|
|HLR_3|A message has to be send to the driver relatives when any kind of accident happens|-|
|HLR_4|If driver consumes alcohol,vehicle has to be automatically stop|-|
|HLR_5|Various parameters has to be displyed on the LCD screen|-|


# Low leval requirements
|LLR ID|Description|Implemented/Furure|
|------|-----------|------------------|
|LLR1_HLR_1|An eye blink sensor has to continuously monitor eye blinking|-|
|LLR2_HLR_1|When eye blinking rate is high then alarm need to be triggered|-|
|LLR2_HLR_1|An warning message has to be displayed on the LCD display|-|
|LLR1_HLR_2|A fire sensor that connected to the microcontroller continiously moniter the temparature|-|
|LLR2_HLR_2|The temparature sensor has to be connected to the window control.|-|
|LLR3_HLR_2|When temparature is too high, it has to consider that fire present in vehicle and give input to the window control|-|
|LLR4_HLR_2|After taking the input from fire sensor, windows control has to open the windows|-|
|LLR5_HLR_2|A message has to send to relatives using gsm module|-|
|LLR1_HLR_3|Using GSM module a mesagge is send to relatives whem ant thing happens|-|
|LLR1_HLR_4|A alcohol sensor conneted to the microcontroller continuosly moniter the alcohol presence in vehicle|-|
|LLR2_HLR_4|If the alcohol is consumed by driver than it gives input to the ignition relay|-|
