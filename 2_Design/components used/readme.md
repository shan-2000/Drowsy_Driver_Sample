# ATmega32 Microcontroller :

![image](https://user-images.githubusercontent.com/94309132/145758270-b5a9d6d3-a7a1-41be-b100-dc562dda9c58.png)

![image](https://user-images.githubusercontent.com/94309132/145758298-a7b1df75-3523-4ecd-9711-0c6add032adc.png)

## Pin Descriptions:
### Port A (PA7-PA0): 
Port A serves as analog inputs for A/D converter. It also acts as an 8-bit bidirectional I/O port if the A/D converter is not used internally.

### Port B (PB7-PB0) and Port D (PD7-PD0):
These ports are 8-bit bidirectional I/O ports. Their output buffers have symmetrical drive characteristics with high source and sink capability. As inputs, these are pulled low if the pull-up resistors are used. It also provides various special functional features of the ATmega32.

### Port C (PC7-PC0): 
Port C is an 8-bit bidirectional I/O port. If the Joint Test Action Group (JTAG) interface is enabled, the pull-up resistors on pins PC2 (TCK), PC3 (TMS), and PC5 (TDI) will be activated.

### Vcc:  
Digital voltage supply

### GND: 
Ground

### RESET:
It is a RESET pin which is utilized to set the microcontroller ATmega32 to its primary value. During the beginning of an application the RESET pin is to be set elevated for two machine rotations.

### XTAL1:
It is an input for the inverting oscillator amplifier and input to an internal clock operating circuit.

### XTAL2: 
It is an output from an inverting oscillator amplifier.

### AVcc:
It is a supply voltage pin for A/D converter and Port A. It must be connected with Vcc.

### AREF:
AREF is an analog signal reference pin for the analog to digital converter.

## Key Features:
Consider some general features of ATmega32 microcontroller is:-

* 2 Kilo bytes of internal Static RAM
* 32 X 8 general working purpose registers
* 32 Kilo bytes of in system self programmable flash program memory.
* 1024 bytes EEPROM
* Programmable serial USART
* 8 Channel, 10 bit ADC
* One 16-bit timer/counter with separate prescaler, compare mode and capture mode.
* Available in 40 pin DIP, 44-pad QFN/MLF and 44-lead QTFP
* Two 8-bit timers/counters with separate prescalers and compare modes
* 32 programmable I/O lines
* In system programming by on-chip boot program
* Master/slave SPI serial interface
* 4 PWM channels
* Programmable watch dog timer with separate on-chip oscillator
* Special Microcontroller Features:
* External and internal interrupt sources
* Six sleep modes: Idle, ADC noise reduction, power-save, power-down, standby and extended standby.
* Power on reset and programmable brown-out detection.
* Internal calibrated RC oscillator

## LCD 16×2 Pin:

![image](https://user-images.githubusercontent.com/94309132/145758679-9869a9e7-e105-465a-9ea4-d901f346c160.png)

![image](https://user-images.githubusercontent.com/94309132/145758772-bbae2d4b-3797-4edb-a42e-a77cd86c47b1.png)




## LCD 16×2 Pin Description: 
The 16×2 LCD pinout is shown below.

###  Pin1 (Ground/Source Pin):
This is a GND pin of display, used to connect the GND terminal of the microcontroller unit or power source.
###  Pin2 (VCC/Source Pin): 
This is the voltage supply pin of the display, used to connect the supply pin of the power source.
###  Pin3 (V0/VEE/Control Pin):
This pin regulates the difference of the display, used to connect a changeable POT that can supply 0 to 5V.
###  Pin4 (Register Select/Control Pin): 
This pin toggles among command or data register, used to connect a microcontroller unit pin and obtains either 0 or 1(0 = data mode, and 1 = command mode).
###  Pin5 (Read/Write/Control Pin): 
This pin toggles the display among the read or writes operation, and it is connected to a microcontroller unit pin to get either 0 or 1 (0 = Write Operation, and 1 = Read Operation).
###  Pin 6 (Enable/Control Pin): 
This pin should be held high to execute Read/Write process, and it is connected to the microcontroller unit & constantly held high.
### Pins 7-14 (Data Pins):
These pins are used to send data to the display. These pins are connected in two-wire modes like 4-wire mode and 8-wire mode. In 4-wire mode, only four pins are connected to the microcontroller unit like 0 to 3, whereas in 8-wire mode, 8-pins are connected to microcontroller unit like 0 to 7.
###  Pin15 (+ve pin of the LED): 
This pin is connected to +5V
### Pin 16 (-ve pin of the LED): 
This pin is connected to GND



## Features of LCD16x2
The features of this LCD mainly include the following.

* The operating voltage of this LCD is 4.7V-5.3V
* It includes two rows where each row can produce 16-characters.
* The utilization of current is 1mA with no backlight
* Every character can be built with a 5×8 pixel box
* The alphanumeric LCDs alphabets & numbers
* Is display can work on two modes like 4-bit & 8-bit
* These are obtainable in Blue & Green Backlight
* It displays a few custom generated characters
